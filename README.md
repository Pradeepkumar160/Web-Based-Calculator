# Web-Based-Calculator
Web-Based Calculator Objective: Created a responsive calculator using HTML, CSS, and JavaScript for basic arithmetic operations. Features: Supports +, −, ×, ÷, % with Clear (C) &amp; Delete (DEL) functions. Real-time display updates and smooth UI interactions. Responsive design with a modern, user-friendly interface.. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web-Based Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="calculator">
        <input type="text" id="display" readonly>
        <div class="buttons">
            <button class="operator" onclick="clearDisplay()">C</button>
            <button class="operator" onclick="deleteLast()">DEL</button>
            <button class="operator" onclick="appendToDisplay('%')">%</button>
            <button class="operator" onclick="appendToDisplay('/')">/</button>

            <button onclick="appendToDisplay('7')">7</button>
            <button onclick="appendToDisplay('8')">8</button>
            <button onclick="appendToDisplay('9')">9</button>
            <button class="operator" onclick="appendToDisplay('*')">×</button>

            <button onclick="appendToDisplay('4')">4</button>
            <button onclick="appendToDisplay('5')">5</button>
            <button onclick="appendToDisplay('6')">6</button>
            <button class="operator" onclick="appendToDisplay('-')">−</button>

            <button onclick="appendToDisplay('1')">1</button>
            <button onclick="appendToDisplay('2')">2</button>
            <button onclick="appendToDisplay('3')">3</button>
            <button class="operator" onclick="appendToDisplay('+')">+</button>

            <button onclick="appendToDisplay('0')">0</button>
            <button onclick="appendToDisplay('.')">.</button>
            <button class="equal" onclick="calculateResult()">=</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
