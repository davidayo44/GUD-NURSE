# GUD-NURSE 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A GOOD NURSE - Master Nursing Online</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#3b82f6',secondary:'#64748b'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
<style>
:where([class^="ri-"])::before { content: "\f3c2"; }
body {
font-family: 'Inter', sans-serif;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
-webkit-appearance: none;
margin: 0;
}
.custom-checkbox {
position: relative;
display: inline-block;
width: 18px;
height: 18px;
margin-right: 8px;
}
.custom-checkbox input {
opacity: 0;
width: 0;
height: 0;
}
.checkmark {
position: absolute;
top: 0;
left: 0;
height: 18px;
width: 18px;
background-color: #fff;
border: 2px solid #d1d5db;
border-radius: 4px;
transition: all 0.2s ease;
}
.custom-checkbox input:checked ~ .checkmark {
background-color: #3b82f6;
border-color: #3b82f6;
}
.checkmark:after {
content: "";
position: absolute;
display: none;
}
.custom-checkbox input:checked ~ .checkmark:after {
display: block;
}
.custom-checkbox .checkmark:after {
left: 5px;
top: 2px;
width: 5px;
height: 10px;
border: solid white;
border-width: 0 2px 2px 0;
transform: rotate(45deg);
}
.custom-switch {
position: relative;
display: inline-block;
width: 48px;
height: 24px;
}
.custom-switch input {
opacity: 0;
width: 0;
height: 0;
}
.slider {
position: absolute;
cursor: pointer;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: #e5e7eb;
transition: .4s;
border-radius: 24px;
}
.slider:before {
position: absolute;
content: "";
height: 20px;
width: 20px;
left: 2px;
bottom: 2px;
background-color: white;
transition: .4s;
border-radius: 50%;
}
input:checked + .slider {
background-color: #3b82f6;
}
input:checked + .slider:before {
transform: translateX(24px);
}
.video-progress {
-webkit-appearance: none;
width: 100%;
height: 6px;
background: #e5e7eb;
border-radius: 3px;
outline: none;
}
.video-progress::-webkit-slider-thumb {
-webkit-appearance: none;
appearance: none;
width: 14px;
height: 14px;
background: #3b82f6;
border-radius: 50%;
cursor: pointer;
}
.video-progress::-moz-range-thumb {
width: 14px;
height: 14px;
background: #3b82f6;
border-radius: 50%;
cursor: pointer;
}
.volume-slider {
-webkit-appearance: none;
width: 80px;
height: 4px;
background: #e5e7eb;
border-radius: 2px;
outline: none;
}
.volume-slider::-webkit-slider-thumb {
-webkit-appearance: none;
appearance: none;
width: 12px;
height: 12px;
background: #3b82f6;
border-radius: 50%;
cursor: pointer;
}
.volume-slider::-moz-range-thumb {
width: 12px;
height: 12px;
background: #3b82f6;
border-radius: 50%;
cursor: pointer;
}
.dropdown {
position: relative;
display: inline-block;
}
.dropdown-content {
display: none;
position: absolute;
background-color: white;
min-width: 160px;
box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
z-index: 1;
border-radius: 8px;
overflow: hidden;
}
.dropdown-content a {
color: #1f2937;
padding: 12px 16px;
text-decoration: none;
display: block;
transition: background-color 0.2s;
}
.dropdown-content a:hover {
background-color: #f3f4f6;
}
.show {
display: block;
}
</style>
</head>
<body class="bg-gray-50 min-h-screen">
<!-- Header -->
<header class="bg-white shadow-sm sticky top-0 z-50">
<div class="container mx-auto px-4 flex items-center justify-between h-16">
<div class="flex items-center">
<a href="#" class="flex items-center mr-10">
<img src="https://static.readdy.ai/image/2f6ae1bb6a2da9fe38b052802b112650/6a7e4afce8e10bff15a7327ac4317fc4.jpeg" alt="A GOOD NURSE Logo" class="h-10 w-auto">
</a>
<nav class="hidden md:flex space-x-8">
<a href="#" class="text-primary font-medium">Home</a>
<a href="#" class="text-gray-700 hover:text-primary transition-colors">Courses</a>
<a href="#" class="text-gray-700 hover:text-primary transition-colors">Resources</a>
<a href="#" class="text-gray-700 hover:text-primary transition-colors">Community</a>
</nav>
</div>
<div class="flex items-center space-x-4">
<div class="relative hidden md:block">
<input type="text" placeholder="Search courses..." class="pl-10 pr-4 py-2 w-64 rounded-full bg-gray-100 focus:outline-none focus:ring-2 focus:ring-primary/20 text-sm">
<div class="absolute left-3 top-2.5 w-5 h-5 flex items-center justify-center text-gray-500">
<i class="ri-search-line"></i>
</div>
</div>
<a href="#" class="text-gray-700 hover:text-primary transition-colors px-4 py-2 rounded-button whitespace-nowrap">Log In</a>
<a href="#" class="bg-primary text-white px-4 py-2 rounded-button shadow-sm hover:bg-primary/90 transition-colors whitespace-nowrap">Sign Up</a>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-gray-700">
<i class="ri-menu-line text-xl"></i>
</button>
</div>
</div>
</header>
<!-- Hero Section -->
<section class="relative">
<div style="background-image: url('https://readdy.ai/api/search-image?query=Professional%20nursing%20education%20scene%20with%20medical%20professionals%20in%20a%20modern%20hospital%20environment%2C%20soft%20lighting%2C%20clean%20and%20sterile%20environment%2C%20medical%20equipment%20visible%2C%20nurses%20and%20doctors%20collaborating%2C%20blue%20and%20white%20color%20scheme%2C%20professional%20atmosphere%2C%20high-quality%20medical%20education&width=1920&height=800&seq=1&orientation=landscape');" class="bg-cover bg-center h-[500px]">
<div class="absolute inset-0 bg-gradient-to-r from-white via-white/90 to-transparent"></div>
<div class="container mx-auto px-4 h-full flex items-center">
<div class="relative z-10 max-w-2xl">
<h1 class="text-4xl md:text-5xl font-bold text-gray-900 mb-4">Master Nursing Online</h1>
<p class="text-lg text-gray-700 mb-8">Comprehensive, accredited nursing education designed by practicing professionals. Advance your career with flexible learning that fits your schedule.</p>
<div class="flex flex-wrap gap-4">
<button class="bg-primary text-white px-6 py-3 rounded-button shadow-md hover:bg-primary/90 transition-colors font-medium !rounded-button whitespace-nowrap">Start Learning Now</button>
<button class="bg-white text-gray-800 px-6 py-3 rounded-button shadow-md border border-gray-200 hover:bg-gray-50 transition-colors font-medium !rounded-button whitespace-nowrap">Explore Courses</button>
</div>
</div>
</div>
</div>
</section>
<!-- Main Content -->
<main class="container mx-auto px-4 py-8 md:py-12">
<div class="flex flex-col lg:flex-row gap-6">
<!-- Left Sidebar - Course Navigation -->
<aside class="lg:w-1/4 bg-white rounded-lg shadow-sm p-4 h-fit sticky top-20">
<h2 class="text-xl font-semibold mb-4">Course Content</h2>
<div class="mb-6">
<div class="flex items-center justify-between mb-2">
<h3 class="font-medium text-gray-900">Module 1: Fundamentals</h3>
<span class="text-xs bg-green-100 text-green-800 px-2 py-1 rounded-full">Completed</span>
</div>
<ul class="pl-4 space-y-2">
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-green-500">
<i class="ri-checkbox-circle-fill"></i>
</div>
Introduction to Nursing
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-green-500">
<i class="ri-checkbox-circle-fill"></i>
</div>
Patient Assessment
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-green-500">
<i class="ri-checkbox-circle-fill"></i>
</div>
Basic Care Procedures
</li>
</ul>
</div>
<div class="mb-6">
<div class="flex items-center justify-between mb-2">
<h3 class="font-medium text-gray-900">Module 2: Clinical Skills</h3>
<span class="text-xs bg-blue-100 text-blue-800 px-2 py-1 rounded-full">In Progress</span>
</div>
<ul class="pl-4 space-y-2">
<li class="flex items-center text-sm text-gray-900 font-medium">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-primary">
<i class="ri-play-circle-fill"></i>
</div>
IV Administration Techniques
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-gray-300">
<i class="ri-checkbox-blank-circle-line"></i>
</div>
Medication Management
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-gray-300">
<i class="ri-checkbox-blank-circle-line"></i>
</div>
Wound Care Protocols
</li>
</ul>
</div>
<div class="mb-6">
<div class="flex items-center justify-between mb-2">
<h3 class="font-medium text-gray-900">Module 3: Specialized Care</h3>
<span class="text-xs bg-gray-100 text-gray-600 px-2 py-1 rounded-full">Upcoming</span>
</div>
<ul class="pl-4 space-y-2">
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-gray-300">
<i class="ri-lock-line"></i>
</div>
Emergency Response
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-gray-300">
<i class="ri-lock-line"></i>
</div>
Critical Care Nursing
</li>
<li class="flex items-center text-sm text-gray-500">
<div class="w-5 h-5 flex items-center justify-center mr-2 text-gray-300">
<i class="ri-lock-line"></i>
</div>
Pediatric Care Essentials
</li>
</ul>
</div>
<button class="w-full py-2 text-primary border border-primary rounded-button hover:bg-primary/5 transition-colors mt-4 whitespace-nowrap">View Full Curriculum</button>
</aside>
<!-- Center Content - Video Player -->
<div class="lg:w-2/4 flex flex-col">
<div class="bg-white rounded-lg shadow-sm overflow-hidden mb-6">
<div class="relative bg-black aspect-video">
<img src="https://readdy.ai/api/search-image?query=Professional%20nursing%20demonstration%20of%20IV%20administration%20technique%20in%20a%20clinical%20setting%2C%20close-up%20of%20hands%20preparing%20IV%20equipment%2C%20sterile%20environment%2C%20medical%20supplies%20visible%2C%20educational%20nursing%20demonstration%2C%20clear%20visualization%20of%20procedure%20steps%2C%20professional%20lighting&width=1280&height=720&seq=2&orientation=landscape" alt="IV Administration Techniques" class="w-full h-full object-cover">
<div class="absolute inset-0 flex items-center justify-center">
<button class="w-16 h-16 bg-primary/90 rounded-full flex items-center justify-center text-white">
<i class="ri-play-fill text-3xl"></i>
</button>
</div>
<div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/70 to-transparent p-4">
<div class="flex items-center justify-between text-white">
<div class="flex items-center space-x-4">
<button class="w-8 h-8 flex items-center justify-center">
<i class="ri-play-fill text-xl"></i>
</button>
<div class="flex items-center space-x-2">
<span class="text-sm">12:45</span>
<span>/</span>
<span class="text-sm">32:10</span>
</div>
</div>
<div class="flex items-center space-x-4">
<div class="flex items-center space-x-2">
<button class="w-8 h-8 flex items-center justify-center">
<i class="ri-volume-up-line"></i>
</button>
<input type="range" class="volume-slider" min="0" max="100" value="80">
</div>
<div class="dropdown">
<button class="w-8 h-8 flex items-center justify-center" onclick="toggleDropdown('quality')">
<i class="ri-settings-3-line"></i>
</button>
<div id="qualityDropdown" class="dropdown-content">
<a href="#">1080p HD</a>
<a href="#">720p HD</a>
<a href="#">480p</a>
<a href="#">360p</a>
<a href="#">Auto</a>
</div>
</div>
<button class="w-8 h-8 flex items-center justify-center">
<i class="ri-fullscreen-line"></i>
</button>
</div>
</div>
<input type="range" class="video-progress mt-2" min="0" max="100" value="40">
</div>
</div>
<div class="p-6">
<h1 class="text-2xl font-semibold mb-2">IV Administration Techniques</h1>
<div class="flex items-center text-sm text-gray-500 mb-4">
<span>Module 2: Clinical Skills</span>
<span class="mx-2">•</span>
<span>Updated April 20, 2025</span>
</div>
<p class="text-gray-700 mb-4">This comprehensive tutorial covers proper IV administration techniques, including equipment selection, site preparation, insertion methods, and monitoring procedures. Learn the critical skills needed for safe and effective intravenous therapy.</p>
<div class="flex flex-wrap gap-2">
<span class="bg-blue-50 text-blue-600 px-3 py-1 rounded-full text-sm">Clinical Skills</span>
<span class="bg-blue-50 text-blue-600 px-3 py-1 rounded-full text-sm">IV Therapy</span>
<span class="bg-blue-50 text-blue-600 px-3 py-1 rounded-full text-sm">Patient Care</span>
</div>
</div>
</div>
<div class="bg-white rounded-lg shadow-sm p-6 mb-6">
<h2 class="text-xl font-semibold mb-4">Video Transcript</h2>
<div class="max-h-60 overflow-y-auto pr-4 text-gray-700 space-y-4">
<p><strong>[00:00]</strong> Welcome to today's tutorial on IV administration techniques. I'm Nurse Sarah Johnson, and I'll be guiding you through the proper procedures for safe and effective intravenous therapy.</p>
<p><strong>[01:25]</strong> Before we begin, let's review the equipment you'll need: IV catheter, extension tubing, IV solution, alcohol swabs, tourniquet, sterile gloves, and transparent dressing.</p>
<p><strong>[03:42]</strong> The first step is proper hand hygiene. Always wash your hands thoroughly or use alcohol-based hand sanitizer before handling any equipment or touching the patient.</p>
<p><strong>[05:18]</strong> Next, we'll assess potential insertion sites. The most common sites include the forearm, back of the hand, and the antecubital fossa. Look for veins that are visible, palpable, and straight.</p>
<p><strong>[08:30]</strong> When selecting a site, avoid areas with bruising, infiltration from previous IVs, phlebitis, sclerosed veins, or areas of infection.</p>
<p><strong>[12:45]</strong> Now we'll prepare the equipment. Connect the extension tubing to the IV solution and prime the line to remove all air bubbles. This is critical to prevent air embolism.</p>
<p><strong>[15:20]</strong> Apply the tourniquet 3-4 inches above the intended insertion site. It should be tight enough to occlude venous flow but not arterial flow.</p>
</div>
<button class="text-primary font-medium mt-4">View Full Transcript</button>
</div>
<div class="bg-white rounded-lg shadow-sm p-6 mb-6">
<div class="flex items-center justify-between mb-4">
<h2 class="text-xl font-semibold">Knowledge Check</h2>
<div class="flex items-center gap-4">
<div class="flex items-center gap-2">
<i class="ri-timer-line text-gray-500"></i>
<span class="text-sm text-gray-500">Time Remaining: <span id="timer" class="font-medium">10:00</span></span>
</div>
<span class="text-sm text-gray-500">5 questions</span>
</div>
</div>
<div id="quiz-container" class="space-y-6">
<div class="question">
<p class="font-medium mb-3">1. During IV administration, a patient develops sudden chest pain, dyspnea, and a decrease in oxygen saturation. Which complication should you suspect first and what immediate action should be taken?</p>
<div class="space-y-2">
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q1" value="a">
<span class="checkmark"></span>
</div>
<span>Infiltration - Stop infusion and elevate extremity</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q1" value="b">
<span class="checkmark"></span>
</div>
<span>Air embolism - Place patient in left lateral Trendelenburg position and stop infusion</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q1" value="c">
<span class="checkmark"></span>
</div>
<span>Phlebitis - Apply warm compress and notify physician</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q1" value="d">
<span class="checkmark"></span>
</div>
<span>Catheter embolism - Administer anticoagulation therapy</span>
</label>
</div>
</div>

