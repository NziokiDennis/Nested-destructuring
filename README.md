# Nested-destructuring
var obj = {
 a: {
 c: 1,
 d: 3
 },
 b: 2
};
var {
 a: {
 c: x,
 d: y
 },
 b: z
} = obj;
console.log(x, y, z); // 1,3,2
