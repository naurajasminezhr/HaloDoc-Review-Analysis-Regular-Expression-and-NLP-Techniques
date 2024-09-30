# HaloDoc-Review-Analysis-with-RegEx
This notebook demonstrates the use of regular expressions to analyze and extract insights from HaloDoc app reviews. The analysis focuses on identifying key patterns and trends in user feedback.

# HaloDoc Review Analysis with Regular Expressions

This repository contains a Jupyter notebook that demonstrates the use of regular expressions to analyze and extract insights from HaloDoc app reviews.

## Overview

The project focuses on analyzing user reviews of the HaloDoc application using regular expressions to identify patterns, extract key information, and gain insights into user experiences and sentiments.

## Contents

- `RegularExpression_HaloDocReview.ipynb`: Jupyter notebook containing the analysis code
- `df_halodoc_after_detectlang.csv`: Dataset of HaloDoc reviews (not included in the repository)

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- re (regular expressions library)

## Key Features

1. Loading and preprocessing of HaloDoc review data
2. Definition of regex patterns for key terms
3. Frequency analysis of key terms in reviews
4. Correlation analysis between different terms with heatmaps
5. Extraction of specific sentences containing target keywords
6. Visualization of results using bar plots

## Results

The analysis provides several insights into HaloDoc user reviews:

Certainly! I'll add the additional regex analyses you mentioned to the Results section of the README. Here's an updated version:

## Results

The analysis provides several insights into HaloDoc user reviews:

1. Frequency of Key Terms:
   - "membantu" (helpful): 7,563 occurrences
   - "dokter" (doctor): 4,098 occurrences
   - "obat" (medicine): 4,060 occurrences
   - "halodoc": 3,270 occurrences
   - "aplikasi" (application): 2,836 occurrences

2. Correlation Analysis:
   - Highest correlation (0.341) between "dokter" (doctor) and "konsultasi" (consultation)
   - Strong correlation (0.246) between "obat" (medicine) and "resep" (prescription)

3. Sentence Extraction:
   - Successfully extracted sentences containing both "obat" (medicine) and "dokter" (doctor), providing context for how these terms are used together in reviews

4. Regular Expression for Extracting Consultation Time:
   - Identified patterns of consultation times mentioned in reviews

5. Regular Expression for Medicine Delivery Duration:
   - Extracted information about the duration of medicine delivery

6. Regex for Extracting Application Rating:
   - Analyzed user-given ratings within the review text

7. Regex for Extracting Application Issues:
   - Identified common issues or complaints mentioned by users

8. Regex for Extracting Favorite Features in Halodoc App:
   - Highlighted features that users frequently mention as favorites

9. Regex for Extracting Suggestion for App Improvement:
   - Collected user suggestions for enhancing the app

10. Regex for Extracting Comparison of Offline Service:
    - Analyzed how users compare Halodoc to traditional offline medical services

11. Regex for Extracting Repeated Usage Experiences:
    - Identified patterns of repeated app usage mentioned in reviews

12. Regex for Extracting Grievance with the Doctor Service:
    - Collected specific complaints or issues related to doctor consultations

13. Regex for Extracting Comments about Service Bills:
    - Analyzed user comments regarding billing and pricing

These regex analyses provide a more comprehensive understanding of user experiences, preferences, and issues with the Halodoc app, offering valuable insights for potential improvements and marketing strategies.

4. Visualizations:
   - Bar plot showing the frequency of key terms
   - Heatmap displaying the correlation between different terms

These results provide valuable insights into user experiences with the HaloDoc app, highlighting the importance of doctors, medicine, and the consultation process in user reviews. The additional regex analyses offer a more nuanced understanding of specific aspects of the user experience, from consultation times to billing comments.


## Usage

1. Clone this repository
2. Ensure you have the required libraries installed
3. Open the Jupyter notebook `RegularExpression_HaloDocReview.ipynb`
4. Run the cells in order to reproduce the analysis

Note: You'll need to have the `df_halodoc_after_detectlang.csv` file in the same directory as the notebook to run the analysis.

## Future Work

- Sentiment analysis of reviews
- Topic modeling to identify main themes in user feedback
- Time series analysis to track changes in user sentiment over time

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology (MIT). It puts only very limited restriction on reuse and has, therefore, high license compatibility.

Key points of the MIT License:
- It allows users to do anything with the code, including using it commercially.
- The only requirement is that the license and copyright notice must be included with the code.
- It provides no warranty or liability protection for the original author.

For the full license text, please refer to the LICENSE file in this repository.

## Acknowledgments

- HaloDoc for providing the platform that generated these user reviews
- The open-source community for the tools and libraries used in this analysis
