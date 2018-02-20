<!SLIDE >
# Code ausführen Live
## Add `execute` Schlüsselwort zu Codeblöcken

    @@@ Ruby execute
    ['eins', 'zwei', 'drei'].collect do |item|
      puts item.upcase
    end

Kann auch Textzeilen hervorheben:

    @@@ Puppet execute
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # Beachten Sie, dass dies ein * String * jetzt sein muss
        content => "Das ist so eine spannende Datei!\n",
      }
    }
    include foo
    
.break

    @@@ Shell execute
    cat /tmp/foo
