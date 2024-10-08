I'm looking for a software engineering management job, so I decided to use Claude AI optimize the application process.

I recorded the prompts in a GitHub repository so you can copy my process.

1: I started with my ideal applicant workflow:

* Identify companies I'm interested in
* Look for relevant openings in those companies
* Use my entire work history to create a custom resume and cover letter for each role
* Pull in the most relevant experiences using a given job description, and what Claude knows about each company
* Write a cover letter targeting specific recruiters.
* Message each recruiter individually in using my LinkedIn Premium account to let them know I applied.
2: Creating an optimized resume:

Since LinkedIn dropped their resume builder tool, I needed a replacement:

* First, I used Claude to convert my resume PDF to raw HTML.
* Then Claude optimized the HTML for style, ATS (application tracking system) compatibility, vertical density, etc.
* I committed the resume to a GitHub repo so I can see each change. This is important because LLMs have a habit or dropping or changing random details in large documents.
* I created a custom project in Claude and uploaded my GitHub project history, personal background, etc, so Claude knows all about my work experience.
* Claude performed a line-by-line optimization of each line. I had it make up details as a template, which I then replace with correct values. Using git made this easy.

3: Helpful starting points (requires LinkedIn Premium)

* Don't job look for job postings. Start by applying at the companies your interested in. Contact recruiters directly.
* Filter the search by recruiters actively hiring for a specific job titles: https://www.linkedin.com/search/results/people/?activelyHiringForJobTitles=%5B%221685%22%5D&keywords=engineers&origin=FACETED_SEARCH&sid=teV&spellCorrectionEnabled=false
* Search for hiring managements who are actively hiring: https://www.linkedin.com/search/results/people/?keywords=hiring&sid=6-r
* Prompts: https://github.com/DavidVeksler/David-Veksler-Resume/blob/master/claude-prompts.txt

* Resume: https://github.com/DavidVeksler/David-Veksler-Resume/blob/master/David%20Veksler%20-%20Resume%20V8.pdf

