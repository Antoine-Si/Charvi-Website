# Charvi-Website
The code for the website Charvi Desai created

//html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MindConnect - Mental Health Resources</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>MindConnect</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#mood-tracker">Mood Tracker</a></li>
                    <li><a href="#resources">Resources</a></li>
                    <li><a href="#videos">Videos</a></li>
                    <li><a href="#self-assessment">Self-Assessment</a></li>
                    <li><a href="#helplines">Helplines</a></li>
                    <li><a href="#professionals">Professionals</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <div class="container">
            <section id="home" class="intro-section">
                <h2>Welcome to MindConnect</h2>
                <p>Your mental health matters. Use our tools and resources to track your mood, access valuable information, and connect with professionals.</p>
                <img src="images/mental_health.jpg" alt="Mental Health Awareness" class="intro-image">
            </section>

            <section id="mood-tracker" class="info-section">
                <h2>Mood Tracker</h2>
                <p>Check-in daily to monitor your emotional well-being.</p>
                <label for="mood">How are you feeling today?</label>
                <select id="mood">
                    <option value="happy">Happy</option>
                    <option value="sad">Sad</option>
                    <option value="stressed">Stressed</option>
                    <option value="anxious">Anxious</option>
                    <option value="neutral">Neutral</option>
                </select>
                <button onclick="trackMood()">Submit</button>
                <p id="mood-result"></p>
            </section>

            <section id="resources" class="info-section">
                <h2>Resources</h2>
                <div class="resource-item">
                    <h3>Understanding Mental Health</h3>
                    <p>Get an overview of mental health and why it's important.</p>
                    <a href="https://www.mentalhealth.gov/basics/what-is-mental-health" class="button">Read More</a>
                </div>
                <div class="resource-item">
                    <h3>Common Mental Health Disorders</h3>
                    <p>Learn about anxiety, depression, bipolar disorder, and more.</p>
                    <a href="https://www.nami.org/About-Mental-Illness/Common-with-Mental-Illness" class="button">Read More</a>
                </div>
                <div class="resource-item">
                    <h3>Online Therapy Services</h3>
                    <p>Access therapy from the comfort of your home.</p>
                    <a href="https://www.betterhelp.com/" class="button">Learn More</a>
                </div>
            </section>

            <section id="videos" class="info-section">
                <h2>Videos & Webinars</h2>
                <div class="resource-item">
                    <h3>Introduction to Cognitive Behavioral Therapy (CBT)</h3>
                    <p>Understand how CBT can help.</p>
                    <a href="https://www.youtube.com/watch?v=9c_Bv_FBE-c" class="button">Watch Video</a>
                </div>
                <div class="resource-item">
                    <h3>Understanding and Managing Depression</h3>
                    <p>Experts discuss managing depression.</p>
                    <a href="https://www.youtube.com/watch?v=XiCrniLQGYc" class="button">Watch Video</a>
                </div>
            </section>

            <section id="self-assessment" class="info-section">
                <h2>Self-Assessment Tools</h2>
                <div class="resource-item">
                    <h3>Depression Screening Questionnaire</h3>
                    <p>Assess your mental health status.</p>
                    <a href="https://www.psycom.net/depression-test" class="button">Start Assessment</a>
                </div>
                <div class="resource-item">
                    <h3>Anxiety Screening Questionnaire</h3>
                    <p>Screen for symptoms of anxiety disorders.</p>
                    <a href="https://www.psycom.net/anxiety-test" class="button">Start Assessment</a>
                </div>
            </section>

            <section id="helplines" class="info-section">
                <h2>Helplines & Crisis Support</h2>
                <div class="resource-item">
                    <h3>National Suicide Prevention Lifeline</h3>
                    <p>1-800-273-TALK (8255) - Available 24/7 for anyone in distress.</p>
                </div>
                <div class="resource-item">
                    <h3>Crisis Text Line</h3>
                    <p>Text "HELLO" to 741741 - Free, 24/7 support via text.</p>
                </div>
            </section>

            <section id="professionals" class="info-section">
                <h2>Professional Services Directory</h2>
                <div class="resource-item">
                    <h3>Search for Therapists and Counselors</h3>
                    <p>Find licensed mental health professionals.</p>
                    <a href="https://www.psychologytoday.com/us/therapists" class="button">Find Professionals</a>
                </div>
                <div class="resource-item">
                    <h3>Online Therapy Services</h3>
                    <p>Access therapy from the comfort of your home.</p>
                    <a href="https://www.betterhelp.com/" class="button">Learn More</a>
                </div>
            </section>
        </div>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 MindConnect. All rights reserved.</p>
            <p>Privacy Policy | Terms of Service | Contact Us</p>
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>

