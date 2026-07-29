# Casos de Uso

## Objetivo

Este documento describe las principales interacciones entre los actores y el sistema Hummi. Los casos de uso representan los procesos más importantes que deberá soportar la aplicación.

---

# Actores

- Usuario
- Entrenador / Nutricionista (Versión 3)

---

# CU-01 Registrar Usuario

## Actor

Usuario

## Descripción

Permite crear una nueva cuenta.

## Precondiciones

- El usuario no posee una cuenta registrada.

## Flujo principal

1. El usuario selecciona "Crear cuenta".
2. Ingresa sus datos.
3. El sistema valida la información.
4. El sistema crea la cuenta.
5. El sistema confirma el registro.

## Postcondiciones

El usuario queda registrado en el sistema.

---

# CU-02 Iniciar Sesión

## Actor

Usuario

## Descripción

Permite acceder a la aplicación.

## Flujo principal

1. El usuario ingresa correo y contraseña.
2. El sistema valida las credenciales.
3. Se inicia la sesión.

---

# CU-03 Registrar Comida

## Actor

Usuario

## Descripción

Registrar alimentos consumidos.

## Flujo principal

1. El usuario selecciona una comida.
2. Busca un alimento.
3. Indica la cantidad.
4. El sistema calcula las calorías.
5. El alimento se agrega al historial.
6. El Dashboard se actualiza.

---

# CU-04 Consultar Dashboard

## Actor

Usuario

## Descripción

Visualizar el resumen diario.

## Flujo principal

1. El usuario abre la aplicación.
2. El sistema obtiene los registros del día.
3. Se muestran:
    - calorías consumidas
    - calorías restantes
    - proteínas
    - carbohidratos
    - grasas

---

# CU-05 Registrar Agua

## Actor

Usuario

## Descripción

Registrar la cantidad de agua consumida.

---

# CU-06 Registrar Progreso Corporal

## Actor

Usuario

## Descripción

Registrar peso, medidas y fotografías.

---

# CU-07 Panel Administrativo (V3)

## Actor

Entrenador

## Descripción

Consultar el progreso nutricional y corporal de los participantes del Proyecto Colibrí.