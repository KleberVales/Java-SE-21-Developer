# Java SE 21 Developer

## Chapter 1: Building blocks

### Learning About the Environment

1. Major Components of Java
2. Downloading a JDK

### Understanding the Class Structure

1. Fields and Methods
2. Classes and Source Files

### Writing a main() Method

1. Creating a main() Method
2. Passing Parameters to a Java Program

### Understanding Package Declarations and Imports

1. Packages
2. Wildcards
3. Redundant Imports
4. Naming Conflicts
5. Creating a New Package
6. Compiling and Running Code with Packages
7. Compiling to Another Directory
8. Ordering Elements in a Class

### Creating Objects

1. Calling Constructors
2. Reading and Writing Member Fields
3. Executing Instance Initializer Blocks
4. Following the Order of Initialization

### Understanding Data Types

1. Using Primitive Types
2. The Primitive Types
3. Writing Literals
4. Literals and the Underscore Character
5. Using Reference Types
6. Distinguishing Between Primitives and Reference Types
7. Creating Wrapper Classes
8. Defining Text Blocks

### Declaring Variables

1. Identifying Identifiers
2. Declaring Multiple Variables

### Initializing Variables

1. Creating Local Variables
2. Final Local Variables
3. Uninitialized Local Variables
4. Passing Constructor and Method Parameters
5. Defining Instance and Class Variables
6. Inferring the Type with var
7. Type Inference of var

### Managing Variable Scope

1. Limiting Scope
2. Tracing Scope
3. Applying Scope to Classes
4. Reviewing Scope

### Destroying Objects

1. Understanding Garbage Collection
2. Tracing Eligibility

## Chapter 2: Operators

### Understanding Java Operators

1. Types of Operators
2. Operator Precedence

### Applying Unary Operators

1. Complement and Negation Operators
2. Increment and Decrement Operators

### Working with Binary Arithmetic Operators

1. Arithmetic Operators
2. Adding Parentheses
3. Changing the Order of Operation
4. Verifying Parentheses Syntax
5. Division and Modulus Operators
6. Numeric Promotion

### Assigning Values

1. Assignment Operator
2. Casting Values
3. Reviewing Primitive Assignments
4. Applying Casting
5. Casting Values vs. Variables
6. Compound Assignment Operators
7. Return Value of Assignment Operators

### Comparing Values

1. Equality Operators
2. Relational Operators
3. Logical Operators
4. Bitwise Operators
5. Conditional Operators

### Making Decisions with the Ternary Operator

## Chapter 3: Making Decisions

### Creating Decision-Making Statements

1. Statements and Blocks
2. The if Statement
3. The else Statement
4. Shortening Code with Pattern Matching

### Building switch Statements and Expressions

1. Introducing switch
2. Structuring switch Statements and Expressions
3. Selecting the switch Variable
4. Determining Acceptable Case Values
5. Working with switch Statements
6. Working with switch Expressions
7. Returning Consistent Data Types
8. Exhausting the switch Branches
9. Using the yield Statement
10. Using Pattern Matching with switch
11. Ordering switch Branches
12. Exhaustive switch Statements
13. Handling a null Case

### Writing while Loops

1. The while Statement
2. The do/while Statement
3. Infinite Loops

### Constructing for Loops

1. The for Loop
2. Printing Elements in Reverse
3. Working with for Loops
4. The for-each Loop

### Controlling Flow with Branching

1. Nested Loops
2. Adding Optional Labels
3. The break Statement
4. The continue Statement
5. The return Statement
6. Unreachable Code
7. Reviewing Branching

## Chapter 4: Core APIs

### Creating and Manipulating Strings

1. Concatenating
2. Important String Methods
3. Determining the Length
4. Getting a Single Character
5. Working with Code Points
6. Getting a Substring
7. Finding an Index
8. Adjusting Case
9. Checking for Equality
10. Searching for Substrings
11. Replacing Values
12. Removing Whitespace
13. Working with Indentation
14. Checking for Empty or Blank Strings
15. Formatting Values
16. Method Chaining

### Using the StringBuilder Class

1. Mutability and Chaining
2. Creating a StringBuilder
3. Important StringBuilder Methods
4. Using Common Methods
5. Appending Values
6. Applying Code Points
7. Inserting Data
8. Deleting Contents
9. Replacing Portions
10. Reversing

### Understanding Equality

1. Comparing equals() and ==
2. The String Pool

### Understanding Arrays

1. Creating an Array of Primitives
2. Creating an Array with Reference Variables
3. Using an Array
4. Sorting
5. Searching
6. Comparing
7. Using equals()
8. Using compare()
9. Using mismatch()
10. Using Methods with Varargs
11. Working with Arrays of Arrays
12. Creating an Array of Arrays
13. Using an Array of Arrays

### Calculating with Math APIs

