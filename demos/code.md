<!SLIDE>
# Add code examples
## Built in syntax highlighting

    @@@ Ruby
    ['one', 'two', 'three'].collect do |item|
      puts item.upcase
    end

Can highlight lines of text too:

    @@@ Puppet
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # notice that this must be a *string* now
        content => "this is such an exciting file!\n",
      }
    }
    include foo
