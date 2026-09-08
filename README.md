## Study Overview

This dataset was used in a study examining public discourse surrounding the
Mpox outbreak on Reddit. The study analyzes the sentiment, topical themes, and
audience engagement of Mpox-related posts and comments, with particular
attention to how the sentiment and topic of a post relate to engagement and
subsequent audience responses.

The study is published in the *Journal of Medical Internet Research*:

**Luo, X. N., Movahedi Nia, Z., & Kong, J. D. (2026). Reddit Discussions During
the 2022 Mpox Outbreak: Observational Analysis of Sentiment, Topics, and
Audience Engagement. Journal of Medical Internet Research, 28, e90152.**

[Read the paper](https://www.jmir.org/2026/1/e90152)

## Dataset Overview

### Description

The dataset contains Reddit posts and comments used in the study. After
removing missing or problematic values and non-English content, the final
dataset contains 1,169 posts and 6,571 comments. The data have been
de-identified to protect user privacy.

### Time Span

The earliest post and comment were created on July 21, 2021, and the latest
on July 16, 2025.

### Data Collection

Data were collected using the ReddAPI package from four subreddits:

- r/Monkeypox
- r/monkeypoxpositive
- r/worldnews
- r/news

For the general news subreddits (r/worldnews and r/news), posts were filtered
using the keywords "mpox" and "monkeypox" to isolate outbreak-related
discussions. Retrieved data included post metadata (e.g., title, score, and
timestamp) and associated comments. The data were subsequently processed and
filtered for English-language content using the cld3 language detection
library in R.
