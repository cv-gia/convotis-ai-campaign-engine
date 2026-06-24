CONVOTIS Naming Convention

Purpose

This naming convention establishes a consistent structure across all campaign-related assets and systems.

The objective is to:

* Standardize campaign creation
* Improve reporting and attribution
* Enable scalable campaign execution
* Support AI-generated campaigns
* Simplify HubSpot, LinkedIn and Clay management
* Create a shared language across Marketing and Sales

This naming convention should be used whenever possible across:

* LinkedIn Campaigns
* HubSpot Campaigns
* Clay Audiences
* Landing Pages
* Forms
* Emails
* Workflows
* Lists
* Creative Assets
* Reporting

⸻

Core Taxonomy

Business Units

CS

Cloud & Security

⸻

DA

Digital Applications

⸻

Solution Clusters

SCI

Sovereign Cloud & Infrastructure

⸻

CYB

Cybersecurity & Compliance

⸻

DPA

Document & Process Automation

⸻

SDP

Software Development & Digital Products

⸻

Buyer Journey Stages

AW

Awareness

Objective:

Create awareness for business challenges and opportunities.

⸻

CON

Consideration

Objective:

Support evaluation of approaches, vendors and solutions.

⸻

DEC

Decision

Objective:

Drive commercial engagement and Conversion.

⸻

Regions

DE

Germany

⸻

CH

Switzerland

⸻

ES

Spain

⸻

DACH

Germany, Austria and Switzerland

⸻

Creative Formats

IMG

Single Image

⸻

DOC

Document Ad

⸻

VID

Video

⸻

CAR

Carousel

⸻

Offer Types

WEB

Webinar

⸻

AUD

Audit

⸻

ASM

Assessment

⸻

DEM

Demo

⸻

CONS

Consultation

⸻

GUIDE

Guide

⸻

WP

Whitepaper

⸻

CS

Case Study

⸻

TEST

Testimonial

⸻

Target Segments

The segment should always reflect the primary target audience.

Examples:

* Manufacturing
* Healthcare
* ISV
* Public
* FinancialServices
* Logistics
* Retail
* Energy
* MidMarketIT
* EnterpriseIT

⸻

LinkedIn Campaign Naming

Structure

[BU][Cluster][Stage][Region][Segment][Quarter-Year][Offer]_[Format]

⸻

Example

CS_CYB_CON_DE_Manufacturing_Q2-2026_WEB_VID

⸻

Breakdown

CS

Cloud & Security

↓

CYB

Cybersecurity & Compliance

↓

CON

Consideration

↓

DE

Germany

↓

Manufacturing

Target Segment

↓

Q2-2026

Campaign Period

↓

WEB

Webinar

↓

VID

Video

⸻

LinkedIn Campaign Group Naming

Structure

GR_[BU][Region][Solution]

⸻

Example

GR_CS_DE_ISA

⸻

Example

GR_CS_DE_Kubernetes

⸻

Example

GR_DA_DACH_DataAI


HubSpot Campaign Naming

HubSpot campaigns serve as the master object for campaign reporting and organization.

All related assets should be associated with the same campaign name.

⸻

Structure

[BU][Cluster][Region][Segment][Year]

⸻

Example

CS_CYB_DE_Manufacturing_2026

⸻

Example

DA_SDP_DACH_ISV_2026

⸻

HubSpot Landing Pages

Landing Pages should use the same naming structure as the HubSpot campaign.

No additional suffix is required.

⸻

Structure

[BU][Cluster][Region][Segment][Year]

⸻

Example

CS_CYB_DE_Manufacturing_2026

⸻

Example

DA_SDP_DACH_ISV_2026

⸻

HubSpot Forms

Forms should use the same naming structure as the HubSpot campaign.

No additional suffix is required.

⸻

Structure

[BU][Cluster][Region][Segment][Year]

⸻

Example

CS_CYB_DE_Manufacturing_2026

⸻

Example

DA_SDP_DACH_ISV_2026

⸻

HubSpot Workflows

Workflows should use the same naming structure as the HubSpot campaign.

No additional suffix is required.

⸻

Structure

[BU][Cluster][Region][Segment][Year]

⸻

Example

CS_CYB_DE_Manufacturing_2026

⸻

Example

DA_SDP_DACH_ISV_2026

⸻

HubSpot Lists

Lists should use the same naming structure as the HubSpot campaign.

No additional suffix is required.

⸻

Structure

[BU][Cluster][Region][Segment][Year]

⸻

Example

CS_CYB_DE_Manufacturing_2026

⸻

Example

DA_SDP_DACH_ISV_2026

⸻

HubSpot Emails

Emails should use the campaign name plus sequential numbering.

This supports invitations, reminders, follow-ups and nurture sequences.

⸻

Structure

[Campaign]EMAIL[Number]

⸻

Example

CS_CYB_DE_Manufacturing_2026_EMAIL_01

⸻

Example

CS_CYB_DE_Manufacturing_2026_EMAIL_02

⸻

Example

