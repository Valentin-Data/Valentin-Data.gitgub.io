---
layout: default
---

<div style="position: fixed; top: 20px; left: 20px; z-index: 1000;">
  <button onclick="toggleMenu()" style="background: #00f2ff; border: none; padding: 10px; cursor: pointer; border-radius: 5px; font-weight: bold;">
    ☰ MENU
  </button>
  
  <div id="nav-menu" style="display: none; background: rgba(11, 14, 20, 0.9); padding: 15px; margin-top: 5px; border: 1px solid #00f2ff;">
    <a href="#acerca" style="display: block; color: #00f2ff; margin-bottom: 10px;">Acerca de mí</a>
    <a href="#proyectos" style="display: block; color: #00f2ff; margin-bottom: 10px;">Proyectos</a>
    <a href="#contacto" style="display: block; color: #00f2ff;">Contacto</a>
  </div>
</div>

<script>
  function toggleMenu() {
    var menu = document.getElementById('nav-menu');
    menu.style.display = (menu.style.display === 'none') ? 'block' : 'none';
  }
</script>

<div style="display: flex; justify-content: center; align-items: center; height: 80vh;">
  <img src="{{ '/assets/img/Logo.png' | relative_url }}" alt="Mi Logo" style="width: 300px; max-width: 90%;">
</div>

<section id="acerca"><h2>Acerca de mí</h2><p>...</p></section>
<section id="proyectos"><h2>Proyectos</h2><p>...</p></section>
<section id="contacto"><h2>Contacto</h2><p>...</p></section>
