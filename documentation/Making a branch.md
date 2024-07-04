# Making a branch

Here I will detail the instructions I am using to explore the branching functionality of Git while making a separate webpage for my CV.

## Step 1: Create a New Branch

Before making any changes, you'll want to create a new branch in your Git repository. This allows you to work on a new feature or change without affecting the main codebase.

```git checkout -b feature/cv-page```

This command creates a new branch named `feature/cv-page` and switches to it.

## Step 2: Make Your Changes

Now, on your new branch, you can make the necessary changes to create a separate page for your CV. Based on the previous instructions:

1. Create `cv.html`: Create a new file named `cv.html` in your project directory and add the HTML structure to embed your CV PDF using an `<iframe>`.
2. Update `index.html`: Modify the `index.html` file to link to `cv.html` instead of directly linking to the PDF file.

## Step 3: Commit Your Changes

After making the changes, you'll need to commit them to your branch. First, add the changes to the staging area:

```git add cv.html index.html```

Then, commit the changes:

```git commit -m "Create separate CV page and update link in index.html"```

## Step 4: Push the Branch to Remote

To share your new branch with others or to create a pull request, you'll need to push the branch to the remote repository:

```git push origin feature/cv-page```

## Step 5: Create a Pull Request

* Go to your repository on GitHub.
* You'll likely see a prompt to create a pull request for your newly pushed branch. Click on "Compare & pull request".
* Fill in the details of your pull request and submit it.

This process allows others to review your changes before they are merged into the main branch, facilitating collaboration and code review.

## Step 6: Merge the Pull Request

Once your pull request has been reviewed and approved, you can merge it into the main branch. This can typically be done directly on GitHub's interface.

## Step 7: Pull Changes to Your Local Main Branch

After merging, make sure to update your local main branch:

```git checkout main```
```git pull origin main```

This workflow allows you to safely experiment with changes in a separate branch, review them, and then integrate them into your main project without disrupting the main codebase.


