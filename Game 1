<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Leo's Grammar Adventure | Present Simple vs Present Continuous</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Comic Neue', 'Segoe UI', 'Comic Sans MS', 'Chalkboard SE', cursive;
            background: linear-gradient(135deg, #f7e6c4 0%, #e8d4a8 100%);
            min-height: 100vh;
            padding: 20px;
        }

        /* Jungle Border */
        .worksheet-container {
            max-width: 1100px;
            margin: 0 auto;
            background: #fffef7;
            border-radius: 40px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
            overflow: hidden;
            position: relative;
        }

        .worksheet-container::before {
            content: "🌿🌴🍃🌱🌳🐒🦜";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            font-size: 40px;
            opacity: 0.1;
            pointer-events: none;
            white-space: nowrap;
            overflow: hidden;
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #2d6a4f, #1b4d3e);
            padding: 25px 30px;
            text-align: center;
            color: white;
            position: relative;
        }

        .header h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            text-shadow: 3px 3px 0 #1b4d3e;
        }

        .header h1 span {
            display: inline-block;
            animation: bounce 1s ease infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }

        .header p {
            font-size: 1.1rem;
            opacity: 0.9;
        }

        .leo-badge {
            position: absolute;
            right: 20px;
            top: 20px;
            background: #f4a261;
            border-radius: 50%;
            padding: 10px;
            font-size: 2rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        /* Student Info */
        .student-info {
            display: flex;
            justify-content: space-between;
            background: #f8f3e0;
            padding: 15px 25px;
            border-bottom: 3px solid #e9c46a;
            flex-wrap: wrap;
            gap: 15px;
        }

        .info-field {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1rem;
        }

        .info-field label {
            font-weight: bold;
            color: #2d6a4f;
        }

        .info-field input {
            border: 2px solid #e9c46a;
            border-radius: 20px;
            padding: 8px 15px;
            font-family: inherit;
            background: white;
        }

        /* Grammar Rules Section */
        .grammar-rules {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            padding: 25px;
            background: #fef9e6;
        }

        .rule-card {
            background: white;
            border-radius: 25px;
            padding: 20px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border-left: 8px solid;
        }

        .rule-card.present-simple {
            border-left-color: #2d6a4f;
        }

        .rule-card.present-continuous {
            border-left-color: #e76f51;
        }

        .rule-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .rule-title.present-simple { color: #2d6a4f; }
        .rule-title.present-continuous { color: #e76f51; }

        .rule-formula {
            background: #f8f3e0;
            padding: 10px;
            border-radius: 15px;
            font-family: monospace;
            font-size: 1rem;
            margin: 10px 0;
            text-align: center;
        }

        .rule-examples {
            margin-top: 10px;
        }

        .rule-examples p {
            padding: 5px 0;
            color: #555;
        }

        .time-words {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-top: 10px;
        }

        .time-badge {
            background: #e9c46a;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            color: #2d6a4f;
            font-weight: bold;
        }

        /* Leo's Story Section */
        .story-section {
            background: linear-gradient(135deg, #e9f5e9, #d4e6d4);
            padding: 25px;
            margin: 0 25px 25px 25px;
            border-radius: 25px;
            position: relative;
        }

        .story-title {
            font-size: 1.4rem;
            color: #2d6a4f;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .story-text {
            background: white;
            padding: 20px;
            border-radius: 20px;
            line-height: 1.8;
            font-size: 1rem;
        }

        .highlight {
            background: #f4a261;
            color: white;
            padding: 2px 8px;
            border-radius: 15px;
            font-weight: bold;
        }

        .tense-badge {
            display: inline-block;
            font-size: 0.7rem;
            background: #e9c46a;
            padding: 2px 6px;
            border-radius: 10px;
            margin-left: 5px;
            vertical-align: middle;
        }

        /* Exercises */
        .exercise {
            padding: 20px 25px;
            border-bottom: 2px dashed #e9c46a;
        }

        .exercise-title {
            font-size: 1.3rem;
            color: #2d6a4f;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .exercise-number {
            background: #f4a261;
            color: white;
            width: 35px;
            height: 35px;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
        }

        /* Exercise 1 - Matching */
        .matching-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
        }

        .matching-item {
            background: #f8f3e0;
            border-radius: 15px;
            padding: 15px;
            display: flex;
            align-items: center;
            gap: 15px;
            cursor: pointer;
            transition: all 0.2s;
        }

        .matching-item:hover {
            transform: translateX(5px);
            background: #e9c46a;
        }

        .matching-emoji {
            font-size: 2rem;
        }

        .matching-text {
            flex: 1;
        }

        .matching-answer {
            font-size: 0.9rem;
            color: #2d6a4f;
            font-weight: bold;
        }

        /* Exercise 2 - Fill Blanks */
        .blank-sentence {
            background: #f8f3e0;
            padding: 15px;
            margin-bottom: 12px;
            border-radius: 15px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 10px;
        }

        .blank-input {
            border: 2px solid #e9c46a;
            border-radius: 25px;
            padding: 8px 15px;
            font-family: inherit;
            width: 150px;
        }

        .blank-input:focus {
            outline: none;
            border-color: #f4a261;
        }

        /* Exercise 3 - Choose */
        .choose-question {
            background: #f8f3e0;
            padding: 15px;
            margin-bottom: 12px;
            border-radius: 15px;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 15px;
        }

        .choose-options {
            display: flex;
            gap: 15px;
        }

        .choose-option {
            display: flex;
            align-items: center;
            gap: 5px;
            cursor: pointer;
        }

        /* Exercise 4 - Picture Match */
        .picture-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }

        .picture-card {
            background: #f8f3e0;
            border-radius: 20px;
            padding: 15px;
            text-align: center;
            transition: all 0.2s;
        }

        .picture-emoji {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        .picture-sentence {
            margin: 10px 0;
            font-size: 0.9rem;
        }

        .picture-input {
            width: 100%;
            border: 2px solid #e9c46a;
            border-radius: 20px;
            padding: 8px;
            font-family: inherit;
            text-align: center;
        }

        /* Check Button */
        .check-section {
            text-align: center;
            padding: 25px;
            background: #fef9e6;
        }

        .check-btn {
            background: linear-gradient(135deg, #2d6a4f, #1b4d3e);
            border: none;
            padding: 15px 40px;
            font-size: 1.2rem;
            font-weight: bold;
            border-radius: 50px;
            color: white;
            cursor: pointer;
            transition: all 0.3s;
            font-family: inherit;
        }

        .check-btn:hover {
            transform: scale(1.05);
            background: linear-gradient(135deg, #40916c, #2d6a4f);
        }

        /* Results */
        .results {
            background: #e9c46a;
            margin: 0 25px 25px 25px;
            padding: 20px;
            border-radius: 25px;
            text-align: center;
            display: none;
        }

        .results.show {
            display: block;
            animation: slideUp 0.3s ease;
        }

        @keyframes slideUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .results h3 {
            color: #2d6a4f;
            margin-bottom: 10px;
        }

        .results-score {
            font-size: 2rem;
            font-weight: bold;
            color: #1b4d3e;
        }

        /* Footer */
        .footer {
            background: #2d6a4f;
            padding: 15px;
            text-align: center;
            color: white;
            font-size: 0.8rem;
        }

        @media (max-width: 768px) {
            .grammar-rules {
                grid-template-columns: 1fr;
            }
            
            .blank-sentence, .choose-question {
                flex-direction: column;
                text-align: center;
            }
            
            .student-info {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
<div class="worksheet-container">
    <!-- Header -->
    <div class="header">
        <div class="leo-badge">🗿🐒✨</div>
        <h1>
            <span>🌿</span> LEO'S GRAMMAR ADVENTURE <span>🗿</span>
        </h1>
        <p>Present Simple vs Present Continuous • Amazon Jungle Edition</p>
    </div>

    <!-- Student Info -->
    <div class="student-info">
        <div class="info-field">
            <label>📝 Name:</label>
            <input type="text" id="studentName" placeholder="Your name here...">
        </div>
        <div class="info-field">
            <label>📅 Date:</label>
            <input type="text" id="date" placeholder="Today's date">
        </div>
        <div class="info-field">
            <label>⭐ Class:</label>
            <input type="text" id="className" placeholder="Class">
        </div>
    </div>

    <!-- Grammar Rules -->
    <div class="grammar-rules">
        <div class="rule-card present-simple">
            <div class="rule-title present-simple">
                <span>📖</span> Present Simple
            </div>
            <div class="rule-formula">
                I/You/We/They + VERB<br>
                He/She/It + VERB + s/es
            </div>
            <div class="rule-examples">
                <p>📌 Leo <strong>works</strong> at a university.</p>
                <p>📌 Monkeys <strong>live</strong> in the jungle.</p>
                <p>📌 The crystal <strong>glows</strong> like the sun.</p>
            </div>
            <div class="time-words">
                <span class="time-badge">always</span>
                <span class="time-badge">usually</span>
                <span class="time-badge">often</span>
                <span class="time-badge">sometimes</span>
                <span class="time-badge">every day</span>
                <span class="time-badge">on Mondays</span>
            </div>
            <div style="margin-top: 10px; font-size: 0.8rem; color: #2d6a4f;">
                💡 Use for: FACTS • HABITS • ROUTINES
            </div>
        </div>

        <div class="rule-card present-continuous">
            <div class="rule-title present-continuous">
                <span>🎯</span> Present Continuous
            </div>
            <div class="rule-formula">
                am/is/are + VERB + ing
            </div>
            <div class="rule-examples">
                <p>📌 Leo <strong>is exploring</strong> the jungle now.</p>
                <p>📌 The monkey <strong>is pointing</strong> at the door.</p>
                <p>📌 They <strong>are searching</strong> for the temple today.</p>
            </div>
            <div class="time-words">
                <span class="time-badge">now</span>
                <span class="time-badge">right now</span>
                <span class="time-badge">at the moment</span>
                <span class="time-badge">today</span>
                <span class="time-badge">look!</span>
                <span class="time-badge">listen!</span>
            </div>
            <div style="margin-top: 10px; font-size: 0.8rem; color: #e76f51;">
                💡 Use for: ACTIONS HAPPENING NOW • TEMPORARY SITUATIONS
            </div>
        </div>
    </div>

    <!-- Leo's Story -->
    <div class="story-section">
        <div class="story-title">
            <span>📖</span> Leo's Amazon Adventure
            <span style="font-size: 0.8rem;">(Find the tenses!)</span>
        </div>
        <div class="story-text">
            <p>🌴 <strong>Leo</strong> <span class="highlight" data-tense="ps">works</span> <span class="tense-badge">Present Simple</span> at a university, but now he <span class="highlight" data-tense="pc">is exploring</span> <span class="tense-badge">Present Continuous</span> the Amazon jungle.</p>
            <p>🔍 Every morning, he <span class="highlight" data-tense="ps">wakes up</span> early and <span class="highlight" data-tense="ps">checks</span> his equipment. Right now, he <span class="highlight" data-tense="pc">is following</span> a mysterious sound.</p>
            <p>🗿 Leo's team usually <span class="highlight" data-tense="ps">stays</span> at the camp, but today they <span class="highlight" data-tense="pc">are searching</span> for an ancient temple.</p>
            <p>🐒 Suddenly, a friendly monkey <span class="highlight" data-tense="ps">appears</span>. The monkey <span class="highlight" data-tense="pc">is pointing</span> at a symbol on the door.</p>
            <p>✨ Leo <span class="highlight" data-tense="ps">touches</span> the symbol, and the door <span class="highlight" data-tense="ps">opens</span>. Inside, a golden crystal <span class="highlight" data-tense="pc">is glowing</span> like the sun.</p>
            <p>📸 While he <span class="highlight" data-tense="pc">is taking</span> photos, the monkey <span class="highlight" data-tense="pc">is sitting</span> beside him. Leo <span class="highlight" data-tense="ps">understands</span> that true treasure is adventure and friendship.</p>
        </div>
    </div>

    <!-- EXERCISE 1: Match the sentences -->
    <div class="exercise">
        <div class="exercise-title">
            <span class="exercise-number">1</span>
            <span>🎯 Match the sentences with the correct tense</span>
        </div>
        <div class="matching-grid" id="matchingGrid">
            <!-- Will be populated by JS -->
        </div>
    </div>

    <!-- EXERCISE 2: Fill in the blanks -->
    <div class="exercise">
        <div class="exercise-title">
            <span class="exercise-number">2</span>
            <span>✏️ Complete the sentences with the correct form</span>
        </div>
        <div id="blanksExercise"></div>
    </div>

    <!-- EXERCISE 3: Choose the correct option -->
    <div class="exercise">
        <div class="exercise-title">
            <span class="exercise-number">3</span>
            <span>🔄 Choose Present Simple or Present Continuous</span>
        </div>
        <div id="chooseExercise"></div>
    </div>

    <!-- EXERCISE 4: Describe the pictures -->
    <div class="exercise">
        <div class="exercise-title">
            <span class="exercise-number">4</span>
            <span>🖼️ What is happening? Describe the pictures!</span>
        </div>
        <div class="picture-grid" id="pictureGrid"></div>
    </div>

    <!-- Check Button -->
    <div class="check-section">
        <button class="check-btn" id="checkBtn">✅ CHECK MY ANSWERS! ✅</button>
    </div>

    <!-- Results -->
    <div class="results" id="results">
        <h3>🎉 YOUR GRAMMAR SCORE! 🎉</h3>
        <div class="results-score" id="scoreDisplay">0 / 0</div>
        <p id="feedbackMessage"></p>
        <p>🐒 "The true treasure is learning!" - Leo's monkey friend</p>
    </div>

    <!-- Footer -->
    <div class="footer">
        🌿 Keep exploring English! Every day is a new adventure! 🌿
    </div>
</div>

<script>
    // Exercise 1 Data
    const matchingData = [
        { text: "Leo works at a university.", tense: "Present Simple", emoji: "🏛️" },
        { text: "He is exploring the jungle now.", tense: "Present Continuous", emoji: "🌴" },
        { text: "Monkeys live in the Amazon.", tense: "Present Simple", emoji: "🐒" },
        { text: "The monkey is pointing at the door.", tense: "Present Continuous", emoji: "👉" },
        { text: "The crystal glows like the sun.", tense: "Present Simple", emoji: "✨" },
        { text: "Leo is taking photos right now.", tense: "Present Continuous", emoji: "📸" }
    ];

    // Exercise 2 Data
    const blanksData = [
        { sentence: "Leo __________ (work) at a university.", answer: "works", tense: "PS" },
        { sentence: "Right now, he __________ (follow) a mysterious sound.", answer: "is following", tense: "PC" },
        { sentence: "Every morning, he __________ (wake) up early.", answer: "wakes", tense: "PS" },
        { sentence: "Look! The monkey __________ (point) at the symbol!", answer: "is pointing", tense: "PC" },
        { sentence: "The crystal __________ (glow) like the sun.", answer: "glows", tense: "PS" },
        { sentence: "While he __________ (take) photos, the monkey sits beside him.", answer: "is taking", tense: "PC" }
    ];

    // Exercise 3 Data
    const chooseData = [
        { sentence: "Leo _______________ in the Amazon right now.", options: ["works", "is working"], correct: 1 },
        { sentence: "Monkeys _______________ in trees.", options: ["live", "are living"], correct: 0 },
        { sentence: "Listen! Someone _______________ a strange noise!", options: ["makes", "is making"], correct: 1 },
        { sentence: "The team usually _______________ at the camp.", options: ["stays", "is staying"], correct: 0 },
        { sentence: "Today, they _______________ for the ancient temple.", options: ["search", "are searching"], correct: 1 }
    ];

    // Exercise 4 Data
    const pictureData = [
        { emoji: "🗿🔍", action: "Leo / explore / jungle", correct: "is exploring", hint: "right now" },
        { emoji: "🐒👉🗿", action: "The monkey / point / at the door", correct: "is pointing", hint: "Look!" },
        { emoji: "🏛️📚", action: "Leo / work / at the university", correct: "works", hint: "every day" },
        { emoji: "✨📸", action: "He / take / photos of the crystal", correct: "is taking", hint: "now" },
        { emoji: "🌙😴", action: "Leo / sleep / early", correct: "sleeps", hint: "usually" }
    ];

    let userAnswers = {
        matching: [],
        blanks: [],
        choose: [],
        pictures: []
    };

    // Initialize Exercise 1
    function initMatching() {
        const container = document.getElementById('matchingGrid');
        container.innerHTML = matchingData.map((item, idx) => `
            <div class="matching-item" data-idx="${idx}">
                <div class="matching-emoji">${item.emoji}</div>
                <div class="matching-text">"${item.text}"</div>
                <div class="matching-answer">
                    <select data-ex1="${idx}" class="ex1-select">
                        <option value="">Select tense...</option>
                        <option value="Present Simple">📖 Present Simple</option>
                        <option value="Present Continuous">🎯 Present Continuous</option>
                    </select>
                </div>
            </div>
        `).join('');
        
        document.querySelectorAll('.ex1-select').forEach(select => {
            select.addEventListener('change', (e) => {
                const idx = parseInt(e.target.dataset.ex1);
                userAnswers.matching[idx] = e.target.value;
            });
        });
    }

    // Initialize Exercise 2
    function initBlanks() {
        const container = document.getElementById('blanksExercise');
        container.innerHTML = blanksData.map((item, idx) => `
            <div class="blank-sentence">
                <span>📝 ${idx+1}.</span>
                <span>${item.sentence.replace('__________', '________')}</span>
                <input type="text" class="blank-input" data-blank="${idx}" placeholder="your answer">
                <span class="tense-badge" style="background: ${item.tense === 'PS' ? '#2d6a4f' : '#e76f51'}">${item.tense === 'PS' ? 'Present Simple' : 'Present Continuous'}</span>
            </div>
        `).join('');
        
        document.querySelectorAll('.blank-input').forEach(input => {
            input.addEventListener('input', (e) => {
                const idx = parseInt(e.target.dataset.blank);
                userAnswers.blanks[idx] = e.target.value;
            });
        });
    }

    // Initialize Exercise 3
    function initChoose() {
        const container = document.getElementById('chooseExercise');
        container.innerHTML = chooseData.map((item, idx) => `
            <div class="choose-question">
                <span>🔍 ${idx+1}.</span>
                <span>${item.sentence}</span>
                <div class="choose-options">
                    <label class="choose-option">
                        <input type="radio" name="choose${idx}" value="0"> ${item.options[0]}
                    </label>
                    <label class="choose-option">
                        <input type="radio" name="choose${idx}" value="1"> ${item.options[1]}
                    </label>
                </div>
            </div>
        `).join('');
        
        chooseData.forEach((_, idx) => {
            document.querySelectorAll(`input[name="choose${idx}"]`).forEach(radio => {
                radio.addEventListener('change', (e) => {
                    userAnswers.choose[idx] = parseInt(e.target.value);
                });
            });
        });
    }

    // Initialize Exercise 4
    function initPictures() {
        const container = document.getElementById('pictureGrid');
        container.innerHTML = pictureData.map((item, idx) => `
            <div class="picture-card">
                <div class="picture-emoji">${item.emoji}</div>
                <div class="picture-sentence">${item.action}</div>
                <div class="picture-sentence" style="font-size: 0.7rem; color: #e76f51;">💡 ${item.hint}</div>
                <input type="text" class="picture-input" data-picture="${idx}" placeholder="Write the verb...">
            </div>
        `).join('');
        
        document.querySelectorAll('.picture-input').forEach(input => {
            input.addEventListener('input', (e) => {
                const idx = parseInt(e.target.dataset.picture);
                userAnswers.pictures[idx] = e.target.value;
            });
        });
    }

    // Check all answers
    function checkAnswers() {
        let totalScore = 0;
        let maxScore = 0;
        
        // Exercise 1: Matching
        matchingData.forEach((item, idx) => {
            maxScore++;
            if (userAnswers.matching[idx] === item.tense) {
                totalScore++;
                // Visual feedback
                const select = document.querySelector(`.ex1-select[data-ex1="${idx}"]`);
                if (select) select.style.border = '2px solid #6fbf4c';
            } else if (userAnswers.matching[idx]) {
                const select = document.querySelector(`.ex1-select[data-ex1="${idx}"]`);
                if (select) select.style.border = '2px solid #e67e22';
            }
        });
        
        // Exercise 2: Blanks
        blanksData.forEach((item, idx) => {
            maxScore++;
            const userAnswer = userAnswers.blanks[idx]?.toLowerCase().trim() || '';
            const correctAnswer = item.answer.toLowerCase();
            if (userAnswer === correctAnswer) {
                totalScore++;
                const input = document.querySelector(`.blank-input[data-blank="${idx}"]`);
                if (input) input.style.border = '2px solid #6fbf4c';
            } else if (userAnswer) {
                const input = document.querySelector(`.blank-input[data-blank="${idx}"]`);
                if (input) input.style.border = '2px solid #e67e22';
            }
        });
        
        // Exercise 3: Choose
        chooseData.forEach((item, idx) => {
            maxScore++;
            if (userAnswers.choose[idx] === item.correct) {
                totalScore++;
            }
        });
        
        // Exercise 4: Pictures (simple check)
        pictureData.forEach((item, idx) => {
            maxScore++;
            const userAnswer = userAnswers.pictures[idx]?.toLowerCase().trim() || '';
            if (userAnswer === item.correct || userAnswer === item.correct.replace('is ', '')) {
                totalScore++;
                const input = document.querySelector(`.picture-input[data-picture="${idx}"]`);
                if (input) input.style.border = '2px solid #6fbf4c';
            } else if (userAnswer) {
                const input = document.querySelector(`.picture-input[data-picture="${idx}"]`);
                if (input) input.style.border = '2px solid #e67e22';
            }
        });
        
        const percentage = Math.round((totalScore / maxScore) * 100);
        document.getElementById('scoreDisplay').innerHTML = `${totalScore} / ${maxScore} (${percentage}%)`;
        
        let feedback = '';
        if (percentage === 100) {
            feedback = '🏆 PERFECT! You are a Grammar Explorer! 🏆';
        } else if (percentage >= 80) {
            feedback = '🌟 Excellent! You really understand Present Simple and Present Continuous! 🌟';
        } else if (percentage >= 60) {
            feedback = '📚 Good job! Review the rules one more time to become a master! 📚';
        } else {
            feedback = '💪 Keep practicing! Look at the grammar rules again. You can do it! 💪';
        }
        
        document.getElementById('feedbackMessage').innerHTML = feedback;
        document.getElementById('results').classList.add('show');
        
        // Scroll to results
        document.getElementById('results').scrollIntoView({ behavior: 'smooth' });
    }

    // Add Enter key support for inputs
    function addEnterSupport() {
        document.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                checkAnswers();
            }
        });
    }

    // Initialize everything
    initMatching();
    initBlanks();
    initChoose();
    initPictures();
    addEnterSupport();
    
    document.getElementById('checkBtn').addEventListener('click', checkAnswers);
    
    // Add student name to header
    document.getElementById('studentName').addEventListener('change', (e) => {
        if (e.target.value) {
            const header = document.querySelector('.header h1');
            header.innerHTML = `🌿 ${e.target.value}'S GRAMMAR ADVENTURE 🗿`;
        }
    });
</script>
</body>
</html>
