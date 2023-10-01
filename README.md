# YouTube-Video-Summariser

A chrome extension to summarise long YouTube videos by utilising YouTube's transcript feature.

## Requirements

- The following python modules must be installed to run the API
  - `flask`
  - `youtube-transcript-api`
  - `transformers`

## Instructions

- Run `app.py` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.

## Some Snapshots

<div style="display: flex;">
    <div style="flex: 50%; padding: 10px;">
        <img src="demo/image-1.png" alt="Image 1" style="max-width: 100%; height: auto;">
    </div>
    <div style="flex: 50%; padding: 10px;">
        <img src="demo/image-2.png" alt="Image 2" style="max-width: 100%; height: auto;">
    </div>
</div>

![summarised output](demo\image-3.png)
