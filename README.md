# cluster-olympus
Integration Cluster for the club Golang Buddies

## RBAC

### Platform Team

- `platform-team-admin`: user role with admin privileges on the entire cluster.
- `platform-team`: user role with read-write privileges on the entire cluster.
- `platform-team-guest`: user role with read-only privileges on the entire cluster.

### Dev Buddy Project

- `dev-buddy-admin`: user role with admin privileges to the dev-buddy namespace.
- `dev-buddy-dev`: user role with read-only privileges to the dev-buddy namespace.
- `dev-buddy-lead`: user role with read-write privileges to the dev-buddy namespace.
- `dev-buddy-deploy`: bot role to integrate in project cd for deployment.
