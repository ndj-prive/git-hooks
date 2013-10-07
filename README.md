git-hooks
=========
[Draft]

The pre-commit hook checks
-------------------

- Running compass process.
- Debuging strings - var_dump alert console.log
- If is a drupal installation and if drupal core is hacked
-- Also check if no settings.php or files folder is added to a commit
- Check if we push or the master branch - in our case most of the time production

Install git hooks globale on osx put the pre-commit hook in 

  /usr/share/git-core/templates/hooks/
  
or 

  [PROJECT_FOLDER]/.git/hooks
  
make sure the script is executable 'sudo chmod +x .git/hooks/pre-commit'
  
I have not yet check a linux distro or windows

enjoy
