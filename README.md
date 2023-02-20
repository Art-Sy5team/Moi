<h1 align="center"><strong>SETUP Testnet Moi<strong></h1>

- [Website](https://iome.ai/)
- [Discord](https://discord.gg/jjx8sJ8TkB)
- [Explorer](https://voyage.moi.technology/)
- [Dashboard](https://iome.ai/signup)
- [Doc offcial](https://validator.moi.technology/docs?activeTab=CLI)

## Spesifikasi Minimum

| Komponen    | Requirements minimal                          |
| ----------- | --------------------------------------------- |
| sistem      | Ubuntu 20.04 atau lebih tinggi                |
| CPU         | 4 Cores                                       |
| RAM         | 8 GB                                          |
| Penyimpanan | 250 GB SSD                                    |
| Koneksi     | 20 mbps / 50 mbps upload & bandwidth download |

<h1 align="center"><strong>SETUP Dashboard MOI ID<strong></h1>

- Buat akun telebih dahulu [MOI ID](https://iome.ai/)
- Buat Usernam dan Password
- Login dan Verifikasi KYC
- Tunggu 5-10 menit iome juga punya aplikasih di [Play Store](https://play.google.com/store/apps/details?id=com.sarvalabs.iome)

<h1 align="center"><strong>SETUP NODE<strong></h1>

Install Node.js & npm

```
curl -sL https://deb.nodesource.com/gpgkey/nodesource.gpg.key | sudo apt-key add -
```

```
echo "deb https://deb.nodesource.com/node_18.14.1 $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/nodesource.list
```

```
apt install npm
```

Check Versi JS & NPM

```
node -v
npm -v
```

<h1 align="center"><strong>RUN NODE<strong></h1>

Step ini ada dua cara manual dan otomatis!

### Auto Install

```
wget -O setup_moipod_indus.sh https://run-indus.moi.technology && chmod +x setup_moipod_indus.sh && bash setup_moipod_indus.sh
```

- Masukan Username Akun
- Masukan Passowrd Akun
- Bagian MOI Pod Masukan Passowrd juga
- Done & tunggu 24 jam untuk Validator muncul di Dashboar akun

### Manual Install

Install moipod, saat ini Versi v0.5.2

```
sudo curl -o moipod https://validator.moi.technology/moipod/v0.5.2/moipod.linux && sudo chmod +x moipod
```

```
sudo npm i @nuid/zk@0.0.12 -g
```

```
./moipod --username <MOI-ID username> --password <MOI-ID password> --nodepass <node password>
```

```
./moipod --username <MOI-ID username> --password <MOI-ID password> --nodepass <node password> --kramaID <kramaID of the node to be imported>
```

```
./moipod --username <moi-id username> --password <moi-id password> --nodepass <node password> --deregister
```
  
### Art-Team INFO

noted: **art team** here does not have any specific goals or intentions, they only collect data and share it with everyone.

untuk INFO Testnet lainya Silahkan join Discord 👇

[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ArtSy5team)
[![Discord](https://img.shields.io/badge/discord-7289d9?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/EAKEdZU6c8)
[![Github](https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/Art-Sy5team)
[![trakteer](https://img.shields.io/badge/trakteer.id-e31e1e?style=for-the-badge&logo=ko-fi&logoColor=white)](https://trakteer.id/Art-Sy5team/tip)
