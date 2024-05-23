# <p align="center"> Vertical Tabs </p>
<p align="center">Firefox Resource Files</p>
<div align="center">  

![preview](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/05742df6-744e-4fbf-9368-f34e90b0c9ab)
</div>

###### Ive recently adopted the MPL 2.0 License, this started off as a project (attempting to fix the Vertical files function from MrOtherGuys CSSHacks) Since then, I've redone the function and leave this as a (a bit outdated) resource. [(Click me) for an example of how you can use these files to create your own theme](https://github.com/soulhotel/FF-CSS-ULTIMA)

## So.. I **attempted** to fix [MrOtherGuys Vertical Tabs](https://github.com/MrOtherGuy/firefox-csshacks) 

### What remains more/less
- Vert tabs, without taking away your Sidebar.
- Works with `custom styles` that target tabs, except for sizing, sizing can be modified within the code.
- Full functionality when interacting with tabs. Groups, Containers, multi selecting, middle click closing.

### Modifications

>[!Note]
> ###### a lot of this functionality can be simplified and semi-automated with user.pref adjustments. (Much better than going into the userchrome file to comment out a line.)

<details>
<summary>(Click me) Autohide tabs (Read the userChrome.css to toggle on/off)</summary>

> Option 1 - push content to the side.
![autohide 1](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/8a634225-24b8-41f6-a41c-eb71447ffcb9)

> Option 2 - overlay over content.
![autohide 2](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/8da65357-ae3b-4b98-8482-5971e8b33215)
</details>
<details>
<summary>(Click me) A Mini Button Bar coded to handle 10 buttons.</summary>
<br>Drag and drop functional, drag all buttons out to disable. Easy to modify `function-mini-button-bar.css`.<br>
 Adding extensions to the bar doesn't work. The following buttons do without issue.<br>
  
![313502235-037051e3-158c-4bd0-a8c8-d91cb6acf30a](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/47bbc63c-9267-47a0-8cc0-96ad0061dbe7)
</details>
<details>
<summary>(Click me) Showing off full functionality</summary>
  
> pin unpin, containers, drag to new window, free up sidebar, themes support, repositioning tabs is faulty. (Unless the transformation applied to individual tab elements can be moved from their right/left to top/bottom, I dont see repositioning ever being fixed. But I'm a newb So you may know otherwise.)
  
![functionality](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/46b0c09b-0599-4e5a-8af8-1cb0ad3255fb)
</details>
<details>
<summary>(Click me) Lwtheme support</summary>

![Screenshot_5 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/7ef945dc-e3c3-4685-ba4d-dcb45179b85e)
![Screenshot_6 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/32fe3a22-d832-477c-83a6-9e28a7990519)
</details>

### Install (Note: this is not a product release)
► Copy and paste the [Install Zip](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/releases/tag/verttab) into your chrome folder<br>
<details>
<summary>(Click me) Reset toolbar to default buttons</summary>
  
![Untitled](https://github.com/soulhotel/FF-CSS-ULTIMA/assets/155501797/75b8bd2e-cb7c-457d-a9b1-7c5ee2023b05)
</details>
► Restart Firefox.<br>

### For Debugging
- Reference notes/details are present throughout the files. Custom variables were used to ease future customization for almost every relevant change made.
  - notes further label changes made to things such as tabs in pinned or unpinned states.
  - `--uc-ultima-`, `--uc-all-margins`, `--uc-all-border-radius`, etc, vars related to -► `all-global-positioning.css`
  - `--uc-ultima-`, `--uc-ultima-tab-background`, vars related to color, lwtheme, etc -► `all-global-theme.css`


