# User Guide: Embedding Security Checks in LLM Interactions

This guide demonstrates how to integrate a **security-checking tool** into an LLM (Large Language Model) workflow. The goal is to validate user inputs and LLM-generated responses for security compliance using ***Palo Alto Network AI Runtime Security API Intercept***.

***Palo Alto Network AI Runtime Security API Intercept*** is a threat detection service designed to secure AI applications. It helps discover and protect applications using REST APIs by embedding Security-as-Code directly into source code.

The Scan API service scans prompts and models responses to identify potential threats and provides actionable recommendations.

The APIs protect your AI models, applications, and datasets by programmatically scanning prompts and models for threats, enabling robust protection across public and private models with model-agnostic functionality. Its model-agnostic design ensures seamless integration with any AI model, regardless of its architecture or framework. This enables consistent security across diverse AI models without any model-specific customization.
You can use this API in your application to send prompts or model responses and receive a threat assessment, along with the recommended actions based on your AI security profile.
For information on using the APIs, see the [API Intercept API Reference](https://pan.dev/ai-runtime-security/scan/api) Documentation.

## Key Benefits:
- Simple integration: Secure AI application models and datasets from insecure model outputs, prompt injections, and sensitive data loss.
- Comprehensive threat detection: Provides extensive app, model, and data threat detection while maintaining ease of use.
- Exceptional flexibility and defense: Integrates API-based threat detection to deliver unmatched adaptability and layered protection.
---

## Objectives:
- Introduce a security-checking tool to validate prompts and responses.
- Demonstrate how to handle blocked inputs and responses based on the security verdict.
- Build a flexible agent workflow that incorporates security checks.

---