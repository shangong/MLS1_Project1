# MLS1_Project1
So I'm working on a 


## Problem Statement: Support Ticket Analysis

### Description

#### Business Context
ShopNest Global is a large-scale e-commerce platform operating across 30+ countries, serving over 50 million active customers and employing 2,000+ human support agents who run 24/7 across the US, Europe, India, and Southeast Asia, across product categories including electronics, fashion, groceries, and home appliances. ShopNest processes over 200,000 orders per day. With every order comes the possibility of a delivery delay, a payment failure, a wrong item, or a return request. Customers reach out to the support team through tickets to report these issues and expect a fast, accurate resolution.

Every order carries a risk of delivery delays, payment failures, wrong items, and returns, all of which generate support tickets. These tickets are written in highly unstructured ways: some are overloaded with background details where the real issue is buried, others use abbreviations, shorthand, and order codes that are hard to interpret, and some contain so little information that the issue is unclear. As a result:

- Human agents spend the first 2–3 minutes on each ticket just trying to decode what the customer is asking before any resolution work can begin.
- During peak periods (sales, holidays, logistics disruptions), daily ticket volume can spike from ~5,000 to ~15,000, multiplying this inefficiency. High volume and inconsistent ticket content contribute to human agent fatigue and higher error rates when accuracy is most critical.
- Drafting responses is manual, slow, and inconsistent in tone and clarity across human agents, leading to suboptimal customer experiences.

#### Objective
The objective is to build a POC of an AI-powered ticket intelligence system for the customer support operations of ShopNest Global that:

Reads incoming customer support tickets in their raw, unstructured form - including overloaded, jargon-filled, and incomplete submissions - and produces a clean, concise summary that gives the support agent an accurate understanding of the customer's issue on first read.
Generates a professional, empathetic response to the customer that acknowledges their issue and communicates a clear next step, enabling human agents to have a draft response with consistent response quality for their review.
Evaluates both the generated summary and the generated response automatically using an LLM-as-a-Judge framework, scoring each output against task-specific criteria to ensure quality is measurable, consistent, and auditable at every stage of the pipeline.
The end goal is to demonstrate that AI-assisted summarisation, response generation, and automated evaluation can meaningfully improve the consistency and quality of customer support operations at scale, sufficient to justify broader adoption across ShopNest's global support teams.

Data Dictionary
The data contains the different attributes of the various products and stores.

support_ticket_id: Unique identifier of the support ticket
support_ticket_desc: Description of the support ticket
Choosing Your Track
The project is available under multiple learning tracks, so you can build toward the role you actually aspire to be in. Here's a quick guide to help you pick the path that fits your career aspirations.


# 🚀 MLS1 Project 1 — Support Ticket Analysis

## 🎓 Program Overview

I am currently pursuing the **Post Graduate Program in AI Agents and Generative AI for Business Applications** offered by
[The University of Texas Austin](https://www.mccombs.utexas.edu/).

Program Details: [Post Graduate Program in AI Agents and Generative AI for Business Applications](https://onlineexeced.mccombs.utexas.edu/post-graduate-program-in-ai-agents-and-generative-ai-for-business-applications?id=f002658d-b536-4fa9-a76e-7ba517122c7e&utm_source=lc_email&utm_medium=ut-aiga-intl&utm_campaign=USCan_lead_pde_msg_1)

This repository/documentation represents **Project 1 (MLS1_Project1)** of the program.

## 📌 Project Title - Support Ticket Analysis using AI & Generative AI

### 🏢 Business Context

#### About ShopNest Global

**ShopNest Global** is a large-scale e-commerce platform operating across:
- 🌍 30+ countries
- 👥 50+ million active customers
- 🧑‍💼 2,000+ support agents
- 🕒 24/7 customer support operations

The company handles over:
- 📦 200,000+ orders per day
across multiple product categories such as:
- Electronics
- Fashion
- Groceries
- Home Appliances

#### ⚠️ The Challenge
With massive order volumes, customer support tickets are generated continuously for issues such as:
- 🚚 Delivery delays
- 💳 Payment failures
- 📦 Wrong items received
- 🔄 Return requests


However, these tickets are often:
- Highly unstructured
- Filled with jargon and abbreviations
- Overloaded with unnecessary details
- Missing critical information

This creates several operational challenges:

#### 🔍 Key Pain Points
- **⏳ Time Wasted Understanding Tickets** - Support agents spend 2–3 minutes per ticket simply trying to understand the actual issue before they can begin resolving it.
- **📈 Ticket Volume Spikes** - During:
  - Holiday seasons
  - Flash sales
  - Logistics disruptions


daily ticket volume can increase from: ~5,000 tickets/day to  ~15,000 tickets/day


This significantly increases:
- Agent fatigue
- Response delays
- Human error rates


#### ✍️ Inconsistent Customer Responses

Customer replies are manually drafted, leading to:

Inconsistent tone
Variable quality
Slow response times
Poor customer experience
🎯 Project Objective

The goal of this project is to build a Proof of Concept (POC) for an:

🤖 AI-Powered Ticket Intelligence System

The system is designed to assist customer support operations by leveraging LLMs (Large Language Models) and Generative AI.

🧠 Core Capabilities
1️⃣ Intelligent Ticket Summarization

The system should:

Read raw and unstructured customer support tickets
Understand overloaded or incomplete submissions
Extract the real customer issue
Generate a clear and concise summary

✅ Outcome:
Support agents can understand the issue immediately on first read.

2️⃣ AI-Generated Customer Responses

The solution should automatically generate:

Professional responses
Empathetic communication
Clear next steps for customers

✅ Outcome:
Human agents receive a high-quality draft response for quick review and approval.

3️⃣ Automated Evaluation using LLM-as-a-Judge

The generated outputs will be evaluated automatically using an:

🧪 LLM-as-a-Judge Framework

The framework scores:

Ticket summaries
Customer responses

based on:

Accuracy
Clarity
Relevance
Tone
Completeness

✅ Outcome:
Quality becomes:

Measurable
Consistent
Auditable
🌟 Expected Business Impact

The project aims to demonstrate that AI-assisted:

Ticket summarization
Response generation
Automated quality evaluation

can significantly improve:

⚡ Operational efficiency
🎯 Response consistency
😊 Customer satisfaction
📉 Agent workload

ultimately supporting large-scale adoption across ShopNest Global’s customer support operations.

📊 Data Dictionary
Column Name	Description
support_ticket_id	Unique identifier for each support ticket
support_ticket_desc	Raw textual description submitted by the customer
🛤️ Choosing Your Learning Track

This project is available under multiple learning tracks, allowing participants to align their work with their intended career path and specialization areas within AI and Generative AI.

🧰 Technologies & Concepts Involved
Generative AI
Large Language Models (LLMs)
Prompt Engineering
AI-based Text Summarization
Response Generation
LLM Evaluation Frameworks
NLP (Natural Language Processing)
AI-assisted Customer Support
📚 Project Repository
MLS1_Project1/
│
├── data/
├── notebooks/
├── src/
├── outputs/
├── README.md
└── requirements.txt
✅ Project Goal Summary

Build an AI-driven support ticket intelligence system capable of:

Understanding messy customer tickets
Summarizing issues clearly
Generating professional responses
Automatically evaluating response quality

while improving efficiency and consistency in large-scale customer support operations.

🙌 Final Note

This project showcases how Generative AI and LLM-powered workflows can transform modern customer support systems by enabling faster, smarter, and more scalable service operations.