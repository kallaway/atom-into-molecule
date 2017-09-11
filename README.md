# Atom Into Molecule - Get an IDE for free.

["TLDR; No time, I just want to set everything up quickly!"]()

This repo provides a way to simplify the setup (including the essential packages (plugins) and settings) to quickly set up your Atom Editor, making it comparable to a full-blown IDE in terms of features and productivity. I promise that once you give Atom a try, it will be difficult to use any other editor. At least, that was my experience so far. :)

Note: This repo is being updated/fixed as I go. Please provide any feedback that you might have and I will do my best to improve it. I will also be adding lists of useful packages for some programming languages, especially for the ones beginners usually start with. 

Below are just the things I've found so far, and I will continue to add more information to this repo, as well as improve the way the content is presented.

If you like this repo and find it useful, please consider ★ starring it (on top right of the page) :)

## What is this repo about?

What's so great about Atom? For starters, it's open-source and hackable and made by the folks in Github. :) 

I've come to really enjoy the flexibility and convenience that Atom Editor offers in terms of coding, but it always takes me a while to set everything up (all the packages) whenever I need to install it and get going on a new machine – at work or at home - I find myself trying to remember all the settings, packages and themes that I've found before and waste a lot of time with that setup. This repo makes it easy to do a quick install of all the needed things to get productive in Atom.

On another note, I also think that if people who want to give Atom a try had a way to set up their editor quickly and experience all the features it has to offer and see the possibilities without the hassle of figuring things out, they would definitely enjoy it more and would become productive very quickly.

I believe that knowing how to use Atom effectively will make your daily life as a programmer or a learner easier and you will be able to do more in less time.

Here is a list of plugins, settings, themes and shortcuts that I find indispensable:

## Step 1: Install Atom Editor

