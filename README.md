# Laporan-Resmi-Jarkom-Modul-4-IT06-2024

| Nama                      | NRP                       |
|---------------------------|---------------------------|
| Muhammad Harvian Dito S.  | 5027221039                |
| Sylvia Febrianti          | 5027221019                |

## VLSM

### Topologi
![Screenshot 2024-06-07 135515](https://github.com/sylxer/Jarkom-Modul-1-IT06-2024/assets/115382618/dcf06bc7-f910-42c4-9872-e50aed3e33a8)

### Subnet
![Screenshot 2024-06-07 144357](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/90572feb-221e-40ae-b721-18d15ada59b7)

### Tree
![IT06_VLSM Tree](https://github.com/sylxer/Jarkom-Modul-1-IT06-2024/assets/115382618/1478cc8f-c982-46e8-932b-7103f5d9f0bc)

### Pembagian IP
![Screenshot 2024-06-07 144422](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/16872796-e109-426d-9b47-a15ea3f344ad)

### Konfigurasi

- Jawa (Router)
```
Fa0/1: 192.236.21.177 (A1)
Netmask: 255.255.255.252

Fa1/0: 192.236.21.181 (A7)
Netmask: 255.255.255.252

Fa1/1: 192.236.21.197 (A15)
Netmask: 255.255.255.252
```
- Sulawesi (Router)
```
Fa0/0: 192.236.21.178 (A1)
Netmask: 255.255.255.252

Fa0/1: 192.236.20.129 (A2)
Netmask: 255.255.255.128

Fa1/0: 192.236.21.161 (A4)
Netmask: 255.255.255.248
```
- Maluku-Utara (Router)
```
Fa0/0: 192.236.20.132 (A2)
Netmask: 255.255.255.128

Fa0/1: 192.236.8.1 (A3)
Netmask: 255.255.248.0
```
- Makasar (Router)
```
Fa0/0: 192.236.21.162 (A4)
Netmask: 255.255.255.248

Fa0/1: 192.236.21.169 (A5)
Netmask: 255.255.255.248
```
- Belawa (Router)
```
Fa0/0: 192.236.21.163 (A4)
Netmask: 255.255.255.248

Fa0/1: 192.236.21.1 (A6)
Netmask: 255.255.255.192
```
- Kalimantan (Router)
```
Fa0/0: 192.236.21.182 (A7)
Netmask: 255.255.255.252

Fa0/1: 192.236.21.185 (A8)
Netmask: 255.255.255.252
```
- Kalimantan-Utara (Router)
```
Fa0/0: 192.236.21.186 (A8)
Netmask: 255.255.255.252

Fa0/1: 192.236.18.1 (A9)
Netmask: 255.255.255.0

Fa1/0: 192.236.21.189 (A10)
Netmask: 255.255.255.252
```
- Kalimantan-Timur (Router)
```
Fa0/0: 192.236.21.190 (A10)
Netmask: 255.255.255.252

Fa0/1: 192.236.16.1 (A11)
Netmask: 255.255.254.0

Fa1/0: 192.236.21.193 (A12)
Netmask: 255.255.255.252
```
- Kalimantan-Selatan (Router)
```
Fa0/0: 192.236.21.194 (A12)
Netmask: 255.255.255.252

Fa0/1: 192.236.21.97 (A13)
Netmask: 255.255.255.224

Fa1/0: 192.236.0.1 (A14)
Netmask: 255.255.248.0
```
- Sumatera (Router)
```
Fa0/0: 192.236.21.198 (A15)
Netmask: 255.255.255.252

Fa0/1: 192.236.21.65 (A16)
Netmask: 255.255.255.224

Fa1/0: 192.236.21.205 (A20)
Netmask: 255.255.255.252
```
- Sumatera-Utara (Router)
```
Fa0/0: 192.236.21.68 (A16)
Netmask: 255.255.255.224

Fa0/1: 192.236.21.201 (A17)
Netmask: 255.255.255.252
```
- Aceh (Router)
```
Fa0/0: 192.236.21.202 (A17)
Netmask: 255.255.255.252

Fa0/1: 192.236.20.1 (A18)
Netmask: 255.255.255.128

Fa1/0: 192.236.21.129 (A19)
Netmask: 255.255.255.224
```
- Lampung (Router)
```
Fa0/0: 192.236.21.206 (A20)
Netmask: 255.255.255.252

Fa0/1: 192.236.19.1 (A21)
Netmask: 255.255.255.0
```
- PC-Gorontalo (PC)
```
(A2) 
IPv4: 192.236.20.130
Netmask: 255.255.255.128
Gateway: 192.236.20.129
```
- PC-Marisa (PC)
```
(A2) 
IPv4: 192.236.20.131
Netmask: 255.255.255.128
Gateway: 192.236.20.129
```
- Tobelo (PC)
```
(A3) 
IPv4: 192.236.8.2
Netmask: 255.255.248.0
Gateway: 192.236.8.1
```
- Morotai (Server)
```
(A3)
IPv4: 192.236.8.3
Netmask: 255.255.248.0
Gateway: 192.236.8.1
```
- Ternate (PC)
```
(A3)
IPv4: 192.236.8.4
Netmask: 255.255.248.0
Gateway: 192.236.8.1
```
- Galesong (Server)
```
(A5)
IPv4: 192.236.21.170
Netmask: 255.255.255.248
Gateway: 192.236.21.169
```
- Topejawa-Takalar (Server)
```
(A5)
IPv4: 192.236.21.171
Netmask: 255.255.255.248
Gateway: 192.236.21.169
```
- Madini (PC)
```
(A6)
IPv4: 192.236.21.2
Netmask: 255.255.255.192
Gateway: 192.236.21.1
```
- Baru (PC)
```
(A6)
IPv4: 192.236.21.3
Netmask: 255.255.255.192
Gateway: 192.236.21.1
```
- Selimau (PC)
```
(A9)
IPv4: 192.236.18.2
Netmask: 255.255.255.0
Gateway: 192.236.18.3
```
- Bangkirai (Server)
```
(A11)
IPv4: 192.236.16.2
Netmask: 255.255.254.0
Gateway: 192.236.16.1
```
- Lamaru (PC)
```
(A11)
IPv4: 192.236.16.3
Netmask: 255.255.254.0
Gateway: 192.236.16.1
```
- Angsana (PC)
```
(A13)
IPv4: 192.236.21.98
Netmask: 255.255.255.224
Gateway: 192.236.21.97
```
- Bajuin (PC)
```
(A14)
IPv4: 192.236.0.2
Netmask: 255.255.248.0
Gateway: 192.236.0.1
```
- Taksiung (PC)
```
(A14)
IPv4: 192.236.0.3
Netmask: 255.255.248.0
Gateway: 192.236.0.1
```
- Batakan (PC)
```
(A14) 
IPv4: 192.236.0.4
Netmask: 255.255.248.0
Gateway: 192.236.0.1
```
- Samosir (PC)
```
(A16) 
IPv4: 192.236.21.66
Netmask: 255.255.255.224
Gateway: 192.236.21.65
```
- Sibandang (PC)
```
(A16)
IPv4: 192.236.21.67
Netmask: 255.255.255.224
Gateway: 192.236.21.66
```
- Berawang-Tampu (PC)
```
(A18)
IPv4: 192.236.20.2
Netmask: 255.255.255.128
Gateway: 192.236.20.1
```
- Enang-Enang (PC)
```
(A18)
IPv4: 192.236.20.3
Netmask: 255.255.255.128
Gateway: 192.236.20.1
```
- Starland (PC)
```
(A18)
IPv4: 192.236.20.4
Netmask: 255.255.255.128
Gateway: 192.236.20.1
```
- Sabang (PC)
```
(A19)
IPv4: 192.236.21.130
Netmask: 255.255.255.224
Gateway: 192.236.21.129
```
- Lambaro (PC)
```
(A19)
IPv4: 192.236.21.131
Netmask: 255.255.255.224
Gateway: 192.236.21.129
```
- Sebuku (PC)
```
(A21)
IPv4: 192.236.19.2
Netmask: 255.255.255.0
Gateway: 192.236.19.1
```
- Sebesi (Server)
```
(A21)
IPv4: 192.236.19.3
Netmask: 255.255.255.0
Gateway: 192.236.19.1
```

### Routing
- Jawa
![Screenshot 2024-06-06 200324](https://github.com/sylxer/Jarkom-Modul-1-IT06-2024/assets/115382618/001c15d0-8c49-4dae-9a97-ece884c5d4dd)

- Sulawesi
![Screenshot 2024-06-06 200356](https://github.com/sylxer/Jarkom-Modul-1-IT06-2024/assets/115382618/594a463f-ebdd-429c-9b34-1b8004ad5bc2)

- Maluku Utara
![Screenshot 2024-06-06 200456](https://github.com/sylxer/Jarkom-Modul-1-IT06-2024/assets/115382618/6de2de68-5913-4117-bfdf-61c91979ec61)

- Makasar
![Screenshot 2024-06-06 201157](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/3d69e6e1-14d4-44ec-bee3-d183cdc1bbf3)

- Belawa
![Screenshot 2024-06-06 201214](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/f6d21eab-419b-4cde-a289-759a97810f98)

- Kalimantan
![Screenshot 2024-06-06 200958](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/cbe078e7-0e2d-4355-ad31-4a7ec2f55810)

- Kalimantan Utara
![Screenshot 2024-06-06 201038](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/a021075d-4111-4f58-8991-553bb2ed0bd1)

- Kalimantan Timur
![Screenshot 2024-06-06 201100](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/8ae7c48b-13bc-463b-a0ab-abe021b7590e)

- Kalimantan Selatan
![Screenshot 2024-06-06 201127](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/11c072d7-829f-4f86-8041-5f41694ee70d)

- Sumatera
![Screenshot 2024-06-06 201330](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/7d18f637-cce4-4548-b1c6-a8a3aef102d0)

- Sumatera Utara
![Screenshot 2024-06-06 201356](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/f1c2a1a0-1fd5-494e-be58-5781b6b69e4b)

- Aceh
![Screenshot 2024-06-06 201420](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/6864ddf4-9706-4be8-b260-0db8a88458ca)

- Lampung
![Screenshot 2024-06-06 201440](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/41d6cd0c-07f0-4ca4-b91c-95d8c9fc3f61)

### Testing
