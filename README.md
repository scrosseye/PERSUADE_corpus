# PERSUADE corpus 1.0

This is the repository for The Persuasive Essays for Rating, Selecting, and Understanding Argumentative and Discourse Elements (PERSUADE) corpus which contains over 280,000 discourse annotations for over 25,000 argumentative essays. 

The PERSUADE corpus formed the core of the Feedback Prize hosted by Kaggle in the winter of 2021-2022 (https://www.kaggle.com/c/feedback-prize-2021)

The corpus is contained in a single .csv file that is machine readable and able to opened in common spreadsheet software. The corpus contains the following columns:


**essay_id_comp:** The essay ID	

**competition_set:** Whether the essay was part of the training or the test set in the Feedback Prize

**full_text:** The full text of the essay

**discourse_id:** ID for the discourse element

**discourse_start:** Character position in the essay where the discourse element starts

**discourse_end	discourse_text:**	Character position in the essay where the discourse element ends

**discourse_type:** Human annotation for the discourse element	

**discourse_type_num:** Number for discourse element in essay

Each essay in the PERSUADE corpus was human annotated for argumentative and discourse elements as well as relationships between argumentative elements. The corpus was annotated using a double-blind rating process with 100 percent adjudication such that each essay was independently reviewed by two expert raters and adjudicated by a third expert rater.

The annotation rubric was developed to identify and evaluate discourse elements commonly found in argumentative writing. The rubric was developed in-house and went through multiple revisions based on feedback from two teacher panels as well as feedback from a research advisory board comprising experts in the fields of writing, discourse processing, linguistics, and machine learning. The discourse elements chosen for this rubric come from Nussbaum, Kardash, and Graham (2005) and Stapleton and Wu (2015). Both annotation schemes are adapted or simplified versions of the Toulmin argumentative framework (1958). Elements scored and brief descriptions for the elements are provided below.

**Lead.** An introduction that begins with a statistic, a quotation, a description, or some other device to grab the reader’s attention and point toward the thesis

**Position.** An opinion or conclusion on the main question

**Claim.** A claim that supports the position

**Counterclaim.** A claim that refutes another claim or gives an opposing reason to the position

**Rebuttal.** A claim that refutes a counterclaim

**Evidence.** Ideas or examples that support claims, counterclaims, rebuttals, or the position

**Concluding Summary.** A concluding statement that restates the position and claims

**Unannotated.** Segments that were not discourse elements

The data is provided under a CC BY-NC-SA 4.0 DEED Attribution-NonCommercial-ShareAlike 4.0 International license (https://creativecommons.org/licenses/by-nc-sa/4.0/deed.en)
