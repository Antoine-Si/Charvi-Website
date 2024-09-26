# Charvi-Website
The code for the website Charvi Desai created
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
