# All You need to do
1. Install NodeJS
2. Install JDK
3. Install Android Emulator
4. Tambahkan yang diperlukan sampai pada tambah avd manager
5. Tambahkan ini pada ~/.bash_profile

export ANDROID_HOME=$HOME/Library/Android/sdk

export PATH=$PATH:$ANDROID_HOME/tools

export PATH=$PATH:$ANDROID_HOME/platform-tools

6. Ketik source $HOME/.bash_profile
7. Cek emulator pada avd yang sudah berhasil ditambahkan dengan perintah
   emulator -list-avds misal keluar 
   Nexus_5X_API_24 dsb jika lebih dari 1
8. Untuk menjalankan emulator harus ke {$android_home/tools}
   cd /Users/rama/Library/Android/sdk/tools
   maka perintahnya adalah
   emulator -avd Nexus_5X_API_24

   ################## SNIFF #####################

# Instalasi React Native App & CLI
1. Untuk CLI setelah install NODE lanjutkan install watchman
   brew install watchman
2. npm install -g create-react-native-ap
3. npm install -g react-native-cli
4. create-react-native-app MyApp
5. cd MyApp
6. jika ingin pakai Expo langsung scan saja pakai HH kalian
   npm start
   kemudian pilih device yang dipakai bisa android atau iOS
7. jika langsung pakai avd android bisa dijalankan emulatornya, hal ini juga berlaku jika pakai xcode
8. jalankan perintah

   npm run eject

   kemudian jalankan sesuai emulator misal

   react-native run-android
   
   tunggu sampai prosesnya selesai maka akan dijalankan pada emulator pilihan
## DONE 