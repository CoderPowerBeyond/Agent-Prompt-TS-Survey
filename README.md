# From Prompts to Agents: A Comprehensive Survey of LLM-Driven Time Series Analysis
<p align="center">
  <img src="\figure\pipeline.png" alt="The pipeline of LLM-Driven time series analysis from prompts to agents Architecture" width="1000"/>
</p>
<p align="center">The pipeline of LLM-Driven time series analysis from prompts to agents</p>

## About This Project
This repository is a continuously updated collection of papers and resources dedicated to **From Prompts to Agents: A Comprehensive Survey of LLM-Driven Time Series Analysis**.

For in-depth knowledge, check out our survey paper: "From Prompts to Agents: A Comprehensive Survey of LLM-Driven Time Series Analysis."

If you find this project helpful, we kindly ask you to consider citing our work:

```bibtex
@misc{zhang_2025_17491653,
  author       = {Zhang, Regina and GOH, SI QI and CHEN,XINGSHENG and LI,ZONGRU and WEN,HONGGANG and GUO,JIALE and YANG,MENGLIN and YIN,HONGZHI and YANG,QIANG and YIU,SIU-MING and LAM,KWOK-YAN},
  title        = {From Prompts to Agents: A Comprehensive Survey of
                   LLM-Driven Time Series Analysis
                  },
  month        = oct,
  year         = 2025,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17491653},
  url          = {https://doi.org/10.5281/zenodo.17491653},
}
```

## Contributions of This Survey
The motivation for this survey is consequently anchored in three critical research gaps:
- The absence of a unified examination of LLM-based agent architectures tailored for temporal data challenges
- The imperative to chronicle the evolution from static model-centric approaches to dynamic, workflow-orchestrating agentic systems
- The need for specialized evaluation frameworks that evaluate agentic competencies beyond conventional accuracy metrics.

Our survey directly addresses these gaps by providing a systematic exploration of how LLM agents synthesize perception, planning, tool manipulation, and reflective learning to revolutionize time series analysis. This integrated perspective responds to the escalating demand for autonomous systems capable of navigating the growing complexity and scale of temporal data across diverse application domains.

