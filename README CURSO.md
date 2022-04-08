Week #1 - Martes
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

WEEK #1 MIERCOLES
traducir tu fecha de nacimiento a binario
Fecha de nacimiento: 2002
2002 / 2 = 1001 -> 0
1001/2 = 500 -> 1
500/2 = 250 ->0
250/2=125 -> 0
125/2 = 62 -> 1
62/1 = 31 -> 0
31/2= 15 -> 1
15/2 = 7 -> 1
7/2 = 3 ->1
3/2 = 1 -> 1
=1
=11111010010

WEEK #1 JUEVES
2. Bad code
var cond = falso;

if ((cond = true)) {
  console.log('La variable cond es verdadera');
} else {
  console.log('La variable cond es false');
}

Good code
var cond = falso;

if (cond == true) {
  console.log('La variable cond es verdadera');
} else {
  console.log('La variable cond es false');
}

BAD CODE
var n = 100;

si (n == 100) {
  console.log('¡Este es un número especial!') ;
}
if (n < 1000) {
  console.log('');
} else {
  console.log('Solo un número normal');
}
if (n % 10 == 0) {
  console.log('Este número es múltiplo de 10');
}
GOOD CODE 
var n = 100;

if (n == 100) {
  console.log('¡Este es un número especial!') ;
}
if (n < 1000 && n % 10 == 0) {
  console.log('Este es un numero especial');
} 
  else {
  console.log('Solo un número normal');
}

