# IETF Plan for HPWAN Services

## Objective
Define what the IETF needs to standardize to enable deployable HPWAN services in:
- Single-domain environments
- Multi-domain environments

This plan maps each needed capability to:
- What is needed?
- Which existing I-Ds provide a solution baseline?
- Remaining gaps?

## Current Drafts 
- draft-kcrh-hpwan-state-of-art-03
- draft-xiong-hpwan-problem-statement-02 (noting newer revisions exist)
- draft-xhy-hpwan-framework-03
- draft-xiong-hpwan-signaling-solution-01
- draft-xiong-teas-rsvp-resource-quota-00
- draft-yx-hpwan-uc-requirements-public-operator-00
- draft-zhao-hpwan-scenarios-deployment-00

## Scope Split: Single-Domain vs Multi-Domain
- Single-domain focus:
  - Host-edge signaling
  - In-domain admission control, quota reservation, scheduling
  - Domain-local telemetry and closed-loop control
- Multi-domain focus:
  - Cross-domain service intent and lifecycle
  - Inter-domain signaling and policy translation
  - End-to-end observability and SLA accountability

## Capability Required baswed on Function

### A. Signaling and Control Plane (Short-term)
- Objectives:
  - Host-to-network signaling specification
  - Node-to-node quota reservation specification
  - Inter-domain coordination profile
- Relevent drafts:
  - draft-xiong-hpwan-signaling-solution-01
  - draft-xiong-teas-rsvp-resource-quota-00
  - draft-xhy-hpwan-framework-03
- Main gaps:
  - Multi-domain semantics, interop across domains and transport domains with different technologies

### B. Data Models and APIs (Short-term)
- Objectives:
  - HPWAN service intent  model
  - QoS/admission/rate policy model
  - Telemetry and KPI model
- Relevent drafts:
  - draft-yx-hpwan-uc-requirements-public-operator-00
  - draft-xhy-hpwan-framework-03
  - draft-kcrh-hpwan-state-of-art-03
- Main gaps:
  - Concrete model definitions and model/protocol bindings 

### C. Operations, Measurement, and Assurance (Medium-term)
- Objectives:
  - HPWAN measurement methodology and KPI taxonomy
  - End-to-end monitoring profile for single and multi-domain services
- Relevent drafts:
  - draft-zhao-hpwan-scenarios-deployment-00
  - draft-kcrh-hpwan-state-of-art-03

### D. Security and Governance (Long-term)
- Deliverables:
  - HPWAN trust model and security
  - Authorization and policy exchange guidance across domains