CS_CYB_DE_Manufacturing_2026_EMAIL_03

⸻

Clay Audience Naming

Clay should use the same segmentation logic as HubSpot.

This ensures consistency across targeting, reporting and audience creation.

⸻

Structure

[Region]_[Segment]

⸻

Example

DE_Manufacturing

⸻

Example

CH_Healthcare

⸻

Example

ES_ISV

⸻

Example

DACH_MidMarketIT

⸻

Campaign Tracking Structure

The HubSpot campaign name should be used as the master campaign identifier.

Example:

CS_CYB_DE_Manufacturing_2026


This identifier should be reused whenever possible across:

* HubSpot
* Landing Pages
* Forms
* Workflows
* Emails
* Reporting
* UTM Campaign Parameters

This creates a single source of truth for campaign reporting.

Creative Asset Naming

Creative assets should be named independently from platform structures while maintaining a direct relationship to the campaign.

All creative assets should inherit the campaign identifier.

⸻

Structure

[Campaign][Format][Number]

⸻

Examples

CS_CYB_DE_Manufacturing_2026_IMG_01

CS_CYB_DE_Manufacturing_2026_IMG_02

⸻

CS_CYB_DE_Manufacturing_2026_DOC_01

CS_CYB_DE_Manufacturing_2026_DOC_02

⸻

CS_CYB_DE_Manufacturing_2026_VID_01

CS_CYB_DE_Manufacturing_2026_VID_02

⸻

CS_CYB_DE_Manufacturing_2026_CAR_01

CS_CYB_DE_Manufacturing_2026_CAR_02

⸻

UTM Naming Convention

The HubSpot Campaign Name should be reused for UTM Campaign naming whenever possible.

⸻

Structure

utm_campaign=[campaign]

⸻

Example

utm_campaign=cs_cyb_de_manufacturing_2026

⸻

UTM Content

Used to identify individual assets.

⸻

Structure

utm_content=[format]_[number]

⸻

Examples

utm_content=img_01

utm_content=doc_01

utm_content=vid_01

utm_content=car_01

⸻

Reporting Naming

Reporting should always roll up into the campaign identifier.

⸻

Master Campaign Identifier

CS_CYB_DE_Manufacturing_2026

⸻

Reporting Levels

Campaign

CS_CYB_DE_Manufacturing_2026

⸻

Asset

CS_CYB_DE_Manufacturing_2026_IMG_01

CS_CYB_DE_Manufacturing_2026_DOC_01

CS_CYB_DE_Manufacturing_2026_VID_01

⸻

Channel

LinkedIn

HubSpot

YouTube

Website

Outbound

⸻

Example 1 – Information Security Assessment Campaign

LinkedIn Campaign

CS_CYB_DEC_DE_Manufacturing_Q2-2026_ASM_VID

⸻

HubSpot Campaign

CS_CYB_DE_Manufacturing_2026

⸻

Landing Page

CS_CYB_DE_Manufacturing_2026

⸻

Form

CS_CYB_DE_Manufacturing_2026

⸻

Workflow

CS_CYB_DE_Manufacturing_2026

⸻

List

CS_CYB_DE_Manufacturing_2026

⸻

Email 1

CS_CYB_DE_Manufacturing_2026_EMAIL_01

⸻

Email 2

CS_CYB_DE_Manufacturing_2026_EMAIL_02

⸻

Audience

DE_Manufacturing

⸻

Creative Asset

CS_CYB_DE_Manufacturing_2026_DOC_01

⸻

Example 2 – Managed Kubernetes Campaign

LinkedIn Campaign

CS_SCI_CON_DE_ISV_Q3-2026_DEM_VID

⸻

HubSpot Campaign

CS_SCI_DE_ISV_2026

⸻

Landing Page

CS_SCI_DE_ISV_2026

⸻

Form

CS_SCI_DE_ISV_2026

⸻

Workflow

CS_SCI_DE_ISV_2026

⸻

List

CS_SCI_DE_ISV_2026

⸻

Email 1

CS_SCI_DE_ISV_2026_EMAIL_01

⸻

Audience

DE_ISV

⸻

Creative Asset

CS_SCI_DE_ISV_2026_VID_01

⸻

Naming Best Practices

Keep Names Human Readable

A user should understand the purpose of an asset without opening it.

⸻

Stay Consistent

The same naming structure should be used across:

* LinkedIn
* HubSpot
* Clay
* Reporting
* Creative Assets

⸻

Use One Primary Segment

Avoid combining multiple segments in a single campaign name.

⸻

Use One Primary Offer

Every campaign should have a clearly defined primary offer.

⸻

Use One Campaign Identifier

Every campaign should have exactly one master campaign identifier.

Example:

CS_CYB_DE_Manufacturing_2026

All related assets should inherit this identifier.

⸻

Key Principle

Naming conventions should support:

* Clarity
* Scalability
* Reporting
* Collaboration
* Automation

The naming structure should be simple enough for humans to understand and structured enough for AI systems, reporting platforms and future automation workflows.

Consistency is more important than complexity.
