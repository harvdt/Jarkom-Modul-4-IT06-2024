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


## GNS (CIDR)

### Topologi
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/5113c8ef-2810-4cab-ab06-da9e0f31cea2)

### Penggabungan CIDR
![1](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/0f984f8e-7734-40d2-b173-3aa0db0c0a1f)
![2](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/1fbfdfe2-0540-4140-a7a4-55470aa2a042)
![3](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/d589c214-dcf1-46b2-92f2-f4d0c0ec3538)
![4](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/5583916a-1737-45ba-a0a6-ca87d4181f79)
![5](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/3d966b9a-286d-40d4-b823-81cbc98730e8)
![6](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/c69d7151-9561-44a0-9a98-b9635533d1fb)
![7](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/1e0ca6a8-753e-4d7c-8e8c-82ef24561e2d)
![8](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/94cc7662-9c1e-4eb5-94f1-335585aeed69)
![9](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/42f509c1-d2ca-4b5d-98de-44a79e427c84)
![10](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/c2f3e9dc-3708-4d84-88f4-5cc776b849b6)
![11](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/a47031d2-d0f5-4943-8391-07cd376f1808)

Kemudian berikut ini merupakan tabel subnetting berdasarkan penggabungan yang sudah dilakukan
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/13d377e2-d5d5-426a-bf8d-918175b1b54e)
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/09dce68b-23cd-4425-9cde-5a65a6c26d3e)
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/41fdeab2-4756-420d-91cf-d00b1e4fa8ba)
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/6ab00fe0-f948-484a-8646-7022ac12451d)


### Tree
Berdasarkan penggabungan yang sudah dilakukan berikut adalah tree subnetting dari CIDR
![finaltreecidrs](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/768e0e65-5eeb-40c1-87b9-aa4efe15a1e1)

