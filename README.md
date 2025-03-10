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

1. Declaring and Using an Interface
2. Extending an Interface
3. Inheriting an Interface
4. Mixing Class and Interface Keywords
5. Inheriting Duplicate Abstract Methods
6. Inserting Implicit Modifiers
7. Conflicting Modifiers
8. Differences between Interfaces and Abstract Classes
9. Declaring Concrete Interface Methods
10. Writing a default Interface Method
11. Inheriting Duplicate default Methods
12. Calling a default Method
13. Declaring static Interface Methods
14. Reusing Code with private Interface Methods
15. Reviewing Interface Members
   
### Working with Enums

1. Creating Simple Enums
2. Calling Common Enum Methods
3. Using Enums in switch Statements
4. Working with Complex Enums
5. Creating Enum Variables
6. Declaring Enum Constructors
7. Writing Enum Methods
   
### Sealing Classes

1. Declaring a Sealed Class
2. Compiling Sealed Classes
3. Specifying the Subclass Modifier
4. Creating final Subclasses
5. Creating sealed Subclasses
6. Creating non-sealed Subclasses
7. Omitting the permits Clause
8. Sealing Interfaces
9. Applying Pattern Matching to a Sealed Class
   
### Encapsulating Data with Records

1. Understanding Encapsulation
2. Applying Records
3. Declaring Constructors
4. The Long Constructor
5. Compact Constructors
6. Transforming Parameters
7. Overloaded Constructors
8. Understanding Record Immutability
9. Using Pattern Matching with Records
10. Matching Records
11. Nesting Record Patterns
12. Matching Records with var and Generics
13. Applying Pattern Matching Records to Switch
14. Customizing Records
   
### Creating Nested Classes

1. Declaring an Inner Class
2. Instantiating an Instance of an Inner Class
3. Referencing Members of an Inner Class
4. Creating a static Nested Class
5. Writing a Local Class
6. Defining an Anonymous Class
7. Reviewing Nested Classes

### Understanding Polymorphism

1. Object vs. Reference
2. Casting Objects
3. Disallowed Casts
4. Casting Interfaces
5. The instanceof Operator
6. Polymorphism and Method Overriding
7. Overriding vs. Hiding Members

## Chapter 8: Lambdas and Functional Interfaces 

### Writing Simple Lambdas

1. Looking at a Lambda Example
2. Learning Lambda Syntax
   
### Coding Functional Interfaces

1. Defining a Functional Interface
2. Adding Object Methods

### Using Method References

1. Calling static Methods
2. Calling Instance Methods on a Particular Object
3. Calling Instance Methods on a Parameter
4. Calling Constructors
5. Reviewing Method References
   
### Working with Built-in Functional Interfaces

1. Implementing Supplier
2. Implementing Consumer and BiConsumer
3. Implementing Predicate and BiPredicate
4. Implementing Function and BiFunction
5. Implementing UnaryOperator and BinaryOperator
6. Checking Functional Interfaces
7. Using Convenience Methods on Functional Interfaces
8. Learning the Functional Interfaces for Primitives
9. Functional Interfaces for boolean
10. Functional Interfaces for double, int, and long
    
### Working with Variables in Lambdas

1. Listing Parameters
2. Using Local Variables Inside a Lambda Body
3. Referencing Variables from the Lambda Body

## Chapter 9: Collections and Generics

### Using Common Collection APIs

1. Understanding Generic Types
2. Shortening Generics Code
3. Applying the Diamond Operator
4. Applying var
5. Adding Data
6. Removing Data
7. Counting Elements
8. Clearing the Collection
9. Checking Contents
10. Removing with Conditions
11. Iterating on a Collection
12. Determining Equality
   
### Using the List Interface

1. Comparing List Implementations
2. Creating a List with a Factory
3. Creating a List with a Constructor
4. Working with List Methods
5. Searching a List
6. Converting from List to an Array
   
### Using the Set Interface

