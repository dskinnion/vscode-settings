# vscode-settings
A repository housing the settings and configuration files for our VSCode preferences.

Configuration Recommendation Profile: https://vscode.dev/profile/github/20e6ae5efe1a14cc1f242e03e41bb715

In addition to this README, there are three more files inside this repository. 
* *extensions_to_copy.json*: this lists out all of our recommended extensions. Upon opening this file in VSCode, you will be prompted to install these extensions. A full list of these extensions are below, in the extensions section.
* *settings_to_copy.json*: this contains all of our non-default settings.
* *keybindings_to_copy.json*: this contains our specialty keyboard shortcuts.

*If you've already installed VSCode, skip the following section.*

## Instructions for Downloading VSCode:
Visual Studio Code has [instructions](https://code.visualstudio.com/learn/get-started/basics) for getting started.

You can download VSCode directly from their [website](https://code.visualstudio.com/download) for your operating system.

Unzip the download (mine was called "VSCode-darwin-universal.zip), and then click on the new application (Visual Studio Code). A pop-up will ask you if you want to open an app downloaded from the internet. Click open.

Congrats, you've downloaded VSCode!


## Installing our Configurations:
* Download the files from this GitHub repository.
* Open VSCode

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
