![SPRITENATOR](https://github.com/christinec-dev/SpriterNator/assets/87696858/ecd307a5-46c6-4590-970f-d798e7f10ee0)
# SpriterNator: Unity Sprite Animation and Library Tool
SpriterNator is a Unity extension that simplifies the process of generating and managing sprite animations and sprite libraries. This tool addresses makes it easier to create, organize, and export sprite-based assets within the Unity ecosystem. SpriterNator helps reduce development time, allowing you to focus on the creative aspects of game development.

---

# Table of Contents
- [Links](#links)
- [Features](#tool-features)
- [Instructions](#usage-instructions)

---

# Links
- [Unity Package](https://assetstore.unity.com/packages/slug/279795)
- [GitBook](https://oops-i-devd.gitbook.io/christinec-dev)
- [Join My Discord](https://discord.gg/4N6b4bkC8h)
- [Support Me](https://ko-fi.com/christinedevs)

---

# Tool Features
### Batch Animation Creation
Automatically generate multiple animations from a single spritesheet, reducing manual setup time. Define animations using start and end frames, and export them as Unity Animation Clips (.anim).
### Sprite Sheet Swapping
Effortlessly switch between spritesheets that follow the same layout. This feature is for developers working with characters or objects that have multiple skins or states, enabling quick swaps without needing to adjust frame ranges or manually creating or dragging animations.
### Animation List Management
Add, remove, and duplicate animations directly from the tool's UI. Organize your animation sequences efficiently, with support for reordering through intuitive controls.
### Save and Load Presets
Save your animation settings as JSON files for future use. This functionality allows for easy reapplication of animation sequences to new spritesheets, significantly speeding up the development process when working with multiple characters or assets.
### Sprite Library Asset Creation
Streamline the organization of sprites into categories and labels by creating Sprite Library assets directly from your animations. This feature organizes sprites based on animation names and frames, facilitating quick access and reuse within your projects.

---

# Usage Instructions

## SECTIONS
- [SpriteSheet Preparations](#spritesheet-preparations)
- [Download & Install](#downloading-the-package-and-adding-it-to-project)
- [Animation Properties](#animation-properties)
- [Creating Animations](#creating-animations)
- [Exporting Animations](#exporting-animations)
- [Creating Sprite Libraries](#creating-sprite-libraries)
- [Exporting & Importing Animation Lists](#exporting-and-importing-animation-lists)
  
## SPRITESHEET PREPARATIONS
- Make sure that you split your sprite sheets.
- When splitting the sheets, ensure that each frame is cropped out correctly.
- Back to [top][#sections].
  
![1](https://github.com/christinec-dev/SpriterNator/assets/87696858/f763ddd5-2dec-4ca6-8cff-bc8faa03dfa4)


## DOWNLOADING THE PACKAGE AND ADDING IT TO PROJECT
- Download the package from the [Unity Store](#links). Once added to your project, you should be able to see it in your project via Tools/SpriterNator.
- Back to [top][#sections].
  
![3](https://github.com/christinec-dev/SpriterNator/assets/87696858/cd1b1840-07e4-4436-b879-7047ef951994)

## ANIMATION PROPERTIES
- Select the spritesheet (not individual frame, complete spritesheet) asset that you want to use to create animations. 
- Also set the location to where your assets should save. 
- If you plan on creating a Sprite Library asset from your animations, add a name for this asset.
- Back to [top][#sections].
  
![4](https://github.com/christinec-dev/SpriterNator/assets/87696858/0c9ff0ad-c106-403b-9b14-9eddaa6a94ef)
![5](https://github.com/christinec-dev/SpriterNator/assets/87696858/67ed880b-36ac-418b-93c5-ddf258a3bbe5)

## CREATING ANIMATIONS
- You can add animations to the list via the "+" button.
- You can remove animations from the list via the "-" button.
- You can duplicate list animations via the "++" button.
- When creating an animation, enter the first frame, last frame, and frame rate of your animation. Also state wether or not it should loop.
- You can find the first frame value on your spritesheet at the end of the frame naming "_x".
- You can find the last frame value on your spritesheet at the end of the frame naming "_x".
- Back to [top][#sections].

![6](https://github.com/christinec-dev/SpriterNator/assets/87696858/f605b1c2-2f22-4aaa-8e93-aeb185c78f73)
![7](https://github.com/christinec-dev/SpriterNator/assets/87696858/d1a56150-f82d-4346-90b0-bd3729e60b1b)
![8](https://github.com/christinec-dev/SpriterNator/assets/87696858/b1cbaa96-855d-495d-8803-6e2b7d11e53a)
![9](https://github.com/christinec-dev/SpriterNator/assets/87696858/c87973ab-2126-4126-9a92-549376e40ae0)
![10](https://github.com/christinec-dev/SpriterNator/assets/87696858/438804dc-e6e4-428a-822b-ecf033ce4e27)
![11](https://github.com/christinec-dev/SpriterNator/assets/87696858/9236c404-8e33-4069-9475-2b5f34d39f18)
![12](https://github.com/christinec-dev/SpriterNator/assets/87696858/92da433f-9e19-42f4-ac66-30e8daf898f0)

## EXPORTING ANIMATIONS
- When you've created your animations, and you want to export them as .anim assets, click the "CREATE ANIMATIONS" button. 
- You can go to the directory where you saved it, and the animations should be there.
- You can add a character to your preview panel, and test the animation.
- Back to [top][#sections].

![13](https://github.com/christinec-dev/SpriterNator/assets/87696858/22548c60-e30c-4d92-95f6-9b405304e7d7)
![14](https://github.com/christinec-dev/SpriterNator/assets/87696858/e67dc7a0-fe52-47eb-87c7-9e71d7d01be2)

## CREATING SPRITE LIBRARIES
- When you've created your animations, and you want to export them as .asset assets, click the "CREATE SPRITE LIBRARY" button.
- Your animation names will be assigned as Categories, and your animation frames per animation will be assigned as Labels to these Categories.
- You'll have to convert the runtime asset that it created into a library asset. Select the asset, and in the Inspector Panel, click on "Open Sprite Library Asset Upgrader".
- Load your created library asset, and upgrade it.
- Your Sprite Library should now be created.
- Back to [top][#sections].

![15](https://github.com/christinec-dev/SpriterNator/assets/87696858/6cefd5da-a140-4818-94bf-38f4c86516da)
![16](https://github.com/christinec-dev/SpriterNator/assets/87696858/05296fc7-8308-413e-a945-19e26ea03874)
![17](https://github.com/christinec-dev/SpriterNator/assets/87696858/8ad8f490-baba-49a3-b6ce-618c0e719c54)

## EXPORTING AND IMPORTING ANIMATION LISTS
- If you have similar spritesheets, and you'd like to come back later to create animations for another character using the same animation frames and naming conventions, then you can save your animations as a JSON file via the "SAVE LIST" button.
- You can edit this file to add more animations, and then load it again using the "LOAD LIST" button.
- Back to [top][#sections].
- 
![18](https://github.com/christinec-dev/SpriterNator/assets/87696858/14b3d25c-ef8b-4257-ba4e-09046145651a)
![19](https://github.com/christinec-dev/SpriterNator/assets/87696858/e27f841c-99d2-4672-83e9-5c16f7402d98)
![20](https://github.com/christinec-dev/SpriterNator/assets/87696858/6515e0f4-9c93-445f-baf1-28e7900ad721)


