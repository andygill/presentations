Title: Sunroof and a Blank Canvas: A tail of two DSLs

Sunroof is a embedded Haskell DSL that compiles to JavaScript.
Blank Canvas is embedded Haskell DSL that provides direct access to the HTML5 Canvas.
Both DSLs superficially provide the same capability, but make different trade-offs in the DSL design space.
Sunroof uses monadic reification to enable bindings in the DSL to be translated into
bindings in JavaScript, while blank canvas has every binding make a round trip from Haskell, to JavaScript,
back to Haskell.
In this talk, we will present the specifics of both DSLs, using examples, then use both DSLs to outline the
difference choices available when designing and implementing embedded DSLs in Haskell.