1. Comparing Set Implementations
2. Working with Set Methods
   
### Using the Queue and Deque Interfaces

1. Comparing Deque Implementations
2. Working with Queue and Deque Methods
   
### Using the Map Interface

1. Comparing Map Implementations
2. Working with Map Methods
3. Calling Basic Methods
4. Iterating through a Map
5. Getting Values Safely
6. Replacing Values
7. Putting If Absent
8. Merging Data
   
### Sorting Data

1. Creating a Comparable Class
2. Designing a compareTo() method
3. Casting the compareTo() Argument
4. Checking for null
5. Keeping compareTo() and equals() Consistent
6. Comparing Data with a Comparator
7. Comparing Comparable and Comparator
8. Comparing Multiple Fields
9. Sorting and Searching
10. Sorting a List
    
### Introducing Sequenced Collections

1. Working with SequencedCollection
2. Working with SequencedMap
   
### Reviewing Collection Types

1. Using Unmodifiable Wrapper Views
2. Comparing Collection Types
   
### Working with Generics

1. Creating Generic Classes
2. Understanding Type Erasure
3. Overloading a Generic Method
4. Returning Generic Types
5. Implementing Generic Interfaces
6. Writing Generic Methods
7. Creating a Generic Record
8. Bounding Generic Types
9. Creating Unbounded Wildcards
10. Creating Upper-Bounded Wildcards
11. Creating Lower-Bounded Wildcards
12. Putting It All Together
13. Combining Generic Declarations
14. Passing Generic Arguments

## Chapter 10: Streams

### Returning an Optional

1. Creating an Optional
2. Dealing with an Empty Optional
   
### Using Streams

1. Understanding the Pipeline Flow
2. Creating Stream Sources
3. Creating Finite Streams
4. Creating Infinite Streams
5. Reviewing Stream Creation Methods
6. Using Common Terminal Operations
7. Counting
8. Finding the Minimum and Maximum
9. Finding a Value
10. Matching
11. Iterating
12. Reducing
13. Collecting
14. Using Common Intermediate Operations
15. Filtering
16. Removing Duplicates
17. Restricting by Position
18. Mapping
19. Using flatMap
20. Sorting
21. Taking a Peek
22. Putting Together the Pipeline
    
### Working with Primitive Streams

1. Creating Primitive Streams
2. Mapping Streams
3. Using Optional with Primitive Streams
4. Summarizing Statistics
   
### Working with Advanced Stream Pipeline Concepts

1. Linking Streams to the Underlying Data
2. Chaining Optionals
3. Collecting Results
4. Using Basic Collectors
5. Collecting into Maps
6. Grouping, Partitioning, and Mapping
7. Teeing Collectors
8. Using a Spliterator

## Chapter 11: Exceptions and Localization

### Understanding Exceptions

1. The Role of Exceptions
2. Understanding Exception Types
3. Checked Exceptions
4. Unchecked Exceptions
5. Error and Throwable
6. Reviewing Exception Types
7. Throwing an Exception
8. Calling Methods That Throw Exceptions
9. Overriding Methods with Exceptions
10. Printing an Exception
   
### Recognizing Exception Classes

1. RuntimeException Classes
2. ArithmeticException
3. ArrayIndexOutOfBoundsException
4. ClassCastException
5. NullPointerException
6. IllegalArgumentException
7. NumberFormatException
8. Checked Exception Classes
9. Error Classes
    
### Handling Exceptions

1. Using try and catch Statements
2. Chaining catch Blocks
3. Applying a Multi-catch Block
4. Adding a finally Block
   
### Automating Resource Management

1. Introducing Try-with-Resources
2. Basics of Try-with-Resources
3. Constructing Try-with-Resources Statements
4. Declaring Resources
5. Scope of Try-with-Resources
6. Following Order of Operations
7. Applying Effectively Final
8. Understanding Suppressed Exceptions
   
### Formatting Values