Download and install Atom for your operating system here (it will probably recognize which system you have automatically): [Click do Download](https://atom.io)

## Step 2: Plugins

One of the coolest things I've found regarding plugins in Atom (besides the fact that you can search for them in the editor itself and install them right there) is that you can install a preset list of packages with one bulk operation - instead of searching for each of them and installing them individually. You can decide if you want to quickly install all of these plugins and have an "IDE" ready to go, or if you want to pick and choose the plugins one by one - see below.

### Install essential plugins quickly:

1. Install Atom Command Line Tools (in the menu of Atom Editor):

**Atom -> Install Shell Commands**

2. Download this file into a folder that's easy for youe to navigate in a Terminal (or bash): 

(It might be easier if you grab the 'raw' version of the file [here](https://raw.githubusercontent.com/Kallaway/atom-into-molecule/master/packages.txt) and save the contents of the file anywhere you want on your computer - and name it 'packages.txt')

Download [packages.txt](packages.txt)

In a Terminal, navigate to the directory (folder) you've downloaded the file to. Run the following command:
```
apm install --packages-file packages.txt
```

(Atom will start automatically installing all the plugins in the list, and it may take a bit of time. That's ok.)

### Pick and choose plugins to install:

Click on links to see more details about each package. Remember you are getting all of these if you quick-install the plugins using the instructions above.

1. [Emmet](https://atom.io/packages/emmet)
Main benefit: Expand abbreviations by Tab key. Immensely increases productivity.

2. [Pigments](https://atom.io/packages/pigments)
A package to display colors in project and files.

3. [Minimap](https://atom.io/packages/minimap)
A preview of the full source code.

4. [Minimap Improvement: Minimap Pigments](https://atom.io/packages/minimap-pigments)
An Atom plugin to display pigments colors in the Minimap.

5. [File Icons](https://atom.io/packages/file-icons)
"Assign file extension icons and colours for improved visual grepping" Basically, show different icons for each file type in the project tree.

6. [Terminal: PlatformIO IDE Terminal](https://atom.io/packages/platformio-ide-terminal)
A terminal package for Atom, complete with themes, API and more for PlatformIO IDE.

7. [Color Picker](https://atom.io/packages/color-picker)
Allows you to pick colors right in the editor, by pressing: CMD+SHIFT+C (CTRL+SHIFT+C). 
Easy to remember because C stands for Color.

8. [Atom Beautify](https://atom.io/packages/atom-beautify)
Beautify HTML, CSS, JavaScript, PHP, Python, Ruby, Java, C, C++, C#, Objective-C, CoffeeScript, TypeScript, Coldfusion, SQL, and more in Atom.

9. [Auto-close HTML](https://atom.io/packages/autoclose-html)
Automates closing of HTML Tags.

10. [Auto-detect indentation](https://atom.io/packages/auto-detect-indentation)
Automatically detect indentation of opened files. I can't stress enough how helpful this is, especially if you work with others - on a team or on open-source projects.

11. [Busy Signal: Show when a plugin is performing a task](https://atom.io/packages/busy-signal)
Busy Signal is a base package that provides an easy to use API to show your package is performing a task.

12. [Highlight Line](https://atom.io/packages/highlight-line)
Highlights the current line in the editor. (Surprisingly useful - helps focus)

13. [Highlight Selected](https://atom.io/packages/highlight-selected)
Highlights the current word selected when double clicking.

14. [Linter](https://atom.io/packages/linter)
Linter is a base linter provider for the hackable Atom Editor. Additionally, you need to install a specific linter for your language. You will find a full list on [atomlinter.github.io](http://atomlinter.github.io/). Install the linters you think you may need.

15. [Linter Add-on: Default UI](https://atom.io/packages/linter-ui-default)
Default UI for the Linter Package.

15. [Linter Add-on: CSS](https://atom.io/packages/linter-csslint)
"Lint CSS on the fly, using csslint"

16. [Linter Add-on: HTML](https://atom.io/packages/linter-htmlhint)
A plugin for Atom Linter providing an interface to HTMLHint.

16. [Linter Add-on: Sass](https://atom.io/packages/linter-sass-lint)
Atom Linter plugin to lint your Sass/SCSS with pure node sass-lint

17. [Markdown Preview Plus](https://atom.io/packages/markdown-preview-plus)
Markdown Preview Plus provides a real-time preview of markdown documents.

18. [Language Babel](https://atom.io/packages/language-babel)
JavaScript ES201x, React JSX, Flow and GraphQL Grammar. Babel Transpiler.

#### Update all packages

In Atom, go to Settings (using CMD+, OR CTRL+,) -> Updates -> Update All.

## Step 3: Themes and UI

You will find a lot of other themes being recommended that the majority of people prefers, but I've tried them out and they didn't work out as well for me. Here is what I use and I find it to be esthetically pleasing, comfortable to read and reason about the code, and easy on the eyes (as I stare at the code).

UI Theme: One Dark (comes with Atom by default)
Syntax Theme: (Cobalt2)[https://atom.io/themes/cobalt2-syntax] (by Wes Bos)

* If you've installed the packages from the packages.txt file above, you will already have Cobalt2 installed on Atom.

## Step 4: Getting Productive with Shortcuts - Mac (Windows)

If you remember one shortcut (key combination) - make it this one:
CMD+SHIFT+P (CTRL+SHIFT+P) - it opens Command Pallette where you can search for any actions that your installed plugins might provide. An example would be: if you have Markdown Previewer installed, after this combination you enter 'Markd' and hit 'Enter' and it will automatically open the current .md file in a Markdown Previewer tab (it uses 'fuzzy' search so you don't have to type in the whole word).

Besides the ones below, remember that all the copy/paste/save shortcuts also work. 

General:

| Action           | Mac           | Windows      |
| ---------------- |:-------------:|:------------:|
| Open Settings    | CMD+,         | CTRL+,       |
| Search File      | CDM+F         | CTRL+F       |
| Search Project   | CDM+SHIFT+F   | CTRL+SHIFT+F |
| Create a File    | CMD+N         | CTRL+N       |

Productivity:

| Action           | Mac            | Windows        |
| ---------------- |:--------------:|:--------------:|
| Duplicate a line | CMD+SHIFT+D    | CTRL+SHIFT+D   |
| Multiple Cursors | CMD+Mouseclick |CTRL+Mouseclick |
| Select a line    | CMD+L          | CTRL+L         |
| Pick a Color*    | CMD+SHIFT+C    | CTRL+SHIFT+C   |

* indicates that you need to have a plugin installed to enable the shortcut.

# Congratulations, you are all set!

Read on to get some other tips and info on niche, more specific (but very useful) plugins.

## General Advice/Tips

1. You can modify how the display is divided into windows: take the file by its name on top and drag around the screen. You will see that Atom will start helping you by highlighting parts of the screen where you could 'drop' the file, for example- into a right half of the screen. Once you release the file, the window will be divided as was shown and you will be able to look and edit both files.

2. Building on the above, if you work with HTML+CSS it is convenient to have a CSS file open on the right (1/4 of the screen or so), and the main file you work with on the left (taking up the majority of space there).
 
## Other Amazing plugins (these are less general but amazingly useful)

1. [SVG Preview](https://atom.io/packages/svg-preview)
Add SVG Preview to Atom

2. [Tablr: Edit CSV](https://atom.io/packages/tablr)
Edit CSV files right in Atom

3. [Docblockr: write documentation](https://atom.io/packages/docblockr)
A helper package for writing documentation

4. [Markdown Writer: Blog Easily](https://atom.io/packages/markdown-writer)
Make Atom a better Markdown editor and an easier static blogging tool.

## Odds and Ends.

It's a common misconception that Atom is slow and/or buggy. Even if it used to be the case, it's definitely changed for the better. I can't even remember when was the last time Atom did something weird or crashed on me. The speed is also much better, and the entire core of Atom has been rewritten recently to improve the experience.

## Contact

If you have any questions or ideas about this repo, feel free to reach out to me on Twitter: [@ka11away](https://twitter.com/ka11away) or submit a Pull Request here.

## #100DaysOfCode Challenge
If you are learning to code or looking to improve your coding skills, find new like-minded friends and become more consistent in your coding, consider doing a #100DaysOfCode challenge. More info here: [www.100DaysOfCode.com](http://100daysofcode.com/)
You can also see the updates of the people in the challenge on Twitter: [#100DaysOfCode Hashtag on Twitter](https://twitter.com/hashtag/100daysofcode?f=tweets&vertical=default&src=hash)
