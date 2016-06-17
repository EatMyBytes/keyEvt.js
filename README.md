#What is keyEvt.js?
KeyEvt.js is a javascript library made by me :D EatMyBytes that allows for easy access to user key input.

#How does it work?
When a user presses a key on their keyboard keyEvt takes that keycode, matches it up with the value of the key on the keyboard and returns that value to the programmer.

#So whats my benifit?
You can see if a user pressed any key with a simple js if statement.



Alright How do i use it?
Just add this code to your website, a keypress or keydown event and a if statement

Jquery users
```html
<script>
$ ( document ).keypress( function (){
if(Key(event) == "anyletter"){ 
do whatever
} 
}); 
</script>
```
#Js users
<script> 
document.addEventListener("onkeypress", function(){
if(Key(event) == "anyletter"){ 
do whatever
} 
}); 
</script>
How ever you Like ;)
<html onkeypress="move()">
<head>
</head> 
<body>
<script>
function move(){
if(Key(event) == "w"){
move Up 
} 
} 
</script> 
</body> 
</html>
