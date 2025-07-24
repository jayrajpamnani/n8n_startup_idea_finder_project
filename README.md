# Startup Idea Finder
Developed an automated workflow in n8n that scrapes specific subreddits to identify user-reported issues related to a particular product or service. These problems are then processed by the Gemini Flash 8B model, which generates corresponding solutions. The final output — a structured list of problems and their respective AI-generated solutions is automatically logged into a Google Sheet for easy reference and analysis.
It could be tried with multiple subreddits (I tried with 3).

Here's the Workflow diagram on n8n:

![n8n_workflow.png](https://github.com/jayrajpamnani/n8n_startup_idea_finder_project/blob/2f467b6d08611c3bd52335a31a190258cec6f65d/n8n_workflow.png)

![google_sheets_example1] (https://github.com/jayrajpamnani/n8n_startup_idea_finder_project/blob/00dd60ec427d68344986651612a5b9647ed28c0f/google_sheets_example1.png)

![google_sheets_example2] (https://github.com/jayrajpamnani/n8n_startup_idea_finder_project/blob/cdb30099383c561db9abceab0a753386701734a9/google_sheets_example2.png)

If you want to clone this diagram, go to this link: https://n8n.io/workflows/6094-generate-startup-ideas-from-reddit-posts-using-gemini-ai-and-google-sheets/
