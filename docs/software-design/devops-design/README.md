# DevOps Design

We use **Drone** to run the CI/CD pipeline.

## Backend Service CI/CD

- For each backend service, runs the following stages:
    1. Dependencies Resolving & Compile
    2. Unit Test
    3. Integration Test (DB)
    4. E2E Test
    5. Code Quality Inspection
    6. Kubernetes Deployment
    
## Frontend Web App CI/CD

- For each backend service, runs the following stages:
    1. Dependencies Resolving & Compile
    2. Unit Test
    3. E2E Test
    4. Code Quality Inspection
    5. Kubernetes Deployment

Next: [Deployment Design](software-design/deployment-design/)

