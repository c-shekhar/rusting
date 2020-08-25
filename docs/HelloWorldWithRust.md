#### Anatomy of a Rust Program
```
fn main() {
    println!("Hello, world!");
}

```
    
`println!("Hello, world!");` This line does all the work in this little program: it prints text to the screen.   

There are four important details to notice here:    

1. Rust style is to indent with four spaces, not a tab.

2. `println!` calls a Rust macro. If it called a function instead, it would be entered as `println` (without the `!`).  
   We’ll discuss Rust macros in more detail later. For now, we just need to know that using a `!` means that we are calling a macro instead of a normal function.  

3. We see the `"Hello, world!"` string. We pass this string as an argument to `println!`, and the string is printed to the screen.  

4. We end the line with a semicolon `(;)`, which indicates that this expression is over and the next one is ready to begin.  
   Most lines of Rust code end with a semicolon.

#### Compiling a Rust program
```
$ rustc main.rs
```
on linux it will create binary excecutables.
```
$ ls
main  main.rs
```
#### Running a Rust program
Simply run the `main` file, like this
```
$ ./main
```
