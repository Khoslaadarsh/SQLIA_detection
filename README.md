# SQLIA_detection
---
description: It will detect malicious text in input file. 
Based on pattern matching and trimming using z-algorithm.

---

```js
const sqlia_detect = require('sqlia_detect');

const result = sqlia_detect(`usual password`);
//Here result will be false

result = sqlia_detect(`anything" or "x"="x`) 
//Here result will be true, as the input is malicious
```