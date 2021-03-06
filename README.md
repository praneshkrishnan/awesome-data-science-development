# Awesome Data Science Development [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A continual adding list of libraries, frameworks, softwares and tools used in data science.


Table of Contents
-----------------

- [Data Science](#data-science)
  - [Machine Learning](#machine-learning) 
  - [ML Ops](#ml-ops)
  - [Visualization](#visualization)
  - [Package Management](#package-management)
  - [Domain Specific](#domain-specific)
  - [Data Science Environment](#data-science-environment)
  - [Data](#data)
  - [Other Notes](#data-science-other-notes)
- [Backend Development](#backend-development)
  - [Roadmap](#backend-development-roadmap) 
  - [Software Architecture](#software-architecture)
  - [REST](#rest) 
  - [Message Queue](#message-queue) 
  - [Version Control](#version-control-system) 
  - [Git-Based Hosting Platform](#git-based-code-hosting-platform)
  - [DevOps](#devops)
  - [Monitoring](#monitoring)
  - [Code Analysis](#code-analysis)
  - [Robotic Process Automation](#robotic-process-automation)
  - [Data Format](#data-format)
  - [Command Line](#command-line)
  - [Deployment](#deployment)
  - [Security](#security)
  - [Programming](#programming)
  - [Other Notes](#backend-other-notes)
- [Database](#database)
  - [Structured Query Language](#structured-query-language)
  - [ERD Diagram Tool](#erd-diagram-tool)
  - [Data Warehouse](#data-warehouse)
- [Cloud Infrastructure](#cloud-infrastructure)
  - [Cloud Provider](#cloud-provider)
  - [Other Notes](#cloud-other-notes)
- [Frontend Development](#frontend-development)
  - [Basic Stack](#basic-stack)
  - [Frontend Library](#frontend-library)
  - [Frontend Framework](#frontend-framework)
  - [IDE](#frontend-ide)
  - [Other Notes](#frontend-other-notes)
- [Web](#web)
  - [Web Hosting](#web-hosting)
- [IOTG](#iotg)
- [Business Intelligence](#business-intelligence)
- [Book](#e-book)
- [Course](#course)
- [Technical Blog](#technical-blog)
- [Technical Vlog](#technical-vlog)


## Data Science

### Machine Learning

**Machine Learning Library**

| Python Libraries |
| ---------------------  |
| [NumPy _Multi Dimensional Array Processing_ ](https://numpy.org/doc/stable/user/whatisnumpy.html)|
| [Scipy _Scientific Library for Python_](https://docs.scipy.org/doc/scipy/reference/) |
| Pandas _Data Manipulation & Analysis_ |
| [Scikit-Learn _Machine Learning Library_](https://scikit-learn.org/stable/) |
| Matplotlib _Data Visualization_ |
| Seaborn _Data Visualization with Matplotlib_ |
| Wandb _ML Visualization_ |
| [Prefect _Data Automation_ ](https://github.com/PrefectHQ/prefect) |
| [OpenCV](https://pypi.org/project/opencv-python/) |
| [Pillow](https://github.com/python-pillow/Pillow) |
| [FlashLight](https://github.com/flashlight/flashlight) |
| [statsmodel _Statistical modeling and econometrics in Python_](https://github.com/statsmodels/statsmodels) |
| [Numpy_ml _Machine Learning, in Numpy_](https://github.com/ddbourgin/numpy-ml)|
| [HuggingFace _NLP Oriented & Model HuB_](https://huggingface.co/) |
| [Augly _Data Augmentation_](https://github.com/facebookresearch/AugLy) |
| [Cleverhans _Benchmark ML System to Adversarial Examples_](https://github.com/cleverhans-lab/cleverhans) |
| [Foolbox _Run adversarial attacks against ML models_](https://github.com/bethgelab/foolbox) |

| Deep Learning Frameworks |
| ---------------------  |
| Pytorch |
| [Pytorch Video](https://github.com/facebookresearch/pytorchvideo) |
| Tensorflow 1 / 2 |
| [Flax](https://github.com/google/flax) |
| Keras |
| Eclipse DeepLearning4j |

| Neural Network Optimization |
| ---------------------  |
| TensorRT |

| Data, Model Probing | 
| ---------------------  |
| [What-If Tool](https://pair-code.github.io/what-if-tool/)

**Auto ML**

| Auto ML | 
| ---------------------  |
| [H20 AutoML](https://www.h2o.ai/products/h2o-automl/) |

### ML Ops

| Model Serving |
| ---------------------  |
| FAST API |
| Flask |
| Tensorflow Serving |
| [TorchServe (Experimental)](https://github.com/pytorch/serve)
| [KbServing](https://www.kubeflow.org/docs/components/serving/kfserving/)  |

| Other  |
| ---------------------  |
| [Tensorflow Extended (TFX) _Google-production-scale ML platform_](https://www.tensorflow.org/tfx) |


### Visualization

| Dashboard, Data Exploration & Visualization  |
| ---------------------  |
| [Apache Superset _Data Exploration and Visualization_](https://superset.apache.org/) |
| [Grafana](https://grafana.com/) |
| Prometheus _Monitoring System and Time Series Database_ |
| Looker _Data Analytics Platform_ |
| Google Data Studio |

### Package Management

**Python** 

| Python | Notes |
| ---------------------  | ---------------------  |
| Anaconda / Miniconda | [Common Commands](https://gist.github.com/codenamewei/a1ac37a4d94264bac9517a306116f0e3)
| Pip | [Virtualenv and pip](https://docs.python.org/3/tutorial/venv.html) |

| Java |
| ---------------------  |
| Apache Maven |
| Gradle |

### Domain Specific

| Text Detector  |
| ---------------------  |
| [EAST: An Efficient and Accurate Scene Text Detector CVPR 2017](https://paperswithcode.com/paper/east-an-efficient-and-accurate-scene-text) |
 
| OCR  |
| ---------------------  |
| [EasyOCR](https://github.com/JaidedAI/EasyOCR) |

| Speech Recognition  |
| ---------------------  |
| [Top 5 OSS Library](https://medium.com/analytics-vidhya/top-5-speech-recognition-open-source-projects-and-libraries-with-most-stars-on-github-d705408b834) |

| Time Series  |
| ---------------------  |
| [Forecasting: Principles and Practice](https://otexts.com/fpp3/) |

### Data Science Environment 

| Python  |
| ---------------------  |
| [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) |
| [Deepnote](https://deepnote.com/home) |
| Jupyter Notebook / [Jupyter Lab](https://github.com/mauhai/awesome-jupyterlab) / [Jupyter Lite](https://github.com/jtpio/jupyterlite)(Data Science)|
| [Polynote](https://github.com/polynote/polynote) |

### Data
| Data  |
| ---------------------  |
| [A Beginner Guide's To Data](https://jameskle.com/writes/beginner-guide-to-data)  |

| Dataset  |
| ---------------------  |
| [Awesome Data](https://github.com/datasets/awesome-data)  |
| [Awesome Public Dataset](https://github.com/awesomedata/awesome-public-datasets)  |

### Data Science Other Notes

| Other Notes |
| ---------------------  |
| [Jupyter Docker _Data Science Notebooks in Docker image_](https://github.com/jupyter/docker-stacks) |
| [Clean Code for Data Science Workflow](https://www.youtube.com/watch?v=Edn6XxWmtEs&list=PLO9pkowc_99ZhP2yuPU8WCfFNYEx2IkwR&index=3) |
| [Netron _Neural Network Visualization_](https://netron.app/)|


## Backend Development

### Backend Development Roadmap
| Overview |
| ---------------------  |
| https://roadmap.sh/backend |

### Software Architecture
| Software Architecture |
| ---------------------  |
| Service-Oriented (SOA) |
| [Microservices](https://github.com/ivan-bilan/The-Microservices-Pandect) |

| Other Notes |
| ---------------------  |
| [Domain Driven Hexagon](https://github.com/Sairyss/domain-driven-hexagon) |

### REST

| REST |
| ---------------------  |
| [Representational State Transfer (REST) Architectural Style](https://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api) |

| REST API Reference |
| ---------------------  |
| [Github](https://developer.github.com/v3/) |
| [Stripe](https://stripe.com/docs/api) |

| Others  |
| ---------------------  |
| Postman _API Testing Platform_ |
| Swagger _REST API Documentation_ |


### Message Queue

| Message Queue | Notes |
| ---------------------  | ---------------------  |
| RabbitMQ | |
| Kafka | - https://bit.ly/2JZH45D<br />- https://jaceklaskowski.gitbooks.io/apache-kafka/content/ |

### Version Control System

| Version Control System  |
| ---------------------  |
| Git |

### Git-Based Code Hosting Platform

| Git-based Code Hosting Platform  |
| ---------------------  |
| Github |
| Gitlab |
| Bitbucket |

### DevOps

| DevOps, CI/CD |
| ---------------------  |
| [Github Actions](https://lab.github.com/githubtraining/github-actions:-hello-world) |
| [CircleCI](https://circleci.com/)
| Jenkins |
| Ansible |
| Azure DevOps |

### Monitoring

| DevOps, CI/CD |
| ---------------------  |
| [Datadog](https://www.datadoghq.com/) |

### Code Analysis

| Code Analysis |
| ---------------------  |
| SonarQube |
| SonarCloud |
| SonarLint |

### Robotic Process Automation

| Robotic Process Automatic (RPA)|
| ---------------------  |
| UiPath |
| Automation Anywhere |

### Data Format 

| Data Format|
| ---------------------  |
| XML |
| [Javascript Object Notation (JSON)](https://www.tutorialspoint.com/json/index.htm) |
| [Base 64 Encoded String](https://bit.ly/2H2W0hT) |

### Command Line

| Command Line|
| ---------------------  |
| [Learn CLI The Hard Way](https://cglab.ca/~morin/teaching/1405/clcc/book/cli-crash-course.html)
| [The Art Of Command Line](https://github.com/jlevy/the-art-of-command-line) |


### Deployment

| Containerization  |
| ---------------------  |
| [Docker](https://docs.docker.com/get-started/) |

| Scaling  |
| ---------------------  |
| Docker Swarm |
| Kubernetes |

### Security

| General  |
| ---------------------  |
| Hashing |
| Encryption |
| [OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) |

| Authentication Token  |
| ---------------------  |
| [JSON Web Token (JWT)](https://jwt.io/introduction) |
| Simple Web Token (SWT) |
| Security Assertion Markup Language Token (SAML) |

### Programming

| Python | Resources|
| ---------------------  | ---------------------  |
| Unstructured | - https://github.com/vinta/awesome-python<br />- https://github.com/faif/python-patterns<br />- https://uwpce-pythoncert.github.io/SystemDevelopment/advanced_oo.html<br />- https://medium.com/@yong.cui01 |
| Clean Code | - https://github.com/zedr/clean-code-python<br />- https://www.amazon.com/Clean-Code-Python-maintainable-efficient/dp/1800560214 |

| Language | IDE |
| ---------------------  | ---------------------  |
| Java | - Intellij Community / Ultimate (Paid) |
| Python | - PyCharm<br />- Visual Studio Code|

| Algorithm Performance  |
| ---------------------  |
| Big O Notation |

| Others | Resources |
| ---------------------  | ---------------------  |
| Programming Practice Platform | - https://www.hackerrank.com/ |

### Backend Other Notes

| Other Notes |
| ---------------------  |
| [How to deal with breaking changes](https://nordicapis.com/what-are-breaking-changes-and-how-do-you-avoid-them/) |
| [Keep a change log](https://keepachangelog.com/en/1.0.0/) |
| [Semantic Versioning](https://semver.org/) |
| [Readme.so _Easy to structure readme_](https://readme.so/editor) |
## Database 

### Structured Query Language

| Structured Query Language |
| ---------------------  |
| [MySQL](https://www.mysqltutorial.org/) |
| [PostgreSQL](https://www.postgresql.org/) |

### ERD Diagram Tool

| ERD Diagram Tool |
| ---------------------  |
| Diagram.net |
| DbDesigner.net |
| SqlDbm |
| DbDiagram.io |
| Visual Paradigm |
| DbSchema |

### Data Warehouse 

| Data Warehouse |
| ---------------------  |
| Apache Hive  |

## Cloud Infrastructure

### Cloud Provider

| Cloud Provider |
| ---------------------  |
| AWS |
| Google Cloud Platform |
| Microsoft Azure |
| [Naver Cloud](https://www.ncloud.com/) |

### Cloud Other Notes
| Other Notes |
| ---------------------  |
|[Server Setup Guidelines](https://www.digitalocean.com/community/tutorials/5-common-server-setups-for-your-web-application)|

## Frontend Development

### Basic Stack

| Basic Stack| Functionality |
| ---------------------  | ---------------------  |
| HTML | Content Layer |
| CSS | Presentation Layer |
| JavaScript | Interactive Layer |

| Javascript |
| ---------------------  |
| [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read)<br />-[Github es6features](https://github.com/lukehoban/es6features#readme)|

| Typescript |
| ---------------------  |
| [TypeScript From Scratch](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html)|
| [Awesome Typescript 1](https://github.com/dzharii/awesome-typescript)|
| [Awesome Typescript 2](https://github.com/semlinker/awesome-typescript)|

### Frontend Library

| Name | Library |
| ---------------------  | ---------------------  |
| React | Javascript Library |

### Frontend Framework

| Name | Framework |
| ---------------------  | ---------------------  |
| Angular | Typescript framework |
| VueJS | Javascript framework |

### Frontend IDE

| Language | IDE |
| ---------------------  | ---------------------  |
| JavaScript/TypeScript | - Visual Studio Code<br /> - JetBrains WebStorm (Paid) |


### Frontend Other Notes
| Name | Functionality |
| ---------------------  | ---------------------  |
| [Electron](https://github.com/electron/electron)| Cross Platform Desktop Application |

## Web

### Web Hosting

| Web Hosting  |
| ---------------------  |
| [Github Pages _Hosting with Github_](https://pages.github.com/)
| [Streamlit _Web Hosting with Python, focusing on Data Science_](https://streamlit.io/)
## IOTG

| Edge Device | 
| ---------------------  | 
| Raspberry Pi | 
| Nvidia Jetson TX1, Nano, TX2, Xavier | 

| Application | Functionality |
| ---------------------  | ---------------------  |
| [Thingsboard](https://github.com/thingsboard/thingsboard) | IOT data collection, processing and visualization |


## Business Intelligence

| Business Intelligence Tool |
| ---------------------  |
| Excel |
| Google Data Studio |
| Power BI |
| Tableau |

## E-Book 

| Data Science  |
| ---------------------  |
| [Designing Data Intensive Applications](https://github.com/Yang-Yanxiang/Designing-Data-Intensive-Applications) |
| [Rules for Machine Learning, Best Practices for ML Engineering](https://drive.google.com/file/d/1JerUZwcMV6se8u-JkERVENgAVnTgdf5j/view?usp=sharing) |
| [Web Scraping With Python](https://drive.google.com/file/d/1Yg8fLmdLBWVot9lOZ6JrWeX4bqCvIKoM/view?usp=sharing) |
| [Practical AI on the Google Cloud Platform](https://drive.google.com/file/d/1_vXUazysEG9EzXadvGWV5PiByy_54C4v/view?usp=sharing) |
| [Full Stack Deep Learning](https://fall2019.fullstackdeeplearning.com/) |
| [Principle of Data Wrangling](https://drive.google.com/file/d/1esVWOzVoitAayixFhAGMOXNvz2fPSWHX/view?usp=sharing) |
| [Python for Data Analysis](https://drive.google.com/file/d/1fyQ5WpDhOeFBidpTo26lDAT8nc70EtvE/view?usp=sharing) |
| [Data Science Cheatsheet](https://drive.google.com/file/d/17HW8Y44PFIoVevIbs2B_uzuMJ7IIVjOg/view?usp=sharing) |
| [Data Cleaning](https://drive.google.com/file/d/1l8rXcxpFNrBg9mmIl7DGjN9KjRVkJ28U/view?usp=sharing) |
| [Approaching Almost Any Machine Learning Problem](https://github.com/abhi1thakur/approachingalmost) |

| Data Science (Domain Specific) |
| ---------------------  |
| [Python For Finance](https://drive.google.com/file/d/1hWBiUiZiYf9CeFnDe5_K11IHmwujutYX/view?usp=sharing) |

| Programming  |
| ---------------------  |
| [Java Notes for Professionals](https://www.computer-pdf.com/programming/java/830-tutorial-java-notes-for-professionals-book.html) |

| Database |
| ---------------------  |
| [MySQL_NotesForProfessional](https://drive.google.com/file/d/1DOvXKckGNXqety0-1WQybPzbhKenlHnJ/view?usp=sharing) |


## Course

**Computer Science**

| Computer Science  |
| ---------------------  |
| [Awesome CS Courses](https://github.com/prakhar1989/awesome-courses) |
| [The missing CS semester](https://missing.csail.mit.edu/) |
| [Deep Dive Into Modern Web Development](https://fullstackopen.com/en/) |
| [Stanford Python Numpy Tutorial](https://cs231n.github.io/python-numpy-tutorial/)|

**Cybersecurity**

| Cybersecurity |
| [Cloudfare](https://www.cloudflare.com/en-gb/learning/) |
| [How HTTP works](https://howhttps.works/) |

**Data Science**

| Deep Learning | 
| ---------------------  |
| [Practical Deep Learning for Coders](https://course.fast.ai/)

| Computer Vision | 
| ---------------------  |
| [Convolutional Neural Network for Visual Recognition CS231n](https://cs231n.github.io/)

| NLP |
| ---------------------  |
| [Hugging Face Course](https://huggingface.co/course) |
| [Stanford NLP CS224n](http://web.stanford.edu/class/cs224n) |
| [The NLP Pandect](https://github.com/ivan-bilan/The-NLP-Pandect) |

| Hands On Learning | 
| ---------------------  |
| [Qwiklabs _Hand On Cloud Training_](https://www.qwiklabs.com/) |


## Technical Blog

| Software Engineering |
| ---------------------  |
| [NormCore Tech](https://vicki.substack.com/) |
| [Linked In Engineering](https://engineering.linkedin.com/blog) |
| [Dropbox Tech](https://dropbox.tech/)
| [Uber Engineering Tech](https://eng.uber.com/category/articles/)
| [Github](https://github.blog/) |
| [Microsoft](https://www.microsoft.com/en-us/research/blog/) |
| [Gojek Tech](https://blog.gojek.io/) |
| [Netflix Tech](https://netflixtechblog.com/) |
| [fast.ai](https://www.fast.ai/) |


| Data Science |
| ---------------------  |
| [Google AI Blog](https://ai.googleblog.com/)
| [Facebook AI](https://ai.facebook.com/) |
| [Landing AI](https://landing.ai/developer/) |
| [DeepMind AI](https://deepmind.com/blog) |
| [Cleverhands _Security & Privacy in ML_](http://www.cleverhans.io/) |
| [DataRobot Wiki](https://www.datarobot.com/wiki/) |
| [SOCAR (In Korean)](https://tech.socarcorp.kr/posts/) |
| [ZZSZA (In Korean)](https://zzsza.github.io/)


## Technical Vlog

| Software Engineering |
| ---------------------  |
| [Joma Tech](https://www.youtube.com/channel/UCV0qA-eDDICsRR9rPcnG7tw) |
| [???????????? Sengineer (In Korean)](https://www.youtube.com/channel/UCW4ixpFivk6eJl8b5bFOLkg) |


