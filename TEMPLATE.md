---
title: ESP_NOW Two Way Communication Tutorial
date: 2025-05-19
authors:
  - name: Keng-Lien Lin
---

<img width="1266" alt="Screenshot 2025-05-19 at 11 11 28 PM" src="https://github.com/user-attachments/assets/3845e0b0-119c-473a-9e08-e551bdfeee83" />

## Introduction

In this tutorial, you’ll learn how to establish two‑way ESP‑NOW communication between multiple ESP32 boards. Rather than relying on a router (Wi‑Fi) or dealing with Bluetooth’s limited range and latency, ESP‑NOW offers a lightweight, peer‑to‑peer protocol capable of sending up to 250 bytes per packet. By the end, you’ll have a reliable, low‑latency link between your ESP32s for seamless data exchange.

### Learning Objectives

By following this guide, you will:

- Understand the fundamentals of ESP‑NOW and how it compares to Wi‑Fi and Bluetooth

- Discover how to retrieve and use ESP32 MAC addresses for peer setup

- Configure ESP‑NOW peers for one‑to‑one and broadcast messaging

- Implement send and receive callbacks to handle incoming data

- Test and troubleshoot two‑way data transfer on multiple boards

### Background Information

**What is ESP‑NOW?**

ESP‑NOW is a proprietary, connectionless wireless protocol developed by Espressif that allows direct, low‑power communication between ESP32 devices. It bypasses the Wi‑Fi stack, reducing overhead and latency, and doesn’t require a network or access point.

**Why use ESP‑NOW?**

- Low latency & power: Ideal for battery‑powered sensors and real‑time controls

- Simple peer setup: Direct MAC‑addressed messaging without DHCP or security keys

- 250‑byte payloads: Sufficient for most sensor readings, commands, and small data packets

**Alternatives**

- Wi‑Fi: High throughput but dependent on routers and networks

- Bluetooth: Good for short‑range but adds pairing complexity and can introduce latency

---

## Getting Started

For any software prerequisites, write a simple excerpt on each
technology the participant will be expecting to download and install.
Aim to demystify the technologies being used and explain any design
decisions that were taken. Walk through the installation processes
in detail. Be aware of any operating system differences.
For hardware prerequisites, list all the necessary components that
the participant will receive. A table showing component names and
quantities should suffice. Link any reference sheets or guides that
the participant may need.
The following are stylistic examples of possible prerequisites,
customize these for each workshop.

### Required Downloads and Installations

List any required downloads and installations here.
Make sure to include tutorials on how to install them.
You can either make your own tutorials or include a link to them.

### Required Components

List your required hardware components and the quantities here.

| Component Name | Quanitity |
| -------------- | --------- |
|                |           |
|                |           |

### Required Tools and Equipment

List any tools and equipment you need here.
(Ex, computer, soldering station, etc.)

## Part 01: Name

### Introduction

Briefly introduce what  you are teaching in this section.

### Objective

- List the learning objectives of this section

### Background Information

Give a brief explanation of the technical skills learned/needed
in this challenge. There is no need to go into detail as a
separation document should be prepared to explain more in depth
about the technical skills

### Components

- List the components needed in this challenge

### Instructional

Teach the contents of this section

## Example

### Introduction

Introduce the example that you are showing here.

### Example

Present the example here. Include visuals to help better understanding

### Analysis

Explain how the example used your tutorial topic. Give in-depth analysis of each part and show your understanding of the tutorial topic

## Additional Resources

### Useful links

List any sources you used, documentation, helpful examples, similar projects etc.
