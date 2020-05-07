# Chapter One
## DEFINITION
### [What is PHP? ](https://www.php.net/manual/en/intro-whatis.php)
PHP is an acronym for PHP Hypertext Preprocessor. 
It is a popular scripting language. What on earth does that mean?
Well, don't think too much of the 'scripting'. Let's look at it this way:
say you want a child on an errand to assist you get something at the store. In order to ease her work and 
ensure your purchase is done accurately, you give a piece of paper with 
the items you want to purchase, this will help the child look at your list and 
make your purchase. When the child is done he/she returns with your item[s].
What happened was that the child made purchase on your behave from the local store, and
return your item[s] for you.
PHP can do same: take your instruction in a script(piece of paper), go 
to the server(local store) and return with a result.
Hope you're getting comfortable with PHP now. PHP is a straight forward 
language, easy to pickup and advanced enough to do cool stuff.

### [What can PHP Do?](https://www.php.net/manual/en/intro-whatcando.php)

Well, what do you want to do with PHP?
PHP can handle server-side tasks. In simple language, this means PHP handles instruction or you can call it tasks
that runs on the server. So, you hear people referring to it as server-side
language or server-side scripting language. If you don't know what a server is 
don't worry just move on. It means nothing much for now. PHP can pretty much do anything a programming language can do.
From building, dynamic web application, to Command line scripting, AI, Desktop applications, games, etc. The list is endless.
Keep moving and you will discover more. What do you have in mind to build, PHP can do it 😀 . 

### PHP As A Scripting Language
Earlier in this chapter, we talked briefly about a script. You shouldn't think too much of a script.
It is just a programming word(terminology) for a block of code or set of instructions.
If you have seen a paper with a list of grocery items, then you good. Like you give 
a paper to a child to assist you make purchases from the local store. The child is only concern with what is on that list, 
that is where your instructions for the purchase are. The list can be long or short, it depends.
A far as the child stick to what is on that paper from the top of it to the bottom, there will be no 
problems. Likely with PHP. your instruction to PHP to do any must be on a script. PHP looks at the begining of 
that script to the end, what is there is what it will do(run), and return the result or output. 

A PHP script begins with `<?php` and ends with `?>`. As a short hand you can do `<?` and `?>`  .
All your instruction(what you want PHP to do) must be within the opening(`<?php`) and closing tags( `<?` ). 
Yes, they are called tags.
 **Note:** the closing tags can omitted if the file is only a PHP file, i.e if everything
in that file is just PHP code.

Example 

`<?php`

    echo 'Hello, World!';
  
  `?>` 

This will print out `Hello, World!`