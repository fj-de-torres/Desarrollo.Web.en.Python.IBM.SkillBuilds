# Git Practice
Practicing with git and Github.<br>
I have accidentally deleted this file and its directory. After many attempts, what has worked for me to restore it, has been this:

1.- *git log* to view where I deleted the file or the last change before deletion.
<br>
2.- *git reset 08b286bf9b08ed0cf1c95164bebf53fd5b5aaf8* which is the id of the last commitment before delection.<br>
3.- *git add.* # It is not clear to me whether this step was necessary.<br>
4.- *git status* #I check here <br>
5.- *git restore --staged git.practice/README.md* # That's the file I deleted along with the directory that contains it.
<br>
6.- *git status* # Checking status again.<br>
7.- *git restore*  git.practice/README.md # I complete restoration.<br>
8.- *git status*<br>
9.- *git push* # final stage.
