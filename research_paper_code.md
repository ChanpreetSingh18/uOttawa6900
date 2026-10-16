# Research paper code

Papers in this folder, ordered by reading priority for the CSI 6900 project on fine-tuning and LLM safety. The order follows the Fraser et al. reading guide: the core paper first, then the result it builds on, the benchmark it uses, and evaluation reliability, before the wider related work.

A link is included only when the authors released code or the benchmark data. “No public code repository” means none was found in the paper or as an official project repository.

## 1. Read first

1. Fraser et al. (2025). Fine-Tuning Lowers Safety and Disrupts Evaluation Consistency
   No public code repository.

2. Qi et al. (2024). Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!
   https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety

3. Xie et al. (2025). SORRY-Bench: Systematically Evaluating Large Language Model Safety Refusal
   https://github.com/SORRY-Bench/sorry-bench

4. Beyer et al. (2025). LLM-Safety Evaluations Lack Robustness
   No public code repository.

5. Vishnubhotla et al. (2026). Safety Measurements for Fine-tuned LLMs Should be Grounded in Capability
   No public code repository.

6. He et al. (2024). What is in Your Safe Data? Identifying Benign Data that Breaks Safety
   https://github.com/princeton-nlp/benign-data-breaks-safety

7. Lyu et al. (2024). Keeping LLMs Aligned After Fine-tuning: The Crucial Role of Prompt Templates
   https://github.com/vfleaking/PTST

8. Kumar et al. (2024). Fine-Tuning, Quantization, and LLMs: Navigating Unintended Outcomes
   No public code repository.

## 2. Fine-tuning and safety, read next

9. Betley et al. (2025). Emergent Misalignment: Narrow finetuning can produce broadly misaligned LLMs
   https://github.com/emergent-misalignment/emergent-misalignment

10. Li et al. (2025). Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning
    No public code repository.

11. Li et al. (2025). SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation
    https://github.com/homles11/SaLoRA

## 3. Adversarial fine-tuning

12. Lermen et al. (2024). LoRA Fine-tuning Efficiently Undoes Safety Training in Llama 2-Chat 70B
    No public code repository.

13. Yang et al. (2024). Shadow Alignment: The Ease of Subverting Safely-Aligned Language Models
    https://github.com/BeyonderXX/ShadowAlignment

14. Zhan et al. (2024). Removing RLHF Protections in GPT-4 via Fine-Tuning
    No public code repository.

15. Bowen et al. (2024). Scaling Trends for Data Poisoning in LLMs
    https://github.com/AlignmentResearch/scaling-poisoning

## 4. How safety scores are judged

16. Huang et al. (2024). TrustLLM: Trustworthiness in Large Language Models
    https://github.com/HowieHwong/TrustLLM

17. Souly et al. (2024). A StrongREJECT for Empty Jailbreaks
    https://github.com/dsbowen/strong_reject

18. Röttger et al. (2024). XSTest: A Test Suite for Identifying Exaggerated Safety Behaviours in Large Language Models
    https://github.com/paul-rottger/xstest

19. Brahman et al. (2024). The Art of Saying No: Contextual Noncompliance in Language Models
    https://github.com/allenai/noncompliance

## 5. Other benchmarks, lower priority for this project

20. Mazeika et al. (2024). HarmBench: A Standardized Evaluation Framework for Automated Red Teaming and Robust Refusal
    https://github.com/centerforaisafety/HarmBench

21. Vidgen et al. (2024). Introducing v0.5 of the AI Safety Benchmark from MLCommons
    https://github.com/mlcommons/modelbench

22. Vidgen et al. (2023). SimpleSafetyTests: a Test Suite for Identifying Critical Safety Risks in Large Language Models
    https://github.com/bertiev/SimpleSafetyTests

23. Wang et al. (2024). Do-Not-Answer: A Dataset for Evaluating Safeguards in LLMs
    https://github.com/Libr-AI/do-not-answer

24. Bianchi et al. (2024). Safety-Tuned LLaMAs: Lessons From Improving the Safety of Large Language Models that Follow Instructions
    https://github.com/vinid/safety-tuned-llamas

25. Li et al. (2024). The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning
    https://github.com/centerforaisafety/wmdp

26. Mireshghallah et al. (2024). Can LLMs Keep a Secret? Testing Privacy Implications of Language Models via Contextual Integrity Theory
    https://github.com/skywalker023/confaide

27. Wang et al. (2024). All Languages Matter: On the Multilingual Safety of Large Language Models (XSafety)
    https://github.com/Jarviswang94/Multilingual_safety_benchmark

28. Kour et al. (2023). Unveiling Safety Vulnerabilities of Large Language Models (AttaQ)
    No GitHub code repository. Official dataset: https://huggingface.co/datasets/ibm-research/AttaQ

29. Liu et al. (2023). Goal-Oriented Prompt Attack and Safety Evaluation for LLMs (CPAD)
    https://github.com/liuchengyuan123/CPAD

30. Zhang et al. (2023). JADE: A Linguistics-based Safety Evaluation Platform for Large Language Models
    https://github.com/whitzard-ai/jade-db

31. Sun et al. (2023). Safety Assessment of Chinese Large Language Models
    https://github.com/thu-coai/Safety-Prompts

32. Friedrich et al. (2025). LLMs Lost in Translation: M-ALERT uncovers Cross-Linguistic Safety Inconsistencies
    No GitHub code repository. Official dataset: https://huggingface.co/datasets/felfri/M-ALERT
