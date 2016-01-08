# ...spread

## notes
Can be used 3 ways
<br />
`function (...args)`
<br />
array literals
<br />
`[...ar, 3, 4, 5]`
<br />
destructuring
<br />
`[d, e, ...iterableObj] = [4, 5, 6, 7];`

Interesting way to push using ...spread, if you have two arrays to join them together
<br />
`var a = ['b', 'c'];`
`var d = ['e', 'f', 'g'];`
`d.push(...a);`

## links
http://www.datchley.name/es6-rest-spread-defaults-and-destructuring/
<br />
http://derickbailey.com/2015/11/16/kill-apply-with-the-spread-operator/
<br />
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters
https://ponyfoo.com/articles/es6-spread-and-butter-in-depth
