# Back-End Scaffolding

## Initial Setup and Test
1. Install [Node.js](https://nodejs.org/en/) 
1. clone this scaffolding repository and `cd` into it with your shell (note: if you're on Windows, you can for example use [Git Bash](https://git-scm.com/download/win) as a shell)
1. run `npm install`
1. To compile the TypeScript code to JavaScript, run `npm run tsc`. After that, your repo should have a `build` folder containing a bunch of JavaScript files
1. Run `node build/server.js`, The command line output should say something like `Listening at http://localhost:3000/`
1. Test your installation by opening the following endpoints (i.e. "pages") in your browser:
  - http://localhost:3000/welcome
  - http://localhost:3000/welcome/[any name]
