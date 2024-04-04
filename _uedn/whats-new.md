---
name: What's new?
tools: [Unreal Editor, Updates]
description: Updates for the newest engine version.
---
<html>
<head>
  <style>
    #ticketForm select {
      width: 350px;
      border-radius: 5px;
      outline: none;
      background-color: #242526;
      color: #fff;
    }

    .documentationSection {
      display: none;
    }
  </style>
</head>

<body background="https://edc-cdn.net/assets/images/bg-header-unreal-engine.png">

  <form id="ticketForm">
    <label for="engineversion">Choose Engine Version:</label>
    <select id="engineversion" name="engineversion" onchange="updateText()">
      <option value="select">Choose Engine Version</option>
        <option value="419">Unreal Editor 4.19 Documentation</option>
        <option value="424">Unreal Editor 4.24 Documentation</option>
        <option value="500">Unreal Editor 5.0 Documentation</option>
    </select>
  </form>

  <div id="documentationText" class="documentationSection">
    <p>Select a version to view documentation.</p>
  </div>

  <div id="version419" class="documentationSection">
    <h1>What's new in the 4.19 Editor</h1>
    <p>Documentation for Unreal Editor 4.19</p>
    <h2>Features</h2>
    <h4>Chaos Physics and Chaos Destruction</h4>
        <li>Introduction of the Chaos Physics and Chaos Destruction systems.</li>
        <li>Improved and more realistic physics simulations for in-game objects.</li>
        <li>Enhanced destruction capabilities for creating realistic, dynamic environments.</li>
    <h4>Niagara Visual Effect System</h4>
        <li>Niagara, a new and powerful visual effects (VFX) editor for creating complex particle effects.</li>
        <li>Improved scalability and performance for handling large numbers of particles.</li>
    <h4>Virtual Texturing</h4>
        <li>Virtual Texturing allows for large texture sets to be streamed and displayed dynamically.</li>
        <li>Improved texture streaming and memory management for detailed and expansive worlds.</li>
    <h4>Real-Time Blueprint Editing</h4>
        <li>Real-time updates and changes to Blueprints without the need to restart the editor.</li>
        <li>Faster iteration and development workflows for Blueprint-based systems.</li>
  </div>

  <div id="version424" class="documentationSection">
    <h1>What's new in the 4.24 Editor</h1>
    <p>Documentation for Unreal Editor 4.24.</p>
    <h2>Features</h2>
    <h4>Real-Time Editing</h4>
      <li>Edit the level and push changes directly to the Servers without publishing to a new version.</li>
      <ul><li>Also available while editing (showing your changes live without pushing changes).</li></ul>
      <li>...</li>
    <h4>Creative and Marketplace Assets</h4>
      <li>Add a "MarketplaceItemDefinition" to publish it to the Marketplace</li>
  </div>

  <div id="version500" class="documentationSection">
    <h1>What's new in the 5.0 Editor</h1>
  </div>

  <div id="version514" class="documentationSection">
    <p>Documentation for Unreal Editor 5.14.</p>
  </div>

  <div id="version8432" class="documentationSection">
    <p>Documentation for Unreal Editor 84.32.</p>
  </div>

  <div id="version135" class="documentationSection">
    <p>Documentation for Unreal Editor 1.35.</p>
  </div>

  <div id="version287" class="documentationSection">
    <p>Documentation for Unreal Editor 2.87.</p>
  </div>

  <div id="version1367" class="documentationSection">
    <p>Documentation for Unreal Editor 13.67.</p>
  </div>

  <div id="version9248" class="documentationSection">
    <p>Documentation for Unreal Editor 92.48.</p>
  </div>

  <script>
    function updateText() {
      var selectedVersion = document.getElementById("engineversion").value;
      hideAllSections();
      showSelectedSection(selectedVersion);
    }

    function hideAllSections() {
      var sections = document.getElementsByClassName("documentationSection");
      for (var i = 0; i < sections.length; i++) {
        sections[i].style.display = "none";
      }
    }

    function showSelectedSection(version) {
      var sectionId = "version" + version;
      var selectedSection = document.getElementById(sectionId);
      if (selectedSection) {
        selectedSection.style.display = "block";
      } else {
        document.getElementById("documentationText").style.display = "block";
      }
    }
  </script>
</body>
</html>

