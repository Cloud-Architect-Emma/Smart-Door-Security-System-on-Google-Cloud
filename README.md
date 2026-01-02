# Project Overview

This repository contains the solution architecture and design documentation for a Cloud-Native Smart Door Security System built on Google Cloud Platform. The project demonstrates an end-to-end IoT security solution with real-time video/audio, biometric access control, and event-driven cloud processing.

## Key Features

Smart door with camera, audio, and sensors

Face and fingerprint biometric unlocking

Two-way audio/video communication

Remote unlock with MFA

Threat detection and alarm triggering

Event-driven architecture using Pub/Sub

Secure cloud-native backend on GCP

GDPR-compliant data retention

## Architecture Summary

Device Layer: Camera, sensors, biometrics, lock

Ingestion: HTTPS → Pub/Sub

Processing: Cloud Run

Storage: Cloud Storage (media), Firestore (metadata)

Notifications: Firebase Cloud Messaging

Client: Mobile application


![Architecture-Flow](architecture/architecture-diagram-(6).gif).

## Technology Stack

Google Cloud Pub/Sub

Google Cloud Run

Google Cloud Storage

Firestore

Firebase Authentication

Firebase Cloud Messaging

HTTPS (TLS-secured APIs)

Security Highlights

Zero Trust design

Edge-based biometric matching

No cloud storage of biometric data

TLS encryption in transit

IAM least privilege access

Compliance

GDPR-compliant data handling

Configurable data retention (3 / 6 months)

Full audit logging

## Use Cases

Smart home security

Gated residential access

Smart apartment systems

IoT security architecture demonstration

Who This Project Is For

Cloud Solutions Architects

IoT Architects

Security Engineers

Smart home system designers

Status

This project is architecture-focused and intended for learning, portfolio demonstration, and interview discussions.

#### License

MIT License

**Project by Emmanuela.**
