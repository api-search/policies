## Contract Metadata
Unique identifier, name, description, tags, and other metadata for the contract that defines the purpose of the API Contract, and how it benefits API producer and consumers, establishing the base of the agreement.

```
name: Contract Metadata
slug: contract-metadata
scope: Business Contract
property: none
type: none
guidance: contract/metadata
image: /images/meta-data.png
description: >-
  Unique identifier, name, description, tags, and other metadata for the
  contract that defines the purpose of the API Contract, and how it benefits API
  producer and consumers, establishing the base of the agreement.
policies:
  - contract-metadata-unique-identifiers
  - apis-json-url-info
  - contract-metadata-names
  - contract-metadata-descriptions
  - contract-metadata-images
  - contract-metadata-tags
  - apis-json-common-info
  - apis-json-created-info
  - apis-json-modified-info
tags:
  - Contracts
  - Discovery
solutions:
  - Alignment
  - Contracts
  - Communication
  - Discovery
  - Onboarding
```
## Unique Identifiers
Providing unique identifiers for API contracts, as well as the APIs that are indexed as part of a contract, providing a key reference.

```
name: Unique Identifiers
slug: contract-metadata-unique-identifiers
scope: Business Contract
property: aid
type: none
guidance: contract/unique-identifiers
image: /images/unique-identifiers.png
description: >-
  Providing unique identifiers for API contracts, as well as the APIs that are
  indexed as part of a contract, providing a key reference.
tags:
  - Contracts
  - Discovery
rules:
  - apis-json-specification-aid-info
```
## Name
Providing a clear, descriptive, and concise name for each API contract, as well as the APIs it contains, properly defining the scope.

```
name: Name
slug: contract-metadata-names
scope: Business Contract
property: name
type: none
guidance: contract/names
image: /images/names.png
description: >-
  Providing a clear, descriptive, and concise name for each API contract, as
  well as the APIs it contains, properly defining the scope.
tags:
  - Contracts
  - Discovery
rules:
  - apis-json-name-info
```
## Descriptions
Providing a robust description of the API contract, as well as each API it contains, providing my context for stakeholders of the contract.

```
name: Descriptions
slug: contract-metadata-descriptions
scope: Business Contract
property: description
type: none
guidance: contract/descriptions
image: /images/descriptions.png
description: >-
  Providing a robust description of the API contract, as well as each API it
  contains, providing my context for stakeholders of the contract.
tags:
  - Contracts
  - Discovery
rules:
  - apis-json-description-info
```
## Images
Including images as part of the metadata for your APIs helps make APIs more visible as part of portals, documentation, and other resources.

```
name: Images
slug: contract-metadata-images
scope: Business Contract
property: image
type: none
guidance: contract/images
image: /images/images.png
description: >-
  Including images as part of the metadata for your APIs helps make APIs more
  visible as part of portals, documentation, and other resources.
tags:
  - Contracts
  - Discovery
rules:
  - apis-json-image-info
```
## Tags
Tags provide a bounded context for your APIs, providing keywords that help organize APIs by domains, and  make them more discoverable.

```
name: Tags
slug: contract-metadata-tags
scope: Business Contract
property: tags
type: none
guidance: contract/tags
image: /images/tags.png
description: >-
  Tags provide a bounded context for your APIs, providing keywords that help
  organize APIs by domains, and  make them more discoverable.
tags:
  - Contracts
  - Discovery
rules:
  - apis-json-tags-info
  - apis-json-tags-upper-case-error
  - apis-json-tags-upper-case-info
```
## API Metadata
Unique identifier, name, description, tags, and other metadata for the API that defines the purpose of the API API, and how it benefits API producer and consumers, establishing the base of the agreement.

```
name: API Metadata
slug: api-metadata
scope: Business Contract
property: none
type: none
guidance: api/metadata
image: /images/meta-data.png
description: >-
  Unique identifier, name, description, tags, and other metadata for the API
  that defines the purpose of the API API, and how it benefits API producer and
  consumers, establishing the base of the agreement.
policies:
  - api-metadata-unique-identifiers
  - api-metadata-names
  - api-metadata-descriptions
  - api-metadata-images
  - api-metadata-tags
tags:
  - APIs
  - Discovery
solutions:
  - Alignment
  - APIs
  - Communication
  - Discovery
  - Onboarding
```
## Unique Identifiers
Providing unique identifiers for API apis, as well as the APIs that are indexed as part of a api, providing a key reference.

```
name: Unique Identifiers
slug: api-metadata-unique-identifiers
scope: Business Contract
property: aid
type: none
guidance: api/unique-identifiers
image: /images/unique-identifiers.png
description: >-
  Providing unique identifiers for API apis, as well as the APIs that are
  indexed as part of a api, providing a key reference.
tags:
  - APIs
  - Discovery
rules:
  - apis-json-apis-aid-error
  - apis-json-apis-aid-info
```
## Name
Providing a clear, descriptive, and concise name for each API api, as well as the APIs it contains, properly defining the scope.

```
name: Name
slug: api-metadata-names
scope: Business Contract
property: name
type: none
guidance: api/names
image: /images/names.png
description: >-
  Providing a clear, descriptive, and concise name for each API api, as well as
  the APIs it contains, properly defining the scope.
tags:
  - APIs
  - Discovery
rules:
  - apis-json-apis-name-info
```
## Descriptions
Providing a robust description of the API api, as well as each API it contains, providing my context for stakeholders of the api.

```
name: Descriptions
slug: api-metadata-descriptions
scope: Business Contract
property: description
type: none
guidance: api/descriptions
image: /images/descriptions.png
description: >-
  Providing a robust description of the API api, as well as each API it
  contains, providing my context for stakeholders of the api.
tags:
  - APIs
  - Discovery
rules:
  - apis-json-apis-description-info
```
## Images
Including images as part of the metadata for your APIs helps make APIs more visible as part of portals, documentation, and other resources.

```
name: Images
slug: api-metadata-images
scope: Business Contract
property: image
type: none
guidance: api/images
image: /images/images.png
description: >-
  Including images as part of the metadata for your APIs helps make APIs more
  visible as part of portals, documentation, and other resources.
tags:
  - APIs
  - Discovery
rules:
  - apis-json-apis-image-info
```
## Tags
Tags provide a bounded context for your APIs, providing keywords that help organize APIs by domains, and  make them more discoverable.

```
name: Tags
slug: api-metadata-tags
scope: Business Contract
property: tags
type: none
guidance: api/tags
image: /images/tags.png
description: >-
  Tags provide a bounded context for your APIs, providing keywords that help
  organize APIs by domains, and  make them more discoverable.
tags:
  - APIs
  - Discovery
rules:
  - apis-json-apis-tags-info
  - apis-json-apis-tags-upper-case-error
  - apis-json-apis-tags-upper-case-info
```
## Human URL
Providing a valid URL to a landing page for the API that is designed for humans to use when learning more about an API.

```
name: Human URL
slug: human-url
scope: Business Contract
property: humanURL
type: none
guidance: api/human-url
image: /images/human-url.png
description: >-
  Providing a valid URL to a landing page for the API that is designed for
  humans to use when learning more about an API.
tags:
  - URLs
solutions:
  - Onboarding
  - Access
rules:
  - apis-json-apis-humanURL-info
```
## Base URL
Providing a valid URL to the base for an API that is designed for machines to use when making call to an API by an consumer.

```
name: Base URL
slug: base-url
scope: Business Contract
property: baseURL
type: none
guidance: api/base-url
image: /images/base-url.png
description: >-
  Providing a valid URL to the base for an API that is designed for machines to
  use when making call to an API by an consumer.
tags:
  - URLs
solutions:
  - Onboarding
  - Access
rules:
  - apis-json-apis-baseURL-error
  - apis-json-apis-baseURL-info
```
## GitHub Repository
A GitHub repository for an API, providing the single source of truth for the API contract, OpenAPI, and other artifacts, as well as the road map, change log, support, feedback, and other elements of a repository.

```
name: GitHub Repository
slug: github-repository
scope: Business Contract
property: none
type: GitHubRepository
guidance: repositories/github
image: /images/repositories.png
description: >-
  A GitHub repository for an API, providing the single source of truth for the
  API contract, OpenAPI, and other artifacts, as well as the road map, change
  log, support, feedback, and other elements of a repository.
tags:
  - GitHub
  - Repositories
  - Source Control
solutions:
  - Change
  - Consistency
  - Communication
  - Discovery
  - Quality
  - Reliability
rules:
  - apis-json-apis-properties-github-repository-info
```
## Teams
Require that API contract management is controlled using Git teams.

```
name: Teams
slug: source-of-truth-teams
scope: Business Contract
property: none
type: GitHubTeams
guidance: repositories/teams
image: /images/teams.png
description: Require that API contract management is controlled using Git teams.
tags:
  - Teams
```
## Issues
Leveraging issues as a way to communicate API change and feedback.

```
name: Issues
slug: source-of-truth-issues
scope: Business Contract
property: none
type: GitHubIssues
guidance: repositories/issues
image: /images/issues.png
description: Leveraging issues as a way to communicate API change and feedback.
tags:
  - Issues
```
## Pull Requests
Using pull requests to submit changes to business or technical artifacts.

