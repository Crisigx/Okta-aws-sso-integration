# Okta to AWS SSO Integration (SAML)

## Overview
This project demonstrates how to configure Single Sign-On (SSO) between Okta and AWS using SAML. Users authenticate through Okta and assume IAM roles in AWS without using IAM user credentials.

## Architecture
User → Okta → SAML Assertion → AWS → Role Access

## Key Features
- SAML-based SSO
- Role-based access (Admin / Read-only)
- Okta group mapping to AWS IAM roles

## Steps
1. Create IAM roles in AWS for SAML federation (Admin and Read-only)
2. Configure AWS as a SAML Identity Provider
3. Download AWS SAML metadata
4. Create AWS application in Okta
5. Upload AWS metadata into Okta
6. Configure SAML attributes and role mappings
7. Assign Okta groups to AWS roles
8. Test SSO login through Okta dashboard

## Screenshots
(To be added)

## What I Learned
(To be added)
