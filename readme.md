*This repository is a mirror of the [component](http://component.io) module [math/utils-linear-partitioning](http://github.com/math/utils-linear-partitioning). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/math-utils-linear-partitioning`.*

# The Partition Problem

See http://www8.cs.umu.se/kurser/TDBAfl/VT06/algorithms/BOOK/BOOK2/NODE45.HTM

Input: given an array of S non-negative numbers and an integer k (the number of partitions we want)

Output: Partition S into k ranges, so as to minimize the maximum sum over all the ranges. 

```javascript
var partition = require('linear-partitioning');

partition([1,2,3,4,5,6,7,8,9], 3);
> [[1,2,3,4,5], [6,7], [8,9]]
```
