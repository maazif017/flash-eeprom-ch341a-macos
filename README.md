# flash-eeprom-ch341a-macos

Hi, friends. I show you how use CH341A Programmer in Mac OS with Terminal.app.

1. Open terminal.
2. Type into terminal "xcode-select --install".
3. Type ...
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
4. Type "brew install flashrom".
5. And then, Connect the programmer to USB Mac. I used Dongle Type-C.
6. Automatically, the CH341A application is installed into Terminal.app.
7. For help, Type "sudo flashrom -p ch341a_spi --help".
7. For erase, Type "sudo flashrom -p ch341a_spi --erase".
8. For write <file> to flash, Type "sudo flashrom -p ch341a_spi --write <file_name>".
9. For verify flash against <file>, Type "sudo flashrom -p ch341a_spi --verify <file_name>".
  

<img width="634" alt="Screen Shot 1443-05-23 at 11 04 59" src="https://user-images.githubusercontent.com/40708744/147526841-bd9e72e5-d6fa-4677-b665-65d88ae30e05.png">
