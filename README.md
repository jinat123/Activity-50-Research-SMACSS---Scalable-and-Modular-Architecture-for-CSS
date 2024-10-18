<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body class="Base">
    <header class="layout">
        <h1>Welcome to My Website</h1>
      <p>Base: Default styles for HTML elements.</p>
      <p>Layout: Defines the major section of a page.</p>
    </header>
    <div class="Module">
        <p>Module card components buttons go here.</p>
    </div>

    <div class="State">
        <p>State style active</p>
        <h3 class="Theme">Theme style</h3>
        <p class="scalability-maintenance">Project content goes here.</p>
        <button class="button is-active">Active Button</button>
        <button class="button is-disabled">Default Button</button>
    </div>
</body>
</html>

/* Base styles */
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
}

/* Layout styles */
.layout-header {
    background-color: #333;
    color: white;
    padding: 20px;
}

.layout-sidebar {
    width: 200px;
    float: left;
    background-color: #f4f4f4;
}

/* Module styles */
.button {
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

.card {
    border: 1px solid #ddd;
    padding: 20px;
    background-color: white;
}

/* State styles */
.is-active {
    background-color: green;
    color: white;
}

.is-disabled {
    background-color: gray;
    cursor: not-allowed;
}

/* Theme styles */
.theme-dark {
    background-color: black;
    color: white;
}

