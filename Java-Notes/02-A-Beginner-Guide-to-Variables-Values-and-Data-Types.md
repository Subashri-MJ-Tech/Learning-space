# Variables, Values, and Data Types in Programming: A Beginner's Complete Guide

Welcome to my Java & Programming learning space! In this guide, we will break down the fundamental building blocks of programming: Variables, Values, and Data Types.

---

## 1.Variable:

1️⃣ Definition:
            ⁜ Variable is the labeled storage box inside a computer memory.
            ⁜ It is used to store values/data.
            ⁜ It is defined as an alphabet which is used to store a value.
            ⁜ The alphabet must in lowercase,because uppercase is called constant.So,we use lowercase.
            ⁜ It cannot start with a number.
  2️⃣ Rules:
     ⁂Each and every variable must be start with alphabet (lowercase).
               Syntax:
                     Variable name=Value;
                Example:
                      a=100;// a->variable,100->integer value.
                      s=11;//s->variable,11->integer value.
                      a2=123;//a2->variable,123->integer value.
                      3a=56;//Invalid declaration.(because it start with number.as per rule variable must start with alphabets).

  ✨ c=a+b;(logic)✨
    variables:c,a,b
    value:a=11,b=5(we assign it)

  ⁂Each and every variable must be separated by commas(,).
           varname1,varname2,.....varnamen;
           a,b,c;->Valid declaration.

  ⁂ No white and blank space are allowed.
         Example:
                 a b c->invalid declaration.
                  (Reason:white space appears)

  ⁂Underscore(_) and dollar($) symbol are the two special characters to be allowed in java during the variable declaration.
             ( _,$ )->only allowed in java.
          Example:
              (Valid)🌟
                     a="hansi";->valid
                      _a=27;->valid
                     a_b=43;->valid
                     $b=128;->valid
                     $total_price=100;->valid
               (Invalid)🌟
                       1st_name="guru";->invalid (it start with number).
                       my-age=20;->invalid (do not use any special characters except ( _,$ ).
                       total amount=30;->invalid (no white space allowed).

📌[These special characters( _ ,$ ) are used at front,back,and middle of the variable.]
📝(Note:Other Programming Languages may use different symbols for example,python only allows underscore( _ )).

   ⁂At the end of the variable declaration or a statement must be end with semicolon (;).
           a,b,c;->valid
          x,y,z->error statement (;) missing.

 3️⃣ Syntax:
       In Java,you can declare variables in two ways depending on your needs:
           1.Single Variable Declaration:
              Use this when you want to create a single variable and assign a value to it.
                    datatype variablename = value;
                             Example:
                                  int age = 20;
                                  string name = "Hansi";
             2.Syntax for Multiple Variable Declaration:
                   Use this when you want to declare multiple variables of the same data type in a single line.
                          datatype varname1,varname2,.........varnamen;
                              Example:
                                      int a,b,c;


## 2.Value:

  1️⃣Definition:
        1.In Programming,a value is the actual piece of data or information stored inside a variable.
        2.A Variable is a named container/box.A Value is the actual content placed inside that box.
        3.A Value is used to assign to a variable.
                     Example:
                         stdname="Hansi"; // "Hansi" is the value,"stdname" is variable
                          age=20; // "20" is the value,"age" is variable

  2️⃣Types of  Values:
             1.Numeric Value (Integer Value)
             2.String Value
             3.Real Value (Floating-Point Value)
             4.Character Value
             5.Boolean Value
 1.Numeric/Integer Value:
       A Numeric Value(or integer) represents whole numbers without any fractional or decimal parts.It can be either positive,negative, or zero.
                 Example:
                           let count = 27; ->Valid
                           let temperature = -11; ->Valid
                           let absent = 0; ->Invalid
                           num = 272.12; ->Invalid
2.Stirng Value:
        A String Value represents a sequence or text of characters (words,sentences,or paragraphs) enclosed inside double quotes(" ").
                 Example:
                          let topicname = "Variables and Values";
                          let greeting = "Welcome to my Blog!";
3.Real/Floating-point Value:
         A Real / Floating-point Value represents number that contain fractional parts or decimal points.
                  Example:
                          let price = 499.50;
                          let pi = 3.14159;
 4.Character Value:
           A Character Value represents a single letter,digit,symbol,or space.It is usually enclosed in single quotes(' ').
                Example:
                        let grade = 'A' ;
 5.Boolean Value:
           A Boolean Value represents a logical state that can only be either (True) or (False).
                 Example:
                         let isLoggedIn = true;
                         let hasPassed = false;

## 3.Data Types:

📌Note: Values and Data Types are Almost the Same!
If you feel that Values and Data Types sound identical,you are absolutely right! In programming, they are two sides of the same coin.

⁑Value is the actual data stored inside a variable (e.g.,11,"Suba",true).
⁑Data Types is simply the category or label given to that values so the computer knows how to handle it (e.g.,Integer,String,Boolean). 

   Example:
         let score = 100;
            //Variable Name: score
            //Value: 100
            //Data Type: Integer/Numeric

So,whenever you assigning a Value to variable, you are automatically defining its Data Type!

📝✨A Simple Thought Example From My Mind:
  When I was thinking about how to explain this simply to my friend,a fun real-life example crossed in my mind....
       Imagine a Water Bottle:
                       ⁑The Bottle is the Variable (the container).
                       ⁑The Liquid inside is the Value (the actual content).
                       ⁑What Kind of Liquid it is (Normal Water,Soft Drink,or Fruit Juice)is the Data Type!

📌💡The Shortest Way to Remember:
                        Value is WHAT data you have.
                        Data Type is WHAT KIND of data it is.
                                        ---

> **Note:** Understanding these three concepts is essential before writing complex code in Java or any other language!
