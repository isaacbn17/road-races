## Final Project Report

### Project Summary
My project is a website where you are able to query a database containing tens of thousands of results from runnercard.com
(a popular race timing and results website in Utah). I used Vercel and Supabase to create the application.

### Website Link
![Road Races Webiste](https://road-races-app-2w9v.vercel.app/)

### Video Demo
[Video Demonstration](Road%20Races%20Video%20Demo.mp4)

(If this doesn't work just check out the website.)

### Key Learnings
1.  **Data gathering** It took me just over 11 hours to scrape runnercard and clean the data, which is much longer than I intially expected. I learned that spot checking data for problems often decreases wasted time in when gathering and cleaning data.
2.  **Collaboration** I didn't know how to query Supabase from the website and spent an hour or two reading irrelevant documentation. Getting some help from Dr. Reynolds showed me that I was looking in the wrong place to find an answer to my question. I feel like I should be more open to getting help, asking questions, and collaborating with other people to solve problems.
3.  **Designing** Near the end of my project, I realized that it wasn't possible to query the database with aggregation (with the method I was using). This made me rethink the design of my application. I wish I had simply selected the content of both tables then created ways on the website to filter the tables. This would have made the end product closer to my goal.

### AI Integration
I integrated with ChatGPT in two different ways for this project.

After the user submits a question, ChatGPT translates this into executable SQL code used to query Supabase.

![Generated Query](Generated%20Query.png)

Once the query is run, the results are again sent to ChatGPT to be rewritten in a user-friendly, readable manner.

![Cleaned Response](Cleaned%20Response.png)

### AI in Building Project
I used AI to build the website, making only minor modifications myself. AI wasn't as helpful in scraping runnercard to get data (which may be part of the reason this process took so long). It was most helpful in this regard by teaching me the correct syntax for using beautiful soup.

### Reason For Interest
I run several 5Ks throughout the year that use runnercard for timing and results. I like comparing my times for the same race across years and am also curious to see if races are getting more competitive (i.e. more participants and faster times). The only way to currently do this is by opening several tabs and bouncing back and forth between them, so I wanted to make this easier by creating a unified database with all the results.

### ERD
![ERD Diagram for Road Races](ERD%20Diagram.png)
