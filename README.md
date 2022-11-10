# CodeIgniter-Exceptions-FrameworkException
CodeIgniter\Exceptions\FrameworkException The framework needs the following extension(s) installed and loaded: intl. SYSTEMPATH\CodeIgniter.php at line 224
Al momento de iniciarme en el mundo de CodeIgniter; pues soy novato en esto de la programación; cuando decidí tomar un toturial en youtube aunque muy bueno, 
faltan muchos aspectos por aclarar; pero bién lo cierto es que realizo los pasos correspondientes de descargarlo en la maquina local xampp; 
pero al ejecutarlo en el mencionado servidor me aparece el bendito error : 
(CodeIgniter\Exceptions\FrameworkException The framework needs the following extension(s) installed and loaded: intl. SYSTEMPATH\CodeIgniter.php at line 224; 
esto aparece en el navegador); 
seguidamente me dispongo a investigar cuanto tutorial que aparece en la web y llegué hasta el punto de desistir en esto; pero en última instancia aparece 
una pregunta casi identica en SatackOverFlow en dónde el usuario 16302651 hace un aporte sencillo y excelente; lo cual estoy muy agradecido pués solucionó 
ese bendito error; lo quice recrear de la siguiente manera:

Primero, Me dirijo a la carpeta de xampp que se encuentra el disco c:\ de mi computador.
Seguidamente, En la carpeta php.ini le doy click derecho y lo edito con NotePad ++
Dentro del archivo me dirijo a la línea 923 del archivo y se encuentra con un punto y coma (;) ;extension=intl (Esta aparece en el error en el navegador)
posteriormente, le quito el punto y coma de la parte inicial de línea y listo eso es todo.
Un gran saludo y mis respetos al usuario 16302651.