<div class="question">
<p class="font-medium mb-3">2. Calculate the IV flow rate for a 1000mL solution to be administered over 8 hours using a drop factor of 15 drops/mL.</p>
<div class="space-y-2">
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q2" value="a">
<span class="checkmark"></span>
</div>
<span>31 drops/minute</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q2" value="b">
<span class="checkmark"></span>
</div>
<span>28 drops/minute</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q2" value="c">
<span class="checkmark"></span>
</div>
<span>35 drops/minute</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q2" value="d">
<span class="checkmark"></span>
</div>
<span>42 drops/minute</span>
</label>
</div>
</div>

<div class="question">
<p class="font-medium mb-3">3. Which of the following combinations of IV medications is potentially incompatible and should NOT be administered through the same line?</p>
<div class="space-y-2">
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q3" value="a">
<span class="checkmark"></span>
</div>
<span>Furosemide and Heparin</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q3" value="b">
<span class="checkmark"></span>
</div>
<span>Calcium gluconate and Ceftriaxone</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q3" value="c">
<span class="checkmark"></span>
</div>
<span>Dopamine and Insulin</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q3" value="d">
<span class="checkmark"></span>
</div>
<span>Potassium chloride and Normal saline</span>
</label>
</div>
</div>

<div class="question">
<p class="font-medium mb-3">4. A patient's IV site shows signs of redness, warmth, and a palpable venous cord extending 3cm above the insertion site. What is the grade of phlebitis according to the VIP (Visual Infusion Phlebitis) score?</p>
<div class="space-y-2">
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q4" value="a">
<span class="checkmark"></span>
</div>
<span>Grade 1</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q4" value="b">
<span class="checkmark"></span>
</div>
<span>Grade 2</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q4" value="c">
<span class="checkmark"></span>
</div>
<span>Grade 3</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q4" value="d">
<span class="checkmark"></span>
</div>
<span>Grade 4</span>
</label>
</div>
</div>