```
name: Pull Requests
slug: source-of-truth-pull-requests
scope: Business Contract
property: none
type: GitHubPullRequests
guidance: repositories/pull-requests
image: /images/pull-requests.png
description: Using pull requests to submit changes to business or technical artifacts.
tags:
  - Pull Requests
  - Commits
```
## GitHub Actions
Employing actions as a pipeline to make sure that the deliver of each API is a repeatable process.

```
name: GitHub Actions
slug: source-of-truth-actions
scope: Business Contract
property: none
type: GitHubActions
guidance: repositories/actions
image: /images/actions.png
description: >-
  Employing actions as a pipeline to make sure that the deliver of each API is a
  repeatable process.
tags:
  - Pull Requests
  - Commits
rules:
  - apis-json-apis-properties-github-action-info
```
## README
Require that each API contract repository has a dedicated README.

```
name: README
slug: source-of-truth-readme
scope: Business Contract
property: none
type: GitHubReadme
guidance: repositories/readme
image: /images/readme.png
description: Require that each API contract repository has a dedicated README.
tags:
  - README
```
## Use Cases
The who, what, how, and why of producing an API, making sure all of the known use cases are accurately described and kept up to date, then used to ensure each API is delivering what is expected with each use case.

```
name: Use Cases
slug: use-cases
scope: Business Contract
property: none
type: UseCases
guidance: use-cases/overview
image: /images/use-cases.png
description: >-
  The who, what, how, and why of producing an API, making sure all of the known
  use cases are accurately described and kept up to date, then used to ensure
  each API is delivering what is expected with each use case.
policies:
  - who
  - what
  - how
  - why
tags:
  - Business
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Discovery
  - Onboarding
  - Simplicity
rules:
  - apis-json-apis-properties-use-cases-info
```
## Who
Who is using an API, focusing on the people who will be putting an API to work in their applications.

```
name: Who
slug: who
scope: Business Contract
property: none
type: none
guidance: use-cases/who
image: /images/who.png
description: >-
  Who is using an API, focusing on the people who will be putting an API to work
  in their applications.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## What
What will consumers be building with the resources and capabilities being made available via APIs.

```
name: What
slug: what
scope: Business Contract
property: none
type: none
guidance: use-cases/what
image: /images/what.png
description: >-
  What will consumers be building with the resources and capabilities being made
  available via APIs.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## How
How will consumers be putting API resources and capabilities, getting into the details of programming languages and frameworks.

```
name: How
slug: how
scope: Business Contract
property: none
type: none
guidance: use-cases/how
image: /images/how.png
description: >-
  How will consumers be putting API resources and capabilities, getting into the
  details of programming languages and frameworks.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Why
What are the reasons an API consumer will be putting APIs to work in their applications and integrations as part of their business.

```
name: Why
slug: why
scope: Business Contract
property: none
type: none
guidance: use-cases/why
image: /images/why.png
description: >-
  What are the reasons an API consumer will be putting APIs to work in their
  applications and integrations as part of their business.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Documentation
The human-readable HTML, Markdown, or PDF representation of the technical surface area of each API, providing path, methods, summaries, description, examples, and the other resources consumers will need.

```
name: Documentation
slug: documentation
scope: Business Contract
property: none
type: Documentation
guidance: documentation/overview
image: /images/documentation.png
description: >-
  The human-readable HTML, Markdown, or PDF representation of the technical
  surface area of each API, providing path, methods, summaries, description,
  examples, and the other resources consumers will need.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Alignment
  - Communication
  - Onboarding
  - Discovery
  - Simplicity
  - Consistency
rules:
  - apis-json-apis-properties-documentation-info
```
## Paths
Providing simple, clean, and intuitive paths as part of the documentation being published for consumers to use.

```
name: Paths
slug: documentation-paths
scope: Business Contract
property: none
type: none
guidance: documentation/paths
image: /images/paths.png
description: >-
  Providing simple, clean, and intuitive paths as part of the documentation
  being published for consumers to use.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Request Bodies
Including details and examples regarding the request bodies being submitted for POST, PUT, and other possible methods.

```
name: Request Bodies
slug: documentation-request-bodies
scope: Business Contract
property: none
type: none
guidance: documentation/request-bodies
image: /images/request-bodies.png
description: >-
  Including details and examples regarding the request bodies being submitted
  for POST, PUT, and other possible methods.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Responses
Making sure there is a complete example for each API response in documentation, including happy and unhappy responses.

```
name: Responses
slug: documentation-responses
scope: Business Contract
property: none
type: none
guidance: documentation/responses
image: /images/responses.png
description: >-
  Making sure there is a complete example for each API response in
  documentation, including happy and unhappy responses.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Schema
Documenting all of the schema which are used as part of request bodies and responses, providing JSON SChema representations of each.

```
name: Schema
slug: documentation-schema
scope: Business Contract
property: none
type: none
guidance: documentation/schema
image: /images/schema.png
description: >-
  Documenting all of the schema which are used as part of request bodies and
  responses, providing JSON SChema representations of each.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Examples
Providing examples of request and responses, with as many variations as possible, helping demonstrate wide usage of an API.

```
name: Examples
slug: documentation-examples
scope: Business Contract
property: none
type: none
guidance: documentation/examples
image: /images/examples.png
description: >-
  Providing examples of request and responses, with as many variations as
  possible, helping demonstrate wide usage of an API.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## OpenAPI
A machine-readable OpenAPI using the most recent version of the API specification, describing the surface area of each API, which is then used to render the human-readable documentation, and other supporting elements.

```
name: OpenAPI
slug: openapi
scope: Technical Contract
property: none
type: none
guidance: contracts/openapi
image: /images/openapi.png
description: >-
  A machine-readable OpenAPI using the most recent version of the API
  specification, describing the surface area of each API, which is then used to
  render the human-readable documentation, and other supporting elements.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Access
  - Automation
  - Change
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-openapi-info
```
## OpenAPI Version
Requiring there is the latest version of OpenAPI available.

```
name: OpenAPI Version
slug: openapi-version
image: /images/versions.png
description: Requiring there is the latest version of OpenAPI available.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Title
Requiring the info title property meets the policy standards.

```
name: Title
slug: openapi-info-title
image: /images/names.png
description: Requiring the info title property meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-title-error
  - openapi-info-title-info
  - openapi-info-title-length-error
  - openapi-info-title-upper-case-error
  - openapi-info-title-upper-case-info
```
## Description
Requiring the info description property meets the policy standards.

```
name: Description
slug: openapi-info-description
image: /images/descriptions.png
description: Requiring the info description property meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-description-error
  - openapi-info-description-info
  - openapi-info-description-length-error
```
## Contact
Requiring that there is a contact included in the OpenAPI info.

```
name: Contact
slug: openapi-info-contact
image: /images/contacts.png
description: Requiring that there is a contact included in the OpenAPI info.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-contact-error
  - openapi-info-contact-info
  - openapi-info-contact-name-error
  - openapi-info-contact-name-info
  - openapi-info-contact-email-error
  - openapi-info-contact-email-info
  - openapi-info-contact-url-error
  - openapi-info-contact-url-info
```
## License
Requiring the info license property meets the policy standards.

```
name: License
slug: openapi-info-license
image: /images/licenses.png
description: Requiring the info license property meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-license-error
  - openapi-info-license-identifier-cc-by-nc-sa-error
  - openapi-info-license-identifier-cc-by-nc-sa-info
  - openapi-info-license-identifier-error
  - openapi-info-license-identifier-info
  - openapi-info-license-info
  - openapi-info-license-name-error
  - openapi-info-license-name-info
  - openapi-info-license-url-error
  - openapi-info-license-url-info
```
## Terms of Service
Requiring the info terms of service property meets the policy standards.

```
name: Terms of Service
slug: openapi-info-terms-of-service
image: /images/terms-of-service.png
description: Requiring the info terms of service property meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-terms-of-service-error
  - openapi-info-terms-of-service-info
```
## Version
Requiring the info version property meets the policy standards.

```
name: Version
slug: openapi-info-version
image: /images/versions.png
description: Requiring the info version property meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-info-version-error
  - openapi-info-version-info
  - openapi-version-date-info
  - openapi-version-semantic-info
```
## Path Names
Requiring API paths meets the policy standards that are set.

```
name: Path Names
slug: openapi-path-names
image: /images/names.png
description: Requiring API paths meets the policy standards that are set.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-no-api-in-path-error
  - openapi-no-api-in-path-info
  - openapi-no-path-trailing-slash-error
  - openapi-no-path-trailing-slash-info
  - openapi-version-in-path-error
  - openapi-version-in-path-info
```
## Operation Summary
Requiring that all operational summaries meets the policy standards.

```
name: Operation Summary
slug: openapi-operation-summary
image: /images/summaries.png
description: Requiring that all operational summaries meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-operations-summary-error
  - openapi-operations-summary-info
  - openapi-operations-summary-length-error
  - openapi-operations-summary-period-none-error
  - openapi-operations-summary-period-none-info
```
## Operation Description
Requiring that all operational descriptions meets the policy standards.

