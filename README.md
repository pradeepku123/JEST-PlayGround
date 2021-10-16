## Explore JEST Testing FrameWork

## install Project Setup

mkdir JEST-PlayGround
cd JEST-PlayGround
npm init -y

## install Project Dependencies

yarn add --dev jest
yarn add --dev babel-jest @babel/core @babel/preset-env

## Create Folder Structure

./src
./src/main
./src/tests
./src/tets/\*.spec/js

## Create babel.config.js file

// babel.config.js
module.exports = {
presets: [['@babel/preset-env', {targets: {node: 'current'}}]],
};