### Hasil Pembagian Subnet
Berdasarkan Tree, didpatkan pembagian subnet sebagai berikut
![image](https://github.com/harvdt/Jarkom-Modul-4-IT06-2024/assets/143340695/fbdc5cf4-dce7-4233-a7a8-9c9d5f26be23)

### Konfigurasi pada GNS3
##### jawa
```
auto eth0
iface eth0 inet dhcp

#####A1
auto eth1
iface eth1 inet static
  address 192.236.16.129
  netmask 255.255.255.252

#####A7
auto eth2
iface eth2 inet static
  address 192.236.48.1
  netmask 255.255.255.252

#####A15
auto eth3
iface eth3 inet static
  address 192.236.8.1
  netmask 255.255.255.252
```

##### sulawesi
```
#####A1 jawa-sulawesi
auto eth0
iface eth0 inet static
	address 192.236.16.130
	netmask 255.255.255.252

#####A2 Sulawesi-SW-Gorontalo-PC-Gorontalo-SW-Gorontalo-PC-Marisa
auto eth1
iface eth1 inet static
	address 192.236.17.1
	netmask 255.255.255.128

#####A4 Sulawesi-SW-Sulsel-Makasar-SW-Sulsel-Belawa
auto eth2
iface eth2 inet static
	address 192.236.16.1
	netmask 255.255.255.248
```

##### PC-Gorontalo
```
auto eth0
iface eth0 inet static
	address 192.236.17.2
	netmask 255.255.255.128
	gateway 192.236.17.1
```

##### PC-Marisa
```
auto eth0
iface eth0 inet static
	address 192.236.17.3
	netmask 255.255.255.128
	gateway 192.236.17.1
```

##### maluku utara
```
#####A3 Maluku-Utara > SW-Maluku > Tobelo > SW-Maluku >  Morotai > SW-Maluku > Ternate
auto eth0
iface eth0 inet static
	address 192.236.18.1
	netmask 255.255.248.0
```

##### tobelo
```
auto eth0
iface eth0 inet static
	address 192.236.18.2
	netmask 255.255.248.0
	gateway 192.236.18.1
```

##### morotai
```
auto eth0
iface eth0 inet static
	address 192.236.18.3
	netmask 255.255.248.0
	gateway 192.236.18.1
```

##### ternate
```
auto eth0
iface eth0 inet static
	address 192.236.18.4
	netmask 255.255.248.0
	gateway 192.236.18.1
```

##### makasar
```
#####A5 Makasar > SW-Limbung > Galesong > SW-Limbung > Topejawa-Takalar
auto eth0
iface eth0 inet static
	address 192.236.16.9
	netmask 255.255.255.248
	gateway 192.236.16.1
```

##### galesong
```
auto eth0
iface eth0 inet static
	address 192.236.16.10
	netmask 255.255.255.248
	gateway 192.236.16.9
```

##### topejawa
```
auto eth0
iface eth0 inet static
	address 192.236.16.11
	netmask 255.255.255.248
	gateway 192.236.16.9
```

##### belawa
```
#####A6 Belawa  > SW-Tempe > Madini > SW-Tempe > Baru
auto eth0
iface eth0 inet static
	address 192.236.16.17
	netmask 255.255.255.192
	gateway 192.236.16.1
```

##### madini
```
auto eth0
iface eth0 inet static
	address 192.236.16.18
	netmask 255.255.255.192
	gateway 192.236.16.17
```

##### baru
```
auto eth0
iface eth0 inet static
	address 192.236.16.19
	netmask 255.255.255.192
	gateway 192.236.16.17
```


##### kalimantan
```
#####A7 Jawa-Kalimantan
auto eth0
iface eth0 inet static
	address 192.236.48.2
	netmask 255.255.255.252

#####A8 Kalimantan-Kalimantan-Utara
auto eth1
iface eth1 inet static
	address 192.236.32.129
	netmask 255.255.255.252
```

##### kalimantan-utara
```
#####A8 Kalimantan-Kalimantan-Utara
auto eth0
iface eth0 inet static
	address 192.236.32.130
	netmask 255.255.255.252

#####A9 Kalimantan-Utara > SW-Tanjung-Selor > Selimau
auto eth1
iface eth1 inet static
	address 192.236.33.1
	netmask 255.255.255.0

#####A10 Kalimantan-Utara > Kalimantan-Timur
auto eth2
iface eth2 inet static
	address 192.236.32.65
	netmask 255.255.255.252
```

##### selimau
```
auto eth0
iface eth0 inet static
	address 192.236.33.2
	netmask 255.255.255.0
	gateway 192.236.33.1
```

##### Kalimantan-Timur
```
#####A10 Kalimantan-Timur > Kalimantan-Utara 
auto eth0
iface eth0 inet static
	address 192.236.32.66
	netmask 255.255.255.252

#####A11 Kalimantan-Timur > SW-Balikpapan > Bangkirari > SW-Balikpapan > Lamaru
auto eth1
iface eth1 inet static
	address 192.236.34.1
	netmask 255.255.254.0

#####A12 Kalimantan-Timur > Kalimantan-Selatan
auto eth2
iface eth2 inet static
	address 192.236.32.1
	netmask 255.255.255.252
```

##### Bangkirari
```
auto eth0
iface eth0 inet static
	address 192.236.34.2
	netmask 255.255.254.0
	gateway 192.236.34.1
```

##### Lemaru
```
auto eth0
iface eth0 inet static
	address 192.236.34.3
	netmask 255.255.254.0
	gateway 192.236.34.1
```

##### Kalimantan-Selatan
```
#####A12 Kalimantan-Selatan > Kalimantan-Timur
auto eth0
iface eth0 inet static
	address 192.236.32.2
	netmask 255.255.255.252

#####A13 Kalimantan-Selatan > SW-Boenati > Angsana
auto eth1
iface eth1 inet static
	address 192.236.32.5
	netmask 255.255.255.224

#####A14 Kalimantan-Selatan > SW-Banjarmasin > Bajuin > SW-Banjarmasin > Taksiun > SW-Banjarmasin > Batakan
auto eth2
iface eth2 inet static
	address 192.236.36.1
	netmask 255.255.248.0
```

##### Angsana
```
auto eth0
iface eth0 inet static
	address 192.236.32.6
	netmask 255.255.255.224
	gateway 192.236.32.5
```

##### Bajuin
```
auto eth0
iface eth0 inet static
	address 192.236.36.2
	netmask 255.255.248.0
	gateway 192.236.36.1
```

##### taksiun
```
auto eth0
iface eth0 inet static
	address 192.236.36.3
	netmask 255.255.248.0
	gateway 192.236.36.1
```

##### batakan
```
auto eth0
iface eth0 inet static
	address 192.236.36.4
	netmask 255.255.248.0
	gateway 192.236.36.1
```

##### sumatera
```
#####A15 Jawa-sumatera
auto eth0
iface eth0 inet static
	address 192.236.8.2
	netmask 255.255.255.252

#####A16 Sumatera-SW-Toba-Samosir-SW-Toba-Sibandang
auto eth1
iface eth1 inet static
	address 192.236.2.1
	netmask 255.255.255.224

#####A20 Sumatera > Lampung 
auto eth2
iface eth2 inet static
	address 192.236.4.1
	netmask 255.255.255.252
```

##### samosir
```
auto eth0
iface eth0 inet static
	address 192.236.2.2
	netmask 255.255.255.224
	gateway 192.236.2.1
```

##### sibandang
```
auto eth0
iface eth0 inet static
	address 192.236.2.3
	netmask 255.255.255.224
	gateway 192.236.2.1
```

##### lampung
```
#####A20 Sumatera > Lampung 
auto eth0
iface eth0 inet static
	address 192.236.4.2
	netmask 255.255.255.252

#####A21 Lampung > SW-Bandar-Lampung > Sebuku > SW-Bandar-Lampung > Sebesi
auto eth1
iface eth1 inet static
	address 192.236.4.5
	netmask 255.255.255.0
```

##### sebuku
```
auto eth0
iface eth0 inet static
	address 192.236.4.6
	netmask 255.255.255.0
	gateway 192.236.4.5
```

##### sebesi
```
auto eth0
iface eth0 inet static
	address 192.236.4.7
	netmask 255.255.255.0
	gateway 192.236.4.5
```

##### Sumatera utara
```
#####A17 Sumatera-Utara > Aceh
auto eth0
iface eth0 inet static
	address 192.236.0.1
	netmask 255.255.255.252
```

##### Aceh
```
#####A17 Sumatera-Utara > Aceh
auto eth0
iface eth0 inet static
	address 192.236.0.2
	netmask 255.255.255.252
    gateway 192.236.0.1

#####A18 Aceh > SW-Blangrakal > Berawang-Tampu > SW-Blangrakal > Enang-Enang > SW-Blangrakal > Starland
auto eth1
iface eth1 inet static
	address 192.236.0.5
	netmask 255.255.255.128

#####A19 Aceh > SW-Banda-Aceh > Sabang > SW-Banda-Aceh > Lambaro
auto eth2
iface eth2 inet static
	address 192.236.1.1
	netmask 255.255.255.224
```

##### Berawang-Tampu
```
auto eth0
iface eth0 inet static
	address 192.236.0.6
	netmask 255.255.255.128
	gateway 192.236.0.5
```

##### Enang-enang
```
auto eth0
iface eth0 inet static
	address 192.236.0.7
	netmask 255.255.255.128
	gateway 192.236.0.5
```

##### Starland
```
auto eth0
iface eth0 inet static
	address 192.236.0.8
	netmask 255.255.255.128
	gateway 192.236.0.5
```

##### Sabang
```
auto eth0
iface eth0 inet static
	address 192.236.1.2
	netmask 255.255.255.224
	gateway 192.236.1.1
```

##### lembaro
```
auto eth0
iface eth0 inet static
	address 192.236.1.3
	netmask 255.255.255.224
	gateway 192.236.1.1
```

### Routing
##### aceh
```
#####aceh ke sumaterautara
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.0.1
```

##### lampung
```
#####lampung ke sumatera
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.4.5
```

##### kalimantanselatan
```
#####kalimantanselatan-timur
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.32.5
```

##### belawa
```
#####belawa kesulawesi
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.16.17
```

##### makasar
```
#####makasar kesulawesi
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.16.9
```

##### MALUKU UTARA
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.17.1
```

##### SUMATERA UTARA
```
route add -net 192.236.0.5 netmask 255.255.255.128 gw 192.236.0.2 #####SW-BLANGKARAI
route add -net 192.236.1.1 netmask 255.255.255.224 gw 192.236.0.2 #####SW-BANDA-ACEH
```


##### sumatera
```
#####kejawa
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.16.129

#####kesumatutr
route add -net 1992.236.0.0 netmask 255.255.255.252 gw 192.236.2.1
route add -net 192.236.0.4 netmask 255.255.255.128 gw 192.236.2.1
route add -net 192.236.1.0 netmask 255.255.255.224 gw 192.236.2.1

#####kelampung
route add -net 192.236.4.4 netmask 255.255.255.0 gw 192.236.4.2
```

##### kalimantam timur
```
route add -net 192.236.32.4 netmask 255.255.255.224 gw 192.236.32.66
route add -net 192.236.36.0 netmask 255.255.248.0 gw 192.236.32.66
```

##### kalimantan utara
```
route add -net 192.236.34.0 netmask 255.255.254.0 gw 192.236.33.1
route add -net 192.236.32.0 netmask 255.255.255.252 gw 192.236.33.1
route add -net 192.236.32.4 netmask 255.255.255.224 gw 192.236.33.1
route add -net 192.236.36.0 netmask 255.255.248.0 gw 192.236.33.1
```

##### kalimantan
```
route add -net 192.236.32.64 netmask 255.255.255.252 gw 192.236.32.129
route add -net 192.236.34.0 netmask 255.255.254.0 gw 192.236.32.129
route add -net 192.236.32.0 netmask 255.255.255.252 gw 192.236.32.129
route add -net 192.236.32.4 netmask 255.255.255.224 gw 192.236.32.129
route add -net 192.236.36.0 netmask 255.255.248.0 gw 192.236.32.129
```

##### sulawesi
```
#####KE MALUKU-UTARA
route add -net 192.236.18.0 netmask 255.255.248.0 gw 192.236.17.1

#####KE MAKASAR
route add -net 192.236.16.8 netmask 255.255.255.248 gw 192.236.16.9

#####KE BELAWA
route add -net 192.236.16.16 netmask 255.255.255.192 gw 192.236.16.17
```

##### jawa 
```
#####jawa ke sulawesi
route add -net 192.236.17.0 netmask 255.255.255.128 gw 192.236.16.130
route add -net 192.236.18.0 netmask 255.255.248.0 gw 192.236.16.130
route add -net 192.236.16.0 netmask 255.255.255.248 gw 192.236.16.130
route add -net 192.236.16.8 netmask 255.255.255.248 gw 192.236.16.130
route add -net 192.236.16.16 netmask 255.255.255.192 gw 192.236.16.130

#####jawa ke kalimantan
route add -net 192.236.32.128 netmask 255.255.255.252 gw 192.236.48.2
route add -net 192.236.33.0 netmask 255.255.255.0 gw 192.236.48.2
route add -net 192.236.32.64 netmask 255.255.255.252 gw 192.236.48.2
route add -net 192.236.34.0 netmask 255.255.254.0 gw 192.236.48.2
route add -net 192.236.32.0 netmask 255.255.255.252 gw 192.236.48.2
route add -net 192.236.32.4 netmask 255.255.255.224 gw 192.236.48.2
route add -net 192.236.36.0 netmask 255.255.248.0 gw 192.236.48.2

#####jawa ke sumatera
route add -net 192.236.2.0 netmask 255.255.255.224 gw 192.236.8.2
route add -net 192.236.0.0 netmask 255.255.255.252 gw 192.236.8.2
route add -net 192.236.0.4 netmask 255.255.255.128 gw 192.236.8.2
route add -net 192.236.1.0 netmask 255.255.255.224 gw 192.236.8.2
route add -net 192.236.4.0 netmask 255.255.255.252 gw 192.236.8.2
route add -net 192.236.4.4 netmask 255.255.255.0 gw 192.236.8.2
```

##### aceh ke sumatera utara
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.236.0.1
```

##### lampung ke sumatera
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.245.20.185
```
