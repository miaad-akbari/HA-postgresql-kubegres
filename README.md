# Postgres-Cluster

kubegres-system for clustering control management in clustering

step1: 
apply control management apply https://kubegres.io  

step2
sc or pvc for  backup "  backup database >> pvc create 

step3
cronjob name pvc and storageclassname 



note: 
if pod is pending > fix bound storage or pvc or pv pvc check 

or syntax manifest postgres.yaml or postgres

# Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.com/miadakbari/postgres-cluster.git
git branch -M main
git push -uf origin main

====================================

#Postgres-Cluster

for ha postgres > kubegres https://kubegres.io
==================================================================================


