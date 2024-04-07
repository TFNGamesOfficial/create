---
name: Hardware and Software Specifications
description: Minimum and recommended hardware specifications and necessary software for developing with Unreal Engine.
tools: [Hardware, Important]
external_url: https://tfngamesofficial.github.io/devcreate/docs/unreal-editor/get-started/hardware-and-software-specifications-for-unreal-engine/
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
  padding-left:20px;
}
  .imgmenu {
    max-width: 887px;
    max-height: 78px;
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
.alert-doc {
            background-color: transparent;
            border: .125rem solid #484E63;
            border-radius: 8px;
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
    width: 56rem;
  }
  .table>:not(caption)>*>* {
    padding: 1.125rem 1rem;
    border-bottom-width: .125rem;
}
.table tbody tr:first-child td:first-child {
    border-top-left-radius: 8px;
}
  .table tbody tr:first-child td:last-child {
    border-top-right-radius: 8px;
}
</style>
<div class="content-nav-container">
<content-nav class="content-nav">
  <header class="content-nav-header">
    <div class="title">on this site</div>
  </header>
  <ul class="list">
    <li class="list-item is-level-1">
      <a class="list-link" href="#recommended-hardware">Recommended Hardware</a>
    </li>
    <li class="list-item is-level-1">
      <a class="list-link" href="#minimum-software-requirements">Minimum Software Requirements</a>
    </li>
</ul>
</content-nav>
</div>
<center>
<div class="profile">
  <ol class="breadcrumb">
    <li class="breadcrumb-item"><a href="/devcreate/">Developer</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/">Documentation</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/unreal-editor/">Unreal Editor for DevNite Documentation</a></li>
    <li class="breadcrumb-item"><a href="/devcreate/docs/unreal-editor/get-started">Get Started</a></li>
    <li class="breadcrumb-item active" aria-current="page">Hardware and Software Specifications</li>
  </ol>
    <h1 style="text-align: left;" class="h2">Hardware and Software Specifications</h1>
    <p style="text-align: left;" class="doc-p">Minimum and recommended hardware specifications and necessary software for developing with UEDN.</p><br>
  <img width="1920" height="335" class="document-thumbnail" src="https://ue-cdn.artstation.com/imgproxy/4bdxJRZWM9eJWM5BY2NW7vke2kZjRc5fCgVhDNZqNwU/filename:uefn-home-hero.png/resizing_type:fill/width:1920/height:335/ext:jpg/aHR0cHM6Ly9kMWl2N2RiNDR5aGd4bi5jbG91ZGZyb250Lm5ldC9kb2N1bWVudGF0aW9uL2ltYWdlcy80MWNiYzg3My03MGRjLTQ2MjMtYTI4Mi0zYjM0MTc1NjU5NzMvdWVmbi1ob21lLWhlcm8ucG5n" alt="Unreal Engine 5.0 Documentation">
  <p style="text-align: left;">This page covers the hardware and software requirements for Unreal Engine. It also describes what is installed by the pre-requisites installer included in the Unreal Engine installer.</p>
  <br>
  <section id="recommended-hardware" class="h2" style="text-align: left;">Recommended Hardware</section>
  <table>
  <thead>
    <tr>
      <th>&nbsp;</th>
      <th>&nbsp;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="td4"><strong>Operating System</strong></td>
      <td class="td3">Windows 10 64-bit version 1909 revision .1350 or higher, or versions 2004 and 20H2 revision .789 or higher</td>
    </tr>
    <tr>
      <td><strong>Processor</strong></td>
      <td>Quad-core Intel or AMD, 2.5 GHz or faster</td>
    </tr>
    <tr>
      <td><strong>Memory</strong></td>
      <td>8 GB RAM</td>
    </tr>
    <tr>
      <td class="td2"><strong>Graphics Card</strong></td>
      <td class="td1">DirectX 11 or 12 compatible graphics card with the latest drivers</td>
    </tr>
  </tbody>
</table>
<br>
<div class="alert alert-doc-warn" role="alert">
    <div style="display: flex;">
        <i class="fa-solid fa-circle-info" style="color: rgb(255, 193, 7); margin-top: 18px;" aria-hidden="true"></i>
          <p style="margin-top: 15px; margin-left: 10px; text-align: left;">Although some features have a minimum requirement of DirectX 11, we recommend DirectX 12 for most games.<br><br>DirectX11 is better for older PCs, especially laptops with integrated graphics. However, DirectX12 provides a higher frame rate, multi-core processing support, and parallel and asynchronous computing.</p>
    </div></div>
  <table>
  <tbody>
    <tr>
      <td class="td3"><strong>Recommended Operating System</strong></td>
      <td class="td4">Latest MacOS 13 Ventura</td>
    </tr>
    <tr>
      <td><strong>Minimum Operating System</strong></td>
      <td>macOS 12.5 Monterey</td>
    </tr>
    <tr>
      <td><strong>Processor</strong></td>
      <td>Quad-core Intel, 2.5 GHz or faster</td>
    </tr>
    <tr>
      <td><strong>Memory</strong></td>
      <td>8 GB RAM</td>
    </tr>
    <tr>
      <td class="td2"><strong>Video Card</strong></td>
      <td class="td1">Metal 1.2 Compatible Graphics Card</td>
    </tr>
  </tbody>
</table><br>
  <table>
  <tbody>
    <tr>
      <td class="td3"><strong>Operating System</strong></td>
      <td class="td4">Ubuntu 22.04</td>
    </tr>
    <tr>
      <td><strong>Processor</strong></td>
      <td>Quad-core Intel or AMD, 2.5 GHz or faster</td>
    </tr>
    <tr>
      <td><strong>Memory</strong></td>
      <td>32 GB RAM</td>
    </tr>
    <tr>
      <td><strong>Video Card</strong></td>
      <td>NVIDIA GeForce 960 GTX or Higher with latest NVIDIA binary drivers</td>
    </tr>
    <tr>
      <td><strong>Video RAM</strong></td>
      <td>8 GB or more</td>
    </tr>
    <tr>
      <td class="td2"><strong>RHI Version</strong></td>
      <td class="td1"><strong>Vulkan:</strong> AMD (21.11.3+) and NVIDIA (515.48+)</td>
    </tr>
  </tbody>
</table><br>
  <div class="alert alert-doc" role="alert">
    <div style="display: flex;">
        <i class="fa-solid fa-circle-info" style="color: #aaaaae; margin-top: 18px;" aria-hidden="true"></i>
        <p style="margin-top: 15px; margin-left: 10px; text-align: left;">To get the most out of rendering features of Unreal Engine 5, such Nanite and Lumen, see the Requirements for UE5 Rendering Features section of this page.</p>
    </div></div>
  <section id="minimum-software-requirements" class="h2" style="text-align: left;">Minimum Software Requirements</section>
  <p style="text-align: left;">Minimum requirements for running the engine or editor are listed below.</p>
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
