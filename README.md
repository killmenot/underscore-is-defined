# _.isDefined 

A quick shortcut to avoid of using `!_.isUndefined`

Original source: https://gist.github.com/turbobabr/11106163

Copyright (C) 2015  Alexey Kucherenko - https://github.com/killmenot

Licensed under the MIT


## Installation:

    npm install underscore-is-defined


## Dependency: 

One of 

- [underscore.js](http://underscorejs.org/)  
- [lodash.js](http://lodash.com/)  


## Usage:

Load it, either as is (in the browser), as an AMD module, or as a CommonJS/Node.js module), then mix it in with the parent library (which must be explicitly injected):

    _.mixin({deepExtend: underscoreIsDefined(_)});
    
Call it like this:

    var myObj = _.isDefined(foo)