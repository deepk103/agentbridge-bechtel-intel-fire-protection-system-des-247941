# Architecture Documentation

## Overview
This Chain-of-Thought implements Bechtel-Intel Fire Protection System Design: Supplier Selection & Self-Maintenance Fire Alarms for automation use cases.

## Components
1. **Webhook Trigger**: Workflow step 1
2. **Manual Trigger**: Workflow step 2
3. **AI Agent - Requirements Intake**: Workflow step 3
4. **AI Agent - System Design & Architecture**: Workflow step 4
5. **AI Agent - Supplier Shortlist & Evaluation Matrix**: Workflow step 5
6. **AI Agent - Self-Maintenance SOPs & Checklists**: Workflow step 6
7. **AI Agent - Final Consolidated Deliverable**: Workflow step 7
8. **Route by HTTP Method**: Workflow step 8
9. **Return GET Acknowledgment**: Workflow step 9
10. **Transform Input**: Workflow step 10
11. **Workflow Configuration**: Workflow step 11
12. **Mock Mode?**: Workflow step 12
13. **Generate Mock Data**: Workflow step 13
14. **Prepare Response Payload**: Workflow step 14
15. **Overview**: Workflow step 15
16. **Meta**: Workflow step 16
17. **AWS Bedrock Chat Model**: Workflow step 17
18. **Simple Memory**: Workflow step 18

## Data Flow
- Input: Manual trigger
- Processing: 18 sequential steps
- Output: Final result
