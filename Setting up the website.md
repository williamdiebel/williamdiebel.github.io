# Step 1: Create a GitHub Repository

1. Log in to your GitHub account and go to your GitHub dashboard.

2. Create a new repository:

* Click the "+" icon at the top right and select "New repository".
* Name your repository with the following format: `username.github.io` (replace `username` with your GitHub username).
* Make sure the repository is public and check the option to "Initialize this repository with a README".

*Click "Create repository".

# Step 2: Set Up GitHub Pages

1. Navigate to the repository settings:

* Go to the repository you just created.
* Click on the "Settings" tab.

2. Enable GitHub Pages:

* Scroll down to the "GitHub Pages" section.  
* Under "Source", select the branch you want to use (usually `main` or `master`).
* Click "Save".

# Step 3: Create Your Website Content

1. Clone the repository to your local machine:

* Open a terminal or command prompt.

* Run `git clone https://github.com/username/username.github.io.git` (replace username with your GitHub `username`).

2. Navigate to the cloned repository:

* `cd williamdiebel.github.io`

3. Create an `index.html` file.

* Use a text editor to create an index.html file in the repository directory.
* Add some basic HTML content, for example:

```
<!DOCTYPE html>
<html>
<head>
    <title>Welcome to My Website</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>Welcome to my personal/professional website.</p>
</body>
</html>
```

4. Commit and push your changes:

* Run `git add .`
* Run `git commit -m "Initial commit"`
* Run `git push origin main` (or `master` if that's your default branch)

# Step 4: Visit Your Website

1. Wait a few minutes for GitHub to build your site.

2. Visit your website:

* Go to https://username.github.io (replace username with your GitHub username).

# Customization and Further Development

* Customize your website:
    * You can add more HTML, CSS, and JavaScript to enhance your site.
    * Consider using a static site generator like Jekyll for more advanced features and templating.
* Check GitHub Pages documentation for more options and configurations:
    * [GitHub Pages Documentation](https://docs.github.com/en/pages)






