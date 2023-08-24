Informe de Testeo- Servicio Web ASP.NET\_LABORATORION°2

EJERCICIO1.asmx

Descripción:

El siguiente código representa un ejemplo de un servicio web ASP.NET escrito en C#. El servicio web contiene un método llamado HelloWorld que devuelve un saludo en forma de cadena de texto. El propósito de este informe es evaluar la funcionalidad y el comportamiento del servicio web.

Codigo del Servicio Web:




Entorno de Prueba:


Visual Studio 2022

Sistema Operativo: Windows 11


Pasos de Ejecución:


Se creó un nuevo proyecto de Servicio Web ASP.NET en Visual Studio.

Se copió y pegó el código proporcionado en el archivo del servicio web.

Se realizó una compilación exitosa del proyecto en Visual Studio.

Se inició el servicio web haciendo clic en "Iniciar con navegador" desde Visual Studio.

Se accedió automáticamente a la URL del servicio web local en un navegador.

Se verificó que el servicio no respondió con la cadena "Hola a todos" debido a la ausencia del return.


Resultados:


El proyecto del servicio web se creó y compiló sin errores en Visual Studio.

Al hacer clic en "Iniciar con navegador", el servicio web se ejecutó en el navegador web predeterminado.

Se accedió correctamente a la página principal del servicio web desde el navegador.

El servicio no respondió según lo esperado debido a la falta del return en el método HelloWorld.


Conclusión:


A pesar de que el servicio web se ejecutó en el navegador desde Visual Studio utilizando la opción "Iniciar con navegador", no se obtuvo el resultado esperado debido a la falta del return en el método HelloWorld. El servicio no proporcionó la funcionalidad esperada durante esta prueba.


Recomendaciones:


Se recomienda corregir el código del método HelloWorld agregando el return necesario para que devuelva la cadena "Hola a todos".


EJERCICIO2.asmx


Descripción:

Este informe describe las pruebas realizadas para ejecutar un servicio web ASP.NET escrito en VB.NET en el entorno de desarrollo de Visual Studio. El servicio web, llamado WebService2, contiene un método GetCotizacion que toma una moneda como entrada y devuelve una cotización en forma de cadena de texto. El propósito de este informe es evaluar la funcionalidad y el comportamiento del servicio web al llamar el método GetCotizacion desde un cliente.


Codigo del Servicio Web:


Entorno de Prueba:


Visual Studio 2022

Sistema Operativo: Windows 11




Pasos de Ejecución:


Creación de un nuevo proyecto de Servicio Web ASP.NET en Visual Studio.

Copiado y pegado del código incorrecto proporcionado en el archivo del servicio web.

Compilación exitosa del proyecto en Visual Studio.

Inicio del servicio web haciendo clic en "Iniciar con navegador" desde Visual Studio.

Acceso automático a la URL del servicio web local en un navegador.

Intento de prueba del servicio web ingresando diferentes monedas en la URL.


Resultados:


El proyecto del servicio web se creó y compiló sin errores en Visual Studio.

Al hacer clic en "Iniciar con navegador", el servicio web se ejecutó en el navegador web predeterminado.

Se accedió correctamente a la página principal del servicio web desde el navegador.

Sin embargo, se identificó un error en el código, ya que falta la palabra clave "Case" antes del caso "RE" en la sección de casos del Select Case, lo que puede causar un comportamiento inesperado del servicio web.


Conclusión:


El servicio web se ejecutó desde Visual Studio, pero se encontró un error en el código en la sección de casos del Select Case. El caso "RE" no tiene la palabra clave "Case" antes de él, lo que puede resultar en un comportamiento incorrecto del servicio web.


Recomendaciones:


Se recomienda corregir el error en el código agregando la palabra clave "Case" antes del caso "RE" en la sección de casos del Select Case.


























































EJERCICIO3.asmx


Descripción:

Este informe detalla las pruebas realizadas para ejecutar un servicio web ASP.NET escrito en VB.NET en el entorno de desarrollo de Visual Studio. El servicio web contiene dos métodos, FahrenheitToCelsius y CelsiusToFahrenheit.


Codigo del Servicio Web:


Pasos de Ejecución:


Creación de un nuevo proyecto de Servicio Web ASP.NET en Visual Studio.

Copiado y pegado del código incorrecto proporcionado en el archivo del servicio web.

Compilación exitosa del proyecto en Visual Studio.

Inicio del servicio web haciendo clic en "Iniciar con navegador" desde Visual Studio.

Acceso automático a la URL del servicio web local en un navegador.

Intento de prueba de los métodos del servicio web ingresando valores en la URL.


Resultados:


El proyecto del servicio web se creó y compiló sin errores en Visual Studio.

Al hacer clic en "Iniciar con navegador", el servicio web se ejecutó en el navegador web predeterminado.

Se accedió correctamente a la página principal del servicio web desde el navegador.

Se identificó un error en uno de los métodos del servicio web. Falta la palabra clave "Return" antes de la expresión matemática en el método FahrenheitToCelsius, lo que provoca que el método no devuelva los resultados esperados.


Conclusión:


El servicio web se ejecutó desde Visual Studio, pero se encontró un error en el código en el método FahrenheitToCelsius. Falta la palabra clave "Return" antes de la expresión matemática, lo que provoca que el método no devuelva el resultado esperado.


Recomendaciones:


Se recomienda corregir el error en el código agregando la palabra clave "Return" antes de la expresión matemática en el método FahrenheitToCelsius.














EJERCICIO4.asmx


Descripción:

El siguiente código representa un ejemplo de un servicio web ASP.NET escrito en C#. El servicio web contiene un método llamado dameCita que devuelve un string random en cada llamada que se le haga. El propósito de este informe es evaluar la funcionalidad y el comportamiento del servicio web.

Codigo del Servicio Web:


Entorno de Prueba:


Visual Studio 2022

Sistema Operativo: Windows 11








Pasos de Ejecución:


Se creó un nuevo proyecto de Servicio Web ASP.NET en Visual Studio.

Se copió y pegó el código proporcionado en el archivo del servicio web.

Se realizó una compilación exitosa del proyecto en Visual Studio.

Se inició el servicio web haciendo clic en "Iniciar con navegador" desde Visual Studio.

Se accedió automáticamente a la URL del servicio web local en un navegador.

Se verificó que el servicio no respondió correctamente a la compilación del método dameCita, debido a que este método no presenta las llaves que marcan su bloque de código.


Resultados:


El proyecto del servicio web se creó y compiló sin errores en Visual Studio.

Al hacer clic en "Iniciar con navegador", el servicio web se ejecutó en el navegador web predeterminado.

Se accedió correctamente a la página principal del servicio web desde el navegador.

Se verificó que el servicio no respondió debido a la falta del delimitador del bloque de código del método dameCita.


Conclusión:


A pesar de que el servicio web se ejecutó en el navegador desde Visual Studio utilizando la opción "Iniciar con navegador", no se obtuvo el resultado esperado debido a la falta del bloque de código para el método dameCita, así que el código no pasaría a producción.


Recomendaciones:


Se recomienda añadir las llaves que delimitan el código para el método dameCita, al inicio en la línea 29, y cerrandolo en la línea 38.
