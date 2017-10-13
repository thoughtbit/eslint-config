# eslint-config
ThoughtBit config for ESLint

## Package contents

`@thoughtbit` basic rules<br />
`@thoughtbit/eslint-config/browser` browser rules and environment<br />
`@thoughtbit/eslint-config/es6` ES6 rules and environment, including [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)<br /> 
`@thoughtbit/eslint-config/node` Node.js rules and environment<br />
`@thoughtbit/eslint-config/react` rules for [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react)<br /> 
`@thoughtbit/eslint-config/angular`  rules for [eslint-plugin-angular](https://github.com/Gillespie59/eslint-plugin-angular)<br /> 
`@thoughtbit/eslint-config/vue`  rules for [eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue)<br /> 
`@thoughtbit/eslint-config/test` mocha, chai, sinon rules and environment, including [eslint-plugin-bdd](https://github.com/Nate-Wilkins/eslint-plugin-bdd)<br /> 

## Usage example

```json
{
  "parser": "babel-eslint",
  "extends": [
    "@thoughtbit",
    "@thoughtbit/eslint-config/browser",
    "@thoughtbit/eslint-config/es6",
    "@thoughtbit/eslint-config/node",
    "@thoughtbit/eslint-config/react",
    "@thoughtbit/eslint-config/angular",
    "@thoughtbit/eslint-config/vue",
    "@thoughtbit/eslint-config/test"
  ]
}
```