### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces.

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript

function whatToDoForLunch(hungry, availableTime) {
  console.log("I don't know what to do!");

  if(hungry === false) {
    console.log("i'm not hungry!");
  } else if (hungry === true && availableTime < 20) {
    console.log("Pick something up and eat it back at the lab!");
  } else if (hungry === true && availableTime > 30) {
    console.log("This is a bootcamp and you should probably reconsider");
  } else {
    console.log("You deserve a break and you should try a place in gastown")
  }
}

```