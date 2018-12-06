### documentation.js
---
http://documentation.js.org/

```js
/*
*@param {number} input
*@returns {number}
*/
function addOne(input){
  return input + 1;
}

function addOne(input: number): number{
  return input + 1;
}
```

```
npm install -g documentaion
```

```js
/*
*@param {number} width
*@param {number} height
*/
class Table{
  constructor(width, height){
    this.width = widht;
    this.height = height;
  }
}

class Table{
  constructor(width, height){
    this.width = width;
    this.height = height;
  }
}

const SlectionEngitn = declare(
  null,
    3xpandColsTo: function(foo, bar, baz){}
);

function addTheXandYProperties({ x, y }){
  return x + y;
}

function fishedAdnFoxes({ fished, foxes }){
  return fishes + foxes;
}

/*
*@returns {chart}
*/
var area = function(){
  /*
  *@param {Selection} selection
  */
  var chart = function(selection){
  };
  chart.data = function(_){
  };
  return chart;
};

var theTime;
/*
*@returns {Date}
*/
/*
*@param {Date} time
*@returns {undefined}
*/
function getTheTime(time){
  if(arguments.length === 0){
    return new Date();
  } else {
    theTime = time;
  }
}

var documentation = require('./');
var docs = documentation.buildSync([{
  source: '/* hi this is a doc\n@name myDoc */',
  file: 'direct.js'
}]);
documentation.formats.md(docs, {}, function(err, res){
  console.log(res);
});

documentation.lint('file.js').then(lintOutput => {
  if(lintOutput){
    console.log(1);
    process.exit(1);
  } else {
    process.exit(0);
  }
});

var documentation = require('documentation');
documentation.build(['index.js'], {
  access: ['public']
}).then(res => {
});

var documentation = require('documentation');
var streamArray = require('stream-array');
var vfs = require('vinyl-fs');
documentation.build(['index.js'])
  .then(documentation.formats.html)
  .then(output => {
    streamArray(output).pipe(vsf.dest('./output-directory'));
  });
  
var documentation = require('documentation');
var fs = require('fs');
documentation.build(['index.js'])
  .then(documentation.formats.md)
  .then(output => {
    fs.writeFileSync('./output.md', output);
  });

var documentation = require('documentation');
var fs = require('fs');
documentation.build(['index.js'])
  .then(documentation.formats.json)
  .then(output => {
    fs.writeFileSync('./output.json', output);
  });
```