<div class="question">
<p class="font-medium mb-3">5. Which of the following statements about central line-associated bloodstream infections (CLABSI) prevention is FALSE?</p>
<div class="space-y-2">
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q5" value="a">
<span class="checkmark"></span>
</div>
<span>Maximum sterile barrier precautions should be used during insertion</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q5" value="b">
<span class="checkmark"></span>
</div>
<span>Chlorhexidine is preferred over iodine for skin antisepsis</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q5" value="c">
<span class="checkmark"></span>
</div>
<span>Administration sets should be replaced every 96 hours regardless of content</span>
</label>
<label class="flex items-start">
<div class="custom-checkbox mt-0.5">
<input type="radio" name="q5" value="d">
<span class="checkmark"></span>
</div>
<span>Femoral site is preferred over subclavian for infection prevention</span>
</label>
</div>
</div>
</div>

<div id="quiz-results" class="hidden space-y-4">
<div class="p-4 bg-gray-50 rounded-lg">
<div class="flex items-center justify-between mb-2">
<h3 class="font-medium">Your Score</h3>
<span class="text-2xl font-bold text-primary" id="score">0/5</span>
</div>
<div class="h-2 bg-gray-200 rounded-full overflow-hidden">
<div id="score-bar" class="h-full bg-primary transition-all duration-500" style="width: 0%"></div>
</div>
</div>
<div class="space-y-2">
<div class="flex items-center gap-2 text-sm">
<div class="w-3 h-3 rounded-full bg-green-500"></div>
<span>Correct Answers: <span id="correct-count">0</span></span>
</div>
<div class="flex items-center gap-2 text-sm">
<div class="w-3 h-3 rounded-full bg-red-500"></div>
<span>Incorrect Answers: <span id="incorrect-count">0</span></span>
</div>
</div>
<button onclick="retakeQuiz()" class="bg-primary text-white px-4 py-2 rounded-button mt-4 whitespace-nowrap">Retake Quiz</button>
</div>

