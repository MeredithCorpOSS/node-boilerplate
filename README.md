# Documentation

## Usage 

* Clone this repo into your repo
* Rename PROJECTNAME in the codebase like in package.json, index.js, this file
* use this for barebone node project or use this with express generator(there may be a boilerplate for express though). 

### Contains
    * editorconfig   - http://editorconfig.org
    * eslint - http://eslint.org/
    * precommit - http://pre-commit.com
    * debug module to debugging instead of console - https://www.npmjs.com/package/debug
    * logging module - yet to be decided
    * infra folder for storing teraform and other keys, migrations and db setups, es and logstash schemas etc 
    * config folder for constant and config - config file is not commited only keys are commited in the default file


## Delete everything above this



# PROJECTNAME

## Setup(mac)

* Install brew
* Install node, npm
* Install [pre-commit](http://pre-commit.com/#install)

   ```brew install pre-commit```
   
* Clone the code  

   ```git clone git@github.com:TimeInc/hr-bot.git```

   
* Install node modules

   ``` npm install ```

* Rename config.default.js to config.js and fill in the values. 
    
