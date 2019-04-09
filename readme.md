# language translation kit voor co2ok

## Execute language file compiler

``` bash
# clone repository
git clone https://github.com/Floris/language_translation_kit.git

# move to folder
cd language_translation_kit

#  -optional: create extra files and objects

# execute script
npm run compile_lang

```

Add the NPM run command by adding:

```
# "scripts": {
    "compile_lang": "node src/lang/compile.js"
  },
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
