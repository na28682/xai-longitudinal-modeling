<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>DarkBrickProductions - TENET LEGO Trailer Analytics</title>
<style>
    body {
        font-family: Arial, sans-serif;
        line-height: 1.6;
        background-color: #f9f9f9;
        color: #333;
        margin: 20px;
    }
    h1, h2 {
        color: #2c3e50;
    }
    table {
        width: 100%;
        border-collapse: collapse;
        margin-bottom: 30px;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: center;
    }
    th {
        background-color: #34495e;
        color: white;
    }
    tr:nth-child(even) {
        background-color: #f2f2f2;
    }
    tr.high-performance {
        background-color: #d4edda; /* light green for high-performing days */
    }
    .note {
        font-size: 0.9em;
        color: #555;
        margin-bottom: 20px;
    }
</style>
</head>
<body>

<h1>DarkBrickProductions YouTube Analytics</h1>

<p class="note">
This project analyzes the performance of my most popular video: <strong>"TENET - New Trailer in LEGO"</strong>. 
The dataset tracks daily views since the video was published, highlights high-performance days (top view counts), 
and adds contextual information such as weekday and month for trend analysis.
</p>

<h2>1. Complete Dataset (Sample)</h2>
<table>
    <thead>
        <tr>
            <th>Date</th>
            <th>Views</th>
            <th>High Performance</th>
        </tr>
    </thead>
    <tbody>
        <tr class="high-performance"><td>2020-07-30</td><td>342</td><td>1</td></tr>
        <tr class="high-performance"><td>2020-07-31</td><td>415</td><td>1</td></tr>
        <tr><td>2020-08-01</td><td>146</td><td>NA</td></tr>
        <tr><td>2020-08-02</td><td>187</td><td>NA</td></tr>
        <tr><td>2020-08-03</td><td>129</td><td>NA</td></tr>
        <tr><td>2020-08-04</td><td>67</td><td>NA</td></tr>
        <tr><td>2020-08-05</td><td>85</td><td>NA</td></tr>
        <tr><td>2020-08-06</td><td>103</td><td>NA</td></tr>
        <tr><td>2020-08-07</td><td>99</td><td>NA</td></tr>
        <tr><td>2020-08-08</td><td>141</td><td>NA</td></tr>
    </tbody>
</table>

<p class="note">
The full dataset contains 2,020 rows. High-performance days are flagged with <strong>1</strong> and highlighted in green.
</p>

<h2>2. High-Performance Days</h2>
<table>
    <thead>
        <tr>
            <th>Date</th>
            <th>Views</th>
            <th>High Performance</th>
        </tr>
    </thead>
    <tbody>
        <tr class="high-performance"><td>2020-07-30</td><td>342</td><td>1</td></tr>
        <tr class="high-performance"><td>2020-07-31</td><td>415</td><td>1</td></tr>
    </tbody>
</table>

<h2>3. Dataset with Weekday and Month</h2>
<table>
    <thead>
        <tr>
            <th>Date</th>
            <th>Views</th>
            <th>Weekday</th>
            <th>Month</th>
        </tr>
    </thead>
    <tbody>
        <tr class="high-performance"><td>2020-07-30</td><td>342</td><td>Thursday</td><td>July</td></tr>
        <tr class="high-performance"><td>2020-07-31</td><td>415</td><td>Friday</td><td>July</td></tr>
        <tr><td>2020-08-01</td><td>146</td><td>Saturday</td><td>August</td></tr>
        <tr><td>2020-08-02</td><td>187</td><td>Sunday</td><td>August</td></tr>
        <tr><td>2020-08-03</td><td>129</td><td>Monday</td><td>August</td></tr>
        <tr><td>2020-08-04</td><td>67</td><td>Tuesday</td><td>August</td></tr>
        <tr><td>2020-08-05</td><td>85</td><td>Wednesday</td><td>August</td></tr>
        <tr><td>2020-08-06</td><td>103</td><td>Thursday</td><td>August</td></tr>
        <tr><td>2020-08-07</td><td>99</td><td>Friday</td><td>August</td></tr>
        <tr><td>2020-08-08</td><td>141</td><td>Saturday</td><td>August</td></tr>
    </tbody>
</table>

<p class="note">
Analyzing trends by weekday and month helps understand audience engagement patterns for this particular video. 
High-performance days often align with initial release dates or promotional activity.
</p>

</body>
</html>
