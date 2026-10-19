| Name           | NRP        | Kelas     |
| ---            | ---        | ----------|
|  |  |  |

> [!IMPORTANT]
> Remember to use the IP prefix allocation provided earlier for this pre-lab assignment (pra-praktikan) and for future ones.
> Access it on [Linktree](https://linktr.ee/jarkom) 


> [!NOTE]
> Praktikum Modul 2 / Module 2 Practicum (Remedial): HTTP Server, DNS Server, dan Reverse Proxy.
>
> Original practicum file document: [here](https://docs.google.com/document/d/1fn0ws-wI6X9SqzrOTLM7Xz7O1uBz8M1k/edit?usp=sharing&ouid=109083087274352750540&rtpof=true&sd=true)

## Put your GNS3 Project file here (gdrive or github upload)!

`Put file URL here`

## Topology

> [!IMPORTANT]
> Create the topology **from scratch**; you may not reuse the topology from the pra-praktikum.
>
> **Put your topology image (PNG/JPEG) here, before continuing to the tasks below!**

`![Topology](put your topology image (PNG/JPEG) here)`

---

#### Soal 1

> Koneksikan seluruh topologi agar bisa mendapat internet dari NAT (konfigurasi router, gateway dan DHCP Server)

> Configure the entire network topology to enable internet access via NAT (configure the router, gateway, and DHCP server).

**Answer:**

```
put your answer here (and screenshot)
```

#### Soal 2

> Pasang DNS server internal dengan domain pilihan sendiri (misalnya sekolah.local) yang mengarah ke Kazdel, dan integrasikan dengan DHCP server agar seluruh PC lab (DHCP client) otomatis mengetahui alamat DNS ini.

> Set up an internal DNS server using a custom domain (e.g., sekolah.local) pointing to Kazdel, and integrate it with the DHCP server so that all lab PCs (DHCP clients) automatically recognize this DNS address.

**Answer:**

```
put your answer here (and screenshot, including /etc/resolv.conf on the clients)
```

#### Soal 3

> Jalankan tiga backend HTTP/aplikasi berbeda (nilai, absensi, kalender akademik) di tiga node berbeda (web1, web2 dan web3), menggunakan nginx.
> a. web1.html
> b. web2.html
> c. web3.html

[drive](https://drive.google.com/drive/folders/1c4rWJrtACG9G0XPTUFTabhSoq1JMveIf?usp=sharing) 

> Run three distinct HTTP backends/applications (grades, attendance, and academic calendar) on three separate nodes (web1, web2, and web3), using nginx.
> a. web1.html
> b. web2.html
> c. web3.html
> [drive](https://drive.google.com/drive/folders/1c4rWJrtACG9G0XPTUFTabhSoq1JMveIf?usp=sharing) 

**Answer:**

```
put your answer here (and screenshot)
```

#### Soal 4

> Pasang satu reverse proxy yang bisa diakses lewat nama domain (misalnya www.sekolah.local), meneruskan /nilai, /absensi, dan /kalender ke masing-masing backend.

> Set up a reverse proxy accessible via a domain name (e.g., www.sekolah.local) that forwards requests for /nilai, /absensi, and /kalender to their respective backends.

**Answer:**

```
put your answer here (and screenshot)
```

#### Soal 5

> Buktikan dari command line (curl) dan browser bahwa ketiga aplikasi dapat diakses lewat satu nama domain yang sama.

> Demonstrate using both the command line (curl) and a web browser that all three applications are accessible via the same domain name.

**Answer:**

```
put your answer here (and screenshot of curl and browser)
```

#### Soal 6

> Jelaskan pada asisten 2 pertanyaan berikut:
> a. Jelaskan bagaimana DNS, reverse proxy, dan backend saling bekerja sama sebagai satu sistem
> b. Serta apa yang terjadi bila salah satu komponen tidak berfungsi

> Explain the following two points to the assistant:
> a. Explain how the DNS, reverse proxy, and backends work together as a unified system.
> b. Explain what happens if one of the components fails to function.

**Answer:**

```
put your answer here
```
