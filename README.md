
<!-- AIRBNB STANDARD

npx create-react-app .

npm i -D eslint  eslint-plugin-import eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-jsx-a11y

npm init @eslint/config

// no need
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted

//


remove from package.json
esconfig


//no need
npx install-peerdeps --dev eslint-config-airbnb
//

add in eslintrc.json
extends: [
    'airbnb',
  ],
plugins: [
    'react',
    'jsx-a11y',
    'import',
  ],
rules: {
    'react/jsx-filename-extension': [1, { extensions: ['.js', '.jsx'] }],
    'new-cap': [2, { capIsNewExceptions: ['List', 'Map', 'Set'] }],
    'react/no-multi-comp': 0,
    'import/default': 0,
    'import/no-duplicates': 0,
    'import/named': 0,
    'import/namespace': 0,
    'import/no-unresolved': 0,
    'import/no-named-as-default': 2,
    'comma-dangle': 0, // not sure why airbnb turned this on. gross!
    indent: [2, 2, { SwitchCase: 1 }],
    'no-console': 0,
    'no-alert': 0,
    'linebreak-style': 0
  }, -->

