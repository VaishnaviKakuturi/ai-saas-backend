# AI SaaS Platform Backend
Built for Amazon SDE-1 | Python, FastAPI, AWS, PostgreSQL

## Matches Amazon JD
- Built backend APIs from scratch using FastAPI + PostgreSQL to store LMS data
- Data processing pipeline for large datasets with MySQL/PostgreSQL
- Scalable, fault-tolerant, low-cost design deployed on AWS EC2
- Solutions to run predictions and manage workflows in distributed environment
- Agile methodology

## Run
pip install -r requirements.txt
uvicorn main:app --reload

## Endpoints
/lms/sync - Sync LMS data
/predict - Run predictions
/pipeline/stats - Data pipeline stats