<button id="submit-quiz" class="bg-primary text-white px-4 py-2 rounded-button mt-6 whitespace-nowrap">Submit Answers</button>
</div>
<div class="bg-white rounded-lg shadow-sm p-6 mb-6">
<h2 class="text-xl font-semibold mb-4">Discussion</h2>
<div class="mb-4">
<textarea placeholder="Share your thoughts or questions about this lesson..." class="w-full p-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/20 focus:border-primary resize-none h-24"></textarea>
</div>
<button class="bg-primary text-white px-4 py-2 rounded-button whitespace-nowrap">Post Comment</button>
<div class="mt-8 space-y-6">
<div>
<div class="flex items-start gap-3 mb-2">
<div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-gray-500 flex-shrink-0">
<i class="ri-user-3-line"></i>
</div>
<div>
<div class="flex items-center gap-2">
<h4 class="font-medium">Emily Rodriguez, RN</h4>
<span class="text-xs text-gray-500">2 days ago</span>
</div>
<p class="text-gray-700 mt-1">I found the tip about using a vein finder device really helpful. Our hospital just got one, and I've been struggling with how to best utilize it. Could you elaborate more on the proper technique for using it with difficult veins?</p>
<div class="flex items-center gap-4 mt-2">
<button class="text-sm text-gray-500 flex items-center gap-1">
<i class="ri-thumb-up-line"></i>
<span>12</span>
</button>
<button class="text-sm text-gray-500">Reply</button>
</div>
</div>
</div>
<div class="ml-12 mt-4">
<div class="flex items-start gap-3">
<div class="w-8 h-8 rounded-full bg-blue-100 flex items-center justify-center text-primary flex-shrink-0">
<i class="ri-user-star-line"></i>
</div>
<div>
<div class="flex items-center gap-2">
<h4 class="font-medium">Dr. Sarah Johnson</h4>
<span class="text-xs bg-blue-100 text-blue-700 px-2 py-0.5 rounded-full">Instructor</span>
<span class="text-xs text-gray-500">1 day ago</span>
</div>
<p class="text-gray-700 mt-1">Great question, Emily! When using a vein finder, it's best to dim the room lights for better contrast. Hold it 4-6 inches above the skin and scan slowly. Look for veins that appear straight and avoid branching points. I'll cover this in more detail in our next lesson on advanced IV techniques.</p>
<div class="flex items-center gap-4 mt-2">
<button class="text-sm text-gray-500 flex items-center gap-1">
<i class="ri-thumb-up-line"></i>
<span>8</span>
</button>
<button class="text-sm text-gray-500">Reply</button>
</div>
</div>
</div>
</div>
</div>
<div>
<div class="flex items-start gap-3">
<div class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center text-gray-500 flex-shrink-0">
<i class="ri-user-3-line"></i>
</div>
<div>
<div class="flex items-center gap-2">
<h4 class="font-medium">Michael Chang, Nursing Student</h4>
<span class="text-xs text-gray-500">5 hours ago</span>
</div>
<p class="text-gray-700 mt-1">I'm still having trouble distinguishing between infiltration and extravasation. Could someone explain the key differences and how to identify each condition during IV therapy?</p>
<div class="flex items-center gap-4 mt-2">
<button class="text-sm text-gray-500 flex items-center gap-1">
<i class="ri-thumb-up-line"></i>
<span>3</span>
</button>
<button class="text-sm text-gray-500">Reply</button>
</div>
</div>
</div>
</div>
</div>
</div>
</div>
<!-- Right Sidebar - Learning Tools -->
<aside class="lg:w-1/4">
<div class="bg-white rounded-lg shadow-sm p-4 mb-6 sticky top-20">
<h2 class="text-xl font-semibold mb-4">My Notes</h2>
<div class="mb-4">
<textarea placeholder="Take notes as you watch..." class="w-full p-3 border border-gray-300 rounded focus:outline-none focus:ring-2 focus:ring-primary/20 focus:border-primary resize-none h-32 text-sm"></textarea>
</div>
<div class="flex justify-between mb-4">
<button class="text-primary flex items-center gap-1 text-sm">
<i class="ri-time-line"></i>
<span>Add Timestamp</span>
</button>
<button class="text-primary flex items-center gap-1 text-sm">
<i class="ri-image-line"></i>
<span>Add Screenshot</span>
</button>
</div>
<button class="w-full bg-primary text-white px-4 py-2 rounded-button whitespace-nowrap">Save Notes</button>
<div class="border-t border-gray-200 mt-6 pt-6">
<div class="flex items-center justify-between mb-4">
<h3 class="font-medium">Saved Notes</h3>
<button class="text-sm text-gray-500">View All</button>
</div>
<div class="space-y-4">
<div class="bg-gray-50 p-3 rounded text-sm">
<div class="flex items-center justify-between mb-1">
<span class="text-xs text-primary font-medium">[05:18] Site Selection</span>
<span class="text-xs text-gray-500">April 23</span>
</div>
<p class="text-gray-700">Remember to avoid areas with bruising or previous infiltration. The forearm veins are usually more stable than hand veins for longer infusions.</p>
</div>
<div class="bg-gray-50 p-3 rounded text-sm">
<div class="flex items-center justify-between mb-1">
<span class="text-xs text-primary font-medium">[12:45] Equipment Prep</span>
<span class="text-xs text-gray-500">April 23</span>
</div>
<p class="text-gray-700">Important: Always prime tubing by holding it upright and allowing solution to flow from bottom to top to ensure all air bubbles are removed.</p>
</div>
</div>
</div>
</div>
<div class="bg-white rounded-lg shadow-sm p-4 mb-6">
<h2 class="text-xl font-semibold mb-4">Resources</h2>
<ul class="space-y-3">
<li>
<a href="#" class="flex items-center p-3 bg-gray-50 rounded hover:bg-gray-100 transition-colors">
<div class="w-8 h-8 flex items-center justify-center text-primary mr-3">
<i class="ri-file-pdf-line text-xl"></i>
</div>
<div>
<h4 class="font-medium text-sm">IV Administration Guidelines</h4>
<span class="text-xs text-gray-500">PDF • 2.4 MB</span>
</div>
</a>
</li>
<li>
<a href="#" class="flex items-center p-3 bg-gray-50 rounded hover:bg-gray-100 transition-colors">
<div class="w-8 h-8 flex items-center justify-center text-primary mr-3">
<i class="ri-file-excel-line text-xl"></i>
</div>
<div>
<h4 class="font-medium text-sm">IV Medication Compatibility Chart</h4>
<span class="text-xs text-gray-500">Excel • 1.8 MB</span>
</div>
</a>
</li>
<li>
<a href="#" class="flex items-center p-3 bg-gray-50 rounded hover:bg-gray-100 transition-colors">
<div class="w-8 h-8 flex items-center justify-center text-primary mr-3">
<i class="ri-file-word-line text-xl"></i>
</div>
<div>
<h4 class="font-medium text-sm">Practice Case Studies</h4>
<span class="text-xs text-gray-500">Word • 850 KB</span>
</div>
</a>
</li>
</ul>
<button class="w-full text-primary border border-primary rounded-button hover:bg-primary/5 transition-colors mt-4 py-2 whitespace-nowrap">View All Resources</button>
</div>
<div class="bg-white rounded-lg shadow-sm p-4">
<h2 class="text-xl font-semibold mb-4">Recommended Next</h2>
<div class="space-y-4">
<a href="#" class="block">
<div class="relative aspect-video rounded overflow-hidden mb-2">
<img src="https://readdy.ai/api/search-image?query=Nurse%20administering%20medication%20to%20patient%2C%20professional%20healthcare%20setting%2C%20medication%20management%20demonstration%2C%20organized%20medication%20tray%2C%20sterile%20environment%2C%20clear%20visualization%20of%20medication%20preparation%2C%20educational%20nursing%20video&width=320&height=180&seq=3&orientation=landscape" alt="Medication Management" class="w-full h-full object-cover">
<div class="absolute inset-0 bg-black/20 flex items-center justify-center">
<div class="w-10 h-10 bg-white/90 rounded-full flex items-center justify-center text-primary">
<i class="ri-play-fill text-xl"></i>
</div>
</div>
<span class="absolute bottom-2 right-2 bg-black/70 text-white text-xs px-2 py-1 rounded">18:45</span>
</div>
<h3 class="font-medium">Medication Management</h3>
<p class="text-sm text-gray-500">Module 2 • Coming up next</p>
</a>
<a href="#" class="block">
<div class="relative aspect-video rounded overflow-hidden mb-2">
<img src="https://readdy.ai/api/search-image?query=Nurse%20demonstrating%20wound%20care%20procedure%2C%20close-up%20of%20hands%20applying%20dressing%2C%20sterile%20wound%20care%20supplies%2C%20clean%20medical%20environment%2C%20educational%20nursing%20demonstration%2C%20professional%20lighting%2C%20detailed%20view%20of%20wound%20care%20technique&width=320&height=180&seq=4&orientation=landscape" alt="Wound Care Protocols" class="w-full h-full object-cover">
<div class="absolute inset-0 bg-black/20 flex items-center justify-center">
<div class="w-10 h-10 bg-white/90 rounded-full flex items-center justify-center text-primary">
<i class="ri-play-fill text-xl"></i>
</div>
</div>
<span class="absolute bottom-2 right-2 bg-black/70 text-white text-xs px-2 py-1 rounded">24:10</span>
</div>
<h3 class="font-medium">Wound Care Protocols</h3>
<p class="text-sm text-gray-500">Module 2 • Lesson 3</p>
</a>
</div>
</div>
</aside>
</div>
</main>
<!-- Footer -->
<footer class="bg-gray-900 text-white py-12">
<div class="container mx-auto px-4">
<div class="grid grid-cols-1 md:grid-cols-4 gap-8">
<div>
<a href="#" class="inline-block mb-4">
<img src="https://static.readdy.ai/image/2f6ae1bb6a2da9fe38b052802b112650/6a7e4afce8e10bff15a7327ac4317fc4.jpeg" alt="A GOOD NURSE Logo" class="h-10 w-auto brightness-0 invert">
</a>
<p class="text-gray-400 mb-4">Empowering nursing professionals with comprehensive online education since 2018.</p>
<div class="flex space-x-4">
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-facebook-fill"></i>
</div>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-twitter-x-fill"></i>
</div>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-instagram-fill"></i>
</div>
</a>
<a href="#" class="text-gray-400 hover:text-white transition-colors">
<div class="w-8 h-8 flex items-center justify-center">
<i class="ri-linkedin-fill"></i>
</div>
</a>
</div>
</div>
<div>
<h3 class="font-semibold text-lg mb-4">Quick Links</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Home</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Courses</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Resources</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Community</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">About Us</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Contact</a></li>
</ul>
</div>
<div>
<h3 class="font-semibold text-lg mb-4">Support</h3>
<ul class="space-y-2">
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Help Center</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">FAQs</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Technical Support</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Feedback</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Terms of Service</a></li>
<li><a href="#" class="text-gray-400 hover:text-white transition-colors">Privacy Policy</a></li>
</ul>
</div>
<div>
<h3 class="font-semibold text-lg mb-4">Subscribe</h3>
<p class="text-gray-400 mb-4">Get the latest updates and nursing resources delivered to your inbox.</p>
<form class="mb-4">
<div class="flex">
<input type="email" placeholder="Your email address" class="px-4 py-2 rounded-l-button bg-gray-800 border-gray-700 text-white focus:outline-none focus:ring-2 focus:ring-primary/30 w-full">
<button type="submit" class="bg-primary text-white px-4 py-2 rounded-r-button whitespace-nowrap">Subscribe</button>
</div>
</form>
<div class="flex flex-wrap gap-2">
<div class="w-10 h-6 flex items-center justify-center bg-white rounded">
<i class="ri-visa-fill text-blue-800 text-lg"></i>
</div>
<div class="w-10 h-6 flex items-center justify-center bg-white rounded">
<i class="ri-mastercard-fill text-red-600 text-lg"></i>
</div>
<div class="w-10 h-6 flex items-center justify-center bg-white rounded">
<i class="ri-paypal-fill text-blue-600 text-lg"></i>
</div>
<div class="w-10 h-6 flex items-center justify-center bg-white rounded">
<i class="ri-apple-fill text-black text-lg"></i>
</div>
</div>
</div>
</div>
<div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400 text-sm">
<p>&copy; 2025 A GOOD NURSE. All rights reserved. Accredited by the Nursing Education Accreditation Commission.</p>
</div>
</div>
</footer>
<script>
function toggleDropdown(type) {
document.getElementById(type + 'Dropdown').classList.toggle('show');
}

