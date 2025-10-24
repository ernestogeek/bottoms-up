# Bottoms Up

Template Typescript React Project

![Travis (.com)](https://img.shields.io/travis/com/tienduy-nguyen/typescript-react-boilerplate)
[![Netlify Status](https://api.netlify.com/api/v1/badges/2c01fcbb-9811-4e0e-b86c-e1b79e4f2c46/deploy-status)](https://app.netlify.com/sites/reactts-boilerplate/deploys)


Demo deploy at: [reactts-boilerplate.netlify.app](https://reactts-boilerplate.netlify.app/)



**This version is deprecated, It will be updated & changed soon. Learn more about  [React boiler plate](https://github.com/react-boilerplate/react-boilerplate)**


---

- [TypeScript React Boilerplate](#typescript-react-boilerplate)
  - [Installation](#installation)
  - [Technologies](#technologies)
  - [Project structure](#project-structure)
    - [src folder](#src-folder)
  - [Project Routes](#project-routes)
    - [Public routes](#public-routes)
    - [Private routes (need auth)](#private-routes-need-auth)
## Installation

To use this template
- Clone this project
- Rename project as you want
- Install dependencies from `package.json` to your machine
  
  ```bash
  $ yarn
  # or
  $ npm install
  ```

- Run or build project
  ```bash
  $ yarn start
  $ yarn build
  # or npm run start / npm run build
  ```
- Start coding

Login
```
username: tester
password: 123456
```


## Technologies
  - Integrate ESlint, Prettier
  - Styled-Component and CSS Module for CSS
  - Using TypeScript
  - Using Redux, React thunks
  - Functional programming with React hooks
  - Lazy load page
  - Using ant design
  - Using json-server to create fake server backend
  - CI-CD with Travisci & Github actions
  

### src folder
  - **@types**: Declare modules, interface, type for TypeScript
    - `action.d.ts`: Action Interface for Redux
    - `api.d.ts`: Response interface for api
    - `files.d.ts`: Declare modules for images, videos, css formats...
    - `reducer.d.ts`: return type of reducer
    - `product.d.ts`, `user.d.ts`: return interface of item in project
  - **api**: services, contains functions get, post .. api (axios e.g)
  - **App**: component App
  - **assets**: images, videos, files, …
  - **components**: contains folders components
  - **constants**: constant, enum
  - **helpers**: functions helpers
  - **hooks**: contains hooks using
  - **pages**: pages of project
  - **routes**: private routes and public routes of project
  - **store**: store of Redux and root reducers

## Project Routes
### Public routes
- **Home**: '/': Show landing page before login
- **Feature - Option 1**: '/feature1'
- **Feature - Option 2**: '/feature2'
- **Demo - Option 1**: '/demo1'
- **Demo - Option 2**: '/demo1'
- **About**: '/about'
- **Contact**: '/about'
- **Login**: '/login'
- **Register**: '/signup'
- **404**: Page not found

### Private routes (need auth)
- **Profile**: '/profile'
- **Products**: '/' or '/products': Show list of products
- **Show Product**: '/products/:id
- **Create Product**: '/products/new
- **Edit Product**: '/products/:id/edit
- **Update Product**: '/products/:id
- **Delete Product**: button click
