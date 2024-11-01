# API Policies
These are machine-readable API policies that define and connect the business rationale that exists behind how we govern APIs, providing a business bridge between Spectral rules governing the technical details, and the research, discussion, guidance, and experience that inform why we are governing our API operations.

All of the [policies applied to APIs.io APIs use the API Commons policy schema are available in a single YAML file](policies.yml) in this repository. These policies are rapidly evolving to support development right now and changes often, providing a way to filter, organize, and apply different areas of API governance in different ways--bridging the business and technical details of API governance.

## API Commons
API policies are a new [API Commons](https://apicommons.org) schema that provide a way to define the business details of API governance in a machine-readable, which can be then used in dashboards, reporting, and other visuals intended for business stakeholders, helping bring more visibility and participation across the API lifecycle.

## Example ([policy-example-1](policy-example-1.yml))

```
name: API Versioning
slug: api-versioning
description: Providing semantic or date-based versioning for an API, offering an overview of what is adopted for an API and why, letting consumers know that their is change management in place and how they can tune into communication.
scope: Business Contract
property: none
type: Versioning  
guidance: change/versioning
image: /images/versions.png

policies:
  - versioning-semantic-versioning
  - versioning-date-base

tags:
  - Change
  - Semantic Versioning
  - Date Based Versioning

experiences:
  - Alignment  
  - Change
  - Communication
  - Consistency
  - Quality
  - Reliability

rules:
  - apis-json-apis-properties-versioning-info

research:

  - name: Evolving HTTP APIs
    description: One of the most vexing problems that still seems to be facing people when I talk to them about HTTP APIs is how to handle versioning and extensibility – i.e., how they evolve.
    url: https://www.mnot.net/blog/2012/12/04/api-evolution 

discussion: https://github.com/api-evangelist/policies/issues/1    
```

## JSON Schema ([policy-json-schema](policy-json-schema.yml))

```
---
"$schema": http://json-schema.org/2020-12/schema
type: object
properties:
  name:
    type: string
    description: The name to accurately describe the policy.
  slug:
    type: string
    description: A slugified version of the policy name.
  description:
    type: string
    description: A more detailed description of a policy.
  scope:
    type: string
    description: What scope of API operations does it apply.
    enum:
      - Business Contract
      - Technical Contract
  property:
    type: string
    description: A JSON Path pointing to a specific property.
  type:
    type: string
    description: The APIs.json property type that applies.
  guidance:
    type: string
    description: A reference to guidance in support of policy.
  image:
    type: string
    description: A visual image or icon representing policy.
  policies:
    type: array
    description: A listing of related policies for a policy.
    items:
    - type: string
  tags:
    type: array
    description: A listing of tags that are applied to policy.
    items:
    - type: string
  experiences:
    type: array
    description: The experiences impacted by a policy existing.
    items:
    - type: string
  rules:
    type: array
    description: The Spectral rules that automate a policy.
    items:
    - type: string
  research:
    type: array
    description: References to any research conducted to inform a policy.
    items:
    - type: object
      properties:
        name:
          type: string
          description: A name describing the research conducted.
        description:
          type: string
          description: More detail regarding the value of research.
        url:
          type: string
          description: A URL reference to support the research.
      required:
      - name
      - description
      - url
  discussion:
    type: string
    description: A URL to where the discussion for a policy is occurring.
required:
- name
- slug
- description
- scope
- property
- type
- guidance
- image
- policies
- tags
- experiences
- rules
- research
- discussion
```

# API Policies, Rules, Experience, and Guidance
Policies are the bridge between rules and the policies, experience, and guidance, but rules can (and are) be used all by themselves. My approach to API governance focuses on the reality that we are primarily investing in the technical details of API governance, and that we are neglecting the business details required. 

<img src="https://kinlane-productions2.s3.us-east-1.amazonaws.com/policies-rules-guidance-experience-lifecycle.jpg">

This work acknowledges that services, tooling, and the general approach of API governance is only using rules applied to OpenAPI, which is beginning to expand to AsyncAPI, GraphQL, and Arazzo workflows, but is proposing the first schema for aligning this work with business objectives, when teams are ready for it.

## Support
This work is in early stage of development and rapidly moving as they are being applied in a variety of user interfaces and approaches to the automation and reporting of API governance. If you would like to contribute, have any questions, or would like to inform the work happening, please submit a GitHub issue on the repository or email kin@apievangelist.com.