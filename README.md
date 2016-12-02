# Cellular_Automata_Hacking
Hacking the JavaScript world that Alan Richardson created using the Browser Dev Tools

##Hacking JavaScript Games YouTube collection

https://www.youtube.com/playlist?list=PLrM2ELpRbbu58T2IDqEyJ9oK98xGu4r9V

Inspired by this awesome platform and a chance to learn some new skills using the Browser Dev Tool, I attempted to go off track a little bit and create a special treat for Alan. I'm a "hobby" coder so this is just all practice in my eyes.

In fairness, the code is poor and it was a complete hack - For me, it was just an exercise in being able to do it, rather than getting the code perfect.

I've put it here to remind myself that sometimes it's ok to write something that "Just works".

I've had a quick think about how I will refactor this first attempt, I will be coming back to this code because it's a great way to gauge my understanding of what I did and how I can be improved. This is what i have so far...


~~~~ 
// Clears the invasion that has started when the page loads
stopInvasion();
world.nukeEmAll();

//E

//addLifeForms.block(world, 100,50)
//addLifeForms.block(world, 105,50)
//addLifeForms.block(world, 110,50)
//addLifeForms.block(world, 115,50)
//......

//To try and refactor the code I would probably interate over an array
var position = [100, 105,110,115];
position.forEach(function(current_value) {
    addLifeForms.block(world, current_value, 50);
		});
~~~~ 
