# FileModification_UiPath
A simple loop for user to change the default name (10 characters) of each file by the characters recognised in the images (4 characters). (Each file has 127 images of a same character). The files of images are saved in the project file and will be used after for machine learning.  
The program will check if the path of files exists, and if the file name hasn't been modified yet (The default name is a 10 character string). Then create a personalized input form with the first 3 images of the file for the user to enter the recognised characters.   
User can switch the images until the 127th images of the file. Once the characters have been entered, the user can press 'enter' to finish the modification, the file name of the file will be modified. The window will be closed and another new form will appear.  
A warning will appear if user submits an empty string.  
The user can click 'leave' to stop the program properly.   
Once all files names have been modified, the program will stop automatically.   
Little problem: Can't not automatically focus on the input form. May be some one can help me?
