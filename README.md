# Setting Up Visual Studio Code (The IQSS Way)

With its Copilot integration and a marketplace full of extensions, we recommend using **Visual Studio Code (VSCode)** for your coding IDE. It is especially useful if you are in academia, and need to write in R[^1], Python, LaTeX, etc. 

## Table of Contents
1. Instructions for Downloading VSCode
2. Importing Our Recommended Profile

## 1. Instructions for Downloading VSCode:
Visual Studio Code has [instructions](https://code.visualstudio.com/learn/get-started/basics) for getting started.

You can download VSCode directly from their [website](https://code.visualstudio.com/download) for your operating system.

Unzip the download (mine was called "VSCode-darwin-universal.zip), and then click on the new application (Visual Studio Code). A pop-up will ask you if you want to open an app downloaded from the internet. Click open.

Congrats, you've downloaded VSCode!

## 2. Importing Our Recommended Profile
* Inside VSCode, click on the settings icon in the bottom-left corner
* Select "Profiles (*Name of your current profile*)" &#8592; this should be "Profiles (Default)" if you are doing this for the first time
* Select "Import Profile"
* Copy and paste the following URL into the search bar pop-up that says "Provide Profile Template URL": https://vscode.dev/profile/github/db112ae4b5aef7a82c7284c2e0525ad2
* A pane on the left will pop up. Leave everything checked off, and select the blue "Create Profile" button
* Enter a name for this profile in the text pop-up, such as "IQSS Recs"
* Leave everything checked off, and select the blue "Create" button

Now the settings icon should have a short descriptor bubble attached, e.g. "IQ", and if you click on it, you should see that it now says "Profiles (*Profile Name*)", such as "Profiles (IQSS Rec)"

Congrats, you've imported our recommended profile!

### Installing our Recommended Extensions:
* In the left-hand toolbar, select Explorer (the top-most icon).
* Open this downloaded repository.
* Click on extensions_to_copy.json in the Explorer pane.
* Copy the text from this file.
* In the left-hand toolbar, select Extensions (four box icon with one slightly off)
* In the Extensions pane, in the search bar, type "@recommended" and two categories will pop up: Workspace Recommendations and Other Recommendations.
* Select the dropdown arrow next to Workspace Recommendations.
* Click on the pencil icon. A file called extensions.json will open, and it will be mostly empty. (To be sure this is the correct file, it should open with ".vscode > extensions.json > [] recommendations" under the title of the file.)
* Paste in the text we copied earlier.
* Save the file.
* In the Extensions Pane, there now should be 22+ extensions in your Workspace Recommendations.
* Click the cloud icon ("Install Workspace Recommended Extensions").
* Congrats! Our recommended extensions should all be installed.

### Installing our Recommended Keyboard Shortcuts:
* Select the Settings icon in the bottom-left corner of VSCode.
* Select 

If you **have** used VSCode before, this process will be a little different:
* list here.

### Extensions:
* **Azure Repos**:
  * Dependency for GitHub extensions.
* **Better Comments**:
  * Color codes types of comments with symbols at the beginning of each. For example, there are:
    * "*" for highlighting a comment (green)
    * "!" for an alert (red)
    * "?" for a question (blue)
    * "TODO" for a to-do (orange)
    * "//" for a strikethrough
  * You can also customize your own.
* **GitHub Copilot**:
  * In-line suggestions: Copilot will anticipate what you are about to type. You can accept these suggestions, or keep typing.
* **GitHub Copilot Chat**:
  * In-line chat: You can use Cmd+I to start an inline chat, where you can ask Copilot to do something for you. One of my favorites is to ask Copilot "Can you write me the outline of a LaTeX document?"
  * Side chat: You can open up a side-pane for a continuous chat with Copilot, much like Chat-GPT. You can ask Copilot to explain things to you, or to make suggestions.
* **GitHub Pull Requests and Issues**:
  * Allows for a smoother integration of GitHub into VSCode.
* **GitHub Repositories**:
  * Another extension which helps to integrate your repositories into VSCode.
* **indent-rainbow**:
  * Highlights vertically along indents, allowing you to see the different levels of structure in your code.
* **LaTeX Utilities**:
  * Extension pack for LaTeX Workshop. Includes quicker paste options, live snippets, and word count.
* **LaTeX Workshop**:
  * Includes many features, including snippets, shortcuts, and pdf-viewing.
* **Live Preview**:
  * Allows you to see HTML previews inside VSCode.
* **LTeX - LanguageTool grammar/spell checking**:
  * Underlines potential spelling and grammar mistakes.
* **Path Autocomplete**:
  * Autocompletes paths for files inside your repository.
* **R**:
  * Allows you to use R in VSCode, with snippets and various viewer options.
* **R Debugger**:
  * Integrates the debugging process for R into VSCode.
* **Rainbow CSV**:
  * If you view a CSV file inside VSCode, each variable will be color-coded (for easier viewing)
* **Remote Repositories**:
  * Dependency for GitHub extensions.
* **Settings Cycler**:
  * Necessary for using special keyboard shortcuts to toggle settings on/off.
* **Toggle**:
  * Necessary for using special keyboard shortcuts to toggle settings on/off.
* **vscode-icons**:
  * Includes additional graphic icons for file types, etc., inside VSCode.
* **Word Count**:
  * Provides additional word count support for markdown documents.
* **Zotero LaTeX**:
  * Allows for more smooth integration for Zotero in LaTeX documents.

## Instructions for Setting up R in VSCode:
* list here

## Instructions for Setting up LaTeX in VSCode:
* list here

## Contact Us:
This is a work in progress! If you like to use VSCode for other languages (Python, etc.), let us know which extensions and settings you like -- we'll add them in to our instructions. If you have additional extensions, settings, or keybindings you'd like to share, please do so!

You can contact me at dominic_skinnion@iq.harvard.edu. Thanks!

[^1]: My personal opinion: RStudio also has Copilot integration now, so that is still a great alternative if you are just writing .R or .Rmd files. Some may even prefer it! I suggest taking a look at Matt Blackwell's instructions for [Getting Started with R, R Studio, Git, and GitHub](https://gov51.mattblackwell.org/assignments/00-r-intro/), as well as Posit's [R Studio User Guide for GitHub Copilot](https://docs.posit.co/ide/user/ide/guide/tools/copilot.html).
