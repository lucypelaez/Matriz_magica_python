### 🔢 Matriz Mágica — Ejercicio de Funciones en Python
#### 📋 Descripción
Ejercicio de nivel principiante para practicar la descomposición de problemas en funciones usando Python.   
El objetivo es construir un programa que determine si una matriz cuadrada N×N es mágica — es decir, si la suma de todas sus filas, columnas y diagonales es siempre el mismo valor (llamado constante mágica).

    Ejemplo de matriz mágica 3×3 — constante mágica = 15 (N = 3)

                                    2  7  6    
                                    9  5  1    
                                    4  3  8

     Filas:      2+7+6=15 | 9+5+1=15 | 4+3+8=15  ✅    
     Columnas:   2+9+4=15 | 7+5+3=15 | 6+1+8=15  ✅    
     Diagonales:       2+5+8=15 | 6+5+4=15       ✅    

#### 🎯 Objetivo del ejercicio
Aprender a resolver un problema complejo dividiéndolo en funciones pequeñas que trabajan juntas, en lugar de intentar resolverlo todo de una vez.

#### 🧠 Conceptos que aprenderás

* Definir y llamar funciones con parámetros y valor de retorno
* Trabajar con listas de listas (matrices) en Python
* Acceder a elementos con índices dobles matriz[i][j]
* Usar bucles for con range() para recorrer estructuras
* Acumular valores con +=
* Combinar funciones — usar unas dentro de otras
* Validar datos de entrada antes de procesarlos
* Usar if __name__ == "__main__" para organizar el código
* Probar cada función de forma independiente

#### ⚙️ Funciones implementadas
Función|Descripción|
|---|---|
es_cuadrada(matriz)|Comprueba si la matriz tiene el mismo número de filas y columnas|
calcular_suma_magica(matriz)|Calcula la constante mágica usando la fórmula N * (N² + 1) / 2|
sumar_fila(matriz, fila)|Devuelve la suma de una fila concreta|
sumar_columna(matriz, columna)|Devuelve la suma de una columna concreta|
sumar_diagonal_principal(matriz)|Devuelve la suma de la diagonal ↘
sumar_diagonal_secundaria(matriz)|Devuelve la suma de la diagonal ↙
es_magica(matriz)Función principal| Devuelve True o False
ejecutar_pruebas()|Lanza los casos de prueba