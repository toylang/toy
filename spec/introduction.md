# Introduction

Toy is a simple, modern, object-oriented, type-safe programming language.

## Hello World

The "Hello, World" program is traditionally used to introduce a programming language. Here it is in Toy (similar to c#):

```toy
namespace Toy
{
    class Hello
    {
        static void Main() {
            Console.WriteLine("Hello, World");
        }
    }
}
```

## Types and variables

There are two kinds of types in Toy: *value types* and *reference types*.

The following table provides an overview of Toy's type system.

| **Category**    | **Description** |
|-----------------|-----------------|
| Value types     | Signed integral: `int`, `long` |
|                 | Unicode characters: `char` |
|                 | IEEE floating point: `float`, `double` |
|                 | Boolean: `bool` |
|                 | User-defined types of the form `enum E {...}` |
|                 | User-defined types of the form `struct S {...}` |
|                 | Extensions of all other value types with a `null` value |
| Reference types | Ultimate base class of all other types: `object` |
|                 | Unicode strings: `string` |
|                 | User-defined types of the form `class C {...}` |
|                 | User-defined types of the form `interface I {...}` |
|                 | Single- and multi-dimensional, for example, `int[]` and `int[,]` |
