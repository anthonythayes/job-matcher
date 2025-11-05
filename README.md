# Job Matcher - Resume-Based Job Recommendation System

## Overview

A Python-based system that intelligently matches job opportunities to user profiles by parsing resumes, collecting job data from multiple APIs, and applying a multi-factor matching algorithm.

**Goal:** Match users with relevant jobs automatically with 80%+ accuracy.

## Features

- Resume parsing (extracts skills, experience, education)
- Multi-source job collection (GitHub Jobs API, TheirStack API)
- Intelligent matching algorithm (skills, experience level, location)
- Interactive Streamlit dashboard for job recommendations

## Tech Stack

- **Backend:** Python, Firecrawler, Perplexity API
- **Frontend:** Streamlit
- **Data:** GitHub Jobs API, TheirStack API
- **Version Control:** Git & GitHub

## Project Status

🚧 In Development (multi week timeline)

## Getting Started

### Prerequisites

- Python 3.8+
- Git

### Installation

git clone <https://github.com/anthonythayes/job-matcher.git>
cd job-matcher
pip install -r requirements.txt

### Run the app

streamlit run app.py

## Project Timeline

- Weeks 1-2: Data collection (500+ jobs)
- Weeks 2-3: Resume parser & job parser
- Weeks 3-4: Matching algorithm design
- Weeks 4-5: Streamlit dashboard
- Weeks 5-7: Testing, deployment, documentation

## What's Inside

- `/data/` - Raw and processed job data
- `/src/` - Core Python modules
- `/notebooks/` - Exploratory analysis
- `app.py` - Streamlit application

## Success Metrics

- ✅ 500+ jobs collected
- ✅ 80%+ match accuracy (manual validation)
- ✅ Working Streamlit deployment
- ✅ Complete documentation

## Next Steps

1. Set up local environment
2. Implement job scraper
3. Build resume parser
4. Design matching algorithm

## Contact

Built by Anthony Hayes - First GitHub project submission

## License

MIT License - see LICENSE file for details
