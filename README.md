# express-gen

A practice of using express-generator

## Components

* node
* npm
  * express-generator
  * nodemon

## Usage

    apt install npm
    npm install -g express-generator
    mkdir express-gen
    express express-gen
    cd express-gen
    npm install # Set all to default
    sed -i -e "s/node /nodemon /g" package.json
    npm start

## Test

    curl http://localhost:3000


