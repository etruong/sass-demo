# SASS demo

This repo is a quick demo of how to use SASS, a CSS pre-processor in which allows developers to use variables, functions, nesting, and more. 

## Installation

To start please run _npm install -g sass_ in the command terminal. After the installation is
complete, run _sass --version_, this should output the sass version of 1.23.0 if installed correctly.

## Using SASS

Create a SASS file (using the .scss extension) call it 'input' and a CSS file called 'output.' 

### Compile manually
```
sass input.scss output.css
```
### Using --watch
```
# Similar to live-server (using --watch), detect changes in input.scss file and outputs to output.css file
sass --watch input.scss output.css

# Specify specific directories in which to output and input files
sass --watch app/sass:public/stylesheets
```

For more information: https://sass-lang.com/documentation
Check SASS quick tutorial: https://sass-lang.com/guide