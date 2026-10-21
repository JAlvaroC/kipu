# Kipu: gastos e ingresos

Anota un gasto en segundos y descubre en qué se va tu dinero, mientras aún puedes cambiarlo.

App de finanzas personales para Android, pensada para el Perú. Gratis y sin anuncios.

**Estado:** en prueba cerrada en Google Play. [Únete a la prueba o conoce más](https://juanalvaro.pages.dev/#apps)

## Qué hace

- Anota gastos e ingresos en segundos, también los que se repiten cada mes.
- Resume el mes: en qué se fue el dinero y cómo vas frente al mes anterior.
- Presupuestos con avisos antes de pasarte.
- Control de gastos deducibles para las 3 UIT adicionales.
- Tus datos viven en tu teléfono, con respaldo que puedes restaurar.

## Cómo está hecha

| | |
|---|---|
| App | React Native con Expo, TypeScript estricto |
| Datos | SQLite local con migraciones versionadas |
| Arquitectura | Monorepo con Clean Architecture: reglas de negocio separadas de la app y probadas |
| Calidad | Pruebas automáticas y revisión en cada cambio |

```
App (pantallas)  ->  Casos de uso  ->  Reglas de negocio
                          |
                     Base de datos local
```

## Sobre el código

El código es privado. Este repositorio presenta la app.

Hecha por [Juan Alvaro](https://juanalvaro.pages.dev). Si te sirve, puedes [apoyarla](https://juanalvaro.pages.dev/#apoyar).
