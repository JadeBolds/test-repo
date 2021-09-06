# test-repo
Follow along code assignment for github repo lesson

Full instructions for how to create a new repo and share it

-Create new Repo
-Create Read me 
  +echo "# the-name" >> README.md
  +git init
  +git add README.md
  +commit -m "first commit"
  +git remote add origin git@github.com:otherStuff/github_guide.git
  +push -u origin master
  
 -Get Repo up to date
  +git add .
  +git commit -m "second commit"
  +git push
  
-Set up TEAM
  +Settings -> Collaborators -> Add collaborator
  +If you're collaborating DON"T fork
  
-Branches should be related to fearures so that changes are categorized by function

-Submit Pull Requests
  +Everyone must push their branches then push the compare and pull button
  +Once you're at the "open a pull request" page write a breif description of what was actually changed
  +Merge the requests; you will want one person to do all of this
  +Review -> Approve -> Merge Pull Requests
