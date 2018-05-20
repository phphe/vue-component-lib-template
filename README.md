# vue-component-lib-template
Base on [vue webpack template](https://github.com/vuejs-templates/webpack). Integrated bili.js to bundle components to library.
## usage
```sh
vue init phphe/vue-component-lib-template my-project
```
## notice
We can omit file extensions when import file and use '@' as alias of src in vue webpack template. That will not work when package. So please don't use '@' and use full file name.
## other
The entrance to the packaged library is src/lib-entry.js. When package library, main.js and App.vue will not be used.   
The npm scripts extended vue webpack template. So you can run 'npm run dev' when develop. 'npm run build' is renamed to 'npm run build-vue'. Now 'npm run build' will call build/build-lib.js to package a library.
