# readme
Se compila o interpreta Java, o ambas cosas?
Ambas cosas. El código Java, una vez compilado, puede llevarse sin modificación alguna sobre cualquier sistema operativo (Windows, Linux, Mac OS, etc)  un código fuente de Java se compila en 'bytecode' luego es 'Compilado' nuevamente por JIT en 'código de máquina'. Es decir, el código fuente se compila primero en un código de bytes independiente de la plataforma y luego se vuelve a compilar en un código específico de la máquina. en resumen se compila primero en alguna forma de código de máquina virtual, que luego se interpreta o compila en tiempo de ejecución en código nativo

Pseudocodigo
START
PRINT("CONVERTIR DOLARES A BITCOINS");
PRINT("INGRESE LA CANTIDAD DE DOLARES QUE DESEA CONVERTIR A BITCOINS");
dls <-- GET;
BTC <-- dls*0.000022;
PRINT("EL VALOR DE DOLARES A BITCOINS ES: " + BTC);
END

