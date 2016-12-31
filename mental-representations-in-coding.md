#Mental Representations in Coding

##Statements.

Not everyone can easily tell where a statement starts and ends. Statements are like those puzzles where you have a triangle cut into a bunch of triangles and they ask you how many triangles there are.  

![Recognizing Triangles](./res/trianglethinker.jpg)
In the image above, it can be hard to ascertain how many triangles there are and a student may be unsure of their answer unless they have a mental representation of how to solve the problem and recognize triangles within the image. Such an algorithm may be seen here. Statements are the same, they are composable and many statements contain sub-statements. Students often have a very hard time understanding where a statement really ends. A good heuristic to give them is that if you introduce a cut at some point in the statement and you look at the sub-statement to the left and then at the one to the right, and if one or both of them become invalid after being cut (with a semicolon for instance) then you cannot consider the two separate statements. In order to decide where a statement starts and ends, then, you can try these cuts from the first character to the last until you find a place where the cut does create two statements.

Examples of where students trip when recognizing statements:
  1. Callback nesting - it's confusing to see how a jquery ajax call is just one statement containing a big function.
  2. Multi-line strings.
  3. Angular expressions and promises with dot-chaining long statements.


##Primitive values

##Reference Values
  1. Methods/properties - reference values are complex and can have properties
  2. Prototypes/types - ie different kinds of reference values have different properties

##Functions
  1. Functions that just run code
  2. Functions that take input (parameters)
  3. Functions that return a value (input-output)

##Loops - yes they are still important

##Algorithms
This is where the chunks start getting bigger. In order to be a good, fast developer, you have to carry at least a few hundred of these in your mind. This small list is not comprehensive but rather a language-agnostic list. Each language/context will have its own chunks you need to create.
  1. Find whether element exists in collection
  2. Find min/max element
  3. Find some kind of aggregation of a collection (sum, average, concatenation of array)
  4.
