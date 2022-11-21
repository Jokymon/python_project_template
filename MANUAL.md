This document contains additional instructions about how to use this Python
project template.

# Getting Started in VSCode

To get an initial virtual environment for your project, perform the following
steps:

  1. Type `Ctrl-Shift-P` and enter "Tasks: Run Tasks", hit the `Enter` key
  2. Select the task "Create Virtual environment" and hit the `Enter` key
  3. A message box will popup about noticing a new virtual environment and
     whether this should be used for the workspace. Choose 'Yes'

The full tutorial to get started with Python under VSCode can be found here:
https://code.visualstudio.com/docs/python/python-tutorial

## Enable Linting

VSCode and Python can help you to create code that is easier to read and more
standard compliant. VSCode can run a tool for you in the background that will
check if your code satisfies certain criteria and then mark your code where it
doesn't. The tool that makes these checks is called a "Linter". This project
template contains a simple configuration and small list of compliance rules to
get you started. It uses the Linter called `flake8`.

After you have created the virtual environment (see previous section for one
way of doing this), follow these steps:

  1. In a Terminal run the command `pip install -r requirements.txt`. This will
     install all necessary libraries for the Linter `flake8`.
  2. Type `Ctrl-Shift-P` and enter "Python: Select Linter", then hit the `Enter`
     key.
  3. From the Dropdown select the entry `flake8`.
  4. Type `Ctrl-Shift-P` and enter "Python: Enable/Disable linting", then hit the
     `Enter` key.
  5. Choose the option "Eanble".

Now your code will be run through the Linter every time you save the changes in
your file. When you violate one of the Linting-rules, you will see a blue,
wavy line appear below the violating line of code. Hovering over the marked
text with your mouse will show you what rule you violated.

# Submission via Moodle or other LMS

From the root directory of your project run the following git command:

    git bundle create <projectname>.bundle --all

Now you can simply upload the newly created file `<projectname>.bundle` to
Moodle.

Make sure you replace `<projectname>` in the above examples with a name that
identifies your own project.

## Using the provided VS Code task

Alternatively you can also use the VS Code task "Bundle for Submission" by
following these steps:

  1. Type `Ctrl-Shift-P` and enter "Tasks: Run Tasks", hit the `Enter` key
  2. Select the task "Bundle for Submission" and hit the `Enter` key

Now you should find a `.bundle` file in your project folder that is named
with your project folder name. This can be submitted to Moodle.