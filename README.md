# Hi, I'm George Gerges

I'm a **Computer Engineering student at the University of Toronto**, with internship experience at **Scentroid** and **Environment and Climate Change Canada**. I work across backend software, data pipelines, and applied machine learning.

**Seeking 2027 new-grad opportunities in software engineering, data engineering, and ML/AI.**

[LinkedIn](https://www.linkedin.com/in/george-gerges-uoft/) · [Education](#education) · [Technical skills](#technical-skills) · [Experience](#experience) · [Projects](#projects)

## Education

### University of Toronto — Toronto, Ontario

**Computer Engineering + Professional Experience Year (PEY)**  
Minor in Artificial Intelligence  
**Expected graduation: April 2027**

**Relevant coursework:**

- Software Design
- Data Structures and Algorithms
- Operating Systems
- Computer Architecture
- Machine Learning and Deep Learning
- Databases (SQL), Probability, and Artificial Intelligence

## Technical Skills

### Programming languages

![Python](https://img.shields.io/static/v1?label=&message=Python&color=3776AB&style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/static/v1?label=&message=C&color=A8B9CC&style=flat-square&logo=c&logoColor=white) ![C++](https://img.shields.io/static/v1?label=&message=C%2B%2B&color=00599C&style=flat-square&logo=cplusplus&logoColor=white) ![TypeScript](https://img.shields.io/static/v1?label=&message=TypeScript&color=3178C6&style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/static/v1?label=&message=JavaScript&color=B89B00&style=flat-square&logo=javascript&logoColor=white) ![SQL](https://img.shields.io/static/v1?label=&message=SQL&color=4169E1&style=flat-square&logo=postgresql&logoColor=white) ![HTML/CSS](https://img.shields.io/static/v1?label=&message=HTML%2FCSS&color=E34F26&style=flat-square&logo=html5&logoColor=white)

### Web frameworks

![React](https://img.shields.io/static/v1?label=&message=React&color=087EA4&style=flat-square&logo=react&logoColor=white) ![Flask](https://img.shields.io/static/v1?label=&message=Flask&color=333333&style=flat-square&logo=flask&logoColor=white) ![Redux Toolkit](https://img.shields.io/static/v1?label=&message=Redux+Toolkit&color=764ABC&style=flat-square&logo=redux&logoColor=white) ![Material UI](https://img.shields.io/static/v1?label=&message=Material+UI&color=007FFF&style=flat-square&logo=mui&logoColor=white)

### Databases and data engineering

![PostgreSQL](https://img.shields.io/static/v1?label=&message=PostgreSQL&color=4169E1&style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/static/v1?label=&message=Redis&color=DC382D&style=flat-square&logo=redis&logoColor=white) ![Apache Airflow](https://img.shields.io/static/v1?label=&message=Apache+Airflow&color=017CEE&style=flat-square&logo=apacheairflow&logoColor=white)

ETL/ELT pipelines · SQL query optimization · Schema migrations · Data quality checks

### Machine learning and scientific computing

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![LightGBM](https://img.shields.io/static/v1?label=&message=LightGBM&color=345B40&style=flat-square&logo=&logoColor=white) ![scikit-learn](https://img.shields.io/static/v1?label=&message=scikit-learn&color=F7931E&style=flat-square&logo=scikitlearn&logoColor=white) ![NumPy](https://img.shields.io/static/v1?label=&message=NumPy&color=013243&style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/static/v1?label=&message=Pandas&color=150458&style=flat-square&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/static/v1?label=&message=Matplotlib&color=11557C&style=flat-square&logo=&logoColor=white)

Anomaly detection · Transfer learning · Image classification · Model evaluation

### Development and deployment tools

![Git](https://img.shields.io/static/v1?label=&message=Git&color=F05032&style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/static/v1?label=&message=Linux&color=333333&style=flat-square&logo=linux&logoColor=white) ![Docker](https://img.shields.io/static/v1?label=&message=Docker&color=2496ED&style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/static/v1?label=&message=Kubernetes&color=326CE5&style=flat-square&logo=kubernetes&logoColor=white) ![Prometheus](https://img.shields.io/static/v1?label=&message=Prometheus&color=E6522C&style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/static/v1?label=&message=Grafana&color=F46800&style=flat-square&logo=grafana&logoColor=white)

CI/CD · Automated testing · Production debugging

## Experience

### Scentroid — Software Engineering Intern

*June 2026 – September 2026*

- Built and deployed an anomaly-detection feature for an environmental-monitoring platform using Python, Flask, React, and TypeScript.
- Implemented REST endpoints and operator feedback controls, backed by PostgreSQL configuration storage and Redis caching.
- Built Airflow workflows for baseline computation, backfills, retention, and event correlation; used Docker and Kubernetes for deployment and troubleshooting.

### Environment and Climate Change Canada — Data Engineering Intern

*May 2025 – June 2026*

- Built and automated ETL workflows to process and align environmental datasets using spatiotemporal aggregation.
- Optimized joins and vectorized transformations, reducing pipeline runtime by 30%.
- Engineered features and trained LightGBM models for pollutant prediction; contributed to two research papers in preparation.

### University of Toronto Aerospace Team — Data Processing Project Lead

*December 2024 – May 2025*

- Led a team developing deep-learning methods for FINCH satellite image enhancement, with preprocessing workflows and SSIM-based reconstruction evaluation.

## Projects

### [YouTube Analytics Pipeline — Data Engineering](https://github.com/gxorge13/youtube-analytics-pipeline)

A containerized pipeline that extracts public YouTube statistics and reconciles them into staging and core warehouse schemas.

- Orchestrates paginated API extraction and PostgreSQL loading with Apache Airflow.
- Preserves dated raw snapshots, transforms ISO 8601 durations, and classifies short-form videos.
- Runs locally with Docker Compose, Redis, and Celery; includes synthetic sample data, automated tests, and CI.

**Technologies:** Python · Apache Airflow · PostgreSQL · Docker · Redis · GitHub Actions  
[Explore the architecture and quick start →](https://github.com/gxorge13/youtube-analytics-pipeline#readme)

### [3D TicTacToe — Embedded Game](https://github.com/gxorge13/3D-TicTacToe)

A joint ECE243 project with **Selim Abdelwahab**, built for the Nios II / DE1-SoC environment.

- Combines 2D and 3D game modes with menus, board rendering, and win handling.
- Implements 320 × 240 VGA graphics with double buffering, PS/2 mouse input, interrupt handling, and audio output.
- Supports mouse-driven rotation of the 3D view and includes Python utilities for converting image and sound assets.

**Technologies:** C · Nios II · DE1-SoC · Python  
[Explore the code and hardware setup →](https://github.com/gxorge13/3D-TicTacToe#readme)

### [Hyperspectral Image Denoising — PyTorch Research Prototype](https://github.com/gxorge13/hyperspectral-image-denoising)

An experimental pipeline that reconstructs hyperspectral image patches from inputs with synthetic Gaussian noise.

- Uses a RIDNet-style residual network with enhancement attention modules and dilated convolutions.
- Normalizes spectral bands, samples image patches, and adds noise during data loading.
- Includes PSNR and per-band SSIM evaluation, training-loss plots, and reconstruction comparisons.

**Technologies:** Python · PyTorch · NumPy · TorchMetrics · scikit-image · Matplotlib  
[Explore the architecture and evaluation limits →](https://github.com/gxorge13/hyperspectral-image-denoising#readme)

### [Medical Image Classification — APS360 Team Project](https://github.com/gxorge13/medical-image-classification)

A university team project exploring classification across cancer, normal, and COVID image categories.

- Extracts VGG16 convolutional features for a PyTorch classifier with batch normalization and dropout.
- Includes class balancing, image preprocessing, train/validation/test splits, and an SVM baseline.
- Evaluates predictions with confusion matrices, precision, recall, F1, and accuracy.

**Technologies:** Python · PyTorch · torchvision · scikit-learn · NumPy  
[Explore the implementation and team credits →](https://github.com/gxorge13/medical-image-classification#readme)
