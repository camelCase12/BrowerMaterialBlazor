# BrowerMaterialBlazor
Experimental implementation of Material 3 in Blazor


index.html contains a few example components implemented at different levels:

![image](https://github.com/camelCase12/BrowerMaterialBlazor/assets/14899204/7af0a9a1-105f-4d2f-a676-a7b9b1affdf5)

# Instructions

## Fully Implemented Components

Fully implemented components are referenceable in BrowerMaterialBlazor/Client/Components. These provide Blazor component wrappers for their Material 3 counterparts.

## Partially Implemented Components

Partially implemented components have been compiled into bundle.js and are only directly referenceable (i.e. \<md-tonal-button/>). Partially implemented components will be listed in the import table in index.js.

## Non-Implemented Components

Material 3 has a number of components which I have yet to import, and they may add more in the future. If you wish to use these, you will need to use npm to pull material-web and compile the bundle.js file yourself (see instructions below).

## How to Pull Material 3

1. First, ensure you have npm installed.
2. Navigate to the Client directory, in this case this would be "cd ./BrowerMaterialBlazor/Client/"
3. Run "npm i" to install the necessary node packages for the material bundling pipeline.
4. Run "npx webpack" to bundle material into ./wwwroot/dist/bundle.js. This should automatically pull any imported material and bundle it for blazor to access.
5. To add material components to your project, add a reference to their .js in the wwwroot/index.js file. Then, repeat step 4 to bundle it into the bundle.js.
6. Make sure to press ctrl+F5 each time you re-bundle material. In my case, the components will not load unless I do this.
