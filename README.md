# vue-vite-boilerplate

This repo is an example.

# Install and run on localhost:
If you look in package.json you will see a scripts section. One will be called dev which starts the vite development server.

in the directory root run this command to start it up:
```
npm run dev
```


# Build this from scratch instead:

Run the following setup:
```
npm init -y

npm install --save-dev vue vite @vitejs/plugin-vue  # (or just copy my package.json and install like in the Install section.)
```

* Note: you will want to change the versions of things in the package.json to the version you have to use.


Make the following files. You can use the files I wrote as guidance for the contents:
```
 index.html
 
 vite.config.js
 
 jsconfig.json (optional)
 
 src/
 
 src/App.vue
 
 src/main.js
 ```

Lastly, refer to the top section on installing and  running in local host.


# Conventions:

 * Subsequent vue files generally go in a directory `src/components/*`

 * The `public/` directory is for static assets like images.
 
 * You can make a styles directory in `src/styles/` if you want to write shared styles.
