# 神.clj | Shen for Clojure

http://shenlanguage.org/

Shen is a portable functional programming language by [Mark Tarver](http://www.lambdassociates.org/) that offers

* pattern matching,
* λ calculus consistency,
* macros,
* optional lazy evaluation,
* static type checking,
* an integrated fully functional Prolog,
* and an inbuilt compiler-compiler.


## The Clojure Port

Is a work in progress by Håkan Råberg. **It doesn't work**. Uses https://github.com/technomancy/leiningen to build.

To run the REPL:

    lein compile; java -cp lib/*:classes shen