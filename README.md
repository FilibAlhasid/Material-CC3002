# Material-CC3002

Manual uso de git

git checkout -b hotfix-{version} master
git status
git add -u
(si hay archivos nuevos:
git add <new files>
)
 
 git commit -a -m "Mensaje"
 
 (volviendo a master para el merge)
 git checkout master
 git merge --no-ff hotfix-{v1}
 git tag -a- v1
 git push origin master
 git push origin --tags
 
 
 
 
 
 
