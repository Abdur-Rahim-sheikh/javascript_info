### Notes on javascript
#### some fantastic implementations using javascript
* [Dynamic Calculator](data-types/calculator.html)


**Array methods**

1. `arr.push(...items)` – adds items to the end.
2. `arr.pop()` – extracts an item from the end.
3. `arr.shift()` – extracts an item from the beginning, 
    - not recommended
4. `arr.unshift(...items)` – adds items to the beginning.
    - not recommended
5. `arr.splice(index, deleteCount, ...items)` – at index delete deleteCount elements and insert items.
6. `arr.slice(start, end)` – creates a new array, copies elements from start till end (not inclusive) into it.
7. `arr.concat(...items)` – returns a new array: copies all members of the current one and adds items to it. If any of items is an array, then its elements are taken.
8. `arr.forEach(function(item, index, array) {})` – calls a function for every element.

9. `arr.indexOf(item, from)/lastIndexOf(item)` – looks for item starting from index from, and returns the index where it was found, otherwise -1.
10. `arr.includes(item, from)` – looks for item starting from index from, returns true if found.
11. `arr.find(function(item, index, array) {})` – returns the first item for which the function returns true, and undefined otherwise.
12. `arr.findIndex(function(item, index, array) {})` – returns the first item index for which the function returns true, and -1 otherwise.
13. `arr.filter(function(item, index, array) {})` – returns an array of all elements for which the function returns true.
14. `arr.map(function(item, index, array) {})` – returns an array of the results of the function for each element.
15. `arr.sort(function(a, b) {})` – sorts the array in place.
    - if function not passed then it will sort in lexicographic order treating as string.
16. `arr.reverse()` – reverses the array in place.
17. `arr.split(separator, limit)` – splits the string into an array by the separator.
18. `arr.join(glue)` – joins the array into a string using glue between elements.
19. `arr.reduce(function(accumulator, item, index, array) {}, initial)` – calculate a single value over the array by calling the function for each element and passing an intermediate result between the calls.
20. `arr.reduceRight(function(accumulator, item, index, array) {}, initial)` – same as arr.reduce, but goes from right to left.
21. `arr.every(function(item, index, array) {})` – returns true if the function returns true for every element.
22. `arr.some(function(item, index, array) {})` – returns true if the function returns true for at least one element.
23. `arr.fill(value, start, end)` – fills the array with repeating value from start to end.
24. `arr.copyWithin(target, start, end)` – copies its elements from position start till position end into itself, at position target (overwrites existing).
25. `Array.isArray(value)` – returns true if the value is an array, and false otherwise.