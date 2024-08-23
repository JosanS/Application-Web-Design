
# Diseño de Aplicaciones Web
### Profesor Jesús Alberto Garza Guerrero

### Josan Salinas Avila
### 2981325
### Ingenieria en Desarrollo de Software
### 6to Semestre

## List of commands used in git:
1.Check the status of a local repository

	**git status**

2.Add individual files or globally

	*Add a specific file:*
	**git add <file_name>**

	*Add all changes:*
	**git add**

3.Add comments to the commit

	**git commit -m <your commit message here>**

4.Upload your changes to the remote repository

	**git push origin <branch_name>**

5.Create, browse and delete branches

	*Create a new branch:*
	**git branch <new_branch_name>**

	*Switch to a different branch:*
	**git checkout <branch_name>**

	*Create and switch to a new branch in one command:*
	**git checkout -b <new_branch_name>**

	*List all branches:*
	**git branch**

	*Delete a branch:*
	**git branch -d <branch_name>**

	*To force delete a branch that hasnt been merged:*
	**git branch -D <branch_name>**

6.Roll back a repository to a specific commit

	*Reset to a specific commit (soft reset, keeps changes in working directory):*
	**git reset --soft <commit_hash>**

	*Reset to a specific commit (hard reset, discards changes):*
	**git reset --hard <commit_hash>**
