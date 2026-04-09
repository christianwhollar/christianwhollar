# Christian Hollar

Software engineer working at the intersection of **AI, machine learning, software systems, and finance**. Currently a **Lead Software Engineer at DTCC QuantLabs**, where I build Python applications on **Beacon** and develop analytics for **risk and default fund modeling**. Previously worked at **Boeing** across avionics software and guidance, navigation, and control for military rotorcraft flight control systems.

## Experience

### DTCC | Lead Software Engineer, QuantLabs
- Build Python applications on Beacon to productionize quantitative models for client-facing risk and default fund analytics
- Engineer Snowflake data pipelines for daily member deficiency data and large-scale default fund contribution modeling
- Develop analytics and reporting workflows that compare required fund contributions against realized client deficiencies

### Boeing | Software Engineer, Avionics Software Design
- Developed Python-based automated end-to-end test procedures for the V-22 Flight Control System Redesign Program
- Wrote MATLAB and C-based test logic for unit verification and coverage analytics in RTOS-based lab environments

### Boeing | Guidance, Navigation, & Control Engineer
- Supported V-22, CH-47, MH-139, and AH-64 flight control and test efforts
- Worked across piloted simulation, live flight testing, telemetry support, and control law analysis

### NASA | Aerospace Engineering Intern
- Conducted wind tunnel and flight testing for the uPSP team
- Developed a Python-based visualization tool for aerodynamic parameter studies in collaboration with cross-functional engineering teams

### nCino | Software Engineering Intern
- Contributed to a cloud-based core banking platform
- Supported product features and analytics within an Agile, Salesforce-driven environment

### Morgan Stanley | Wealth Management Intern
- Supported portfolio reviews, client proposals, and investment strategy discussions
- Built exposure to wealth management workflows and high-net-worth client service

## Education

- **Duke University**  
  M.Eng. in Artificial Intelligence  
  M.Eng. in Financial Technology

- **Georgia Institute of Technology**  
  M.S. in Computer Science, Concentration in Computational Systems

- **Lafayette College**  
  B.S. in Mechanical Engineering, Minor in Mathematics

## What I Work On
- Agentic AI systems
- Retrieval-augmented generation (RAG)
- Reinforcement learning
- NLP and LLM applications
- Predictive modeling and analytics
- Financial and trading systems

## Selected Projects

### [DocuWhisper](https://github.com/christianwhollar/DocuWhisper)

Built a **RAG** document intelligence **agent** in **Python** for interacting with technical documents through natural language. Designed the system with **FastAPI** for the backend, **Streamlit** for the chat interface, **Hugging Face Transformers** and **PyTorch** for embedding generation, **FAISS** for vector retrieval, and **PostgreSQL** for document and embedding storage. Also used **Docker**, **Docker Compose**, and **GitHub Actions** to support containerized deployment and CI/CD, plus a **Rust** ingestion utility for automated document download and processing.

**Tech:** Python, FastAPI, Streamlit, Hugging Face Transformers, PyTorch, FAISS, PostgreSQL, Docker, Docker Compose, GitHub Actions, Rust, NLTK, NumPy, psycopg2, OpenAI-compatible API  
**Analytics / Math:** RAG pipeline design, document chunking, transformer embeddings, mean pooling, vector similarity search, top-*k* retrieval, latency benchmarking, token throughput analysis  
**Models:** LlamaFile-served local LLMs including Meta-Llama-3-8B-Instruct, TinyLlama-1.1B-Chat-v1.0, and Mixtral-8x7B-Instruct-v0

### [IBIT RL Agent](https://github.com/christianwhollar/ibit_rl_agent)

Built a reinforcement learning trading agent in **Python** to trade **IBIT options** using a **Deep Q-Network (DQN)** framework. Used **TensorFlow / Keras** to implement the neural agent, **Gymnasium** to build a custom trading environment, **pandas** and **NumPy** for market-state construction, and **Shiny / ShinyBroker** with **Matplotlib** and **Plotly** to create an interactive interface for live market visualization and model-driven trade recommendations.

