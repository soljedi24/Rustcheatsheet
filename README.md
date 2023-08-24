# Rustcheatsheet
Solana Sierra Leone / Christex Foundation Learning information


Variables and Data Types:

let variable_name = value;
Common data types: i32, u32, f64, bool, char, String
Control Flow:

if condition { } else { }
match value { pattern => { } }
for item in iterable { }
Functions:

fn function_name(parameters) -> return_type { }
Ownership and Borrowing:

Ownership: Each value has a single owner.
Borrowing: References allow multiple read-only accesses.
Structs:

Define with struct StructName { field_name: type }
Enums:

Define with enum EnumName { Variant1, Variant2 }
Pattern Matching:

Match enums or destructure tuples/structs.
Modules:

Organize code with mod module_name { } and pub keyword.
Error Handling:

Use Result<T, E> for functions that can return errors.
Handle errors with match or .unwrap().
Traits and Generics:

Define shared behavior with traits.
Create generic functions and structs.
Closures:

Anonymous functions with captured variables.
Collections:

Arrays: [value, value]
Vectors: Vec<T>
HashMaps: HashMap<K, V>
Concurrency:

Use std::thread::spawn for basic concurrency.
Use std::sync for synchronization.
Lifetime and References:

Specify lifetimes to indicate how long reference
