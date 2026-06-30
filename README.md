# Simulasi Infrastruktur Jaringan Perusahaan Menggunakan Cisco Packet Tracer

## Deskripsi

Project ini merupakan simulasi jaringan perusahaan yang terdiri dari Head Office dan Branch Office menggunakan Cisco Packet Tracer.

Fitur yang diterapkan:

- DHCP Server
- Routing antar jaringan
- WAN dan LAN
- Pengujian konektivitas menggunakan Ping

---

## Topologi Jaringan

<img width="1030" height="452" alt="image" src="https://github.com/user-attachments/assets/0a1cb2c0-f67c-46e2-a128-1f26e8f7f25d" />


---

## Pembagian Divisi

### Head Office

- HR (2 PC)
- Finance (4 PC)
- IT (2 PC)

### Branch Office

- Sales (3 PC)
- Marketing (2 PC)
- Support (3 PC)

---

## Skema IP

| Lokasi | Network | Gateway |
|--------|---------|----------|
| Head Office | 192.168.1.0/24 | 192.168.1.20 |
| Branch Office | 192.168.2.0/24 | 192.168.2.20 |

---

## Hasil Pengujian

<img width="299" height="132" alt="image" src="https://github.com/user-attachments/assets/7b43779f-02c5-43b2-bd0b-9889341f6588" />
Pengujian berhasil. HR-PC02 di Head Office dapat berkomunikasi dengan ADMIN-PC02 di Branch Office melalui Router-HO

---

## Konfigurasi DHCP

<img width="621" height="454" alt="image" src="https://github.com/user-attachments/assets/726dd00a-5cb2-42ec-937c-d0737b5893c3" />
DHCP Server HO

<img width="608" height="443" alt="image" src="https://github.com/user-attachments/assets/870335a8-c137-4846-8e08-6915ed2a495b" />
Application Server (Branch)

---

## Konfigurasi Router

<img width="607" height="440" alt="image" src="https://github.com/user-attachments/assets/51ca1513-f919-42d8-ab46-281f7b8220d9" />


---

## Teknologi

- Cisco Packet Tracer
- Cisco Router 1841
- Cisco Switch 2960
- DHCP
- IPv4
