```js
// This is a quine. Don't believe me? Try running it in node
const code = [
    "// This is a quine. Don't believe me? Try running it in node",
    "const code = [",
    "",
    "];",
    "",
    "const SiddharthShyniben = {",
    "    age: 13,",
    "    position: 'India' | 'Oman',",
    "    code: ['Javascript', 'Typescript', 'HTML', 'CSS'],",
    "    tools: ['Angular', 'Node'],",
    "}",
    "",
    "for (let i = 0; i < 2; i++) console.log(code[i])",
    "for (let i = 0; i < code.length; i++) console.log('    ' + String.fromCharCode(34) + code[i] + String.fromCharCode(34) + ',');",
    "for (let i = 3; i < code.length; i++) console.log(code[i])"
];

const SiddharthShyniben = {
    age: 13,
    position: 'India' | 'Oman',
    code: ['Javascript', 'Typescript', 'HTML', 'CSS'],
    tools: ['Angular', 'Node'],
}

for (let i = 0; i < 2; i++) console.log(code[i]);
for (let i = 0; i < code.length; i++) console.log('    ' + String.fromCharCode(34) + code[i] + String.fromCharCode(34) + ',');
for (let i = 3; i < code.length; i++) console.log(code[i])
```
