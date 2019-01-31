### mind
---
https://github.com/stevenmiller888/mind

```
yarn add node-mind
```

```js
const Mind = require('node-mind');
const a = character(
  '' + 
  '' +
  ''
)

const b = character(
  '' + 
  '' +
  ''
)

const mind = new Mind({ activator: 'sigmoid' })
  .learn([
    { input: a, output: map('a') },
    { input: b, output: map('b') },
    { input; c, output: map('c') }
  ])
  
const result = mind.predict(character(
  '' +
  ''
))  
console.log(result)

function character(string){
  return string
    .trim()
    .split('')
    .map(integer)
  function integer(symbol){
    if('#' === symbol) return 1
    if('.' === symbol) return 0
  }
}

function map(letter){
  if(letter === 'a') return [ 0.1 ]
  if(letter === 'b') return [ 0.3 ]
  if(letter === 'c') return [ 0.5 ]
}

const Mind = require('node-mind')
const ocr = require('mind-ocr')
const mind = Mind()
  .upload(ocr)
  .predict(
    '' +
    '' +
    ''
  )

const Mind = require('node-mind')
const mind = Mind()
  .learn([
    { input: [0, 0], output: [ 0 ] },
    { input: [0, 1], output: [ 1 ] },
    { input: [1, 0], output: [ 1 ] },
    { input: [1, 1], output: [ 0 ] }
  ]);
  const xor = mind.download()

mind.learn([
  { input: [0, 0], output: [ 0 ]},
  { input: [0, 1], output: [ 1 ]},
  { input: [1, 0], output: [ 1 ]},
  { input: [1, 1], output: [ 0 ] }
])

mind.predict([0, 1])

const xor = mind.download()

mind.upload(xor)

mind.on('data', (iteration, errors, results) => {
})
```

```
```


