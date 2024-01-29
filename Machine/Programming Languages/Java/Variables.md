
## Declaring Variables

Syntax: `type variableName;` Example: `int age;`

## Initializing Variables

Syntax: `variableName = value;` Example: `age = 25;`

![[Pasted image 20240128155407.png]]

## Declaring and Initializing Together

Syntax: `type variableName = value;` Example: `int age = 25;`

## Variable Naming Conventions

- Start with a letter, `$`, or `_`
- Case sensitive
- Use camelCase for multi-word names
- Be descriptive

## Scope of Variables

- **Local Variables**: Declared inside a method or block.
- **Instance Variables**: Declared inside a class but outside a method.
- **Static Variables**: Declared as `static`, which means they belong to the class rather than an object.
![[Pasted image 20240128155441.png]]
## Constants

Declared with the `final` keyword. Value can't be changed once assigned. Example: `final int MAX_HEIGHT = 200;`

## Example

```java
`public class Main {     
	public static void main(String[] args) {         
		int age = 30; // local variable         
		System.out.println("Age is: " + age);     
	} 
}`
```

---

## Resources

https://www.w3schools.com/java/java_variables.asp
https://www.javatpoint.com/java-variables