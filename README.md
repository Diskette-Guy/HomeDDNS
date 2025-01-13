# HomeDDNS
Shell Script Home DDNS (BIND9 nsupdate)

Script นี้รองรับทั้ง IPv4 และ IPv6

จะถือว่าคุณได้ใช้ BIND9 และ ได้กำหนดค่าเซิร์ฟเวอร์ไว้เรียบร้อยแล้ว

## ความต้องการ


ต้องติดตั้ง nsupdate ก่อน (`bind9-dnsutils` บน Debian, `bind9-next-utils` บน RHEL-based และ `dnsutils` บน Arch Linux) หากติดตั้งไว้แล้วก็สามารถใช้งานได้เลย

เพียงแค่แก้ไขไฟล์ Script ตามคำแนะนำข้างในไฟล์

**อย่าลืมเพิ่มเรคคอร์ดเปล่าก่อนใช้** สามารถแก้ไขได้โดยใช้ ```editName.sh```

## ข้อแนะนำ

ควรใช้คู่กับ ```crontab``` แนะนำให้เรียกใช้งานทุก ๆ 1 นาที
