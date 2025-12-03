# **AbjadGenEval**: Abjad AI Generated Text Detection Shared Task for Languages Using Arabic Script  

### Hosted with [AbjadNLP Workshop](https://wp.lancs.ac.uk/abjad/) within EACL 2026 Conference

## 1. Overview of the Shared Task
The rapid expansion of user-generated content across social media, digital news platforms, and online communication has created a growing demand for sophisticated Natural Language Processing (NLP) techniques to distinguish between human-written and machine-generated text. Recent advances in multilingual Large Language Models (LLMs) have made it increasingly difficult to identify AI-generated content, particularly in low-to-medium resource languages.

This shared task, AbjadGenEval, focuses specifically on languages utilizing the Abjad (Arabic) script, covering Arabic, Urdu, and Persian. While AI detection tools are maturing for English, performance often degrades significantly for Abjad languages due to complex morphology, script specificities, and varying degrees of data availability.

We invite participants to develop robust models for the following main task:

- **Abjad AI-Generated Text Detection (Binary Classification)**: Distinguishing between human-written and AI-generated text across Arabic, Urdu, and Persian.

## 2. Motivation
AI-generated text detection is critical for maintaining information integrity in education, journalism, and social media. The motivation for launching this shared task arises from the increasing capabilities of LLMs in generating fluent text in Arabic, Urdu, and Persian, combined with the lack of robust detection benchmarks for these specific languages.

The Abjad domain presents distinct challenges:

  - Script Complexity: The shared script features (ligatures, absence of short vowels) present unique tokenization and encoding challenges compared to Latin scripts.

  - Linguistic Diversity: While sharing a script, Arabic (Semitic), Urdu (Indo-Aryan), and Persian (Indo-Iranian) belong to different language families, requiring models that can generalize or adapt across distinct grammatical structures.

  - Limited Labeled Data: Large-scale, high-quality datasets for AI detection in Urdu and Persian are particularly scarce compared to Arabic.

Our goal is to inspire researchers to tackle these challenges and enhance detection techniques specifically for the Abjad ecosystem.

## 3. Data Collection and Creation

The dataset for this task is a curated collection of human and machine-generated texts across the three target languages.

  - Human-Written Texts: Collected from reputable news sites, verified literary sources, and opinion pieces.

    - Arabic: Sourced from diverse regions to cover Modern Standard Arabic (MSA).

    - Urdu: Collected from major news outlets and literary archives in Pakistan and India.

    - Persian: Curated from news agencies and contemporary literature.

  - AI-Generated Texts: Produced using a variety of Abjad-compatible LLMs (e.g., GPT-4, LLaMA 3, Mistral, and language-specific fine-tunes such as Jais or AceGPT where applicable) under diverse prompting strategies to simulate varying levels of generation quality.

  - Annotation: Strict binary labels (Human vs. AI).

## 4. Task Description: Abjad AI-Generated Text Detection

Participants are required to build models that can classify a given text as either human-written or AI-generated. The task is divided into three language-specific tracks and one combined track:

  1. Arabic Track: Detection on Arabic data only.

  2. Urdu Track: Detection on Urdu data only.

  3. Persian Track: Detection on Persian data only.

  4. Multilingual Abjad Track: A unified model evaluated across all three languages.

- Input: A text snippet (news excerpt, literary paragraph, or social media post).

- Output: Binary Label (0 for Human, 1 for AI).

- Evaluation:

  - Primary Metric: Macro-F1 Score (to account for potential class imbalances).

  - Secondary Metric: Accuracy.).

## 5. Tentative Timeline
- **December 10, 2025**: Release of training data  
- **December 25, 2025**: Release of test data  
- **December 31, 2025**: End of evaluation cycle (test submissions close)  
- **January 2, 2026**: Final results released  
- **January 8, 2026**: Shared task papers due date  
- **January 20, 2026**: Notification of acceptance  
- **February 3, 2026**: Camera-ready versions due  
- **March 24–29, 2026**: Workshop Dates [TBD]

## 6. Organizers’ Details
- **Saad Ezzini**, King Fahd University of Petroleum & Minerals 
- **Irfan Ahmed**, King Fahd University of Petroleum & Minerals
- **Salmane Chafik**, Mohammed VI Polytechnic University  
- **Mo El-Haj**, VinUniversity  
- **Shadi Abudalfa**, King Fahd University of Petroleum & Minerals  
- **Ahmed Abdelali**, HUMAIN  
- **Mustafa Jarrar**, Hamad Bin Khalifa University / Birzeit University  
 

## 7. Participation Guidelines
- For participation guidelines, please refer to [Participation Guidelines](guidelines.md).
- Comprehensive instructions for preparing and submitting your paper(s) are available at [Paper Submission Guidelines](PAPER.md).


---


### Logistics and Support
- **Website Hosting**: GitHub Pages
- **Submission System**: Codabench
- **Communication Channels**:
  - Slack workspace
  - Mailing list
  - GitHub repository
- **Regular updates and participant support**


### Stay Updated
- Official **GitHub Repository**: https://github.com/ezzini/AbjadGenEval
- Join our [Slack community](https://join.slack.com/t/abjadgeneval/shared_invite/zt-3jiv20dw3-SErhRYds~Z_9PrdE2iPgtA)

### Announcements and Updates
- The final phase will begin on December 25, 2025 (UTC-12h) and will run for 6 days, ending on December 31, 2025 (UTC-12h). During this time, each team must submit their predictions on the test set (not the validation set) via the Codabench system. Only submissions made within this timeframe will be considered as official contributions when submitting your papers to the OpenReview system.
- The main content of your paper should not exceed 4 pages. There is no page limit on appendices and references; these sections are excluded from the 4-page limit.
  
### Anti-Harassment policy
We uphold the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/index.php?title=Anti-Harassment_Policy), and participants in this shared task are encouraged to reach out with any concerns or questions to any of the shared task organizers.



