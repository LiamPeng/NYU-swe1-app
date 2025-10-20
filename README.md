# SWE1 - APP

[![Build Status](https://app.travis-ci.com/LiamPeng/NYU-swe1-app.svg?token=BEzMtBAig19uP8o4hQjp&branch=main)](https://app.travis-ci.com/LiamPeng/NYU-swe1-app)
[![Coverage Status](https://coveralls.io/repos/github/LiamPeng/NYU-swe1-app/badge.svg)](https://coveralls.io/github/LiamPeng/NYU-swe1-app)

This is the personal assignment for **NYU Fall 2025 – CS-GY 6063-1-INET**:  
**Django “Hello World” Developed and Deployed**

![Index](docs/app_preview.png)

This repository contains a classic **Polls** application with a clean UI (Bootstrap), end-to-end CRUD, and deployment scripts for **AWS Elastic Beanstalk**.

---

## Project Structure

```bash
.
├── polls/
│   ├── admin.py
│   ├── models.py
│   ├── urls.py
│   ├── views.py
│   └── templates/polls/
│       ├── index.html
│       ├── detail.html
│       └── results.html
├── mysite/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── static/
├── requirements.txt
├── Procfile                # for EB / Gunicorn
└── README.md
```
