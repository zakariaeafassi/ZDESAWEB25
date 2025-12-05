# detalle-funcional

 La pagina web debe contener un formulario de inicio secion o creacion de cuenta de cliente, con los siguientes datos: **nombre completo** del cliente, **documentacion** (DNI/NIE/pasaporte), y **correo electronico** ; esto sirverá para facilitar la gestion de citas, ya que el cliente no tendrá que meter sus datos cada vez que genera una cita, tambien ayudará al taller a identificar a sus clientes, y por ultimo, se podrá comunicar con el cliente por su correo electronico.

 Para crear citas, la pagina ofrece un calendario en el cual señala los dias y las horas libres en las cuales los clientes pueden pedir citas, en caso de que el cliente le da igual la hora y el dia, este podrá pulsar un boton de generar cita automatica, eligiendo un dia aleatorio con un plazo maximo de dos semanas. Una vez creada la cita como un borrador (tanto manual como automatica), se debría enviar un mensaje en el correo electronico del cliente para avisarle que se creo una cita con la fecha y hora indicada, _en el caso que no fuera él o que ya no la necesite podrá indicarlo y eliminarla_, en el caso contrario le da a confirmar y esta se manda a la base de datos del taller.

 Los usarios de esta pagina podría ser cualquier persona con un vehiculo con necesidad de arreglar una averia o de modificar su apriencia tanto interios (tapiceria, limpieza, instalacion de luces/ pantalla inteligente, ...) o exterior (pintura/aplicacion de vinilo, limpieza, instalacion o cambio de componentes exteriores de coche, ...).

Para usar la aplicacion se debe iniciar secion o crear cuenta. **Si vas a iniciar sesion** hace falta poner tu correo y la contraseña, y **si vas a crearla desde 0** debes poner tu nombre completo, dni, correo electronico no usado anteriormente en esta aplicacion, y crear una contraseña y confirmarla en el correo. Una vez iniciada sesion, el cliente debe eligir entre reparacion o modificacion, para que el taller puede identificar la necesidad deñ cliente, una vez eligida se rellena un formulario que pide obligatoriamente: la matricula del coche, y la fecha, en caso de no haberla eligido hay que señalar un checkbox aclarando que no le importa la fecha de este servicio para evitar el hecho de olvidar ponerla.

## ¿Que encontraré en la pagina de reparacio y modificacion?

Dentro de reparacion encontraras algunas averias que una persona puede identificar sin necesidad de conocimiento mecanico como:
 - el coche no arranca.
 - problemas en las ruedas.
 - problemas de carroceria (las puertas/maletero/capo no abren, cristales rotos, ventanas no bajan/suben, ...).
 - el coche echa humo.
 - problemas de freno.
 - ruidos raros al acelerar.
 - ruido anormal al arrancar.
 - otros ruidos.

Dentro de modificaciones habra lo siguiente:

+ modificacion externa:
  - pintura.
  - vinilo.
  - choques.
  - rayones.
  - wide body.
  - cambio y montaje de componentes.
  - limpieza
  
+ modificacion interna:
  - montaje de luces.
  - arreglo de tapiceria.
  - cambio de componentes.
  - montaje de pantalla tactil.
  
