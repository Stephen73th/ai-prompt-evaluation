# T1-BASIC: GEMINI RESPONSE RECORD

## 1. Experiment Information

- **Experiment ID:** T1-B1
- **Task:** Knowledge and Explanation
- **AI Platform:** Google Gemini
- **Model/Version:** Gemini (record the exact model displayed in the interface, if available)
- **Prompt Type:** Basic
- **Test Date:** 24 November 2026

## 2. Prompt Used

Explain machine learning.

## 3. AI Response

**Machine learning (ML)** is a branch of artificial intelligence where computer systems learn patterns from data to make predictions or decisions—without being explicitly programmed with step-by-step rules for every scenario.

Instead of a developer writing "if the email contains 'free money' and comes from an unknown sender, mark as spam," a machine learning model is shown thousands of labelled examples of spam and legitimate emails and figures out the statistical patterns on its own.

### How Machine Learning Works

At a high level, building and using an ML model follows a repeatable loop:

1. **Collect and prepare data:** Gather relevant examples (rows of numbers, images, text, audio) and clean missing or noisy entries.
2. **Choose a model:** Pick a mathematical structure suited to the task—such as linear regression, decision trees, or neural networks.
3. **Train the model:** Feed training data into the model. It makes guesses, measures how far off those guesses are using a loss function, and adjusts internal parameters (weights) to reduce error.
4. **Evaluate on unseen data:** Test the trained model on a held-out dataset it has never seen to check whether it generalises rather than just memorising training examples (overfitting).
5. **Deploy and monitor:** Put the model into production and watch for data drift as real-world patterns change over time.

### Core Types of Machine Learning

| Paradigm | How It Learns | Common Algorithms | Everyday Examples |
|---|---|---|---|
| Supervised Learning | Trains on labelled input-output pairs to predict outcomes on new inputs. | Linear/logistic regression, random forests, gradient boosting, neural networks | House price estimation, spam detection, medical image triage |
| Unsupervised Learning | Finds hidden structure, groups, or compressed representations in unlabelled data. | K-means clustering, DBSCAN, PCA, autoencoders | Customer segmentation, anomaly detection, dimensionality reduction |
| Reinforcement Learning | An agent takes actions in an environment and learns a policy to maximise cumulative reward over time. | Q-learning, PPO, actor-critic methods | Game-playing AI, robotics control, dynamic resource scheduling |

In practice, hybrid approaches are common too—such as semi-supervised learning (mixing a small set of labelled data with lots of unlabelled data) and self-supervised learning (generating training signals directly from raw data, which powers modern large language and vision models).

### Machine Learning vs. Traditional Programming vs. Deep Learning

- **Traditional programming:** You supply rules and data to get answers. Works well when logic is clear and deterministic (e.g., calculating tax brackets or sorting a list).
- **Machine learning:** You supply data and answers (examples) to get rules (a trained model). Ideal when rules are too complex or shifting to write by hand.
- **Deep learning:** A specialised subset of ML using multi-layered neural networks that automatically learn hierarchical features from raw, unstructured data like pixels, waveforms, and text.

## 4. Initial Observations

Gemini produced a comprehensive and technically detailed explanation of machine learning despite receiving a simple prompt. The response covered the definition, machine learning process, major learning types, traditional programming, deep learning and practical applications. It also introduced advanced technical concepts and algorithms. The answer demonstrated strong subject knowledge, but some explanations were more technical than necessary for a general beginner. The response was well structured and included a comparison table to organise information.

## 5. Evaluation Scores

| Evaluation Criterion | Score (1–5) |
|---|---:|
| Accuracy | 5 |
| Relevance | 5 |
| Completeness | 5 |
| Clarity | 3 |
| Instruction Following | 5 |
| **Total Score** | **23/25** |

## 6. Errors or Limitations

The response introduced several technical terms, including loss function, weights, generalisation, overfitting, data drift, DBSCAN and PCA, without providing simple explanations for all of them. This could make the explanation difficult for someone without a background in programming or artificial intelligence. The response was also considerably more advanced than necessary for a general introductory explanation.

## 7. Assessment

Gemini achieved 23 out of 25 with the basic prompt. It demonstrated strong technical knowledge and provided a comprehensive explanation of machine learning. However, its use of advanced terminology reduced accessibility for beginners. The result suggests that a broad prompt can produce technically rich content, but does not necessarily ensure that the explanation is appropriate for the intended audience.