window.addEventListener('DOMContentLoaded', function() {
window.onclick = function(event) {
if (!event.target.matches('.dropdown button')) {
var dropdowns = document.getElementsByClassName("dropdown-content");
for (var i = 0; i < dropdowns.length; i++) {
var openDropdown = dropdowns[i];
if (openDropdown.classList.contains('show')) {
openDropdown.classList.remove('show');
}
}
}
}

const correctAnswers = {
q1: 'b',
q2: 'a',
q3: 'b',
q4: 'c',
q5: 'd'
};

let timeLeft = 600;
const timerElement = document.getElementById('timer');
const timerInterval = setInterval(() => {
timeLeft--;
const minutes = Math.floor(timeLeft / 60);
const seconds = timeLeft % 60;
timerElement.textContent = ${minutes}:${seconds.toString().padStart(2, '0')};
if (timeLeft <= 0) {
clearInterval(timerInterval);
submitQuiz();
}
}, 1000);

document.getElementById('submit-quiz').addEventListener('click', submitQuiz);

function submitQuiz() {
clearInterval(timerInterval);
const quizContainer = document.getElementById('quiz-container');
const resultsContainer = document.getElementById('quiz-results');
const submitButton = document.getElementById('submit-quiz');

let correct = 0;
let incorrect = 0;

Object.keys(correctAnswers).forEach(question => {
const selected = document.querySelector(input[name="${question}"]:checked);
if (selected) {
if (selected.value === correctAnswers[question]) {
correct++;
} else {
incorrect++;
}
} else {
incorrect++;
}
});

const score = (correct / 5) * 100;
document.getElementById('score').textContent = ${correct}/5;
document.getElementById('score-bar').style.width = ${score}%;
document.getElementById('correct-count').textContent = correct;
document.getElementById('incorrect-count').textContent = incorrect;

quizContainer.classList.add('hidden');
resultsContainer.classList.remove('hidden');
submitButton.classList.add('hidden');
}

function retakeQuiz() {
timeLeft = 600;
const quizContainer = document.getElementById('quiz-container');
const resultsContainer = document.getElementById('quiz-results');
const submitButton = document.getElementById('submit-quiz');

document.querySelectorAll('input[type="radio"]').forEach(radio => {
radio.checked = false;
});

quizContainer.classList.remove('hidden');
resultsContainer.classList.add('hidden');
submitButton.classList.remove('hidden');

timerInterval = setInterval(() => {
timeLeft--;
const minutes = Math.floor(timeLeft / 60);
const seconds = timeLeft % 60;
timerElement.textContent = ${minutes}:${seconds.toString().padStart(2, '0')};
if (timeLeft <= 0) {
clearInterval(timerInterval);
submitQuiz();
}
}, 1000);
}
});
</script>
</body>
</html>
