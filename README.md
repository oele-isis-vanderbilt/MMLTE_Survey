# Multimodal Methods for Analyzing Learning and Training Environments: A Systematic Literature Review
Created by <a href="https://www.claytoncohn.com" target="_blank">Clayton Cohn</a>, <a href="https://edavalosanaya.github.io" target="_blank">Eduardo Davalos</a>, <a href="https://www.vatral.net" target="_blank">Caleb Vatral</a>, <a href="https://scholar.google.com/citations?user=6QmCCGEAAAAJ&hl=en" target="_blank">Joyce Horn Fonteles</a>, <a href="https://hcwdavid.github.io/" target="_blank">Hanchen David Wang</a>,  <a href="https://meiyima.github.io" target="_blank">Meiyi Ma</a>, and <a href="https://scholar.google.com/citations?user=-m5wrTkAAAAJ&hl=en" target="_black">Gautam Biswas</a> from <a href="https://www.vanderbilt.edu/" target="_blank">Vanderbilt University</a>

### [Project](https://oele-isis-vanderbilt.github.io/MMLTE_SLR) | [Paper](./static/pdfs/Examining_Multimodal_Methods_for_Analyzing_Learning_and_Training_Environments__A_Systematic_Literature_Review__ACM_Computing_Surveys_.pdf)

<!-- ## Citation
If you find our work useful in your research, please consider citing: -->

## Introduction

Welcome to our comprehensive resource on multimodal methods for analyzing learning and training environments. Our website is dedicated to exploring the latest advancements in collecting and analyzing rich multimodal data to enhance educational and training experiences. Leveraging technologies such as speech recognition, video analysis, and eye-tracking, we provide insights into learner behaviors in both physical and virtual spaces. Our systematic literature review presents a taxonomy and framework of recent methodological advances, categorizing multimodal data into five groups: Natural Language, Video, Sensors, Human-Centered, and Environment Logs. By integrating these diverse data streams, we aim to offer a holistic understanding of learner interactions, uncovering patterns that single modalities may miss. Dive into our resources to discover state-of-the-art techniques, challenges, and future directions in multimodal learning and training environments. 

This paper makes the following contributions:

1. A comprehensive review of the research methods used in multimodal learning and training environments, the challenges encountered, and relevant results that have been reported in the literature. Simultaneously, we also identify the research gaps in the data collection and analysis methodologies;
2. A congruent framework and taxonomy that reflects the recent advances in multimodal learning and training methodologies;
3. An additional data fusion classification that we call mid fusion (i.e., it is between early fusion and late fusion) that allows for differentiating processed features relative to the observability line.
4. A graph-based corpus reduction procedure using a citation graph, which we refer to as citation graph pruning, that allows for programmatically pruning literature review corpora.

# Framework

![](./static/images/20240502_architecture.png)

During our literature review, we formulated a framework and taxonomy to help understand, organize, and explore the relationship between crucial elements in multimodal learning analytics. The "Multimodal Learning and Training Environments Literature Review" framework decomposes the multimodal learning and training analytics process into four primary components: the learning or training environment, multimodal data, learning analytics methods, and feedback. This framework provides a structured approach to understanding how different modalities and methods are integrated to enhance the analysis of educational and training environments, ultimately aiming to improve learning outcomes through comprehensive data collection and analysis techniques.

# Findings

The findings of the review reveal that leveraging multiple modalities provides a more holistic understanding of learner behaviors and outcomes, often uncovering patterns that single-modality data might miss. The study highlights the current state-of-the-art techniques, key challenges, and gaps in research, emphasizing the potential of multimodal methods in enhancing learning and training experiences. Readers are encouraged to explore the paper to find more specific statistics and detailed descriptions tailored to their particular interests.

# Conclusion & Future Work

The review identifies several challenges and limitations in the field of multimodal learning and training environments. Key challenges include the complexity of integrating diverse data streams, ensuring data quality and privacy, and addressing the variability in data collection environments. Limitations are noted in the scalability of certain methods and the need for more robust, standardized approaches to data fusion and analysis. The research also highlights significant gaps, such as the underrepresentation of certain modalities and the need for more studies focused on active learning environments, such as physical training and embodied learning. Future work should aim to bridge these gaps by developing more scalable, standardized methodologies and exploring new avenues for integrating and analyzing multimodal data.

# Corpus Distillation

Our literature review corpus was acquired through an extensive literature search using 42 search strings to encapsulate relevant works in the field. This search yielded 4,200 papers from Google Scholar, which were then filtered down to 73 papers through a combination of citation graph pruning and qualitative analysis, ensuring a representative and focused dataset for the review.

![](/static/images/cgp.png)

The corpus distillation process involved a novel approach called citation graph pruning combined with a methodical qualitative review. Citation graph pruning utilized a directed citation graph to iteratively remove papers with minimal connections to the corpus, thereby reducing the initial set from 4,200 to 1,063 papers. Following this, a systematic qualitative process employed, which included reviewing titles, abstracts, and full texts. This rigorous method further refined the corpus by excluding irrelevant works and those that met our exclusion criteria, ultimately distilling the set to the 73 papers that were comprehensively analyzed in the review.
