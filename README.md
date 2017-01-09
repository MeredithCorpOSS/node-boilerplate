# Project Name


## Usage 

* Clone this repo into your repo
* Rename project name in package.json and this file
* Delete this section 
* use this for barebone node project or use this with express generator(there may be a boilerplate for express though). 

### Contains
    * editorconfig   - http://editorconfig.org
    * eslint - http://eslint.org/
    * precommit - http://pre-commit.com
    * infra folder for storing teraform and other configs, migrations and db setups, es and logstash schemas etc 
    * config folder for constant and config - config file is not commited only keys are commited in the default file

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
    
