# docs
Starting on Angular's framework.

# Create and run a project

```bash
ng new my-app
cd my-app

# the following lines removes an unnecessary warning message
npm install rxjs@5.5.5
npm install @angular-devkit/schematics@0.0.40

# launches the server
# The --open flag is optional and, if it is present, opens
# the app in the default browser
ng serve --open
```

# Angular-CLI utility

```bash
# generates the .ts, .html and .css files that defines a component
# and places it under the /src/app/<name> folder (the --spec flag is optional)
ng generate component <name> --spec=false

# generate the .ts file that defines a service
# and places it under the /src/app folder (the --spec flag is optional)
```
