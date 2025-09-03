# Intelligent-Tutoring-for-Law-Courses-Accesebale-Prompts
Prompts and example interactions used in the paper “Intelligent Tutoring for Law Courses: Design and Evaluation of an LLM-based System". This repository provides the exact system prompts employed in our study, along with documentation to support reproducibility and reuse in related research. The prompts in the prompts/ folder are written in English and designed to support students in learning the IRAC method for legal case writing. These prompts were implemented in our system and evaluated in the associated paper.

The adapted prompts, available in the adapted_prompts/ folder, are currently only provided in German (focusing on the apprasial style). We are working on an English version, which will be made available soon. The main change in the prompts is the integration of sample solutions for each case study. By providing these model answers as a reference, the CaseCoach can give more precise and targeted feedback to students. This ensures that evaluations are not only consistent but also better aligned with the expected structure and content of legal reasoning.

In your prompt, the three # NOTE: lines are placeholders that indicate where content should be inserted. They are not part of the actual instructions.
# NOTE: Case Study
👉 Marks the spot where the case facts / case study should be inserted.
Placeholder for: “What happened?” or the description of the legal case.
# NOTE: Text Students
👉 Marks the spot where the student’s answer should be inserted.
Placeholder for: the solution or essay written by the student.
# NOTE: Sample Solution for the Case Study
👉 Marks the spot where the model solution should be inserted.
Placeholder for: the official or exemplary solution that will be used for comparison and feedback.