```
name: Operation Description
slug: openapi-operation-description
image: /images/descriptions.png
description: Requiring that all operational descriptions meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-operations-description-error
  - openapi-operations-description-info
  - openapi-operations-description-length-error
```
## Operation Ids
Requiring that all operational unique identifiers meets the policy standards.

```
name: Operation Ids
slug: openapi-operation-identifiers
image: /images/unique-identifiers.png
description: Requiring that all operational unique identifiers meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-operations-operation-ids-error
  - openapi-operations-operation-ids-info
  - openapi-operations-operation-ids-camel-case-error
  - openapi-operations-operation-ids-camel-case-info
```
## Operation Tags
Requiring that all operational tags meets the policy standards.

```
name: Operation Tags
slug: openapi-operation-tags
image: /images/tags.png
description: Requiring that all operational tags meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-operations-tags-error
  - openapi-operations-tags-info
  - openapi-operations-tags-one-error
  - openapi-operations-tags-upper-case-error
  - openapi-operations-tags-upper-case-info
```
## Operation Security
Requiring that all operational security meets the policy standards.

```
name: Operation Security
slug: openapi-operation-security
image: /images/security.png
description: Requiring that all operational security meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-operation-security-definitions-error
  - openapi-operation-security-definitions-info
```
## Request Bodies
Requiring that all operational request bodies meets the policy standards.

```
name: Request Bodies
slug: openapi-operation-request-bodies
image: /images/request-bodies.png
description: Requiring that all operational request bodies meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-no-request-body-on-delete-error
  - openapi-no-request-body-on-delete-info
  - openapi-no-request-body-on-get-error
  - openapi-no-request-body-on-get-info
  - openapi-request-bodies-description-error
  - openapi-request-bodies-description-info
  - openapi-request-bodies-required-property-error
  - openapi-request-bodies-required-property-info
  - openapi-request-body-content-on-post-error
  - openapi-request-body-content-on-post-info
  - openapi-request-body-content-on-put-error
  - openapi-request-body-content-on-put-info
```
## Request Bodies Media Types
Requiring that all operational request body media types meets the policy standards.

```
name: Request Bodies Media Types
slug: openapi-operation-request-bodies-meda-types
image: /images/media-types.png
description: >-
  Requiring that all operational request body media types meets the policy
  standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-request-body-have-application-json-info
  - openapi-request-body-have-application-x-www-form-url-encoded-info
```
## Request Bodies Schema
Requiring that all operational request body schema meets the policy standards.

```
name: Request Bodies Schema
slug: openapi-operation-request-bodies-schema
image: /images/schema.png
description: Requiring that all operational request body schema meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-request-body-have-schema-error
  - openapi-request-body-have-schema-info
  - openapi-request-body-have-schema-ref-error
  - openapi-request-body-have-schema-ref-info
  - openapi-request-body-on-post-error
  - openapi-request-body-on-post-info
  - openapi-request-body-on-put-error-info
  - openapi-request-body-on-put-info
  - openapi-response-put-204-no-body-error
  - openapi-response-delete-204-no-body-error
```
## Request Bodies Examples
Requiring that all operational request body examples meets the policy standards.

```
name: Request Bodies Examples
slug: openapi-operation-request-bodies-examples
image: /images/examples.png
description: >-
  Requiring that all operational request body examples meets the policy
  standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-request-body-have-examples-error
  - openapi-request-body-have-examples-info
  - openapi-request-body-have-examples-ref-error
  - openapi-request-body-have-examples-ref-info
```
## Parameters
Requiring that all operational parameters meets the policy standards.

```
name: Parameters
slug: openapi-operation-parameters
image: /images/parameters.png
description: Requiring that all operational parameters meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-parameters-componentized-error
  - openapi-parameters-componentized-info
```
## Parameter In
Requiring that all operational parameters in property meets the policy standards.

```
name: Parameter In
slug: openapi-operation-parameter-in
image: /images/parameters.png
description: >-
  Requiring that all operational parameters in property meets the policy
  standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-in-error
  - openapi-components-parameters-in-info
```
## Parameter Names
Requiring that all operational parameters names meets the policy standards.

```
name: Parameter Names
slug: openapi-operation-parameter-names
image: /images/parameter-names.png
description: Requiring that all operational parameters names meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-name-error
  - openapi-components-parameters-name-info
  - openapi-components-parameters-name-length-error
  - openapi-components-parameters-casing-camel-warn
  - openapi-components-parameters-casing-camel-info
```
## Parameter Descriptions
Requiring that all operational parameters descriptions meets the policy standards.

```
name: Parameter Descriptions
slug: openapi-operation-parameter-descriptions
image: /images/parameter-descriptions.png
description: >-
  Requiring that all operational parameters descriptions meets the policy
  standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-description-error
  - openapi-components-parameters-description-info
  - openapi-components-parameters-description-length-error
```
## Parameter Type
Requiring that all operational parameters type property meets the policy standards.

```
name: Parameter Type
slug: openapi-operation-parameter-types
image: /images/types.png
description: >-
  Requiring that all operational parameters type property meets the policy
  standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-allowed-integer-format-error
  - openapi-schema-properties-allowed-number-format-error
  - openapi-schema-properties-array-items-error
  - openapi-schema-properties-array-items-info
  - openapi-schema-properties-array-maxitems-error
  - openapi-schema-properties-array-maxitems-info
  - openapi-schema-properties-array-minitems-error
  - openapi-schema-properties-array-minitems-info
  - openapi-schema-properties-define-number-maximum-error
  - openapi-schema-properties-define-number-minimum-error
  - openapi-schema-properties-string-maxlength-error
  - openapi-schema-properties-string-maxlength-info
  - openapi-schema-properties-string-minlength-error
  - openapi-schema-properties-string-minlength-info
```
## Parameter Schema
Requiring that all operational parameters schema meets the policy standards.

```
name: Parameter Schema
slug: openapi-operation-parameter-schema
image: /images/schema.png
description: Requiring that all operational parameters schema meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-schema-error
  - openapi-components-parameters-schema-info
  - openapi-components-parameters-schema-ref-error
  - openapi-components-parameters-schema-ref-info
```
## Parameter Enumerators
Requiring that all operational parameters enums meets the policy standards.

```
name: Parameter Enumerators
slug: openapi-operation-parameter-enum
image: /images/enumerators.png
description: Requiring that all operational parameters enums meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-enum-casing-error
  - openapi-components-parameters-enum-casing-info
  - openapi-components-parameters-enum-info
```
## Response 2xx
Requiring that all 2xx responses meets the policy standards.

```
name: Response 2xx
slug: openapi-operation-response-2xx
image: /images/check.png
description: Requiring that all 2xx responses meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-200-status-code-error
  - openapi-response-get-200-status-code-info
  - openapi-response-get-200-description-error
  - openapi-response-get-200-description-info
  - openapi-response-get-200-content-error
  - openapi-response-get-200-content-info
  - openapi-response-post-201-status-code-error
  - openapi-response-post-201-status-code-info
  - openapi-response-post-201-description-error
  - openapi-response-post-201-description-info
  - openapi-response-post-201-content-error
  - openapi-response-post-201-content-info
  - openapi-response-put-204-status-code-error
  - openapi-response-put-204-status-code-info
  - openapi-response-delete-204-status-code-error
  - openapi-response-delete-204-status-code-info
```
## Response 2xx Media Type
Requiring that all 2xx response media types meets the policy standards.

```
name: Response 2xx Media Type
slug: openapi-operation-response-2xx-media-types
image: /images/check.png
description: Requiring that all 2xx response media types meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-200-media-type-error
  - openapi-response-get-200-media-type-info
  - openapi-response-post-201-media-type-error
  - openapi-response-post-201-media-type-info
```
## Response 2xx Schema
Requiring that all 2xx responses schema meets the policy standards.

```
name: Response 2xx Schema
slug: openapi-operation-response-2xx-schema
image: /images/check.png
description: Requiring that all 2xx responses schema meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-200-media-type-schema-error
  - openapi-response-get-200-media-type-schema-info
  - openapi-response-get-200-media-type-schema-ref-error
  - openapi-response-get-200-media-type-schema-ref-info
  - openapi-response-post-201-media-type-schema-error
  - openapi-response-post-201-media-type-schema-info
  - openapi-response-post-201-schema-ref-error
  - openapi-response-post-201-schema-ref-info
```
## Response 2xx Examples
Requiring that all 2xx response examples meets the policy standards.

```
name: Response 2xx Examples
slug: openapi-operation-response-2xx-examples
image: /images/check.png
description: Requiring that all 2xx response examples meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-200-media-type-examples-error
  - openapi-response-get-200-media-type-examples-info
  - openapi-response-get-200-media-type-examples-ref-error
  - openapi-response-get-200-media-type-examples-ref-info
  - openapi-response-post-201-media-type-examples-error
  - openapi-response-post-201-media-type-examples-info
  - openapi-response-post-201-examples-ref-error
  - openapi-response-post-201-examples-ref-info
```
## Response 4xx
Requiring that all 4xx responses meets the policy standards.

