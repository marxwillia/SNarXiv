# SNarXiv
SNarXiv is a collection of summaries of supernova related arXiv papers.
It is meant to help the supernova community stay updated on recent 
research posted to arXiv, as well as act as an educational tool for new
members of our community.  

## Installation

1. Fork this repository to your github account.
2. Clone your forked repo: `git clone git@github.com:your-user-name/SNarXiv.git`
3. Add upstream: `git remote add upstream git@github.com:marxwillia/SNarXiv.git`


## How to contribute:

1. Navigate to the root directory of the cloned repo on your local machine.
2. Make sure you are on the main branch using `git status`. If you are not, 
checkout the main branch using `git checkout master`
3. Update using `git fetch upstream` and `git pull upstream master`
4. Update your forked repo in your local github using `git push origin`
5. Create a new branch: `git branch <name of your new branch>` 
6. Checkout your new branch: `git checkout <name of your new branch>`
7. Navigate to the posts directory: `cd posts/`
8. Copy the new paper template: `cp post_template.rst
 <name of your new post file>` (filename should end in .rst)
9. Answer the questions in your new post file.
10. When you are finished writing your post, add it using 
`git add <name of your new post file>`
11. Commit your changes: `git commit -m <brief description of your post>`
12. Push your changes: `git push`
13. Open a Pull Request!