# How-to-full-screen-Kali-Linux-on-VirtualBox
How to full-screen Kali Linux on VirtualBox

1-)Terminal ekranında leafpad /etc/apt/sources.list yaz.
Açılan txt dosyasındaki herşeyi sil .Aşağıdakileri yapıştır ve Kaydet.

deb http://http.kali.org/kali kali-rolling main contrib non-free
deb-src http://http.kali.org/kali kali-rolling main contrib non-free

2-)Terminal > apt-get update

3-)Terminal > apt-cache search linux-headers , yazıp çıktılar arasından

linux-headers-4.16.0-kali2-all-amd64 olanı kopyala.Terminale 

sudo apt-get install linux-headers-4.16.0-kali2-all-amd64 komutunu yaz.

4-)Terminal > apt-cache search linux-image yazıp çıktılar arasından

linux-image-4.16.0-kali2-amd64 olanı kopyala.

sudo apt-get install linux-image-4.16.0-kali2-amd64 komutunu yaz.

5-)Terminal > apt-get install virtualbox-guest-x11

reboot


















