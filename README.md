# sentiment-analysis
Google Play Review Sentiment Analysis (Blibli)

🔗 Google Colab Links: https://colab.research.google.com/drive/1oWq0mvVhD0msi9I22_KY0v6JtRdw-m2W?usp=sharing

## Project Overview

This project analyzes user reviews of the Blibli mobile application collected from the Google Play Store. The objective is to understand customer sentiment by performing text preprocessing, sentiment labeling, visualization, and machine learning classification.

## Objectives

- Collect user reviews from Google Play Store
- Clean and preprocess Indonesian text data
- Classify reviews into positive and negative sentiments
- Compare machine learning models for sentiment classification
- Visualize sentiment distribution and frequently used words

## Dataset

- **Source:** Google Play Store
- **Application:** Blibli
- **Reviews Collected:** 1500
- **Language:** Indonesian

### Dataset Preview

| Review | Rating |
|---------|--------|
| goooood | 5 |
| ada kendala stlh di update..langsung direspon sm sistem dan dibantu cari solusinya..Thanks..masalah sudah teratasi. | 1 |
| proses retur lamban | 5 |
| Pembayaran gagal terus | 2 |
| mantappppp betulllll | 5 |
| pengalaman belanja sangat baik , Customer service nya juara bagus banget. | 2 |

## Tools & Libraries

- Google Colab

## Workflow

1. Scrape user reviews from Google Play Store
2. Data cleaning
3. Text preprocessing
    - Case folding
    - Remove punctuation
    - Slang normalization
    - Tokenization
    - Stopword removal
    - Stemming (Sastrawi)
4. Sentiment labeling
5. TF-IDF feature extraction
6. Train machine learning models
7. Evaluate model performance
8. Visualize results

## Machine Learning Models

- Multinomial Naive Bayes
- K-Nearest Neighbors (KNN)

## Visualizations

### Sentiment Distribution

![Sentiment Distribution](sentiment-percentage.png)

Approximately 69% of reviews were classified as positive, suggesting that most users had a favorable experience with the application.

### Word Cloud

**Positive Reviews**

![Positive Reviews](wordcloud-positive-bibli.png)

The positive word cloud indicates that users generally had a satisfying shopping experience.

**Key observations:**

- "mantap", "bagus", and "keren" reflect high overall customer satisfaction.
- "mudah", "cepat", and "lancar" suggest that users found the application easy to use and responsive.
- "promo", "diskon", and "voucher" show that promotional campaigns and competitive pricing were highly appreciated.
- "terpercaya", "aman", and "original" indicate strong customer trust in product authenticity and transaction security.


**Negative Reviews**

![Negative Reviews](wordcloud-negative-bibli.png)

The negative word cloud highlights the main issues experienced by users.

**Key observations:**

- "barang", "kirim", "batal", and "retur" indicate that shipping delays, order cancellations, and return processes were common complaints.
- "bayar", "refund", "saldo", and "paylater" suggest payment and refund-related issues.
- "error", "login", and "apk" reveal recurring technical problems affecting user experience.
- "chat" and "cs" imply dissatisfaction with customer support responsiveness.

### Model Accuracy Comparison
![Model Comparison](model-sentiment-bibli.png)

The Naive Bayes model outperformed KNN in this classification task, likely because Naive Bayes is well suited for sparse TF-IDF text features.

## Result
![Result](review-comparison-graphic-bibli.png)

In conclusion, It is proven by the graphic that the majority reviews for Bibli application in Google Playstore are positives.


## sentiment-analysis
Youtube comment sentiment analysis

Youtube video: https://www.youtube.com/watch?v=z0PFetRQg4Q

Google Colab link: https://colab.research.google.com/drive/1dZnbP6xPRA34mEpBXKiyI5pxrs_ZZmfU?usp=sharing

## Project Overview

This project analyzes user comments collected from a public YouTube video to understand audience sentiment. The analysis includes web scraping, text preprocessing, sentiment classification, and visualization using Python.

## Objectives

- Collect comments from a YouTube video
- Clean and preprocess text data
- Translate Indonesian comments into English
- Perform sentiment analysis using TextBlob
- Visualize sentiment distribution
- Identify frequently used words using Word Cloud

## Dataset

- **Source:** YouTube
- **Comments Collected:** 150
- **Language:** Indonesian

### Dataset Preview

| Comment | Likes |
|---------|------:|
| denger "naik perahu" fatimah sampe kaget😭 krn that's the POINT infrastruktur lebih penting | 1.1K |
| fatimah azahra publik speaking nya udah bisa mantatin presiden sama wakilnya😂 | 524 |
| Bapak baju hitam punya banyak dapur di daerah Sulawesi makanya membela banget program ini | 45 |
| Dukung mahasiswa untuk indonesia lebih baik | 427 |
| PREEET itu pak siapa yg mewakili pemerintah dari gerindra... | 435 |

---

## Tools & Libraries

- Google Colab
- Pandas
- Youtube Comment Downloader
- TextBlob
- Google Translator
- Matplotlib
- Seaborn
- WordCloud

---

## Workflow

1. Scrape comments from YouTube
2. Data cleaning
3. Translate Indonesian comments into English
4. Perform sentiment analysis
5. Label comments as Positive, Neutral, or Negative
6. Visualize sentiment distribution
7. Generate Word Cloud
8. Export processed data to CSV

---

## Visualizations

### Sentiment Distribution

![Sentiment Distribution](sentiment-video-comment-graphic.png)

**Key observations:**
- Positive sentiment indicates that many viewers expressed support or appreciation for the discussion presented in the video.
- Neutral comments mainly consisted of questions, factual discussions, or opinions without a clear positive or negative stance.
- Negative comments represented a smaller share and were generally associated with disagreement or criticism toward certain viewpoints discussed in the debate.

**Insights**

The results suggest that the YouTube audience responded constructively to the discussion. The high proportion of positive and neutral comments indicates that viewers were generally engaged with the topic and participated in meaningful discussions rather than expressing predominantly negative reactions.


### Word Cloud

![Word Cloud](wordcloud-youtube.png)

**Key Observations**
- "MBG" (Free Nutritious Meals Program) appeared as one of the most prominent keywords, indicating that the program was the central topic of discussion.
- Words such as "infrastruktur" (infrastructure), "SPP" (school tuition), "sekolah" (school), and "dana" (funds) suggest that many viewers discussed government budget allocation and public service priorities.
- Economic-related terms including "harga" (price), "pasar" (market), "pedagang" (merchant), and "petani" (farmer) indicate that viewers frequently connected the discussion to broader economic conditions and their real-life experiences.
- Keywords such as "mahasiswa" (students) and "rakyat" (people) show that the conversation also focused on public participation and the role of students in expressing social concerns.

**Discussion**

The word cloud suggests that the comment section extended beyond reactions to the debate itself. Viewers actively discussed public policy, education, infrastructure, and economic issues, indicating a high level of engagement with the broader topics presented in the video.

