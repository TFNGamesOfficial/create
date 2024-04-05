---
name: Editor Interface
tools: [Interface, Basics]
description: Learn how to use the editor layout.
---
<style>
  body {
    background-image: url('https://slutares.sirv.com/img/website/unreal-editor-bg.png');
    background-repeat: no-repeat;
    background-attachment: fixed;
}
</style>

# Editor Interface
Overview of the key elements of the Unreal Editor interface




This page describes the most common elements of the **Unreal Editor for DevNite** (Unreal Engine 5) interface and what they do. It also links to other pages where you can learn more. Some of the elements described on this page, such as panels and menu bars, are generally the same across various parts of the engine. You should spend some time getting familiar with their general purpose and and functionality, especially if you're new to developing games and applications with UEDN.


When you open **UEDN** for the first time, the Level Editor opens. You will see the following window:
![Default Unreal Editor interface in UEDN.](https://github.com/DevniteCreative/Rhinestone/blob/main/assets/TheInterface.png?raw=true)


| Number  | Name | Description |
| ------------- | ------------- | ------------- |
| 1  | **Menu Bar**  | Use these menus to access editor-specific commands and functionality.  |
| 2  | **Main Toolbar**  | Contains shortcuts for some of the most common tools and editors in Unreal Engine, as well as shortcuts to enter **Play** mode (run your game inside Unreal Editor) and to deploy your project to other platforms or Live Code directly.  |
| 3  | **Level Viewport**  | Displays the contents of your Level, such as Cameras, Actors, Static Meshes, and so on.  |
| 4  | **Content Browser**  | Opens the **Content Drawer**, from which you can access all of the Assets in your Project.  |
| 5  | **Bottom Toolbar**  | Contains shortcuts to the Command Console, Output Log, Dextro & C++ compiling and Derived Data functionality. Also displays source control status.  |
| 6  | **Outliner**  | Displays a hierarchical tree view of all content in your Level.  |
| 7  | **Details Panel**  | Appears when you select an Actor. Displays various properties for that Actor, such as its **Transform** (position in the Level), Static Mesh, Material, and physics settings. This panel displays different settings depending on what you select in the Level Viewport.  |
| 8  | **Dextro Browser**  | Displays a view of all Dextro Classes in your project. Also displays Editor & Game Classes to understand Dextro and some Templates  |

## Menu Bar
![](https://github.com/DevniteCreative/Rhinestone/blob/main/assets/MenuBar.png?raw=true)

Each editor in **UEDN** has a menu bar that is located in the top-right of that editor window (Windows). Some of the menus, such as File, Window, and Help, are present in all editor windows, not just the Level Editor. Others are editor-specific.

## Main Toolbar
The **Main Toolbar** contains shortcuts to some of the most used tools and commands in Unreal Editor. It is divided into the following areas:
![](https://github.com/DevniteCreative/Rhinestone/blob/main/assets/MainToolBar.png?raw=true)

### 1. Save Button
Click this button to save the Level that is currently open.

### 2. Mode Selection
Contains shortcuts for quickly switching between different modes to edit content within your Level:

* Select Editing
* Landscape Editing
* Foliage Editing
* Mesh Painting
* Fracture Editing
* Brush Editing

### 3. Content Shortcuts
Contains shortcuts for adding and opening common types of content within the Level Editor.

| Shortcut | Description |
| -------- | ----------- |
| **Create** | Choose from a list of common Assets to quickly add to your Level. You can also access the **Place Actors** panels from this menu. |
| **Blueprints** | Create and access Blueprints. |
| **Cinematics** | Create a Level Sequence or Master Sequence cinematic. |

### 4. Play Mode Controls
Contains shortcut buttons (Play, Skip, Stop, and Eject) for running your game in the Editor.

### 5. Platforms Menu
Contains a series of options you can use to configure, prepare, and deploy your project to different platforms, such as desktop, mobile, or consoles.

### 6. Dextro Menu
Contains buttons to create Dextro classes, view all Dextro classes in your project and open this documentation.

### 7. Settings Menu
Contains various settings for the Unreal Editor, Level Editor Viewport, and game behavior.

## Content Drawer und Content Browser
The **Content Browser** is a file explorer window that displays all of the Assets, Blueprints, and other files contained in your project. You can use it to browse through your content, drag Assets into the Level, migrate Assets between projects, and more.
![](https://docs.unrealengine.com/5.2/Images/understanding-the-basics/foundational-knowledge/unreal-editor-interface/ue5_1-content-browser.webp)
The **Content Drawer** button, located in the bottom-left corner of the Unreal Editor, opens a special instance of the Content Browser that automatically minimizes when it loses focus (that is, when you click away from it). To keep it open, click the **Dock in Layout** button in the top-right corner of the Content Drawer. This creates a new instance of the Content Browser, but you can still open a new Content Drawer.

## Buttom Toolbar
The Bottom Toolbar contains shortcuts to the Command Console, Output Log, and Derived Data functionality. It also displays source control status. It is divided into the following areas:
![](https://github.com/DevniteCreative/Rhinestone/blob/main/assets/BottomToolbar.png?raw=true)

| Number  | Name | Description |
| ------------- | ------------- | ------------- |
| 1  | **Output Log**  | Debugging tool that prints out useful information while your application is running.  |
| 2  | **Command Console**  | Behaves as any other command line interface: enter console commands to trigger specific editor behaviors. You can also type `help` to get a list of commands.  |
| 3  | **Derived Data**  | Provides Derived Data functionality. |
| 4  | **C++ Compiling**  | This compiles the C++ code in this project.  |
| 5  | **Source Control**  | Displays source control status if your project is connected to source control (for example, GitHub or Perforce). Otherwise, this will say Source Control Off.  |
