### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.



let whatToDoForLunch = function(hungry, availableTime) {

  if (hungry === false) {
    console.log(" Get back to work");
  } else if(hungry === true && availableTime < 20) {
     console.log("Pick something up and eat in the lab");
   }
   else if (hungry === true && availableTime >= 20 || availableTime <=30){
     console.log
   }
    else {
    
      console.log(" Hey! we are in a bootcamp. we should consider how much time do we have to spare.")
    }
  }

    console.log("I'm hungry and I have 20 minutes for lunch.");
  whatToDoForLunch(true, 20);
  
  
  console.log("I'm hungry and I have 50 minutes for lunch.");
  whatToDoForLunch(true, 50);
  
  
  console.log("I'm not hungry and I have 30 minutes for lunch.");
  whatToDoForLunch(false, 30);
  
  console.log("I'm hungry and I have 15 minutes for lunch.");
  whatToDoForLunch(true, 15);