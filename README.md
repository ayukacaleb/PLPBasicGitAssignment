+ GitHub Repository Creation:

  - Log in to your GitHub account.
  - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").
  - Check the box Initialize this repository with a README.
+ Open Git bash and write the following commands
  - cd C:/ (navigate to your desired Drive)
+ Create folder with name "PLPBasicGitAssignment"
  - mkdir PLPBasicGitAssignment (makes directory with name PLPBasicGitAssignment)
+ Navigate into the folder
  - cd PLPBasicGitAssignment (gets into the folder with name PLPBasicGitAssignment)
+ Initialize Git
  - git init (Initializes)
+ Link local repo with the one in Github
  - git remote add origin github.com/ayukacaleb/PLPBasicGitAssignment.git (links your local repository to the github repository)
+ Create text file and name it the input something
  - cat > hello.txt
  + Hello,Git
  - press Ctrl+D to save
+ Stage the changes
  - git add hello.txt
Commit the changes.
  - git commit -m "Add hello.txt with a greeting"
+Push the committed changes to the Github repository
  - git push -u origin main
