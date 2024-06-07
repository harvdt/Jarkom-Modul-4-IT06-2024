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
![Screenshot 2024-06-08 013520](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/b2e1342f-d475-43ee-b194-79e10e4a2590)
![Screenshot 2024-06-08 013514](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/1d03044e-e3d3-405b-b3f3-992a282bf0ae)

- Sulawesi
![Screenshot 2024-06-08 013813](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/af197de9-3624-4765-b213-ad8388d2bb0b)

- Maluku Utara
![Screenshot 2024-06-08 013853](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/ebd8b2b4-b595-44b3-8cb3-622f3580d281)

- Makasar
![Screenshot 2024-06-08 013937](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/6bea41a5-0482-44c3-9f6f-103121d1ee97)

- Belawa
![Screenshot 2024-06-08 014007](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/0647bbca-fc89-4069-88d0-e7ce2c60b21a)

- Kalimantan
![Screenshot 2024-06-08 014425](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/b03afb18-d996-4304-9ce7-e99ea5fbc822)

- Kalimantan Utara
![Screenshot 2024-06-08 014509](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/6fc12b11-2f9a-4fae-9971-49dd935fcf9b)

- Kalimantan Timur
![Screenshot 2024-06-08 014554](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/68658a8d-130e-44ff-a9bf-f1ddfe1c579a)

- Kalimantan Selatan
![Screenshot 2024-06-08 014718](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/3b2756b6-efde-48a8-9bbf-40b3c7176427)

- Sumatera
![Screenshot 2024-06-08 013715](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/3f34e2a7-08bd-4283-882a-41bd0de05b92)

- Sumatera Utara
![Screenshot 2024-06-08 014755](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/702e9104-db62-4747-98ed-f44e4ccdf300)

- Aceh
![Screenshot 2024-06-08 014839](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/d760483b-a669-4fda-a066-d070d2c4d1fe)

- Lampung
![Screenshot 2024-06-08 014911](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/437717e3-af64-49cb-9204-07bc8adab3df)

### Testing
![Screenshot 2024-06-08 020730](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/122193a9-d445-4f56-b0d7-f1b17fa5c686)
![Screenshot 2024-06-08 020903](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/1183e3b8-0bed-4486-91ef-2d7d9249d850)
![Screenshot 2024-06-08 020946](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/23c2cd79-cb5d-4fca-af4f-d6ff8d33c9e4)
![Screenshot 2024-06-08 021046](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/1c3a8d97-7e67-462c-8dfb-0c8550a6b69f)
![Screenshot 2024-06-08 021207](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/115382618/173fcf10-ca70-40fa-b4d3-9f8d0d3bcc5f)