# Consumer Financial Protection Bureau Complaints – Clustering Analysis

This project analyzes customer complaints submitted to the Consumer Financial Protection Bureau (CFPB), specifically within the domain of credit reporting. Using unsupervised learning (K-Means clustering), the project segments thousands of consumer grievances into meaningful thematic groups to uncover distinct patterns in consumer concerns, legal awareness, and potential regulatory gaps.

---

## Objective

- To classify consumer complaints using clustering techniques.
- To uncover underlying themes and pain points in credit reporting grievances.
- To generate actionable insights for credit bureaus and regulatory bodies.

---

## Dataset

- Source: Consumer Complaint Database (CFPB)
- Focus: Credit reporting-related complaints
- Fields analyzed: Narrative text content of complaints

---

## Methodology

1. **Text Preprocessing**
   - Tokenization, stopword removal, and lemmatization.
   - TF-IDF vectorization to numerically represent text data.

2. **Clustering Technique**
   - Applied K-Means clustering to categorize complaints into groups based on content similarity.
   - Optimal number of clusters determined using elbow method and silhouette scores.

3. **Cluster Interpretation**
   - Word frequency analysis and legal reference identification used to interpret cluster themes.

---

## Clustering Results

### Cluster 0: General Credit Report Disputes
- **Size**: 420 complaints
- **Focus**: Inaccurate or outdated account information, report correction requests.
- **Insight**: Represents standard disputes where consumers request factual corrections.

### Cluster 1: Privacy Right Violations
- **Size**: 58 complaints
- **Focus**: Privacy breaches, misuse of credit data, legal references to FCRA (15 U.S.C. §1681).
- **Insight**: Indicates high consumer awareness of legal rights and frustration with data misuse.

### Cluster 2: Fraudulent/Unauthorized Reporting
- **Size**: 142 complaints
- **Focus**: Credit reports with unauthorized or fraudulent entries.
- **Insight**: Highlights concerns over identity theft, urgent deletion requests, and fraud resolution delays.

---

## Key Takeaways

- **Cluster diversity** shows varied consumer concerns: general disputes, legal rights, and fraud.
- **Legal literacy** is notable, especially in clusters where FCRA is cited.
- **Actionable insights** can aid credit bureaus in refining reporting practices, privacy safeguards, and fraud mitigation workflows.

---

## Technologies Used

- Python
- scikit-learn
- NLTK / spaCy
- Pandas / NumPy
- Matplotlib / Seaborn

---

## Author

Abhimanyu Pratap Singh 
Data Analyst | NLP Enthusiast | Regulatory Data Research

---

## License

This project is licensed under the MIT License. See `LICENSE.md` for more details.





