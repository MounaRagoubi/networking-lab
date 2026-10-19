# Subnetting Practice

## Objective

Practice basic IPv4 subnetting and network calculations.

## Example

Given the network:

`192.168.1.0/24`

If the network is divided into 4 subnets, each subnet uses a `/26` mask.

## Subnets

### Subnet 1
- Network: `192.168.1.0/26`
- Host range: `192.168.1.1 - 192.168.1.62`
- Broadcast: `192.168.1.63`

### Subnet 2
- Network: `192.168.1.64/26`
- Host range: `192.168.1.65 - 192.168.1.126`
- Broadcast: `192.168.1.127`

### Subnet 3
- Network: `192.168.1.128/26`
- Host range: `192.168.1.129 - 192.168.1.190`
- Broadcast: `192.168.1.191`

### Subnet 4
- Network: `192.168.1.192/26`
- Host range: `192.168.1.193 - 192.168.1.254`
- Broadcast: `192.168.1.255`

## What I Learned

- How CIDR notation works
- How to divide a network into smaller subnets
- How to identify network and broadcast addresses
- How to calculate valid host ranges