```
name: Response 4xx
slug: openapi-operation-response-4xx
image: /images/not-found.png
description: Requiring that all 4xx responses meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-400-status-code-error
  - openapi-response-get-400-status-code-info
  - openapi-response-get-401-status-code-info
  - openapi-response-get-401-status-code-error
  - openapi-response-get-403-status-code-info
  - openapi-response-get-403-status-code-error
  - openapi-response-get-404-status-code-error
  - openapi-response-get-404-status-code-info
  - openapi-response-get-429-status-code-info
  - openapi-response-get-429-status-code-error
  - openapi-response-post-400-status-code-info
  - openapi-response-post-400-status-code-error
  - openapi-response-post-401-status-code-info
  - openapi-response-post-401-status-code-error
  - openapi-response-post-403-status-code-info
  - openapi-response-post-403-status-code-error
  - openapi-response-post-404-status-code-info
  - openapi-response-post-404-status-code-error
  - openapi-response-post-429-status-code-error
  - openapi-response-post-429-status-code-info
  - openapi-response-put-400-status-code-error
  - openapi-response-put-400-status-code-info
  - openapi-response-put-401-status-code-error
  - openapi-response-put-401-status-code-info
  - openapi-response-put-403-status-code-error
  - openapi-response-put-403-status-code-info
  - openapi-response-put-404-status-code-error
  - openapi-response-put-404-status-code-info
  - openapi-response-put-429-status-code-error
  - openapi-response-put-429-status-code-info
  - openapi-response-delete-400-status-code-error
  - openapi-response-delete-400-status-code-info
  - openapi-response-delete-401-status-code-error
  - openapi-response-delete-401-status-code-info
  - openapi-response-delete-403-status-code-error
  - openapi-response-delete-403-status-code-info
  - openapi-response-delete-404-status-code-error
  - openapi-response-delete-404-status-code-info
  - openapi-response-delete-429-status-code-error
  - openapi-response-delete-429-status-code-info
  - openapi-response-delete-500-status-code-error
  - openapi-response-delete-500-status-code-info
```
## Response 4xx Schema
Requiring that all 4xx response schema meets the policy standards.

```
name: Response 4xx Schema
slug: openapi-operation-response-4xx-schema
image: /images/not-found.png
description: Requiring that all 4xx response schema meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-400-schema-ref-error
  - openapi-response-get-400-schema-ref-info
  - openapi-response-get-401-schema-ref-error
  - openapi-response-get-401-schema-ref-info
  - openapi-response-get-403-schema-ref-error
  - openapi-response-get-403-schema-ref-info
  - openapi-response-get-404-schema-ref-error
  - openapi-response-get-404-schema-ref-info
  - openapi-response-get-429-schema-ref-error
  - openapi-response-get-429-schema-ref-info
  - openapi-response-post-400-schema-ref-error
  - openapi-response-post-400-schema-ref-info
  - openapi-response-post-401-schema-ref-error
  - openapi-response-post-401-schema-ref-info
  - openapi-response-post-403-schema-ref-error
  - openapi-response-post-403-schema-ref-info
  - openapi-response-post-404-schema-ref-error
  - openapi-response-post-404-schema-ref-info
  - openapi-response-post-429-schema-ref-error
  - openapi-response-post-429-schema-ref-info
  - openapi-response-put-400-schema-ref-error
  - openapi-response-put-400-schema-ref-info
  - openapi-response-put-401-schema-ref-error
  - openapi-response-put-401-schema-ref-info
  - openapi-response-put-403-schema-ref-error
  - openapi-response-put-403-schema-ref-info
  - openapi-response-put-404-schema-ref-error
  - openapi-response-put-404-schema-ref-info
  - openapi-response-put-429-schema-ref-error
  - openapi-response-put-429-schema-ref-info
  - openapi-response-delete-400-schema-ref-error
  - openapi-response-delete-400-schema-ref-info
  - openapi-response-delete-401-schema-ref-error
  - openapi-response-delete-401-schema-ref-info
  - openapi-response-delete-403-schema-ref-error
  - openapi-response-delete-403-schema-ref-info
  - openapi-response-delete-404-schema-ref-error
  - openapi-response-delete-404-schema-ref-info
  - openapi-response-delete-429-schema-ref-error
  - openapi-response-delete-429-schema-ref-info
  - openapi-response-delete-500-schema-ref-error
  - openapi-response-delete-500-schema-ref-info
```
## Response 5xx
Requiring that all 5xx responses meets the policy standards.

```
name: Response 5xx
slug: openapi-operation-response-5xx
image: /images/error.png
description: Requiring that all 5xx responses meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-500-status-code-error
  - openapi-response-get-500-status-code-info
  - openapi-response-post-500-status-code-error
  - openapi-response-post-500-status-code-info
  - openapi-response-put-500-status-code-error
  - openapi-response-put-500-status-code-info
```
## Response 5xx Schema
Requiring that all 5xx response schema meets the policy standards.

```
name: Response 5xx Schema
slug: openapi-operation-response-5xx-schema
image: /images/error.png
description: Requiring that all 5xx response schema meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-response-get-500-schema-ref-error
  - openapi-response-get-500-schema-ref-info
  - openapi-response-post-500-schema-ref-error
  - openapi-response-post-500-schema-ref-info
  - openapi-response-put-500-schema-ref-error
  - openapi-response-put-500-schema-ref-info
```
## Schema Type
Requiring that all schema type meets the policy standards.

```
name: Schema Type
slug: openapi-schema-type
image: /images/types.png
description: Requiring that all schema type meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-type-error
  - openapi-schema-type-info
```
## Schema Names
Requiring that all schema names meets the policy standards.

```
name: Schema Names
slug: openapi-schema-names
image: /images/names.png
description: Requiring that all schema names meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-names-pascal-case-error
  - openapi-schema-names-pascal-case-info
  - openapi-schema-names-length-error
```
## Schema Descriptions
Requiring that all schema descriptions meets the policy standards.

```
name: Schema Descriptions
slug: openapi-schema-descriptions
image: /images/descriptions.png
description: Requiring that all schema descriptions meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-description-error
  - openapi-schema-description-info
  - openapi-schema-description-length-error
```
## Schema Properties
Requiring that all schema properties meets the policy standards.

```
name: Schema Properties
slug: openapi-schema-properties
image: /images/properties.png
description: Requiring that all schema properties meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-error
  - openapi-schema-properties-info
```
## Schema Property Names
Requiring that all schema property names meets the policy standards.

```
name: Schema Property Names
slug: openapi-schema-property-names
image: /images/names.png
description: Requiring that all schema property names meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-names-camel-case-error
  - openapi-schema-properties-names-camel-case-info
  - openapi-schema-properties-names-length-error
```
## Schema Property Descriptions
Requiring that all schema property descriptions meets the policy standards.

```
name: Schema Property Descriptions
slug: openapi-schema-property-descriptions
image: /images/descriptions.png
description: Requiring that all schema property descriptions meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-descriptions-error
  - openapi-schema-properties-descriptions-info
  - openapi-schema-properties-descriptions-length-error
```
## Schema Property Type
Requiring that all schema property types meets the policy standards.

```
name: Schema Property Type
slug: openapi-schema-property-types
image: /images/types.png
description: Requiring that all schema property types meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-array-items-error
  - openapi-schema-properties-array-items-info
  - openapi-schema-properties-allowed-integer-format-error
  - openapi-schema-properties-allowed-number-format-error
```
## Schema Property Shapes
Requiring that all schema property shapes meets the policy standards.

```
name: Schema Property Shapes
slug: openapi-schema-property-shapes
image: /images/shapes.png
description: Requiring that all schema property shapes meets the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-schema-properties-string-maxlength-error
  - openapi-schema-properties-string-maxlength-info
  - openapi-schema-properties-string-minlength-error
  - openapi-schema-properties-string-minlength-info
  - openapi-schema-properties-array-items-error
  - openapi-schema-properties-array-items-info
  - openapi-schema-properties-array-maxitems-error
  - openapi-schema-properties-array-maxitems-info
  - openapi-schema-properties-array-minitems-error
  - openapi-schema-properties-array-minitems-info
  - openapi-schema-properties-define-number-maximum-error
  - openapi-schema-properties-define-number-minimum-error
```
## OpenAPI External Docs
Requiring that all OpenAPI external documentation meet the policy standards.

```
name: OpenAPI External Docs
slug: openapi-external-docs
image: /images/documentation.png
description: Requiring that all OpenAPI external documentation meet the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-external-docs-error
  - openapi-external-docs-info
```
## OpenAPI Tags
Requiring that all OpenAPI tags meet the policy standards.

```
name: OpenAPI Tags
slug: openapi-tags
image: /images/tags.png
description: Requiring that all OpenAPI tags meet the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-tags-description-error
  - openapi-tags-description-info
  - openapi-tags-name-error
  - openapi-tags-name-info
  - openapi-tags-object-error
  - openapi-tags-object-info
  - openapi-tags-one-error
  - openapi-tags-upper-case-error
```
## OpenAPI Security
Requiring that OpenAPI security meet the policy standards.

```
name: OpenAPI Security
slug: openapi-security
image: /images/security.png
description: Requiring that OpenAPI security meet the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-security-schemes-error
  - openapi-security-schemes-info
```
## OpenAPI Component Headers
Requiring that OpenAPI components headers meet the policy standards.

