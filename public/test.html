

<!DOCTYPE html>
<html>
  <head>
    <title>Fancy Form</title>
    <style>
      body {
        background-color: #eee;
        font-family: Arial, sans-serif;
      }

      .form-container {
        background-color: white;
        margin: 50px auto;
        padding: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        width: 500px;
      }

      .form-container h1 {
        font-size: 30px;
        margin-bottom: 20px;
      }

      .form-group {
        margin-bottom: 20px;
        display: flex;
        flex-direction: column;
      }

      .form-group label {
        margin-bottom: 5px;
        font-size: 18px;
      }

      .form-group input[type="text"] {
        border: none;
        border-bottom: 2px solid #ddd;
        font-size: 18px;
        padding: 5px;
      }

      .form-group input[type="submit"] {
        background-color: #4caf50;
        color: white;
        border: none;
        padding: 10px;
        font-size: 18px;
        cursor: pointer;
        margin-top: 10px;
      }

      .result {
        margin-top: 20px;
        font-size: 18px;
        display: none;
      }

      .result p {
        margin-bottom: 10px;
      }
    </style>
  </head>
  <body>
    <div class="form-container">
      <h1>Fancy Form</h1>
      <form>
        <div class="form-group">
          <label>Input:</label>
          <input type="text" id="input-field" required />
        </div>
        <input type="submit" value="Submit" />
      </form>
      <div class="result">
        <p>Result:</p>
        <div id="result-field"></div>
      </div>
    </div>
    <script>
      const form = document.querySelector("form");
      const input = document.getElementById("input-field");
      const result = document.getElementById("result-field");
      const resultSection = document.querySelector(".result");
      
      form.addEventListener("submit", submitForm);

      async function submitForm(event) {
        event.preventDefault();
        const data = { input: input.value };
        const response = await fetch('/api/request', {
          method: 'POST',
          headers: {'Content-Type': 'application/json'},
          body: JSON.stringify(data)
          })
        const json = await response.json();
        result.textContent = json.choices[0].text;
        resultSection.style.display = "block";
      }
    </script>
  </body>
</html>