1. Formatting Numbers
2. Formatting Dates and Times
3. Customizing the Date/Time Format
4. Learning the Standard Date/Time Symbols
5. Selecting a format() Method
6. Adding Custom Text Values
   
### Supporting Internationalization and Localization

1. Picking a Locale
2. Localizing Numbers
3. Formatting Numbers
4. Parsing Numbers
5. Formatting with CompactNumberFormat
6. Localizing Dates
7. Specifying a Locale Category
   
### Loading Properties with Resource Bundles

1. Creating a Resource Bundle
2. Picking a Resource Bundle
3. Selecting Resource Bundle Values
4. Formatting Messages
5. Using the Properties Class

## Chapter 12: Modules

### Introducing Modules

1. Exploring a Module
2. Benefits of Modules
   
### Creating and Running a Modular Program

1. Creating the Files
2. Compiling Our First Module
3. Running Our First Module
4. Packaging Our First Module
5. Updating Our Example for Multiple Modules
    
### Updating Our Example for Multiple Modules

1. Updating the Feeding Module
2. Creating a Care Module
3. Creating the Talks Module
4. Creating the Staff Module

### Diving into the Module Declaration

1. Exporting a Package
2. Requiring a Module Transitively
3. Effects of requires transitive
4. Duplicate requires Statements
5. Opening a Package
   
### Creating a Service

1. Declaring the Service Provider Interface
2. Creating a Service Locator
3. Invoking from a Consumer
4. Adding a Service Provider
5. Reviewing Directives and Services
   
### Discovering Modules

1. Identifying Built-in Modules
2. Getting Details with java
3. Describing a Module
4. Listing Available Modules
5. Showing Module Resolution
6. Describing with jar
7. Learning About Dependencies with jdeps
8. Using the --jdk-internals Flag
9. Using Module Files with jmod
10. Creating Java Runtime Images with jlink
11. Creating Self-Contained Java Applications with jpackage
12. Reviewing Command-Line Options

### Comparing Types of Modules

1. Named Modules
2. Automatic Modules
3. Unnamed Modules
4. Reviewing Module Types
   
### Migrating an Application

1. Determining the Order
2. Exploring a Bottom-Up Migration Strategy
3. Exploring a Top-Down Migration Strategy
4. Splitting a Big Project into Modules
5. Failing to Compile with a Cyclic Dependency

## Chapter 13: Concurrency

### Introducing Threads

1. Comparing to Virtual Threads
2. Understanding Thread Concurrency
3. Creating a Thread
4. Working with Daemon Threads
5. Managing a Thread’s Life Cycle
6. Reviewing Thread Concepts
   
### Creating Threads with the Concurrency API

1. Introducing the Single-Thread Executor
2. Submitting Tasks
3. Waiting for Results
4. Investigating Callable
5. Shutting Down a Thread Executor
6. Scheduling Tasks
7. Increasing Concurrency with Pools
   
### Writing Thread-Safe Code

1. Understanding Thread-Safety
2. Protecting Data with Atomic Classes
3. Improving Access with synchronized Blocks
4. Synchronizing Methods
5. Understanding the Lock Framework
6. Applying a ReentrantLock
7. Attempting to Acquire a Lock
8. Acquiring the Same Lock Twice
9. Reviewing the Lock Framework
10. Orchestrating Tasks with a CyclicBarrier
    
### Using Concurrent Collections

1. Understanding Memory Consistency Errors
2. Working with Concurrent Classes
3. Obtaining Synchronized Collections
   
### Identifying Threading Problems

1. Understanding Liveness
2. Deadlock
3. Starvation
4. Livelock
5. Managing Race Conditions
   
### Working with Parallel Streams

1. Creating Parallel Streams
2. Performing a Parallel Decomposition

## Chapter 14: I/O

### Referencing Files and Directories
### Operating on File and Path
### Introducing I/O Streams
### Reading and Writing Files
### Serializing Data
### Interacting with Users
### Working with Advanced APIs
### Review of Key APIs








