## Dataset Overview

### Source

The dataset used for analysis was sourced from Reddit, which, after
removing missing or problematic values and non-English contents,
contains a total of 1,169 posts and 6,571 comments.

### Time span

The earliest post and comment were both created on July 21 2021, and the
latest July 16 2025.

### Keywords used for collection

Data were collected using the ReddAPI package, targeting four
subreddits:

-   r/Monkeypox

-   r/monkeypoxpositive

-   r/worldnews

-   r/news

For the general news subreddits (r/worldnews and r/news), posts were
filtered using the keywords “mpox” and “monkeypox” to isolate
outbreak-related discussions. Retrieved data included post metadata
(e.g., title, score, timestamp) and associated comments, which were
subsequently processed and filtered for English-language content using
the cld3 language detection library in R.
