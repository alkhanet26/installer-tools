# Installer Tools
1. Cara pasang Installer Tools
   Paste Command ini di terminal
   ```
   wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/installer-tools/main/inpass" -O /tmp/inpass && chmod 777 /tmp/inpass && cd /tmp && sh inpass
   ```
   
```
echo -e "$DB ******************************************************"
echo -e "$DB ******************************************************"
echo -e " **                                                  **"
echo -e "$DB **$R       SELAMAT DATANG INSTALLER TOOLS       $DB**"
echo -e " **                                                  **"
echo -e "$DB ******************************************************"
echo -e "$DB **$Y     PILIH ARCH SESUAI DEVICE YANG DIPAKAI!!!     $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB **$G        DAFTAR :                    *  PERINTAH : $DB**"
echo -e "$DB **$G SCRIPT REPO                        * sh inpass 1 $DB**"
echo -e "$DB **$G INSTALL PASSWALL 16MB MIPSEL_24KC  * sh inpass 2 $DB**"
echo -e "$DB **$G INSTALL XRAY WSS MIPSEL_24KC       * sh inpass ws$DB**"
echo -e "$DB **$G INSTALL PASSWALL ALL ARCH          * sh inpass 3 $DB**"
echo -e "$DB **$G INSTALL OPENCLASH ALL ARCH         * sh inpass 4 $DB**"
echo -e "$DB **$G INSTALL CORE MIPSEL_24KC           * sh inpass cr$DB**"
echo -e "$DB **$G INSTALL TERMINAL                   * sh inpass 5 $DB**"
echo -e "$DB **$G INSTALL AUTO SYNC JAM              * sh inpass 6 $DB**"
echo -e "$DB **$G INSTALL AUTO RELEASE RAM           *sh inpass cup$DB**"
echo -e "$DB **$G INSTALL AUTO VMESS CONVERTER       *sh inpass vms$DB**"
echo -e "$DB ******************************************************"
echo -e "$DB **$Y           INSTALLER TOOSL BY ALKHANET            $DB**"
echo -e "$DB **$B                 VERSI ALPHA 1.0                  $DB**"
echo -e "$DB ******************************************************"
echo -e "$DB ******************************************************"
```
2. Pasang dulu ``Custom Repo`` untuk menginstall paket pendukung ``TOOLS`` yang mau dipasang
   ```
   sh inpass 1
   ```
3. Kemudian pilih sesuai arch device yang di pakai contoh saya pakai untuk Mi4A GE rom 16MB pilih ``INSTALL PASSWALL 16MB MIPSEL_24KC`` 
   ```
   sh inpass 2
   ```
4. Tunggu sampai Proses installasi selesai

# INFORMATION
  - Installer Tools ini dibuat untuk mempermudah dalam penginstallasian ``Tools`` dalam firmware ``Openwrt``
  - Akan selalu di update sesuai dengan ``Tools`` yang sudah ada dan umum di pergunakan dalam firmware ``Openwrt``

1. Tools ``Passwall`` saya buat khusus untuk ``mipsel_24kc`` dengan rom 16MB karena tools ini yang bisa berjalan dengan baik di router minim
   - ``Passwall mipsel_24kc 16MB``
       * Xray-core dengan pengurangan vless
       * Protocol vmess dan trojan-ws berajalan baik disini
   - ``Passwall All arch``
       * Passwall untuk rom diatas 64MB
       * Xray-core lates dan support semua protocol
       * untuk xray-core wss silahkan replace sendiri sesuai dengan ``ARCH`` masing" device
2. Tools ``Openclash`` bisa untuk semua ``ARCH`` tetapi pertimbangkan juga space rom yang tersedia tools ini minimal rom 32MB
   - Untuk 16MB bisa di install tetapi core tidak permanen pertimbangkan juga penggunaan ram yang akan terpakai banyak oleh source ``Openclash``
   - Setelah Installasi selesai silahkan download core di ``Openclash`` di menu ``Global Settings`` tab ``Version Update``


# NOTE
  - Jika sudah memakai ``Custom Repo`` bisa di SKIP untuk command ``sh inpass 1``
  - PASTIKAN JARINGAN INTERNET STABIL
  
# Thanks To
- Script AIN [Vito Harhari](https://github.com/vitoharhari)
- Custom Repo [Nugroho](https://github.com/lrdrdn) 

# Support Me
- [Beli Kopi](https://saweria.co/alkhanet)
