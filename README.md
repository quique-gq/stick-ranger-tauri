<h1>stick-ranger-tauri</h1>
  <p>Stick Ranger for the desktop using Tauri.</p>
  <img src="https://github.com/quique-gq/stick-ranger-tauri/blob/main/screenie.png" alt="Gameplay screenshot">

<h2>Where to Download</h2>
  <p>Downloads are located in the <a href="https://github.com/quique-gq/stick-ranger-tauri/releases">releases</a> page.</p>

<h2>How to Build Manually (hasn't been tested on Linux or macOS)</h2>
  <h3>Prerequisites</h3>
    <p><strong>It is recommended that you use Yarn as the default package manager instead of NPM (these instructions also use Yarn).</strong></p>
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
