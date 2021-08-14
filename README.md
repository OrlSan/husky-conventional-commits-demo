# Husky Conventional Commits Demo

Proyecto de ejemplo de un repositorio de código utilizando Husky y Standard Version para
generar automáticamente un CHANGELOG.md basado en los mensajes de las confirmaciones (commits)
de git.

[Husky](https://www.npmjs.com/package/husky) es una herramienta para instalar y ejecutar _hooks_ 
en un repositorio git. [Standard Version](https://www.npmjs.com/package/standard-version) es 
una utilidad compatible con [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), 
una especificación que estandariza los mensajes de confirmación de los commits en un repositorio 
git para hacerlos legibles por procesos automatizados para lograr, por ejemplo, 
la generación de un archivo CHANGELOG, sin intervención de los desarrolladores.

Los detalles de la implementación y configuración de estas herramientas en tu propio repositorio 
pueden ser encontradas en el Post 
["Genera tu Changelog con Conventional Commits"](https://orlsan.com/post/changelog-conventional-commits/).

El uso de estas herramientas no implica que tu proyecto debe estar basado en Javascript o Node.js: 
Puede ser utilizado por cualquier repositorio, escrito en cualquier lenguaje de programación. Husky 
y Standard Version son herramientas de desarrollo y por lo tanto el código real de tu proyecto 
no tendrá relación con dichas herramientas.

## TODO list

- [ ] Add an english version README.md file
- [ ] Create an english version for the original blog post https://orlsan.com/post/changelog-conventional-commits/