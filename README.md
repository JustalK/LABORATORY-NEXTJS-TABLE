# LABORATORY-NEXTJS-MUI

This project is a set of different component adapted from material ui. The library gave a lot of example but there are not well presented and mix the css with the code.
I try to do something different here for getting an easy way to plug those component and since I am the one who built them, I know how to use them.

Obviously I am using `material-ui` and `next.js` as the core technology.

For the documentation for development, I am using `jsdoc` which I find quite good.

## Plan of the presentation

I explain with all the details how I build the project and my way of working.

- [Documentation](#documentation)
- [Organization](#organization)
- [Development](#development)
- [Running](#running)
- [Commands](#commands)

## Documentation
#### Code documentation

The `jsdoc` can be generated locally with the following command :

```bash
$ npm run build:docs
```

## Organization
#### Organization of the global folder

| Folder's Name | Description of the folder                               |
| :------------ | :------------------------------------------------------ |
| out           | The documentation generated by `jsdoc`                  |
| public        | Regroup the images and public files                     |
| src           | Regroup the source code                                 |

#### Organization of the src folder

| Folder's Name | Description of the folder                               |
| :------------ | :------------------------------------------------------ |
| components    | Regroup the components used inside the pages            |
| constants     | Regroup the exported constants                          |
| pages         | Regroup the components representing the pages           |
| services      | Regroup the services of the app                         |
| styles        | Regroup the scss files                                  |

#### Packages

- **react**: The react library
- **react-dom**: The react dom manipulator
- **next**: Framework for building the app
- **sass**: For managing the style of the app under scss file
- **babel-plugin-istanbul**: For managing the transpiling
- **jsdoc**: For building the documentation
- **husky**: For managing the hook
- **eslint**: The linter of the app
- **eslint-plugin-import**: Adding the support for new recommended file
- **@mui/material**: Adding materiel design
- **@emotion/styled**: Adding the emoticon of materiel design
- **@emotion/react**: Adding the style of react
- **@mui/icons-material**: Adding the icons of material

## Running

For running the API, a single command is needed.

```bash
$ npm run start
```

## Commands

- **npm run start**: Run the built project
- **npm run build**: Build the project
- **npm run linter:fix**: Run the linter and fix the errors
- **npm run build:docs**: Build the documentation from the comments in the code
