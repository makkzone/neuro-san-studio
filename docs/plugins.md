# Plugins

Plugins are a way to extend the functionality of a Neuro SAN server largely for deployment-related use-cases.
Note that plugins are never required for Neuro SAN to function.

Here are a few examples ordered by level of complexity.

<!-- TOC -->

- [Plugins](#plugins)
  - [Authorization](#authorization)
    - [Open FGA](#open-fga)

<!-- TOC -->

## Authorization

Authorization plugins allow user-by-user access control to Agent Networks.
This is not to be confused with _authentication_, which is the process of verifying a user's identity.

### Open FGA

[Open FGA](../plugins/authorization/openfga/README.md) is a plugin that extends the authorization capabilities
of a Neuro SAN server using a free and open source Open FGA server to do Relation-Based Access Control (ReBAC)
authorization.
