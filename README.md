# OIDC Migrator

A tool to easily migrate from Old AWS Users & Groups management to Identity Center and away from Secret Key management!

## TODO

- AWS migrated from "User & Groups" to "Identity Center"
  - Move existing users & groups to Identity Center
- Get Initial AWS Root account access (ACCESS_KEY / SECRET_ACCESS_KEY)
  - Create roles in AWS for OIDC request/verification
  - Configure the 3rd party provider to remove ACCESS_KEY and use OIDC instead
