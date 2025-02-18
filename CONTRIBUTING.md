# How to contribute


## Beginners
### Small changes (from few characters to a whole file)
1. From the [project's homepage](https://github.com/Venekiel/Origins-Vampire), go to the file you want to edit (or to the folder you want to create a new file in).
2. Make your changes.
3. Click on "Commit changes...", a green button in the top right corner of the page.
4. type in a message explaining what you tried to change with this modifications.
5. Select "Create a new branch for this commit and start a pull request".
6. Type in a **name for the branch** you are creating to help others know what it is about. See [Naming conventions > Branches](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#branches) for naming conventions.

Your changes will be tested and reviewed by me (i.e. Venekiel) or other contributors to make sure no bugs are introduced and that the source will remain maintainable.

### Bigger changes (more than a file)
1. Create a new branch :
   Go to the [project's branch list](https://github.com/Venekiel/Origins-Vampire/branches) and create a new one by clicking on the green button labelled "New branch" in the top right. See [Naming conventions > Branches](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#branches) for naming conventions.
2. Now from the [project's branch list](https://github.com/Venekiel/Origins-Vampire/branches), select the branch you newly created and edit the files you want to change.
3. Once you are done making changes, [create a pull request](https://github.com/Venekiel/Origins-Vampire/compare/latest...latest). See [Naming conventions > Pull requests]([#](https://github.com/Venekiel/Origins-Vampire/blob/doc/add-contributing.md/CONTRIBUTING.md#pull-requests)) for naming conventions.


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
