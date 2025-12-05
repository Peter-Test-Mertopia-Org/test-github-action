# Test GitHub Action

Testing auto-merge release branch workflow.

## Branches

- `main` - Main branch
- `develop` - Development branch
- `release/v0.146` - Release v0.146
- `release/v0.147` - Release v0.147
- `release/v0.148` - Release v0.148

## Test Scenario

1. Push a change to `release/v0.146`
2. Workflow should auto-merge to:
   - `develop`
   - `release/v0.147`
   - `release/v0.148`
