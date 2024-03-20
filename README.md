# <p align="center"> Vertical Tabs </p>
<p align="center">Firefox Resource Files, FF 60+, 100% CSS </p>
<div align="right">  

![GitHub Release](https://img.shields.io/github/v/release/soulhotel/Vertical-Tabs-Firefox-CSS?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/soulhotel/Vertical-Tabs-Firefox-CSS?style=for-the-badge)
</div>

https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/9b2af243-bc7f-47c2-8341-863901645a31

## So, I fixed [MrOtherGuys Vertical Tabs](https://github.com/MrOtherGuy/firefox-csshacks) 
- Vert tabs, without taking away your Sidebar
- Works with color themes, addons, because its just the regular tab bar.
- Works with `custom CSS` that targets tabs, except for sizing, sizing is handled in the code.
- Full functionality, interacting with tabs, its the regular tab bar after all..
- Groups, Containers, multi selecting, middle click closing, etc, its the regular bar tab after, youre drunk..

## Whats fixed?
- Pinned tabs and scrolling fixed
- Body, Nav bar, random lines pushing things to the side, fixed
- 1.1 patch - title bar buttons are fixed, no need for extension replacement

### [(Click me) for an example of how you can use these files to create themes](https://github.com/soulhotel/FF-CSS-ULTIMA)

## Modifications
- Auto hiding tabs, without pushing the browser to the side
  - Autohide the Sidebar, you can adjust the min/maximum width's in `vertical-tabs-hide.css`
  - Can also be disabled, simply delete a (labeled) section `vertical-tabs-hide.css`
- Reference Modifiers to style the tabs more easily at the end of the code
  - `pinned , not pinned , 'if one is pinned do this' , buttons, etc`
- A Mini Button Bar coded to handle 10 buttons. Easy to modify `mini-button-bar.css`, easy to drag and drop items.

## Preview
![Screenshot_5 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/7ef945dc-e3c3-4685-ba4d-dcb45179b85e)
![Screenshot_6 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/32fe3a22-d832-477c-83a6-9e28a7990519)
![Screenshot_3 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/abb15550-39e0-4f77-9339-21f73ee09be1)
![Screenshot_2 (Custom)](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/d69ff0a0-48bc-4dc8-b0b3-a8ff23488292)
![Screenshot_8](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/dac08516-aa59-4e5f-8a8c-5524c7b49bb6)

## Install (Note: This is just a resource)
- [Install Zip](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/releases/tag/verttab)
- You MUST `restore to default` your toolbar before adding the files, this resets your button locations.
- ![Screenshot_5](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/02aa4ab1-466c-4e23-9d45-36d47d5f32b5)
- ![Screenshot_7](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/c7eb12a0-9703-4d59-a044-73ab54146e15)

## Extra
- It took a couple of hours to get this done, so there may be possible bugs
- This is not a product release, just a share
- However feel free to let me know about any discovered bugs
- Just discovered something myself, some (not all) themes from the Add-On Store resize/add padding to the tabs
  - Im only seeing 1-3 pixel differences BUT this may make your tabs seem uncentered
  - Luckily, you can always create your own theme and stylize with CSS, and again, not all themes from the Store are doing this, not even most
  - ![Screenshot_9](https://github.com/soulhotel/Vertical-Tabs-Firefox-CSS/assets/155501797/d60eba42-708d-492e-a58d-87571a661782)
- You cannot add extensions to the Mini Button Bar
   - Firefox has some rule that goes against this, probably because im utilizing the titlebar to make it work
