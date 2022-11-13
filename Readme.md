## Children's Reading Confidence Dataset

The dataset contains 600 recordings of English paragraphs read by 155 L2 learners (Maharashtra, India) in grades 5-8 (age group 10-14 years). 

The reading material was short English stories in 2-3 paragraphs of about 50-70 words each. A paragraph was displayed on an Android app screen with recording performed in relatively quiet school room using a headset microphone. All recordings are in `.wav` format with 16kHz sampling frequency and 16-bit PCM format. 

Each recording duration is between 10 sec to 72 sec (mean = 26.4s, s.d. = 10.6s).

Each recording was listened to by two raters who independently rated it on a 3-point scale (low, medium, high) for perceived reading confidence using a web interface.

The dataset is subset of all acquired recordings so that lexical miscues (number of substitutions, deletions and insertions) are below 20% of the total number of words in the paragraph. Further, the recordings included in this dataset are where both the raters agree on the confidence level rating. The dataset has approximately even distribution across the three levels (low - 196, medium - 242, high - 162).


#### Organisation of the Dataset
1. audios - this folder has all the 600 audio recordings.
2. ratings.csv - a comma separated file containing audio names and confidence ratings
3. Readme.md


This dataset is being made available for non-commercial research purposes only. Please do cite this paper if you happen to use this dataset in your research:

[Kamini Sabu and Preeti Rao (2020) ``Automatic prediction of confidence level from children's oral reading recordings", Proc. Interspeech 2020, Shanghai, China](https://www.isca-speech.org/archive_v0/Interspeech_2020/abstracts/2276.html)

Please contact us at this email id for a copy of the dataset:
prao@ee.iitb.ac.in
(Prof. Preeti Rao, Dept of EE, IITB)

