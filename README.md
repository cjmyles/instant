# Instant

`Instant` is a collection of application boilerplates, CLI tools and NPM packages, designed to enable the rapid development and deployment of applications on the Firebase platform.

[React](#instant-react) and [Express](#instant-express) boilerplates utilise the suite of `instant` packages to enable routing, authentication/authorisation, state management, interaction with all Firebase services and more. Although the `instant` packages have been specifically tailored to work with these boilerplates, they could also be used in isolation in any project.

The [`instant-tools`](#instant-tools) CLI can be used to create new applications (by cloning the relevant boilerplate), install dependencies, and generate project files such as new React components and Redux modules.

## Boilerplates

### [instant-react](https://github.com/cjmyles/instant-react)

React boilerplate bundled with [React Router](https://github.com/ReactTraining/react-router), [Material-UI](https://material-ui.com/) (with support for [Bootstrap](https://getbootstrap.com/)), layouts, and Redux ([Redux Thunk](https://github.com/reduxjs/redux-thunk) implementing [Ducks](https://github.com/erikras/ducks-modular-redux) with optional [localstorage persistence](https://www.npmjs.com/package/redux-localstorage)). Integrates seemlessly with the [Firebase](https://firebase.google.com/) platform to enable services such as [Firebase Authentication](https://firebase.google.com/docs/auth/), [Cloud Firestore](https://firebase.google.com/docs/firestore/), [Cloud Storage](https://firebase.google.com/docs/storage/) and [Firebase Hosting](https://firebase.google.com/docs/hosting/).

### [instant-express](https://github.com/cjmyles/instant-express)

Express boilerplate bundled with authentication, routing, CORS, logging, sessions, API model-mapping and more. Integrates seemlessly with the [Firebase](https://firebase.google.com/) platform to enable services such as [Firebase Admin](https://firebase.google.com/docs/reference/admin/), [Firebase Authentication](https://firebase.google.com/docs/auth/), [Cloud Firestore](https://firebase.google.com/docs/firestore/), [Cloud Storage](https://firebase.google.com/docs/storage/) and [Firebase Functions](https://firebase.google.com/docs/functions/).

## NPM Packages

### [instant-tools](https://www.npmjs.com/package/instant-tools)

Command Line Tools for assisting with creating [`instant`](https://github.com/cjmyles/instant) applications and generating project files.

### [instant-react-core](https://www.npmjs.com/package/instant-react-core)

Core [`instant-react`](https://github.com/cjmyles/instant-react) functionality, including components, forms, Redux modules, utilities and [Firebase](https://firebase.google.com/) integration.

### [instant-express-core](https://www.npmjs.com/package/instant-express-core)

Core [`instant-express`](https://github.com/cjmyles/instant-express) functionality, including routing, authentication, session, utilities and [Firebase](https://firebase.google.com/) integration.

### [instant-firestore](https://www.npmjs.com/package/instant-firestore)

[Firebase Cloud Firestore](https://firebase.google.com/docs/firestore/) ORM to ease common tasks such as creating, finding, updating and deleting documents.

### [instant-firestore-utils](https://www.npmjs.com/package/instant-firestore-utils)

Lightweight [Firebase Cloud Firestore](https://firebase.google.com/docs/firestore/) utility library.

### [instant-request](https://www.npmjs.com/package/instant-request)

Client/server agnostic Http Request library utilising the `fetch` API.

### [instant-utils](https://www.npmjs.com/package/instant-utils)

Lightweight utility library to assist other instant packages.
