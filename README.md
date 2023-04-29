# svn_commands
The most useful commands used for the SVN repository 

- svn checkout <repository-url>: 
  This command is used to download a copy of the latest version of the code from the SVN repository.

- svn update: 
  This command is used to update your local copy of the code with any changes that have been made to the repository since your last update.

- svn add <file>: 
  This command is used to add a new file to the repository. After adding the file, you need to commit it to the repository.

- svn commit: 
  This command is used to upload changes made to your local copy of the code to the repository.

- svn status: 
  This command is used to display the status of files in your local copy of the code. It shows which files are modified, added or deleted.

- svn diff: 
  This command is used to view the differences between your local copy of the code and the version in the repository.

- svn log: 
  This command is used to display the revision history of a file or a directory.

- svn revert: 
  This command is used to undo changes made to a file or a directory in your local copy of the code.

- svn merge: 
  This command is used to merge changes made in one branch of the code to another branch.

- svn cleanup: 
  This command is used to clean up the working copy of the code and remove any temporary files or directories.

## Examples 

- svn checkout https://svn.example.com/repo/trunk

- svn update

- svn add myfile.txt

- svn commit -m "Added new feature"

- svn revert myfile.txt

- svn copy <local folder>  https://svn.example.com/repo/branches/mybranch

- svn switch https://svn.example.com/repo/branches/mybranch

- svn merge https://svn.example.com/repo/branches/mybranch https://svn.example.com/repo/trunk

- svn diff -r 123:456 myfile.txt

- svn log myfile.txt

- svn propset svn:externals "EXTERNAL_PATH LOCAL_PATH" PROJECT_PATH
  - svn propset svn:externals "https://github.com/user/repo/trunk/ibrary /generic_library" svn://svnserver/project/myproject
  
- peg revision 
  - svn cat -r 100 myfile.txt

  




