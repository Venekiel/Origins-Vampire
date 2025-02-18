# How to contribute


## Beginners
1. Create a new branch :
   Go to the [project's branch list](https://github.com/Venekiel/Origins-Vampire/branches) and create a new one by clicking on the green button labelled "New branch" in the top right. See [Guidelines > Naming conventions > Branches](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#branches) for naming conventions.
2. Now from the [project's branch list](https://github.com/Venekiel/Origins-Vampire/branches), select the branch you newly created and edit the files you want to change.
3. Once you are done making changes, [create a pull request](https://github.com/Venekiel/Origins-Vampire/compare/latest...latest). See [Guidelines > Naming conventions > Pull requests](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#pull-requests) for naming conventions.

   - In the "base" dropdown, select the branch you want to apply your changes to. (most likely "latest")
   - In the "compare" dropdown, select the branch containing your changes.
   - click on the green "Create pull request" button.
   - Name your pull request. See [Guidelines > Naming conventions > Pull requests](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#pull-requests) for naming conventions.
   - You can assign yourself to the pull request so the community knows who worked on it and so you receive updates on your pull request's status.
   - Add a description to explain why you made those changes, why you made it a certain way, and how people could test the effect of the changes.
   - You can also add labels that match the changes.

Your changes will be tested and reviewed by me (i.e. Venekiel) or other contributors to make sure no bugs are introduced and that the source will remain          maintainable.


## Guidelines
### Naming conventions
Excepted in-game translations, EVERYTHING should be typed in english to ensure the majority of people are able to read and write it.

#### Branches
Branch names are made to know at a glance what the changes on that branch are about.
A good rule of thumb is to follow this format :
```txt
[type]/#[issue-id]/[my-branch-name]
```
- The **type** represents what type of change you are introducing, is it a bug fix, a new feature, new documentation ?
   **Example : "doc"** (stands for documentation changes)
- The **issue id** is meant to link the branch to the related issue. If there is none, skip this part.
   **Example : "#43"** linking to [this issue](https://github.com/Venekiel/Origins-Vampire/issues/43).
- The **name** should be a short title explaining what the changes are about.
   **Example : "add-contributing.md"** suggesting that we are adding a contributing.md file to explain to people how they can contribute to the project.

   Assembling everything from this example would look like "doc/#43/add-contributing.md".

#### Pull requests
Pull request names are made to identify what the pull request is about. You can stick to the following format :
```txt
[source-branch-name] into [target-branch-name]
```
- The source branch is the branch containing your changes. ("doc/#43/add-contributing.md" in the case of our above example)
- The target branch is the one you want to add your changes to. (generally "latest" will be your target branch)

   The pull request name from our example would be "doc/#43/add-contributing.md into latest".
