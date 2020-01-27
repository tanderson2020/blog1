How To SSH/Log Into Your Clarkson Polaris Account
======

STEP 1: Logging into to polaris
---------------	
You will log in using ssh, using your clarkson account 

$ ssh username@polaris.clarkson.edu 

Then it will ask for your password. 

It is important to note that as you are typing in your password it will not be visible. Do not be alarmed, this is for security reasons.

Once done hit ENTER and you have successfully logged into your clarkson polaris account.


## Step 2: Creating a directory

To create a folder, also known as a directory:

$ mkdir (folder_name)

To step into the folder 

$ cd (folder_name)

To look at where you are currently located in the directory

$ pwd

## Step 3: Create a file

We want to create a file, for our html project

$ touch index.html

Then we want a another folder that will contain our style sheets. This will will help with file organization and readability

$ mkdir styles

Then we step into that folder and create the style sheet

$ touch style.css

## Step 4: listing items in the directory

Suppose we want to see what we have in our styles folder. Either command can be used

$ ls
Or 

$ ls -al

Step 5: Editing a file

We can use vim or nano to edit our styles.css file. We use vim for this demo

$ vim styles.css

If we want to edit we hit **i** to enter into insert mode.

To save and quit we hit the **esc** button and type in **:wq**

You should now be back on the command line after exiting the vim editor

## Step 5: deleting a directory

Create another directory
$ mkdir (file_name2)

Delete the directory
$rmdir (file_name2)


That’s all folks!
======

Now you should have some of the basics of the command line and being able to ssh into polaris. More information can be found from [here](https://web2.clarkson.edu/class/cs141/webresources/resources.html)