**Tech:** Python, TensorFlow, Keras, Gymnasium, pandas, NumPy, Shiny, ShinyBroker, Matplotlib, Plotly, pytz  
**Analytics / Math:** reinforcement learning, Deep Q-Networks, Bellman-style Q-value updates, epsilon-greedy exploration, target networks, experience replay, portfolio value tracking, long/short straddle logic, volatility-based decision-making, support and resistance analysis, reward optimization  
**Models:** DQN trading agent with a 13-feature state space, two hidden dense layers, replay buffer memory, and target-model synchronization

### [AgentOrg](https://github.com/christianwhollar/AgentOrg)

Built an **agent orchestration framework** in **Python** for creating autonomous, tool-augmented LLM agents with a web-based chat interface. Used **Flask** to serve the frontend, **OpenAI API** integrations for **GPT-3.5 Turbo** and **GPT-4**, **threading** and **queue** for continuous agent execution, and custom tool modules for internet search and file-system actions. Designed the system around modular agent classes, prompt-driven tool use, recipient switching, and layered operational states to support more advanced **agentic** workflows.

**Tech:** Python, Flask, OpenAI API, GPT-3.5 Turbo, GPT-4, threading, queue, requests, BeautifulSoup, python-dotenv, tiktoken, HTML  
**Analytics / Math:** finite state machines, queue-based agent orchestration, tool routing, prompt engineering, token usage tracking, cost estimation, autonomous workflow design  
**Models:** Tool-augmented LLM agents powered by GPT-3.5 Turbo and GPT-4, with support for specialized organizational agent roles

### [NLP Business News Summarization](https://github.com/christianwhollar/NLP-Business-News-Summarization)

Built an **NLP** pipeline in **Python** for **business news summarization**, combining transformer-based **abstractive summarization** with a classical **extractive TextRank** baseline. Used **Hugging Face Transformers** and **Datasets** to fine-tune sequence-to-sequence summarization models, **NLTK** and **NetworkX** to build the extractive graph-based summarizer, and **Streamlit** to create an interactive app for generating article summaries.

**Tech:** Python, Hugging Face Transformers, Hugging Face Datasets, Evaluate, NLTK, NetworkX, scikit-learn, NumPy, pandas, Kaggle API, Streamlit  
**Analytics / Math:** sequence-to-sequence learning, transformer fine-tuning, tokenization, train/validation/test dataset construction, ROUGE evaluation, cosine similarity, graph-based ranking, PageRank, extractive vs. abstractive summarization  
**Models:** **Google T5 (`t5-small`)**, **DistilBART (`sshleifer/distilbart-cnn-12-6`)**, and a **TextRank** extractive summarizer

### [KryptonaFrontend](https://github.com/christianwhollar/KryptonaFrontend)

Built a full-stack **Web3 DAO platform** for governing, tokenizing, and transacting **AI models and agents**. Used **React** to create the frontend experience for wallet-connected proposal creation, voting, membership workflows, and child DAO exploration, while using **Solidity**, **Hardhat**, **OpenZeppelin**, and **Ethers.js** to build and interact with the underlying smart contract system for governance, treasury management, and tokenized AI artifacts.

**Tech:** JavaScript, React, React Router, Bootstrap, Ethers.js, Solidity, Hardhat, OpenZeppelin, Express, IPFS, Node.js  
**Analytics / Math:** DAO governance mechanics, token-weighted voting, treasury allocation logic, proposal systems, ERC-20 / ERC-721 tokenization, proportional treasury-share redemption, parent / child DAO architecture  
**Models / Agents:** Platform for managing and transacting tokenized AI artifacts, including data, architectures, models, and agents

### [BotnetClassification](https://github.com/christianwhollar/BotnetClassification)

