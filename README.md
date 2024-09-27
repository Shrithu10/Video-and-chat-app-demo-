
# ChatApplication
Spring boot websocket backend and reactjs client

Server:
    - Spring boot Websocket

Client
    - ReactJS

=======
# SecureLink: Privacy-Focused Communication Platform

SecureLink is a web-based communication platform designed to provide highly secure messaging, voice, and video calls. In an era of increasing data privacy concerns, many communication tools fail to offer adequate protection for user information. SecureLink tackles these challenges by integrating cutting-edge encryption technologies, message expiration, secure file sharing, and multi-factor authentication (MFA). Leveraging WebRTC for real-time video communication and the Spring framework for chat, SecureLink ensures a seamless and secure user experience across desktop platforms. This platform is designed for individuals and organizations that prioritize data security while seeking a reliable and intuitive communication solution.

## Team Members

- **Shritij Reddy**
- **Hanuth** 
- **Sathvik** 
- **Komal**

## Abstract

SecureLink is an all-in-one communication platform featuring the following key components:

- **End-to-End Encryption**: All messages, voice, and video calls are encrypted, ensuring that no unauthorized party can access user communications.
- **WebRTC Video Calls**: Facilitates high-quality, real-time video communication with fallback options to a media server when direct peer-to-peer connections fail.
- **Spring-Powered Chat**: Implements real-time chat functionality using the Spring framework, supporting encrypted messaging, secure file sharing, and chat history management.
- **Multi-Factor Authentication (MFA)**: Enhances user authentication security, significantly reducing the risk of unauthorized access.
- **Message Expiration**: Allows users to set a timer for message deletion, ensuring that sensitive information is not stored indefinitely.

## Problem Statement

### Theme: Privacy and Security in Digital Communication

With the rise of data breaches and unauthorized access incidents, the need for a secure communication platform has never been more critical. Existing communication tools often lack robust security features or present complexity that deters average users. SecureLink aims to bridge this gap by delivering a highly secure yet user-friendly communication platform that ensures privacy without compromising on usability.

## Proposed Solution

SecureLink is an all-in-one communication platform featuring robust security measures and user-friendly design:

- **End-to-End Encryption (E2EE)**: Ensures that all communications (text, voice, and video) are encrypted to prevent unauthorized access.
- **WebRTC Video Calls**: Enables real-time video communication with seamless fallback options for reliable connections.
- **Spring Framework**: Powers the chat functionality with support for encrypted messaging, secure file sharing, and message expiration.
- **Multi-Factor Authentication (MFA)**: Enhances user authentication security by requiring multiple forms of verification.
- **Message Expiration**: Allows users to set timers for message deletion, ensuring sensitive information is not retained longer than necessary.

## Architecture Overview

### Communication Architecture

#### Video and Voice Calls:

- **WebRTC**: SecureLink utilizes WebRTC (Web Real-Time Communication) for real-time video and voice communication. WebRTC provides browsers with Real-Time Communications (RTC) capabilities via simple APIs.
- **Media Server Fallback**: Uses a media server (based on Elixir) for relaying media streams securely in cases where peer-to-peer connections are not feasible.

#### Chat Messaging:

- **Spring Framework**: A robust backend framework in Java that powers the chat functionality. Supports RESTful APIs and WebSocket communication for real-time interactions.
- **Message Queue (e.g., RabbitMQ)**: Manages high-throughput messaging, ensuring efficient and reliable message delivery.
- **Database (e.g., PostgreSQL)**: Stores message data securely with encryption-at-rest and encryption-in-transit features enabled.

### Security Architecture

- **End-to-End Encryption (E2EE)**: Encrypts all data using AES-256 for data encryption and RSA-2048 for key exchange.
- **Public Key Infrastructure (PKI)**: Manages encryption keys securely, ensuring only intended recipients can decrypt communications.
- **Authentication & Access Control**: Implements Multi-Factor Authentication (MFA) for secure user authentication and authorization.
- **Encryption in Transit and At Rest**: Secures data transmission using TLS (Transport Layer Security) and encrypts data stored in databases.

### Frontend Architecture

- **React.js**: Developed using React.js for responsive and intuitive web interfaces.
- **WebRTC Integration**: Integrates WebRTC APIs directly for in-browser video and voice calls without additional plugins.

## Target Audience

SecureLink is designed for:

- **Individuals**: Users who prioritize privacy and secure communication in their personal and professional lives.
- **Businesses and Organizations**: Teams requiring secure communication channels for sharing sensitive information, especially in industries like finance, legal, and healthcare.

## Feasibility Analysis

The technical feasibility of SecureLink is high, leveraging mature technologies like WebRTC and Spring Framework, known for their stability and security. The development team possesses the necessary expertise to build secure, scalable applications. However, extensive testing and optimization are required, especially for security compliance and performance on desktop platforms.

## Implementation Plan

SecureLink is developed in phases to ensure comprehensive feature integration and security enhancements:

1. **Core Features Development**: Implementing end-to-end encryption, chat, and video calls.
2. **Security Enhancements**: Integrating multi-factor authentication, secure file sharing, and message expiration.
3. **UX/UI Improvements**: Enhancing user interface design and optimizing cross-platform performance.
4. **Testing and Deployment**: Conducting thorough testing and deploying the platform for desktop users.

## Submission Details

This document is a submission for the Ethos 2024 hackathon. Below are the details for submission:

- **Team Name**: bytebyte
- **Hackathon Theme**: Privacy and Security in Digital Communication
- **Submission Date**: 27th September 2024

![image](https://github.com/user-attachments/assets/c6fd2598-3e10-4f17-9189-3f64dbcacdf3)
>>>>>>> f6dd79b04061ba0f37ff666b2e2a4606771b1e51
