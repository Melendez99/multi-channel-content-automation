#System Architecture Overview

This automation is designed to distribute AI-generated content across multiple social media platforms from a single trigger.

## Flow Overview
1. Webhook receives new content input
2. HTTP modules retrieve or enrich campaign data
3. OpenAI generates platform-specific variations
4. Router sends content to individual social platforms
5. Each platform receives optimized formatting and tone

## Key Design Decisions
- Router-based distribution for scalability
- Platform-specific AI prompts to avoid duplicate content penalties
- Safe ignore paths for disabled or deprecated channels
- Stateless execution for high reliability

## Platforms Supported
- Facebook Pages
- Instagram for Business
- LinkedIn
- Pinterest
- Tumblr
- X (Twitter – deprecated)
