---
name: Editor Interface
tools: [Interface, Basics]
description: Learn how to use the editor layout.
---
<script src="https://kit.fontawesome.com/36b257c118.js" crossorigin="anonymous"></script>
<style>
.content-nav-container {
  position: sticky;
  position:-webkit-sticky;
  width:300px;
  top: 0;
  height:0px;
  bottom:0;
  right: 0;
  margin-left: auto;
  padding-top:10px;
}
  
.content-nav {
  right: 50px;
  top: 40%;
}
  
.content-nav.is-collapsible {
    position: relative
}

.content-nav.is-collapsible .list {
    position: absolute;
    z-index: 1;
    top: 100%;
    left: 0;
    background: #000;
    padding: 1rem;
    margin-top: .25rem;
    width: 100%
}

.content-nav.is-scrollable {
    min-height: calc(var(--site-y-visible-height) - 1rem);
    display: flex;
    flex-direction: column
}

.content-nav.is-scrollable .ng-scrollbar {
    flex-grow: 1
}

.content-nav.is-scrollable .list {
    padding-bottom: 0
}

.content-nav-header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 1.5rem
}

.content-nav-header .title {
    font-size: .75rem;
    font-weight: 700;
    letter-spacing: .1em;
    text-transform: uppercase
}

.content-nav-header .sublink {
    font-size: .875rem;
    color: #26bbff;
    text-decoration: none
}

.content-nav-header .sublink:hover {
    text-decoration: underline
}

.content-nav .btn {
    font-size: .875rem;
    letter-spacing: normal;
    border-width: .125rem;
    margin-bottom: 1.5rem;
    text-transform: initial;
    width: 100%;
    display: flex;
    justify-content: space-between
}

.content-nav .btn .material-icons {
    font-size: 1.25rem
}

.content-nav .list {
    list-style: none;
    padding: 0 0 3rem;
    margin: 0;
    font-size: .875rem;
    border-radius: 4px
}

.content-nav .list-item+.list-item {
    margin-top: .5rem
}

.content-nav .list-item.is-level-2 {
    padding-left: .75rem
}

.content-nav .list-item.is-level-3 {
    padding-left: 1.5rem
}

.content-nav .list-item.is-level-4 {
    padding-left: 2.25rem
}

.content-nav .list-item.is-level-5 {
    padding-left: 3rem
}

.content-nav .list-item.is-level-6 {
    padding-left: 3.75rem
}

.content-nav .list-link {
    display: flex;
    text-decoration: none;
    color: #aaaaae;
    transition: color .1s linear,border-left-color .1s linear;
    padding-left: .875rem;
    border-left: .125rem solid transparent
}

.content-nav .list-link:hover,.content-nav .list-link.is-active {
    color: #e6e6ea
}

.content-nav .list-link.is-active {
    font-weight: 700;
    border-left-color: #ff0000
}

.content-nav .sub-list {
    list-style: none;
    padding: 0;
    margin: 1rem 0 0 1.25rem
}

