# NLP-1K-Stories-Dataset-Genres-100
This repository hosts a diverse NLP dataset comprising 1,000 stories spanning 100 genres for comprehensive language understanding tasks.

[![HuggingFace Space](https://img.shields.io/badge/🤗-HuggingFace%20Dataset-cyan.svg)]([https://huggingface.co/spaces/IDEA-Research/Grounded-SAM](https://huggingface.co/datasets/FareedKhan/1k_stories_100_genre))

license: cc-by-2.0 (Personal or commercial use but give attribution)

language:
- en

size_categories:
- 1K<n<10K

pretty_name: Thousand Stories, Hundred Genres

task_categories:
- summarization
- text-generation
- text-classification

tags:
- data science
- Storytelling
- Genre Classification
- NLP
- LLM
- Deep Learning

# Dataset Documentation

## Overview

This dataset contains 1000 stories spanning 100 different genres. Each story is represented in a tabular format using a dataframe. The dataset includes unique IDs, titles, and the content of each story.

## Genre List

The list of all genres can be found in the [genres.txt](https://huggingface.co/datasets/FareedKhan/1k_stories_100_genre/blob/main/story_genres.pkl) file.

reading genre_list variable
```python
with open('story_genres.pkl', 'rb') as f:
    story_genres = pickle.load(f)
```
Sample of genre list:
```python
genres = ['Sci-Fi', 'Comedy', ...]
```

## Dataframe Format

The dataset is structured in the following format:

1. **id**: Unique identifier for each dataframe.
2. **title**: Title of the story.
3. **story**: The content of the story.
4. **genre**: The genre of the story.

## Sample Dataframe

| id    | title                | story                                      | genre  |
|-------|----------------------|--------------------------------------------| ------ |
| 25235 | The Unseen Miracle   | It was a stormy night in ...               | Horror |
| ...   | ...                  | ...                                        | ...    |

## Average Length of Words

- Title: 6 words
- Story: 960 words

# License

This dataset is licensed under the [cc-by-2.0](https://creativecommons.org/licenses/by/2.0/deed.en)
