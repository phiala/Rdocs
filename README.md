# Rdocs
R documentation

The R documentation is sometimes confusing to non-programmers. This is a trial project to edit the R documentation and submit the edited pages to R Core for potential inclusion.



# Using git to work with GitHub

These steps only need to be done once.

	git init
	git remote add origin https://github.com/phiala/Rdocs.git
	git fetch origin

	# set up a local copy of the repo
	git clone https://github.com/phiala/Rdocs.git
	cd Rdocs

	# create a local copy of the dev branch
	git checkout dev


Your local git repo is now set up. Make your desired changes.

	# save those changes to the local repo
	git commit -a -m "Commit message"

When you're satisified, upload your changes to the GitHub dev repo.

	git push origin dev

Finally, you'll go to the GitHub page and submit a pull request with more details. One of the admins will review your request and add it to the master branch.
