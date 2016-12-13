# Liquid Theme DE Setup

### Install Shopify_theme

Install Shopify_theme in your machine. If you are using OS X, you don't need to install Ruby. This is the link to Shopify_theme (https://github.com/Shopify/shopify_theme). We will use this command line tool to manage and edit the theme file, upload our theme into shopify and debug our code.

**DONT set up the theme as told in shopify_theme reference. The config file has been included in the repository.**

### Create Your Repository

- Create a new folder in your local machine and init it as Git Repository by using either git or GitHub GUI. 
- Add this repository as the remote repo of your local repository.
- Run a pull operation to get all the code in master branch.

Once you see all the code is downloaded into your local repository, you are all-set. 
**Please DONT push any change to the repository for now. ** I will create a branch exclusively for you to use later.

Git Command:
```
git init
git remote add origin master my_repo_url
git pull origin master

```

### Test Your Development Environment 

Open the internal terminal of your OS and naviagte to your local repository direcotry. Then run below command:

```
theme open
```

If you can see your browser pop up displaying your shopify theme, you are all set. Otherwise, please try to follow above step and try again.


### Suggestion

Visual Studio Code integrate the internal terminal and git. It would give you a lot of convenience during your coding. 

