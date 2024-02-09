# ContentGen: Automated YouTube Shorts Content Generation

## Overview
ContentGen is a comprehensive project that automates the generation of content for YouTube Shorts by sourcing from various platforms like TikTok and Reddit. It leverages cutting-edge technologies and serverless cloud services to identify popular videos and images, download them, generate engaging commentary, and post them on YouTube Shorts. The entire workflow is designed to be scalable, efficient, and easy to maintain.

## Project Structure
ContentGen consists of two main components, each responsible for a distinct source of content:

1. **TikTok to YouTube Shorts Automation**: This component focuses on identifying and processing popular TikTok videos. It includes features for video identification, download, analysis, commentary generation, subtitle addition, and posting to YouTube Shorts.

2. **Reddit to YouTube Shorts Automation**: This component specializes in scraping Reddit for posts containing videos and images. It employs Selenium for web scraping, ensuring compatibility with dynamic website elements. Like the TikTok component, it handles video and image download, analysis, commentary creation, subtitle addition, and posting to YouTube Shorts.

## Core Technologies
ContentGen utilizes a variety of technologies to deliver a seamless content generation pipeline:

- **Python**: The core programming language for scripting and automation.
- **Google Cloud Platform (GCP) Services**: Provides serverless infrastructure for orchestrating workflows, running containers, messaging, storage, and vision APIs.
- **ImageAI and OpenCV**: Powerful tools for analyzing and editing videos and images.
- **MoviePy**: An advanced video editing library for adding subtitles and commentary.
- **NLP Libraries**: Employed for generating human-like commentary.
- **Selenium**: A web scraping tool for interacting with Reddit's dynamic website elements.

## Usage
To use ContentGen, configure the system to periodically fetch popular content from TikTok and Reddit. Once the content is processed and posted to YouTube Shorts, you can access the platform to view the generated videos with autogenrated commentary.

## Contributing
Contributions to ContentGen are welcome. Whether it's improving the codebase, adding new features, or fixing bugs, your contributions can help enhance the project's capabilities.

## License
ContentGen is distributed under the MIT License. See `LICENSE` for more information.
