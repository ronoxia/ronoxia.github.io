---
layout: page
title: Work Samples
permalink: /work-samples.html
---

# E-Commerce Integration Case Study
## The Last Bookstore - System Architecture & Stakeholder Management

*A technical communication and project management work sample demonstrating API integration strategy, legacy system analysis, and professional stakeholder coordination.*

---

### Project Context
**Client**: The Last Bookstore LLC, Los Angeles  
**Role**: Systems Integration Consultant  
**Challenge**: Integrate Ingram Content Group's 12+ million title database with Wix e-commerce platform  
**Timeline**: 3 months (June - August 2024)

### Technical Challenge

The Last Bookstore needed to consolidate multiple e-commerce platforms (Amazon, eBay, proprietary website) into a single Wix-based solution with real-time access to Ingram's complete book catalog. The integration required navigating legacy systems, modern web development practices, and complex stakeholder relationships.

**Key Technical Decisions:**
- **API Architecture**: FTP vs. Web Service integration analysis
- **Legacy System Navigation**: SOAP to REST migration strategy  
- **Database Design**: Balancing real-time data access with maintenance overhead
- **Cost Optimization**: Usage-based pricing model analysis

---

### Professional Communication Samples

*The following excerpts demonstrate technical explanation, stakeholder management, and project scoping skills.*

#### **Technical Architecture Explanation**
*Email excerpt: Explaining database architecture to non-technical stakeholders*

> "I know this is very confusing to anyone who hasn't spent time studying it. Bear with me... The reason the database is split up by Ingram or others is by design. In Ingram's case, inventory data is updated much more frequently than other product data, and it is smaller, so it makes sense to split up so that the large chunk of product data doesn't need to be refreshed or updated along with the inventory each time inventory is updated."

**Analysis**: Demonstrates ability to break down complex technical concepts using clear analogies and business logic.

#### **Modern Development Advocacy**
*Email excerpt: Technical recommendation with industry context*

> "The reason being - I will be using REST queries to make API calls rather than SOAP queries. I received sample SOAP queries type 1, 5 and 9. SOAP has not been widely used and replaced by REST since 2010."

**Analysis**: Shows technical leadership by advocating for modern development practices and explaining the rationale.

#### **Scope and Constraint Management**
*Email excerpt: Professional project transition*

> "Upon careful consideration, I realize I won't be able to deliver the implementation as initially discussed. With school and other responsibilities beginning in two months, my availability will be significantly limited. I sincerely apologize for any inconvenience this may cause."

**Analysis**: Demonstrates professional communication when recognizing project constraints, with clear handoff documentation provided.

---

### Technical Deep Dive

**Integration Strategy Analysis:**

| Approach | Data Volume | Update Frequency | Maintenance | Cost Model |
|----------|-------------|------------------|-------------|------------|
| **FTP Method** | 12M+ titles (4GB+) | Inventory: 6x daily<br>Bibliographic: Weekly | High - Database management required | Fixed monthly fee |
| **Web Service** | On-demand queries | Real-time | Low - Ingram maintains backend | Usage-based (per API call) |

**Recommendation**: Web Service for initial implementation due to lower maintenance overhead and scalable cost structure.

**Key Technical Insights:**
- Identified inventory vs. bibliographic data separation rationale
- Analyzed caching strategies for performance optimization  
- Evaluated database hosting requirements (cloud vs. local)
- Assessed ongoing technical support needs

---

### Stakeholder Coordination

**Multi-party Communication:**
- **Ingram Data Services**: Technical requirements and API documentation
- **Ingram Micro**: Account validation and service differentiation
- **Client (Josh & Jenna)**: Business requirements and budget constraints
- **End Users**: E-commerce experience optimization

**Key Challenge**: Coordinating between technical complexity, business constraints, and realistic timeline expectations.

---

### Project Outcome & Learning

**Deliverables Completed:**
- Comprehensive technical architecture documentation
- Ingram API integration research and testing setup
- Website audit and improvement recommendations
- Clear project handoff documentation for future developers

**Key Insight**: Sometimes the most valuable deliverable is honest assessment of project feasibility and clear documentation for future implementation.

**Professional Growth**: Enhanced ability to communicate technical concepts to non-technical stakeholders and manage scope constraints proactively.

---

### Client Feedback

*"I am continually astonished at how well you can communicate in English despite your multiple challenges... Thank you for the document of the groundwork laid out so far."* - Josh Spencer, Owner

---

**Complete Email Documentation**: Available upon request  
**Project Handoff Document**: [View technical overview →](https://docs.google.com/document/d/e/2PACX-1vQI40V3qGc-2-ZOSeMmWyebHXIeYYyH96kWU3YsuuU1z5Xvbo9gUl2r333SIYYqC2pX5qwNSfQ98ZDN/pub)