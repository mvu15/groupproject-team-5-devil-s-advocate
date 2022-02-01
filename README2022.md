The first commit must provide new file (README.md) that will have two sections, 
the first being the overview of the feature that you are implementing and 
a second section called pseudocode that will provide the pseudocoding process for this feature 
- as outlined in chapter 9 of code complete or what was mentioned in lecture

1) The overview of the feature that you are implementing:
  a. In our game of Super Mario, I will be adjusting the speed of the character's jump force 
     ability as well as attemping to store and condense all the images of the characters in 
     a text file for someone to be able to modify the file rather than the code itself. 

2) Pseudocode

  a. Adjustments for Jump Speed
  
    Declare a function for JumpForceSpeed{
        
        Locate the X and Y coordinates of character
        
        Set up max Velocity Acceleration
        
        Set up max Height
        
     }
  b. Create a file for images
     
        Declare variable for different directions{
     
        Set up forward facing character
          Left foot forward
          Right foot forward
     
        Set up backward facing character
          Left foot forward
          Right foot forward
     
        Set up jump up forward facing chaaracter
        
        Set up jump up forward facing chaaracter
        }

   c. Linking the images with movement
  
        Make a general image function to import images from file{
        Call file
        
        Connect foward moving images to movement
        
        Connect barward moving images to movement
        
        Connect jump foward moving images to movement
      
        Connect jump backward moving images to movement
     }
        
3. Current Status:
  a. As of right now, I was unable to successfully implement the new features. 
      However, in regards to what I have completed I had created a class which
      would essentially read in the value of the jumpForce.txt file which can
      be easily altered once connected to the mainEntity.yVel in the Physics
      Engine.
      
  b. In regards to the images, I created a file which had established which 
      .png of the characte Yoshi would translate to when correlated with the 
      direction of the character. However, I had difficulties trying to figure
      out how exactly to link the physics and replace the current images of 
      Mario. However, given more time and resources, I would attempt to turn
      the images into filenames which could then be implemented into a 
      characters class that would link to the physics.
