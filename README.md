# pic-easy
A quick front end snippet for nice looking, user friendly profile pictures. Simply add your desired size or make it responsive using your preferred grid system css framework.


I you are looking for some nice looking easy to set up profile picture front end. Here's a code snippet I have just created.
https://codepen.io/ocanodiego/pen/ayYeeN

Dependencies:

  font-awesome

Installation:

  Just copy and paste the snippet into your html and css respectively
  Instructions:
  If you don't want a circular image just remove the pic-circle class
  Select your size with the following classes:
  
  ```
  pic-xs
  pic-small
  pic-medium
  pic-large
  pic-xl
  ```

Or feel free to edit as you like for colors and size, I added sizes so you can easily display the picture at different places across an entire application, in which you often display this kind of sizes.

If you are using a css grid system you can wrap the picture within your column setup and omit the size class to make it responsive.
The edit and delete buttons are simple anchor elements so you can open a modal for image edition before uploading and delete via Ajax.
Any addition or improvement is welcome, but keep in mind I want to keep it simple.
