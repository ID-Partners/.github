# ID Partners Git Repo

Welcome to the official GitHub organization for ID Partners. This repository serves as a collection of tools, utilities, and resources that we have created and shared with the broader identity community.

## Who We Are

ID Partners is a professional services organization, supported by Ping Identity, and founded to offer organizations a modern approach to building their identity capabilities. We specialize in:
	•	Digital Identity
	•	Trust Ecosystems
	•	Complex Authorization

We believe your engagement with customers, partners, or employees is fundamentally dependent on a strong identity foundation. Whether you’re looking to build modern digital journeys for your customers, enhance cybersecurity, or reduce fraud, our goal is to provide expertise and tools to help you succeed.

## Ping Identity Partnership

We are proud to be a Ping Identity Partner, leveraging Ping’s enterprise-grade identity solutions to help organizations:
	•	Strengthen their Customer Identity & Access Management (CIAM) platforms
	•	Bolster authentication and authorization mechanisms
	•	Secure digital interactions while improving user experiences

## Our Vision

Identity is challenging—it requires the right mix of specialized skills, robust technologies, and a commitment to continuous learning. We founded ID Partners because we’ve seen too many consultancies deliver new capabilities and then leave, taking critical knowledge with them. Our vision is different:
	1.	Build & Transfer Capability: We embed skills and knowledge into your teams so that you can continue to grow and evolve your identity solutions.
	2.	Long-Term Resilience: We focus on delivering solutions that enable persistent, strong digital relationships with your customers and partners.
	3.	Future-Proof Platforms: We work with you to adapt quickly as new technologies and ecosystems emerge.


## About This Repository

This GitHub organization houses tools, utilities, and reference implementations we have developed to support the identity ecosystem. Here, you’ll find:
	•	Automation Scripts: Scripts for automating identity and access management tasks
	•	Reference Architectures: Example deployments, best practices, and architectural diagrams
	•	Utilities & Libraries: Reusable code libraries and modules that streamline integration with identity platforms
	•	Guides & Tutorials: Documentation to help developers and architects learn from our experience

We encourage you to explore our repositories, try out our tools, and contribute where you can.

How to Contribute
	1.	Fork & Clone: Start by forking the repository to your own GitHub account, then clone it locally.
	2.	Create a Branch: Create a new feature branch for your changes.
	3.	Commit & Push: Make your changes and commit them, then push your branch back to GitHub.
	4.	Submit a Pull Request: Open a pull request against the main branch of this repository.

We welcome bug reports, feature requests, and general feedback. Please review our contribution guidelines (if provided in a separate CONTRIBUTING.md) before submitting your pull request.

Contact Us

For inquiries about partnerships, custom solutions, or general questions, reach out to us at:
	•	Website: https://www.idpartners.com.au
	•	Email: info@idpartners.com 


Thank you for visiting ID Partners. We look forward to collaborating with you on building a more secure, resilient, and customer-centric digital identity landscape.

## What you can find in this repo:
1. Launch Darkly API Sidecar for Ping Authorize

A sidecar service that integrates LaunchDarkly feature flags with Ping Authorize, enabling dynamic toggling of access policies or other configuration parameters in real-time without impacting core Ping Authorize services.

2. AuthZen Adapter for Ping Authorize

A custom AuthZen adapter that allows Ping Authorize to leverage AuthZen’s policy engine. This facilitates centralized policy management and advanced authorization logic within Ping Authorize workflows.

3. Rich Authorization Request Ping Federate Plugin for Ping Authorize

A Ping Federate plugin designed to support Rich Authorization Requests when interfacing with Ping Authorize. This enables more granular authorization data to be carried within OAuth or OIDC flows, improving fine-grained policy enforcement.

4. Rich Authorization Request Adapter for OpenID Provider and AuthZen PDP

An adapter that extends OpenID Provider functionality to incorporate Rich Authorization Requests with the AuthZen Policy Decision Point (PDP). It enables a more robust authorization model by attaching detailed context and policy data to each request.

5. Grant Management API for Ping Fed and Ping Authorize

A standardized Grant Management API that streamlines the management of OAuth/OIDC grants across Ping Federate and Ping Authorize. It allows centralized and programmatic control of user authorization grants, policies, and consent data within AuthZen-driven environments.

6. Grant Management API for Ping Fed and AuthZen PDP

An implementation of the Grant Management API tailored to Ping Federate and AuthZen PDP integrations. It allows centralized and programmatic control of user authorization grants, policies, and consent data within AuthZen-driven environments.