```
name: OpenAPI Component Headers
slug: openapi-component-headers
image: /images/headers.png
description: Requiring that OpenAPI components headers meet the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-headers-rate-limit-error
  - openapi-components-headers-rate-limit-info
  - openapi-components-headers-retry-after-error
  - openapi-components-headers-retry-after-info
```
## OpenAPI Components
Requiring that OpenAPI components meet the policy standards.

```
name: OpenAPI Components
slug: openapi-components
image: /images/components.png
description: Requiring that OpenAPI components meet the policy standards.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-parameters-error
  - openapi-components-parameters-info
  - openapi-components-examples-error
  - openapi-components-examples-info
  - openapi-components-schemas-error
  - openapi-components-schemas-info
  - openapi-components-headers-error
  - openapi-components-headers-info
```
## Problem Details for HTTP APIs
Requiring that errors use the Problem Details for HTTP APIs standard.

```
name: Problem Details for HTTP APIs
slug: problem-details-for-http-apis
image: /images/errors.png
description: Requiring that errors use the Problem Details for HTTP APIs standard.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - openapi-components-responses-info
  - openapi-components-responses-bad-request-error
  - openapi-components-responses-bad-request-info
  - openapi-components-responses-conflict-error
  - openapi-components-responses-conflict-info
  - openapi-components-responses-error
  - openapi-components-responses-forbidden-error
  - openapi-components-responses-forbidden-info
  - openapi-components-responses-internal-server-error-error
  - openapi-components-responses-internal-server-error-info
  - openapi-components-responses-not-found-error
  - openapi-components-responses-not-found-info
  - openapi-components-responses-too-many-requests-error
  - openapi-components-responses-too-many-requests-info
  - openapi-components-responses-unauthorized-error
  - openapi-components-responses-unauthorized-info
```
## Postman Collection
A machine-readable Postman Collection describing the surface area of the API contract or providing more modular and executable representations of portions of the API contract. - Postman - Executable

```
name: Postman Collection
slug: postman-collection
scope: Technical Contract
property: none
type: none
guidance: contracts/collection
image: /images/collections.png
description: >-
  A machine-readable Postman Collection describing the surface area of the API
  contract or providing more modular and executable representations of portions
  of the API contract. - Postman - Executable
solutions:
  - Access
  - Automation
  - Change
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-postman-collection-info
```
## Getting Started
The step by step walk-through for new API consumers, ensuring they have exactly what is needed to discover and onboard, but also help make sure the getting started steps are as simple, plain language, and easy to follow.

```
name: Getting Started
slug: getting-started
scope: Business Contract
property: none
type: GettingStarted
guidance: onboarding/getting-started
image: /images/getting-started.png
description: >-
  The step by step walk-through for new API consumers, ensuring they have
  exactly what is needed to discover and onboard, but also help make sure the
  getting started steps are as simple, plain language, and easy to follow.
tags:
  - Business
solutions:
  - Communication
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
  - Simplicity
rules:
  - apis-json-apis-properties-getting-started-info
```
## Documentation
Provide a link and description to your API documentation, providing the entry point for API consumers to begin learning about what your API does.

```
name: Documentation
slug: getting-started-documentation
image: /images/documentation.png
description: >-
  Provide a link and description to your API documentation, providing the entry
  point for API consumers to begin learning about what your API does.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Authentication
Needs description.

```
name: Authentication
slug: getting-started-authentication
image: /images/authentication.png
description: Needs description.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## SDKs
Provide a link and description of where API consumers can learn more about authentication and how it will work when they use an API.

```
name: SDKs
slug: getting-started-sdks
image: /images/sdks.png
description: >-
  Provide a link and description of where API consumers can learn more about
  authentication and how it will work when they use an API.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Login
Providing a way to login and gain access to an API, offering a simple human-readable URL to the login page, or ideally some sort of automated login process that allows access with as few clicks and steps as possible.

```
name: Login
slug: login
image: /images/login.png
description: >-
  Providing a way to login and gain access to an API, offering a simple
  human-readable URL to the login page, or ideally some sort of automated login
  process that allows access with as few clicks and steps as possible.
policies:
  - None
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Onboarding
  - Access
```
## Plans
Plans are all about being explicit and transparent with all of the access for an API, breaking down the tiers, rate limits, features, and pricing that is available for API consumers, standardizing the business of APIs.

```
name: Plans
slug: plans
scope: Business Contract
property: none
type: none
guidance: onboarding/plans
image: /images/plans.png
description: >-
  Plans are all about being explicit and transparent with all of the access for
  an API, breaking down the tiers, rate limits, features, and pricing that is
  available for API consumers, standardizing the business of APIs.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Alignment
  - Communication
  - Onboarding
  - Access
  - Simplicity
  - Consistency
rules:
  - apis-json-apis-properties-plans-info
```
## Metrics
Providing details regarding the metrics available for each plan, outlining how the usage of digital resources and capabilities are being measured.

```
name: Metrics
slug: plan-metrics
image: /images/metrics.png
description: >-
  Providing details regarding the metrics available for each plan, outlining how
  the usage of digital resources and capabilities are being measured.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Rate Limits
Providing details of rate limits being applied as part of each plan, and what is available to consumers as part of their application usage.

```
name: Rate Limits
slug: plan-rate-limits
image: /images/rate-limits.png
description: >-
  Providing details of rate limits being applied as part of each plan, and what
  is available to consumers as part of their application usage.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Time Frame
Break down usage for for consumers based upon second, minutes, days, weeks, months, or other relevant time-frame for them to understand their usage.

```
name: Time Frame
slug: plan-time-frame
image: /images/time-frame.png
description: >-
  Break down usage for for consumers based upon second, minutes, days, weeks,
  months, or other relevant time-frame for them to understand their usage.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Regions
Providing regional details available for access API resources and capabilities in different geographical regions as part of API plan usage.

```
name: Regions
slug: plan-regions
image: /images/regions.png
description: >-
  Providing regional details available for access API resources and capabilities
  in different geographical regions as part of API plan usage.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Elements
Offering other elements or features of an API that are included or not included within a plan to help API consumers understand scope of what is available.

```
name: Elements
slug: plan-elements
image: /images/elements.png
description: >-
  Offering other elements or features of an API that are included or not
  included within a plan to help API consumers understand scope of what is
  available.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Authentication
Distilling down the authentication required for an API, outlining API keys required, JWT, OAuth, and other authentication types, providing details on how to obtain accounts, tokens, and anything needed for accessing APIs.

```
name: Authentication
slug: authentication
scope: Business Contract
property: none
type: none
guidance: authentication/overview
image: /images/authentication.png
description: >-
  Distilling down the authentication required for an API, outlining API keys
  required, JWT, OAuth, and other authentication types, providing details on how
  to obtain accounts, tokens, and anything needed for accessing APIs.
policies:
  - authentication-keys
  - authentication-jwt
  - authentication-oauth
  - authentication-scopes
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Onboarding
  - Security
  - Access
  - Consistency
rules:
  - apis-json-apis-properties-authentication-info
```
## Keys
Require the API key usage meets standards set by authentication policies.

```
name: Keys
slug: authentication-keys
image: /images/keys.png
description: Require the API key usage meets standards set by authentication policies.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## JWT
Require JWT usage meets standards set by authentication policies.

```
name: JWT
slug: authentication-jwt
image: /images/jwt.png
description: Require JWT usage meets standards set by authentication policies.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## OAuth
Require that OAuth usage meets standards set by authentication policies.

```
name: OAuth
slug: authentication-oauth
image: /images/oauth.png
description: Require that OAuth usage meets standards set by authentication policies.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Scopes
Require Oauth scopes meets standards set by authentication policies.

```
name: Scopes
slug: authentication-scopes
image: /images/scopes.png
description: Require Oauth scopes meets standards set by authentication policies.
tags:
  - Properties
  - 3rd-Party
```
## Road Map
Providing a simple yet informative look at what features are being planned for future releases of an API, or even sharing that nothing is currently being planned--just providing any insight on what the future will hold.

```
name: Road Map
slug: road-map
scope: Business Contract
property: none
type: RoadMap
guidance: change/road-map
image: /images/road-maps.png
description: >-
  Providing a simple yet informative look at what features are being planned for
  future releases of an API, or even sharing that nothing is currently being
  planned--just providing any insight on what the future will hold.
tags:
  - GitHub
  - Issues
  - Labels
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Quality
  - Reliability
rules:
  - apis-json-apis-properties-road-map-info
```
## Date
The date for the proposed API change in the road map.

```
name: Date
slug: road-map-date
image: /images/dates.png
description: The date for the proposed API change in the road map.
tags:
  - Properties
  - 3rd-Party
```
## Title
The title for the proposed API change in the road map.

```
name: Title
slug: road-map-title
image: /images/names.png
description: The title for the proposed API change in the road map.
tags:
  - Properties
  - 3rd-Party
```
## Details
The description for the proposed API change in the road map.

```
name: Details
slug: road-map-details
image: /images/descriptions.png
description: The description for the proposed API change in the road map.
tags:
  - Properties
  - 3rd-Party
