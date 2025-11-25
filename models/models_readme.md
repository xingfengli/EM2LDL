
### Codings for Experiments on EM²LDL

- **Org.zip on Experiment 1: Overall Baseline Performance on the EM²LDL**  
  A speaker-independent split of the full corpus into training/validation/test partitions at a 70/10/20 ratio (7:1:2) by speaker ID. No speaker overlap occurs across partitions.

- **Gender.zip on Experiment 2: Gender-Effect Investigation on the EM²LDL**  
  Cross-validation (CV) was performed by training on male speakers (1,022 utterances) and testing on female speakers (2,976 utterances), and vice versa, to examine gender-specific emotional expression patterns.

- **Age.zip on Experiment 3: Age-Effect Investigation on the EM²LDL**  
  CV was conducted by training on youth speakers (3,220 utterances) and testing on non-youth speakers (778 utterances), and vice versa, to investigate age-related differences in emotional speech.

- **MBTI-4.zip on Experiment 4: Personality-Effect Investigation on the EM²LDL**  
  A leave-one-out personality (LOPO) CV was performed on a subset of speakers with MBTI annotations, covering four personality types (IN, IS, EN, ES). Each fold trained on three personality types and tested on the held-out type, resulting in a 4-fold CV.
