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

<table style="width:100%;">
  <tr>
    <td><img src="demo/image-1.png" alt="Image 1" style="max-width: 100%; height: auto;"></td>
    <td><img src="demo/image-2.png" alt="Image 2" style="max-width: 100%; height: auto;"></td>
  </tr>
  <tr>
    <td colspan="2"><img src="demo/image-3.png" alt="Image 3" style="max-width: 100%; height: auto;"></td>
  </tr>
</table>
