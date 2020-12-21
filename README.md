# Netlify Lambda Local Server

Npm package done to be able to run locally Netlify lambda functions using directly Typescript.
It allows JS files as well.

## Set up

Before using this package is needed to have ts-node installed on your machine.

## Install it globaly

As this package isn't uploaded to npm yet, you need to:
- Clone the repository
- From the repositoy folder run: `npm install -g .`

## Use it

When running the local server, it expect your functions path to be: `src/<function-folder>/<function.ts|js>`. Being the name of the folder function and the functions itself the same one.

- From the root folder of any proyect using netlify lambda functions run: `lambda-server`
