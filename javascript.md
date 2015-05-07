# JS Style

- Indent with two spaces (even though tabs are technically better, we're conforming because fuck it).

- JS variables are `lowerCamelCase` when neccessary, single `word` variables preferred.

- Variable names should be human readable and understandable (wrong: `zzzzzsomeshithere`, `x1`, `x3`).

- Things instantiated with `new` are `UpperCaseCamel`

- Function names are also `camelCase`.

- Use var when defining a new var.

- Use ; at the end of lines - just do it.

- Strings are enclosed with single quotes e.g. `var username = 'buns';`

- Quality code is not determined by the least number of characters one types.

- Use characters and whitespace to make your code legible to others.

- Use comments judiciously to explain why things are the way they are.


## Newlines
A newline after the start of a block helps you see it.

*Right:*
```
function addFive(input){

  var output = input + 5;

  return output;
}

for(var i = 0; i < 5; i++){

  console.log(i);
}
```

*Wrong:*
```
function addFive(input){  
  var output = input + 5;
  return output;}

for(var i = 0; i < 5; i++){
  console.log(i);
}
```

## Brackets

*Right:*
```
function addFive(input){

  var output = input + 5;

  return output;
}

for(var i = 0; i < 5; i++){

  console.log(i);
}

if(test == true){

  doSomething();
}
```

*Wrong:*
```
function addFive(input)
{  
  var output = input + 5;

  return output;
}

for(var i = 0; i < 5; i++){

  console.log(i);}
```

## Always Enclose Blocks

*Right:*
```
if(test == true){

  doSomething();
}
```

*Wrong:*
```
if(test == true) doSomething();

if(test == true)
  doSomething();
```
