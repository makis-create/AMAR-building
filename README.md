🏢 Amar Building - Commercial Property Manager

A modern, serverless, single-page web application designed specifically for managing commercial property finances, tenants, staff, and maintenance.

🌟 Features

Tenant Management: Track unit numbers, tenant businesses, base rent, water, and electric utilities. Toggle payment statuses between "Paid" and "Pending."

Staff Salaries: Log monthly payments for property staff, such as security guards and cleaners.

Maintenance Log: Record repair descriptions, dates, and associated costs.

Automated Dashboard: Generates a real-time Monthly Board Report calculating Total Income, Total Expenses, and Net Operating Income.

Month-to-Month Memory: Toggle between different months to view historical data using built-in persistent cloud storage (via Firebase).

Export to CSV: Download the monthly report directly into a spreadsheet format for Excel or Google Sheets.

Print/PDF Ready: Optimized layout for generating hard copies or PDFs for board meetings.

🚀 How to Deploy to GitHub Pages

GitHub Pages allows you to host this application completely for free directly from your repository. Follow these steps:

Step 1: Create the Repository

Log into your GitHub account.

Create a new repository and name it (e.g., amar-building-manager).

Leave it Public or Private (Note: GitHub Pages is free for Public repos on the basic plan).

Step 2: Add the Project Files

In your new repository, click "Add file" > "Create new file".

Name the file index.html.

Copy the entire HTML code for the Property Manager app and paste it into this index.html file.

Click "Commit changes".

Create another file named README.md, paste the contents of this document into it, and commit it as well.

Step 3: Enable GitHub Pages

In your repository, click on the Settings tab (the gear icon near the top).

On the left-hand sidebar, click on Pages.

Under the "Build and deployment" section, look for the Source dropdown and ensure it is set to Deploy from a branch.

Under the Branch section, click the dropdown that says None, change it to main (or master), and click Save.

Wait about 1-2 minutes. GitHub will process your code.

Refresh the page, and you will see a message at the top saying: "Your site is live at https://[your-username].github.io/[repo-name]/".

Click that link, and your app is now live on the web!

🛠️ Technology Stack

Frontend: HTML5, JavaScript (ES6 Modules)

Styling: Tailwind CSS (via CDN)

Icons: SVG Inline

Database/Storage: Firebase Firestore (Anonymous Auth & Realtime snapshot syncing)
