# mq_scan
Scans an IBM MQ instance for unauthenticated access to admin channels.

## Usage
```
python mq_scan.py <IP> <PORT>
```

## Exploiting MQ
Connect to the queue manager using MQ explorer and the details found by the scanner.
Create a service with the desired command and arguments.
Start the service.

## Requirements

This script requires the pymqi library to be installed.
