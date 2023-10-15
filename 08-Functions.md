# Functions: Architects of Logic

In the realm of code, functions stand as the architects of logic, meticulously crafting sequences of actions to execute at your command. Much akin to their Python counterparts, code functions possess a distinctive elegance in their creation and execution.

## Function Creation
To summon forth a function, the `def` keyword serves as your incantation. Functions are born like any other variable, yet their purpose is attached within the intricate dance of expressions that follow.

```py
def add(x, y) {
    return x + y;
}
```

## Function Invocation
Unlocking the potential of functions is achieved through the invocation ritual, signaled by the `()` operator. By uttering the function's name within these parentheses, you beckon its execution.

```py
add(5, 5);
```

## Function Assignment
In the realm of functions, the boundaries between variables and functions blur. In addition, functions can take residence within variables, just as any other entity. Such assignments harness the power of functions for further manipulation.

```py
def add(x, y) {
    return x + y;
}

x = add;
k = x(5, 5);
print(k);
```

## Functions in Objects
The amalgamation of functions and objects engenders a compelling synergy. Functions assume an integral role within objects, serving as a pivotal means to unlock their inherent potential. As you define functions within objects, the nomenclature of the functions takes on the mantle of a key, guiding you into a realm of meticulously structured logic.

```py
let hello = {
    something: def(name){
        println("Hello, " + name + "!");
    },
    earth: def(){
        println("Hello, Earth!");
    }
};
```

## Interaction and Expression
Coda's functions extend an invitation to engagement and creative expression. By summoning the essence of the function with meticulous parameters, a harmonious orchestration of actions takes place, resulting in an elegantly choreographed sequence of events.

```py
let inp = input("What is your name? ");
hello.something("World");
hello.earth();
hello.something(inp);
```

## Explicit Return
Within the domain of function composition, a notable feature distinguishes itself: the automatic default return of the last executed statement within a function is no longer in effect. Instead, the 'return' function allows for explicit specification of the desired return value.

```py
def multiply(x, y) {
    return x * y;
}
```

Within the world of Coda, functions serve as more than mere tools; they emerge as the master craftsmen of you programming canvas. The process of thier creation, invocation, and integration within objects embarks on a journey into the realm of structured logic, weaving a narrative characterized by precision and expressive artistry.
