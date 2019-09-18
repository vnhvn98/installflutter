# installflutter
NAMA : HEVEN
NIM : 20175520002
PRODI : TEKNIK INFORMATIKA
MATA KULIAH : PEMROGRAMAN MOBILE (COE-5109)

INSTALL FLUTTER TANPA ANDROID STUDIO <br>

Langkah-langkah instalasi flutter (spesifikasi ringan) : <br>
1. Download SDK Flutter. Silahkan kunjungi halaman download disini, dan sesuaikan dengan sistem operasi teman teman. saat tulisan ini dibuat flutter dalam versi 1.2.1 Stable. <br>
2. Selanjutnya silahkan download Command Line Tools Only di halaman ini , penampakan nya seperti berikut, silahkan download sesuai sistem operasi yang digunakan.<br>
<img src="command line.jpg"><br>
3. Silahkan Ekstrak kedua file tersebut dan letakkan di C:\Android untuk windows dan untuk sistem operasi yang lainnya bisa menaruh di root dan buat folder Android. Maka hasilnya akan ada 2 folder yaitu folder flutter dan tools.<br>
<
4. sampai sini kita harus menge-set Environment Variable dan Path, untuk windows silahkan buka command prompt dan ketikan command perbaris. <br>
  setx JAVA_HOME “C:\Android\openjdk” <br>
  setx ANDROID_HOME “C:\Android” <br>
  setx ANDROID_SDK_ROOT “C:\Android\tools” <br> 
  setx path “%path%;”C:\Android\sdk;C:\Android\tools\bin;C:\Android\flutter\bin” <br>
  <img src="environment.png"><br>
5. Buka terminal (Command Prompt) di C:/Android/tools/bin lalu ketikan beberapa perintah berikut. sdkmanager “system-images;android-28;default;x86_64” sdkmanager “platform-tools” sdkmanager “build-tools;28.0.3” sdkmanager “platforms;android-28”.<br>

sdkmanager “system-images;android-28;default;x86_64” <br>
<img src="system images.png"><br>
 
sdkmanager “platform-tools” <br>
<img src="platform tools.png"><br>
 
sdkmanager “build-tools;28.0.3”<br>
<img src="build tools.png"><br>
 
sdkmanager “platforms;android-28”<br>
<img src="platform android.png"><br>
 
6. Selanjutnya install Visual Studio Code dan ekstension flutter serta dart nya.<br>
<img src="vscode flutter.png"><br>

7. Step terakhir adalah buat project di VsCode dengan klik F1 dan mengetikan Flutter: New Project setelah project selesai di load, klik F5 untuk mendeploy ke android device teman-teman.<br>

<img src="flutter doctor.JPG"><br>


