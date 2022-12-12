# Holonym monorepo

## Structure

    .
    ├── contracts
    ├── zk                      # Includes circuits and helpers for interacting with them
    ├── issuers
    │   ├── government-id
    │   └── phone
    ├── frontend
    │   ├── app                 # app.holonym.id
    │   └── home                # holonym.id
    ├── relayer
    ├── holonym-api             # HTTPS API for querying smart contracts
    ├── storage                 # Backend services for storing and retrieving encrypted user data
    ├── mobile-app
    ├── constants               # For contract addresses, ABIs, server URLs, etc.
    ├── utils
    ├── dashboards
    │   └── metrics-dashboard   # metrics.holonym-internal.net
    └── infrastructure          # Terraform for provisioning infrastructure
