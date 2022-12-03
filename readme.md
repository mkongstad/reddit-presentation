# Reddit Powerpoint Generator
A tool to generate a simple powerpoint containing images pulled from specified subreddit. 

The PowerPoint will contain a title page with a description, the file will be named the same as the title page appended
with the `.pptx` file extension, and the rest of the slides are going to contain
the image content of a post along with the post title.

**Example**
```python
poetry run python main.py 
    --subreddit redditpowerpointdemo 
    --limit 20 
    --title "Generating PowerPoints from subreddits" 
    --description "A guide on how to go through a lot of effort to avoid manually creating PowerPoint slides"
```

This will generate a PowerPoint of the subreddit https://www.reddit.com/r/RedditPowerpointDemo/.
