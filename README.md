# Multi-Channel AI Content Automation & Distribution

## Problem
Posting content manually across multiple social platforms is time-consuming, inconsistent, and difficult to scale.

## Solution
An AI-powered automation that generates and distributes optimized content across multiple social media channels from a single input.

## Automation Logic
- Content is submitted via webhook
- OpenAI generates platform-specific copy
- Router distributes content to each channel
- Each platform receives tailored formatting and tone
- Disabled channels are safely ignored

## Platforms Supported
- Facebook Pages
- Instagram for Business
- LinkedIn
- Pinterest
- Tumblr
- X (Twitter – deprecated)

## Tools Used
- Make.com
- OpenAI (ChatGPT)
- Facebook Pages API
- Instagram for Business API
- LinkedIn API
- Pinterest API
- Webhooks & HTTP modules

## Outcome
- One input → multi-platform distribution
- Consistent brand voice with platform optimization
- Reduced posting time from hours to seconds
- Scalable for agencies and content teams

## Screenshots
![Automation Workflow](screenshots/social-media-automation.png)

## Notes
Client credentials and sensitive data have been removed.
