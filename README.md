# Installer Passwall Lite
1. Cara pasang Installer passwall lite
   Paste Command ini di terminal
   ```
   wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/installer-passwall-lite/main/inpass" -O /tmp/inpass && chmod 777 /tmp/inpass
   ```
2. Jalankan installer dengan ketik command dibawah
   ```
   cd /tmp && sh inpass
   ```
3. Pilih dulu script repo untuk dengan mengetik ``in1``
```
**     SELAMAT DATANG INSTALLER PASSWALL LITE       **
**                                                  **
******************************************************
**      PILIH ARCH SESUAI DEVICE YANG DIPAKAI!!!    **
******************************************************
**         DAFTAR :                    *  PERINTAH :**
**  SCRIPT REPO                        * sh inpass 1**
**  INSTALL PASSWALL 16MB MIPSEL_24KC  * sh inpass 2**
**  INSTALL PASSWALL >32MB MIPSEL_24KC * sh inpass 3**
**  INSTALL PASSWALL STB AMLOGIC       * sh inpass 4**
******************************************************
**        INSTALLER PASSWALL LITE BY ALKHANET       **
```
4. Pasang dulu ``Custom Repo`` untuk menginstall paket pendukung ``Passwall Lite``
   ```
   sh inpass 1
   ```
5. Kemudian pilih sesuai arch device yang di pakai contoh saya pakai untuk Mi4A GE rom 16MB pilih ``16MB MIPSEL_24KC``
   ```
   sh inpass 2
   ```
5. Tunggu sampai Proses installasi selesai

# Note 
  PASTIKAN JARINGAN INTERNET STABIL
  
# Thanks To
- Script AIN [Vito Harhari](https://github.com/vitoharhari)
- Custom Repo [Nugroho](https://github.com/lrdrdn) 
