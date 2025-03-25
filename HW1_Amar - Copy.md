Q1: What is the CLI and how to work with it.
a1: CLI is the Command Line Interface (CLI) that is used by a developer to navigate through a computer's file structure.


Q2: What is a versioning control system and why we need it.
a2: Versioning control system works a bit like a Time Machine, in the sense that you'll be able to revert to any saved state within a directory. So if you mangle your 
    site's directory structure, you can always use git to revert back to simpler times.


Q3: Understand the differences between Git and GitHub?
a3: Git is a command-line tool that works as a version control system to let you manage and keep track of your source code history and GitHub is the cloud based hosting         service that lets you manage git repositories.


Q4: Understand the difference between the main branch and other branches of a repository.
a4: Main Branch is also known as the Master Branch which the main working area of the repository whereas are copies of the main branch which allow to make changes to the        code base without endangering the original code in the master branch.


Q5: Understand what an IDE is.
a5: An IDE is a software application that provides a comprehensive environment for software development, combining tools like a code editor, compiler, debugger, and other       utilities into a single interface. Micrsoft Visual Studio is a popular IDE in the proramming industry.


Q6: How to open and use VS Code.
a6: To open VS Code on windows one can go to start open terminal/command prompt, type "code" and press enter. To use VS Code, one can navigate through the directory on the      left hand explorer panel to execute desired action or can create new folder, create new file, access existing file, navigate through directory using prompts provided 
    in resource 1.5.1 and 1.5.2


Q7: Development tools -- CLI, Git and GitHub, and VS Code.
a7: All the development tools answered and explained above.


Q8: Know what Jupyter Notebooks are.
a8: Jupyter Notebook is an open source web application used to create and share documents that contain live code, equations, visulaizations and text.
    i:   How to Install and start up Jupyter Notebooks -
         To instal Jupyter Notebooks in VS Code, to use directly inside the IDE Terminal we can use "pip install jupyter notebook" and then add the following VS Code         
         Extensions by Microsoft Jupyter, Jupyter Keymap, Jupyter Notebook Renderer, Jupyter Slide Show, Jupyter Cell Tags.
    ii:  How to use Jupyter Notebooks inside of VS Code -
         We can either Initialize Jupyter Notebook from the VS Code internal console by navigating to the correct directory in the terminal and then typing "jupyter 
         notebook" in the terminal and press enter OR we can use Jupyter Notebook inside VS Code, by simply creating a new file with the ".ipynb" extension.
    iii: Read the resources on beautifying Jupyter Notebooks -
         Done.


Q9: Know what type of programming language the Python language is
a9: Python is considered a high-level and Interpreted language. Python is different from major compiled languages, such as Java, C# and C++; Python code is not required to       be built and linked like code for these other languages.


Q10: Know how to install Python
a10: Python can be installed directly in the computer as a software but for the cohort there are two ways to use Python:
      1) IDE - By setting up and using the VS Code IDE 'Integrated Development Environment'.
               For this we first navigate to the correct directory, create a new folder is needed and then create a python file which should end with '.py' for example     
               'hello_world.py' and then access the file by typing 'python hello_world.py'
      2) CLI interpreter - By using built-in command-line interpreter to run Python commands and execute Python files.
               The most straightforward way to start working with Python is in an interactive Read-Eval-Print Loop (REPL) environment. That simply means starting up the 
               interpreter and typing commands to it directly. For this we can type the command "python" in the terminal and use python language.

      
Q11: Know how to start coding Python:
a11: We can run Python code in 2 different ways
       1) From the bash terminal - 
          a) Launch the Python CLI by typing 'python'
          b) Type python code syntax and execute for example type 'print("Hello, World!")' and press enter.
       2) From within VS Code -
          a) Navigate into the directory where we created the "hello.py" file
          b) In the terminal type the following command to execute the file: "python hello.py"
    i) how to create Python files in VS Code - 
       1) Open "SavvyCoders" folder in VSCode, and type "code ."
       2) Create a new folder called "activities"
       3) Create a file called "hello.py"
       4) Type the command print("Hello, World!")
       5) Save the file.
    ii) How to write Python code inside a Jupyter Notebook.
       1) Either Initialize Jupyter Notebook from the VS Code internal console.
          a) Navigate to the correct directory in your terminal.
          b) Type "jupyter notebook" in your terminal and press enter.
       2) Use Jupyter Notebook inside VS Code, simply create a new file with the ".ipynb" extension
          a) Clicking on an existing Notebook (a file with an .ipynb extension) should open the Jupyter notebook within VS Code.


Q12: Understand how to run your Python code:
     i)  How to run Python code files in the CLI -
       a) Launch the Python CLI by typing 'python'
       b) Type python code syntax and execute for example type 'print("Hello, World!")' and press enter.
       c) Ensure that the '>>>' prompt is displayed, and the cursor is positioned after it. The interpreter’s response should appear on the next line. You can tell it is               console output because the >>> prompt is absent in the response line.
     ii) How to run Python code files in VS Code -
       a) Navigate into the directory where python or ".py" file is created. 
       b) In the terminal type the following command to execute the file: "python FILENAME.py"
       c) The python code within the .py file will excute in the below line.
     iii) How to run Python code files in Jupyter Notebooks -
       a) Open Jupyter notebook as explained above.
       b) Create a new Notebook or open an existing one as expained above.
       c) Double click on a cell block, type the code and execute the cell by pressing "Shift+Enter" or clicking the "Run" button.
       d) We can also use the cell block to create markdown statements and type text if needed using prompts provide in the resources.
         
        
Q13: Understand some basics about debugging:
a13: Debugging is the process of detecting and removing existing and potential errors (aka 'bugs’) from software code. Errors could cause code to behave unexpectedly or           crash. Debugging is a foundational skill as it is very useful and an essential skill in coding/programming.
     i) Examples of Error Types - 
        SYNTAX errors – mistakes in the code like spelling, punctuation, spacing, incorrect labels, etc. The program won’t run.
        RUNTIME errors – occurs at the time of running or executing a program; program may hang or crash.
        SEMANTIC errors – code is grammatically correct but doesn't make any sense; it does not produce the expected results.
        LOGICAL errors –when instructions given do not accomplish the intended goal. EG: wrong calculations.
        
