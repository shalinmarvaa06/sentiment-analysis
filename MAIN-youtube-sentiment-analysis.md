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
