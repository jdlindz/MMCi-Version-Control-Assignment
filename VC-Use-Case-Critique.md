Lecture 5 Laboratory in Version Control

This will be a team project focused on using version control to cooperatively compose and edit a document. The document should be on the subject "Interesting use cases for version control". If you Google the topic, you should be a variety of cases in which people have used version control for interesting projects, not necessarily for developing software. What I'd like your team to do is find such a use case and discuss/critique it. We will use this class time as a lab for getting familiar with using Git and Github with me and Ben Neely in the room so you can ask questions.

Goals & Assignment

Each team should create a Project in Github
As described in van Strien, create a plain text document and place it under version control, even better if you use Markdown, i.e. create a "*.md" file (see here for Github-flavored markdown).
The document should have these sections:

Description of Use Case

Why is it a good use of version control (Git/Github)?

Where does it fall short in leveraging version control tools?

What would you do differently?

Within the repository, for many of the directories and subdirectories, there is not consistent verbiage to denote what exactly was done when updates were performed with the coding. For example, within the “Samples” subdirectory, the verbiage clearly states that the file names were changed for sample clinical documents, however inside the “ehr-edition” subdirectory the update comment is “fix deployment issues”. While Git does allow the viewing of a prior version of files that were changed, it would be beneficial to have a standard naming convention for update comments.

Within the project website, which is hosted by GitHub, in the “Documentation” dropdown menu there are user guides which cover many roles and versions. For the typical end user, i.e. non-technical person, viewing the project website, there is room for confusion related to the multiple versions and roles. This could be simplified by larger icons related to role and then smaller icons or hyperlinks related to the different versions. While the most recent version is listed at the top of the webpage, I would deemphasize older versions of the documentation by either decreasing the font size associated with their hyperlinks or move to another webpage altogether. 

Reviewing the repository there is no notation of testing of the application and how the application fared. Utilizing the “Find File” feature does return results within the “scripts” subfolder.  These files do not denote how the application fared during testing utilizing these scripts. If the coding is public, at a minimum there should be documentation regarding how well the application performed in testing of the most recent released version. 

We suggest that each team create a Github "Organization" (see here) and have all the team members join it.

The organization should create a Project entitled "mmci-versioncontrol-assignment"
As the organization, should create an empty *.md document on Github using the 'create new file' button
Then all members should 'fork' to clone the repo into their personal Github repos

In performing each assignment some version control conditions have to be met:

Each member of a team must perform a 'commit'

Each member of a team must perform a 'pull request'

You must use a 'branch' for each section of the document

When you are ready to submit your assignment on 7 July 2018

Create a 'Production' branch which will represent the final version of the assignment

Add me as a collaborator on your Repo (unless you've made it open to the public, otherwise just send me a link to the repo)