Built a network security classification pipeline in **Python** to detect botnet traffic using both classical machine learning and deep learning. Used **scikit-learn** to develop and tune a **Random Forest** classifier with **GridSearchCV**, **TensorFlow / Keras** to build an **LSTM** sequence model for time-dependent traffic classification, and **pandas**, **NumPy**, **SciPy**, **seaborn**, and **matplotlib** for preprocessing, statistical feature analysis, and visualization.

**Tech:** Python, scikit-learn, TensorFlow, Keras, pandas, NumPy, SciPy, seaborn, matplotlib, requests  
**Analytics / Math:** ANOVA feature analysis, binary classification, feature standardization, sequence generation for time-series modeling, hyperparameter tuning, train/test splitting, accuracy, precision, recall, F1 score, ROC-AUC  
**Models:** Random Forest classifier, LSTM neural network for sequential botnet traffic classification

### [Book Recommendation System](https://github.com/christianwhollar/Book-Recommendation-System)

Built a book recommendation system in **Python** with a strong emphasis on the technical, analytical, and mathematical side of machine learning. Used **PyTorch** to develop a hybrid neural filtering model with learned embeddings and dense layers, **scikit-learn** to build a content-based recommender using vectorization and cosine similarity, **pandas** and **NumPy** for large-scale preprocessing and feature preparation, and **Streamlit** to create an interactive web app for personalized book recommendations.

**Tech:** Python, PyTorch, scikit-learn, Streamlit, pandas, NumPy, requests, tqdm  
**Analytics / Math:** recommender systems, embedding-based modeling, vectorization, cosine similarity, train/test splitting, MSE, accuracy, precision, recall  
**Models:** Hybrid neural filtering, content-based filtering

### [ASL Classification](https://github.com/christianwhollar/ASL-Classification)

Built a **computer vision** application in **Python** for **ASL image classification**, combining a deep learning pipeline with a classical machine learning baseline and a **Streamlit** interface for interactive prediction. The project uses **PyTorch** and **torchvision** for transfer learning, **scikit-learn** for the SVM baseline, **pandas** and **NumPy** for data handling, **scikit-image** and **Pillow** for image preprocessing, and the **Kaggle API** to ingest and merge the source datasets.

**Tech:** Python, PyTorch, torchvision, scikit-learn, scikit-image, Streamlit, pandas, NumPy, Pillow, joblib, Kaggle API, Jupyter Notebook  
**Analytics / Math:** transfer learning, image classification, data augmentation, image normalization, train/test splitting, GridSearchCV, Negative Log Likelihood loss, Adam optimization, learning-rate scheduling, accuracy, recall  
**Models:** MobileNetV2 transfer learning model with a custom classifier head for **39-class** ASL recognition, plus a Support Vector Machine baseline for comparative image classification

### [Trading Project](https://github.com/christianwhollar/Trading-Project)

Built an **algorithmic trading** and **financial forecasting** platform in **Python** focused on cryptocurrency markets and Solana price prediction. Used **PyTorch** to develop **LSTM** sequence models for forecasting multiple crypto assets, **scikit-learn** to build an **MLP** regression model that combined predicted prices and **TVL** features to estimate next-day Solana prices, and **Streamlit** to create an interactive dashboard for model analysis, trade simulation, and live prediction workflows.

**Tech:** Python, PyTorch, scikit-learn, Streamlit, pandas, NumPy, matplotlib, yfinance  
**Analytics / Math:** time-series forecasting, LSTM sequence modeling, multilayer perceptron regression, MinMax scaling, StandardScaler normalization, train/test splitting, MAE, MSE, RMSE, R², trade simulation, log returns, alpha, beta, TVL-driven market analysis  
**Models:** PyTorch LSTM models for Bitcoin, Ethereum, Solana, Raydium, Orca, and Uniswap forecasting, plus a scikit-learn MLPRegressor for next-day Solana price prediction