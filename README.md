# Git Workshop Exercise
In this exercise your team will create a mini-website (with simple markdown pages) documenting your project.
There are several tasks to complete (listed as `GitLab Issues`), but take these with a pinch of salt.
The questions should get you thinking about positive open-source documentation, but the priority here is to **practice conflict resolution with Git**.

To complete the exercises you'll just need to edit markdown files (end with a `.md`) with any text-editor.
The `#`'s are for headings (more `#` means smaller).
Wrap text in `*` for italics or `**` for bold and `\`` for code-blocks (`\`\`\`` for multi-line code blocks).

Think very carefully about your actions (creating files, editing files, where you create a branch from...) and discuss any doubts/questions with your teammates.
If you stay conscious of what you're doing, you'll quickly become a Git lean mean machine!
Please **work on merging and fixing conflicts together** where possible.
Note that it may be useful to use a visual UI to show what changes have been made (VScode is a great choice).

# Setup and Workflow
Sart by forking and cloning this repository (`git clone YOUR_REPO_LINK`).
There will be a fork button near the top right hand side of the screen (left of the blue clone button).
**Only one person per-team should do this** (you can share screen with everyone else so they know how too though)!
Once you've got your own GitLab repository clone it (hitting the clone button and then HTTPS will give you the URL) to use in `git clone REPO_LINK`.

Once everyone knows what task they'll start with create a feature branch to work in (`git checkout -b some-feature-branch`, but use a meaningful name which doesn't include the words feature branch).
Although it won't be immidiately useful, do recall that you by default branch from your current (**not `master`**) branch.

> Remember, each task should be completed in a new branch!

You should gradually commit (`git commit -m "ADDED COOL THING/CHANGED BLAH BLAH BLAH"`) your changes.
Once you've completed a task make sure to push (`git push`) everything and create a pull request (through the website).

Before creating a pull request remember to get the latest changes (`git pull`).
This is one place where conflicts may occur (hint - this is when rebases are useful).

# Project Description

Microfluidics is a project working in collaboration with the Monash Applied Microfluidics & Bioengineering Lab, to assist in creating deep learning applications to assist with male fertility outcomes.

Our first objective as part of Microfluidics is to create a deep learning computer vision tool, based on a CNN, to assist fertility clinicians with the analysis and selection of sperm cells.

# How it works

Our project has begun by creating a skeleton model in pytorch, using transfer learning, which we are slowly building upon.

# Project Timeline

So far, we have built up a basic model aiming to beat the performance on the current state-of-the-art on our two datasets, SCIAN and HuSHem.

Over the next few months we will be working with Lindsay, who is a student working under Reza, to assist him in publishing a paper.

In a few months time we will hopefully have a new dataset available, having been made by a PHD student on Reza's team, and we will work on using a real-life dataset to train a model. 

Part 3: 
<a href="http://www.youtube.com/watch?feature=player_embedded&v=2rCP4CRRO7E&ab_channel=SE7EN13" target="_blank"><img src="http://img.youtube.com/vi/2rCP4CRRO7E&ab_channel=SE7EN13/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


Part 2: These are some further details about our project
blahblahblahblahblah
blahblahblahblahblah
v interesting

# Contributors
This project is done in collaboration by the members of the Monash DeepNeuron Microfluidics team. 

Project members:
* Jared - Project manager
* Nidhi
* Sahil (I was here)
* Rebekah

# Requirements
* Python 3
* PyTorch - a Python deep learning library
* Numpy
* Pandas

