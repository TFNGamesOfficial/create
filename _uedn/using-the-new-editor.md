---
name: Using the Editor (BETA)
tools: [Unreal Editor, BETA, Basics]
description: This is a testing for version selector (not working).
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
  </style>
</head>

<body>

  <h1>Using the Editor (BETA)</h1>

  <form id="ticketForm">
    <label for="engineversion">Choose Engine Version:</label>
    <select id="engineversion" name="engineversion" onchange="updateText()">
      <option value="select">Choose Engine Version</option>
      <optgroup label="Unreal Editor for DevNite">
        <option value="423">Unreal Editor 4.23 Documentation</option>
        <option value="424">Unreal Editor 4.24 Documentation</option>
        <option value="427">Unreal Editor 4.27Plus Documentation</option>
      </optgroup>
      <optgroup label="Unreal Editor for Rhinestone">
        <option value="514">Unreal Editor 5.14 Documentation</option>
        <option value="8432">Unreal Editor 84.32 Documentation</option>
      </optgroup>
      <optgroup label="Unreal Editor for Scoring BR/FB">
        <option value="135">Unreal Editor 1.35 Documentation</option>
        <option value="287">Unreal Editor 2.87 Documentation</option>
        <option value="1367">Unreal Editor 13.67 Documentation</option>
        <option value="9248">Unreal Editor 92.48 Documentation</option>
      </optgroup>
    </select>
  </form>

  <div id="documentationText">
    <p>Select a version to view documentation.</p>
  </div>

  <script>
    function updateText() {
      var selectedVersion = document.getElementById("engineversion").value;
      var documentationText = getDocumentationText(selectedVersion);
      document.getElementById("documentationText").innerHTML = documentationText;
    }

    function getDocumentationText(version) {
      // Placeholder documentation text for each version
      switch (version) {
        case "423":
          return "Unreal Engine 4.23 introduced features such as Niagara Effects System and Chaos Physics.";
        case "424":
          return "Unreal Engine 4.24 included the Virtual Production features with new cine cameras and improvements to the sequencer.";
        case "427":
          return "Unreal Engine 4.27Plus brings enhanced rendering capabilities, improved animation tools, and new virtual production features.";
        case "514":
          return "Unreal Engine 5.14 is a major release with the introduction of the Nanite virtualized geometry and Lumen global illumination.";
        case "8432":
          return "Unreal Engine 84.32 includes advanced AI tools, improved multiplayer features, and enhanced rendering capabilities.";
        case "135":
          return "Unreal Engine 1.35 introduced the basics of level design and basic scripting.";
        case "287":
          return "Unreal Engine 2.87 brought improvements to graphics and the introduction of Kismet visual scripting.";
        case "1367":
          return "Unreal Engine 13.67 featured advanced scripting capabilities and improvements to the rendering engine.";
        case "9248":
          return "Unreal Engine 92.48 includes advanced AI capabilities, improved physics simulation, and enhanced graphics.";
        default:
          return "Select a version to view documentation.";
      }
    }
  </script>

</body>

</html>
