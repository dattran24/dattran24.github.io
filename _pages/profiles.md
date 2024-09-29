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
        .badge {
            display: inline-block;
            padding: 10px 20px;
            border-radius: 10px; /* Creates the round shape */
            background: linear-gradient(135deg, #a8cfcb, #1034a6); /* Gradient background */
            color: white; /* Text color */
            font-weight: bold;
            font-size: 0.9em;
            text-align: center;
            cursor: pointer; /* Changes cursor to pointer on hover */
            transition: all 0.3s ease; /* Smooth transition */
        }
        .badge:hover {
            transform: translateY(-3px); /* Lift effect on hover */
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4); /* Shadow on hover */
        }
        .newbage {
        background-color: blue; /* Light gray background for the badge */
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

<div class="badge" onclick="toggleTalks()">Advisors</div>

<div style="margin-top: 20px;"></div> 

<!-- Content to be toggled -->
<div id="talks-content">
    <span class="newbage">PhD Advisor</span>
    <a href="https://borismordukhovich.com/">Prof. Boris Mordukhovich,</a> Distinguished University Professor of Mathematics, Wayne State University
    <div>
        Dissertation: Inexact first-order algorithms in convex and nonconvex optimization
    </div>
    <span class="newbage">PhD Advisor</span>
    <a href="https://sites.google.com/site/khanhpd182/">Dr. Pham Duy Khanh,</a> Ho Chi Minh University of Education
    <div>
        PhD Dissertation: Inexact first-order algorithms in convex and nonconvex optimization
    </div>
    <div>
        Undergraduate Research/Thesis: Some Properties of Gradient Systems
    </div>
</div>

<div style="margin-top: 20px;"></div> 

<div class="badge" onclick="togglestudent()">Supervised Students</div>

<div style="margin-top: 20px;"></div> 

<!-- Content to be toggled -->
<div id="student-content">
    <span class="newbagest">Undergraduate</span>
    Bui Ho Kim Anh, Ho Chi Minh City University of Education  (2024/9 - )
    <div>
        Student Research: Inexact Difference-of-convex Algorithm (co-supervised with Dr. Pham Duy Khanh)
    </div>
    <span class="newbagest">Undergraduate</span>
    Tran Trung Tin, Ho Chi Minh City University of Education  (2024/9 - )
    <div>
        Student Research: Inexact Difference-of-convex Algorithm (co-supervised with Dr. Pham Duy Khanh)
    </div>
    <span class="newbagest">Undergraduate</span>
    Bui Huynh Tram, Ho Chi Minh City University of Education  (2024/9 - )
    <div>
        Student Research: Adaptive finite difference interval estimation for derivative-free optimization (co-supervised with Dr. Pham Duy Khanh)
    </div>
    <span class="newbagest">Undergraduate</span>
    Le Lam Thuan, Ho Chi Minh City University of Education  (2024/9 - )
    <div>
        Student Research: Adaptive finite difference interval estimation for derivative-free optimization (co-supervised with Dr. Pham Duy Khanh)
    </div>
    <span class="newbagest">Undergraduate</span>
    Tran Hoang Phi, Ho Chi Minh City University of Education  (2022/6 - 2023/5)
    <div>
        Undergraduate Thesis: Subgradient Methods and their Applications (co-supervised with Dr. Pham Duy Khanh)
    </div>
    <span class="newbagest">Undergraduate</span>
    To Hoang Thanh, Ho Chi Minh City University of Education  (2022/6 - 2023/5)
    <div>
        Undergraduate Thesis: The Simplex Method for Multiobjective Linear Programming (co-supervised with Dr. Pham Duy Khanh)
    </div>
</div>













