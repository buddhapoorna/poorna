<html lang="en">
    <head>
      
        <title>Notes</title>
        
       <!--<link rel="stylesheets" href="notes.css">-->
       <style>
        body{
           color: rgb(15, 15, 246);
            line-height: 1.5;
            font-family: Arial, Helvetica, sans-serif;
          }
        #sidebar{
          position: fixed;
          top:0px;
          left:0px;
          width:300px;
          height:100%;
          border-right:solid;
          border-color:rgb(66, 232, 37);
          color: rgb(216, 86, 93);
        }
       </style>
    </head>
    <body>
      <h1 style="color: palevioletred;">My Notes</h1>
       <nav id="sidebar">
        <ul>
         <li>
            <a class="nav-item" href="#Introduction">Introduction</a> 
         </li>
         <li>
            <a class="nav-item" href="#chapter1">Chapter-01</a> 
         </li>
         <li>
            <a class="nav-item" href="#chapter2">Chapter-02</a> 
         </li>
         <li>
            <a class="nav-item" href="#chapter3">Chapter-03</a> 
         </li>
         <li>
            <a class="nav-item" href="#chapter4">Chapter-04</a> 
         </li>
         <li>
            <a class="nav-item" href="#chapter5">Chapter-05</a> 
         </li>
    </ul>
       </nav>
    <section id="Introduction">
        <h2>Introduction to CPP</h2>
       <p>C++ is the most used and most popular programming language developed by Bjarne Stroustrup. 
        C++ is a high-level and object-oriented programming language. 
        This language allows developers to write clean and efficient code for large applications and software development, game development, and operating system programming. 
        It is an expansion of the C programming language to include Object Oriented Programming(OOPs) and is used to develop programs for computers. 
        This C++ Tutorial will cover all the basic to advanced topics of C++ like C++ basics, C++ functions, C++ classes, OOPs and STL concepts.
      </p>


      <h3>What is c++?</h3>
      <p>
        C++ is a most popular cross-platform programming language which is used to create
         high-performance applications and software like OS, Games, E-commerce software, etc.
          It was developed by Bjarne Stroustrup, as an extension of C language.
           C++ give a high level of control over system resources and memory.
      </p>
      <h3>Why should we learn c++?</h3>
      <ul>
        <li>C++ is one of the most used and popular programming languages.</li>
        <li>C++ is used in making operating systems, embedded systems, and Graphical User Interfaces.</li>
        <li>It is an object-oriented programming language that implements all the OOPs concepts such as
             Abstraction, Encapsulation, and Inheritance, which gives a clear structure to programs and allows code to be reused,
              lowering development costs and providing security. </li>
        <li>It is portable and can be used to create applications that can be adapted to multiple platforms.</li>
        <li>C++ is easy to learn so that you can choose it as your first programming language.</li>
        <li>It makes programming easy for programmers to switch to C++ because its syntax is similar to C, Java, and C#.</li>
      </ul>
      <h2>Features of c++</h2>
      <p>C++ is a general-purpose programming language that was developed as an enhancement of the C language to 
        include an object-oriented paradigm.
         It is an imperative and compiled language. C++ has a number of features, including:</p>
      <ul>
        <li>Object-Oriented Programming</li>
        <li>Machine Independent</li>
        <li>Simple</li>
        <li>High-Level Language</li>
        <li>Popular</li>
        <li>Case-sensitive</li>
        <li>Dynamic Memory Allocation</li>
      </ul>
      <h2>History of cpp</h2>
      <p>The C++ language is an object-oriented programming language & is a combination of both low-level & high-level language –
         a Middle-Level Language. The programming language was created, designed & developed by a Danish Computer Scientist –
          Bjarne Stroustrup at Bell Telephone Laboratories (now known as Nokia Bell Labs) in Murray Hill, New Jersey.
           As he wanted a flexible & a dynamic language which was similar to C with all its features, but with additionality of active type
            checking, basic inheritance, default functioning argument, classes, inlining, etc. and hence C with Classes (C++) was launched. 
       
       C++ was initially known as “C with classes, ” and was renamed C++ in 1983.
     C++ is shorthand for adding one to variety in programming; therefore C++ roughly means that “one higher than C.” 
        
         </p>

    </body>
    </section>

    <section id="chapter1">
      
              <h2>Basics of c++</h2>
             <p>C++ is a widely used Object Oriented Programming language and is relatively easy to understand. The “Hello World” program is the first step towards learning any programming language and is also one of the most straightforward programs you will learn.</p>
             <h3>C++ Hello World Program</h3>
             <p>#include<iostream><br>
                using namespace std;<br>
                int main(){<br>
                 cout<<"Hello World!!!!";<br>
                 return 0;<br>
                 }<br>
              </p>
              </h3>Working of Hello World Program in C++</h3>
              <ul>
              <li>1. // C++ program to display “Hello World”</li>
              <p>This line is a comment line. A comment is used to display additional information about the program. A comment does not contain any programming logic.
      
      When a comment is encountered by a compiler, the compiler simply skips that line of code. Any line beginning with ‘//’ without quotes OR in between /*…*/ in C++ is a comment.</p>
              <li>2. #include</li>
              <p>This is a preprocessor directive. The #include directive tells the compiler to include the content of a file in the source code.
      
      For example, #include<iostream> tells the compiler to include the standard iostream file which contains declarations of all the standard input/output library functions</p>
              
    </section>

    <section id="chapter2">
        
        <h1>C++ Variables</h1>
        <p>Variables in C++ is a name given to a memory location. It is the basic unit of storage in a program. </p>
        <ul>
            <li>The value stored in a variable can be changed during program execution.</li>
            <li>A variable is only a name given to a memory location, all the operations done on the variable effects that memory location.</li>
            <li>In C++, all the variables must be declared before use.</li>
        </ul>
        <h2>How to Declare Variables?</h2>
        <p>A typical variable declaration is of the form:</p>
        <p>// Declaring a single variable
