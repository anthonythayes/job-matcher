# Job Matcher - Resume-Based Job Recommendation System

## Overview

A Python-based system that intelligently matches job opportunities to user profiles by parsing resumes, collecting job data from multiple APIs, and applying a multi-factor matching algorithm.

**Goal:** Match users with relevant jobs automatically with XX%+ accuracy.

## Features

- Resume parsing (extracts skills, experience, education)
- Multi-source job collection (Firecrawler, TheirStack API)
- Intelligent matching algorithm (skills, experience level, location)
- Interactive Streamlit dashboard for job recommendations

## Tech Stack

- **Backend:** Python, Firecrawler, Perplexity API
- **Frontend:** Streamlit
- **Data:** TheirStack API
- **Version Control:** Git & GitHub

## Project Status

🚧 In Development (multi week timeline)

## Getting Started

### Prerequisites

- Python 3.9+
- Git

### Installation

git clone https://github.com/anthonythayes/job-matcher.git
cd job-matcher
pip install -r requirements.txt

### Run the app

streamlit run app.py

## Project Timeline

- Data collection (500+ jobs)
- Resume parser & job parser
- Matching algorithm design
- Streamlit dashboard
- Testing, deployment, documentation

## What's Inside

- `/data/` - Raw and processed job data
- `/src/` - Core Python modules
- `/notebooks/` - Exploratory analysis
- `app.py` - Streamlit application

## Success Metrics

- ✅ XXX+ jobs collected
- ✅ XX%+ match accuracy (manual validation)
- ✅ Working Streamlit deployment
- ✅ Complete documentation

## Next Steps

1. Set up local environment
2. Implement job scraper
3. Build resume parser
4. Design matching algorithm

## Contact

Built by Anthony Hayes

## License

MIT License - see LICENSE file for details
