<!DOCTYPE html>
<head>
 
    <title>USIU Advanced Web Development Evaluation Form</title>s
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f9f9f9;
        }
        form {
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: auto;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        label {
            font-weight: bold;
        }
        button {
            background-color: #007bff;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<form>
    <h2>USIU Advanced Web Development Evaluation Form</h2>

    <label for="fullName">Full Name:</label>
    <input type="text" id="fullName" name="fullName" placeholder="Enter your full name">

    <label for="studentId">Student ID:</label>
    <input type="text" id="studentId" name="studentId" placeholder="Enter your USIU Student ID">

    <label for="email">USIU Email Address:</label>
    <input type="email" id="email" name="email" placeholder="Enter your USIU email">

    <label for="github">GitHub Profile URL:</label>
    <input type="url" id="github" name="github" placeholder="Enter your GitHub profile URL">

    <label for="phone">Local Phone Number (WhatsApp-enabled):</label>
    <input type="tel" id="phone" name="phone" placeholder="+2547XX-XXX-XXX">

    <label for="problemSolving">1. Nairobi-Specific Problem Solving:</label>
    <textarea id="problemSolving" name="problemSolving" placeholder="Describe your API security and scalability solution for Nairobi matatu integration"></textarea>

    <label for="jsFramework">2. Select the best JavaScript framework for real-time Nairobi news aggregation:</label>
    <select id="jsFramework" name="jsFramework">
        <option value="React.js">React.js</option>
    </select>

    <label>3. Which Laravel optimization method is best for a Nairobi e-commerce startup?</label>
    <br>
    <input type="radio" id="databaseCaching" name="laravelOptimization" value="Database Caching">
    <label for="databaseCaching">Database Caching</label>
    <br>
    <input type="radio" id="queuesJobScheduling" name="laravelOptimization" value="Queues & Job Scheduling" checked>
    <label for="queuesJobScheduling">Queues & Job Scheduling</label>
    <br>
    <input type="radio" id="horizontalScaling" name="laravelOptimization" value="Horizontal Scaling">
    <label for="horizontalScaling">Horizontal Scaling</label>

    <label for="uploadProject">4. Upload a link to a past web project (PDF/Screenshot):</label>
    <input type="file" id="uploadProject" name="uploadProject">

    <label for="hostingProvider">5. Select a Kenyan hosting provider that supports M-Pesa payments:</label>
    <select id="hostingProvider" name="hostingProvider">
        <option value="Safaricom Cloud">Safaricom Cloud</option>
    </select>

    <label for="optimization">6. How would you optimize a web app for Nairobi users on 2G/3G networks?</label>
    <textarea id="optimization" name="optimization" placeholder="Explain using PWA, lazy loading, and CDN strategies"></textarea>

    <label for="techStartups">7. Name two Kenyan tech startups actively hiring full-stack developers:</label>
    <input type="text" id="techStartups" name="techStartups" placeholder="Example: Cellulant, Twiga Foods">

    <label for="freelancingPlatforms">8. Name two Kenyan freelancing platforms for web developers besides Upwork/Fiverr:</label>
    <input type="text" id="freelancingPlatforms" name="freelancingPlatforms" placeholder="Example: Kuhustle, WorkPay Africa">

    <input type="checkbox" id="certify" name="certify">
    <label for="certify">I certify that all responses are original and not AI-generated.</label>
    
    <br><br>
    <button type="submit">Submit Form</button>
</form>

</body>
</html>
