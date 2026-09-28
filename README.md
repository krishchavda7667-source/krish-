<!DOCTYPE html>
<html>
<head>
    <title>Student Prediction</title>

    <style>
        body {
            font-family: Arial;
            background: #f2f5ff;
            text-align: center;
            padding: 40px;
        }

        .box {
            background: white;
            max-width: 400px;
            margin: auto;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 20px #ccc;
        }

        h1 {
            color: #4f46e5;
        }

        input, select, button {
            width: 90%;
            padding: 12px;
            margin: 8px;
            border: 1px solid #ddd;
            border-radius: 7px;
        }

        button {
            background: #4f46e5;
            color: white;
            cursor: pointer;
            border: none;
        }

        .result {
            margin-top: 20px;
            padding: 15px;
            background: #eef2ff;
            border-radius: 10px;
        }
    </style>
</head>

<body>

    <div class="box">
        <h1>🎓 Student Prediction</h1>

        <input type="text" placeholder="Student Name">
        <input type="number" placeholder="Attendance %">
        <input type="number" placeholder="Previous Marks %">
        <input type="number" placeholder="Study Hours">

        <select>
            <option>Select Performance</option>
            <option>Low</option>
            <option>Average</option>
            <option>Good</option>
            <option>Excellent</option>
        </select>

        <button>Predict Performance</button>

        <div class="result">
            <h3>Prediction Result</h3>
            <p>Predicted Score: <b>87%</b></p>
            <p>Performance: <b>Good</b></p>
        </div>
    </div>

</body>
</html>
