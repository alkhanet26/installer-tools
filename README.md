# Installer Tools
1. Cara pasang Installer Tools
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
**     SELAMAT DATANG INSTALLER TOOLS       **
**                                                  **
******************************************************
**      PILIH ARCH SESUAI DEVICE YANG DIPAKAI!!!    **
******************************************************
**         DAFTAR :                    *  PERINTAH :**
**  SCRIPT REPO                        * sh inpass 1**
**  INSTALL PASSWALL 16MB MIPSEL_24KC  * sh inpass 2**
**  INSTALL PASSWALL ALL ARCH          * sh inpass 3**
**  INSTALL OPENCLASH ALL ARCH         * sh inpass 4**
******************************************************
**        INSTALLER TOOLS BY ALKHANET       **
```
4. Pasang dulu ``Custom Repo`` untuk menginstall paket pendukung ``TOOLS`` yang mau dipasang
   ```
   sh inpass 1
   ```
5. Kemudian pilih sesuai arch device yang di pakai contoh saya pakai untuk Mi4A GE rom 16MB pilih ``INSTALL PASSWALL 16MB MIPSEL_24KC`` 
   ```
   sh inpass 2
   ```
5. Tunggu sampai Proses installasi selesai

# INFORMATION
  - Installer Tools ini dibuat untuk mempermudah dalam penginstallasian ``Tools`` dalam firmware ``Openwrt``
  - Akan selalu di update sesuai dengan ``Tools`` yang sudah ada dan umum di pergunakan dalam firmware ``Openwrt``

1. Tools ``Passwall`` saya buat khusus untuk ``mipsel_24kc`` dengan rom 16MB karena tools ini yang bisa berjalan dengan baik di router minim
   - ``Passwall mipsel_24kc 16MB``
       * Xray-core dengan pengurangan vless
       * Protocol vmess dan trojan-ws berajalan baik disini
   - ``Passwall All arch``
       * Passwall untuk room diatas 64MB
       * Xray-core lates dan support semua protocol
       * untuk xray-core wss silahkan replace sendiri sesuai dengan ``ARC`` masing" device
2. Tools ``Openclash`` bisa untuk semua ``ARC`` tetapi pertimbangkan juga space rom yang tersedia tools ini minimal rom 32MB
   - Untuk 16MB bisa di install tetapi core tidak permanen pertimbangkan juga penggunaan ram yang akan terpakai banyak oleh source ``Openclash``
   - Setelah Installasi selesai silahkan download core di ``Openclash`` di menu ``Global Settings`` tab ``Version Update``


# NOTE
  PASTIKAN JARINGAN INTERNET STABIL
  
# Thanks To
- Script AIN [Vito Harhari](https://github.com/vitoharhari)
- Custom Repo [Nugroho](https://github.com/lrdrdn) 
