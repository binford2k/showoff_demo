<!SLIDE>
# Demos
## Einige nette Zeug Showoff kann tun

    @@@ Ruby
    ['eins', 'zwei', 'drei'].collect do |item|
      puts item.upcase
    end

Kann auch Textzeilen hervorheben:

    @@@ Puppet
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # Beachten Sie, dass dies ein * String * jetzt sein muss
        content => "Das ist so eine spannende Datei!\n",
      }
    }
    include foo
