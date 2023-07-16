# BrowerMaterialBlazor
Experimental implementation of Material 3 in Blazor


index.html contains a few example components implemented at different levels:

![image](https://github.com/camelCase12/BrowerMaterialBlazor/assets/14899204/84af1694-1846-454d-816a-132edc35f595)

# Instructions

## Fully Implemented Components

Fully implemented components are referenceable in BrowerMaterialBlazor/Client/Components. These provide Blazor component wrappers for their Material 3 counterparts.

## Partially Implemented Components

Partially implemented components have been compiled into bundle.js and are only directly referenceable (i.e. <md-tonal-button/>). Partially implemented components will be listed in the import table in index.js.

## Non-Implemented Components

Material 3 has a number of components which I have yet to import, and they may add more in the future. If you wish to use these, you will need to use npm to pull material-web and compile the bundle.js file yourself.
