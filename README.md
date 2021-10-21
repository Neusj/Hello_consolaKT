# Hello_consolaKT

app de primer encuentro con Kotlin, donde se prueban algunos comandos en Kotlin REPL

#Ejemplo

Welcome to Kotlin version 1.4.31 (JRE 11.0.8+10-b944.6842174)
Type :help for help, :quit for quit

4+4
res0: kotlin.Int = 8

30/2
res1: kotlin.Int = 15

30/3.4
res2: kotlin.Double = 8.823529411764707

var constante: Int = 10

constante
res4: kotlin.Int = 10

val variable: Int = 10

variable
res6: kotlin.Int = 10

fun saludar(){
     print("Hola soy una funcion")
 }

saludar()
Hola soy una funcion

fun muestraMasDiez (numIn : Int ){
     print(numIn + 10)
 }

muestraMasDiez()
error: no value passed for parameter 'numIn'
muestraMasDiez()              

muestraMasDiez(3)
13

fun devuelveMasTres(numIn : Int) : Int{
     return numIn + 3
 }

4 + devuelveMasTres(13)
res14: kotlin.Int = 20