//script.css
/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
    padding: 0 20px;
}

/* Header styles */
header {
    background: #35424a;
    color: #ffffff;
    padding-top: 30px;
    min-height: 70px;
    border-bottom: #e8491d 3px solid;
}

header h1 {
    float: left;
    margin-bottom: 10px;
}

header nav {
    float: right;
    margin-top: 10px;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    padding: 0 20px;
}

header nav ul li a {
    color: #ffffff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 16px;
}

/* Main content styles */
main {
    padding: 30px 0;
}

.intro-section, .info-section {
    background: #ffffff;
    margin-bottom: 30px;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #35424a;
    margin-bottom: 20px;
}

.intro-image {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 20px auto;
}

/* Form styles */
select, button {
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
    border-radius: 4px;
}

button {
    background-color: #e8491d;
    color: #ffffff;
    cursor: pointer;
    border: none;
}

button:hover {
    background-color: #333333;
}

/* Resource items */
.resource-item {
    background: #f9f9f9;
    padding: 15px;
    margin-bottom: 15px;
    border-radius: 5px;
}

.resource-item h3 {
    color: #35424a;
}

.button {
    display: inline-block;
    background: #e8491d;
    color: #ffffff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

.button:hover {
    background: #333333;
}

/* Footer styles */
footer {
    background: #35424a;
    color: #ffffff;
    text-align: center;
    padding: 20px 0;
    margin-top: 20px;
}

/* Responsive design */
@media(max-width: 768px) {
    header h1, header nav, header nav li {
        float: none;
        text-align: center;
        padding: 5px;
    }

    .container {
        width: 95%;
    }
}

//Script .java
// Mood Tracker functionality
function trackMood() {
    const moodSelect = document.getElementById('mood');
    const moodResult = document.getElementById('mood-result');
    const selectedMood = moodSelect.value;
    
    // Store mood in localStorage
    const today = new Date().toISOString().split('T')[0];
    localStorage.setItem(today, selectedMood);
    
    // Display result
    moodResult.textContent = `You're feeling ${selectedMood} today. Take care!`;
    
    // Provide a suggestion based on mood
    const suggestion = getMoodSuggestion(selectedMood);
    moodResult.textContent += ` ${suggestion}`;
}

function getMoodSuggestion(mood) {
    const suggestions = {
        happy: "Great! Why not share your positivity with someone today?",
        sad: "Remember, it's okay to not be okay. Consider talking to a friend or professional.",
        stressed: "Try some deep breathing exercises or take a short walk to clear your mind.",
        anxious: "Grounding techniques can help. Try naming 5 things you can see, 4 you can touch, 3 you can hear, 2 you can smell, and 1 you can taste.",
        neutral: "This could be a good time for self-reflection. What would you like to accomplish today?"
    };
    return suggestions[mood] || "Take some time for self-care today.";
}

// Smooth scrolling for navigation
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Initialize mood tracker on page load
window.onload = function() {
    const today = new Date().toISOString().split('T')[0];
    const savedMood = localStorage.getItem(today);
    if (savedMood) {
        document.getElementById('mood').value = savedMood;
        trackMood();
    }
};
