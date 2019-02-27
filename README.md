# Introduction 

This is a basic Hello World app programme. A "Hello World!" programme generally is a computer programme that outputs or displays the message "Hello World!" It is often the first programme that those learning to code write. Once you have written your "Hello World" programme the next phase will be to create your own GitHub repository and push your Hello World programme there. 

Python already comes pre-installed on Mac OS X

## To Start

- Open your terminal and type `python` *this will put you in interactive mode*
- Type `print ("Hello World")` 
- *Press enter* to run your programme
- Type `exit ()` *this will bring you out of interactive mode and take you back to your terminal*

A key point here is to also have a basic knownledge of VIM. VIM is a text editor. These are a few of the basic commands you'll need to know.
To insert text into the text editor you must be in **-- INSERT --** mode to get into the insert mode you must type `i`. you can identify what mode you are in by looking at the bottom left hand corner. To escape the insert mode you must press `esc`. Before saving or exiting the vim editor you must press `:` followed by `wq` or `q!` see below for details and basic commands.

| Command | Note |
| ------- | ---- |
| h | Move Left |
| j | Move down |
| k | Move up |
| l | Move left |
| wq | To save any changes to a file |
| q! | This exits the editor, not saving any changes made |
| i | This is to initially insert text |

Here's a coulpe of things that helped me:
* [Interactive Vim Tutorial](https://www.openvim.com/) 
* Open your terminal and type `vimtutor`

If you would like to play around in python and create more than one Hello World app I advise you to create a folder.

*Follow these steps*

- To create a new folder type `mkdir <e.g python_learning>` *press enter*
- To save your Python example you must `.py` e.g `01_hello_world.py`
- This is where you can save all your python examples.

*Now you have had time to play around with python and hopefully created your own *Hello World* app. Its now time to take  that Hello World app and push it to your own GitHub repository.*

First step you need to complete is:

### Create your own GitHub account. 
* [GitHub.com](github.com) 

Next step is to create your own repository:
* [How to create my own repository](https://help.github.com/en/articles/create-a-repo) - Click the link and follow the instructions

Next step is to clone your repository to your local terminal.

1 Under the repository name,*click Clone or download.*

2 Copy the clone URL for the repository.

3 Open Terminal.

4 Change the current working directory to the location where you want the cloned directory to be made.

5 Type `git clone`, and then paste the URL you copied in Step 2. e.g `git clone <https://github.com/roger/git_learning.git>`

6 *Press enter* and your local clone will be created.

Now you have created your repository and cloned it to your local terminal, the next stage will be to push your `Hello World` app to your own Git repo.
