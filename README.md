# c29_complete_code

game, called Feed the Bunny!
Before we get started with the code, let's see a quick overview of the game.
Note: Image to be presented from the Visual Aid.
In this game, we have a watermelon fruit hanging from the rope.
The bunny is waiting at the bottom to eat the watermelon fruit.
When the user clicks on the cut the rope button, the

watermelon falls and the bunny eats it.
As we have seen in the visual aid, we will have different arrangements of ropes in the further classes, in a way so that the user has to choose which rope to cut for the watermelon to land on the bunny.


Using Composites.stack() function we create the multiple
rectangular bodies and store it in the rect variable. Using the Composites.chain() function we create the
chain of the rectangles.
And then using the Constraints.create() we add the constraints to the chain which connects all the bodies of the chain together like we have string in a necklace.
We have the break() function which helps us to break the chain.It simply makes the rope body null.


For our code we are only going to use the rope.js to create the rope and break() function to break the rope when the user clicks on the cut button(which will be added in upcoming classes).
Add rope.js in index.html
To create a rope we need two pieces of important information, first is how long our rope will be, and where we want to hang our rope.
To define the length of the rope, we define a number that creates those many sections in the rope. One section essentially is a rectangle, so you can imagine our rope to be multiple rectangles connected together.
Next, we need the point where we are going to hang the rope, which will be a certain x and y position on the canvas.
