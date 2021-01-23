# VS Code Setup

## Lesson Objectives

1. Overview
2. Take a look at my set up
3. Add some of my VS code extensions
4. Take a look at some VS Code short cuts
5. Fork, Clone, and Contribute

## Overview

My favorite code editor is [ VS Code](https://code.visualstudio.com/) mainly because it is highly customizable and some of the awesome features you encounter here are created and maintained by developers just like you!

VS Code has a market place which makes it easy for you to add features to your editor that can help you to be more productive when developing applications.

**Here are my some tips, shortcuts, and set-up that you can feel free to incorporate in your environment**

## 🎨 Theme:

I created my own dark color theme called Golden-Blue color Theme. It an enhanced version of the `Tomorrow Night Blue`. 

![Golden-Blue Color Theme](https://marketplace.visualstudio.com/items?itemName=BrunoDaSilvaThemes.golden-blue&ssr=false#review-details)

Let's change the theme to a VS Code default theme.

1. Click on the settings icon, located in the left bottom. ⚙️
2. Color Theme
3. OR use the shortcut CTR+K CTR+T
4. Select a theme from the dropdown list.

Here is a collection of vs code theme you can incorporate to your VS CODE from the market place.

[ 50 VS Code Themes for 2020](https://dev.to/thegeoffstevens/50-vs-code-themes-for-2020-45cc)

#### 🤓 Nerd Section & Fun Themes:

[ win95 ](https://marketplace.visualstudio.com/items?itemName=asilva.win95)

[ Star Wars Theme ](https://marketplace.visualstudio.com/items?itemName=NiravAgarwal.star-wars-theme)

[ Slack Theme ](https://marketplace.visualstudio.com/items?itemName=felipe-mendes.slack-theme)

[ HotDogStand ](https://marketplace.visualstudio.com/items?itemName=somekittens.hot-dog-stand)

[ HotDogStand ](https://marketplace.visualstudio.com/items?itemName=somekittens.hot-dog-stand)

## 📁 Icons:

File Icons is a quick a way to visualize directory, organize your files, and enhance your Visual Studio look

You can go directly to the market place for this one.

Here are some suggestions:

[ VSCode Great Icons](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons)

[ Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

[ VSCode Icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

**Minimalist icons**

[ Chalice Icon Theme](https://marketplace.visualstudio.com/items?itemName=artlaman.chalice-icon-theme)

[ Minimalist Product Icon Theme](https://marketplace.visualstudio.com/items?itemName=ElAnandKumar.el-vsc-product-icon-theme)

#### 🤓 Nerd Section & Fun icons:

[ Cage Icons ](https://marketplace.visualstudio.com/items?itemName=stepanog.cage-icons)

[ MK Icons ](https://marketplace.visualstudio.com/items?itemName=JohnnyReina.MK)

## ✏️ Font:

The font I use is called `Fira Code, Cascadia Code`, and it supports ligatures, which is just away to style symbols (it is just for visual purpose).

[ The best monospace fonts for coding in 2020 ](https://www.creativebloq.com/features/the-best-monospace-fonts-for-coding)

1. You have to install the font in your VS Code first
2. Click on the settings icon, located in the left bottom. ⚙️
3. Settings
4. OR use the shortcut CTR+,
5. Under Commonly Used>>Text Editor Select Font
6. You can just add the name of the font and default fonts
7. You can also use Json format to insert the name of the Font.

**Important: You must have the font installed and have the exact font name and defaults, Read the docs**

If you want to use my settings

```
{
 "editor.fontSize": 16,
  "editor.lineHeight": 22,
  "editor.letterSpacing": 0.5,
  "editor.fontWeight": "400",
  "editor.formatOnSave": true,
  "editor.fontFamily": "Fira Code, Cascadia Code",
  "editor.fontLigatures": true,
  "editor.cursorWidth": 5,
  "editor.cursorStyle": "line",
  "markdown.preview.lineHeight": 2.2,
  "workbench.colorTheme": "Tomorrow Night Blue",
  "liveServer.settings.donotShowInfoMsg": true
}

```

## ✏️ Extension:

1. [ Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
2. [ Bracket Pair Colorizer ](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
3. [ Code Spell Checker ](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
4. [ JavaScript (ES6) code snippets ](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
5. [ Auto Rename Tag ](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
6. [ indent-rainbow ](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
7. [ Live Server ](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
8. [ Live Sass Compiler ](https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass)
9. [ Sass ](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)
10. [ Path Intellisense ](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
11. [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
12. [ Color Highlight ](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
13. [ Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
14. [Markdown All in One ](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
15. [ DotEnv ](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
16. [Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)

## 🙏 Advance Settings: 🙏

You don't have to do this part, if you don't want to. This is just extra stuff given by VS code that I hardly use.

### ⚠️ Danger Zone 👾

#### Optional:

1.  Open Editor
2.  Minimap
3.  Breadcrumbs
4.  Move side bar to the right (it is recommended)
5.  Change default setting to json

## 😎 Visual Studio Shortcuts ⌨️

Shortcuts helps you to stay focus and productive. Here are some of shortcuts.

| Shortcuts                           |        Action        |
| ----------------------------------- | :------------------: |
| Ctrl + P                            |  Search for a file   |
| Ctrl + ` | Open terminal in VS Code |
| Alt + Down                          |    Move Line Down    |
| Alt + Up                            |     Move Line Up     |
| Ctrl + D                            |   Find next Match    |
| Ctrl + Space                        |     Open Suggest     |
| Shift Alt + Down                    |    Copy Line Down    |
| Shift Alt + Up                      |     Copy Line Up     |
| Ctrl+ B                             | Toggle the side menu |
| _Next shortcut above_               | _simple description_ |

Now, you can practice some fork, clone, and pull request. Follow the steps showed in class and add a short to the table above.

1. Click on the the link below
2. Pick one keyboard shortcut
3. Add to your local version of this repo
4. Git add, commit, and push
5. Head to github and make a pull request

I will review your code, make sure that there is no conflicts, and eventually merge your request to this repository.

[VS Code Shortcut ](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

<details>
<summary>Additional Links:</summary>

[How to make a pull request ](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

[Difference between Fork and Cloning ](https://github.community/t/the-difference-between-forking-and-cloning-a-repository/10189)

[Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)

</details>

### What Next?

#### See if there is any other areas in the markdown that could be improved, fix it and submit your pull request!

This markdown is made with ❤️ by Bruno DaSilva - You can find more about me at https://www.bruno-dasilva.com/
