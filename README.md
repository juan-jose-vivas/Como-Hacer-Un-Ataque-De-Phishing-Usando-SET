# Como-Hacer-Un-Ataque-De-Phishing-Usando-SET
Bien, vamos a explicar como se hace un ataque de phishing usando un correo electrónico fraudulento
Y ¿Qué es esto del phishing?, pues es una técnica de ingeniería social mediante la cual hacemos creer a la víctima mediante un correo o una web manipulada que somos quien realmente no somos con el objeto habitual de que nos den ellos mismos sus contraseñas para acceder a sus cuentas bancarias, o bien sus contraseñas para acceder a sus correos electrónicos y redes sociales y así poder victimizarlo y manipularlo posteriormente con otros fines.
El planteamiento del ataque será el siguiente.
    1. selecciono la víctima de la cual conozco su correo electrónico, y a la cual me dirigiré vía email con la intención de que pique el anzuelo.
    2. enviaré un email fraudulento al correo de la víctima. Este será el email de ataque.
    3. clonaré la web legítima de www.gmail.com de tal forma que, cuando la víctima abra el correo fraudulento que le he enviado desde el email de ataque, ella verá que es gmail quien le escribe y le pide pinchar en un enlace.
    4. con la excusa de un nuevo servicio o la prevención de un fraude, se le pide a la víctima que entre en su gestor de correo de email (la web clonada de gmail.com) para hacer una pequeña comprobación.
    5. En la web clonada la víctima introducirá su usuario y contraseña que nos aparecerá en la consola de nuestra máquina de ataque linux parrot y así ya habremos obtenido lo que queremos de la víctima,
    6. Lo que suceda posteriormente es indiferente. Se le dirige a la web legítima, se le muestra una página de error, etc, pero que no sospeche.
Este es un ataque de ingeniería social. Si sustituyen las palabras "ingeniería social" por "engañar a la víctima como a un chino" tendrán un significado mas preciso de lo que queremos decir.
Como habéis visto necesitamos varias cosas: generar el email fraudulento y clonar la web anzuelo entre otras cosas. Esto no es fácil hacerlo, pero en nuestro laboratorio de hacking, y en concreto en la máquina linux parrot, aunque también está en la máquina kali, disponemos de una herramienta que se encarga de automatizar este proceso.
