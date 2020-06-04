### <b>Windows Server</b>
Baca Documentasi Microsoft ini karena sudah jelas: <br/>
https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-iis?view=aspnetcore-3.1&tabs=visual-studio <br/>
Langkah langkah nya adalah:
<ol>
<li>Install Hosting bundle di Servermu. (Ingat bukan runtime ya tapi hosting bundle sesuai dengan versi .netcore aplikasimu)</li>
<li>Buat Site di IIS portalmu. (misalkan kamu ingin URL IP server langsung open aplikasi mu maka tinggal replace saja default folder ke folder aplikasimu)(jika iis belum terinstal maka kamu harus install dulu dari control panel)</li>
<li>Deploy Aplikasimu. (masuk Visual Studio klik publish lalu pastekan hasil publish itu ke folder servermu)</li>
</ol>

