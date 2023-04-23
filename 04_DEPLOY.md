---
title: 4. Testing and deploying your site
---

## See it live with VS Code

Any time you need to edit your website, you'll use VS Code. Like most text editors, VS Code has a handy plugin for seeing your work "live" in a local development server. Basically, this means you can see changes to your website reflected in real time as you make those changes in your text editor.

Let's begin by loading your personal website repo as a VS Code workspace. (The word `workspace` has a specific definition in VS Code-speak, and while that definition won't matter a ton for our purposes, you can [learn more about it here](https://code.visualstudio.com/docs/editor/workspaces).)

When you open VS Code for the first time, you'll be prompted to open a folder. Go ahead and click `Open`, navigate to your repo, and load it.

![Loading repo as workspace in VS Code](media/newWorkspace.gif)

Once it's loaded, click on the `Extensions` button ![extensions](media/extensions.png) in the left-hand pane of VS Code. Search for `live server` and install this one:

![Live server extension in VS Code](media/live.png)

A little radio button with the words "Go Live" should appear on the bar at the bottom of the VS Code interface after the extension has installed. Click that button; a new tab showing the Creative template will open in your default web browser. Nice!

## Make it yours with VS Code

VS Code's Live Server extension makes it easy to see edits to your website in real time.

Note that the URL of your locally-served version of the template is suffixed with `index.html`. When an HTTP client requests a URL that points to a directory structure instead of an actual web page within the directory structure, the web server will generally serve a default page, which is often named `index.html`.

Go ahead and open the `index.html` file in VS Code. It contains all of the structural ingredients that comprise the web page. 

![Editing the website with real-time updates in VS Code](media/liveEdits.gif)

## Make it real with GitHub Pages

## Extras: Domain names, search engine optimization, and websites-as-a-service

---

# &rarr; [5: Wrap-up](05_WRAP.md)