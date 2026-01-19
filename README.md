# Real-Time Slack Operations

## 🌟 Overview
**Scenario**<br/>
ChatOpsBot is a lightweight DevOps automation assistant that brings AWS operations directly into Slack. Traditionally, engineers respond to issues by jumping between the AWS Console, CloudWatch, and various dashboards ,slowing down incident response.

With ChatOpsBot, teams get **real-time alerts in Slack**, and can **trigger fixes like restarting a Lambda or checking logs**, without leaving the chat interface.

This system uses AWS Chatbot, CloudWatch, Lambda, IAM, and CloudFormation to build a secure, automated operations workflow, and fully aligns with the **Operational Excellence Pillar** of the AWS Well-Architected Framework.

**Your Role**<br/>
In this project, you’ll take on the role of a **Solutions Architect focused on operational excellence**. Your goal is to build a system that connects alerts to your team’s daily tools and enables secure, real-time response via chat.

You’ll integrate Slack with AWS services to enable **automated, auditable, and permission-controlled actions**, improving visibility and reducing mean time to recovery.
## 🛠️ Services used
* **AWS Chatbot**: Connect Slack to AWS
* **Amazon CloudWatch**: Alarms for system health
* **AWS Lambda / SSM**: Run automated fixes
* **Amazon EventBridge**: Route events to Chatbot
* **AWS IAM**: Secure who can run what
* **AWS CloudFormation**: Infrastructure + frontend deployment
* **Amazon S3 + CloudFront**: Host optional dashboard

## ☁️ AWS Architecture

## &rarr; Final Result

<!-- ![alt text](design/igw.png) -->