```
## Version
The version of the proposed API change in the road map.

```
name: Version
slug: road-map-version
image: /images/versions.png
description: The version of the proposed API change in the road map.
tags:
  - Properties
  - 3rd-Party
```
## Versioning
Providing semantic or date-based versioning for an API, offering an overview of what is adopted for an API and why, letting consumers know that their is change management in place and how they can tune into communication.

```
name: Versioning
slug: versioning
scope: Business Contract
property: none
type: Versioning
guidance: change/versioning
image: /images/versions.png
description: >-
  Providing semantic or date-based versioning for an API, offering an overview
  of what is adopted for an API and why, letting consumers know that their is
  change management in place and how they can tune into communication.
policies:
  - versioning-semantic-versioning
  - versioning-date-base
tags:
  - Semantic Versioning
  - Date Based Versioning
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Quality
  - Reliability
```
## Semantic Versioning
Require usage of major, minor, and patch Semantic Versioning for managing change.

```
name: Semantic Versioning
slug: versioning-semantic-versioning
image: /images/semantic-versioning.png
description: >-
  Require usage of major, minor, and patch Semantic Versioning for managing
  change.
tags:
  - Properties
  - 3rd-Party
```
## Date-Based Versioning
Require usage of date-base versioning for managing change.

```
name: Date-Based Versioning
slug: versioning-date-base
image: /images/date-based-versioning.png
description: Require usage of date-base versioning for managing change.
tags:
  - Properties
  - 3rd-Party
```
## Change Log
Having a change log of anything added, updated, or removed for an API, but also for the other operational and supporting resources for each API, ensuring there is a easy to read manifest of what has happened for an API.

```
name: Change Log
slug: change-log
scope: Business Contract
property: none
type: ChangeLog
guidance: change/change-log
image: /images/change-logs.png
description: >-
  Having a change log of anything added, updated, or removed for an API, but
  also for the other operational and supporting resources for each API, ensuring
  there is a easy to read manifest of what has happened for an API.
tags:
  - GitHub
  - Issues
  - Labels
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Quality
  - Reliability
rules:
  - apis-json-apis-properties-change-log-info
```
## Date
The date of the change that was made to an API.

```
name: Date
slug: change-log-date
image: /images/dates.png
description: The date of the change that was made to an API.
tags:
  - Properties
  - 3rd-Party
```
## Title
The title of the change that was made to an API.

```
name: Title
slug: change-log-title
image: /images/names.png
description: The title of the change that was made to an API.
tags:
  - Properties
  - 3rd-Party
```
## Details
The description of the change that was made to an API.

```
name: Details
slug: change-log-details
image: /images/descriptions.png
description: The description of the change that was made to an API.
tags:
  - Properties
  - 3rd-Party
```
## Version
The version of the change that was made to an API.

```
name: Version
slug: change-log-version
image: /images/versions.png
description: The version of the change that was made to an API.
tags:
  - Properties
  - 3rd-Party
```
## SDKs
Offering software development kits, or SDKs for an API, handling authentication, and working across all available API operations in a variety of relevant programming languages to the targeted consumers of an API.

```
name: SDKs
slug: sdks
scope: Business Contract
property: none
type: SDKs
guidance: code/software-development-kits
image: /images/sdks.png
description: >-
  Offering software development kits, or SDKs for an API, handling
  authentication, and working across all available API operations in a variety
  of relevant programming languages to the targeted consumers of an API.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Alignment
  - Automation
  - Change
  - Consistency
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-sdk-info
```
## JavaScript
Require a JavaScript client SDK available with each API.

```
name: JavaScript
slug: sdks-javascript
image: /images/javascript.png
description: Require a JavaScript client SDK available with each API.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-sdk-node-info
```
## PHP
Require a PHP client SDK available with each API.

```
name: PHP
slug: sdks-php
image: /images/php.png
description: Require a PHP client SDK available with each API.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Java
Require a Java client SDK available with each API.

```
name: Java
slug: sdks-java
image: /images/java.png
description: Require a Java client SDK available with each API.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-sdk-java-info
```
## Go
Require a Go client SDK available with each API.

```
name: Go
slug: sdks-go
image: /images/go.png
description: Require a Go client SDK available with each API.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-sdk-go-info
```
## CSharp
Require a CSharp client SDK available with each API.

```
name: CSharp
slug: sdks-csharp
image: /images/csharp.png
description: Require a CSharp client SDK available with each API.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Status
Making an API status page, monitoring reports, or other real-time updates regarding the uptime and availability of an API, providing current, but also the historical status of API, helping maintain trust with API consumers.

```
name: Status
slug: status
scope: Business Contract
property: none
type: Status
guidance: monitoring/uptime
image: /images/status.png
description: >-
  Making an API status page, monitoring reports, or other real-time updates
  regarding the uptime and availability of an API, providing current, but also
  the historical status of API, helping maintain trust with API consumers.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Automation
  - Communication
  - Quality
  - Reliability
rules:
  - apis-json-apis-properties-status-info
```
## Status Dashboard
Require a link to as well as results from a status dashboard for an API.

```
name: Status Dashboard
slug: status-dashboard
image: /images/dashboard.png
description: Require a link to as well as results from a status dashboard for an API.
tags:
  - Testing
```
## Status History
Require a link to as well as results from a status history for an API.

```
name: Status History
slug: status-history
image: /images/history.png
description: Require a link to as well as results from a status history for an API.
tags:
  - Testing
```
## Performance
Publishing details regarding the performance of APIs, complimenting status and uptime information, but drilling into more detail regarding speed, latency, and other performance related metrics that matter to API consumers.

```
name: Performance
slug: performance
scope: Business Contract
property: none
type: Performance
guidance: monitoring/performance
image: /images/performance.png
description: >-
  Publishing details regarding the performance of APIs, complimenting status and
  uptime information, but drilling into more detail regarding speed, latency,
  and other performance related metrics that matter to API consumers.
tags:
  - Testing
solutions:
  - Automation
  - Communication
  - Quality
  - Reliability
rules:
  - apis-json-apis-properties-performance-info
```
## Latency
Requiring details regarding the regular latency for each available API.

```
name: Latency
slug: performance-latency
image: /images/latency.png
description: Requiring details regarding the regular latency for each available API.
tags:
  - Testing
```
## Response Time
Requiring details regarding the regular response time for each available API.

```
name: Response Time
slug: performance-response-time
image: /images/response-time.png
description: Requiring details regarding the regular response time for each available API.
tags:
  - Testing
```
## Security
Providing an overview of security practices for an API, including details covered as part of authentication and access management, but also security testing and certifications that matter to API consumers.

```
name: Security
slug: security
image: /images/security.png
description: >-
  Providing an overview of security practices for an API, including details
  covered as part of authentication and access management, but also security
  testing and certifications that matter to API consumers.
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Reliability
  - Quality
  - Change
  - Security
  - Access
  - Consistency
rules:
  - apis-json-apis-properties-security-info
```
## Authentication
Require details regarding how authentication is handled as part of API security.

```
name: Authentication
slug: security-authentication
image: /images/authentication.png
description: >-
  Require details regarding how authentication is handled as part of API
  security.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## OWASP
Require that OWASP API security top ten has been applied as part of API security.

```
name: OWASP
slug: security-owasp-top-10
image: /images/owasp.png
description: >-
  Require that OWASP API security top ten has been applied as part of API
  security.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Testing
Require that security testing has occurred and publishing results for API security.

```
name: Testing
slug: security-testing
image: /images/security.png
description: >-
  Require that security testing has occurred and publishing results for API
  security.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Support
Outline what support is available for API consumers, including email, tickets, forums, and paid support services, making it easy for API consumers to understand how they can get the help they need across APIs.

```
name: Support
slug: support
scope: Business Contract
property: none
type: none
guidance: support/overview
image: /images/support.png
description: >-
  Outline what support is available for API consumers, including email, tickets,
  forums, and paid support services, making it easy for API consumers to
  understand how they can get the help they need across APIs.
policies:
  - support-email
  - support-issues
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Discovery
  - Quality
  - Reliability
  - Simplicity
rules:
  - apis-json-apis-properties-support-support-info
```
## Support Email
Require that an API is supported using email.

```
name: Support Email
slug: support-email
image: /images/email.png
description: Require that an API is supported using email.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-support-email-info
```
## Support Issues
Require that an API is supported using Git issues.

```
name: Support Issues
slug: support-issues
image: /images/issues.png
description: Require that an API is supported using Git issues.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-support-issues-info
```
## Feedback
Providing feedback on the business and technical details of each API contract, helping facilitate feedback from consumers and other stakeholders, but also from the learnings across other private and public API contracts in use.

```
name: Feedback
slug: feedback
image: /images/feedback.png
description: >-
  Providing feedback on the business and technical details of each API contract,
  helping facilitate feedback from consumers and other stakeholders, but also
  from the learnings across other private and public API contracts in use.
policies:
  - feedback-issues
tags:
  - Support
  - 3rd-Party
  - Producers
```
## Feedback Issues
Allow for teams to receive feedback on API contracts via Git issue.