## Table of Contents
- [Passive Prompt Paradigm](#passive-prompt-paradigm)
  - [+Direct Prompting](#direct-prompting)
  - [+Instruction Tuning](#instruction-tuning)
- [Agentic Systems](#agentic-systems)
  - [Planning](#planning)
    - [+Direct Prompting](#direct-prompting-1)
    - [+Instruction Tuning](#instruction-tuning-1)
    - [Others](#others)
  - [Reasoning](#reasoning)
    - [+Direct Prompting](#direct-prompting-2)
    - [+Instruction Tuning](#instruction-tuning-2)
    - [Others](#others)
  - [Memory](#memory)
  - [Tool Use](#tool-use)
  - [Self-Refinement](#self-refinement)
## Paper
### Passive Prompt Paradigm
<p align="center">
  <img src="\figure\prompt component.png" alt="The components for prompts" width="1000"/>
</p>
<p align="center">The components for prompts</p>

#### +Direct Prompting

- Harnessing LLMs for Temporal Data-A Study on Explainable Financial Time Series Forecasting
- Pretrained LLMs as Real-Time Controllers for Robot Operated Serial Production Line
- $s^2$ IP-LLM: Semantic space informed prompt learning with LLM for time series forecasting
- Univariate to Multivariate: LLMs as Zero-Shot Predictors for Time-Series Forecasting
- Refining Time Series Anomaly Detectors using Large Language Models
- See it, think it, sorted: Large multimodal models are few-shot time series anomaly analyzers
- SST-LLM: time series forecasting based on large language models
- LLM-DSK: A Domain-Specific Semantic Knowledge-Guided Ocean Environment Prediction Method Based on Large Language Models
- Time series forecasting with llms: Understanding and enhancing model capabilities
- Large language models are zero-shot time series forecasters
- Large language models can deliver accurate and interpretable time series anomaly detection
- Aad-llm: Adaptive anomaly detection using large language models
- Large language models can be zero-shot anomaly detectors for time series?
- Can Slow-thinking LLMs Reason Over Time? Empirical Studies in Time Series Forecasting
- A Soft Sensor Method with Uncertainty-Awareness and Self-Explanation Based on Large Language Models Enhanced by Domain Knowledge Retrieval
- EXPRESS: An LLM-Generated Explainable Property Valuation System with Neighbor Imputation
- Humans vs Large Language Models: Judgmental Forecasting in an Era of Advanced AI
- Time-LLM: Time Series Forecasting by Reprogramming Large Language Models

#### +Instruction Tuning

- LLMForecaster: Improving Seasonal Event Forecasts with Unstructured Textual Data
- Proactive Detection and Calibration of Seasonal Advertisements with Multimodal Large Language Models
- FSTLLM: Spatio-Temporal LLM for Few Shot Time Series Forecasting
- An LLM-Based Method for Quality Information Extraction From Web Text for Crowed-Sensing Spatiotemporal Data
- InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
- LLM-TFP: Integrating large language models with spatio-temporal features for urban traffic flow prediction
- EF-LLM: Energy forecasting LLM with AI-assisted automation, enhanced sparse prediction, hallucination detection
- LLM-PS: Empowering Large Language Models for Time Series Forecasting with Temporal Patterns and Semantics
- TSRating: Rating Quality of Diverse Time Series Data by Meta-learning from LLM Judgment
- PaSTS: Parameter-affined Seasonal-Trend Synthesis for Multi-dimensional Long-Term Time Series Forecasting within LLM
- Research on cloud platform network traffic monitoring and anomaly detection system based on large language models
- Trend Decomposition Enhanced Large Language Model for Non-Stationary Network Traffic Prediction
- ADTime: Adaptive Multivariate Time Series Forecasting Using LLMs
- Position: Empowering time series reasoning with multimodal llms
- AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
- Genomics-Enhanced Cancer Risk Prediction for Personalized LLMs-Driven Healthcare Recommender Systems
- Back to the future: Towards explainable temporal reasoning with large language models
- Lightweight LLM-Based Anomaly Detection Framework for Securing IoTMD Enabled Diabetes Management Control Systems
- Foundation Forecasting in IoE Networks: When Generative AI Meets Programmable Edge Nodes
- From Values to Tokens: An LLM-Driven Framework for Context-aware Time Series Forecasting via Symbolic Discretization
- Time Series Forecasting as Reasoning: A Slow-Thinking Approach with Reinforced LLMs
- Action Prompt Assimilation in Large Language Models for Time Series Forecasting of Nuclear Power Industry Systems
- Llm-based misbehavior detection architecture for enhanced traffic safety in connected autonomous vehicles
- LLM4FTS: Enhancing Large Language Models for Financial Time Series Prediction
- AI on the Pulse: Real-Time Health Anomaly Detection with Wearable and Ambient Intelligence
- Time series forecasting based on optimized LLM for fault prediction in distribution power grid insulators
- A Three-Tier LLM Framework for Forecasting Student Engagement from Qualitative Longitudinal Data

### Agentic Systems

<p align="center">
  <img src="\figure\agent component.png" alt="The components for agents" width="1000"/>
</p>
<p align="center">The components for agents</p>

#### Planning

##### +Direct Prompting

- AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
- Position: Empowering time series reasoning with multimodal llms
- An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
- RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
- Agentic AI for autonomous anomaly management in complex systems
- Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
- Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations

##### +Instruction Tuning

- IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

##### Others

- FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
- TradingAgents: Multi-Agents LLM Financial Trading Framework
- Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making

#### Reasoning

##### +Direct Prompting

- Position: Empowering time series reasoning with multimodal llms
- Pretrained LLMs as Real-Time Controllers for Robot Operated Serial Production Line
- FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
- Visiongpt: Llm-assisted real-time anomaly detection for safe visual navigation
- Aad-llm: Adaptive anomaly detection using large language models
- An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
- RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
- Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
- Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
- Agentic AI for autonomous anomaly management in complex systems
- Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
- IIoT-enabled digital twin for legacy and smart factory machines with LLM integration
- Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations

##### +Instruction Tuning

- AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
- InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
- TRACE: Unlocking the Potential of LLMs in Time Series Forecasting for Distributed Energy Resources

##### Others

- TradingAgents: Multi-Agents LLM Financial Trading Framework
- Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making

#### Memory

- Aad-llm: Adaptive anomaly detection using large language models
- TradingAgents: Multi-Agents LLM Financial Trading Framework
- Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
- Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
- Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
- Agentic AI for autonomous anomaly management in complex systems
- Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
- IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

#### Tool Use

- AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
- Aad-llm: Adaptive anomaly detection using large language models
- TradingAgents: Multi-Agents LLM Financial Trading Framework
- Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
- An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
- RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
- Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
- Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
- Agentic AI for autonomous anomaly management in complex systems
- Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
- IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

#### Self-Refinement

- Position: Empowering time series reasoning with multimodal llms
- FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
- InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
- CALM: A Framework for Continuous, Adaptive, and LLM-Mediated Anomaly Detection in Time-Series Streams
- TRACE: Unlocking the Potential of LLMs in Time Series Forecasting for Distributed Energy Resources
- An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
- RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
- Aad-llm: Adaptive anomaly detection using large language models
- Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
- Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
- Aad-llm: Adaptive anomaly detection using large language models
- Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting




