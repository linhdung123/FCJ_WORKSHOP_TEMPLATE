---
title: "Event 4"
date: 2026-06-27
weight: 4
chapter: false
pre: " <b> 4.4. </b> "
---

# Event Report: “FCAJ Community Day”

### Purpose of the Event
- Exploring IT career development, the impact of AI on software engineering, and cloud infrastructure solutions provided by Cloud Thinker.
- Understanding how to build Voice AI assistants, their real-world applications, and techniques for processing the Vietnamese language.
- Introducing the AWS DevOps Agent solution for automating incident response and system operations.
- Solving Human Resources (HR) challenges using Amazon Q.
- Learning how to establish secure internal connectivity between Amazon Q and third-party systems through an MCP Server.

### Speakers
- **Steve Tran** - Founder, Cloud Thinker
- **Hieu Nghi** - AI Engineer, Renova Cloud
- **Kiet Tran** - AI Engineer, AWS Student Builder Group
- **Trung Vu** - CEO, Revve AI
- **Bao Phan and Nguyen Nguyen** - Cloud Engineers, Cloud Kinetics
- **Truong Tran and Anh Dang** - Solution Architects, Cloud Kinetics
- **Toan Nguyen and Hieu Nghi** - Senior Business Systems Analysts, VPBank

### Key Highlights

### The IT Job Market
- AI is significantly accelerating software development, changing hiring demands for software developers. However, highly skilled Cloud Engineers who can operate and troubleshoot large-scale cloud infrastructure remain in strong demand.

### AI Agent Architecture
- The session compared Single-Agent and Multi-Agent architectures. Multi-Agent systems, where each agent specializes in a specific task, provide better context management, Role-Based Access Control (RBAC), and cost optimization.

### Voice AI Architecture
- A typical Voice AI system follows a three-stage pipeline: converting speech into text (Speech-to-Text), processing the request using a Large Language Model (LLM), and converting the generated response back into speech (Text-to-Speech).

### Processing Low-Resource Languages such as Vietnamese
- Since Vietnamese lacks sufficient training data for high-quality Speech-to-Speech models, combining Speech-to-Text, LLM reasoning, and Text-to-Speech produces better contextual understanding and more reliable tool calling, such as securely locking a bank card.

### Building Natural Conversations
- To make Voice AI interact naturally like humans, the system should recognize the user's gender to use appropriate pronouns, detect when users have finished speaking before responding, and understand different regional Vietnamese accents.

### Automated Incident Response
- AI agents can classify incidents, investigate root causes by generating hypotheses, recommend mitigation plans, and suggest long-term system improvements. During the demonstration, the agent automatically detected a DDoS attack, identified abnormal system overload, and generated terminal commands to mitigate the issue.

### HR Challenges
- HR departments often struggle with manually screening resumes, subjective candidate evaluations, and potential data leakage when uploading candidate information to public AI services.

### AI in Recruitment
- Amazon Q can automate resume analysis, identify candidates' strengths and weaknesses, compare resumes against Job Descriptions (JD), and generate evaluation scores, helping organizations speed up recruitment while reducing manual effort.

### Enterprise Security Requirements
- When integrating Amazon Q with third-party applications such as Jira, WhatsApp, or Zalo, communication should be routed through an MCP Server. Enterprises also require that sensitive data never traverse the public Internet.

### What I Learned
- If you have a good idea, start building it immediately instead of postponing it.
- Launch prototypes early to gain practical experience and user feedback.
- Choose flexible architectures for low-resource languages. For Vietnamese, a three-stage architecture (Speech-to-Text → LLM → Text-to-Speech) is more practical and reliable than direct Speech-to-Speech models.
- Humans remain the final decision-makers, while AI serves as a tool to enhance engineers' productivity rather than replace them.

### Lessons Learned
- **Protect AI Communication Channels:** When connecting internal AI platforms such as Amazon Q to third-party applications through an MCP Server, organizations should avoid using the public Internet. Instead, these services should be deployed within private subnets and connected through Amazon VPC networking to reduce the risk of DDoS attacks and Man-in-the-Middle (MITM) attacks while ensuring secure communication.

#### Some Photos from the Event
* Add your event photos here.

![overview](images/4-EventParticipadted/4.4-Event4/image.png)

![overview](images/4-EventParticipadted/4.4-Event4/image1.png)

> Overall, this event provided not only valuable technical knowledge but also broadened my understanding of AI system architecture, cloud infrastructure operations, enterprise security, and modern software engineering practices. It also strengthened my ability to think from both technical and business perspectives when designing AI-powered cloud solutions.