```
name: Feedback Issues
slug: feedback-issues
image: /images/issues.png
description: Allow for teams to receive feedback on API contracts via Git issue.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-feedback-issues-info
```
## Questions
Empowering teams to ask questions via issue or discussion via Git repository, or directly via email about the API lifecycle, governance, as well as the business or technical elements of producing an API for wider consumption.

```
name: Questions
slug: questions
image: /images/questions.png
description: >-
  Empowering teams to ask questions via issue or discussion via Git repository,
  or directly via email about the API lifecycle, governance, as well as the
  business or technical elements of producing an API for wider consumption.
policies:
  - questions-issues
tags:
  - Support
  - 3rd-Party
  - Producers
```
## Questions Issues
Allow for teams to ask questions and get answers via Git Issues.

```
name: Questions Issues
slug: questions-issues
image: /images/issues.png
description: Allow for teams to ask questions and get answers via Git Issues.
tags:
  - Policies
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-questions-issues-info
```
## Terms of Service
Making sure that terms of service are front and center for API consumers, ensuring that the legal side of using API resources and capabilities in applications and integrations by 3rd party consumers is covered.

```
name: Terms of Service
slug: terms-of-service
image: /images/terms-of-service.png
description: >-
  Making sure that terms of service are front and center for API consumers,
  ensuring that the legal side of using API resources and capabilities in
  applications and integrations by 3rd party consumers is covered.
policies:
  - None
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Change
  - Legal
rules:
  - apis-json-apis-properties-terms-of-service-info
```
## Privacy Policy
Publishing a privacy policy covering the producer and consumers of an API, as well as end-users of applications, adding to the legal resources that are available to 3rd party developers when putting APIs to work.

```
name: Privacy Policy
slug: privacy-policy
image: /images/privacy-policy.png
description: >-
  Publishing a privacy policy covering the producer and consumers of an API, as
  well as end-users of applications, adding to the legal resources that are
  available to 3rd party developers when putting APIs to work.
policies:
  - None
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Reliability
  - Quality
  - Access
  - Legal
rules:
  - apis-json-apis-properties-privacy-policy-info
```
## Licensing
Publishing a license for the interface, client code, server code, and data to ensure consumers understand the legal implications of using the API, code, and data into their own applications and integrations.

```
name: Licensing
slug: licensing
image: /images/licenses.png
description: >-
  Publishing a license for the interface, client code, server code, and data to
  ensure consumers understand the legal implications of using the API, code, and
  data into their own applications and integrations.
policies:
  - None
tags:
  - Policies
  - 3rd-Party
  - Producers
solutions:
  - Onboarding
  - Change
  - Consistency
  - Legal
rules:
  - apis-json-apis-properties-license-info
```
## Guidance
Ensuring there is Just-in-Time API Guidance (TM) available throughout the life of an API contract, providing links to technological, business, and more policy focused guidance that helps teams producing API through their journey.

```
name: Guidance
slug: guidance
image: /images/guidance.png
description: >-
  Ensuring there is Just-in-Time API Guidance (TM) available throughout the life
  of an API contract, providing links to technological, business, and more
  policy focused guidance that helps teams producing API through their journey.
policies:
  - guidance-technical
  - guidance-business
  - guidance-policies
  - guidance-people
tags:
  - Support
  - 3rd-Party
  - Producers
```
## Technical
Provide access to technical API guidance as part of API contract support.

```
name: Technical
slug: guidance-technical
image: /images/technical.png
description: Provide access to technical API guidance as part of API contract support.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Business
Provide access to business API guidance as part of API contract support.

```
name: Business
slug: guidance-business
image: /images/business.png
description: Provide access to business API guidance as part of API contract support.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## policies
Provide access to API policy guidance as part of API contract support.

```
name: policies
slug: guidance-policies
image: /images/policies.png
description: Provide access to API policy guidance as part of API contract support.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## people
Provide access to people API guidance as part of API contract support.

```
name: people
slug: guidance-people
image: /images/people.png
description: Provide access to people API guidance as part of API contract support.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Provenance
Helping curate the provenance of each API contract as it evolves over time, documenting change, and cataloging the reviews, validation, certification, and conversation that occurs as each API moves forward and matures over time.

```
name: Provenance
slug: provenance
image: /images/provenance.png
description: >-
  Helping curate the provenance of each API contract as it evolves over time,
  documenting change, and cataloging the reviews, validation, certification, and
  conversation that occurs as each API moves forward and matures over time.
policies:
  - provenance-issues
  - provenance-pull-requests
  - provenance-reviews
  - provenance-certifications
tags:
  - Support
  - 3rd-Party
  - Producers
```
## Issues
Provide the provenance of an API contract using Git issues.

```
name: Issues
slug: provenance-issues
image: /images/issues.png
description: Provide the provenance of an API contract using Git issues.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Pull Requests
Provide the provenance of an API contract using Git pull requests.

```
name: Pull Requests
slug: provenance-pull-requests
image: /images/pull-requests.png
description: Provide the provenance of an API contract using Git pull requests.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Reviews
Provide the provenance of an API contract using API governance reviews.

```
name: Reviews
slug: provenance-reviews
image: /images/reviews.png
description: Provide the provenance of an API contract using API governance reviews.
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Certifications
Provide the provenance of an API contract using regular certifications

```
name: Certifications
slug: provenance-certifications
image: /images/certifications.png
description: Provide the provenance of an API contract using regular certifications
tags:
  - Policies
  - 3rd-Party
  - Producers
```
## Policies
Providing the machine-readable policies that link machine-readable rules with the business reasons why we are governing an API and the operations around it, helping organize rules based upon the business reasoning behind them.

```
name: Policies
slug: policies
image: /images/policies.png
description: >-
  Providing the machine-readable policies that link machine-readable rules with
  the business reasons why we are governing an API and the operations around it,
  helping organize rules based upon the business reasoning behind them.
policies:
  - None
tags:
  - Support
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-policies-info
```
## Rules
Providing the machine-readable rules used to govern an API that can be used as part of pipelines or other automation to lint an API, making sure the baseline for each API and the operations around it are available as part of the contract.

```
name: Rules
slug: rules
image: /images/rules.png
description: >-
  Providing the machine-readable rules used to govern an API that can be used as
  part of pipelines or other automation to lint an API, making sure the baseline
  for each API and the operations around it are available as part of the
  contract.
policies:
  - None
tags:
  - Support
  - 3rd-Party
  - Producers
```
## Guidance
Ensuring there is guidance for teams throughout their API journey, providing simple text and video guidance for all of the topics business and engineering teams will encounter as part of their regular work to produce consistent APis.

```
name: Guidance
slug: guidance
image: /images/guidance.png
description: >-
  Ensuring there is guidance for teams throughout their API journey, providing
  simple text and video guidance for all of the topics business and engineering
  teams will encounter as part of their regular work to produce consistent APis.
policies:
  - None
tags:
  - Support
  - 3rd-Party
  - Producers
rules:
  - apis-json-apis-properties-rules-info
```
## GitHub Organization
A GitHub organization provides a dedicated workspaces for teams to produce APIs, organize all the API contracts in motion, and leverage source countrol, CI/CD, teams, and other resources provided by GitHub to manage API operations.

```
name: GitHub Organization
slug: github-organization
scope: Business Contract
property: none
type: GitHubOrganization
guidance: workspaces/github-organization
image: /images/github-organization.png
description: >-
  A GitHub organization provides a dedicated workspaces for teams to produce
  APIs, organize all the API contracts in motion, and leverage source countrol,
  CI/CD, teams, and other resources provided by GitHub to manage API operations.
tags:
  - GitHub
  - Repositories
  - Source Control
solutions:
  - Access
  - Automation
  - Communication
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-github-organization-info
```
## Teams
GitHub organizations allow for the management of people and teams to help define who has access to repositories, contracts, and other assets managed via this dedicated domain workspace.

```
name: Teams
slug: github-organization-teams
scope: Business Contract
property: none
type: GitHubTeams
guidance: workspaces/github-organization-teams
image: /images/teams.png
description: >-
  GitHub organizations allow for the management of people and teams to help
  define who has access to repositories, contracts, and other assets managed via
  this dedicated domain workspace.
tags:
  - Teams
```
## Repositories
GitHub organizations provide teams with the ability to create repositories for managing API contracts, separating and organizing contracts by meaningful bounded contexts within a specific domain.

```
name: Repositories
slug: github-organization-repositories
scope: Business Contract
property: none
type: GitHubTeams
guidance: workspaces/github-organization-repositories
image: /images/teams.png
description: >-
  GitHub organizations provide teams with the ability to create repositories for
  managing API contracts, separating and organizing contracts by meaningful
  bounded contexts within a specific domain.
tags:
  - Teams
```
## README
GitHub organization provide the ability to have a dedicated README, providing a single landing page for the API workspace of a domain, line of business, or domain, where all API contracts can be found and searched.

```
name: README
slug: github-organization-readme
scope: Business Contract
property: none
type: GitHubReadme
guidance: workspaces/github-organization-readme
image: /images/readme.png
description: >-
  GitHub organization provide the ability to have a dedicated README, providing
  a single landing page for the API workspace of a domain, line of business, or
  domain, where all API contracts can be found and searched.
tags:
  - README
