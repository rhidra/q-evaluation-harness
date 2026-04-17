# 🏆 Q Programming Language Leaderboard

Welcome to the official leaderboard for Q programming language model evaluation! This leaderboard tracks the performance of various language models on Q/kdb+ programming tasks.


## 🥇 Q-HumanEval Leaderboard

The following table shows model performance on the Q-HumanEval dataset, ranked by Pass@1 score:

| Rank | Model | Type | Size | Pass@1 | Pass@5 | Pass@10 |
|------|-------|------|------|--------|--------|---------|
| 🥇 | **qqWen**<br/>*Morgan Stanley* | 🔓 Open Source | **72B** | 45.10% | 59.24% | 62.63% |
| 🥈 | **Grok**<br/>*xAI* | 🧠 Reasoning (medium) | *Unknown* | 43.37% | 68.45% | 74.32% |
| 🥉 | **Claude 4 Sonnet**<br/>*Anthropic* | 🧠 Reasoning (medium) | *Unknown* | 37.70% | 53.47% | 59.13% |
| 4 | **Gemini 2.5 pro**<br/>*Google* | 🧠 Reasoning (medium) | *Unknown* | 27.75% | 51.41% | 59.68% |
| 5 | **GPT-5**<br/>*OpenAI* | 🧠 Reasoning (medium) | *Unknown* | 27.36% | 54.96% | 65.05% |
| 6 | **Claude Haiku 4.5**<br/>*Anthropic* | 🔒 Proprietary | *Unknown* | 25.82% | 38.12% | 43.57% |
| 7 | **o3**<br/>*OpenAI* | 🧠 Reasoning (medium) | *Unknown* | 18.42% | 40.93% | 52.15% |
| 8 | **GPT-4o**<br/>*OpenAI* | 🔒 Proprietary | *Unknown* | 14.42% | 24.49% | 29.44% |
| 9 | **Llama 3.3 70B**<br/>*Meta* | 🔓 Open Source | **70B** | 10.12% | 16.69% | 20.14% |
| 10 | **DeepSeek-R1-Distill-Qwen-32B**<br/>*DeepSeek* | 🧠 Reasoning (medium) | **32B** | 9.32% | 17.59% | 22.10% |
| 11 | **Qwen3 Coder 30B A3B**<br/>*Alibaba* | 🔓 Open Source | **30B** | 8.29% | 13.51% | 16.45% |
| 12 | **Gemma 3 12B**<br/>*Google* | 🔓 Open Source | **12B** | 4.15% | 6.22% | 6.66% |
| 13 | **Gemma 3 4B**<br/>*Google* | 🔓 Open Source | **4B** | 3.02% | 4.26% | 4.60% |

## 📊 Statistics

- **Total Models Evaluated:** 13
- **Model Types:**
  - 🧠 Reasoning: 6 models
  - 🔒 Proprietary: 2 models
  - 🔓 Open Source: 5 models

### 🏆 Best Scores
- **Highest Pass@1:** qqWen (45.10%)
- **Highest Pass@5:** Grok (68.45%)
- **Highest Pass@10:** Grok (74.32%)

## 🔬 Methodology

### Evaluation Metrics
- **Pass@k:** The percentage of problems solved when generating k samples per problem
- **Pass@1:** Single attempt success rate (most restrictive)
- **Pass@5:** Success rate with 5 attempts per problem
- **Pass@10:** Success rate with 10 attempts per problem

### Model Categories
- 🧠 **Reasoning Models:** Advanced models with enhanced reasoning capabilities
- 🔒 **Proprietary Models:** Closed-source commercial models
- 🔓 **Open Source Models:** Publicly available models

### Evaluation Process
All models are evaluated using the same standardized process:
1. 50 samples generated per model per problem
2. Consistent prompting and evaluation criteria
3. Automated scoring using the Q evaluation harness
4. Results verified for accuracy and reproducibility

### Statistical Rigor
For reliable Pass@k evaluation, Q-HumanEval requires at least 50 samples per problem to achieve statistically significant results with ±3 percentage point confidence intervals at 95% confidence level using Wilson confidence intervals.

---

**Last Updated:** April 16, 2026 | **Version:** 1.0.0 | **Total Submissions:** 13 models

*Want to submit your model? Check out our [submission guide](submission_guide.md) for details.*
