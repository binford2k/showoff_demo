<!SLIDE >
# Ejecutar código en vivo
## Añadir palabra clave `execute` a bloques de código

    @@@ Ruby execute
    ['uno', 'dos', 'tres'].collect do |item|
      puts item.upcase
    end

Puede resaltar líneas de texto también:

    @@@ Puppet execute
    class foo {
      file { '/tmp/foo':
    *    ensure  => file,
    *    mode    => '0644',  # Observe que esto debe ser una *cadena* ahora
        content => "Este es un archivo tan emocionante!\n",
      }
    }
    include foo
    
.break

    @@@ Shell execute
    cat /tmp/foo
