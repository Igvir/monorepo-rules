# Desarrollo de aplicaciones con arquitectura monorepositorio

Dentro de los conceptos relacionado al desarrollo *Agile*, hay varios elementos necesarios para lograr que no solo el diseño sino también la construcción responda a la necesidad de comunicación continua, estandarización y eficiencia. Uno de estos elementos es la gestión del código fuente que, sin ser el único factor involucrado, puede ser el punto de partida para los beneficios o los problemas de la solución.
Cuando nos involucramos en el delivery de soluciones con capacidad de escalar a un nivel empresarial, hay que tener en consideración estrategias de gestión de todos los recursos y muy especialmente de la gestión del código ya que es muy fácil dejarse llevar por la tentación de construir y postergar la definición de lineamientos o incluso se pierden de vista y al no aplicarse desde el inicio, generan un efecto de bola de nieve y se vuelve un tema más grande a medida que el proyecto avanza.
Tener un lineamiento inicial, fomentar una disciplina interna de uso de estas línea de instrucción y hacerlas propias de la construcción, facilita que el proceso se vuelva natural al punto que todos puedan "saltar" al proceso de construcción con una estrategia exitosa.

## Resumen

## Conceptos

### 1. ¿Qué es un monorepo?
Mono-repositorios, *Mono-repository* o simplemente *monorepo* como se les conoce en inglés es una estrategia de gestión del control de versiones de código fuente que consiste en agrupar en un único repositorio de código todos los componentes de la solución.

### 2. Estructuras de repositorio de código fuente
---
|       Estructura       |                    Implementación             |                              Implementada  por                          |
| :--------------------: | :--------------------------------------------------------------------: | :--------------------------------------------------------------------: |
| Multiples repositorios |   Un repositorio para cada componente o librería de código   |   Amazon, Netflix , Lyft                             |
|    Mono-repositorio    | Un repositorio para todos los componentes o incluso para toda la compañía | Google, Facebook, Microsoft, Uber, Twitter, React, Angular, Babel, Kubernetes |
| Híbrido: Multirepos manejados como  monorepositorio | Los cambios se realizan en multiples repositorios pero se gestionan como un monorepo  | Android, chrome |
| Híbrido: Monorepo manejado como multi | Las cambios se realizan en un monorepo pero luego se dividen en multiples repositorios de solo lectura para construcción o distribución | Symfony, Shopsys | 
---
*Tabla 1: Estructuras de repositorio de código fuente*

### 3. ¿Qué es un repositorio?



### CI/CD


## Referencias
* [Monorepo](https://en.wikipedia.org/wiki/Monorepo)
* [Monorepo’s for Microservices Architecture](https://dzone.com/articles/monorepos-for-microservices-commerce-architecture)
* [Lerna.js](https://lerna.js.org/)
* [How to structure microservices in your repository](https://softwareengineering.stackexchange.com/questions/386066/how-to-structure-microservices-in-your-repository)
* [From Monolith to Monorepo](https://medium.com/@brockreece/from-monolith-to-monorepo-19d78ffe9175)
* GBM Release Management para Software, IN-COT-005, Marzo 2022
* The Issue of Monorepo and Polyrepo In Large
Enterprises, Nicolas Brousse, 2019 
* [Monorepo, Manyrepo, Metarepo. 2017](https://notes.burke.libbey.me/metarepo/)
* [Automatically detect changes and initiate different CodePipeline pipelines for a monorepo in CodeCommit](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/automatically-detect-changes-and-initiate-different-codepipeline-pipelines-for-a-monorepo-in-codecommit.html)