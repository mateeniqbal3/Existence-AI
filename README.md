# existence.com - AI Assistant

**Founder:** Muhammad Mateen Iqbal  
**Born:** 24 Feb 2007, Lahore (From Lakki Marwat, KPK, Pakistan)

existence.com is a deployable AI platform built in Python using:
- Chat + Math Solver + Code Executor
- Google/DuckDuckGo Search
- Image Generation & Style Transfer
- Signup/Login + User Logging
- Deployed on Railway (Docker)

## Features

- Ask questions & chat naturally
- Solve math and code problems
- Search the web (Google/DDG)
- Generate images with AI
- Style photos (blur, contour, detail)
- Secure user system
- Store user queries for UX improvements

## Tech Stack

- Python + Streamlit + LangChain
- SQLite / PostgreSQL
- Docker
- Railway (Deploy)

## Run Locally

```bash
git clone https://github.com/yourname/existence-com.git
cd existence-com
docker build -t existence-com .
docker run -p 8501:8501 existence-com
