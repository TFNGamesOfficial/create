---
name: Editor Interface
tools: [Interface, Basics]
description: Learn how to use the editor layout.
---
<script src="https://kit.fontawesome.com/36b257c118.js" crossorigin="anonymous"></script>
<style>

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
        body {
            margin: 0;
            padding: 0;
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
.doc-table1 {
  background-color: #202024;
}
  .doc-table2 {
  background-color: transparent;
}

  
</style><center>
<div class="profile">
  <nav aria-label="breadcrumb">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="/devcreate/">Developer</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/">Documentation</a></li>
    <li class="breadcrumb-item"><a href="#">Unreal Editor for DevNite</a></li>
    <li class="breadcrumb-item active" aria-current="page">Unreal Editor for DevNite Documentation</li>
  </ol>
</nav>
    <h1 style="text-align: left;" class="h2">Unreal Editor Interface</h1>
    <p style="text-align: left;" class="doc-p">Overview of the key elements of the Unreal Editor interface</p><br>
  <img width="1920" height="335" class="document-thumbnail" src="https://ue-cdn.artstation.com/imgproxy/GZPUr12sG24cwLowRvirYfQJ_NRSeH3lAOCTD9bjfOw/filename:ue5-hero.png/resizing_type:fill/width:1920/height:335/ext:jpg/aHR0cHM6Ly9kMWl2N2RiNDR5aGd4bi5jbG91ZGZyb250Lm5ldC9kb2N1bWVudGF0aW9uL2ltYWdlcy9jZjNiMGJjYy0yMGI3LTQzYzEtYWM2MC1mNmQ1OTc2MDc3MTgvdWU1LWhlcm8ucG5n" alt="Unreal Engine 5.0 Documentation">
  <p style="text-align: left;">This page describes the most common elements of the <strong>Unreal Engine 5 interface</strong> and what they do. It also links to other pages where you can learn more. Some of the elements described on this page, such as panels and menu bars, are generally the same across various parts of the engine. You should spend some time getting familiar with their general purpose and and functionality, especially if you're new to developing games and applications with Unreal Engine.</p>
  <br>
  <p style="text-align: left;">When you open Unreal Engine 5 for the first time, the <strong>Level Editor</strong> opens. You will see the following window:</p>
    <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/3947c961-4847-4df7-b604-bc0bcf40854a/ue5-default-interface.png" alt="">
    <table class="table table-hover table-dark">
  <thead>
    <tr>
      <th class="doc-table2" scope="col">Number</th>
        <th class="doc-table2" scope="col">Name</th>
      <th class="doc-table2" scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="doc-table1">1</th>
      <td class="doc-table1"><strong>Menu Bar</strong></td>
      <td class="doc-table1">Use these menus to access editor-specific commands and functionality.</td>
    </tr>
    <tr>
      <th class="doc-table1">2</th>
      <td class="doc-table1"><strong>Main Menu</strong></td>
      <td class="doc-table1">Contains shortcuts for some of the most common tools and editors in Unreal Engine, as well as shortcuts to enter Play mode (run your game inside Unreal Editor) and to deploy your project to other platforms.</td>
    </tr>
    <tr>
      <th class="doc-table1">3</th>
      <td class="doc-table1"><strong>Level Viewport</strong></td>
      <td class="doc-table1">Displays the contents of your Level, such as Cameras, Actors, Static Meshes, and so on.</td>
    </tr>
        <tr>
      <th class="doc-table1">4</th>
      <td class="doc-table1"><strong>Content Drawer</strong> button</td>
      <td class="doc-table1">Opens the <strong>Content Drawer</strong>, from which you can access all of the Assets in your Project.</td>
    </tr>
    <tr>
      <th class="doc-table1">5</th>
      <td class="doc-table1"><strong>Bottom Toolbar</strong></td>
      <td class="doc-table1">Contains shortcuts to the Command Console, Output Log, and Derived Data functionality. Also displays source control status.</td>
    </tr>
    <tr>
      <th class="doc-table1">6</th>
      <td class="doc-table1"><strong>Outliner</strong></td>
      <td class="doc-table1">Displays a hierarchical tree view of all content in your Level.</td>
    </tr>
        <tr>
      <th class="doc-table1">7</th>
      <td class="doc-table1"><strong>Details</strong> panel</td>
      <td class="doc-table1">Appears when you select an Actor. Displays various properties for that Actor, such as its <strong>Transform</strong> (position in the Level), Static Mesh, Material, and physics settings. This panel displays different settings depending on what you select in the Level Viewport.</td>
    </tr>
  </tbody>
</table><br>
  <h2 style="text-align: left;">Menu Bar</h2>
    <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/42484885-71eb-457a-9eab-fcc8a7aae940/menu-bar.png" alt="">
  <p style="text-align: left;">Each editor in Unreal Engine has a <strong>menu bar</strong> that is located in the top-right of that editor window (Windows) or at the top of the screen (macOS). Some of the menus, such as <strong>File</strong>, <strong>Window</strong>, and <strong>Help</strong>, are present in all editor windows, not just the Level Editor. Others are editor-specific.</p><br>
  <h2 style="text-align: left;">Main Toolbar</h2>
  <p style="text-align: left;">The <strong>Main Toolbar</strong> contains shortcuts to some of the most used tools and commands in Unreal Editor. It is divided into the following areas:</p>
  <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/a5a0e141-cbf3-4963-b89d-0ef6cebf985b/main-toolbar.png" alt="">
  

<br>
  <h2 style="text-align: left;">1. Save Button</h2>
  <p style="text-align: left;">Click this button to save the Level that is currently open.</p>
  <br>
  <h2 style="text-align: left;">2. Mode Selection</h2>
    <p style="text-align: left;">Contains shortcuts for quickly switching between different modes to edit content within your Level:</p>
  <ul>
    <li style="text-align: left;">Select Editing</li>
    <li style="text-align: left;">Landscape Editing</li>
    <li style="text-align: left;">Foliage Editing</li>
    <li style="text-align: left;">Mesh Painting</li>
    <li style="text-align: left;">Fracture Editing</li>
    <li style="text-align: left;">Brush Editing</li>
  </ul><br>
  <h2 style="text-align: left;">3. Content Shortcuts</h2>
  <p style="text-align: left;">Contains shortcuts for adding and opening common types of content within the Level Editor.</p>
    <table class="table table-hover table-dark">
  <thead>
    <tr>
      <th class="doc-table2" scope="col">Shortcut</th>
      <th class="doc-table2" scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="doc-table1" scope="row">Create</th>
      <td class="doc-table1">Choose from a list of common Assets to quickly add to your Level. You can also access the <strong>Place Actors</strong> panels from this menu.</td>
    </tr>
    <tr>
      <th class="doc-table1" scope="row">Blueprints</th>
      <td class="doc-table1">Create and access Blueprints.</td>
    </tr>
    <tr>
      <th class="doc-table1" scope="row">Cinematics</th>
      <td class="doc-table1">Create a Level Sequence or Master Sequence cinematic.</td>
    </tr>
  </tbody>
</table><br>
      <h2 style="text-align: left;">4. Play Mode Controls</h2>
  <p style="text-align: left;">Contains shortcut buttons (Play, Skip, Stop, and Eject) for running your game in the Editor.</p><br>
          <h2 style="text-align: left;">5. Platforms Menu</h2>
  <p style="text-align: left;">Contains a series of options you can use to configure, prepare, and deploy your project to different platforms, such as desktop, mobile, or consoles.</p><br>
          <h2 style="text-align: left;">6. Settings</h2>
  <p style="text-align: left;">Contains various settings for the Unreal Editor, Level Editor Viewport, and game behavior.</p><br>
              <h2 style="text-align: left;">Level Viewport</h2>
  <p style="text-align: left;">The <strong>Level Viewport</strong> displays the contents of the Level that is currently open. When you open a project in Unreal Engine, the project's default Level opens in the Level Viewport by default. This is where you can view and edit the contents of your active Level, whether it's a game environment, a product visualization app, or something else.</p>
      <p style="text-align: left;">The Level Viewport can generally display the contents of the Level in two different ways:</p>
    <ul>
      <li style="text-align: left;"><strong>Perspective</strong>, which is a 3D view you can navigate to see the contents of the viewport from different angles.</li>
      <li style="text-align: left;"><strong>Ortographic</strong>, which is a 2D view that looks down one of the main axes (X, Y, or Z).</li>
    </ul>
    <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/abc80d74-e0a6-4a72-a9a9-74f932e16408/viewport-examples.png" alt=""><br>
    <h2 style="text-align: left;">Content Browser / Content Drawer</h2>
    <p style="text-align: left;">The <strong>Content Browser</strong> is a file explorer window that displays all of the Assets, Blueprints, and other files contained in your project. You can use it to browse through your content, drag Assets into the Level, migrate Assets between projects, and more.</p>
    <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/1b58678d-b5de-46fb-ae3d-da81a4d7144e/content-browser.png" alt="">
    <p style="text-align: left;">The <strong>Content Drawer</strong> button, located in the bottom-left corner of the Unreal Editor, opens a special instance of the Content Browser that automatically minimizes when it loses focus (that is, when you click away from it). To keep it open, click the <strong>Dock in Layout</strong> button in the top-right corner of the Content Drawer. This creates a new instance of the Content Browser, but you can still open a new Content Drawer.</p>
    <br>
    <h2 style="text-align: left;">Bottom Toolbar</h2>
    <p style="text-align: left;">The Bottom Toolbar contains shortcuts to the Command Console, Output Log, and Derived Data functionality. It also displays source control status. It is divided into the following areas:</p><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/bf18b6ef-477b-43cc-b6cd-4f847eb53123/bottom-toolbar.png" alt="">
    <table>
      <thead>
    <tr>
      <th class="doc-table2" scope="col">Number</th>
      <th class="doc-table2" scope="col">Name</th>
      <th class="doc-table2" scope="col">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th class="doc-table1">1</th>
      <td class="doc-table1">Output Log</td>
      <td class="doc-table1">Debugging tool that prints out useful information while your application is running.</td>
    </tr>
    <tr>
      <th class="doc-table1">2</th>
      <td class="doc-table1"><strong>Output Log</strong></td>
      <td class="doc-table1">Behaves as any other command line interface: enter console commands to trigger specific editor behaviors. <br><div class="alert alert-doc-warn" role="alert"><div style="display: flex;">
        <i class="fa-solid fa-circle-info" style="color: rgb(255, 193, 7); margin-top: 18px;" aria-hidden="true"></i>
  <p style="margin-top: 15px; margin-left: 10px; text-align: left;">Type <code>help</code> and press Enter to open a list of available console commands in your browser.</p></div></div></td>
    </tr>
    <tr>
      <th class="doc-table1">3</th>
      <td class="doc-table1"><strong>Derived Data</strong></td>
      <td class="doc-table1">Provides Derived Data functionality.</td>
    </tr>
    <tr>
      <th class="doc-table1">4</th>
      <td class="doc-table1">Source Control Status</td>
      <td class="doc-table1">Displays source control status if your project is connected to source control (for example, GitHub or Perforce). Otherwise, this will say <i>Source Control Off</i>.</td>
    </tr>
  </tbody>
</table>
        <br>
    <h2 style="text-align: left;">Outliner</h2>
    <p style="text-align: left;">The <strong>Outliner</strong> panel (formerly known as World Outliner) displays a hierarchical view of all content in your Level. By default, it is located in the upper-right corner of the Unreal Editor window.</p>
    <img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/7860d6d9-062e-4564-9a0f-43f69ceff29d/world-outliner.png" alt="">
     <p style="text-align: left;">You can also use the Outliner panel to:</p>
    <ul>
      <li>Quickly hide or reveal Actors by clicking their associated <strong>Eye</strong> button.</li>
      <li>Access an Actor's <strong>context menu</strong> by right-clicking that Actor. You can then perform additional, Actor-specific operations from that menu.</li>
      <li>Create, move, and delete content folders.</li>
    </ul>
        <br>
    <h2 style="text-align: left;">Details Panel</h2>
    <p style="text-align: left;">When you select an Actor in the Level Viewport, the <strong>Details</strong> panel will show the settings and properties that affect the Actor you selected. By default, it is located on the right side of the Unreal Editor window, under the <strong>World Outliner</strong> panel.</p><img src="https://d1iv7db44yhgxn.cloudfront.net/documentation/images/711bb535-278e-4e3f-b48a-6c40d0e9e0f1/details-panel.png" alt="">
</div>
</center>
