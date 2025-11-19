# enterprise-integration-examples
📦  Examples of enterprise integration patterns using IBM MQ, MFT, IIB, and Python automation scripts.
Enterprise Integration Examples (IBM MQ / MFT / IIB + Python)

This repository showcases practical examples, documentation, and demo workflows based on my experience as an Application Integration Support Engineer working with IBM MQ, IBM MFT, and IBM Integration Bus (IIB).
It also includes simplified Python automation scripts, integration patterns, and message flow diagrams.

## 🔧 Technologies Covered

IBM MQ
IBM MFT
IBM Integration Bus (IIB)
Message Queues & Integration Patterns
Python
REST APIs
Logging & Monitoring Automation


## 📁 Repository Structure
enterprise-integration-examples/
│
├── docs/
│   ├── MQ_Architecture.md
│   ├── MFT_Flow.md
│   ├── IIB_MessageFlow.md
│   └── Integration_UseCases.md
│
├── python-scripts/
│   ├── mq_publish.py
│   ├── mq_consume.py
│   ├── log_monitor.py
│   └── message_transform.py
│
├── sample-flows/
│   ├── OrderProcessingFlow.png
│   ├── FileTransferFlow.png
│   └── QueueToAPI.png
│
└── README.md

## 📘 What This Repository Demonstrates

1️⃣ IBM MQ Concepts — With Diagrams & Examples

Queue Manager

Local queues

Channels

PUB/SUB

DLQ (Dead Letter Queue)

Triggering

Message persistence

2️⃣ IBM IIB Message Flows (with diagrams)

MQ Input → Compute Node → MQ Output

MQ → REST API flow

File → MQ → Database pattern

3️⃣ IBM MFT File Transfer Workflows

Source → Agent → Queue → Target

Automatic retry & logging

Transfer error handling

4️⃣ Python Automation Scripts Included

Publish a message

Consume a message

Transform and log MQ messages

Monitor queue depth

Log file monitoring script

## 🚀 Why This Repo Exists

Inorder to demonstrate:

✔ Real integration experience
✔ Understanding of enterprise systems
✔ Ability to automate using Python
✔ Clear documentation