1. Finding the Minimum and Maximum
2. Rounding Numbers
3. Determining the Ceiling and Floor
4. Calculating Exponents
5. Generating Random Numbers
6. Using BigInteger and BigDecimal

### Working with Dates and Times

1. Creating Dates and Times
2. Manipulating Dates and Times
3. Working with Periods
4. Working with Durations
5. Working with Instants
6. Accounting for Daylight Saving Time

## Chapter 5: Methods

### Designing Methods

1. Access Modifiers
2. Optional Specifiers
3. Return Type
4. Method Name
5. Parameter List
6. Method Signature
7. Exception List
8. Method Body
   
### Declaring Local and Instance Variables

1. Local Variable Modifiers
2. Effectively Final Variables
3. Instance Variable Modifiers
   
### Working with Varargs

1. Creating Methods with Varargs
2. Calling Methods with Varargs
3. Accessing Elements of a Vararg
4. Using Varargs with Other Method Parameters
   
### Applying Access Modifiers

1. Private Access
2. Package Access
3. Protected Access
4. Public Access
   
### Accessing Static Data

1. Designing Static Methods and Variables
2. Accessing a Static Variable or Method
3. Class vs. Instance Membership
4. Static Variable Modifiers
5. Static Initializers
6. Static Imports
   
### Passing Data among Methods

1. Passing Objects
2. Returning Objects
3. Autoboxing and Unboxing Variables
   
### Overloading Methods

1. Reference Types
2. Primitives
3. Autoboxing
4. Arrays
5. Varargs
6. Putting It All Together

## Chapter 6: Class Design

### Understanding Inheritance

1. Declaring a Subclass
2. Class Modifiers
3. Single vs. Multiple Inheritance
4. Inheriting Object
   
### Creating Classes

1. Extending a Class
2. Applying Class Access Modifiers
3. Accessing the this Reference
4. Calling the super Reference
   
### Declaring Constructors

1. Creating a Constructor
2. The Default Constructor
3. Calling Overloaded Constructors with this()
4. Calling Parent Constructors with super()
5. Understanding Compiler Enhancements
6. Default Constructor Tips and Tricks
   
### Initializing Objects

1. Initializing Classes
2. Initialize Class X
3. Initializing final Fields
4. Initializing Instances
   
### Inheriting Members

1. Overriding a Method
2. Rule #1: Method Signatures
3. Rule #2: Access Modifiers
4. Rule #3: Checked Exceptions
5. Rule #4: Covariant Return Types
6. Redeclaring private Methods
7. Hiding Static Methods
8. Hiding Variables
9. Writing final Methods
   
### Creating Abstract Classes

1. Introducing Abstract Classes
2. Declaring Abstract Methods
3. Creating a Concrete Class
4. Creating Constructors in Abstract Classes
5. Spotting Invalid Declarations
6. abstract and final Modifiers
7. abstract and private Modifiers
8. abstract and static Modifiers
   
### Creating Immutable Objects

1. Declaring an Immutable Class
2. Performing a Defensive Copy


## Chapter 7: Beyond Classes

### Implementing Interfaces
### Working with Enums
### Sealing Classes
### Encapsulating Data with Records
### Creating Nested Classes
### Understanding Polymorphism

## Chapter 8: Lambdas and Functional Interfaces

### Writing Simple Lambdas
### Coding Functional Interfaces
### Using Method References
### Working with Built-in Functional Interfaces
### Working with Variables in Lambdas

## Chapter 9: Collections and Generics

### Using Common Collection APIs
### Using the List Interface
### Using the Set Interface
### Using the Queue and Deque Interfaces
### Using the Map Interface
### Sorting Data
### Introducing Sequenced Collections
### Reviewing Collection Types
### Working with Generics

## Chapter 10: Streams

### Returning an Optional
### Using Streams
### Working with Primitive Streams
### Working with Advanced Stream Pipeline Concepts

## Chapter 11: Exceptions and Localization

### Understanding Exceptions
### Recognizing Exception Classes
### Handling Exceptions
### Automating Resource Management
### Formatting Values
### Supporting Internationalization and Localization
### Loading Properties with Resource Bundles

## Chapter 12: Modules

### Introducing Modules
### Creating and Running a Modular Program
### Updating Our Example for Multiple Modules
### Diving into the Module Declaration
### Creating a Service
### Discovering Modules
### Comparing Types of Modules
### Migrating an Application

## Chapter 13: Concurrency

### Introducing Threads
### Creating Threads with the Concurrency API
### Writing Thread-Safe Code
### Using Concurrent Collections
### Identifying Threading Problems
### Working with Parallel Streams

## Chapter 14: I/O

### Referencing Files and Directories
### Operating on File and Path
### Introducing I/O Streams
### Reading and Writing Files
### Serializing Data
### Interacting with Users
### Working with Advanced APIs
### Review of Key APIs








