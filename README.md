# README XSS Test

Raw HTML img: <img src=x onerror="this.outerHTML='XSS-EXECUTED-README-IMG-MARKER'">

Raw script tag: <script>console.log('XSS-POC-README-SCRIPT-'+document.domain)</script>

SVG onload: <svg onload="this.outerHTML='XSS-EXECUTED-README-SVG-MARKER'"></svg>

Markdown link javascript href: [click me](javascript:alert(1))
