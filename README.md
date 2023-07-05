<!-- index.html -->
<!DOCTYPE html>
<html>
<head>
  <title>Create Dependent Fields</title>
</head>
<body>
  <h1>Create Dependent Fields</h1>
  <form id="dependentFieldsForm">
    <label for="fieldName">Field Name:</label>
    <input type="text" id="fieldName" required>
    <br>

    <label for="fieldOptions">Field Options (comma-separated):</label>
    <input type="text" id="fieldOptions" required>
    <br>

    <label for="dependentOn">Dependent On:</label>
    <select id="dependentOn">
      <option value="">None</option>
    </select>
    <br>

    <button type="submit">Save Dependent Field</button>
  </form>
  <script src="script.js"></script>
</body>
</html>
