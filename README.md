# XML External Entity Lab

Educational XML external entity lab with vulnerability analysis and remediation notes.

**Python · XML · Docker**

## Learning focus

External entity resolution and unintended access to server resources.

## Repository guide

| Resource | Location |
| --- | --- |
| Assessment | [Readme.md](Readme.md) |
| Remediation | [Fix.md](Fix.md) |
| Compose configuration | [docker-compose.yml](docker-compose.yml) |

## Inspect the lab

1. Read the assessment and remediation notes together.
2. Inspect the Dockerfile and Compose configuration before running the application.
3. Use an isolated local environment for authorized training. The supplied Compose file publishes a host port; it is not a production deployment configuration.
4. Record observations and compare them with the mitigation notes.

## Setup requirements

Docker with Compose is required for the supplied container configuration. The lab directory is `the repository root`.

Container builds and vulnerability demonstrations have not been revalidated as part of this documentation update.

---

Part of [Osama Alsmadi’s project portfolio](https://github.com/osamaalsmadi).
