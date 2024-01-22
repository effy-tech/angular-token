# Warning

This repository is a fork from https://github.com/neroniaky/angular-token which seems to not be maintained anymore (last official package support Angular 7 while Angular 16 is already out).

Migrations to next Angular versions will be performed on this repository so Effy repositories depending on this library can keep using it.

# Migration to new Angular Version

1. In order to make a migration to a new Angular version, you need to update root package.json file to use Angular new version.
2. You can update projects/angular-token/package.json to change version of angular-token
3. Build and publish your version by using the command : npm run build:lib && npm run publish:lib
4. Verify your version is there : [https://github.com/effy-tech/angular-token/pkgs/npm/angular-token]
5. You can use this version in our project
