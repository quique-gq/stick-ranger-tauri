<h1>stick-ranger-tauri</h1>
  <p>Stick Ranger for the desktop using Tauri.</p>
  <img src="https://github.com/quique-gq/stick-ranger-tauri/blob/main/screenie_windows.png" alt="Gameplay screenshot on Windows">
    <img src="https://github.com/quique-gq/stick-ranger-tauri/blob/main/screenie_linux.png" alt="Gameplay screenshot on Linux">

<h2 id="where-to-download">Where to Download</h2>
  <p>Precompiled binaries are located in the <a href="https://github.com/quique-gq/stick-ranger-tauri/releases">releases</a> page.</p>
  <p>If playing on Windows, make sure <a href="https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section">WebView2</a> is installed.</p>

<h2>How to Run</h2>
  <h3>Windows</h3>
    <ol>
      <li>Install using the msi file if you downloaded the installer.</li>
      <li>Run the exe file :)</li>
    </ol>
  <h3>Linux</h3>
    <h4>Using the Debian Installer Package</h4>
      <p>On Debian and Debian-based Linux distros (Ubuntu, Linux Mint, etc.), you can install the game using the deb installer located in the <a href="https://github.com/quique-gq/stick-ranger-tauri/releases">releases</a> page.</p>
    <h4>Using the AppImage File</h4>
      <p>If <a href="https://appimage.org/">AppImage</a> is installed on your system, you should be able to run the appimage file located in the <a href="https://github.com/quique-gq/stick-ranger-tauri/releases">releases</a> page.</p>
    <h4>Using the Binary Executable</h4>
      <p>In the executable's file properties, check the option for "Allow executing file as program" if it isn't checked already. This can also be done in the terminal using the <code>chmod +x</code> command. <strong>Example below:</strong></p>
      <pre>cd ./Downloads/stick-ranger-location<br>sudo chmod +x ./Stick_Ranger_Linux</pre>
      <p>If you can't run the executable from your file manager, try running it in the terminal.</p>
  <h3>macOS</h3>
    <p>idk</p>

<h2>How to Build Manually (hasn't been tested on macOS)</h2>
  <h3>Prerequisites</h3>
    <p><strong>It is recommended you use Yarn as the default Node.js package manager instead of NPM (these instructions also use Yarn).</strong></p>
    <ul>
      <li><a href="https://tauri.studio/en/docs/getting-started/setup-windows">Windows</a></li>
      <li><a href="https://tauri.studio/en/docs/getting-started/setup-macos">macOS</a></li>
      <li><a href="https://tauri.studio/en/docs/getting-started/setup-linux/">Linux</a></li>
    </ul>
  <h3>Building</h3>
    <ol>
      <li>Clone this repository.</li>
      <li>Open the terminal and cd into the repository.</li>
      <li>Run <code>yarn tauri build</code>.</li>
    </ol>
    <p>Once Tauri has finished compiling, the binary output should be located in <code>src-tauri/target/release</code>.</p>
