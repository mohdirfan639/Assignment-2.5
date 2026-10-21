Assignment 2.5 — HTML Foundations Mini-Project
1. Aim
To create a personal introduction webpage using basic HTML elements and semantic headings, organizing personal information, education, technical skills, hobbies, and contact information into a complete webpage.

2. Complete HTML Code (index.html)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Introduction</title>
</head>
<body>
    <header>
        <h1>Welcome to My Personal Webpage</h1>
        <p>Hello! I am a student learning web development.</p>
    </header>

    <main>
        <section>
            <h2>About Me</h2>
            <p>
                Hello! My name is Your Name. I am a student who enjoys
                learning new technologies and developing my programming
                skills. I am interested in creating websites and exploring
                the world of technology.
            </p>
        </section>

        <section>
            <h2>Education</h2>
            <ul>
                <li>
                    <strong>Current Course:</strong>
                    Your Course Name
                </li>
                <li>
                    <strong>School/College:</strong>
                    Your School or College Name
                </li>
                <li>
                    <strong>Area of Interest:</strong>
                    Computer Science and Web Development
                </li>
            </ul>
        </section>

        <section>
            <h2>Technical Skills</h2>
            <ul>
                <li>HTML - Basic knowledge</li>
                <li>CSS - Beginner</li>
                <li>JavaScript - Currently learning</li>
                <li>Problem-solving</li>
                <li>Computer fundamentals</li>
            </ul>
        </section>

        <section>
            <h2>Hobbies</h2>
            <ul>
                <li>Learning new technologies</li>
                <li>Reading books</li>
                <li>Listening to music</li>
                <li>Exploring the internet</li>
                <li>Practicing programming</li>
            </ul>
        </section>

        <section>
            <h2>Contact Information</h2>
            <p>
                <strong>Email:</strong>
                <a href="mailto:your.email@example.com">
                    your.email@example.com
                </a>
            </p>
            <p>
                <strong>GitHub:</strong>
                <a href="https://github.com/your-username">
                    My GitHub Profile
                </a>
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
Important: Replace Your Name, Your Course Name, the school/college name, email address, and GitHub username with your actual information before submitting.

3. Expected Webpage Output
Welcome to My Personal Webpage
Hello! I am a student learning web development.

About Me
Hello! My name is Your Name. I am a student who enjoys learning new technologies and developing my programming skills.

Education
Current Course: Your Course Name

School/College: Your School or College Name

Area of Interest: Computer Science and Web Development

Technical Skills
HTML - Basic knowledge

CSS - Beginner

JavaScript - Currently learning

Problem-solving

Computer fundamentals

Hobbies
Learning new technologies

Reading books

Listening to music

Exploring the internet

Practicing programming

Contact Information
Email: your.email@example.com

GitHub: My GitHub Profile

© 2026 Your Name. All rights reserved.

Illustrative preview of the webpage using the browser's default HTML styling. No CSS is used.
4. How to Run the HTML File
Open Visual Studio Code or another text editor.

Create a new file named index.html.

Paste the HTML code into the file.

Save the file.

Open index.html in your web browser.

Verify that all six sections appear in the correct order.

5. Commit the Project to GitHub
Follow these steps to create a GitHub repository and upload your work.

Step 1: Create a repository
Open GitHub .

Sign in to your account.

Click New repository.

Enter the repository name Assignment-2.5.

Select Public if you want your instructor to access the project without special permissions.

Create the repository.

Step 2: Upload your code using Git
Open a terminal in the folder containing index.html and run:


bash

git init
git add index.html
git commit -m "Complete Assignment 2.5 personal webpage"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/Assignment-2.5.git
git push -u origin main
Replace YOUR-USERNAME with your GitHub username. If Git is already initialized or the remote already exists, you may need to skip or adjust the corresponding commands.

Step 3: Submit your GitHub link
Your repository link will follow this format:

Assignment-2.5 Repository

https://github.com/YOUR-USERNAME/Assignment-2.5 

This is a template, not a verified repository link. After uploading, copy your actual repository URL for submission.

6. Conclusion
The personal introduction webpage has been created using HTML alone. It contains a page title, main heading, About Me, Education, Technical Skills, Hobbies, and Contact Information sections. Semantic HTML elements such as header, main, section, and footer organize the content, and the final code can be committed to a Git repository.