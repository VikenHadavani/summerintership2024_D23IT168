# summerintership2024_D23IT168

<h2>4th Sem Summer Internship</h2>
# 🌟 AWS Summer Internship 2024 - Project Showcase 🌟

Welcome to my GitHub repository for the AWS Summer Internship 2024! This project showcases the work done during the internship, including practical insights and hands-on experience with Amazon Web Services (AWS). 

## 🚀 Introduction

### *25th May 2024*
- *AWS Bootcamp Live Session*: Basics of Amazon Web Services
- On 25th may, there was a live bootcamp which Amit Arora(Security Architect at AWS) is doing for an AWS Club where entry level engineers can participate and build there AWS skills from groundsup.. So it wasn't the start of internship but we learnt the basics of amazon web services , how it provides various functionalities to developers.
The internsip period is of 4 weeks with focus on Labs and Practical Insights to make familiar with aws.

# Start of Internship

## 1️⃣ week 1
### *28th May 2024*
- *Orientation Meeting*: Introduction to AWS and overview of the internship tasks
- At the start of meeting I tackled questions regarding aws to know its base. Then the 1st week agenda regarding the tasks to be done was discussed. The tasks including from the start of creating an account to generating a portfolio hosted on a aws instance.

<img src="https://media.licdn.com/dms/image/D5612AQEpoU1DdzX4yw/article-cover_image-shrink_600_2000/0/1654203654746?e=2147483647&v=beta&t=1WAkA9Pdvki3nSBEkXHCF7LkPrQvbmaeJu39czxaqpg" alt="AWS Bootcamp" width="300"/>


### *Here is the Outine of Week-1:*
1. Create an AWS Free Tier account
2. Log on to the AWS Console
3. AWS Billing and Cost Management
4. Set up a zero-dollar limit budget
5. Launch an EC2 Instance
6. Connect to the EC2 Instance
7. Install Apache Web Server on the Linux Instance
8. Deploy a personal page.html on Apache
9. Open Security Group for Apache to accept connections on port 80
10. Access the page.html using the public IP address of the EC2 instance

## 📝 Day-by-Day Progress

### Day 1: Creating AWS Free Tier Account
- Created an AWS Free Tier account as part of Task 1.
- Logged on to the AWS Console (Task 2).
- Explored AWS Billing and Cost Management (Task 3).
- Set up a zero-dollar limit budget (Task 4).
- Launched an EC2 instance from the free tier options (Task 5).


### Day 2: creating instance with apache server to deploy web page
- Connected to the EC2 Instance (Task 6):
After launching the EC2 instance, I connected to it using SSH. This allowed me to access the virtual server, which is essentially a remote computer running on AWS infrastructure. The connection was established securely using the provided key pair, ensuring that my data remains protected.

-Commands : 
shell- to write command in it
pwd-current web directory
whoami-this will which user is as logged in this account

- Installed an Apache Web Server on the Linux Instance (Task 7):
Once connected, I installed Apache, a widely-used open-source web server software. Apache is crucial for serving web pages to users. The installation involved updating the package repositories and using package management commands to install Apache on the Linux-based EC2 instance.

-Commands : 
sudo su-to elevate your credentials to root
yum install -y httpd- to install apache web server(Linux server)
cd /var/www/html- to create a HTML file into directory

- Deployed a Personal page.html on Apache (Task 8):
With Apache running, I deployed a simple HTML page (Personalpage.html). This involved placing the HTML file in Apache’s root directory and configuring the server to serve this page. Deploying the HTML page allowed me to create a personal webpage accessible over the internet via the EC2 instance's public IP address.

### Day 3: Building the Portfolio

➠ Setting Up the Project Structure:
-Created a project directory on the EC2 instance for the portfolio website. This included folders for HTML, CSS, JavaScript, and assets like images and fonts.
-Initialized the project with a basic index.html file to serve as the homepage.

➠ Creating the HTML Structure:
-Developed the initial structure of the portfolio using HTML5. This involved creating sections for the header, about me, projects, and contact information.
-Ensured the HTML code was semantic and well-organized to improve readability and SEO.

➠ Integrating Bootstrap:
-Incorporated Bootstrap, a popular CSS framework, to make the portfolio responsive and visually appealing.
Used Bootstrap components like navigation bars, cards, and buttons to enhance the design and functionality of the website.

### Day 4: Enhancing with JavaScript, SASS, and CSS

➠Adding Interactivity with JavaScript:
Implemented JavaScript to add interactive features to the portfolio, such as form validation for the contact section and dynamic content loading for the projects section.
Utilized event listeners and DOM manipulation to create a more engaging user experience.

➠ Styling with SASS and CSS:
-Used SASS (Syntactically Awesome Style Sheets) to write more maintainable and modular CSS code. SASS variables, nesting, and mixins helped streamline the styling process.
-Compiled SASS files into CSS and applied custom styles to enhance the visual aesthetics of the portfolio. This included customizing Bootstrap themes and adding unique design elements.

➠ Finalizing the Deployment:
-Ensured all the files were correctly linked and the website was functioning as intended.
-Tested the portfolio on different browsers and devices to ensure compatibility and responsiveness.

➠Technologies Explored
-HTML5: Structured the content and elements of the portfolio.
-Bootstrap: Provided a responsive and modern design framework.
-JavaScript: Added interactivity and dynamic functionality to the website.
-SASS: Enhanced the CSS with advanced features for better maintainability and efficiency.
-CSS: Styled the website to improve visual appeal and user experience.

### Day 5: Configuration and final Touchup
-Configured the Security Group for the Apache server on the EC2 instance to accept incoming connections on port 80. This involved adding an inbound rule in the Security Group settings to allow HTTP traffic, ensuring that the web server is accessible from the internet.(Task 9)

-Verified the configuration by accessing the personal webpage hosted on the EC2 instance. Used the public IP address of the instance in a web browser to confirm that the Apache server is serving the webpage correctly. This demonstrated successful setup and configuration of the web server.(Task 10)

-Here is the finalised link : http://52.63.0.141/personalpage.html

## Notes:
We were given this repo which contains basic documentation of AWS services which can be helpful to everybody --
https://github.com/hamidgholami/accp-cheatsheet

