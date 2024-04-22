media-data.pkl


---

## DataFrame Description

### Index

- **ID**: Unique identifier for each entry in the DataFrame.
- **URL**: The URL associated with the entry.
- **Body**: The main content or text body of the entry.
- **Title**: The title or headline of the entry.
- **media_name**: The name of the media source associated with the entry.
- **publish_date**: The date when the entry was published.
- **stories_id**: ID related to stories (if applicable).
- **story_tags**: Tags or categories associated with the story.
- **Summary**: A brief summary or abstract of the entry.
- **Cleaned_Body**: Body text after text cleaning and preprocessing.
- **Cleaned_Title**: Title text after text cleaning and preprocessing.
- **collect_date_**: The date when the entry was collected or retrieved.
- **collect_year**: The year when the entry was collected.
- **collect_month**: The month when the entry was collected.
- **Cleaned_Body_sw**: Body text after text cleaning and removing stop words.
- **Cleaned_Title_sw**: Title text after text cleaning and removing stop words.
- **title_url**: Title that came with the URL extraction


### Source

This DataFrame is a combination of data downloaded from Media Cloud and data scraped manually. It represents a mix of curated content from Media Cloud URLs and scraped content gathered by the user.

### Usage

This DataFrame is structured to store information about various entries such as articles, stories, or content pieces. It includes details like the content itself (Body), title, associated URLs, publication date, media source, and additional cleaned/preprocessed versions of the text.

The DataFrame is organized with the following columns:

- **Text Data**: Columns such as 'Body' and 'Title' contain textual information related to the entries.
- **Metadata**: Columns like 'publish_date', 'media_name', 'stories_id', 'story_tags', 'collect_date_', 'collect_year', and 'collect_month' provide metadata information about each entry.
- **Cleaned Data**: Columns with names like 'Cleaned_Body', 'Cleaned_Title', 'Cleaned_Body_sw', and 'Cleaned_Title_sw' represent versions of text data after cleaning and processing, potentially including stop words removal.

This DataFrame can be used for various data analysis tasks related to text processing, content categorization, time-based analysis, and more.

---
