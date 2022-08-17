# AKM Modelling

## Introduction

AKM Modelling can be done as a individual task with models stored in local Project.json files.
It can also be done as a collaborate task with several team members.

Project.json files can be saved

- locally on your computer (PC) and loaded in the AKM Modeller when needed.
- globally in a GitHub repository and loaded in the AKM Modeller when needed.

## Lets get started

Start AKM Modeller by selecting "Modelling" in the top menu.

---

## 1. Use Local Project files

<details><summary markdown="span">To open local project files: <code> Click: "Choose file" button</code></summary>

Click on: Project files: "Choose file" button and select the project file you want to load (.json file).

![alt text](./img/ChooseFile.png)

The selected file will be loaded in the AKM Modeller.

</details>

---

<details><summary markdown="span">To save local project files: <code> Click on: "Save" button</code></summary>

To save the current project.json file Click on the "Save" button.

The file will default be saved in Download folder as the "Projectname"_project_"date".json file.

</details>

---

## 2. Use GitHub Project files

### 2.1. To open GitHub project files

<details><summary markdown="span">To open GitHub repository AKM project files: <code> Click on: "GitHub" button</code></summary>

Click on "GitHub" button to open the dialog for GitHub repository and fill in the required fields.

- Repository URL:  <https://api.github.com/users/UserName/repos/>
- Repository name: RepositoryName
- Branch name:     Main (default and cannot be changed)
- Model path:      Path/To/Model/Folder

then click on: "LIST MODELS" button and then select a model in the "Select Model" dropdown list.

The model will be loaded in AKM Modeller.

Click on "X" button in the top right corner to close the GitHub repository select dialog.

---

</details>

### 2.2. To save GitHub project files

#### 2.2.1. Prepare a branch to upload the project file too

<details><summary markdown="span">Go to the GitHub repository and into the model folder <code> Open Github.com </code> </summary>

To keep track of the changes we will use GitHub's versioning system.

Go to the GitHub repository in the web browser (<https://github.com/UserName/RepositoryName>)

![Code.png](./img/Code.png)

Navigate to the model folder (StartModels, Models etc. by opening the folder).

</details>

<details><summary markdown="span">Open the Issues <code> Click "Issues" in the menu</code></summary>

This will be used to keep track of the changes.

Create a new issue in the GitHub repository by clicking on Issues in the menu.

![alt text](./img/Issues.png)

</details>

<details><summary markdown="span">Create a "New Issue" <code> Click "New Issue" button</code></summary>

Click on the "New Issue" button.

![NewIssue](./img/NewIssue.png)

---

</details>

<details><summary markdown="span">Name and submit the Issue ...  <code> Type in Name (and description) </code></summary>

Type a name and description for the issue in the "Title" and "Description" field.

then click on the "Submit New Issue" button.

![NewIssue](./img/SubmitNewIssue.png)

---

</details>

<details><summary markdown="span">Go to Create branch <code> Click "Create a branch" link (lower right in the page)</code></summary>

![Add file](./img/NewIssue.png)

---

</details>

<details><summary markdown="span">Create the new branch  <code> Click "Create branch" button</code></summary>

Click on the "Create branch" button.

![Add file](./img/CreateBranchCheckout.png)

---

</details>

<details><summary markdown="span">Checkout the branch  <code> (only if local repository)</code> (this step can be skipped)</summary>

(If you want to clone to a local repository you can copy these two lines and execute them in your terminal.)

![Add file](./img/CheckoutLocalBranch.png)

---

</details>

---

In the following we will use the upload file function to upload the model project file to the GitHub repository,  
(so the local clone is not necessary and the copying of the two lines can be dropped.)

#### 2.2.2. Upload the project file

<details><summary markdown="span">Go to the GitHub repository, your branch and into the model folder <code> Select branch (not main or master)</code></summary>

Select the branch you created the last step in 2.2.1.

![Code.png](./img/ChooseBranch.png)

</details>

<details><summary markdown="span">Upload file (the updated model project.json)  <code> Drag or select file to upload and click "Commit changes" </code></summary>

Drag in file and click "Commit changes" button.

![Code.png](./img/DraginFiles.png)

</details>

<details><summary markdown="span">Compare and Pull request <code> Click "Compare & pull request" button.</code></summary>

Click "Compare & pull request" button.

![Code.png](./img/ComparePullRequest.png)

</details>

<details><summary markdown="span">Create Pull Request for the uploaded model project file <code> Click "Create pull request" button.</code></summary>

As you see this will create a pull request for the uploaded model project file from your branch to the main branch.

(Add a comment and)Click "Create pull request" button.

![Code.png](./img/CreatePullRequestUploadFiles.png)

</details>

<details><summary markdown="span">Confirm Merge <code> Click "Confirm merge" button</code></summary>

(Add a comment and) Click "Confirm merge" button.

![Code.png](./img/ConfirmeMergeOfUploadedProject.png)

</details>

<details><summary markdown="span">The update of the project file to the main branch is completed <code> "Sucessfully Merged!" </code> </summary>

The Main branch is updated with the new model project file

![Code.png](./img/SuccessfullyMerged.png)

</details>

<details><summary markdown="span">Delete you temporary branch <code> Click: "Delete branch" button</code></summary>

Your branch which was created for the upload of the model project file can be deleted.

![Code.png](./img/SuccessfullyMerged.png)

</details>
