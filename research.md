---
layout: page
title: "Research"
permalink: "/research/"
description: "Publications by Mike Riess — papers on process mining, predictive process monitoring, business process simulation, and NLP for Nordic languages."
---

Peer-reviewed papers and preprints, most recent first. See also my [Google Scholar profile](https://scholar.google.com/citations?user=Mgz-wTYAAAAJ).

## [Telenor Nordics Customer Service Self-Help Corpus](https://journals.uio.no/NMI/article/view/13262)
<p class="pub-meta">Mike Riess &middot; Nordic Machine Intelligence &middot; 2026 &middot; <a href="https://arxiv.org/abs/2605.26891">arXiv</a></p>

A multilingual customer service self-help corpus of 1,122 manually validated documents in Finnish, Danish, Norwegian and Swedish, totalling over one million tokens.

<details markdown="1">
<summary>Abstract</summary>
This paper presents a multilingual customer service self-help corpus comprising 1,122 manually validated documents in Finnish, Danish, Norwegian, and Swedish, totaling over one million tokens. The documents have been sourced from the public self-help pages of four Nordic telecommunications operators and subsequently filtered for person-identifiable information and relevance through a combined LLM and human annotation pipeline. Domain-specific datasets for Nordic languages remain scarce, particularly in customer service — a domain of growing importance for retrieval-augmented generation, cross-lingual transfer learning, and emerging agent-based service architectures.
</details>

## [The BRAGE Benchmark: Evaluating Zero-shot Learning Capabilities of Large Language Models for Norwegian Customer Service Dialogues](https://aclanthology.org/2025.nodalida-1.57/)
<p class="pub-meta">Mike Riess, Tollef Emil Jørgensen &middot; NoDaLiDa/Baltic-HLT 2025, pp. 525&ndash;536 &middot; 2025</p>

A benchmark testing the ability of open-weight large language models to classify Norwegian customer service dialogues from a single instruction.

<details markdown="1">
<summary>Abstract</summary>
This study explores the capabilities of open-weight Large Language Models in a zero-shot learning setting, testing their ability to classify the content of customer service dialogues in Norwegian from a single instruction, named the BRAGE benchmark. The results show that (1) instruction-tuned models greatly exceed base models on the benchmark, (2) both English and multilingual instruction models outperform the tested Norwegian models of similar sizes, and (3) the difference between base and instruction models is less pronounced than in other generative tasks, suggesting that BRAGE is a challenging benchmark that requires precise and generalizable instruction-tuning.
</details>

## [SynBPS: a parametric simulation framework for the generation of event-log data](https://doi.org/10.1177/00375497241233326)
<p class="pub-meta">Mike Riess &middot; SIMULATION: Transactions of The Society for Modeling and Simulation International, 100, pp. 849&ndash;870 &middot; 2024 &middot; <a href="https://github.com/Mikeriess/SynBPS">Code</a></p>

A Python library for generating event-log data from theoretical business processes specified by well-known parametric distributions.

<details markdown="1">
<summary>Abstract</summary>
Business process simulation methods are typically calibrated to data from an existing process. To test hypotheses in the area of predictive process monitoring, it can however be more helpful to simulate event-log data from a theoretical process, in which all aspects can be manipulated — for example, when assessing the influence of process complexity or variability on the performance of a new prediction method, where the ability to include control variables and systematically change process characteristics is key. SynBPS is a Python library for the generation of event-log data from synthetic processes specified by well-known parametric distributions. Aspects such as process memory, trace distribution, duration distributions and case arrivals can be fully controlled by the user.
</details>

## [Remaining cycle time prediction: Temporal loss functions and prediction consistency](https://journals.uio.no/NMI/article/view/10141)
<p class="pub-meta">Mike Riess &middot; Nordic Machine Intelligence, vol. 3, pp. 12&ndash;26 &middot; 2023 &middot; <a href="https://github.com/Mikeriess/Temporal_loss">Code</a> &middot; <a href="/Temporal-loss-functions/">Blog post</a></p>

An evaluation of temporally weighted L1 loss functions for improving the earliness of remaining time predictions, and a new Temporal Consistency metric for model assessment.

<details markdown="1">
<summary>Abstract</summary>
The usefulness of remaining cycle time models for predictive and prescriptive process monitoring depends not only on the overall accuracy of the predictions, but also on their earliness: predictions should be as accurate as possible, as early as possible. To give this criterion more weight in model fitting, this paper evaluates three L1 loss functions with temporal decay, all of which increase the weight of residuals from the early stages of a process relative to residuals from later stages, but do so to different degrees. The loss functions are used in LSTM networks for training remaining time models of four different business processes based on publicly available event log datasets. Compared to models trained with an unweighted L1 loss, the suggested modifications yield small but significant improvements in earliness on out-of-sample data.
</details>

## [Essays on predictive and prescriptive process monitoring](https://www.nmbu.no/forskning/disputaser/9-june-mike-riess-hh)
<p class="pub-meta">Mike Riess &middot; PhD thesis 2022:21, School of Economics and Business, Norwegian University of Life Sciences (NMBU) &middot; 2023 &middot; ISBN 978-82-575-1896-7</p>

Doctoral thesis on proactive methods of decision support in business processes, defended 9 June 2023.

<details markdown="1">
<summary>About the thesis</summary>
The thesis addresses problems related to proactive methods of decision support in business processes: predictive process monitoring, which aims to warn about potential problems before they occur, and prescriptive process monitoring, which seeks to proactively remedy predicted issues before they materialise.
</details>

## [Automating model management: a survey on metaheuristics for concept-drift adaptation](https://doi.org/10.1007/s42488-022-00075-5)
<p class="pub-meta">Mike Riess &middot; Journal of Data, Information and Management &middot; 2022</p>

A survey of the literature on automated adaptation of machine learning models via metaheuristics in settings with concept drift.

<details markdown="1">
<summary>Abstract</summary>
This study provides an overview of the literature on automated adaptation of machine learning models via metaheuristics in settings with concept drift. Drift-adaptation of machine learning models presents a high-dimensional optimisation problem, and stochastic optimisation via metaheuristics has therefore been a popular choice for finding semi-optimal solutions at a low computational cost. Automated concept-drift adaptation has mainly been studied in data stream mining; however, as data drift is prevalent in many areas, analogous solutions have been proposed in other fields. The surveyed literature is qualitatively classified in terms of relevant aspects of concept drift, adaptation/automation approach and type of metaheuristic. Among the findings, the vast majority of studies use population-based metaheuristics, with eleven of the proposed algorithms derived from either Genetic Algorithms or Particle Swarm Optimisation.
</details>
