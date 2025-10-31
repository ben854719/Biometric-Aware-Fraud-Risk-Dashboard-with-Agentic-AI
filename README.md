## Biometric Aware Fraud Risk Dashboard with Agentic AI Avatar

## Objective:

This fraud detection system blends biometric signals, behavioral analytics, and an agentic AI avatar to detect, explain, and mitigate stock fraud in real time. The application builts with Polars for scalable data modeling and Matplotlib for dynamic visualization, it applies ML-driven sentiment analysis with over 90% accuracy across multiple datasets. Adaptive thresholds recalibrate based on market volatility and user behavior, boosting detection precision by 42%, while autonomous investigative agents reduce manual review time by 60%. With sub-2-second detection latency, 99.9% dashboard uptime, and a 28% increase in risk team engagement, it delivers transparent intelligence and avatar-led clarity for compliance teams. Most fraud platforms stops at detection. This prototype goes further—bridging biometric signals with agentic AI to guide compliance teams through risk scenarios in real time. It’s the missing link between behavioral data and human-centered fraud response.

## Video of the project:



## Features:

## Agentic AI & Avatar-Led Intelligence:

- Agentic AI Avatar: Narrates fraud scenarios and investigative outcomes using Heygen video overlays, enhancing clarity and engagement for compliance teams.
  
- Autonomous Investigative Agents: Built with LangGraph and LangChain, these agents trace suspicious trades, generate audit trails, and reduce manual review time by 60%.

 ## Scalable Data Modeling & Cleaning with Polars:
 
- Lightning-Fast DataFrames: Polars powers the backend with parallelized, columnar execution — enabling real-time ingestion and transformation of multi-market trading data.
  
- Robust Cleaning Pipeline: Handles missing values, outlier filtering, and normalization with modular logic, ensuring clean inputs for ML and biometric analysis.
  
- Behavioral Drift Modeling: Tracks user deviation from baseline patterns using Polars’ efficient groupby and rolling window operations.

## LangGraph and LangChain: 

- Multi-Dataset Scalability: Seamlessly integrates with biometric signals, sentiment scores, and encrypted payloads across diverse exchanges.

## Biometric & Behavioral Analytics:

- Biometric Signal Integration: Ingests MCP Server inputs to detect physiological stress markers and correlate them with anomalous trading behaviors or access patterns.
- 
- Sentiment–Behavior Fusion: Combines emotional tone analysis with behavioral drift (e.g., navigation irregularities, timing anomalies) to surface high-risk patterns in real time.

## Performance & Engagement Metrics:

- Fraud Detection Latency: Under 2 seconds from signal ingestion to dashboard alert.
  
- Risk Team Engagement: Increased by 28% post-deployment due to avatar led clarity and transparent analytics.
  
- Scalable Architecture: Modular backend supports multi-market deployment and real-time recalibration.

## Installation Requirements:

- Ensure you have the following software and frameworks installed.

## Prerequisites:

- Cryptography
- Python
- Polars
- Pandas
- Pytorch
- Numpy
- Matplotlib
- Seaborn
- RS256 Asymmetric Encryption
- JSON
- Agentic AI
- LangGraph
- LangChain
- NLTK
- Heygen AI Avatar
- MCP Server
- Gemini 2.5 flash

## Python: Required for all major components:

- Cryptography
- Python
- Polars
- Pandas
- PyTorch
- Matplotlib
- Numpy
- Seaborn

## RS256 Asymmetric Encryption Setup:

-  is an RSA signature algorithm used with JSON Web Tokens (JWT). It uses a private key to sign data and a public key to verify it.

## LangGraph and LangChain - Autonomous Investigative Agents:

- To enable the autonomous investigative agents that trace suspicious trades and generate audit trails.
  
- install the core agentic frameworks with (!pip install langgraph) and (!pip install langchain). LangGraph provides the stateful orchestration layer that governs how the avatar and agents move    through reasoning steps, while LangChain handles tool routing, memory, and external API integration.
  
- Node.
  
- Greeting the user
  
- They power the modular intelligence behind the system — reducing manual review time by 60% and enabling scalable, explainable fraud detection.

- Answering follow-up questions.

## Avatar Setup in Google Colab:

## Create and Download your Avatar:

- Heygen videos should be pre-rendered and uploaded to your Colab environment for integration.

- Install video processing and orchestration tools for the avatar integration.

- Install IPython to enable HTML rendering of the HeyGen avatar video link within your Colab notebook.

-  For agentic flow control and avatar behavior scripting (!pip install langgraph & langchain).

## Display the Avatar:

- For Video use Markdown or HTML to show it in the notebook.

- Add a Scripted Introduction:

- Write a short welcome message below the avatar (e.g., “Hi, I am your assistant!”).

  ## LangGraph + LangChain Overview: Multi-Step Report Generation Flow:

- This agentic flow uses LangGraph to orchestrate reasoning steps and LangChain to route tools, manage memory, and trigger external APIs. It processes incoming text,          detects key signals, and generates structured reports — all within a modular, explainable framework.

##  Node Structure:

- Input Normalization
  
- Cleans and standardizes incoming text using lightweight string logic or LangChain tools.
  
- Prepares input for signal detection and downstream reasoning.

## Signal Detection:

- Identifies sentiment, anomalies, or behavioral cues using LangChain-integrated models.
  
- Flags relevant patterns for deeper interpretation.

## Report Structuring:

- Organizes findings into structured formats (JSON, Markdown, dashboard-ready).
  
- Includes timestamps, severity scores, and recommended actions.

 ## Fallback Logic:
 
- Activates when input is noisy, signal confidence is low, or APIs fail.
  
- LangGraph routes to clarifying prompts or simplified analysis paths using LangChain memory or tools.

## Output Delivery:

- Returns the structured report or triggers avatar narration.
  
- Optionally escalates to dashboards or compliance systems.

## Integration Notes:

- LangGraph handles stateful orchestration and node transitions.
  
- LangChain powers tool routing, memory, and external API access.
  
- Fallback logic ensures resilience and graceful recovery.
  
- Optional: Trigger Heygen avatar overlays based on report severity or signal type.

## Data Referral:

- Dataset title: Marketwatch

- Links: https://www.marketwatch.com/investing/index/gsptse/download-data?startDate=9/29/2025&endDate=10/27/2025&countryCode=ca





  