```
## Postman Workspace
A Postman Workspace provides a dedicated space to manage API contracts within a domain, complimenting other types of workspaces, allowing for private, partner, and public workspaces to exist for managing API operations.

```
name: Postman Workspace
slug: postman-workspace
scope: Business Contract
property: none
type: PostmanWorkspace
guidance: workspaces/postman-workspace
image: /images/postman-workspace.png
description: >-
  A Postman Workspace provides a dedicated space to manage API contracts within
  a domain, complimenting other types of workspaces, allowing for private,
  partner, and public workspaces to exist for managing API operations.
tags:
  - Postman
  - Workspaces
  - Automation
solutions:
  - Access
  - Automation
  - Communication
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-postman-public-workspace-info
```
## Blogs
A blog helps provide a regular channel for publishing relevant stories and information for both producers and consumers of an API, providing a simple, informative, and recurring way to stay in engaged and receive regular updates about an API.

```
name: Blogs
slug: blogs
scope: Business Contract
property: none
type: Blogs
guidance: communication/blog
image: /images/blogs.png
description: >-
  A blog helps provide a regular channel for publishing relevant stories and
  information for both producers and consumers of an API, providing a simple,
  informative, and recurring way to stay in engaged and receive regular updates
  about an API.
tags:
  - Blog
  - Stories
  - Updates
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-blog-feed-info
```
## Blog Feeds
A blog RSS or Atom feed provides a simple way to syndicate information and updates about APIs with producers and consumers, allowing it to be pushed out to where they are located and regularly consuming information, without having to visit a blog.

```
name: Blog Feeds
slug: blog-feeds
scope: Business Contract
property: none
type: BlogFeeds
guidance: communication/blog-feeds
image: /images/blog-feeds.png
description: >-
  A blog RSS or Atom feed provides a simple way to syndicate information and
  updates about APIs with producers and consumers, allowing it to be pushed out
  to where they are located and regularly consuming information, without having
  to visit a blog.
tags:
  - Blog
  - Stories
  - Updates
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-blog-feed-info
```
## Videos
Videos offer an engaging way to provide information and updates with producers nad consumers of APIs, demonstrating how an API can be used, providing webinars, workshops, and other useful videos about what is happening with an API.

```
name: Videos
slug: videos
scope: Business Contract
property: none
type: Videos
guidance: communication/videos
image: /images/videos.png
description: >-
  Videos offer an engaging way to provide information and updates with producers
  nad consumers of APIs, demonstrating how an API can be used, providing
  webinars, workshops, and other useful videos about what is happening with an
  API.
tags:
  - Videos
  - Stories
  - Updates
solutions:
  - Alignment
  - Change
  - Communication
  - Consistency
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-video-info
```
## Governance
Governance standardizes APIs across teams using a common platform and lifecycle, applying governance policies and rules, and keeping everyone moving in the same direction using common guidance.

```
name: Governance
slug: governance
scope: Business Contract
property: none
type: none
guidance: governance/overview
image: /images/governance.png
description: >-
  Governance standardizes APIs across teams using a common platform and
  lifecycle, applying governance policies and rules, and keeping everyone moving
  in the same direction using common guidance.
policies:
  - governance-policies
  - governance-operational-rules
  - governance-api-rules
  - governance-lifecycle
  - governance-vocabulary
tags:
  - Governance
solutions:
  - Access
  - Alignment
  - Automation
  - Change
  - Communication
  - Consistency
  - Discovery
  - Legal
  - Onboarding
  - Quality
  - Reliability
  - Security
  - Self-Service
  - Simplicity
```
## Policies
Human and machine-readable policies that define an aspect of API operations, which are always kept in alignment with business objectives.

```
name: Policies
slug: governance-policies
image: /images/policies.png
description: >-
  Human and machine-readable policies that define an aspect of API operations,
  which are always kept in alignment with business objectives.
tags:
  - Governance
rules:
  - apis-json-apis-properties-policies-info
```
## Operational Rules
Spectral rules that apply to the operational level, linting APIs.json.

```
name: Operational Rules
slug: governance-operational-rules
image: /images/rules.png
description: Spectral rules that apply to the operational level, linting APIs.json.
tags:
  - Governance
rules:
  - apis-json-apis-properties-apis-json-rules-info
```
## API Rules
Spectral rules that apply to the API level, linting OpenAPI.

```
name: API Rules
slug: governance-api-rules
image: /images/rules.png
description: Spectral rules that apply to the API level, linting OpenAPI.
tags:
  - Governance
rules:
  - apis-json-apis-properties-openapi-rules-info
```
## Lifecycle
A human and machine-readable schema of the common and agreed upon API lifecycle.

```
name: Lifecycle
slug: governance-lifecycle
image: /images/lifecycle.png
description: >-
  A human and machine-readable schema of the common and agreed upon API
  lifecycle.
tags:
  - Governance
rules:
  - apis-json-apis-properties-lifecycle-info
```
## Vocabulary
A formal vocabulary of words and phrases that can and cannot be used across operations.

```
name: Vocabulary
slug: governance-vocabulary
image: /images/lifecycle.png
description: >-
  A formal vocabulary of words and phrases that can and cannot be used across
  operations.
tags:
  - Governance
rules:
  - apis-json-apis-properties-vocabulary-info
```
## Standards
Internet, industry, market, and government standards help make APIs more consistent, but also save time and money for both producer and consumer, while keeping APIs better aligned with existing industry areas of interoperability and reuse.

```
name: Standards
slug: standards
scope: Business Contract
property: none
type: none
guidance: standards/overview
image: /images/standards.png
description: >-
  Internet, industry, market, and government standards help make APIs more
  consistent, but also save time and money for both producer and consumer, while
  keeping APIs better aligned with existing industry areas of interoperability
  and reuse.
policies:
  - standards-http
  - standards-json
  - standards-yaml
  - standards-openapi
  - standards-json-schema
  - standards-spectral
tags:
  - Standards
solutions:
  - Access
  - Alignment
  - Automation
  - Change
  - Communication
  - Consistency
  - Discovery
  - Legal
  - Onboarding
  - Quality
  - Reliability
  - Security
  - Self-Service
  - Simplicity
```
## HTTP
The Hyper Text Transfer Protocol (HTTP) from the IETF.

```
name: HTTP
slug: standards-http
image: /images/http.png
description: The Hyper Text Transfer Protocol (HTTP) from the IETF.
tags:
  - Standards
```
## JSON
Using the JavaScript Object Notation (JSON) format.

```
name: JSON
slug: standards-json
image: /images/json.png
description: Using the JavaScript Object Notation (JSON) format.
tags:
  - Standards
```
## YAML
Using the Yet Another Markdown Language (YAML) format.

```
name: YAML
slug: standards-yaml
image: /images/yaml.png
description: Using the Yet Another Markdown Language (YAML) format.
tags:
  - Standards
```
## OpenAPI
Using the OpenAPI specification to describe HTTP APIs.

```
name: OpenAPI
slug: standards-openapi
image: /images/openapi.png
description: Using the OpenAPI specification to describe HTTP APIs.
tags:
  - Standards
  - Linux Foundation
```
## JSON Schema
Using the JSON Schema to define and validate models.

```
name: JSON Schema
slug: standards-json-schema
image: /images/json-schema.png
description: Using the JSON Schema to define and validate models.
tags:
  - Standards
  - Validation
```
## Spectral
Using the Spectral to define linting rules for APIs.

```
name: Spectral
slug: standards-spectral
image: /images/spectral.png
description: Using the Spectral to define linting rules for APIs.
tags:
  - Standards
  - Linting
  - RUles
```
## Problem Details for HTTP APIs
Using the  Problem Details for HTTP APIs standard for errors.

```
name: Problem Details for HTTP APIs
slug: problem-details-for-http-apis
image: /images/errors.png
description: Using the  Problem Details for HTTP APIs standard for errors.
tags:
  - Standards
  - Errors
```
## Portals
Dedicated developer portals for an API provide a way to make documentation, sign-up, getting started, plans, SDKs, and other resources API consumers need more easily accessible publicly or privately to a specific audience.

```
name: Portals
slug: portals
scope: Business Contract
property: none
type: none
guidance: portals/overview
image: /images/portals.png
description: >-
  Dedicated developer portals for an API provide a way to make documentation,
  sign-up, getting started, plans, SDKs, and other resources API consumers need
  more easily accessible publicly or privately to a specific audience.
tags:
  - Portals
solutions:
  - Access
  - Alignment
  - Communication
  - Discovery
  - Onboarding
  - Self-Service
rules:
  - apis-json-apis-properties-portal-info
```
## Teams
Requiring at least one product and one engineering, as well as other potential stakeholders involved through the API lifecycle from define to production, ensuring there is always someone actively owning and leading APIs forward.

```
name: Teams
slug: teams
scope: Business Contract
property: none
type: Teams
guidance: organization/teams
image: /images/teams.png
description: >-
  Requiring at least one product and one engineering, as well as other potential
  stakeholders involved through the API lifecycle from define to production,
  ensuring there is always someone actively owning and leading APIs forward.
tags:
  - Teams
rules:
  - apis-json-apis-properties-teams-info
```
