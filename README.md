# week-day-calculator
NPM project where a user inputs the date and it will tell you what day of the week it is.

#include a .babelrc and .eslintrc files!

npm install and npm run build start.


## .babelrc


  
{
    "env": {
      "test": {
        "plugins": ["@babel/plugin-transform-modules-commonjs"]
      }
    }
  }
  
  ## .eslintrc
  
  
{
    "parserOptions": {
        "ecmaVersion": 2018,
        "sourceType": "module"
    },
    "extends": "eslint:recommended",
    "env": {
      "es6": true,
      "browser": true,
      "jquery": true,
      "node": true
    },
    "rules": {
        "semi": 1,
        "indent": ["warn", 2],
        "no-console": "warn",
        "no-debugger": "warn"
    }
}

## .gitignore

  
node_modules/
.DS_Store
dist/
