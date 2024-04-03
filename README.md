# Project: WTO Publications Sovereignty Threat Analysis using GPT-4

## Overview

This project employs OpenAI's GPT-4 model to analyze publications on the World Trade Organization (WTO) website, focusing on detecting any implications of a potential threat to US sovereignty. By processing textual content from the WTO publications, the model assesses the sentiment and implications of these documents concerning the United States.

## Objective

The primary goal is to understand the stance of WTO publications regarding the United States. This analysis aims to detect sentiments that might imply dissatisfaction, complaints, criticism, or suggest the changes within the United States. By systematically evaluating the content, we seek to gain insights into how the WTO's communications might reflect on US policies and global standing.

## Methodology

The GPT-4 model is tasked with examining the text of each publication for specific sentiment markers. The analysis is structured around four key questions, designed to ascertain the publication's tone and implications regarding the United States:

1. **Is there an expression of disappointment with the United States?**
2. **Does the article relay complaints about the United States from other countries?**
3. **Is there criticism of the United States coming directly from the WTO?**
4. **Does the article suggest that there is a need for policy change within the United States?**

Based on the text content, GPT-4 will respond to each question with a binary "yes" or "no," populating the following keys accordingly:

- `isDisappointment`: Indicates whether the article shows disappointment towards the United States.
- `isComplain`: Reflects whether the article contains complaints about the United States from other countries.
- `isCritic`: Identifies if the article contains criticism of the United States directly from the WTO.
- `isAffect`: Determines whether the article implies a need for policy change within the United States.

These keys are designed to distill the sentiment of the publications into actionable insights, guiding the analysis towards understanding the potential sovereignty threats against the US as depicted by WTO communications.
