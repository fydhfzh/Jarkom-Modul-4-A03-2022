# Jarkom-Modul-4-A03-2022

# VLSM / CPT

## Topologi

![image](https://user-images.githubusercontent.com/72655301/204281151-c7dde724-6b4a-428c-9b9d-32e146d7821a.png)

## Subnetting

![image](https://user-images.githubusercontent.com/72655301/204094402-6b0abdde-2edb-45fc-a8d7-094de1a56b7a.png)

## Subnet IP

![image](https://user-images.githubusercontent.com/72655301/204095147-2a5da675-4b98-4699-b86a-d766bd0458b4.png)

## Pembagian IP per Subnet

![image](https://user-images.githubusercontent.com/72655301/204095170-b623926c-17d3-4725-b4b0-22d96f094c65.png)

## Static Routes

### The Dauntless
- 0.0.0.0/0 via 192.170.0.6
### The Minister
- 0.0.0.0/0 via 192.170.0.1
- 192.170.2.0/24 via 192.170.0.5
### The Order
- 0.0.0.0/0 via 192.170.0.9
- 192.170.4.0/22 via 192.170.0.2
- 192.170.2.0/24 via 192.170.0.2
- 192.170.0.4/30 via 192.170.0.2
### The Resonance
- 192.170.4.0/22 via 192.170.0.10
- 192.170.2.0/24 via 192.170.0.10
- 192.170.0.64/26 via 192.170.0.10
- 192.170.8.0/23 via 192.170.0.17
- 192.170.0.128/25 via 192.170.0.22
- 192.170.0.28/30 via 192.170.0.22
- 192.170.3.0/24 via 192.170.0.22
- 192.170.12.0/23 via 192.170.0.22
- 192.170.1.0/25 via 192.170.0.22
- 192.170.1.128/25 via 192.170.0.22
- 192.170.0.4/30 via 192.170.0.10
- 192.170.0.0/30 via 192.170.0.10
- 192.170.0.48/30 via 192.170.0.22
- 192.170.0.24/30 via 192.170.0.22
### The Magical
- 0.0.0.0/0 via 192.170.0.18
### The Instrument
- 0.0.0.0/0 via 192.170.0.21
- 192.170.12.0/23 via 192.170.0.25
- 192.170.0.28/30 via 192.170.0.25
- 192.170.1.128/25 via 192.170.0.49
- 192.170.1.0/25 via 192.170.0.49
- 192.170.3.0/24 via 192.170.0.25
### The Profound
- 0.0.0.0/0 via 192.170.0.50
### The Firefist
- 0.0.0.0/0 via 192.170.0.26
- 192.170.0.28/30 via 192.170.3.2
### The Queen
- 0.0.0.0/0 via 192.170.3.1

# CIDR / GNS3
Untuk metode CIDR hanya Subnetting subnet besar dengan subnet kecil karena masih terkendala dengan sistem penurunan tree dari metode ini. Untuk penggabungan subnetnya dapat dilihat dibawah ini.

![image](https://user-images.githubusercontent.com/72655301/204280829-7bb6dc92-fa35-41c6-885e-078cb08e76f1.png)

