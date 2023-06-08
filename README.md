# FrontEndAssignment

This a simple drag and drop using html, css and Javascript. 

# Procedure for Drag and Drop:
## Step 1: Make an object draggable 

First set the draggable attribute to true for that element to be draggable <img draggable = “true”>

Then, specify what should happen when the element is dragged. The ondragstart attribute calls a function, drag(event), that specifies what data to be dragged. The dataTransfer.setData() method sets the data type and the value of the dragged data

The event listener ondragstart will set the allowed effects (copy, move, link, or some combination).

## Step 2: Dropping the Object 
The ondragover event specifies where the dragged data can be dropped. By default, data/elements cannot be dropped in other elements. To allow a drop, it must prevent the default handling of the element. This is done by calling the event.preventDefault() method

Finally, the drop event, which allows the actual drop to be performed