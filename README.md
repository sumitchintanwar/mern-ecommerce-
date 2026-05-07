# MERN Ecommerce

## Description

An ecommerce store built with MERN stack, and utilizes third party API's. This ecommerce store enable three main different flows or implementations:

1. Buyers browse the store categories, products and brands
2. Sellers or Merchants manage their own brand component
3. Admins manage and control the entire store components

### Features:

- Node provides the backend environment for this application
- Express middleware is used to handle requests, routes
- Mongoose schemas to model the application data
- React for displaying UI components
- Redux to manage application's state
- Redux Thunk middleware to handle asynchronous redux actions

## Database Seed

- The seed command will create an admin user in the database
- The email and password are passed with the command as arguments
- Like below command, replace brackets with email and password.
- For more information, see code [here](server/utils/seed.js)

```
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
```

## Install

`npm install` in the project root will install dependencies in both `client` and `server`. [See package.json](package.json)

Some basic Git commands are:

```
git clone <repository-url>
cd project
npm install
```

## ENV

Create `.env` file for both client and server. See examples:

[Frontend ENV](client/.env.example)

[Backend ENV](server/.env.example)

## Start development

```
npm run dev
```

## Languages & tools

- Node
- Express
- Mongoose
- React
- Webpack

### Code Formatter

- Add a `.vscode` directory
- Create a file `settings.json` inside `.vscode`
- Install Prettier - Code formatter in VSCode
- Add the following snippet:

```json
{
  "editor.formatOnSave": true,
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",
  "prettier.jsxSingleQuote": true,
  "prettier.trailingComma": "none",
  "javascript.preferences.quoteStyle": "single"
}
```
