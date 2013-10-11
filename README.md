git-hooks
=========
[Draft]

The pre-commit hook checks
-------------------

- Running compass process.
- Debuging strings - var_dump alert console.log
- If is a drupal installation is found and if drupal core is hacked
-- Also check if no settings.php or files folder is added to the repo
- Check if we push to the master branch - for me most of the time the production branch

Install git hooks globale put the pre-commit hook in 

  /usr/share/git-core/templates/hooks/
  
or for each project

  [PROJECT_FOLDER]/.git/hooks
  
make sure the script is executable 'sudo chmod +x .git/hooks/pre-commit' or 'sudo chmod +x /usr/share/git-core/templates/hooks/pre-commit'
  
I have not yet checked on windows

enjoy
