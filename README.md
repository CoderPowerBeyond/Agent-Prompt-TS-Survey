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
@misc{author,
      title={From Prompts to Agents: A Comprehensive Survey of LLM-Driven Time Series Analysis}, 
      author={..},
      year={2025},
      eprint={..},
      archivePrefix={arXiv},
      primaryClass={cs.},
      url={https://arxiv.org/..}, 
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

1. Harnessing LLMs for Temporal Data-A Study on Explainable Financial Time Series Forecasting
2. Pretrained LLMs as Real-Time Controllers for Robot Operated Serial Production Line
3. $s^2$ IP-LLM: Semantic space informed prompt learning with LLM for time series forecasting
4. Univariate to Multivariate: LLMs as Zero-Shot Predictors for Time-Series Forecasting
5. Refining Time Series Anomaly Detectors using Large Language Models
6. See it, think it, sorted: Large multimodal models are few-shot time series anomaly analyzers
7. SST-LLM: time series forecasting based on large language models
8. LLM-DSK: A Domain-Specific Semantic Knowledge-Guided Ocean Environment Prediction Method Based on Large Language Models
9. Time series forecasting with llms: Understanding and enhancing model capabilities
10. Large language models are zero-shot time series forecasters
11. Large language models can deliver accurate and interpretable time series anomaly detection
12. Aad-llm: Adaptive anomaly detection using large language models
13. Large language models can be zero-shot anomaly detectors for time series?

#### +Instruction Tuning

1. LLMForecaster: Improving Seasonal Event Forecasts with Unstructured Textual Data
2. Proactive Detection and Calibration of Seasonal Advertisements with Multimodal Large Language Models
3. FSTLLM: Spatio-Temporal LLM for Few Shot Time Series Forecasting
4. An LLM-Based Method for Quality Information Extraction From Web Text for Crowed-Sensing Spatiotemporal Data
5. InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
6. LLM-TFP: Integrating large language models with spatio-temporal features for urban traffic flow prediction
7. EF-LLM: Energy forecasting LLM with AI-assisted automation, enhanced sparse prediction, hallucination detection
8. LLM-PS: Empowering Large Language Models for Time Series Forecasting with Temporal Patterns and Semantics
9. TSRating: Rating Quality of Diverse Time Series Data by Meta-learning from LLM Judgment
10. PaSTS: Parameter-affined Seasonal-Trend Synthesis for Multi-dimensional Long-Term Time Series Forecasting within LLM
11. Research on cloud platform network traffic monitoring and anomaly detection system based on large language models
12. Trend Decomposition Enhanced Large Language Model for Non-Stationary Network Traffic Prediction
13. ADTime: Adaptive Multivariate Time Series Forecasting Using LLMs
14. Position: Empowering time series reasoning with multimodal llms
15. AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
16. Genomics-Enhanced Cancer Risk Prediction for Personalized LLMs-Driven Healthcare Recommender Systems
17. Back to the future: Towards explainable temporal reasoning with large language models
18. Lightweight LLM-Based Anomaly Detection Framework for Securing IoTMD Enabled Diabetes Management Control Systems
19. Foundation Forecasting in IoE Networks: When Generative AI Meets Programmable Edge Nodes
20. From Values to Tokens: An LLM-Driven Framework for Context-aware Time Series Forecasting via Symbolic Discretization
21. Time Series Forecasting as Reasoning: A Slow-Thinking Approach with Reinforced LLMs
22. Action Prompt Assimilation in Large Language Models for Time Series Forecasting of Nuclear Power Industry Systems
23. Llm-based misbehavior detection architecture for enhanced traffic safety in connected autonomous vehicles
24. LLM4FTS: Enhancing Large Language Models for Financial Time Series Prediction
25. AI on the Pulse: Real-Time Health Anomaly Detection with Wearable and Ambient Intelligence
26. Time series forecasting based on optimized LLM for fault prediction in distribution power grid insulators
27. A Three-Tier LLM Framework for Forecasting Student Engagement from Qualitative Longitudinal Data

### Agentic Systems

<p align="center">
  <img src="\figure\agent component.png" alt="The components for agents" width="1000"/>
</p>
<p align="center">The components for agents</p>

#### Planning

##### +Direct Prompting

1. AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
2. Position: Empowering time series reasoning with multimodal llms
3. An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
4. RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
5. Agentic AI for autonomous anomaly management in complex systems
6. Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
7. Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations

##### +Instruction Tuning

1. IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

##### Others

1. FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
2. TradingAgents: Multi-Agents LLM Financial Trading Framework
3. Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making

#### Reasoning

##### +Direct Prompting

1. Position: Empowering time series reasoning with multimodal llms
2. Pretrained LLMs as Real-Time Controllers for Robot Operated Serial Production Line
3. FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
4. Visiongpt: Llm-assisted real-time anomaly detection for safe visual navigation
5. Aad-llm: Adaptive anomaly detection using large language models
6. An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
7. RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
8. Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
9. Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
10. Agentic AI for autonomous anomaly management in complex systems
11. Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
12. IIoT-enabled digital twin for legacy and smart factory machines with LLM integration
13. Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations

##### +Instruction Tuning

1. AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
2. InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
3. TRACE: Unlocking the Potential of LLMs in Time Series Forecasting for Distributed Energy Resources

##### Others

1. TradingAgents: Multi-Agents LLM Financial Trading Framework
2. Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making

#### Memory

1. Aad-llm: Adaptive anomaly detection using large language models
2. TradingAgents: Multi-Agents LLM Financial Trading Framework
3. Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
4. Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
5. Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
6. Agentic AI for autonomous anomaly management in complex systems
7. Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
8. IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

#### Tool Use

1. AIS-LLM: A Unified Framework for Maritime Trajectory Prediction, Anomaly Detection, and Collision Risk Assessment with Explainable Forecasting
2. Aad-llm: Adaptive anomaly detection using large language models
3. TradingAgents: Multi-Agents LLM Financial Trading Framework
4. Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
5. An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
6. RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
7. Question Answering under Temporal Conflict: Evaluating and Organizing Evolving Knowledge with LLMs
8. Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models
9. Agentic AI for autonomous anomaly management in complex systems
10. Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting
11. IIoT-enabled digital twin for legacy and smart factory machines with LLM integration

#### Self-Refinement

1. Position: Empowering time series reasoning with multimodal llms
2. FinRL-DeepSeek: LLM-infused risk-sensitive reinforcement learning for trading agents
3. InsightBuild: LLM-Powered Causal Reasoning in Smart Building Systems
4. CALM: A Framework for Continuous, Adaptive, and LLM-Mediated Anomaly Detection in Time-Series Streams
5. TRACE: Unlocking the Potential of LLMs in Time Series Forecasting for Distributed Energy Resources
6. An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation
7. RTQA: Recursive Thinking for Complex Temporal Knowledge Graph Question Answering with Large Language Models
8. Aad-llm: Adaptive anomaly detection using large language models
9. Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making
10. Argos: Agentic time-series anomaly detection with autonomous rule generation via large language models




