<div class="main-download-instructions"> <div class="main-download-instructions-inner"> <h2 id="install_julia"> <a href="#install_julia">Install <img src="https://julialang.org/assets/infra/logo.svg" class="julialogo inline-h2-julia-logo" alt="Julia"></a></h2> <div class="container pt-sm-2"> <div class="row" id="windows-instructions" style="display: block;"> Install the latest Julia version (<a href="#current_stable_release">v1.10.0</a> December 25, 2023) from the <a href="https://www.microsoft.com/store/apps/9NJNWW8PVKMN">Microsoft Store</a> by running this in the command prompt: <pre><code class="language-plaintext cmdprompt-block">winget install julia -s msstore</code><button class="copy-button">Copy</button></pre>
        <div class="install-platform-note"><span id="platform-subnote-windows">
                It looks like you're using Windows. </span>For Linux and MacOS instructions <a onclick="showOther()" href="javascript:void(0);">click here</a></div>
      </div>
      <div class="row" id="other-platforms-instructions" style="display: none;">
        Install the latest Julia version (<a href="#current_stable_release">v1.10.0</a> December 25, 2023) by running this in your terminal:
        <pre><code class="language-plaintext bash-block">curl -fsSL https://install.julialang.org | sh</code><button class="copy-button">Copy</button></pre>
        <div class="install-platform-note"><span id="platform-subnote-other" style="display: none;">

<p>Once installed <code>julia</code> will be available via the command line interface.</p>
<p>This will install the <a href="https://github.com/JuliaLang/juliaup">Juliaup</a> installation manager, which will automatically install julia and help keep it up to date. The command <code>juliaup</code> is also installed. To install different julia versions see <code>juliaup --help</code>.</p>
<hr>
<p>Please star us <a href="https://github.com/JuliaLang/julia">on GitHub</a>. If you use Julia in your research, please <a href="https://julialang.org/research/">cite us</a>. If possible, do consider <a href="https://github.com/sponsors/MyloCyrus">sponsoring</a> us.</p>

   </div>
  </div>

<div class="row"><div class="col-12"><table class="downloads table table-hover table-bordered">
  
    <tbody><tr>
      <th> Platform
      </th><th> 64-bit
      </th><th> 32-bit
    
    </th></tr><tr>
      <td> Windows <a href="/downloads/platform/#windows">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/winnt/x64/1.10/julia-1.10.0-win64.exe">installer</a>, <a href="https://julialang-s3.julialang.org/bin/winnt/x64/1.10/julia-1.10.0-win64.zip">portable</a> 
      </td><td> <a href="https://julialang-s3.julialang.org/bin/winnt/x86/1.10/julia-1.10.0-win32.exe">installer</a>,  <a href="https://julialang-s3.julialang.org/bin/winnt/x86/1.10/julia-1.10.0-win32.zip">portable</a>  
    
    </td></tr><tr>
      <td> macOS x86 (Intel or Rosetta) <a href="/downloads/platform/#macos">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/mac/x64/1.10/julia-1.10.0-mac64.dmg">.dmg</a>, <a href="https://julialang-s3.julialang.org/bin/mac/x64/1.10/julia-1.10.0-mac64.tar.gz">.tar.gz</a> 
      </td><td> 
    
    </td></tr><tr>
      <td> macOS (Apple Silicon) <a href="/downloads/platform/#macos">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/mac/aarch64/1.10/julia-1.10.0-macaarch64.dmg">.dmg</a>, <a href="https://julialang-s3.julialang.org/bin/mac/aarch64/1.10/julia-1.10.0-macaarch64.tar.gz">.tar.gz</a> 
      </td><td> 
    
    </td></tr><tr>
      <td> Generic Linux on x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a>
      </td><td>
        <a href="https://julialang-s3.julialang.org/bin/linux/x64/1.10/julia-1.10.0-linux-x86_64.tar.gz">glibc</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x64/1.10/julia-1.10.0-linux-x86_64.tar.gz.asc">GPG</a>),
        <a href="https://julialang-s3.julialang.org/bin/musl/x64/1.10/julia-1.10.0-musl-x86_64.tar.gz">musl</a><sup>[<a href="#musl-fn">1</a>]</sup>
        (<a href="https://julialang-s3.julialang.org/bin/musl/x64/1.10/julia-1.10.0-musl-x86_64.tar.gz.asc">GPG</a>)
      
      </td><td> <a href="https://julialang-s3.julialang.org/bin/linux/x86/1.10/julia-1.10.0-linux-i686.tar.gz">glibc</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x86/1.10/julia-1.10.0-linux-i686.tar.gz.asc">GPG</a>)
      
    
    </td></tr><tr>
      <td> Generic Linux on ARM <a href="/downloads/platform/#linux_and_freebsd">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/linux/aarch64/1.10/julia-1.10.0-linux-aarch64.tar.gz">AArch64</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/aarch64/1.10/julia-1.10.0-linux-aarch64.tar.gz.asc">GPG</a>)
      
      </td><td> <!-- <a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{stable_release_short}}/julia-{{stable_release}}-linux-armv7l.tar.gz">ARMv7-a hard float</a>
                                       (<a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{stable_release_short}}/julia-{{stable_release}}-linux-armv7l.tar.gz.asc">GPG</a>) -->
      
      
    
    </td></tr><tr>
      <td> Generic Linux on PowerPC <a href="/downloads/platform/#linux_and_freebsd">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/linux/ppc64le/1.10/julia-1.10.0-linux-ppc64le.tar.gz">little endian</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/ppc64le/1.10/julia-1.10.0-linux-ppc64le.tar.gz.asc">GPG</a>)
      
      </td><td>
      
    
    </td></tr><tr>
      <td> Generic FreeBSD on x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a>
      </td><td> <a href="https://julialang-s3.julialang.org/bin/freebsd/x64/1.10/julia-1.10.0-freebsd-x86_64.tar.gz">.tar.gz</a>
        (<a href="https://julialang-s3.julialang.org/bin/freebsd/x64/1.10/julia-1.10.0-freebsd-x86_64.tar.gz.asc">GPG</a>)
      
      </td><td> 
    
  
</td></tr></tbody></table>
<table>
  
    <tbody><tr>
      <th> Source 
      </th><td> <a href="https://github.com/JuliaLang/julia/releases/download/v1.10.0/julia-1.10.0.tar.gz">Tarball</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v1.10.0/julia-1.10.0.tar.gz.asc">GPG</a>)
      
      </td><td> <a href="https://github.com/JuliaLang/julia/releases/download/v1.10.0/julia-1.10.0-full.tar.gz">Tarball with dependencies</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v1.10.0/julia-1.10.0-full.tar.gz.asc">GPG</a>)
      
      </td><td> <a href="https://github.com/JuliaLang/julia/tree/v1.10.0">GitHub</a> 
    
  
</td></tr></tbody></table></div></div>
