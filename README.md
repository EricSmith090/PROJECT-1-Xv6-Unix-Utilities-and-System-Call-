# PROJECT-1-Xv6-Unix-Utilities-and-System-Call-
1. Để test XARGS gõ vào terminal: (đã có dấu nhắc lệnh $ của hệ điều hành xv6 hiện ra)
make clean
make qemu
echo hello too | xargs echo bye
2. Để test PROCINFOR gõ vào terminal:
make clean
make qemu
procinfortest
-> hiện ra infor của chính process procinfortest được gọi.