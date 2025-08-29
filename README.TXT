What happens if you call moveDown twice? Or three times? What happens if you call
makeInvisible twice?

Everytime moveDown is called, the shape affected simply moves down. If you use makeInvisible more than once, 
the shape will become invisible and remain invisible no matter how many times we call the command.

Invoking the changeColor method without the quotes gives an error saying it can't find symbol.

I placed the shapes to create a house and the sun. To be able to change each shape's size, I have to inspect to see the original size of each shape to then know if I have to lower or add to
the number in ChangeSize. To move the shapes around, I used moveLeft, moveRight, moveUp and moveDown. I used the int distance using moveVertical and moveHorizontal for most precise placements.
