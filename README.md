# installflutter
NAMA : HEVEN<br>
NIM : 20175520002<br>
PRODI : TEKNIK INFORMATIKA<br>
MATA KULIAH : PEMROGRAMAN MOBILE (COE-5109)<br>

#INSTALL FLUTTER TANPA ANDROID STUDIO <br>

Langkah-langkah instalasi flutter (spesifikasi ringan) : <br>
1. Download SDK Flutter. Silahkan kunjungi halaman download disini, dan sesuaikan dengan sistem operasi teman teman. saat tulisan ini dibuat flutter dalam versi 1.2.1 Stable. <br>
2. Selanjutnya silahkan download Command Line Tools Only di halaman ini , penampakan nya seperti berikut, silahkan download sesuai sistem operasi yang digunakan.<br>
<br>
<img src="command line.jpg"><br>
<br>
3. Silahkan Ekstrak kedua file tersebut dan letakkan di C:\Android untuk windows dan untuk sistem operasi yang lainnya bisa menaruh di root dan buat folder Android. Maka hasilnya akan ada 2 folder yaitu folder flutter dan tools.<br>
4. sampai sini kita harus menge-set Environment Variable dan Path, untuk windows silahkan buka command prompt dan ketikan command perbaris. <br>
  setx JAVA_HOME “C:\Android\openjdk” <br>
  setx ANDROID_HOME “C:\Android” <br>
  setx ANDROID_SDK_ROOT “C:\Android\tools” <br> 
  setx path “%path%;”C:\Android\sdk;C:\Android\tools\bin;C:\Android\flutter\bin” <br>
  <br>
  <img src="environment.png"><br>
  <br>
5. Buka terminal (Command Prompt) di C:/Android/tools/bin lalu ketikan beberapa perintah berikut. sdkmanager “system-images;android-28;default;x86_64” sdkmanager “platform-tools” sdkmanager “build-tools;28.0.3” sdkmanager “platforms;android-28”.<br>
<br>
sdkmanager “system-images;android-28;default;x86_64” <br>
<br>
<img src="system images.png"><br>
 <br>
sdkmanager “platform-tools” <br>
<br>
<img src="platform tools.png"><br>
 <br>
sdkmanager “build-tools;28.0.3”<br>
<br>
<img src="build tools.png"><br>
 <br>
sdkmanager “platforms;android-28”<br>
<br>
<img src="platform android.png"><br>
 <br>
6. Selanjutnya install Visual Studio Code dan ekstension flutter serta dart nya.<br>
<br>
<img src="vscode flutter.png"><br>
<br>
7. Step terakhir adalah buat project di VsCode dengan klik F1 dan mengetikan Flutter: New Project setelah project selesai di load, klik F5 untuk mendeploy ke android device teman-teman.<br>
<br>
<img src="flutter doctor.JPG"><br>


