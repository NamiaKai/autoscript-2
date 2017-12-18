# repo
Berikut adalah langkah-langkah eksekusi Script Auto Install untuk VPS Debian 7 32 bit atau 64 bit :
1. Login ke VPS dengan menggunakan user root, via aplikasi Putty, JuiceSSH atau Connecbot
2. Install sertifikat dengan perintah :
apt-get install ca-certificates
3. Download script dengan perintah :
wget https://raw.githubusercontent.com/NamiaKai/autoscript-2/master/debian7.sh
4. Atur permisi dengan perintah :
chmod +x debian7.sh
5. Terakhir, eksekusi script dengan perintah :
./debian7.sh
Installasi memakan waktu lebih kurang 3 – 5 menit.
