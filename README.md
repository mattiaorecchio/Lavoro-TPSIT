<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <title>Calcolatrice</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .calcolatrice {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    #display {
      width: 100%;
      height: 50px;
      font-size: 24px;
      text-align: right;
      margin-bottom: 10px;
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    .tasti {
      display: grid;
      grid-template-columns: repeat(4, 60px);
      gap: 10px;
      justify-content: center;
    }

    button {
      padding: 15px;
      font-size: 18px;
      border: none;
      background: #e0e0e0;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.2s;
    }

    button:hover {
      background: #d0d0d0;
    }

    .uguale {
      background: #4CAF50;
      color: white;
    }

    .uguale:hover {
      background: #45a049;
    }

    .operatore {
      background: #2196F3;
      color: white;
    }

    .operatore:hover {
      background: #1e87e5;
    }
  </style>
</head>
<body>

  <div class="calcolatrice">
    <input type="text" id="display" disabled>
    <div class="tasti">
      <button onclick="append('7')">7</button>
      <button onclick="append('8')">8</button>
      <button onclick="append('9')">9</button>
      <button class="operatore" onclick="append('/')">/</button>

      <button onclick="append('4')">4</button>
      <button onclick="append('5')">5</button>
      <button onclick="append('6')">6</button>
      <button class="operatore" onclick="append('*')">*</button>

      <button onclick="append('1')">1</button>
      <button onclick="append('2')">2</button>
      <button onclick="append('3')">3</button>
      <button class="operatore" onclick="append('-')">-</button>

      <button onclick="append('0')">0</button>
      <button onclick="append('.')">.</button>
      <button onclick="clearDisplay()">C</button>
      <button class="operatore" onclick="append('+')">+</button>

      <button class="uguale" onclick="calculate()" style="grid-column: span 4;">=</button>
    </div>
  </div>

  <script>
    function append(value) {
      document.getElementById('display').value += value;
    }

    function clearDisplay() {
      document.getElementById('display').value = '';
    }

    function calculate() {
      try {
        const result = eval(document.getElementById('display').value);
        document.getElementById('display').value = result;
      } catch (e) {
        alert('Espressione non valida');
      }
    }
  </script>

</body>
</html>
