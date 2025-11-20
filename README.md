
Customer Support Conversational Agent built with Google CCAI (Conversational Agents, formerly Dialogflow CX) demonstrating multi-intent handling, dynamic routing, and AI-driven responses.
# Customer Support Bot (Dialogflow CX)

## Overview
This is a simple conversational agent built using Google Dialogflow CX (new Conversational Agents).  
It demonstrates:
- Handling multiple user intents
- Routing to different pages
- Using Entry Fulfillment responses

## Intents and Training Phrases

| Intent | Sample Training Phrases |
|--------|-----------------------|
| TrackOrder | Where is my order?, Track my order, Order status |
| ReturnItem | I want to return something, How do I return my order?, Return my product |
| TalkToAgent | I want to talk to a human, Connect me to support, Speak to an agent |

## Pages and Responses

| Page | Response |
|------|----------|
| OrderStatusPage | Sure! Please provide your order number. |
| ReturnPage | I can help you return your item. What’s the item name? |
| HumanAgentPage | Connecting you to a live agent… |

## How to Test / Demo

1. Open the agent in the **Google Conversational Agents console** (or import the ZIP).  
2. Go to **TEST & EVALUATE → Conversation History**.  
3. Type phrases like:
   - "Where is my order?"
   - "I want to return something"
   - "Talk to human"
4. Observe the bot responses and routing.

## Notes
- Responses are configured only on pages to avoid duplicates.  
- Routes connect user intents to pages.  
- This bot is suitable for demo purposes to showcase Conversational AI skills.
