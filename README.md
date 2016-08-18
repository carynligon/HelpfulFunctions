##### Remove all duplicates from an array
```js
let reduced = arrayToReduce.reduce((returnSoFar, curr) => {
      if (returnSoFar.indexOf(curr) === -1) {
        returnSoFar.push(curr);
      }
      return retsf;
    },[]);
```
