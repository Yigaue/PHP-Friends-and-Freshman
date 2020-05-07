# Introduction

## 1.1 [What is PHP? ](https://www.php.net/manual/en/intro-whatis.php)
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

## 1.2 [What can PHP Do?](https://www.php.net/manual/en/intro-whatcando.php)

Well, what do you want to do with PHP?
PHP can handle server-side tasks. In simple language, this means PHP handles instruction or you can call it tasks
that runs on the server. So, you hear people referring to it as server-side
language or server-side scripting language. If you don't know what a server is 
don't worry just move on. It means nothing much for now. PHP can pretty much do anything a programming language can do.
From building, dynamic web application, to Command line scripting, AI, Desktop applications, games, etc. The list is endless.
Keep moving and you will discover more. What do you have in mind to build, PHP can do it 😀 . 

## 1.3 PHP As A Scripting Language
Earlier in this chapter, we talked briefly about a script. You shouldn't think too much of it.
It is just a programming word(terminology) for a block of code or set of instructions.
If you have seen a paper with a list of grocery items, then you're good. Like you give 
a paper to a child to assist you make purchases from the local store. The child is only concern with what is on that list, 
that is where your instructions for the purchase are. The list can be long or short, it depends.
A far as the child stick to what is on that paper from the top of it to the bottom, there should be no 
issues. Same with PHP. your instruction to PHP to do anything must be on a script. PHP looks at the beginning of 
that script to the end, what is there is what it will do(run), and return the result or output. 

A PHP script begins with `<?php  and ends with ?>`. As a short hand you can do `<?` and `?>`  .
All your instruction(what you want PHP to do) must be within the opening(`<?php`) and closing tags( `<?` ). 
Yes, they are called tags.
 **Note:** the closing tags can be omitted if the file is only a PHP file, i.e if everything
in that file is just PHP code.

### Example 1. 3.1

`<?php`

    echo 'Hello, World!';
  
  `?>` 

This will print out `Hello, World!`


## 1.4 PHP And The Server
Lol, PHP is not  a server. Sorry not referring to you, a friend whispered it. PHP code , you can call it script, runs on the server.
So, you recall, it's mainly a server side scripting language. Then what is a server? This is a tiny 
digression. But here it is.
Yes you're are right. A server is a machine. There are several servers. A web server serves a web resource (in simple words web pages, and related things that makes it functional).
You make request using your device, phone, laptop, palmtop, toetop(just kidding), etc.
and you get a response. The web server can hold or store several web resources.
You making the request is the client, and the machine returning response is the server.
Note. the server does not see you. It only sees your device, so it is right to say your
device (phone or laptop) is the client. Remember communication is machine to machine. In summary a client sends a request for the 
server to fetch a resource and return a response to the client(a browser for instance). The server response may vary. Some common response code may be a 404 response which means 
the resource you're looking for is not available. And other responses like 500, 200, 302 etc.
Where does PHP come in?


## 1.6 The Interpreter


PHP is an interpreted language. There are other interpreted languages and some are compiled.
What does 'interpreted' mean? Say you traveled to china and you needed to get around. 
You entered a store, the price tags are written in 
Mandarin. You'll surely need someone to help you here right. This person interprets the 
language to you. A PHP script needs a PHP interpreter. When you make a request to 
a server for a web resource: e.g you visit wwww.somename.com/index.php, you're 
requesting for a php file. The server knows this because the file name ends with .php.
The server picks this file as it can't read it and send it to the PHP interpreter
and say 'hey man, what is in here?'. The interpreter looks at the file and says "oh, 'Hello world!'".
Then the server passes the response back to the client who requested for the file. And the client 
sees 'Hello world!' (in the browser for instance).
So basically, what the PHP interpreter does is interpret PHP script line by line, just like you read a book sentence by sentence.
And the server sends(serve the response) the message back to the client.