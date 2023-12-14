# YouTube Comments Analyzer 📈

![demo_gif](https://github.com/Krittaprot/youtube-comments-analyzer/assets/130896641/ab29576d-90a5-40cc-8556-9d3f94bed4fe)

Access the application demo here: [https://huggingface.co/spaces/Krittaprot/YT-comments-analyzer-demo](url)

The app takes in your YouTube video link as input, pull comments data from YouTube API, pre-process it for sentiment analysis (labelling if a comment is positive, neutral, or negative), then the processed data is visualized via the Gradio interface.

Key Features:
1) Sentiment Analysis: Utilizes the transformers pipeline for sentiment analysis, accurately categorizing comments as positive, negative, or neutral.
2) YouTube API Integration: Efficiently extracts comments from YouTube videos using the youtube-search-python library, integrated API usage with data extraction.
3) Data Processing and Visualization: Implements pandas and matplotlib for data handling and visualization, transforming raw data into meaningful insights.
4) Word Cloud Generation: Creates visually appealing word clouds to represent the most frequent words in comments.
5) Gradio Interface: Offers an interactive and user-friendly web interface, making the tool accessible to a wide range of users.

For more details on the app development process, read here: (placeholder for the medium article link)

# License

MIT License

Copyright (c) 2023 Krittaprot Tangkittikun
