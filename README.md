# Svg-to-ttf

## Setup

Add the script to your package.json under scripts for example

    "fonts": "svg-to-ttf --name test --svgs 'resources/font-src/*.svg' --config src/components/Icon/config.json --font resources/fonts",

    --name || -n    The name of the font file that will be generated
    --svgs || -s    The folder containing the svgs you want included in the font
    --config || -c  The folder where the generated config will be output
    --font || -f    The folder where the generated font will be output

Add any svgs you want to be used to the svgs folder you specified

## Running

Run either command depending on if you are using yarn or not

    npm run fonts

    yarn fonts

## Utilizing Font With React

For example use the font file with [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons#custom-fonts) to create a React Component