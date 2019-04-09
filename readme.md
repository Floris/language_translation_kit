# language translation kit

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
"scripts": {
    "compile_lang": "node src/lang/compile.js"
  },
```
