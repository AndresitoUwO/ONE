Algoritmo: Calcular_Salario_Semanal.
Entrada: Dos numeros a y b. 
   Pago_por_hora = a
   Horas_Laboradas = b

Restricciones: a y b no pueden ser Negativos 

Proceso:
1. Pedir(leer) a y b numericos
2.    ¿a y b > 0? SI, Continuar al paso 3, En caso de lo contrario regresar al paso 1
3.    Si b<=40, Ir a paso 4 y Terminar. De lo contrario ir a paso 5
4.    Mostrar a * b y Terminar

5.    Horas_Extra = b - 40
7.    Bono =  Horas_Extras * a * 1.5 
8.    Pago_semanal = 40 * a + Bono
9.    Mostrar Pago_Semanal y Terminar
Fin_del_Algoritmo
