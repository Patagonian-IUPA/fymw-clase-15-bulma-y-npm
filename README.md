# Clase 15 FyMW - proyecto bulma con NPM

En esta clase seguimos explorando [BULMA][bulma] (framework css) con en un
proyecto NPM.

## Clonar e Instalar el repo

El proyecto requiere tener instalado [Git][git], [NodeJS][nodejs] y
[Npm][npm]. Podemos comprobar la instalación de esas
herramientas con los comandos:

```bash
git --version
node --version # o tal vez nodejs --version
npm --version
```

Estando en la carpeta donde guardás tus proyectos habitualmente:

```bash
git clone https://github.com/Patagonian-IUPA/fymw-clase-15-bulma-y-npm.git
cd fymw-clase-15-bulma-y-npm
npm install
npm run dev
```

Los comandos arriba:

- clona el repositorio a tu local.
- `cd` para _pararse_ en la raíz del proyecto.
- instala las dependencias del proyecto (sass y bulma) usando `npm install`.
- corre el script `dev` usando `npm run dev` que inicia el compilador de sass en
  modo `watch`.

[bulma]: https://bulma.io/
[nodejs]: https://nodejs.org/
[npm]: https://www.npmjs.com/
[git]: https://git-scm.com/
