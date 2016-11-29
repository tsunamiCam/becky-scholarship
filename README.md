# becky-scholarship

Running the site locally (this makes sure that the url is set correctly):

jekyll serve --baseurl ''


Cloning the website:

git clone https://github.com/tsunamiCam/becky-scholarship.git

This creates a becky-scholarship git repository in where this command is executed.

Check that it has all the required branches (remote and local):

git branch -r
git branch -l

Create a branch and make changes to it:

git branch branch_name
git checkout branch_name

Commit changes:

git commit -a -m 'msg describing what you did'

Merge branch with master:

git checkout master
git merge branch_name

Delete branch when it is no longer required:

git branch -d branch_name

Update the gh-pages branch at push to remote:

git checkout gh-pages
git merge master
git push origin gh-pages