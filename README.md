# Structure-in-C
A structure is a keyword that creates user-defined data types in C/C++. A structure creates a data type that can be used to group items of possibly different types into a single type. 
## How to create a structure? 
‘struct’ keyword is used to create a structure.
## How to declare structure variables? 
A structure variable can either be declared with structure declaration or as a separate declaration like basic types. 
>// A variable declaration with structure declaration.  
>struct Point
>{  
>   int x, y;  
>} p1;  // The variable p1 is declared with 'Point'  
>
>// A variable declaration like basic data types  
>struct Point  
>{  
>   int x, y;  
>};  
>int main()  
>{  
>   struct Point p1;  // The variable p1 is declared like a normal variable  
>}
