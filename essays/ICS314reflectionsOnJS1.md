##How It feels to Royally Mess Up Early in the Semester

I’ve never met anyone who openly announces their failures as much as their successes. In fact, I feel that most people avoid openly talking about times they messed up. It may be because I lack any sense of shame, but personal failures are what I tend to elaborate more on. I’ve noticed that my role in a network of support is to be the empathizer and the comforter. If I tell my friends about the (many) times I’ve fallen flat on my face, it makes them feel better about admitting their own short-comings. So, friends, let me detail the accounts of my royal screw up during the first two weeks of ICS 314.

In ICS 314, we have an assignment known as WOD or Work Out of The Day which is a short, timed programming assignment in JavaScript. During a module, we will have 2 WODs to be done at home and 2 to be done in class. However, one of the in-class WODs will count towards our grades. Not only do you have to finish the exercise in the time limit, but your solution must be correct. On my first in-class, graded WOD, I messed up severely and ended up running out of the 20 minutes given as the maximum amount of time to be used. As soon as I was told to stop, I knew why my program wasn’t working. I had gotten the logic down, but I made a deadly syntax mistake. I failed to give my counter a number value, even though I had initialized the variable. Here’s what I did.
```
function countVowels(someString){
let v;
let i;
	for(i = 0; i< someString.length; i ++){
  switch (someString[i]){
  case 'a':
  v++;
  break;
  case "e":
 	v++;
  break;
  case 'i':
  v++;
  break;
  case 'o':
  v++;
  break;
  case 'u':
  v++;
  break;
  }
  }
  if(v != 0){
  return ("There are " + v + "vowels");
  }else {return ("There are no vowels.");}
}
```
I find that the simplest, most obvious mistakes are the ones that sting the most. I expect more from myself than to be stuck on a syntax error for 20 minutes. But just like you, reader, I am human. It is perfectly alright to make mistakes because although we, as programmers, may work with machines, we are not computers. For, if humans were omnipotent, schools would cease to exist.

If you have messed up in the beginning of any class and felt like that single mistake defined who you will be for the rest of the semester, fret not. Fortunately, for me and for you, there are roughly 4 months left in the semester and plenty of room for improvement. Once you hit rock bottom, you can only go up from there. 
