# micro-invest-robo-AI-advisor

## Overview   
A micro-investment platform that enables users to start investing with small amounts using AI-based portfolio recommendations and it also 
help in auto payment select option on a fixed date every month/week expenses.

## Problem
- High entry barriers in traditional investment.  
- Lack of affordable, personalized advice.  
- Complexity of financial markets for beginners.  

## Solution
- Enables micro-investments (₹100+).  
- AI-driven personalized portfolio suggestions.  
- Real-time analytics and performance tracking.  

## Architecture Diagram

flowchart TD
    User[Mobile / Web App] --> API[Backend - Spring Boot]
    API --> DB[(Database)]
    API --> AI[AI Engine]
    API --> Broker[External Investment APIs]


# Tech Stack

  **Language/Frameworks:** Java 21, Spring Boot
  **Database:** PostgreSQL
  **AI/ML:** Python (scikit-learn, PyTorch)
  **Messaging:** Kafka
  **Tools:** Postman, GitHub Actions

# Roadmap
**Week 1:** Repo setup, documentation
**Week 2–3:** Backend API skeleton + DB schema
**Week 4:** AI model prototype
**Week 5:** Kafka event handling
**Week 6:** Documentation + polish