type variable_name;
</p><br>
<p>// Declaring multiple variables:
type variable1_name, variable2_name, variable3_name;</p>
<p>A variable name can consist of alphabets (both upper and lower case), numbers, and the underscore ‘_’ character. However, the name must not start with a number. 

</p>
<ul>
    <li>
datatype: Type of data that can be stored in this variable. </li>
<li>variable_name: Name given to the variable. </li>
<li>value: It is the initial value stored in the variable.</li>
</ul>
<h2>Examples:  </h2>
<p>// Declaring float variable
float simpleInterest;</p>
<p>// Declaring integer variable
int time, speed; </p>
<p>// Declaring character variable
char var; </p>
<p>We can also provide values while declaring the variables as given below:</p>
<ul>
    <li>int a=50,b=100;  //declaring 2 variable of integer type </li>
    <li>float f=50.8;  //declaring 1 variable of float type </li>
    <li>char c='Z';    //declaring 1 variable of char type</li>
</ul>
<h2>Rules For Declaring Variable</h2>
<ul><li>The name of the variable contains letters, digits, and underscores.</li>
<li>The name of the variable is case sensitive (ex Arr and arr both are different variables).</li>
<li>The name of the variable does not contain any whitespace and special characters (ex #,$,%,*, etc).</li>
<li>All the variable names must begin with a letter of the alphabet or an underscore(_).</li>
<li>We cannot used C++ keyword(ex float,double,class)as a variable name.</li></ul>

    </section>

    <section id="chapter3">
      <!DOCTYPE html>
      <html>
          <title>Cpp Operators</title>
          <body>
              <h2>Cpp Operators</h2>
              <p>
                  An operator is a symbol that operates on a value to perform specific mathematical or logical computations. They form the 
                  foundation of any programming language. In C++, we have built-in operators to provide the required functionality.
                  </p>
              <ul>
                  <li>Arithmetic Operators</li>
                  <li>Relational Operators</li>
                   <li>Logical Operators</li>
                   <li>  Bitwise Operators</li>
                   <li>  Assignment Operators</li>
                   <li>  Ternary or Conditional Operators</li>
              </ul>
              <h3>Arithmetic operators</h3>
              <p> 
                  These operators are used to perform arithmetic or mathematical operations on the operands.
                   For example, ‘+’ is used for addition, ‘-‘ is used for subtraction ‘*’ is used for multiplication, etc. </p>
                  <h3> Relational Operators</h3>
                  <p>These operators are used for the comparison of the values of two operands. 
                      For example, ‘>’ checks if one operand is greater than the other operand or not, etc. 
                      The result returns a Boolean value, i.e., true or false.</p>
                  <h3>Logical Operators</h3>
                  <p>These operators are used to combine two or more conditions or constraints or to complement the
                       evaluation of the original condition in consideration. The result returns a Boolean value, i.e., true or false.</p>
                  <h3>Bitwise Operators</h3>
                  <p>These operators are used to perform bit-level operations on the operands. The operators are first converted to bit-level and
                       then the calculation is performed on the operands. 
                      Mathematical operations such as addition, subtraction, multiplication, etc. can be performed at
                       the bit level for faster processing. </p> 
                  <h3>Assignment Operators</h3>
                  <p>These operators are used to assign value to a variable. The left side operand of the assignment operator is a
                       variable and the right side operand of the assignment operator is a value. The value on the right 
                      side must be of the same data type as the variable on the left side otherwise the compiler will raise an error. </p>
                  <h3>Ternary or Conditional Operators</h3>
                  <p>
                      This operator returns the value based on the condition. 
      
      <br>Expression1? Expression2: Expression3<br>
      The ternary operator ? determines the answer on the basis of the evaluation of Expression1.
       If it is true, then Expression2 gets evaluated and is used as the answer for the expression. 
       If Expression1 is false, then Expression3 gets evaluated and is used as the answer for the expression.
      
      This operator takes three operands, therefore it is known as a Ternary Operator. 
                  </p>
          </body>
      </html>
    </section>

    <section id="chapter4">
      <html>
         <head><title>Constants in C</title></head>
         <h1>Constants in C</h1>
         <p>The constants in C are the read-only variables whose values cannot be modified once they are declared in the C program. The type of constant can be an integer constant, a floating pointer constant, a string constant, or a character constant. In C language, the const keyword is used to define the constants.
         </p>
         <h2>What is a constant in C?</h2>
         <p>As the name suggests, a constant in C is a variable that cannot be modified once it is declared in the program. We can not make any change in the value of the constant variables after they are defined.</p>
         <h2>How to define a constant in C?</h2>
         <p>We define a constant in C language using the const keyword. Also known as a const type qualifier, the const keyword is placed at the start of the variable declaration to declare that variable as a constant.</p>
         <h3>Syntax to Define Constant</h3>
         const data_type var_name = value;
         <h2>Types of Constants in C</h2>
         The type of the constant is the same as the data type of the variables. Following is the list of the types of constants
         <ul>
             <li>Integer Constant</li>
             <li>Character Constant</li>
             <li>Floating Point Constant</li>
             <li>Double Precision Floating Point Constant</li>
             <li>Array Constant</li>
             <li>Structure Constant</li>
         </ul>
    </section>

    <section id="chapter5">
        
           
            integer: 89
            short: 56
            long: 4564
            float: 3.733064
            double: 8.358674532
            decimal: 389.5
            Unsinged integer: 95
            Unsinged short: 76
            Unsinged long: 3624573
              <p><strong>Example :</strong></p><div class=code-block><div class=code-gutter><div class=editor-buttons-container><div class=editor-buttons><div class=editor-buttons-div title="Run and Edit"><i id=copy-code-button title="Copy Code" class="gfg-icon gfg-icon_copy code-sidebar-button padding-2px copy-code-button"></i></p><div id=run-and-edit-loader class=ring-load></div><p><i id=run-and-edit-button title="Edit Code" lang=csharp class="gfg-icon gfg-icon_edit_1 padding-2px code-sidebar-button"></i><br><i id=close-code-editor-button title="Close Editor" class="gfg-icon gfg-icon_close-editor padding-2px code-sidebar-button close-code-editor-button"></i></p><div id=run-code-loader class=ring-load></div><p><i id=run-code-button lang=csharp title="Run Code and See Output" class="gfg-icon gfg-icon_play padding-2px code-sidebar-button"></i></p><div id=generate-url-loader class=ring-load></div><p><i id=generate-url-and-run-button title="Run Code and Generate IDE URL" lang=csharp class="gfg-icon gfg-icon_link padding-2px code-sidebar-button generate-url-and-run-button"></i><br><i title="Dark Mode" class="gfg-icon gfg-icon_dark-toggle padding-2px code-sidebar-button dark-editor-button"></i><br><i id=edit-on-ide-button title="Edit on IDE" lang=csharp class="gfg-icon gfg-icon_code padding-2px code-sidebar-button edit-on-ide-button"></i></div></p></div></p></div></p></div><div class=code-container><div id=highlighter_320863 class="syntaxhighlighter nogutter"><table border=0 cellpadding=0 cellspacing=0><tbody><tr><td class=code><div class=container><div class="line number1 index0 alt2"><code class=comments>// C# program to demonstrate the Sbyte</code></div><div class="line number2 index1 alt1"><code class=comments>// signed integral data type</code></div><div class="line number3 index2 alt2"><code class=keyword>using</code> <code class=plain>System;</code></div><div class="line number4 index3 alt1"><code class=keyword>namespace</code> <code class=plain>ValueTypeTest {</code></div><div class="line number5 index4 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number6 index5 alt1"><code class=keyword>class</code> <code class=plain>GeeksforGeeks {</code></div><div class="line number7 index6 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number8 index7 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Main function</code></div><div class="line number9 index8 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>static</code> <code class=keyword>void</code> <code class=plain>Main()</code></div><div class="line number10 index9 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>{</code></div><div class="line number11 index10 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>sbyte</code> <code class=plain>a = 126;</code></div><div class="line number12 index11 alt1"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number13 index12 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// sbyte is 8 bit&nbsp;</code></div><div class="line number14 index13 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// singned value</code></div><div class="line number15 index14 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number16 index15 alt1"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number17 index16 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number18 index17 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number19 index18 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number20 index19 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// It overflows here because</code></div><div class="line number21 index20 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// byte can hold values&nbsp;</code></div><div class="line number22 index21 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// from -128 to 127</code></div><div class="line number23 index22 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number24 index23 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number25 index24 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number26 index25 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Looping back within&nbsp;</code></div><div class="line number27 index26 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// the range</code></div><div class="line number28 index27 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number29 index28 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number30 index29 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>}</code></div><div class="line number31 index30 alt2"><code class=plain>}</code></div><div class="line number32 index31 alt1"><code class=plain>}</code></div></div></td></tr></tbody></table></div></div><div class=code-editor-container></div></p></div><div class=code-output-container><div class=output-block><i id=output-icon title=Output class="gfg-icon gfg-icon_arrow-right-editor padding-2px code-sidebar-button output-icon"></i></p><pre class=output-pre>  </p></div><div class=ide-link-div><i id=copy-url-button title="Copy Generated Ide URL" class="gfg-icon gfg-icon_copy padding-2px code-sidebar-button copy-url-button"></i></p><pre id=ide-url>  </p></div></p></div><p><strong>Output :</strong></p><pre>
            126
            127
            -128
            -127
             <p><strong>Example :</strong></p><div class=code-block><div class=code-gutter><div class=editor-buttons-container><div class=editor-buttons><div class=editor-buttons-div title="Run and Edit"><i id=copy-code-button title="Copy Code" class="gfg-icon gfg-icon_copy code-sidebar-button padding-2px copy-code-button"></i></p><div id=run-and-edit-loader class=ring-load></div><p><i id=run-and-edit-button title="Edit Code" lang=csharp class="gfg-icon gfg-icon_edit_1 padding-2px code-sidebar-button"></i><br><i id=close-code-editor-button title="Close Editor" class="gfg-icon gfg-icon_close-editor padding-2px code-sidebar-button close-code-editor-button"></i></p><div id=run-code-loader class=ring-load></div><p><i id=run-code-button lang=csharp title="Run Code and See Output" class="gfg-icon gfg-icon_play padding-2px code-sidebar-button"></i></p><div id=generate-url-loader class=ring-load></div><p><i id=generate-url-and-run-button title="Run Code and Generate IDE URL" lang=csharp class="gfg-icon gfg-icon_link padding-2px code-sidebar-button generate-url-and-run-button"></i><br><i title="Dark Mode" class="gfg-icon gfg-icon_dark-toggle padding-2px code-sidebar-button dark-editor-button"></i><br><i id=edit-on-ide-button title="Edit on IDE" lang=csharp class="gfg-icon gfg-icon_code padding-2px code-sidebar-button edit-on-ide-button"></i></div></p></div></p></div></p></div><div class=code-container><div id=highlighter_317810 class="syntaxhighlighter nogutter"><table border=0 cellpadding=0 cellspacing=0><tbody><tr><td class=code><div class=container><div class="line number1 index0 alt2"><code class=comments>// C# program to demonstrate&nbsp;</code></div><div class="line number2 index1 alt1"><code class=comments>// the byte data type</code></div><div class="line number3 index2 alt2"><code class=keyword>using</code> <code class=plain>System;</code></div><div class="line number4 index3 alt1"><code class=keyword>namespace</code> <code class=plain>ValueTypeTest {</code></div><div class="line number5 index4 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number6 index5 alt1"><code class=keyword>class</code> <code class=plain>GeeksforGeeks {</code></div><div class="line number7 index6 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number8 index7 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Main function</code></div><div class="line number9 index8 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>static</code> <code class=keyword>void</code> <code class=plain>Main()</code></div><div class="line number10 index9 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>{</code></div><div class="line number11 index10 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>byte</code> <code class=plain>a = 0;</code></div><div class="line number12 index11 alt1"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number13 index12 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// byte is 8 bit&nbsp;</code></div><div class="line number14 index13 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// unsigned value</code></div><div class="line number15 index14 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number16 index15 alt1"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number17 index16 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number18 index17 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number19 index18 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number20 index19 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a = 254;</code></div><div class="line number21 index20 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number22 index21 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// It overflows here because</code></div><div class="line number23 index22 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// byte can hold values from</code></div><div class="line number24 index23 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// 0 to 255</code></div><div class="line number25 index24 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number26 index25 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number27 index26 alt2"><code class="undefined spaces">&nbsp;</code>&nbsp;</div><div class="line number28 index27 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Looping back within the range</code></div><div class="line number29 index28 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a++;</code></div><div class="line number30 index29 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number31 index30 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>}</code></div><div class="line number32 index31 alt1"><code class=plain>}</code></div><div class="line number33 index32 alt2"><code class=plain>}</code></div></div></td></tr></tbody></table></div></div><div class=code-editor-container></div></p></div><div class=code-output-container><div class=output-block><i id=output-icon title=Output class="gfg-icon gfg-icon_arrow-right-editor padding-2px code-sidebar-button output-icon"></i></p><pre class=output-pre>  </p></div><div class=ide-link-div><i id=copy-url-button title="Copy Generated Ide URL" class="gfg-icon gfg-icon_copy padding-2px code-sidebar-button copy-url-button"></i></p><pre id=ide-url>  </p></div></p></div><p><strong>Output :</strong></p><pre>
            0
            1
            255
            0
              <li><strong>Boolean Types :</strong> It has to be assigned either true or false value. Values of type bool are not converted implicitly or explicitly (with casts) to any other type. But the programmer can easily write conversion code.</p><table width=100% style="border:2px solid #000"><thead><tr><th style=padding:8px;background-color:#4cb96b;text-align:center>Alias</th><th style=padding:8px;background-color:#4cb96b;text-align:center>Type name</th><th style=padding:8px;background-color:#4cb96b;text-align:center>Values</th></tr></thead><tbody><tr><td style=text-align:center>bool</td><td style=text-align:center>System.Boolean</td><td style=text-align:center>True / False</td></tr></tbody></table><p><strong>Example :</strong></p><div class=code-block><div class=code-gutter><div class=editor-buttons-container><div class=editor-buttons><div class=editor-buttons-div title="Run and Edit"><i id=copy-code-button title="Copy Code" class="gfg-icon gfg-icon_copy code-sidebar-button padding-2px copy-code-button"></i></p><div id=run-and-edit-loader class=ring-load></div><p><i id=run-and-edit-button title="Edit Code" lang=csharp class="gfg-icon gfg-icon_edit_1 padding-2px code-sidebar-button"></i><br><i id=close-code-editor-button title="Close Editor" class="gfg-icon gfg-icon_close-editor padding-2px code-sidebar-button close-code-editor-button"></i></p><div id=run-code-loader class=ring-load></div><p><i id=run-code-button lang=csharp title="Run Code and See Output" class="gfg-icon gfg-icon_play padding-2px code-sidebar-button"></i></p><div id=generate-url-loader class=ring-load></div><p><i id=generate-url-and-run-button title="Run Code and Generate IDE URL" lang=csharp class="gfg-icon gfg-icon_link padding-2px code-sidebar-button generate-url-and-run-button"></i><br><i title="Dark Mode" class="gfg-icon gfg-icon_dark-toggle padding-2px code-sidebar-button dark-editor-button"></i><br><i id=edit-on-ide-button title="Edit on IDE" lang=csharp class="gfg-icon gfg-icon_code padding-2px code-sidebar-button edit-on-ide-button"></i></div></p></div></p></div></p></div><div class=code-container><div id=highlighter_138007 class="syntaxhighlighter nogutter"><table border=0 cellpadding=0 cellspacing=0><tbody><tr><td class=code><div class=container><div class="line number1 index0 alt2"><code class=comments>// C# program to demonstrate the</code></div><div class="line number2 index1 alt1"><code class=comments>// boolean data type</code></div><div class="line number3 index2 alt2"><code class=keyword>using</code> <code class=plain>System;</code></div><div class="line number4 index3 alt1"><code class=keyword>namespace</code> <code class=plain>ValueTypeTest {</code></div><div class="line number5 index4 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number6 index5 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>class</code> <code class=plain>GeeksforGeeks {</code></div><div class="line number7 index6 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number8 index7 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Main function</code></div><div class="line number9 index8 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>static</code> <code class=keyword>void</code> <code class=plain>Main()&nbsp;</code></div><div class="line number10 index9 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>{</code></div><div class="line number11 index10 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number12 index11 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// boolean data type</code></div><div class="line number13 index12 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>bool</code> <code class=plain>b = </code><code class=keyword>true</code><code class=plain>;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code></div><div class="line number14 index13 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>if</code> <code class=plain>(b == </code><code class=keyword>true</code><code class=plain>)</code></div><div class="line number15 index14 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(</code><code class=string>"Hi Geek"</code><code class=plain>);</code></div><div class="line number16 index15 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>}&nbsp;</code></div><div class="line number17 index16 alt2"><code class=plain>}</code></div><div class="line number18 index17 alt1"><code class=plain>}</code></div></div></td></tr></tbody></table></div></div><div class=code-editor-container></div></p></div><div class=code-output-container><div class=output-block><i id=output-icon title=Output class="gfg-icon gfg-icon_arrow-right-editor padding-2px code-sidebar-button output-icon"></i></p><pre class=output-pre>  </p></div><div class=ide-link-div><i id=copy-url-button title="Copy Generated Ide URL" class="gfg-icon gfg-icon_copy padding-2px code-sidebar-button copy-url-button"></i></p><pre id=ide-url>  </p></div></p></div><p><strong>Output :</strong></p><div style="text-align:center;margin:20px 0;max-height:280px" id=GFG_AD_gfg_outstream_incontent></div><pre>
            Hi Geek
            </li></ul><li><strong>Reference Data Types :</strong> The Reference Data Types will contain a memory address of variable value because the reference types won’t store the variable value directly in memory. The built-in reference types are <strong>string, object.</strong><ul><li><strong>String :</strong> It represents a sequence of Unicode characters and its type name is <strong>System.String</strong>. So, string and String are equivalent.<br><strong>Example :</strong></p><pre>
            string s1 = "hello"; // creating through string keyword  
            String s2 = "welcome"; // creating through String class  
              </li><li><strong>Object :</strong> In C#, all types, predefined and user-defined, reference types and value types, inherit directly or indirectly from Object. So basically it is the base class for all the data types in C#. Before assigning values, it needs type conversion. When a variable of a value type is converted to object, it&#8217;s called <strong>boxing</strong>. When a variable of type object is converted to a value type, it&#8217;s called <strong>unboxing</strong>. Its type name is <strong>System.Object</strong>.</li><p><strong>Example :</strong></p><div class=code-block><div class=code-gutter><div class=editor-buttons-container><div class=editor-buttons><div class=editor-buttons-div title="Run and Edit"><i id=copy-code-button title="Copy Code" class="gfg-icon gfg-icon_copy code-sidebar-button padding-2px copy-code-button"></i></p><div id=run-and-edit-loader class=ring-load></div><p><i id=run-and-edit-button title="Edit Code" lang=csharp class="gfg-icon gfg-icon_edit_1 padding-2px code-sidebar-button"></i><br><i id=close-code-editor-button title="Close Editor" class="gfg-icon gfg-icon_close-editor padding-2px code-sidebar-button close-code-editor-button"></i></p><div id=run-code-loader class=ring-load></div><p><i id=run-code-button lang=csharp title="Run Code and See Output" class="gfg-icon gfg-icon_play padding-2px code-sidebar-button"></i></p><div id=generate-url-loader class=ring-load></div><p><i id=generate-url-and-run-button title="Run Code and Generate IDE URL" lang=csharp class="gfg-icon gfg-icon_link padding-2px code-sidebar-button generate-url-and-run-button"></i><br><i title="Dark Mode" class="gfg-icon gfg-icon_dark-toggle padding-2px code-sidebar-button dark-editor-button"></i><br><i id=edit-on-ide-button title="Edit on IDE" lang=csharp class="gfg-icon gfg-icon_code padding-2px code-sidebar-button edit-on-ide-button"></i></div></p></div></p></div></p></div><div class=code-container><div id=highlighter_42543 class="syntaxhighlighter nogutter"><table border=0 cellpadding=0 cellspacing=0><tbody><tr><td class=code><div class=container><div class="line number1 index0 alt2"><code class=comments>// C# program to demonstrate&nbsp;</code></div><div class="line number2 index1 alt1"><code class=comments>// the Reference data types</code></div><div class="line number3 index2 alt2"><code class=keyword>using</code> <code class=plain>System;</code></div><div class="line number4 index3 alt1"><code class=keyword>namespace</code> <code class=plain>ValueTypeTest {</code></div><div class="line number5 index4 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number6 index5 alt1"><code class=keyword>class</code> <code class=plain>GeeksforGeeks {</code></div><div class="line number7 index6 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number8 index7 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// Main Function</code></div><div class="line number9 index8 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>static</code> <code class=keyword>void</code> <code class=plain>Main()&nbsp;</code></div><div class="line number10 index9 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>{</code></div><div class="line number11 index10 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number12 index11 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// declaring string</code></div><div class="line number13 index12 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>string</code> <code class=plain>a = </code><code class=string>"Geeks"</code><code class=plain>;&nbsp;</code></div><div class="line number14 index13 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number15 index14 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>//append in a</code></div><div class="line number16 index15 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a+=</code><code class=string>"for"</code><code class=plain>;</code></div><div class="line number17 index16 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>a = a+</code><code class=string>"Geeks"</code><code class=plain>;&nbsp;</code></div><div class="line number18 index17 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(a);</code></div><div class="line number19 index18 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number20 index19 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// declare object obj</code></div><div class="line number21 index20 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=keyword>object</code> <code class=plain>obj;</code></div><div class="line number22 index21 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>obj = 20;</code></div><div class="line number23 index22 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(obj);</code></div><div class="line number24 index23 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code>&nbsp;</div><div class="line number25 index24 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// to show type of object</code></div><div class="line number26 index25 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=comments>// using GetType()</code></div><div class="line number27 index26 alt2"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>Console.WriteLine(obj.GetType());&nbsp;</code></div><div class="line number28 index27 alt1"><code class="undefined spaces">&nbsp;&nbsp;&nbsp;&nbsp;</code><code class=plain>}&nbsp;</code></div><div class="line number29 index28 alt2"><code class=plain>}</code></div><div class="line number30 index29 alt1"><code class=plain>}</code></div></div></td></tr></tbody></table></div></div><div class=code-editor-container></div></p></div><div class=code-output-container><div class=output-block><i id=output-icon title=Output class="gfg-icon gfg-icon_arrow-right-editor padding-2px code-sidebar-button output-icon"></i></p><pre class=output-pre>  </p></div><div class=ide-link-div><i id=copy-url-button title="Copy Generated Ide URL" class="gfg-icon gfg-icon_copy padding-2px code-sidebar-button copy-url-button"></i></p><pre id=ide-url>  </p></div></p></div><p><strong>Output :</strong></p><pre>
            GeeksforGeeks
            20
            System.Int32
              </ul><li><strong>Pointer Data Type :</strong> The Pointer Data Types will contain a memory address of the variable value.<br>To get the pointer details we have a two symbols <strong>ampersand (&) and asterisk (*)</strong>.<br><strong><em>ampersand (&)</em>:</strong> It is Known as Address Operator. It is used to determine the address of a variable.<br><strong><em>asterisk (*)</em>:</strong> It also known as Indirection Operator. It is used to access the value of an address.<br><strong>Syntax :</strong></p><pre>
            type* identifier;
              <p><strong>Example :</strong></p><pre>
            int* p1, p;   // Valid syntax
            int *p1, *p;   // Invalid 
            
            
            
    </section>
    </body>
</html>
