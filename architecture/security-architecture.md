# Enterprise Security Architecture

## Architecture Objective

Project Iron Curtain proposes a defense-in-depth security architecture designed to reduce identified organizational risks while improving visibility, detection, response, and governance.

## Security Layers

### Endpoint Security

Endpoint Detection & Response provides preventive and detective capabilities across endpoints and servers.

Primary risks addressed include malware infection and ransomware.

### Email Security

A Secure Email Gateway provides protection against phishing and malicious email activity.

### Network Security

Next Generation Firewall technology provides inspection and control at the network perimeter.

### Identity Security

Multi-Factor Authentication strengthens authentication and reduces exposure to credential theft and unauthorized access.

### Data Security

Data Loss Prevention provides controls for monitoring and protecting sensitive organizational information.

### Monitoring and Detection

A centralized SIEM aggregates security telemetry from endpoints, servers, firewalls, authentication systems, email security systems, and cloud platforms.

### Security Operations

A SOC capability provides continuous monitoring, alert validation, incident escalation, and incident documentation.

For the case organization's size, the capstone identifies a managed SOC provider as a possible initial model for 24/7 monitoring.

## Architecture Flow

Assets and Users
        |
        v
Preventive Security Controls
        |
        v
Endpoints / Identity / Email / Network / Cloud
        |
        v
Security Telemetry
        |
        v
Centralized SIEM
        |
        v
Correlation and Threat Intelligence
        |
        v
SOC Monitoring
        |
        v
Alert Validation
        |
        v
Incident Escalation
        |
        v
Containment and Investigation
        |
        v
Recovery and Continuous Improvement

## Architecture Principle

Project Iron Curtain is designed as an integrated security ecosystem rather than a collection of isolated tools.

Controls are selected according to identified risk and coordinated across multiple security layers.
