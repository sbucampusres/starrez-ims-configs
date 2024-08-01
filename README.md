# StarRez IMS Configurations

Welcome to the **StarRez IMS Configurations** repository. This repository contains a collection of IMS files used for integrating and managing housing operations at Stony Brook University. The repository is organized into two main sections: **User IMS** and **Cloud IMS**.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [User IMS](#user-ims)
- [Cloud IMS](#cloud-ims)
- [Getting Started](#getting-started)

## Overview

This repository contains a variety of IMS files that support operations such as data imports, cancellations, room space management, billing, and access control. The IMS files facilitate integration with external systems like PeopleSoft, Lenel, and CBORD.

## Repository Structure

```
starrez-ims-configs/
├── User IMS/
│   ├── (various IMS files)
└── Cloud IMS/
    ├── (import scripts for automated tasks)
```

### User IMS

The **User IMS** folder contains IMS files that are manually executed to support specific housing operations. These files are used for tasks such as:

- Booking and cancellations
- Damage billing
- Student profile management
- Room space closures

**Example Files:**

- `Booking_Import.ims`: Handles booking imports.
- `DamageBilling-Sample.ims`: Manages damage billing operations.
- `Application_Cancellations.ims`: Manages booking cancellations.

### Cloud IMS

The **Cloud IMS** folder contains import scripts that are scheduled and automated for regular data integration tasks. These scripts are designed to streamline processes and reduce manual intervention.

**Example Files:**

- `Automated_Booking_Import.ims`: Runs scheduled booking imports.
- `Scheduled_PeopleSoft_Import.ims`: Integrates PeopleSoft data on a schedule.
- `CBORD_Reconcile_Automated.ims`: Automates the reconciliation process with CBORD.

## Getting Started

### Prerequisites

To utilize the IMS files, ensure you have access to the StarRez system and have appropriate permissions for executing these scripts. Additionally, ensure any automated scripts are properly configured in your cloud environment.

### Execution

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/sbucampusres/starrez-ims-configs.git
   ```
2. Navigate to the folder of your choice (User IMS or Cloud IMS).
   ```
   cd starrez-ims-configs/User\ IMS
   ```
3. ???
4. Profit
