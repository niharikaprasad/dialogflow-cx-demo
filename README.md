# Customer Support Conversational Agent (Google CCAI / Dialogflow CX)

A demo Conversational AI bot built using **Google CCAI (Conversational Agents, formerly Dialogflow CX)**.  
Demonstrates **multi-intent handling, page-based routing, and AI-driven responses** for a customer support scenario.

---

## Overview

This agent showcases:  
- Handling multiple user intents  
- Routing conversations to different pages  
- Entry fulfillment responses for dynamic messaging  
- Conceptual exposure to **Google Agent Assist** and **Google Insights**

---

## Intents and Training Phrases

| Intent | Sample Training Phrases |
|--------|-----------------------|
| TrackOrder | Where is my order?, Track my order, Order status |
| ReturnItem | I want to return something, How do I return my order?, Return my product |
| TalkToAgent | I want to talk to a human, Connect me to support, Speak to an agent |

---

## Pages and Responses

| Page | Response |
|------|----------|
| OrderStatusPage | Sure! Please provide your order number. |
| ReturnPage | I can help you return your item. What’s the item name? |
| HumanAgentPage | Connecting you to a live agent… |

---

## How to Test / Demo

1. Open the agent in **Google Conversational Agents console** or import the `CustomerSupportBot.zip`.  
2. Navigate to **TEST & EVALUATE → Conversation History**.  
3. Type sample phrases:
   - "Where is my order?"  
   - "I want to return something"  
   - "Talk to human"  
4. Observe responses from each page.  

---

## Project Structure

- `CustomerSupportBot.zip` → Full exported agent  
- `screenshots/` → Images of flows and conversation history (optional)  
- `README.md` → This document  

---

## Skills Demonstrated

- Designing conversational AI workflows with **Dialogflow CX**  
- Creating intents, training phrases, and page-based routing  
- Configuring **Entry Fulfillment** responses to streamline conversation  
- Conceptual understanding of **Google Agent Assist** and **Insights**  
- Preparing a demo-ready agent for stakeholder review  

---

## Future Enhancements

- Integrate **Google Agent Assist** for live agent support  
- Implement **Google Info Bot** for knowledge retrieval  
- Extend flows for domain-specific scenarios (e.g., insurance or retail)  

