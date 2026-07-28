# Requerimientos No Funcionales

## Objetivo

Definir las características de calidad que deberá cumplir el sistema Hummi para garantizar un funcionamiento eficiente, seguro, mantenible y escalable.

## Requerimientos

| ID | Categoría | Descripción |
|----|-----------|-------------|
| RNF-01 | Arquitectura | El sistema deberá implementar una arquitectura desacoplada basada en una aplicación móvil (Flutter) y un backend independiente mediante una API REST (Spring Boot). |
| RNF-02 | Rendimiento | El sistema deberá ofrecer tiempos de respuesta adecuados que permitan una experiencia fluida durante la interacción del usuario. |
| RNF-03 | Persistencia | La información de usuarios, alimentos, registros nutricionales e historial deberá almacenarse de manera consistente en una base de datos relacional. |
| RNF-04 | Escalabilidad | La arquitectura deberá permitir incorporar nuevas funcionalidades sin afectar significativamente las existentes. |
| RNF-05 | Integración | El sistema deberá permitir la integración con servicios externos mediante APIs, como almacenamiento de imágenes o servicios de inteligencia artificial. |
| RNF-06 | Usabilidad | La aplicación deberá ofrecer una interfaz intuitiva y orientada a dispositivos móviles, reduciendo al mínimo las acciones necesarias para registrar información. |
| RNF-07 | Mantenibilidad | El backend deberá seguir una arquitectura por capas y buenas prácticas de desarrollo que faciliten el mantenimiento del código. |
| RNF-08 | Seguridad | Las contraseñas deberán almacenarse utilizando algoritmos de cifrado seguros y el acceso a la información personal deberá requerir autenticación. |
| RNF-09 | Compatibilidad | La aplicación deberá funcionar correctamente en dispositivos Android con una versión mínima definida (Android 10 o superior). |
| RNF-10 | Disponibilidad | La información del usuario deberá mantenerse disponible entre sesiones y recuperarse correctamente al iniciar nuevamente la aplicación. |
| RNF-11 | Accesibilidad | La interfaz deberá utilizar tamaños de fuente, colores y contrastes adecuados para facilitar la lectura y navegación. |
| RNF-12 | Portabilidad | La arquitectura deberá facilitar una futura compatibilidad con dispositivos iOS sin modificar la lógica de negocio. |