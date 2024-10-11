# APISpecifications
This repository contains all API Specifications, also known as API Documents.

## Conventions
1. Each subdirectory represents an API Specification.  Each subdirectory represents a noun, managed by the operations defined in an API Specification, for example, the "organizations" subdirectory represents the API Specification used to manage organizations.
2. Under the noun subdirectory, the next level subdirectory represents a major version of an API Specification, for example, the "v1" subdirectory under the "organizations" noun represents version one of the organizations API Specification.
3. Under the major version subdirectory, the next level includes a "schema" subdirectory, an "example" subdirectory as well as the OpenAPI Specification files.  The "schema" subdirector contains the message payload schema files.  The "example" subdirectory contains example instances of the message payload schemas.
4. An OpenAPI Specification file includes in the filename, the term "open-api".
5. An OpenAPI Specificiation file, that is self-contained where schema definitions are local to the file, includes in the filename the term "open-api-bundle".
