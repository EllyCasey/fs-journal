# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > | Const and let are the variable declarations we use. It used to be Var |

02. What is the definition of a function?

    > | Code that is used to perform a defined task |

03. What are the `SOLID` principles?

    > | S- Single responsibility principle; every function should do 1 thing
        O- Open-closed principle; entities should be open for extension, but   closed for modification.
        L- Liskov substitution principle; a derived class must be completely substitutable for its base classes
        I- Interface segregation principle; Doesn't require everything to contain the same classes; if they don't need it and it's not defined, that is okay.
        D- Dependency inversion principle; We should depend on abstractions instead of concrete implementations.|

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | const removed = fruit.splice('pineapple'); |

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > | you could append each variable to the brackets for the friends section (ex. w/in 'you', friends: [them]) |

06. Give an example of a JavaScript `Conditional`:

    > | an 'if' or 'elseif' statement|

07. What is the main difference between `parameters` and `arguments`?

    > | Parameters are names and arguments are values. There can be no parameter until it has an argument. |

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | there is also a console.debug() command that will do similar things with a bit more organization to errors. |

09. What is the difference between a `primitive` value and a `reference` value?

    > | Primitive values are stored directly whereas reference values store their information in memory addresses, allowing more complex information to be stored and retrieved |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | for (let i = -100, i < 100; i++){
        console.log(i)
    } |
