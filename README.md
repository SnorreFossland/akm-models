# AKM Modelling

## Introduction

AKM Modelling can be done locally with models stored in local Project.json files.
AKM Modelling can also be done as a collaborate task with several team members with Project.json files stored in a GitHub repository.

## Lets get started

(you can duplicate this browsertab and move it on the side, to have it avaiable when doing the procedure)

Open the webpage:  

<https://akmclient-beta.herokuapp.com/modelling> latest version with newest features

<https://akmclient.herokuapp.com/modelling> previous more tested version

---

## 1. Open Project files

### Open Project file

<details><summary markdown="span">Open local project files: <code> Click: "Choose file" button</code></summary>

Click on: Project files: "Choose file" button and select the project file you want to load (.json file).

![alt text](./img/ChooseFile.png)

The selected file will be loaded in the AKM Modeller.

</details>

or

<details><summary markdown="span">Open GitHub repository AKM project files in AKM Modeller: <code> Click on: "GitHub" button</code></summary>
..

Click on "GitHub" button to open the dialog for GitHub repository and fill in the required fields.

- Repository URL:  <https://api.github.com/users/UserName/repos/>

then click on: "LIST MODELS" button and then select a model in the "Select Model" dropdown list.

(The list is from the **main** branch of the repository.)

The model will be loaded in AKM Modeller.

Click on "X" button in the top right corner to close the GitHub repository select dialog.

---

</details>

---

## 2. Work with your model project

After updating your model project, you can save it locally.

## 3. Save your model project to Local file

<details><summary markdown="span">To save local project files: <code> Click on: "Save" button</code></summary>

To save the current project.json file Click on the "Save" button.

The file will default be saved in Download folder as the "Projectname"_project_"date".json file.

</details>

## 4. Upload the project file to GitHub repository

<details><summary markdown="span">Go to the GitHub repository, and open the model folder <code> Open the model folder </code> </summary>

(https://api.github.com/users/UserName/repos/)

</details>

<details><summary markdown="span">Upload file (the updated or new model project.json)  <code> Drag or select file to upload and click "Commit changes" </code></summary>
..

Drag in or "choose your files.

Select "Creat anew branch for this commit and start a pull request.

Then click "Commit changes" button.


![Code.png](./img/DraginFiles.png)

</details>

<details><summary markdown="span">Compare and Pull request <code> Click "Compare & pull request" button.</code></summary>
..

Click "Compare & pull request" button.

![Code.png](./img/ComparePullRequest.png)

</details>

<details><summary markdown="span">Create Pull Request for the uploaded model project file <code> Click "Create pull request" button.</code></summary>
..

(Add a comment and)Click "Create pull request" button.

![Code.png](./img/CreatePullRequestUploadFiles.png)

</details>

<details><summary markdown="span">Confirm Merge <code> Click "Confirm merge" button</code></summary>
..

Click "Confirm merge" button.


![Code.png](./img/ConfirmeMergeOfUploadedProject.png)

</details>

<details><summary markdown="span">The update of the project file to the main branch is completed <code> "Sucessfully Merged!" </code> </summary>
..

The Main branch is updated with the new model project file

![Code.png](./img/SuccessfullyMerged.png)

</details>

<details><summary markdown="span">Delete you temporary branch <code> Click: "Delete branch" button</code></summary>
..

Your branch which was created for the upload of the model project file can be deleted.


</details>

