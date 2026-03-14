# Hello World
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="css/custom.css">
    <link rel="icon" href="https://www.genesys.com/wp-content/themes/genesys-kraken/logo/favicon32.png" sizes="32x32" type="image/png">
    <title>Genesys - AI Enablement</title>
</head>

<body>
<header>
  <div class="branding">
    <div class="branding-logo">
      <img src="images/adaptive-g-orange.png" alt="Adaptive G Logo">
    </div>
    <span class="branding-text">AI Studio</span>
    <div class="branding-icon">
      <img src="images/sparkles-solid.svg" alt="Sparkles Icon">
    </div>
  </div>

  <div class="page-title">CSM/SED AI Enablment - Web Messaging</div>

  <div id="headerRight">
    <div class="button">
      <button id="gcdButton">
        <img src="images/white-settings.svg" width="20" height="20">
        Configure
      </button>
    </div>
  </div>
</header>

<!-- CONFIG MODAL -->
<div id="gcdModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>

    <h2>Set Messenger Configuration</h2>

    <label>First Name</label>
    <input type="text" id="firstNameInput">

    <label>Last Name</label>
    <input type="text" id="lastNameInput">

    <label>Organization</label>
    <select id="orgSelect">
      <option value="">-- Select Org --</option>
      <option value="CSM">CSM Org</option>
      <option value="SED">SED Org</option>
      <option value="TAMUSWest2">TAMUSWest2 Org</option>
      <option value="TAMUSEast">TAMUSEast Org</option>
      <option value="Tamcacentral1">TAMCAcentral1 Org</option>  
    </select>
    <br> <br>
    <button id="submitGCD" disabled>
      <img src="images/white-save.svg" style="width:20px; height:20px; margin-right:6px;">
      Save Configuration
    </button>
  </div>
</div>

<script src="js/custom.js"></script>
</body>
</html>
