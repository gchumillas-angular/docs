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

# generates the .ts file that defines a service
# and places it under the /src/app folder (the --spec flag is optional)
ng generate service <name> --spec=false

# generates a 'module'.
# a module contains important information about how the rest of the application
# fits together (the --spec flag is optional)
#   --flat puts the file in src/app instead of its own folder.
#   --module=app tells the CLI to register it in the imports array of the AppModule.
ng generate module <name> --flat --module=app --spec=false
```