.content-nav .sub-list .list-link {
    font-weight: 400
}
.document-header .content-nav .list {
    min-width: 16.25rem
}
  
  body {
    background-image: url('https://edc-cdn.net/assets/images/bg-header-unreal-engine.png');
    background-repeat: no-repeat;
    background-color: #101014;
}

    h2 {
      font-family: Inter;
      font-weight: 900;
    }
  
  @font-face {
font-family : "Recursive Mono";
src : url(https://edc-cdn.net/assets/fonts/recursive-mono-regular.woff2) format("woff2");
font-weight : 400;
font-style : normal;
}
@font-face {
font-family : Inter;
src : url(https://edc-cdn.net/assets/fonts/inter-light.woff2) format("woff2");
font-weight : 300;
font-style : normal;
font-display : swap;
}
@font-face {
font-family : Inter;
src : url(https://edc-cdn.net/assets/fonts/inter-regular.woff2) format("woff2");
font-weight : 400;
font-style : normal;
font-display : swap;
}
@font-face {
font-family : Inter;
src : url(https://edc-cdn.net/assets/fonts/inter-medium.woff2) format("woff2");
font-weight : 500;
font-style : normal;
font-display : swap;
}
@font-face {
font-family : Inter;
src : url(https://edc-cdn.net/assets/fonts/inter-bold.woff2) format("woff2");
font-weight : 700;
font-style : normal;
font-display : swap;
}
@font-face {
font-family : "Inter Tight";
src : url(https://edc-cdn.net/assets/fonts/inter-tight.woff2) format("woff2");
font-weight : 900;
font-style : normal;
font-display : swap;
}

.h1, .h2, .h3, .h4, .h5, .h6, h1, h2, h3, h4, h5, h6 {
    margin-bottom: .5rem;
    font-weight: 500;
    margin-top: 0;
    margin-bottom: 1rem;
    font-family: 'Inter Tight', Inter, -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol;
    font-weight: 900;
    line-height: 1.25;
}
  
      doc-h2 {
        font-family: Inter;
        font-weight: 900;
      }
      .profile {
            background-color: translate;
            width: 56rem;
            box-shadow: 0 0 0px rgba(0, 0, 0, 0);
            margin-left: 0 auto;
            margin-right: 0 auto;
            margin-top: 15px;
        }
        .doc-article {
            margin: 0 auto;
        }
        .doc-container {
            width: 56rem;
            height: auto;
            align-items: stretch;
            background-color: #202024;
            overflow: hidden;
            border-radius: 10px;
            padding: 0px;
            margin-top: 25px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            display: flex;
            flex-direction: row;
        }
        .doc-image {
            width: 15%;
            height: auto;
            max-width: 15%;
            border-bottom-left-radius: 10px;
            border-top-left-radius: 10px;
            background-color: #222;
            object-fit: cover;
        }
        .doc-details {
            flex-direction: column;
            align-items: flex-start;
            padding-top: 15px;
            overflow-wrap: break-all;
            padding-bottom: 15px;
            margin-left: 20px; 
            display: flex;
            justify-content: center;
        }
        .doc-title {
            font-size: 16px;
            font-weight: bold;
            margin-bottom: 5px;
            color: #aaa;
        }
        .doc-desc {
            font-size: 14px;
            color: #aaa;
            margin-bottom: 5px;
        }


  .doc-links {
    color: #26bbff;
    text-decoration: underline;
  }

  .doc-links:hover {
    color: #26bbff;
    text-decoration: none;
  }
      a {
        color: #aaa;
      }

      a:hover {
        color: #eee;
      }
      .doc-p {
        color: #aaa;
      }
      .breadcrumb {
        background-color: transparent;
      }

.breadcrumb-item {
  color: #aaa;
}
  
.breadcrumb-item.active {
    color: #eee;
}
  .document-thumbnail {
    width: 56rem;
    height: auto;
    border-radius: 12px;
    margin-bottom: 2rem;
}
.alert-doc-warn {
            background-color: #bbcc330d;
            border: .125rem solid #bc3;
            border-radius: 8px;
        }
td {
  background-color: #202024;
  padding-left: 10px;
  padding: 20px 0px;
}

  .td3 {
  background-color: #202024;
    border-top-left-radius: 8px;
}
  .td4 {
  background-color: #202024;
    border-top-right-radius: 8px;
}
  .td1 {
  background-color: #202024;
    border-bottom-right-radius: 8px;
}
  .td2 {
  background-color: #202024;
    border-bottom-left-radius: 8px;
}
  th {
  background-color: transparent;
    padding-left: 10px;
}

code {
    border-radius: .5rem;
    border: .0625rem solid #262B3D;
    background: #0c0d16;
  color: white;
    padding: .125rem .4375rem;
}
  
  .markdown-body table:not(.highlight) th {
    padding-top: 12px;
    padding-bottom: 12px;
    font-weight: 500;
    text-align: left;
    background-color: transparent;
    border: 0px solid transparent;
    color: white;
}

  .markdown-body table:not(.highlight) td, .markdown-body table:not(.highlight) th {
    border: 0px solid transparent;
padding: 18px 16px;
}
th, td {
  padding-left: 20px;
}

  table {
border-collapse: separate;
    border-spacing: 0 .125rem;
    line-height: 1.4;
    font-size: .875rem;
    margin-bottom: 0;
  }
  .table>:not(caption)>*>* {
    padding: 1.125rem 1rem;
    border-bottom-width: .125rem;
}
</style>
<div class="content-nav-container">
<content-nav class="content-nav">
  <header class="content-nav-header">
    <div class="title">on this site</div>
  </header>
  <ul class="list">
    <li class="list-item is-level-1">
      <a class="list-link" href="#menubar">Menu Bar</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#maintoolbar">Main Toolbar</a>
    </li>
        <li class="list-item is-level-2">
      <a class="list-link" href="#savebutton">1. Save Button</a>
    </li>
    <li class="list-item is-level-2">
      <a class="list-link" href="#modeselection">2. Mode Selection</a>
    </li>
        <li class="list-item is-level-2">
      <a class="list-link" href="#contentshortcuts">3. Content Shortcuts</a>
    </li>
        <li class="list-item is-level-2">
      <a class="list-link" href="#playmodecontrols">4. Play Mode Controls</a>
    </li>
        <li class="list-item is-level-2">
      <a class="list-link" href="#platformsmenu">5. Platforms Menu</a>
    </li>
    <li class="list-item is-level-2">
      <a class="list-link" href="#settings">6. Settings</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#levelviewport">Level Viewport</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#contentbrowser-contentdrawer">Content Browser / Content Drawer</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#bottomtoolbar">Bottom Toolbar</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#outliner">Outliner</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#detailspanel">Details Panel</a>
    </li>
    
</ul>
</content-nav>
</div>
<center>
<div class="profile">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="/devcreate/">Developer</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/">Documentation</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/unreal-editor/">Unreal Editor for DevNite</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/unreal-editor/get-started/">Get Started</a></li>
    <li class="breadcrumb-item active" aria-current="page">Unreal Editor Interface</li>
  </ol>
    <h1 style="text-align: left;" class="h2">Unreal Editor Interface</h1>
    <p style="text-align: left;" class="doc-p">Overview of the key elements of the Unreal Editor interface</p><br>
  <img width="1920" height="335" class="document-thumbnail" src="https://ue-cdn.artstation.com/imgproxy/GZPUr12sG24cwLowRvirYfQJ_NRSeH3lAOCTD9bjfOw/filename:ue5-hero.png/resizing_type:fill/width:1920/height:335/ext:jpg/aHR0cHM6Ly9kMWl2N2RiNDR5aGd4bi5jbG91ZGZyb250Lm5ldC9kb2N1bWVudGF0aW9uL2ltYWdlcy9jZjNiMGJjYy0yMGI3LTQzYzEtYWM2MC1mNmQ1OTc2MDc3MTgvdWU1LWhlcm8ucG5n" alt="Unreal Engine 5.0 Documentation">
  <p style="text-align: left;">This page describes the most common elements of the <strong>Unreal Engine 5 interface</strong> and what they do. It also links to other pages where you can learn more. Some of the elements described on this page, such as panels and menu bars, are generally the same across various parts of the engine. You should spend some time getting familiar with their general purpose and and functionality, especially if you're new to developing games and applications with Unreal Engine.</p>
  <br>
  <p style="text-align: left;">When you open Unreal Engine 5 for the first time, the <strong>Level Editor</strong> opens. You will see the following window:</p>
    <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/3947c961-4847-4df7-b604-bc0bcf40854a/ue5-default-interface.png" width="800" alt=""></div>
    <table>
  <thead>
    <tr>
      <th scope="col">Number</th>
        <th scope="col">Name</th>
      <th scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class=" td3" style="vertical-align: top;">1</td>
      <td class="" style="vertical-align: top;"><strong>Menu Bar</strong></td>
      <td class=" td4" style="vertical-align: top;">Use these menus to access editor-specific commands and functionality.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">2</td>
      <td class="" style="vertical-align: top;"><strong>Main Menu</strong></td>
      <td class="" style="vertical-align: top;">Contains shortcuts for some of the most common tools and editors in Unreal Engine, as well as shortcuts to enter Play mode (run your game inside Unreal Editor) and to deploy your project to other platforms.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">3</td>
      <td class="" style="vertical-align: top;"><strong>Level Viewport</strong></td>
      <td class="" style="vertical-align: top;">Displays the contents of your Level, such as Cameras, Actors, Static Meshes, and so on.</td>
    </tr>
        <tr>
      <td class="" style="vertical-align: top;">4</td>
      <td class="" style="vertical-align: top;"><strong>Content Drawer</strong> button</td>
      <td class="" style="vertical-align: top;">Opens the <strong>Content Drawer</strong>, from which you can access all of the Assets in your Project.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">5</td>
      <td class="" style="vertical-align: top;"><strong>Bottom Toolbar</strong></td>
      <td class="" style="vertical-align: top;">Contains shortcuts to the Command Console, Output Log, and Derived Data functionality. Also displays source control status.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">6</td>
      <td class="" style="vertical-align: top;"><strong>Outliner</strong></td>
      <td class="" style="vertical-align: top;">Displays a hierarchical tree view of all content in your Level.</td>
    </tr>
        <tr>
      <td class=" td2" style="vertical-align: top;">7</td>
      <td class="" style="vertical-align: top;"><strong>Details</strong> panel</td>
      <td class=" td1" style="vertical-align: top;">Appears when you select an Actor. Displays various properties for that Actor, such as its <strong>Transform</strong> (position in the Level), Static Mesh, Material, and physics settings. This panel displays different settings depending on what you select in the Level Viewport.</td>
    </tr>
  </tbody>
</table><br>
  <section id="menubar" class="h2" style="text-align: left;">Menu Bar</section>
    <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/42484885-71eb-457a-9eab-fcc8a7aae940/menu-bar.png" alt=""></div>
  <p style="text-align: left;">Each editor in Unreal Engine has a <strong>menu bar</strong> that is located in the top-right of that editor window (Windows) or at the top of the screen (macOS). Some of the menus, such as <strong>File</strong>, <strong>Window</strong>, and <strong>Help</strong>, are present in all editor windows, not just the Level Editor. Others are editor-specific.</p><br>
  <section id="maintoolbar" class="h2" style="text-align: left;">Main Toolbar</section>
  <p style="text-align: left;">The <strong>Main Toolbar</strong> contains shortcuts to some of the most used tools and commands in Unreal Editor. It is divided into the following areas:</p>
  <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/a5a0e141-cbf3-4963-b89d-0ef6cebf985b/main-toolbar.png" alt=""></div>
  

<br>
  <section id="savebutton" class="h2" style="text-align: left;">1. Save Button</section>
  <p style="text-align: left;">Click this button to save the Level that is currently open.</p>
  <br>
  <section id="modeselection" class="h2" style="text-align: left;">2. Mode Selection</section>
    <p style="text-align: left;">Contains shortcuts for quickly switching between different modes to edit content within your Level:</p>
  <ul>
    <li style="text-align: left;">Select Editing</li>
    <li style="text-align: left;">Landscape Editing</li>
    <li style="text-align: left;">Foliage Editing</li>
    <li style="text-align: left;">Mesh Painting</li>
    <li style="text-align: left;">Fracture Editing</li>
    <li style="text-align: left;">Brush Editing</li>
  </ul><br>
  <section id="contentshortcuts" class="h2" style="text-align: left;">3. Content Shortcuts</section>
  <p style="text-align: left;">Contains shortcuts for adding and opening common types of content within the Level Editor.</p>
    <table>
  <thead>
    <tr>
      <th class="" scope="col">Shortcut</th>
      <th class="" scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class=" td3" style="vertical-align: top;" scope="row">Create</td>
      <td class=" td4" style="vertical-align: top;">Choose from a list of common Assets to quickly add to your Level. You can also access the <strong>Place Actors</strong> panels from this menu.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;" scope="row">Blueprints</td>
      <td class="" style="vertical-align: top;">Create and access Blueprints.</td>
    </tr>
    <tr>
      <td class=" td2" style="vertical-align: top;" scope="row">Cinematics</td>
      <td class=" td1" style="vertical-align: top;">Create a Level Sequence or Master Sequence cinematic.</td>
    </tr>
  </tbody>
</table><br>
      <section id="playmodecontrols" class="h2" style="text-align: left;">4. Play Mode Controls</section>
  <p style="text-align: left;">Contains shortcut buttons (Play, Skip, Stop, and Eject) for running your game in the Editor.</p><br>
          <section id="platformsmenu" class="h2" style="text-align: left;">5. Platforms Menu</section>
  <p style="text-align: left;">Contains a series of options you can use to configure, prepare, and deploy your project to different platforms, such as desktop, mobile, or consoles.</p><br>
          <section id="settings" class="h2" style="text-align: left;">6. Settings</section>
  <p style="text-align: left;">Contains various settings for the Unreal Editor, Level Editor Viewport, and game behavior.</p><br>
              <section id="levelviewport" class="h2" style="text-align: left;">Level Viewport</section>
  <p style="text-align: left;">The <strong>Level Viewport</strong> displays the contents of the Level that is currently open. When you open a project in Unreal Engine, the project's default Level opens in the Level Viewport by default. This is where you can view and edit the contents of your active Level, whether it's a game environment, a product visualization app, or something else.</p>
      <p style="text-align: left;">The Level Viewport can generally display the contents of the Level in two different ways:</p>
    <ul>
      <li style="text-align: left;"><strong>Perspective</strong>, which is a 3D view you can navigate to see the contents of the viewport from different angles.</li>
      <li style="text-align: left;"><strong>Ortographic</strong>, which is a 2D view that looks down one of the main axes (X, Y, or Z).</li>
    </ul>
    <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/abc80d74-e0a6-4a72-a9a9-74f932e16408/viewport-examples.png" width="600" alt=""></div><br>
    <section id="contentbrowser-contentdrawer" class="h2" style="text-align: left;">Content Browser / Content Drawer</section>
    <p style="text-align: left;">The <strong>Content Browser</strong> is a file explorer window that displays all of the Assets, Blueprints, and other files contained in your project. You can use it to browse through your content, drag Assets into the Level, migrate Assets between projects, and more.</p>
    <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/1b58678d-b5de-46fb-ae3d-da81a4d7144e/content-browser.png" width="800" alt=""></div>
    <p style="text-align: left;">The <strong>Content Drawer</strong> button, located in the bottom-left corner of the Unreal Editor, opens a special instance of the Content Browser that automatically minimizes when it loses focus (that is, when you click away from it). To keep it open, click the <strong>Dock in Layout</strong> button in the top-right corner of the Content Drawer. This creates a new instance of the Content Browser, but you can still open a new Content Drawer.</p>
    <br>
    <section id="bottomtoolbar" class="h2" style="text-align: left;">Bottom Toolbar</section>
    <p style="text-align: left;">The Bottom Toolbar contains shortcuts to the Command Console, Output Log, and Derived Data functionality. It also displays source control status. It is divided into the following areas:</p><div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/bf18b6ef-477b-43cc-b6cd-4f847eb53123/bottom-toolbar.png" alt=""></div>
    <table>
      <thead>
    <tr>
      <th class="" scope="col">Number</th>
      <th class="" scope="col">Name</th>
      <th class="" scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class=" td3" style="vertical-align: top;">1</td>
      <td class="" style="vertical-align: top;">Output Log</td>
      <td class=" td4" style="vertical-align: top;">Debugging tool that prints out useful information while your application is running.</td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">2</td>
      <td class="" style="vertical-align: top;"><strong>Command Line</strong></td>
      <td class="" style="vertical-align: top;">Behaves as any other command line interface: enter console commands to trigger specific editor behaviors. <br><div class="alert alert-doc-warn" role="alert"><div style="display: flex;">
        <i class="fa-solid fa-circle-info" style="color: rgb(255, 193, 7); margin-top: 18px;" aria-hidden="true"></i>
  <p style="margin-top: 15px; margin-left: 10px; text-align: left;">Type <code>help</code> and press Enter to open a list of available console commands in your browser.</p></div></div></td>
    </tr>
    <tr>
      <td class="" style="vertical-align: top;">3</td>
      <td class="" style="vertical-align: top;"><strong>Derived Data</strong></td>
      <td class="" style="vertical-align: top;">Provides Derived Data functionality.</td>
    </tr>
    <tr>
      <td class="td2" style="vertical-align: top;">4</td>
      <td class="" style="vertical-align: top;">Source Control Status</td>
      <td class="td1" style="vertical-align: top;">Displays source control status if your project is connected to source control (for example, GitHub or Perforce). Otherwise, this will say <i>Source Control Off</i>.</td>
    </tr>
  </tbody>
</table>
        <br>
    <section id="outliner" class="h2" style="text-align: left;">Outliner</section>
    <p style="text-align: left;">The <strong>Outliner</strong> panel (formerly known as World Outliner) displays a hierarchical view of all content in your Level. By default, it is located in the upper-right corner of the Unreal Editor window.</p>
    <div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/7860d6d9-062e-4564-9a0f-43f69ceff29d/world-outliner.png" alt=""></div>
     <p style="text-align: left;">You can also use the Outliner panel to:</p>
    <ul>
      <li style="text-align: left;">Quickly hide or reveal Actors by clicking their associated <strong>Eye</strong> button.</li>
      <li style="text-align: left;">Access an Actor's <strong>context menu</strong> by right-clicking that Actor. You can then perform additional, Actor-specific operations from that menu.</li>
      <li style="text-align: left;">Create, move, and delete content folders.</li>
    </ul>
        <br>
    <section id="detailspanel" class="h2" style="text-align: left;">Details Panel</section>
    <p style="text-align: left;">When you select an Actor in the Level Viewport, the <strong>Details</strong> panel will show the settings and properties that affect the Actor you selected. By default, it is located on the right side of the Unreal Editor window, under the <strong>World Outliner</strong> panel.</p><div style="display: flex; justify-content: flex-start; align-items: flex-start;"><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/711bb535-278e-4e3f-b48a-6c40d0e9e0f1/details-panel.png" width="900" alt=""></div>
</div>
</center>
<script>
// Code für das Scroll-Verhalten
window.addEventListener('scroll', function() {
  let navLinks = document.querySelectorAll('content-nav a');
  let sections = document.querySelectorAll('section');

  sections.forEach((section, index) => {
    let rect = section.getBoundingClientRect();
    if (rect.top <= 0 && rect.bottom >= 0) {
      navLinks.forEach(link => link.classList.remove('is-active'));
      navLinks[index].classList.add('is-active');
    }
  });
});

// Code für das Klick-Verhalten
// JavaScript Code
document.querySelectorAll('.list-link').forEach(item => {
  item.addEventListener('click', event => {
    // Entfernen Sie die is-active Klasse von allen Elementen
    document.querySelectorAll('.list-link').forEach(link => {
      link.classList.remove('is-active');
    });
    // Fügen Sie die is-active Klasse zum geklickten Element hinzu
    event.target.classList.add('is-active');
  })
});
</script>
