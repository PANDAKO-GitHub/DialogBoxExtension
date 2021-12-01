# DialogBoxExtension for GDevelop

## Summary
This extension adds Dialog Box functionality that can be used for RPGs, visual novels, and more.

## How to use:
1. You will need a background **sprite**, a character **sprite**, a **BBText** to display the name, a **BBText** to display the text, and a **sprite** for the icon to prompt the player for action.
1. Add the "Dialog Box" behavior to the background object.
1. Place each object in the scene.
1. Execute the "Setup Dialog Box" action only once in the event.
1. After that, execute the "Open Dialog Box" action, "Close Dialog Box" action, etc.

## This extension add:
**Dialog Box** - behavior  
**Setup Dialog Box** - action  
**Open Dialog Box** - action  
**Close Dialog Box** - action  
**Change Dialog Box Text** - action  
**Change Dialog Box contents** - action  
**Change Dialog Box typing sound** - action  
**Change Dialog Box typing interval** - action  
**Skip Dialog Box typing** - action  
**Dialog Box is open** - condition  
**Dialog Box is typing** - condition  
**Dialog Box is close** - condition  
**Number of times the Text in Dialog Box has changed** - condition  
**Number of times the Text in Dialog Box has changed** - expression  

## Tips
This Dialog Box has a useful counter function.  
It is zero when the dialog box is opened, and increases by one each time the text changes.  
(However, it will not increase until the frame advances).  
This feature is useful for keeping track of the progress of a conversation.

## Note
In typing, style tags in BBText OBjects are also counted as characters.

 
