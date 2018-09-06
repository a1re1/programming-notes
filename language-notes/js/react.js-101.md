## Setup
### Installing
npm install -g create-react-app
create-react-app {app-name} // in order to setup react project

### Post Setup
Inside that directory, you can run several commands:

  npm start
    Starts the development server.

  npm run build
    Bundles the app into static files for production.

  npm test
    Starts the test runner.

  npm run eject
    Removes this tool and copies build dependencies, configuration files
    and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  cd frontend
  npm start

Happy hacking!

## Rendering
- React modules must return some form of jsx (html) code that the DOM can take in and send to the page.

- React.createElement('div', {className:CSS element}, 'h1', ...) // component, config, children, ... (more children) ##default behavior of children is to render as text; recursively call React.createElement() to include more layers

- JSX element must have one root element usually, but sometimes can have adjacent elements

- By convention, components are put inside a folder starting with a capital letter

- Dynamic content can be loaded by executing JS functions in the jsx code with {function()}.
