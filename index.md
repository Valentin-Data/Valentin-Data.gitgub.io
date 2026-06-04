---
layout: default
---

<!-- Menú Superior Izquierdo -->
<nav style="position: fixed; top: 20px; left: 20px; z-index: 10;">
  <a href="#acerca" style="margin-right: 15px; color: #00f2ff;">Acerca de mí</a>
  <a href="#proyectos" style="margin-right: 15px; color: #00f2ff;">Proyectos</a>
  <a href="#contacto" style="color: #00f2ff;">Contacto</a>
</nav>

<!-- Logo Centrado -->
<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <img src="assets/img/tu-logo.png" alt="Logo" style="width: 300px;">

<div id="chatbot" style="position: fixed; bottom: 20px; right: 20px; cursor: pointer; text-align: right; z-index: 100;">
  <div id="chat-bubble" style="background: #00f2ff; color: #0b0e14; padding: 10px 20px; border-radius: 20px; font-weight: bold;">
    Hola, ¿en qué te puedo ayudar?
  </div>
  <div id="chat-response" style="display: none; background: rgba(0,0,0,0.8); color: white; padding: 15px; margin-top: 10px; border: 1px solid #00f2ff; border-radius: 10px;">
    Data Analytics es el proceso de analizar datos crudos para extraer información útil. Como futuro Data Analyst, mi trabajo será transformar datos en decisiones estratégicas para optimizar procesos.
  </div>
</div>

<script>
  document.getElementById('chatbot').onclick = function() {
    var resp = document.getElementById('chat-response');
    resp.style.display = (resp.style.display === 'none') ? 'block' : 'none';
  };
</script>
</div>

<!-- Secciones (Scroll automático) -->
<section id="acerca" style="height: 100vh; padding: 50px;"><h2>Acerca de mí</h2><p>...</p></section>
<section id="proyectos" style="height: 100vh; padding: 50px;"><h2>Proyectos</h2><p>...</p></section>
<section id="contacto" style="height: 100vh; padding: 50px;"><h2>Contacto</h2><p>...</p></section>
