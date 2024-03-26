# Typescript_VS_Javascript

**What is Typescript?**
- TypeScript is an object-oriented programming language. This language is a strongly typed programming language that builds on JavaScript.
- JavaScript is well suited for small-scale applications but TypeScript is used for large-scale applications.
- TypeScript code has been written first, then it will be converted to plain JavaScript code using the TypeScript compiler.

**Why Typescript?**
- Typescript language that can detect errors in the code during the compile time. 

**TypeScript Features?**
- OOPs (Object Oreiented Programing)

**What is Union Type?**
- A union type has the ability to combine more than one data type for a variable or a function parameter.
  
**What is Inheritance?**
- Inheritance is passing down properties & methods from parent class to child class.
- If child & parent have same method, child's method will be used. [Method Overriding]

**Different bt type & interface?**
- Use customs types when you need unions or intersections
- Use interface when defining object or classes
```
type StudentOne = {
      name : string;
      age: number;
      address: string | number
}

interface StrudentTwo {
      name : string;
      age: number;
      great(){}
}
```
