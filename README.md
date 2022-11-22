# Intersight Cloud Orchestrator - Get VMware Virtual Machine Guest IP 
###### Filename: `Export_Task_GetVMwareVirtualMachineGuestIP.json`
###### Category: `Virtualization`

## Use Case
Custom Task based on Web API Executor to retrieve a Virtual Machine Guest IP Address leveraging vCenter API

### Inputs

- vCenter Target (mandatory)
- Virtual Machine Name (mandatory)

### Outputs

- Virtual Machine IP

## Claimed Targets

- vCenter

## Prerequisites

- vCenter is claimed on Intersight
- Virtual Machine runs vmtools (vCenter is aware of its IP Address)

