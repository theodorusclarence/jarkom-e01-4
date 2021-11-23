# jarkom-e01-4

## VLSM

### Pembagian Subnet

![image](https://user-images.githubusercontent.com/55318172/143030727-cda6d42a-9925-4d7e-b819-5525f7c7bb8e.png)

### Pohon IP

![image](https://user-images.githubusercontent.com/55318172/143030798-3d3986c7-0c44-43ff-90b6-57713392ed79.png)

### Subnet + IP

![image](https://user-images.githubusercontent.com/55318172/143030843-8acda53c-1d70-41b2-8c21-3597a420d949.png)


### Pembagian IP per node

| Subnet | Node | IP | Subnet Mask | Length |
| --- | --- | --- | --- | --- |
| A1 | Pucci | 192.200.27.1 | 255.255.255.128 | /25 |
| A1 | Jipangu | 192.200.27.2 | 255.255.255.128 |  |
| A2 | Pucci | 192.200.0.1 | 255.255.248.0 | /21 |
| A2 | Courtyard | 129.200.0.2 | 255.255.248.0 |  |
| A2 | Calmbelt | 129.200.0.3 | 255.255.248.0 |  |
| A3 | Pucci | 192.200.27.145 | 255.255.255.252 | /30 |
| A3 | Water7 | 192.200.27.146 | 255.255.255.252 |  |
| A4 | Water7 | 192.200.8.1 | 255.255.252.0 | /22 |
| A4 | Cipher | 192.200.8.2 | 255.255.252.0 |  |
| A5 | Foosha | 192.200.12.1 | 255.255.252.0 | /22 |
| A5 | Blueno | 192.200.12.2 | 255.255.252.0 |  |
| A6 | Water7 | 192.200.27.149 | 255.255.255.252 | /30 |
| A6 | Foosha | 192.200.27.150 | 255.255.255.252 |  |
| A7 | Foosha | 192.200.27.153 | 255.255.255.252 | /30 |
| A7 | Guanhao | 192.200.27.154 | 255.255.255.252 |  |
| A8 | Guanhao | 192.200.16.1 | 255.255.252.0 | /22 |
| A8 | Jabra | 192.200.16.2 | 255.255.252.0 |  |
| A9 | Guanhao | 192.200.24.1 | 255.255.254.0 | /23 |
| A9 | Alabasta | 192.200.24.2 | 255.255.254.0 |  |
| A9 | Maingate | 192.200.24.3 | 255.255.254.0 |  |
| A10 | Alabasta | 192.200.27.129 | 255.255.255.240 | /28 |
| A10 | Jorge | 192.200.27.130 | 255.255.255.240 |  |
| A11 | Guanhao | 192.200.27.157 | 255.255.255.252 | /30 |
| A11 | Oimo | 192.200.27.158 | 255.255.255.252 |  |
| A12 | Oimo | 192.200.26.1 | 255.255.255.0 | /24 |
| A12 | Seastone | 192.200.26.2 | 255.255.255.0 |  |
| A12 | Enieslobby | 192.200.26.3 | 255.255.255.0 |  |
| A13 | Seastone | 192.200.20.1 | 255.255.252.0 | /22 |
| A13 | Elena | 192.200.20.2 | 255.255.252.0 |  |
| A14 | Foosha | 192.200.27.161 | 255.255.255.252 | /30 |
| A14 | Doriki | 192.200.27.162 | 255.255.255.252 |  |
| A15 | Oimo | 192.200.27.165 | 255.255.255.252 | /30 |
| A15 | Fukurou | 192.200.27.166 | 255.255.255.252 |  |

### VLSM Routing Check 

https://user-images.githubusercontent.com/55318172/143031251-1e2bdc97-7a13-49dc-8a0d-4f90056357ab.mp4

## CIDR

![image](https://user-images.githubusercontent.com/55318172/143031393-5d270e7e-9c79-477c-bcc0-4225c9198df3.png)

![image](https://user-images.githubusercontent.com/55318172/143031408-3d7fe57e-8559-4034-ad8d-9de585c52619.png)

![image](https://user-images.githubusercontent.com/55318172/143031429-62803a1a-cb51-4b1e-b541-b12658d80e4e.png)

![image](https://user-images.githubusercontent.com/55318172/143031448-6e47724a-4b41-4418-a486-ed84a17fc963.png)

![image](https://user-images.githubusercontent.com/55318172/143031467-09182464-4e0d-4dfb-9114-798ce77990b1.png)

![image](https://user-images.githubusercontent.com/55318172/143031507-354f3610-5eb8-45d2-951c-46fce3168096.png)

![image](https://user-images.githubusercontent.com/55318172/143031532-8c0800ac-703d-4917-ab26-1969a7bb5f7e.png)

![image](https://user-images.githubusercontent.com/55318172/143031579-3d5f6775-46ff-4a14-b423-901617d70d39.png)

### Pohon IP

![image](https://user-images.githubusercontent.com/55318172/143033944-8ba7468d-6cce-4ce0-9b47-609e05b19d47.png)


### Tabel

| Subnet | Node | IP | Subnet Mask | Length |
| --- | --- | --- | --- | --- |
| A1 | jipangu pucci | 192.201.8.0 | 255.255.255.128 | 25 |
| A2 | court, calm, puc | 192.201.0.0 | 255.255.248.0 | 21 |
| A3 | pucci water | 192.201.16.0 | 255.255.255.252 | 30 |
| A4 | cipher water | 192.201.32.0 | 255.255.252.0 | 22 |
| A5 | blueno foosh | 192.201.128.0 | 255.255.252.0 | 22 |
| A6 | foosh wat | 192.201.64.0 | 255.255.255.252 | 30 |
| A7 | foosh guan | 192.200.64.0 | 255.255.255.252 | 30 |
| A8 | guan jabra | 192.200.36.0 | 255.255.252.0 | 22 |
| A9 | guanhao maingate alabas | 192.200.0.0 | 255.255.254.0 | 23 |
| A10 | alabas jorge | 192.200.34.0 | 255.255.255.240 | 28 |
| A11 | guan oimo | 192.200.16.0 | 255.255.255.252 | 30 |
| A12 | oimo enies seastone | 192.200.4.0 | 255.255.255.0 | 24 |
| A13 | seas elena | 192.200.0.0 | 255.255.252.0 | 22 |
| A14 | foosha doriki | 192.200.128.0 | 255.255.255.252 | 30 |
| A15 | fukurou oimo | 192.200.8.0 | 255.255.255.252 | 30 |
