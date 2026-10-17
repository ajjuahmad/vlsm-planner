# VLSM Planner

Split one IPv4 network into right-sized subnets. Enter a parent block such as 192.168.10.0/24 and the number of hosts each department needs.

**Live demo:** https://ajjuahmad.github.io/vlsm-planner/

## How it works

Each subnet needs hosts + 2 addresses (network and broadcast), rounded up to the next power of two, with a minimum block of /30. Subnets are sorted largest first and placed one after another, each aligned to its block boundary. The table shows network, mask, first and last host, broadcast and usable hosts, and the tool reports when the parent block runs out of space.

## Run it locally

It is a single `index.html` file with no build step. Download it and open it in a browser.

## About

Sample project by [Ejaz Ahemad](https://ajjuahmad.github.io), built with AI assistance. Networking tool.
