<div class="main-download-instructions"> <div class="main-download-instructions-inner"> <h2 id="install_julia"> <a href="#install_julia">Install <img src="https://julialang.org/assets/infra/logo.svg" class="julialogo inline-h2-julia-logo" alt="Julia"></a></h2> <div class="container pt-sm-2"> <div class="row" id="windows-instructions" style="display: block;"> Install the latest Julia version (<a href="#current_stable_release">v1.10.0</a> December 25, 2023) from the <a href="https://www.microsoft.com/store/apps/9NJNWW8PVKMN">Microsoft Store</a> by running this in the command prompt: <pre><code class="language-plaintext cmdprompt-block">winget install julia -s msstore</code><button class="copy-button">Copy</button></pre>
        <div class="install-platform-note"><span id="platform-subnote-windows">It looks like you're using Windows. </span>For Linux and MacOS instructions <a onclick="showOther()" href="javascript:void(0);">click here</a></div>
      </div>
      <div class="row" id="other-platforms-instructions" style="display: none;">
        Install the latest Julia version (<a href="#current_stable_release">v1.10.0</a> December 25, 2023) by running this in your terminal:
        <pre><code class="language-plaintext bash-block">curl -fsSL https://install.julialang.org | sh</code><button class="copy-button">Copy</button></pre>
        <div class="install-platform-note"><span id="platform-subnote-other" style="display: none;">It looks like you're using a Unix-type system. </span>For Windows instructions <a onclick="showWindows()" href="javascript:void(0);">click here</a></div>
      </div>
    </div>
    <script>
      function showWindows() {
        document.getElementById('windows-instructions').style.display = 'block';
        document.getElementById('other-platforms-instructions').style.display = 'none';
      }
      function showOther() {
        document.getElementById('windows-instructions').style.display = 'none';
        document.getElementById('other-platforms-instructions').style.display = 'block';
      }
      var isWindows = navigator.platform.indexOf('Win') > -1;
      if (isWindows) {
        document.getElementById('platform-subnote-other').style.display = 'none';
        showWindows();
      } else {
        document.getElementById('platform-subnote-windows').style.display = 'none';
        showOther();
      }
    </script>

<p>Once installed <code>julia</code> will be available via the command line interface.</p>
<p>This will install the <a href="https://github.com/JuliaLang/juliaup">Juliaup</a> installation manager, which will automatically install julia and help keep it up to date. The command <code>juliaup</code> is also installed. To install different julia versions see <code>juliaup --help</code>.</p>
<hr>

If possible, do consider <a href="https://github.com/sponsors/MyloCyrus">sponsoring</a> us.</p>


