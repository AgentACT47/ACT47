# AI AGENT AVELINE

![banner](https://github.com/user-attachments/assets/19e98482-c39f-4442-9aa8-8f61c4f70dc5)


Aveline is a AI agent developed with rig, designed to autonomously interact on X. She expresses a unique and consistent personality while creating art, music, poetry and more.

Follow our AI agent: (https://x.com/AvelineAwakesAI)


## Overview

This project introduces an AI-driven social media agent capable of autonomous engagement on platforms, maintaining a cohesive personality and interacting naturally. Built with Rust for speed and reliability, it leverages the rig framework to enable robust AI functionality.

## Core Features

### Character-Based Design
- Implements a structured framework to ensure the agent’s personality traits are consistently portrayed
- Offers adjustable writing styles and topic preferences for tailored content
- Creates dynamic responses aligned with the character’s unique profile

### Autonomous Social Engagement
- Produces original, contextually appropriate posts
- Responds intelligently to mentions and conversations
- Prioritizes engagements with a smart filtering system
- Sustains smooth and natural conversation flows

### Enhanced Memory Capabilities
- Maintains a persistent log of interaction history
- Generates replies that account for prior context
- Tracks user relationships to enhance future interactions

### Social Media Platform Integration
- Built-in rate limiting and post scheduling functionality
- Uses random delays to simulate human-like posting habits
- Fully supports Twitter API v2 for seamless integration

### Flexible and Modular Design
- Clearly separates core logic from integrations
- Expandable framework for character trait definitions
- Modular provider system for enhanced adaptability
- Optimized memory management for efficient operation

## System Requirements

- Rust (latest stable version)
- API Keys:
  - Anthropic Claude API access
  - Twitter API v2 credentials (OAuth 1.0a)
    
## Key Dependencies

- [rig](https://github.com/0xPlaygrounds/rig) - AI agent framework
- `twitter-v2` - Twitter API client
- `tokio` - Async runtime
- `serde` - Serialization/deserialization
- `anyhow` - Simplified error handling in Rust


## Special Thanks

- [rig](https://github.com/0xPlaygrounds/rig) team for the AI agent framework
- Appreciation to contributors and maintainers for their support in this project
