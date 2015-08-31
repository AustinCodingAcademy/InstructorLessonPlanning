#ACA Objectives Document

##Front End Intro
+ HTML page structure elements
    - `<!DOCTYPE>` Declaration
    - `<html></html>` tags
    - `<heading></heading>` tags
    - `<title></title>` tags
    - `<body></body>` tags
    - `<h1>` to `<h6>` heading tags
    - `<p></p>`  paragraph tags
    - `<a></a>` link tags
        - href attribute
    - `<img>` image tags
        - src attribute
        - size attributes (width and height)
        - alt attribute
    - `<hr>` tag
    - `<br>` tag
    - lists 
        - `<ol>` ordered list element
        - `<ul>` unordered list element
        - `<menu>` menu element
    - formatting elements
        - `<b></b>` bold text
        - `<strong></strong>` important text
        - `<i></i>` italic text
        - `<em></em>` emphasized text
        - `<mark></mark>` marked (highlighted) text
        - `<small></small>` small text
        - `<del></del>` deleted (line through) text
        - `<ins></ins>` inserted (underlines) text
        - `<blockquote></blockquote>` long quotes
    - form syntax
+ Ways to implement CSS and the pros and cons of each
    - Within elements of HTML page
    - In the header of the HTML file
        - `<style>` elements
    - In an external CSS file
        - `<link rel="stylesheet" href="css/my-style.css">`
+ CSS properties
    - Box Model Properties
        - Offset
        - Padding
        - Margin
        - Dimensions (width and height)
        - Border
    - Breaking the normal document flow
        - Floats (Left and right)        
    - Reinstating normal document flow 
        - Clearing Floats (Left, right, and both)
        - Use of Clear Fix
+ Typography:
    - Font-family
    - Font-size
    - Font-weight
    - Line height
+ Units of Measurement (px, %)
+ CSS selectors:
    - `.class`
    - `#id`
    - Native HTML Tags
+ Selective Precedence within CSS selectors
+ Media Queries
+ Bootstrap
    - Grid classes (xs, sm, md, and lg)
    - Grid system concepts
        - `.container`
        - `.container-fluid`
        - `.row`
        - `.col`
    - Responsive utilities in Bootstrap
    - Navbar components
        



##Front End Intermediate
+ Primitives
    - Boolean
    - Null
    - Number
    - String
    - Symbol
    - Undefined
+ Variables
    - var
    - let
    - const
+ JS Tools
    - Node.js
    - NPM
    - Gulp
    - Babel
+ Logging Output
+ Conditionals and Comparisons: 
    - If/else
    - Switch 
    - Logical Operators
    - Making comparisons
+ Objects
+ Arrays
+ Maps
+ Sets 
    - Mutability
+ Loops: 
    - For
    - While
+ Functions
+ Classes and Objects
+ Bugs and Error Handling 
    - Strict Mode
    - Testing
    - Debugging
+ Regular Expressions
+ Manipulating the DOM 
    - Getting Elements
    - Creating Elements
    - Traversing the DOM
+ Events
+ Angular



##Back End Intro
+ Variables
    - Assignment
    - Assignments as expressions
    - Naming conventions
+ Strings
    - Relevant functions
        - `strlen()`
        - `empty()`
        - `strpos()`
        - `str_replace()`
        - `substr()`
+ Arrays
    - Nested Arrays
    - Keys
    - Iteration
    - Relevant functions
        - `count()`
        - `isset()`
        - `array_sum()`
        - `array_key_exists()`
        - `array_keys()`
        - `array_values()`
        - `implode()`
        - `explode()`
+ Operators
    - Arithmetic
        - `+`  addition 
        - `++` incrementing up by 1 each time
        - `-`  subtraction
        - `--` incrementing down by 1 each time
        - `*`  multiplication
        - `/`  division
        - `%`  modulus (remainder from division)
    - Concatenation    
    - Relational
        - `==`  equal to
        - `!=`  not equal to
        - `>=`  greater than or equal to
        - `<=`  less than or equal to
        - `>`  greater than 
        - `<` less than
    - Logical 
        - `&&`  -  AND
        - `||`  -  OR
        - `!`  -  NOT
+ If and if/else statements
    - DeMorgan's Laws
+ Values
    * Primitive data types
        - int
        - float
        - string
        - boolean
        - NULL
    * Statements vs Expressions
+ Typecasting
    - truncation
+ Loops
    - for
    - foreach
    - while
    - do...while
    - break and continue keywords
    - infinite loops
+ Debugging
    - Dissecting error messages
    - Manually stepping through source
    - Print debugging
    - Relevant functions
        - `exit()`
        - `die()`
        - `gettype()`
        - `print_r()`
