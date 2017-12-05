## Step 1. Set up the Development Environment
```sh
npm install -g @angular/cli
```

## Step 2. Update existing angular/cli

```sh
npm uninstall -g angular-cli
npm uninstall --save-dev angular-cli

npm uninstall -g @angular/cli
npm cache clean
# if npm version is > 5 then use `npm cache verify` to avoid errors (or to avoid using --force)
npm install -g @angular/cli@latest
```

## Step 3. Create a new project
```sh
ng new ngx-profile
```

## Step 4. Serve the application
```sh
ng serve --open
```



