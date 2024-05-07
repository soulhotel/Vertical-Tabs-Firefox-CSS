# <p align="center"> Vertical Tabs </p>
<p align="center">Firefox Resource Files</p>
<div align="center">  

![preview](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/05742df6-744e-4fbf-9368-f34e90b0c9ab)
</div>

###### Ive recently adopted the MPL 2.0 License, this started off as a project (attempting to fix the Vertical files function from MrOtherGuys CSSHacks) Since then, I've redone the function and leave this as a (a bit outdated) resource. [(Click me) for an example of how you can use these files to create themes](https://github.com/soulhotel/FF-CSS-ULTIMA)

## So.. I attempted to fixed [MrOtherGuys Vertical Tabs](https://github.com/MrOtherGuy/firefox-csshacks) 
- Vert tabs, without taking away your Sidebar.
- Works with color themes, addons, because its just the regular tab bar.
- Works with `custom CSS` that targets tabs, except for sizing, sizing can be modified within the code.
- Full functionality when interacting with tabs. Groups, Containers, multi selecting, middle click closing, etc.
<details>
<summary>(Click me) Showing off full functionality</summary>
pin unpin, containers, drag to new window, free up sidebar, themes support
  
![functionality](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/46b0c09b-0599-4e5a-8af8-1cb0ad3255fb)
</details>
<details>
<summary>(Click me) Showing off Color Theme support</summary>

![Screenshot_5 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/7ef945dc-e3c3-4685-ba4d-dcb45179b85e)
![Screenshot_6 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/32fe3a22-d832-477c-83a6-9e28a7990519)
</details>

## Modifications

###### Note: a lot of this functionality can be simplified with user preferences instead of having to edit the file.

<details>
<summary>(Click me) Autohide tabs (Delete 1 line in userChrome.css to disable)</summary>
  
![autohide 1](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/8a634225-24b8-41f6-a41c-eb71447ffcb9)
![autohide 2](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/8da65357-ae3b-4b98-8482-5971e8b33215)
</details>
<details>
<summary>(Click me) A Mini Button Bar coded to handle 10 buttons.</summary>
<br>Drag and drop functional, drag all buttons out to disable. Easy to modify `function-mini-button-bar.css`.<br>
 NO EXTENSIONS! THE FOLLOWING BUTTONS WORK.<br>
  
![313502235-037051e3-158c-4bd0-a8c8-d91cb6acf30a](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/47bbc63c-9267-47a0-8cc0-96ad0061dbe7)
</details>

## Install (Note: this is not a product release)
► Copy and paste the [Install Zip](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/releases/tag/verttab) into your chrome folder<br>
<details>
<summary>(Click me) Reset toolbar to default buttons</summary>
  
![Untitled](https://github.com/soulhotel/FF-CSS-ULTIMA/assets/155501797/75b8bd2e-cb7c-457d-a9b1-7c5ee2023b05)
</details>
► Restart Firefox.<br>

## Modifications
- Reference notes and custom variables to easily customize all tabs, borders, spacing, etc
  - `pinned , not pinned , 'if one is pinned do this' , buttons, etc`
  - `--uc-ultima-`, `--uc-ultima-tab-background`, `--uc-all-border-radius`, etc -► `all-global-positioning.css`
- Support to create/use your own color scheme for when theme addons are not used.
- Create a theme live, with Live Debugger, my `--uc-ultima-` variables will target everything.