+ Functions
    - Principles of software design
        - Code reuse
        - Encapsulation
        - Testability
    - Parameters
    - Arguments
    - `return` statement
    - By value vs by reference
    - Scope
    - 3rd party library functions
+ Files
    - The need for data persistence
    - Absolute vs Relative paths
    - File modes
        - read
        - write
        - append
    - Handles/Resources
        - Connections
        - Iteration
        - Closing
    - Custom formats
    - Relevant functions
        - `file_put_contents()`
        - `file_get_contents()`
        - `file_exists()`
+ Serialization
    - The need for serialization
    - PHP serialization
        - Saving serialized data to files
        - Reading serialized data from files and converting
        - Understand limitations
    - JSON serialization
        - Portability
        - Use in APIs
    - Relevant functions
        - `serialize()`
        - `unserialize()`
        - `json_encode()`
        - `json_decode()`
+ Misc Functions:
    - `phpinfo()`
    - `rand()`
+ HTML/CSS
    - Basic elements
        - `<html>`
        - `<head>`
        - `<title>`
        - `<body>`
        - `<h1>`, `<h2>`, ...
        - `<p>`
        - `<em>`
        - `<strong>`
        - `<img>`
        - `<ul>`
        - `<ol>`
        - `<a>`
    - Styles
        - Basic CSS selectors
        - Basic CSS properties
        - Elements used for sectioning
            - `<div>` tags
            - `<span>` tags
        - ids
        - classes
        - Spacing and layout
        - Padding
        - Margin
        - Border
        - Background
    - Forms
        - GET vs POST requests
        - Relationship between forms and the browser
            - HTTP requests built from form data
        - Form elements
            - `<form>`
            - `<input>`
                - text
                - password
                - submit
                - radio
                - checkbox
            - `<textarea>`
            - `<select>`
            - `<option>`
        - Accessing form values via PHP's `$_GET` and `$_POST`
+ HTTP
    - The HTTP protocol
        - Host
        - Protocol
        - Requested resource
        - Method
        - Data
    - Status codes
    - Relationship with the browser
    - Performing HTTP Requests with PHP
    - Interaction with JSON APIs
    - Session management
        - Understanding state
            - HTTP is stateless
        - Sessions
        - Cookies
+ Basics of web application development
    - Users
        - Authentication
            - Password management
        - Authorization
    - Creating a local JSON data store
        - Understand limitations and the need for a database
    - Firebase integration
    - JavaScript crash course
        - The DOM
        - Including JavaScript files
        - JS console
        - Declaring varibles
        - Data types
        - Declaring functions
            - Anonymous functions
        - jQuery
            - Document ready
            - Selectors
            - Basic DOM manipulation
            - AJAX
                - Understanding the relationship between JS and PHP via AJAX
                - Callbacks

##Back End Intermediate 
+ HTML
+ Syntax
    - PHP tags
    - Comments
    - Debug using die
+ Variables
+ Data types and loose typing
+ Typecasting
+ Operators
+ Control Structures
    - If-else
    - Nested conditional
    - Switch-case
    - For loop
    - Foreach loop
    - While loop
+ Strings
    - Creating a string
    - Concatenating two strings
    - Escaping literal values
    - Referencing individual characters using array notation
+ Functions
    - Creating a function
    - Returning values
    - Distinction between ‘by value’ and ‘by reference” arguments
    - Documenting functions using DocBlock
    - Variable scope within a function
+ Arrays
    - Creating an array
    - Basic array operations
        - (referencing, adding, removing, replacing, values)
        - Utilizing built in array functions
    - Looping through an array
    - Creating a hash table for fast index lookups
    - Sorting Arrays
+ Scaffolding using Bootstrap
+ Adding style using CSS
+ Dynamic behavior using the power of javascript and jQuery
+ Collecting user input using forms
    - Text, textarea, radio, checkbox, select, a file use
+ Making AJAX call
+ Sessions
+ Fundamentals of Object Oriented Programming
    - Defining a class
    - Instantiating an object
    - Inheritance
+ Classes
    - Constructors
    - Visibility
        - Public, Protected, Private
+ Class Constants
+ Static Methods and Properties
+ Visibility and Encapsulation
+ Abstract Classes
+ Interfaces
+ Design Patterns
    - Factory
    - Singleton
    - Front Controller
    - Model View Controller
    - Dependency Injection
+ MySQL Fundamentals
    - Terminology
    - Create tables
    - Inserting records
    - Selecting records
    - Simple queries
    - Aggregate queries
    - Joins
    - Modifying tables
    - Updating values in tables
    - Remove existing field from table
    - Select specific fields
+ Installation and use of Symfony
    - Create bundles
    - Routing
    - Controllers
    - Templating
    - PSR-4 autoloading
    - Namespaces
    - Dependency Injection
        -Service Container











