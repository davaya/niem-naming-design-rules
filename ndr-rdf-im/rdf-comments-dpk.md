# NDR RDF Comments

Section 14 of [NDR Version 6](https://github.com/niemopen/niem-naming-design-rules/blob/dev/ndr6src.md),
"Interpretation of NIEM data"


**XML Objects**
>
> An XML object, in the context of XML processing, represents an element within an XML document.
> It's a fundamental part of the XML Document Object Model (DOM), which treats XML documents
> as trees of interconnected nodes. The XML object acts as an interface for accessing and
> manipulating the data and structure of the XML document.
> 
> **XML Object as a Node**:  
> The XML object represents a specific node in this tree.
> It provides access to the node's properties (like its name, value, and attributes)
> and methods for interacting with it (like adding, removing, or modifying child nodes). 

**[JavaScript Objects](https://www.w3schools.com/js/js_objects.asp)**
>
> **Objects** are containers for **Properties** and **Methods**.  
> **Properties** are named **Values**.
> **Methods** are **Functions** stored as **Properties**.  
> **Properties** can be primitive values, functions, or even other objects.
>
> In JavaScript, almost "everything" is an object.
> * Objects are objects
> * Maths are objects
> * Functions are objects
> * Dates are objects
> * Arrays are objects
> * Maps are objects
> * Sets are objects
> 
> All JavaScript values, except primitives, are objects.

**Python Objects**
> In Python, all values, including primitives, are objects.
>
> In the Python statement `x = 5`:  
> 5 is an integer object, and x is a variable that refers to this integer object.
> x does not contain the value 5; instead, it holds a reference (or memory address) to the object 5.
> This distinction is important because:
> 
> **Identity**:  
> Multiple variables can refer to the same object.
> For example, if you assign y = x, both x and y will refer to the same integer object 5.
> 
> **Mutability**:
> When you modify a mutable object (like a list or dictionary) through one variable,
> the changes are reflected when accessing the object through any other variable referring to it.
> Immutable objects (like numbers, strings, and tuples) create new objects upon modification.

**[JSON Object Literals](https://www.w3schools.com/js/js_json_objects.asp)**
>
> This is a JSON string:
>
> `'{"name":"John", "age":30, "car":null}'`
>
> Inside the JSON string there is a JSON object literal:
>
> `{"name":"John", "age":30, "car":null}`
>
> JSON object literals are surrounded by curly braces {}.
> JSON object literals contains key/value pairs.
> Keys and values are separated by a colon.
> Each key/value pair is separated by a comma.
>
> It is a common mistake to call a JSON object literal "a JSON object".
> JSON cannot be an object. JSON is a string format.
> The data is only JSON when it is in a string format.
> When it is converted to a JavaScript variable, it becomes a JavaScript object.

