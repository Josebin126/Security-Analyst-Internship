# Task 1: Basic Network Scanning with Nmap

## Objective

Perform a network scan to identify open ports and services using Nmap.

## Tool Used

* Nmap 7.99
* Zenmap

## Target

127.0.0.1 (Localhost)

## Scan Results

### Port 135 (MSRPC)

Microsoft Remote Procedure Call service used for communication between Windows applications and services.

### Port 445 (Microsoft-DS)

Used for SMB (Server Message Block) file sharing and printer sharing on Windows systems.

## Findings

The scan identified two open ports:

* 135/tcp (MSRPC)
* 445/tcp (SMB)

## Conclusion

Nmap successfully detected open ports and services running on the local Windows machine. Understanding open ports helps identify potential security risks and monitor network services.
