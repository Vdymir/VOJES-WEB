## VOJES_WEB

#### - Como será la estructura del proyecto 

------------
La idea es aprender a estructurar un proyecto con el fin de expandirlo lo mas grande posible :

```structure
src/
|--- components/
|---|--- Avatar/
|---|---|-- Avatar.tsx
|---|---|-- Avatar.test.ts
|---|---|-- index.ts
|---|--- Button/
|---|---|-- Button.tsx
|---|---|-- Button.test.ts
|---|---|-- index.ts
|---|--- TextField/
|---|---|-- TextField.tsx
|---|---|-- TextField.test.ts
|---|---|-- index.ts
|-- contexts/
|---|-- UserContext/
|---|---|-- UserContext.ts
|---|---|-- index.ts
|-- hooks/
|---|-- useMediaQuery/
|---|---|-- useMediaQuery.ts
|---|---|-- index.ts
|-- pages/
|---|-- UserProfile/
|---|---|-- components/
|---|---|---|-- SomeUserProfileComponent/
|---|---|---|---|-- SomeUserProfileComponent.tsx
|---|---|---|---|-- SomeUserProfileComponent.test.ts
|---|---|-- UserProfile.tsx
|---|---|-- UserProfile.test.ts
|---|-- index.ts
|-- routes/
|---|-- routes.tsx
|---|-- routes.test.ts
|---|-- index.ts
|-- utils/
|---|-- some-util/
|---|---|-- index.ts
|---|---|-- someUtil.ts
|---|---|-- someUtil.test.ts
|-- services/
|---|-- some-service/
|---|---|-- index.ts/
|---|---|-- someService.ts/
|---|---|-- index.test.ts
|-- App.tsx
|-- index.tsx
```

#### - FORMATOS PARA COMMIT 

A la hora de realizar algun commit estaremos usando el formato de los [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/ "Conventional Commits")

##### -TIPOS:
------------
1. build : Cambios que afectan el sistema de compilación o dependencias externas (ámbitos de ejemplo: gulp, broccoli, npm)
2. ci : Cambios en nuestros archivos y scripts de configuración de CI (ámbitos de ejemplo: Travis, Circle, BrowserStack, SauceLabs)
3. docs : Documentación solo cambios
4. feat : una nueva característica
5. fix : una corrección de errores
6. perf : un cambio de código que mejora el rendimiento
7. refactor : un cambio de código que no corrige un error ni agrega una característica
8. style : Cambios que no afectan el significado del código (espacios en blanco, formato, puntos y coma faltantes, etc.)
9. test : Adición de pruebas faltantes o corrección de pruebas existentes