# Task 7: Monitor System Resources Using Netdata

## Objective
Install and visualize system and app performance metrics using Netdata.

## Tools Used
- Netdata (Docker container)
- CentOS (Linux)

## Steps Performed
1. Installed Docker.
2. Pulled and ran the Netdata container:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
# Netdate-Project
