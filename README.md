<!DOCTYPE html>
<html lang="bn">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>House of Programming</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #000 40%, #004d00);
            color: whitesmoke;
            background-attachment: fixed;
            background-repeat: no-repeat;
        }

        header {
            background: linear-gradient(135deg, #1b5e20, #000000);
            padding: 40px;
            text-align: center;
            border-bottom: 4px solid #00ff00;
            box-shadow: 0px 4px 20px rgba(0, 255, 0, 0.3);
            transition: background 0.3s ease, transform 0.3s ease;
            position: relative;
            overflow: hidden;
            border-radius: 20px;
        }

        header:hover {
            transform: scale(1.05);
        }

        h1 {
            margin: 0;
            margin-bottom: 10px;
            font-size: 3.5em; /* Keeping original size */
            color: #ffffff;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
            animation: fadeIn 1s ease-in-out;
        }

        h4 {
            margin: 5px 0 0;
            font-weight: 400;
            color: #d0d0d0;
            letter-spacing: 1px;
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        nav {
            display: flex;
            justify-content: center;
            background: linear-gradient(135deg, #005700, #003300);
            padding: 10px 0;
            border-radius: 20px;
            box-shadow: 0px 5px 15px rgba(0, 255, 0, 0.3);
        }

        nav a {
            padding: 12px 20px;
            color: whitesmoke;
            text-align: center;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            border-radius: 15px;
            margin: 0 15px;
            background-color: rgba(255, 255, 255, 0.1);
            font-size: 1.1em;
        }

        nav a:hover {
            background-color: rgba(18, 18, 18, 0.8);
            color: #00ff00;
            transform: scale(1.1);
        }

        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
            background-color: rgba(30, 30, 30, 0.8);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .topic-box {
            background-color: rgba(50, 50, 50, 0.9);
            padding: 80px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }

        .topic-box:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 255, 0, 0.5);
        }

        h2 {
            font-size: 30px;
            color: rgb(46, 184, 46);
            margin-top: 0;
        }

        .cta {
            background-color: rgba(50, 50, 50, 0.9);
            color: #00ff00;
            padding: 15px 25px;
            text-align: center;
            border-radius: 8px;
            margin-top: 10px;
            display: inline-block;
            text-decoration: none;
            transition: background-color 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
            border: 2px solid transparent;
        }

        .cta:hover {
            background: linear-gradient(145deg, #1c1c1c, #0f0f0f);
            border-radius: 10px;
            box-shadow: 0 6px 15px rgba(0, 255, 0, 0.5);
            transform: scale(1.05);
            border-color: #00ff00;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 18px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        @media (max-width: 768px) {
            section {
                grid-template-columns: 1fr;
            }
        }

        /* === Go Up Button === */
        .go-up {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color:black;
            color: #00ff00;
            border: none;
            border-radius: 5px;
            padding: 10px;
            font-size: 20px; 
            cursor: pointer;
            display: none; 
            transition: background 0.3s;
        }

        .go-up:hover {
            background-color: #005700;
        }

        .go-up i {
            font-size: 20px;
        }
        
    </style>
</head>

<body>
    <header>
        <h1><i class="fas fa-laptop-code"></i> House Of Programming</h1> 
        <h4><i class="fas fa-lightbulb"></i> Learn C programming With Visualization</h4> 
    </header>

    <nav>
        <a href="index.html"><i class="fas fa-home"></i> Home</a>
        <a href="about.html"><i class="fas fa-info-circle"></i> About</a>
        <a href="tutorial.html"><i class="fas fa-book-open"></i> Tutorial</a> 
        <a href="contact.html"><i class="fas fa-address-book"></i> Contact</a> 
    </nav>

    <section>
        <div class="topic-box">
            <h2><i class="fas fa-book"></i> Fundamentals of C</h2>
            <p>C একটি শক্তিশালী, সাধারণ উদ্দেশ্যের প্রোগ্রামিং ভাষা যা অনেক অন্যান্য ভাষাকে প্রভাবিত করেছে। এটি প্রক্রিয়াগত, অর্থাৎ এটি কাজগুলিকে ভাঙার জন্য ফাংশনের উপর নির্ভর করে।</p>
            <a href="tutorial.html#fundamentals" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-cogs"></i> Compiling and Linking</h2>
            <p>C কোডকে মেশিন কোডে রূপান্তর করার প্রক্রিয়া, যেমন কম্পাইল ও লিঙ্কিং।</p>
            <a href="tutorial.html#compiling" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-file-code"></i> Statements and Syntax</h2>
            <p>C তে স্টেটমেন্ট লেখার নিয়ম, যেমন সেমিকোলন এবং কোড ব্লক ব্যবহার।</p>
            <a href="tutorial.html#statements" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-exchange-alt"></i> Control Statements</h2>
            <p>নিয়ন্ত্রণ বিবৃতিগুলি একটি প্রোগ্রামে কার্যক্রমের প্রবাহ পরিবর্তন করতে ব্যবহৃত হয়।</p>
            <a href="tutorial.html#control-statements" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-database"></i> Data Types, Variables, and Extensions</h2>
            <p>C দ্বারা প্রদত্ত বিভিন্ন ডেটা প্রকারের বর্ণনা, ভেরিয়েবল ঘোষণা করার পদ্ধতি এবং এক্সটেনশনের ব্যাখ্যা।</p>
            <a href="tutorial.html#data-types" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-th"></i> Arrays and Strings</h2>
            <p>অ্যারে একসাথে একই ডেটা টাইপের উপাদানের সংগ্রহ, ধারাবাহিক মেমরি অবস্থানে সংরক্ষিত।</p>
            <a href="tutorial.html#arrays-strings" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-cogs"></i> Functions</h2>
            <p>C তে ফাংশনগুলি নির্দিষ্ট কাজ সম্পাদনের জন্য ব্যবহৃত হয়, যা প্রোগ্রামটিকে মডুলার এবং রক্ষণাবেক্ষণ করা সহজ করে।</p>
            <a href="tutorial.html#functions" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-terminal"></i> Console I/O</h2>
            <p>মানক ইনপুট এবং আউটপুট স্ট্রিম ব্যবহার করে ইনপুট এবং আউটপুট অপারেশন।</p>
            <a href="tutorial.html#console-io" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-folder-plus"></i> Structures and Unions</h2>
            <p>ভেরিয়েবলগুলি গ্রুপ করার জন্য ইউজার-ডিফাইন্ড ডেটা টাইপ, এবং মেমরি ব্যবস্থাপনা।</p>
            <a href="tutorial.html#structures-unions" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-map-marker-alt"></i> Pointers</h2>
            <p>পয়েন্টারগুলি এমন ভেরিয়েবল যা অন্য ভেরিয়েবলের মেমরি ঠিকানা সংরক্ষণ করে।</p>
            <a href="tutorial.html#pointers" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-memory"></i> Dynamic Memory Allocation</h2>
            <p>প্রোগ্রামের কার্যক্রমের সময় অ্যালোকেট এবং ফ্রি করার পদ্ধতিগুলি।</p>
            <a href="tutorial.html#dynamic-memory" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-file-alt"></i> File Handling</h2>
            <p>ফাইলের সাথে কাজ করার জন্য ফাইল হ্যান্ডলিং।</p>
            <a href="tutorial.html#file-handling" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-code-branch"></i> Preprocessor Directives</h2>
            <p>কম্পাইলেশনের আগে প্রক্রিয়া করা নির্দেশনা, যেমন `#include` এবং `#define`।</p>
            <a href="tutorial.html#preprocessor" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-bug"></i> Bit Manipulation</h2>
            <p>বিট স্তরের কার্যাবলি নিয়ে কাজ করা।</p>
            <a href="tutorial.html#bit-manipulation" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-exclamation-triangle"></i> Error Handling</h2>
            <p>প্রোগ্রামে ত্রুটি পরিচালনার কৌশলগুলো।</p>
            <a href="tutorial.html#error-handling" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-list-alt"></i> Enumerations</h2>
            <p>ভাল কোড পাঠযোগ্যতার জন্য নামকৃত ধ্রুবক তৈরির জন্য।</p>
            <a href="tutorial.html#enumerations" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-random"></i> Type Casting</h2>
            <p>ডেটা এক প্রকার থেকে অন্য প্রকারে রূপান্তর।</p>
            <a href="tutorial.html#type-casting" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-code"></i> Function Pointers</h2>
            <p>ফাংশনে পয়েন্টার যা ডাইনামিক ফাংশন কলের জন্য ব্যবহৃত হয়।</p>
            <a href="tutorial.html#function-pointers" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-clipboard-list"></i> Basic Structure of a C Program</h2>
            <p>C প্রোগ্রামের সুনির্দিষ্ট সিনট্যাক্স এবং কাঠামোর পরিচিতি, যেমন হেডার এবং `main()` ফাংশন।</p>
            <a href="tutorial.html#basic-structure" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-recycle"></i> Macros</h2>
            <p>কোড রিপিটিশন কমানোর জন্য পুনঃব্যবহৃত কোড স্নিপেট।</p>
            <a href="tutorial.html#macros" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-sync-alt"></i> Static and Global Variables</h2>
            <p>ফাংশন কলের মাধ্যমে তাদের মান রক্ষা করা এবং প্রোগ্রামের লাইফটাইম।</p>
            <a href="tutorial.html#static-global" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-undo"></i> Recursive Functions</h2>
            <p>যে ফাংশনগুলির নিজেকেই কল করে সমস্যার সমাধান।</p>
            <a href="tutorial.html#recursive" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-link"></i> Linked Lists</h2>
            <p>নোটগুলির লিঙ্কযুক্ত কাঠামো তৈরি।</p>
            <a href="tutorial.html#linked-lists" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-table"></i> Hash Tables</h2>
            <p>কী এবং মানের মধ্যে সম্পর্ক, দক্ষ ডেটা পুনরুদ্ধারের জন্য।</p>
            <a href="tutorial.html#hash-tables" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-stream"></i> Multi-threading</h2>
            <p>একাধিক কার্যপএকে একসাথে চালানোর কৌশল।</p>
            <a href="tutorial.html#multi-threading" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>

        <div class="topic-box">
            <h2><i class="fas fa-book-reader"></i> C Standard Library</h2>
            <p>সাধারণ প্রোগ্রামিং কাজের জন্য C এর স্ট্যান্ডার্ড লাইব্রেরী দ্বারা সরবরাহিত ফাংশন এবং ডেটা স্ট্রাকচার।</p>
            <a href="tutorial.html#c-standard-library" class="cta"><i class="fa-solid fa-arrow-right-from-bracket"></i> বিস্তারিত জানুন</a>
        </div>
    </section>

    <footer>
        <p>© 2025 @ All rights reserved.</p>
    </footer>

    <button class="go-up" onclick="scrollToTop()"><i class="fas fa-chevron-up"></i></button>

    <script>
        // Show the button when the user scrolls down 100px from the top of the document
        window.onscroll = function() {
            const goUpButton = document.querySelector('.go-up');
            if (document.body.scrollTop > 100 || document.documentElement.scrollTop > 100) {
                goUpButton.style.display = "block";
            } else {
                goUpButton.style.display = "none";
            }
        };

        // Function to scroll to the top of the page
        function scrollToTop() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth' // Smooth scroll effect
            });
        }
    </script>
</body>

</html>
