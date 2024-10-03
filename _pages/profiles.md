---
layout: page
permalink: /people/
title: People
description: 
nav: true
nav_order: 6
---
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toggle Talks Section</title>
    <style>
        .container {
            display: flex; /* Flexbox for alignment */
            align-items: flex-start; /* Center items vertically */
        }
        .badge {
        display: block; /* Ensures the heading takes up the full width */
        padding: 10px 20px;
        background-color: #1034a6; /* Solid background color */
        color: black; /* Text color */
        font-weight: bold;
        font-size: 1.5em; /* Adjust font size for heading */
        text-align: right; /* Aligns the text to the right */
        transition: all 0.3s ease; /* Smooth transition */
}
        .badge:hover {
            transform: translateY(-3px); /* Lift effect on hover */
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4); /* Shadow on hover */
        }
        .newbage {
        background-color: #2698ba; /* blue gray background for the badge */
        border-radius: 5px; /* Rounded corners */
        padding: 5px 10px; /* Padding inside the badge */
        font-size: 0.8em; /* Slightly smaller font */
        margin-right: 10px; /* Space between badge and name */
        color: white; /* Set the font color to white */
        font-weight: bold;
        }
        .newbagest {
        background-color: grey; /* Light gray background for the badge */
        border-radius: 5px; /* Rounded corners */
        padding: 5px 10px; /* Padding inside the badge */
        font-size: 0.8em; /* Slightly smaller font */
        margin-right: 10px; /* Space between badge and name */
        color: white; /* Set the font color to white */
        font-weight: bold;
        }
        #talks-content {
            display: block; /* Initially show the content */
            margin-top: 10px; /* Space above the content */
        }
        #student-content {
            display: block; /* Initially show the content */
            margin-top: 10px; /* Space above the content */
        }
        .content {
            line-height: 1.5; /* Space between lines */
        }
    </style>
    <script>
        function toggleTalks() {
            var content = document.getElementById('talks-content');
            content.style.display = (content.style.display === 'block') ? 'none' : 'block';
        }
        function togglestudent() {
            var content = document.getElementById('student-content');
            content.style.display = (content.style.display === 'block') ? 'none' : 'block';
        }
    </script>
</head>
<body>

<div style="text-align: right; color: #e5e5e5;">
    <hr style="margin: 0; margin-top: 0px;"> <!-- Set margins to 0 and add a small top margin -->
    <h2 style="display: inline; margin: 0; color: #5c5a5a;">Advisors</h2> <!-- Remove margin -->
</div>



<!-- Content to be toggled -->
<div id="talks-content">
    <div class="container">
        <div class="newbage">PhD Advisor</div>
        <div class="content">
            <a href="https://borismordukhovich.com/" style="font-weight: bold;">Prof. Boris Mordukhovich,</a> Distinguished University Professor of Mathematics, Wayne State University<br>
             Dissertation: Inexact first-order algorithms in convex and nonconvex optimization
        </div>
    </div>
    <div style="margin-top: 20px;"></div> 
    <div class="container">
        <div class="newbage">PhD Advisor</div>
        <div class="content">
            <a href="https://sites.google.com/site/khanhpd182/" style="font-weight: bold;">Dr. Pham Duy Khanh,</a> Ho Chi Minh University of Education<br>
            PhD Dissertation: Inexact first-order algorithms in convex and nonconvex optimization<br>
            Undergraduate Research/Thesis: Some Properties of Gradient Systems
        </div>
    </div>
    <div style="margin-top: 20px;"></div> 
</div>

<div style="margin-top: 40px;"></div> 

<div style="text-align: right;">
    <hr style="margin: 0; margin-top: 0px;">
    <h2 style="display: inline; color: #5c5a5a; text-align: right;">Students</h2> 
</div>


<!-- Content to be toggled -->
<div id="student-content">
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            Bui Ho Kim Anh, Ho Chi Minh City University of Education (2024/9 - )<br>
            Student Research: Inexact Difference-of-convex Algorithm (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div>
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            Tran Trung Tin, Ho Chi Minh City University of Education  (2024/9 - )<br>
            Student Research: Inexact Difference-of-convex Algorithm (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            Bui Huynh Tram, Ho Chi Minh City University of Education  (2024/9 - )<br>
            Student Research: Adaptive finite difference interval estimation for derivative-free optimization (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
           Le Lam Thuan, Ho Chi Minh City University of Education  (2024/9 - )<br>
            Student Research: Adaptive finite difference interval estimation for derivative-free optimization (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            Tran Hoang Phi, Ho Chi Minh City University of Education  (2022/6 - 2023/5)<br>
            Thesis: Subgradient Methods and their Applications (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
    <div class="container">
        <div class="newbagest">Undergraduate</div>
        <div class="content">
            To Hoang Thanh, Ho Chi Minh City University of Education  (2022/6 - 2023/5)<br>
            Thesis: Simplex Method for Multiobjective Linear Programming (co-supervised with Dr. Pham Duy Khanh)
        </div>
    </div> 
    <div style="margin-top: 20px;"></div>
</div>













