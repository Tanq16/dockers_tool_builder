# ARCHIVED - Incorporated into CST

---

### Security Docker Tool Builder

This repo builds a tool docker once a month for all golang executables to be used for the Security Docker container at the [CST](https://github.com/tanq16/containerized-security-toolkit) repo. It also build NeoVIM for all containers of CST (this is needed because ARM .deb files cannot be extracted from a container without pushing to a registry in GitHub runners). The docker containers from this repo are used for multi-stage builds for the security docker, where executables are copied from this docker to the security docker.
