---
title: Send and Receive Images
navigation_weight: 4
---

# Send and Receive Images

## Overview

This guide covers sending and receiving images within a conversation.

Before you begin, make sure you [added the SDK to your app](/client-sdk/setup/add-sdk-to-your-app) and you are able to [create a conversation](/client-sdk/in-app-messaging/guides/simple-conversation).

```partial
source: _partials/client-sdk/messaging/chat-app-tutorial-note.md
```

This guide will make use of the following concepts:

- **Conversation Events** - `image` events that fire on a Conversation, after you are a Member

## Send an Image

Given a conversation you are already a member of:

```tabbed_content
source: _tutorials_tabbed_content/client-sdk/guides/messaging/send-images
```

## Receive an Image

A `image` conversation event will be received when a member sends an image to a conversation:

```tabbed_content
source: _tutorials_tabbed_content/client-sdk/guides/messaging/receive-images
```
