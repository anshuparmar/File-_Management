# File_Managment


File_Handling

We all know that to organize all this files manually. 
It's so boraring and time taking task so first off all. 
We need to import the required modules.
So import os and shutil module.these are inbuilt modules, so don't need to install them.
And you need to create a variable called path which takes input of the directory path that you want to organize.
And then create a variable called files.
Which consists of a list of lines.
Now write a for loop condition.
Using for loop we traverse through every file from files.
The we spilt the filename and extension of the file.
We only need an extansion name so we remove the dot from the extension through slicing.
And then we need write to if statement.
If the extension directly already exits, then we move the file to that directory.
In else statement we make a new directory and then we move the file into it.
At the last lets runs the program......
After that you get your all saparate file in their respactive folder............



2)category wise:-

So now secondly it's category wise as said above now we will again import os but we don't need to download it from anywhere it's already inbuilt then we will create a basepath variable for the input of paths for files to organize  now we create a list in which which category we want to organize here I have organized category as vedios images and many more now we use if loop here first we check that if vedios are there then its will go to vedios if images then image and so on in the vedios I have entered mp3 and wav
In the vedio I entered mp4 avi and many more so if this extension exist then it will go in that categorynow we will tack the define function define the move items for folder after the define the function we will tack the if condition for os.path.basepath is not in whislist and than print the move folder for the def function after the if condition we will tack ext file for ever whislist items the music ext file are consider the mp3,wav.... the video ext file are consider the mp4,,mov,mkv...or you can add other file and the image ext file consider the png,jpg or other image type... after tha tacking the file typewe will tack the for loop for every whislist and than tack if condition for image are not consider in whislist then remove it this for loop and if condition are suitable on all item in whislist like....video,image,music,file after the for loop and if condition end my program and run my program you can see my program are run sucessfully and say that enter the path so first i will copy my file path you can see my file are mixed format so paste the path in program and run the program and see my file folder are in the file like category wise thank you.......
