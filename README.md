# Genieacs For Windows (Unofficial)
# [ID]
Genieacs adalah aplikasi gratis opensource untuk mengelola CPE secara masal.
Saya telah mengconvert aplikasi genieacs agar dapat dijalankan di windows.
Sumber asli: https://github.com/genieacs/genieacs

Cara install:
1. Download dan install MongoDB melalui shortcut di file ini (nomor 1)
2. Download dan install NodeJS melalui shortcut di file ini (nomor 2)
3. Buka 3.install-ACS.bat, kemundian tunggu sampai proses selesai

    Genieacs beserta config didalamnya akan otomatis terinstall.
    Akan terbuka comand promt service genieacs, biarkan terbuka.
    Jika service genieacs tidak sengaja tertutup, buka manual di lokasi instalasi genieacs, default di C:\genieacs-app\start.bat
    Genieacs akan otomatis berjalan saat PC logon (menyala).

Untuk akses genieacs, buka IP PC dengan port 3000 di browser.
User: admin
password: admin

Integrasi ONT ke GenieACS
- Buat WAN dengan service TR069, dhcp misalnya jika ingin dipisah.
- Jika sudah ada wan internet_TR069 sebelumnya yang dibuat di PPPoE, boleh digabung tidak perlu tambah wan baru lagi.
- Masukan IP PC di ONT di bagian menu ACS-URL biasanya berada di TR069/ITMS/RMS/Remot Management.
- Isi ACS URL dengan ip PC port 7547, misalkan http://172.16.16.2:7547
- Enable centang
- Lainnya abaikan atau isi sembarang karna pada akhirnya akan terconfig otomatis
- TUnggu berberapa saat perangkat akan masuk ke genieacs

Sawer Kopi https://trakteer.id/r-tech/tip

# [EN]
Genieacs is a free, open-source application for mass CPE management.
I've converted the Genieacs application to run on Windows.
Origina source: https://github.com/genieacs/genieacs


How to install:
1. Download and install MongoDB via the shortcut in this file (number 1).
2. Download and install NodeJS via the shortcut in this file (number 2).
3. Open 3.install-ACS.bat and wait for the process to complete.

Genieacs and its configuration files will be automatically installed.
The Genieacs service command prompt will open; leave it open.
If the Genieacs service is accidentally closed, open it manually from the Genieacs installation location, which is C:\genieacs-app\start.bat by default.
Genieacs will automatically run when the PC logs on.

To access Genieacs, open the PC's IP address using port 3000 in a browser.
User: admin
Password: admin

ONT/CPE Integration with GenieACS
- Create a WAN with TR069 services, such as DHCP, if you want to separate them.
- If you already have an internet_TR069 WAN created using PPPoE, you can combine it without adding a new WAN.
- Enter the PC IP address on the ONT in the ACS-URL menu, usually located at TR069/ITMS/RMS/Remote Management.
- Fill in the ACS URL with the PC IP address and port 7547, for example, http://172.16.16.2:7547
- Check Enable
- Ignore the rest or fill in any fields as they will be configured automatically.
- Wait a few moments for the device to added to GenieACS.

