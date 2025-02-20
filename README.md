# HackerNews
A Playwright-based script that extracts the first 100 articles from Hacker News' "Newest" page and validates their sorting from newest to oldest.

Prerequisites: 
   -Node.js (v16 or later)
   -Playwright package

   
Installation:

1.Clone this repository:
git clone https://github.com/your-username/qawolf-assignment.git

2.Navigate to the project directory:
cd qawolf-assignment

3.Install required dependencies:
npm install

Install Playwright browsers:
npx playwright install

Usage: To run the script:
node index.js

The script will:

-Navigate to the Hacker News "Newest" page
-Extract the titles and timestamps of the first 100 articles
-Verify that the articles are sorted by timestamp from newest to oldest
-Output the validation result in the terminal








