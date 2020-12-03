# section 3: Basic programming skills

<table style="float:right" width="50%">
    <tr>
        <td>                      
            <div style="text-align: left"><a href="" target="_blank">Dr Peter Causey-Freeman</a></div>
            <div style="text-align: left">Lecturer - Healthcare Sciences</div>
            <div style="text-align: left">(Clinical Bioinformatics)</div>
            <div style="text-align: left">The University of Manchester</div>
         </td>
         <td>
             <img src="https://github.com/i3hsInnovation/resources/blob/master/images/pete.001.png?raw=true" width="30%" />
         </td>
     </tr>
</table>

## Working solo and in a team
*In this section you will learn the basics of Shell Scripting and Python programming*
for those of you new to programming, this may seem daunting. However, you are not alone. By now you should be set up in 
Slack and also be aware of Git Issues. The notebooks in this section are designed for you to work through solo, but this
section of the course is structured so that you can work collaboratively. To complete the exercises we have set, you 
will need to interact with your team-mates and the facilitators (Product owners) using slack and git issues. 

<br>

*Why? Because some of the exercises are deliberately vague to encourage discussion. The ethos of this unit is team work,
so you will need to get used to working collaboratively to achieve the tasks we have set you throughout the unit.*

As part of this section, you will also learn the following skills
- Creating a branch in git for you to work on
- Committing and pushing code to your branch
- Pulling your team-mate's code from their branches and helping them to complete coding projects
- Effective communication in slack and Git issues

### Creating your branch
At this stage of the project, you should have cloned the course into a directory called 
`PycharmProjects` which is in your home directory
If not, go back to the rise material and `clone` the course as instructed

Once you have the code in place:
 - `cd` into this directory.
 - run the command "git branch <name>": for example I would run "git branch pete_CF"
 - run the command "git checkout <name>": for example I would run "git checkout pete_CF"
 - check you are on the correct branch by running "git status"
 
### Committing and pushing
When prompted in the tutorials, or as frequently as you feel comfortable with, push your code
up to your branch. Additional instructions will be provided in the notebooks
 
The stages you will need to complete are
- "git status" which shows you the locations of modified and un-staged changes
- "git add <changed files>" which stages your modified files
- "git push -u origin <name>": for example I would run "git push -u origin pete_CF"
***Note: Only commit and push your scripts and notebooks. Do not commit alignment files, even the shortened alignment 

### Pulling your team-mate's code and navigating branches
Before pulling your team-mate's code, make sure your changes are staged and committed.
***Note: You do not need to push the code!***
Run the following commands after a team mate has asked you for help
- "git fetch --all"
- "git checkout <team-mate's branch>"
- "git pull"
You can then help your team mate, commit your changes to their code and push your
changes up to your team-mate's branch (see committing and pushing)

### Workflow
In this section the work flow is:
- Introduction to programming shell-scripts
- Introduction to programming with Python
- When you have finished both notebooks, commit 
your changes and scripts and push them to your github branch
