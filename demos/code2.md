<!SLIDE >
# Executing Code Live
## Add `execute` keyword to code blocks

    @@@ Ruby execute
    ['one', 'two', 'three'].collect do |item|
      puts item.upcase
    end

.break

    @@@ Shell execute
    cowsay 'Showoff is rad!'

Can highlight lines of text too:

    @@@ Puppet execute
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # notice that this must be a *string* now
        content => "this is such an exciting file!\n",
      }
    }
    include foo
    
.break

    @@@ Shell execute
    cat /tmp/foo
