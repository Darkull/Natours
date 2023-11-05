# Natours - A travelling web page

##Node SASS

# node sass

`npm init`

`npm install node-sass --save-dev`

- `—save` it saves as dependencies while `—save-dev` saves as dev-dependencies

to install from package.json run `npm install`

to uninstall a package `npm uninstall jquery`

### make scss

create sass folder `mkdir sass`

- `touch main.scss` creates first scss file
-

### run compiler

```json
"scripts": {
"compile:sass": "node-sass sass/main.scss css/style.css -w" // -w keeps watching the code
},
```

“command”: “package name input folder output folder” `npm run compile:sass`
