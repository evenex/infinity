# infinity
generic and type-agnostic infinity type constructor

dependencies: meta (github.com/evenex/meta, available on dub)

`infinity!T` creates an infinite variant of type T  

`infinity` creates an untyped infinity which only gains a type when it is operated on by a typed value  

`Infinite!T` is the type of infinity!T  

`Finite!T` extracts the underlying type of an infinity, or acts as the Identity functor when T is finite  
