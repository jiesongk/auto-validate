# Auto-Validate Evaluational Data

This is the shared folder containing data relating to AutoValidate evaluation.

## Top Level Folder Structure

We have three top-level folders: `benchmarks-data` contains the public benchmark datasets from the government domain (referred to as government in the paper) used for evaluation;  `user-study-data` contains the user study design and results from participants.

```
.
├── README.md
├── benchmarks-data
└── user-study-data
```

## Benchmarks
Under `benchmarks-data`, we share the benchmark from the government domain:  `Government` ($B_G$) in `Government-benchmark-1000-case/Revision-NewData-Gov-ProcessedColFile-all-of-10.txt`.

```
./benchmarks-data
└── Government-benchmark-1000-case
    └── Revision-NewData-Gov-ProcessedColFile-all-of-10.txt
```



## User Study

In `user-study-data`, for the 20 samples test columns in benchmark $B_E$, we show the pattern and the pattern written time of each test for the three participants in `user_study.xlsx` automatically generated from the online user study. For each participant, files named `user_study_*_precision_and_recall.txt` show the test columns and the pattern he/she generated and `user_study_*_precision_and_recall.stats` show the corresponding precision and recall statistics of the participant. 

```
./user-study-data
├── user_study.txt
├── user_study.xlsx
├── user_study_2_precision_and_recall.stats
├── user_study_2_precision_and_recall.txt
├── user_study_3_precision_and_recall.stats
├── user_study_3_precision_and_recall.txt
├── user_study_4_precision_and_recall.stats
└── user_study_4_precision_and_recall.txt
```

