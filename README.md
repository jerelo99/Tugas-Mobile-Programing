# Tugas-Mobile-Programing
Step by step menginstal flutter
1.	Siapkan Software FLUTTER beserta SDK. 
2.	Selanjutnya, download Command Line Tools Only pada link dibawah ini : https://developer.android.com/studio/#command-tools
(download sesuai OS anda).
3.	Download serta Extract ke dalam satu folder baru serta letakkan di dalam Local Disk (C:\Android). Maka hasilnya akan ada 2 folder yaitu folder flutter dan tools. 
4.	Selanjutnya silahkan download OpenJDK di halaman ini, dan pilih yang berekstensi zip. sesuaikan dengan sistem operasi yang digunakan, saya menggunakan versi jdk8u212-b03 . setelah di download jangan lupa untuk mengekstrak ke folder Android yang sudah kita punya sebelumnya dan rename nama folder dari jdk8u212-b03 menjadi openjdk. totalnya sekarang kita punya 3 folder yaitu flutter, tools dan openjdk.

5.	Setelah itu, kita harus menge-set Environment Variable dan Path, untuk windows silahkan buka command prompt dan ketikan command perbaris. 
•	setx JAVA_HOME “C:\Android\openjdk” 
•	setx ANDROID_HOME “C:\Android” 
•	setx ANDROID_SDK_ROOT “C:\Android\tools” 
•	setx path “%path%;”C:\Android\sdk;C:\Android\tools\bin;C:\Android\flutter\bin”
6.	Buka terminal (Command Prompt) di C:/Android/tools/bin lalu ketikkan beberapa perintah berikut. 
•	sdkmanager “system-images;android-28;default;x86_64” 
•	sdkmanager “platform-tools” 
•	sdkmanager “build-tools;28.0.3” 
•	sdkmanager “platforms;android-28” 
7.	Selanjutnya install Visual Studio Code dan ekstension flutter serta dart nya.
8.	Jika semuanya sudah selesai silahkan buka terminal (Command Prompt) di 
Android/flutter atau untuk pengguna windows bisa double klik di
C:\Android\Flutter\flutter_console.bat dan jalankan perintah flutter doctor, maka hasilnya seperti gambar berikut.
