# University Digital Libraries & Research Infrastructure

**Proxmox VE · Ubuntu Server · SudanREN · Koha · DSpace**

A university infrastructure project in Sudan involving an on-campus physical server, a Proxmox VE virtualization environment, an Ubuntu Server VM, and the Koha and DSpace platforms serving university libraries and academic research.

![Conceptual infrastructure architecture](assets/university-infrastructure.svg)

## Project scope

- Installed and configured a physical university server using **Proxmox VE**.
- Deployed **Ubuntu Server** in a virtual machine to host library platforms.
- Connected academic services via a public IP address through **SudanREN**, Sudan's research and education network.
- Installed and configured **Koha** for library management and **DSpace** for research publications and digital collections.
- Enabled access for faculty and students.
- Configured library staff accounts to catalog books and manage scholarly publications.
- Set up synchronization with a central university server in the Sudanese Ministry of Higher Education and Scientific Research environment, as reported by the project engineer.

## Architecture

Physical server → Proxmox VE → Ubuntu Server VM → Koha / DSpace → SudanREN connectivity.

Staff catalog and maintain library resources. Faculty and students access publications remotely. The synchronization mechanism and sensitive network details are intentionally not disclosed.

## Engineering responsibilities

Server installation · Proxmox configuration · Linux administration · Research-network connectivity · Digital library deployment · Accounts and permissions · Institutional integration.

## Full case study

[English](https://fatihmh.online/university-digital-libraries-koha-dspace/) · [العربية](https://fatihmh.online/ar/university-digital-libraries-koha-dspace-ar/) · [Français](https://fatihmh.online/fr/bibliotheques-numeriques-koha-dspace-universite/)

## Documentation languages

[العربية](docs/README.ar.md) · [Français](docs/README.fr.md)

## Confidentiality

This is a high-level professional case study and **not** the university's production configuration. No real IP addresses, server hostnames, authentication data, institutional identifiers or private integration settings are provided. Exact application versions and synchronization protocols have not been verified independently.

© 2026 Elfatih Mohamed Hameid Farah. All rights reserved.
