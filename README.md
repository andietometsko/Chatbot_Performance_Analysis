# Best of Bots: Identifying Top Performers with SQL & Data Pipelines

## Tech Stack
- Python: Data collection, transformation, automation
- SQL: Descriptive & diagnostic analysis
- AWS RDS PostgreSQL: Cloud database hosting
- GitHub Actions: Workflow via CI/CD
- Looker Studio: API dashboard visualizations
- Google Colab (Matplotlib & Seaborn): Kaggle visualizations
- Lucidchart: Data pipeline & ERD diagrams

## Project Objective
- Who am I helping? 
  Product and engineering teams are selecting the right AI chatbot for their app or platform.

- What problem am I solving?  
  Many teams struggle to compare chatbots across quality, speed, and user trust.

- How am I solving it?  
  I built automated data pipelines to collect chatbot data from APIs and web scraping, analyzed performance using SQL, and visualized insights to identify the best models for different business needs.

##  Job Description
I tailored this project to a job posting for an AI Chatbot Training role. This position requires training and evaluating AI chatbots, solving coding problems, and explaining technical decisions clearly.  
My project reflects these responsibilities by simulating real-world chatbot evaluation using SQL, automation, and data storytelling.  
[Job_Description.pdf](proposal/Job_Description.pdf)

## Data

### Sources
- API Source: iOS App Store API (via RapidAPI)  
- Web Scraped Source: Tech.co’s top chatbot models  
- Supplemental Dataset: Kaggle – [Local AI Chatbot Performance](https://www.kaggle.com/datasets/mussaddiqahmed/local-ai-chatbot-performance)

### Characteristics
- API data includes app names, ratings, categories, review counts, and URLs.  
- Web-scraped/Kaggle data includes chatbot model names, average accuracy, latency, performance time, memory usage, optimization technique, and query type.

## Notebooks & Scripts

- [`iOS_API_Extract_Load_Raw.ipynb`](notebooks/iOS_API_Extract_Load_Raw.ipynb) – Pulls and loads app data into PostgreSQL.
- [`tech_co_Web_Scrape_Extract_Load_Raw.ipynb`](notebooks/tech_co_Web) - Parses and loads scraped data.
- [`iOS_API_SQL_Analysis.ipynb`](notebooks/iOS_API_SQL_Analysis.ipynb) – Descriptive & diagnostic queries on App Store chatbot data.
- [`chatbot_diagnostic_SQL_Analysis.ipynb`](notebooks/Web_Scrape_SQL_Analysis.ipynb) – Full analysis of chatbot performance from scraped data.

## Future Improvements
- Deploy an interactive dashboard with dropdown filters so teams can explore chatbots by performance or use case.
- Add real-time tracking of new chatbot reviews using a streaming API and push updates into the PostgreSQL database.
