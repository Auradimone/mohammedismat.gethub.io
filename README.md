<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Grades Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 10px;
    }
    h2 {
      font-size: 1.5em;
      font-style: italic;
      margin-bottom: 40px;
      color: #555;
    }
    button {
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Grades Calculator</h1>
  <h2>
    Welcome, fellow future doctor! After six and a half years of endless lectures, caffeine overdoses, and more stress than you care to admit, 
    you've finally arrived. Sit back, relax, and let's see if your grades are as impressive as your insomnia!
  </h2>
  <button onclick="window.location.href='page2.html'">Start</button>
</body>
</html>

<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Choose Your Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }
    h1 {
      margin-bottom: 40px;
    }
    .button-container {
      display: flex;
      justify-content: center;
      gap: 50px;
      margin-bottom: 20px;
    }
    .button-container button {
      padding: 15px 30px;
      font-size: 1.2em;
      cursor: pointer;
    }
    .back-button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>Choose Your Calculator</h1>
  <div class="button-container">
    <button onclick="window.location.href='page3.html'">Term Calculator</button>
    <button onclick="window.location.href='page4.html'">GPA Calculator</button>
  </div>
  <button class="back-button" onclick="window.location.href='index.html'">Back</button>
</body>
</html>

<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Term Calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin-bottom: 20px;
    }
    /* Container for all rows */
    .rows-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 10px;
      margin-bottom: 20px;
    }
    /* Each row contains the credit input and grade select */
    .row {
      display: flex;
      align-items: center; /* Vertically center the items */
      justify-content: center;
      gap: 20px;
    }
    .input-box {
      padding: 5px;
      text-align: center;
      font-size: 1em;
    }
    /* Fixed widths for consistency */
    .credit-input {
      width: 120px;
    }
    .grade-select {
      width: 140px;
    }
    .button-container {
      text-align: center;
      margin-bottom: 10px;
    }
    .back-button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
    }
    .error {
      color: red;
      margin-top: 10px;
    }
    .result-message {
      margin-top: 10px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <h1>Term Calculator</h1>
  
  <!-- Container for the 8 rows -->
  <div class="rows-container">
    <!-- Row 1 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit1" placeholder="Credit Hour 1">
      <select class="input-box grade-select" id="grade1">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 2 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit2" placeholder="Credit Hour 2">
      <select class="input-box grade-select" id="grade2">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 3 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit3" placeholder="Credit Hour 3">
      <select class="input-box grade-select" id="grade3">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 4 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit4" placeholder="Credit Hour 4">
      <select class="input-box grade-select" id="grade4">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 5 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit5" placeholder="Credit Hour 5">
      <select class="input-box grade-select" id="grade5">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 6 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit6" placeholder="Credit Hour 6">
      <select class="input-box grade-select" id="grade6">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 7 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit7" placeholder="Credit Hour 7">
      <select class="input-box grade-select" id="grade7">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
    <!-- Row 8 -->
    <div class="row">
      <input type="number" class="input-box credit-input" id="credit8" placeholder="Credit Hour 8">
      <select class="input-box grade-select" id="grade8">
        <option value="">Select Grade</option>
        <option value="A">A</option>
        <option value="B+">B+</option>
        <option value="B">B</option>
        <option value="C+">C+</option>
        <option value="C">C</option>
      </select>
    </div>
  </div>
  
  <!-- Calculate Button -->
  <div class="button-container">
    <button onclick="calculate()">Calculate</button>
  </div>
  
  <!-- Message Display -->
  <div id="errorMessage" class="error"></div>
  <div id="finalResult" class="result-message"></div>
  
  <!-- Back Button -->
  <button class="back-button" onclick="window.location.href='page2.html'">Back</button>
  
  <script>
    function calculate() {
      // Clear previous messages
      document.getElementById('errorMessage').innerText = "";
      document.getElementById('finalResult').innerText = "";
      
      // Mapping of allowed grade inputs to their numeric values.
      const gradeMapping = {
        "A": 4,
        "B+": 3.5,
        "B": 3,
        "C+": 2.5,
        "C": 2
      };

      let sumRowProducts = 0;
      let sumCreditTimes4 = 0;
      
      // Process each of the 8 rows.
      for (let i = 1; i <= 8; i++) {
        const creditValue = document.getElementById('credit' + i).value;
        const gradeInput = document.getElementById('grade' + i).value.trim();
        
        // Skip row if grade input is empty or "null"
        if (gradeInput === "" || gradeInput.toLowerCase() === "null") {
          continue;
        }
        
        let credit = parseInt(creditValue, 10);
        if (isNaN(credit)) {
          credit = 0;
        }
        
        if (!gradeMapping.hasOwnProperty(gradeInput)) {
          document.getElementById('errorMessage').innerText =
            "Error: Invalid grade input in row " + i + ". Allowed values: A, B+, B, C+, C, or leave blank.";
          return;
        }
        
        let gradeValue = gradeMapping[gradeInput];
        
        // Row product = Credit × GradeValue
        let rowProduct = credit * gradeValue;
        sumRowProducts += rowProduct;
        sumCreditTimes4 += credit * 4;
      }
      
      if (sumCreditTimes4 === 0) {
        document.getElementById('errorMessage').innerText = "Error: Total credit hours multiplied by 4 is zero. Please provide at least one valid row.";
        return;
      }
      
      let J = sumRowProducts * 4;
      let T = J / sumCreditTimes4;
      let formattedT = T.toFixed(2).replace(".", ",");
      
      document.getElementById('finalResult').innerText = "Your GPA is: " + formattedT + "\nCongratulations!";
    }
  </script>
</body>
</html>

<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>GPA calculator</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
    }
    h1 {
      margin-bottom: 10px;
    }
    p.subtitle {
      margin-bottom: 40px;
      font-size: 1.2em;
      color: #777;
    }
    h2 {
      margin-bottom: 30px;
      color: #333;
    }
    .input-container {
      display: flex;
      justify-content: center;
      gap: 15px;
      margin-bottom: 20px;
    }
    .input-container input {
      width: 100px;
      padding: 10px;
      font-size: 1em;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      font-size: 1.2em;
      cursor: pointer;
      margin-bottom: 30px;
    }
    .result {
      margin-top: 20px;
      font-weight: bold;
      font-size: 1.5em;
    }
    .back-button {
      margin-top: 30px;
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <h1>GPA calculator</h1>
  <p class="subtitle">
    Until now! There are two known ways to calculate your GPA, I'm not sure which one is the official one, so until our college gives us more information you can use these two ways to calculate your GPA.
  </p>
  
  <!-- Student Guideline Way Section -->
  <h2>Student Guideline Way</h2>
  <div class="input-container">
    <input type="number" id="year1" placeholder="First Year">
    <input type="number" id="year2" placeholder="Second Year">
    <input type="number" id="year3" placeholder="Third Year">
    <input type="number" id="year4" placeholder="Fourth Year">
    <input type="number" id="year5" placeholder="Fifth Year">
  </div>
  <button onclick="calculateGPA()">Calculate</button>
  <div class="result" id="resultDisplay"></div>
  
  <!-- Alternative Way Section -->
  <h2>Alternative Way</h2>
  <div class="input-container">
    <input type="number" id="altYear1" placeholder="First Year">
    <input type="number" id="altYear2" placeholder="Second Year">
    <input type="number" id="altYear3" placeholder="Third Year">
    <input type="number" id="altYear4" placeholder="Fourth Year">
    <input type="number" id="altYear5" placeholder="Fifth Year">
  </div>
  <button onclick="calculateAlternative()">Calculate</button>
  <div class="result" id="alternativeResultDisplay"></div>
  
  <!-- Back Button -->
  <button class="back-button" onclick="window.location.href='page2.html'">Back</button>
  
  <script>
    function calculateGPA() {
      // Retrieve values; default to 0 if empty
      const year1 = parseFloat(document.getElementById('year1').value) || 0;
      const year2 = parseFloat(document.getElementById('year2').value) || 0;
      const year3 = parseFloat(document.getElementById('year3').value) || 0;
      const year4 = parseFloat(document.getElementById('year4').value) || 0;
      const year5 = parseFloat(document.getElementById('year5').value) || 0;
      
      // Calculation based on the given weights:
      // First Year * 0.10, Second Year * 0.15, Third Year * 0.20,
      // Fourth Year * 0.25, Fifth Year * 0.30
      const sum = (year1 * 0.10) + (year2 * 0.15) + (year3 * 0.20) + (year4 * 0.25) + (year5 * 0.30);
      
      // Display the result, formatted to two decimals
      document.getElementById('resultDisplay').innerText = "Result: " + sum.toFixed(2);
    }
    
    function calculateAlternative() {
      // Retrieve values for the alternative calculation; default to 0 if empty
      const alt1 = parseFloat(document.getElementById('altYear1').value) || 0;
      const alt2 = parseFloat(document.getElementById('altYear2').value) || 0;
      const alt3 = parseFloat(document.getElementById('altYear3').value) || 0;
      const alt4 = parseFloat(document.getElementById('altYear4').value) || 0;
      const alt5 = parseFloat(document.getElementById('altYear5').value) || 0;
      
      // Sum the inputs of the first 3 boxes, divide by 3, then multiply by 0.25.
      const sumFirstThree = alt1 + alt2 + alt3;
      const result1 = (sumFirstThree / 3) * 0.25;
      
      // Multiply the fourth box by 0.35 and the fifth box by 0.40.
      const result2 = alt4 * 0.35;
      const result3 = alt5 * 0.40;
      
      // Sum the results of these multiplications and add to result1.
      const finalAlternative = result1 + result2 + result3;
      
      // Display the final alternative result, formatted to two decimals.
      document.getElementById('alternativeResultDisplay').innerText = "Alternative GPA: " + finalAlternative.toFixed(2);
    }
  </script>
</body>
</html>
