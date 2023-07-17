## Job Application Tracker

A project that helps you keep track of your job applications by monitoring your incoming emails on Gmail. It utilizes a serverless AWS Lambda function that gets triggered when specific keywords are detected in your email. The function extracts the email header and body and sends it to the OpenAI API for summarization and extraction of specific information, including job title, company name, job posting link, and job application status.

The extracted data is then posted to a Google Spreadsheet, providing a centralized and organized way to track your job applications. By automating the process of monitoring and summarizing emails, the Job Application Tracker streamlines your job search efforts, saving you time and ensuring important details are easily accessible.

Key Features:
- Integration with Gmail API for monitoring incoming emails
- Utilization of OpenAI API for email summarization and data extraction
- AWS Lambda function for serverless and scalable processing
- Seamless posting of extracted data to a Google Spreadsheet for efficient job application tracking

Get started with the Job Application Tracker today and simplify your job search process while keeping your job applications organized and easily manageable.
