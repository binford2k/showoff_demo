<!SLIDE>
# Añadir ejemplos de código
## Construido en el resaltado de sintaxis

    @@@ Ruby
    ['uno', 'dos', 'tres'].collect do |item|
      puts item.upcase
    end

Puede resaltar líneas de texto también:

    @@@ Puppet
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # Observe que esto debe ser una *cadena* ahora
        content => "Este es un archivo tan emocionante!\n",
      }
    }
    include foo
