# cse341-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CSE341 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cse341-grading-each-project-will-be-graded-on-the-scale-100-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112784&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE341 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
G++ Language Syntax Analyzer: Given the description of the G++ language (G++Syntax.pdf) you are asked to implement a syntax analyzer that accepts or rejects a given program in G++. Syntax analysis rules of G++ is explained in the document in G++Syntax.pdf.

You are asked to implement the syntax analysis in two different ways:

1. There are tools to implement syntax analysis given the rules in a meta-grammar such as CFGs. One such tool is “Yacc” that lets you generate C code to do the syntax analysis.

2. For this course, you will be implementing a syntax analysis algorithm for G++ in Lisp as well. For this you are not expected to use a meta-grammar to define the lexical syntax of your language.

Both analyses tool should start the interpreter. It will read one line at a time from the user and check if the input syntax is correct while generating the parse tree for later processing. You are also expected to implement code for expressions as well as if statements.

G++ Language Interpreter using Flex and Yacc (35 points): Implement your interpreter using Yacc. For this you will also need your lexer from the previous homework. Hand in your “gpp_interpreter.y” file for this part of the homework. You are also expected to submit the corresponding C file generated by your lexer and syntax analyzer along with any other .h or .c file that is needed to compile “gpp_interpreter.c” using GCC on Ubuntu (16 or later).

Full score would require the lexer code to implement the CFG for expressions and if statements. This also means that you need to have the proper things for some basic data types. 20 points will be taken away for those not implementing a proper CFG.

G++ Language Interpreter in Lisp (65 points): Implement your interpreter in Common Lisp. Hand in your “gpp_interpreter.lisp” file for this part of the homework. This file should have a function called “gppinterpreter” that will start your interpreter. “gppinterpreter” can have zero or one input. The input can be a file name which will be loaded by the interpreter and interpreted right away.

There will be 20 point reduction if proper CFG parsing algorithm is not implemented.

Examples: The following table provides the correct tokenization for a few instances of G++ language. Note that lexical syntax error messages should give some information about the error encountered.

;; helloworld.g++

(+ 10 10 ) Syntax OK.

Result: 20

(++ 1 2 3) SYNTAX_ERROR Expression not recognized

Handin your code in a single tar for zip file named yourstudentnumber_lastname_firstname_hw3.zip/rar. For example, if your name us John Wayne, student number is 123456789 and zipped everything in a RAR file, then you should submit your file as “123456789_Wayne_John_hw2.rar”.
