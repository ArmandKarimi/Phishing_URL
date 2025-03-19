This notebook explores the PhiUSIIL Phishing URL Dataset, a large-scale collection of both legitimate and phishing URLs. In total, the dataset contains 134,850 legitimate and 100,945 phishing URLs, most of which are recently gathered.

To facilitate phishing detection, we extracted various features directly from each URL and its corresponding webpage source code. In addition to these base features, we derived more advanced metrics, such as:

CharContinuationRate
URLTitleMatchScore
URLCharProb
TLDLegitimateProb
These engineered features aim to capture subtle patterns in URL structure and webpage content that are often indicative of malicious intent. Throughout this notebook, we will perform data exploration, preprocessing, model training, and evaluation steps to demonstrate how these features can be leveraged to accurately distinguish between phishing and legitimate URLs.
