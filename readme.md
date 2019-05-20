# Command Line Dictionary 

It's a command line tool written in NodeJS which gives output to definitions, synonyms, antonyms and examples to a word. Also there is a command to play game with words where user has to guess word, if failed can ask for hint. The dictionary feature is implemented by using api calls to [Fourty Two Words](https://fourtytwowords.herokuapp.com)

## Installation

Use the package manager [NPM](https://www.npmjs.com/) to install the node_modules

```npm install```

Give execution permission to the file dict so that it can be executed.

```chmod +x ./dict```

## Usage

API endpoints for the CLI tool

```
./dict def <word> #Display definitions of a word. 

./dict syn <word> #Display synonyms of a word. 

./dic ant <word> #Display antonyms of a word

./dict <word> or ./dict dict <word> #Display all above details for a word

./dict #Display all above details of word of the day

./dict play #The program should display a definition, a synonym or an antonym and ask the user to enter the word
```
