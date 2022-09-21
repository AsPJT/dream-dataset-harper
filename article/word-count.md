# 📝 Word count 文字数

### 🖥️ Source code ソースコード

|Name|Variable|Source code|
|:---|:---|:---|
|Dream Characters|word-count.word-count|=COUNT(FILTER(story.word-count-list, story.word-count-list > word-count.word-count-min, story.word-count-list <= word-count.word-count-max))|
|Word count|fiscal-year.word-count|=SUM(FILTER(story.word-count-list, story.fiscal-year-list=fiscal-year.fiscal-year))|
|Average Word count|fiscal-year.average-word-count|=fiscal-year.word-count/fiscal-year.dreams|

|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/dreams-separated-by-every-15-characters.svg)|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/dreams-separated-by-every-25-characters.svg)|
|:---|:---|
|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/dreams-separated-by-every-50-characters.svg)|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/dreams-separated-by-every-100-characters.svg)|

### 📈 Figure. Dream Characters 夢の文字数

|![word count](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/fiscal-year/word-count.svg)|![word count](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/fiscal-year/word-count-log-scale.svg)|
|:---|:---|

### [📈 Figure. Word count 文字数](https://github.com/Asuimin/dream-dataset-harper/blob/main/data/fiscal-year.tsv)

![word count](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/fiscal-year/average-word-count.svg)

### [📈 Figure. Average word count 平均文字数](https://github.com/Asuimin/dream-dataset-harper/blob/main/data/fiscal-year.tsv)

|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/word-count-in-story-and-year.svg)|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/word-count-in-story-and-year-2013.svg)|
|:---|:---|
|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/word-count-in-story-and-year-2018.svg)|![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/word-count-in-story-and-year-2020.svg)|

### 📈 Figure. Word count in story and year 物語文字数と年

![story](https://raw.githubusercontent.com/Asuimin/dream-dataset-harper/main/graph/story/word-count-in-story-and-rank.svg)

### 📈 Figure. Word count in story and rank 物語文字数と順位
