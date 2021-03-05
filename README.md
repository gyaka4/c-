<!-- PROJECT LOGO -->
<br />
<p align="center">
    <a href="#Csharp-essentials">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
    </a>

<!-- Main -->
## Csharp Essentials



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#tasks">Tasks</a>
      <ul>
        <li><a href="#2020-03-05">2020-03-05</a></li>
      </ul>
    </li>   
  </ol>
</details>

<br />
<br />
<br />

<!-- Imperative -->
## Tasks


Imperative way to run commands with kubectl.


### 2020-03-05

* List pods showing their labels
<pre><code>kubectl get pod --show-labels</code></pre>

* List pods with specific label
<pre><code>kubectl get pod -owide --selector=$label</code></pre>
