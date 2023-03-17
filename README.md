# Tienda web de muebles estilo industrial diseñado por MidJourney:writing_hand:

Este proyecto fue creado basándose en un diseño creado por MidJourney.

## Entorno

Asegurarse de tener instalado `git` . Esto se puede revisar muy fácilmente a través del comando `git --version` . En caso de no estar instalado, se puede hacer a través de los siguientes paso

- En linux, a travez del comando `sudo apt install git`.
- En Windows, a travez de la pagina oficial https://git-scm.com/

Procurar tener actualizado `node.js` a la versión `lts`. Si desea asegurarse, puede ejecutar el comando `npm doctor` que le indicara si cumple con los requisitos. Si el comando no se encuentra o `node.js` esta desactualizado, puede instalar `node.js --lts` mediante alguno de los siguientes pasos

- En windows, desde la [pagina oficial](https://nodejs.org/en/), descargando y ejecutando la versión `lts`.

- En Linux, a través de [nvm](https://github.com/nvm-sh/nvm)

  - Abrir una terminal y ejecutar el comando que se encuentra en la sección [Install & update script](https://github.com/nvm-sh/nvm#install--update-script)

  - Cerrar la terminal y abrir otra para ejecutar el siguiente comando para verificar la correcta instalación`nvm --version` . Una vez observada la versión, ejecutar el siguiente comando para instalar Node.js

    ```bash
    nvm install --lts
    ```

## Instalación y ejecución

- 🛠Para instalar las dependencias ejecutar el siguiente comando `npm install`
- ⚒Para ejecutar el modo playground o repl, ejecutar el siguiente comando `npm run dev`
- 🔧Para traducir el código en `/src` a `JavaScript` , usar el comando `npm run build`
- 🔑Para ejecutar el código con `Node.js`, usar el comando `npm run start`

## Tecnologías usadas

- [TypeScript](https://www.typescriptlang.org/)
- [NextJS](https://nextjs.org/)
- [Jest](https://jestjs.io/)
- [Material UI](https://mui.com/core/)
- [MidJourney](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F)

