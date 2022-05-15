# BANK KATA

## Instrucciones
Escriba una clase llamada AccountService que implemente la siguiente interfaz pública:
```java
public interface AccountService
{   
    void deposit(int amount);
    void withdraw(int amount);
    void printStatement();
}
```

## Reglas
No puede cambiar la interfaz pública de esta clase.

## Comportamiento Deseado
Aquí está la especificación para una prueba de aceptación que expresa el comportamiento deseado para este:
* Dado que un cliente hace un depósito de 1000 el 10-01-2012
* Y un depósito de 2000 el 13-01-2012
* Y un retiro de 500 el 14-01-2012


* Cuando imprima su extracto bancario


* Entonces vería:
```
Date       || Amount || Balance
14/01/2012 || -500   || 2500
13/01/2012 || 2000   || 3000
10/01/2012 || 1000   || 1000
```

## Notas
- Usamos ints para las cantidades de dinero para mantener los auxiliares lo más simple posible. En un sistema real, siempre usaríamos un tipo de datos con precisión arbitraria garantizada, pero hacerlo aquí distraería la atención del objetivo principal del ejercicio.
- No se preocupe por el espaciado y la sangría en la salida de la declaración. (Si lo desea, puede indicar a su prueba de aceptación que ignore los espacios en blanco).
- Utilice la prueba de aceptación para guiar su progreso hacia la solución. Sandro hace esto haciendo que todos los métodos no implementados arrojen una excepción, de modo que pueda ver de inmediato lo que queda por implementar cuando ejecuta la prueba de aceptación.
- En caso de duda, ¡busque la solución más sencilla!

https://katalyst.codurance.com/bank

----
# BANK KATA (English Version)
## Instructions

  Write a class named Account that implements the following public interface:
```java
public interface AccountService
    {
      void deposit(int amount);
      void withdraw(int amount);
      void printStatement();
    }
```

## Rules
You cannot change the public interface of this class.

## Desired Behaviour
Here's the specification for an acceptance test that expresses the desired behaviour for this:

* Given a client makes a deposit of 1000 on 10-01-2012
* And a deposit of 2000 on 13-01-2012
* And a withdrawal of 500 on 14-01-2012



* When they print their bank statement


* Then they would see:
```
Date       || Amount || Balance
14/01/2012 || -500   || 2500
13/01/2012 || 2000   || 3000
10/01/2012 || 1000   || 1000
```

## Notes
- We're using ints for the money amounts to keep the auxiliaries as simple as possible. In a real system, we would always use a datatype with guaranteed arbitrary precision, but doing so here would distract from the main purpose of the exercise.
- Don't worry about spacing and indentation in the statement output. (You could instruct your acceptance test to ignore whitespace if you wanted to.)
- Use the acceptance test to guide your progress towards the solution. Sandro does this by making all unimplemented methods throw an exception, so that he can immediately see what remains to be implemented when he runs the acceptance test.
- When in doubt, go for the simplest solution!


https://katalyst.codurance.com/bank
