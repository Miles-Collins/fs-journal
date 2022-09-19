# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is a declarative region that provides a scope to the identifiers (the names of types, functions, variables, etc) inside it. Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A class is a user-defined blueprint or prototype from which objects are created. Basically, a class combines the fields and methods(member function which defines actions) into a single unit. A structure is a collection of variables of different data types under a single unit.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
A constructor is a special kind of subroutine in a class. It has the same name as the name of the class, and it has no return type, not even void. A constructor is called with the new operator in order to create a new object.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
The type of variable that goes into Start()
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It is preventing the inheritance of a class or certain class members that were previously marked virtual.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
Virtual methods can be overridden using the override or final modifier.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected and default 
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
 A private entity can only be accessible from within the class.
```