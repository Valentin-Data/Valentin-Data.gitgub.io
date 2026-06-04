---
layout: default
---

<div style="position: fixed; top: 20px; left: 20px; z-index: 1000;">
  <button onclick="toggleMenu()" style="background: #00f2ff; border: none; padding: 10px; cursor: pointer; border-radius: 5px; font-weight: bold;">
    ☰ MENU
  </button>
  <div id="nav-menu" style="display: none; background: rgba(11, 14, 20, 0.9); padding: 15px; margin-top: 5px; border: 1px solid #00f2ff; border-radius: 5px;">
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

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <img src="{{ '/assets/img/Logo.png' | relative_url }}" alt="Mi Logo" style="width: 300px;">
</div>

<section id="acerca">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Acerca de mí</h2>
    <p>Soy un profesional en formación apasionado por el mundo de los datos, enfocado en desarrollar habilidades sólidas para transformar información bruta en soluciones estratégicas. Cuento con una base técnica de 3 años en la carrera de Ingeniería en Sistemas...</p>
  </div>
</section>

<section id="proyectos">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Proyectos</h2>
    <div style="margin-bottom: 20px;">
        <h3 style="color: #00f2ff;">Análisis y Limpieza de Inventario</h3>
        <p>Transformación de un dataset con inconsistencias en información confiable y estructurada mediante Python (pandas, matplotlib), permitiendo un análisis de stock preciso.</p>
    </div>
    <div>
        <h3 style="color: #00f2ff;">Otros Proyectos</h3>
        <p>[Próximamente] - Estoy trabajando en nuevas implementaciones y análisis de datos.</p>
    </div>
  </div>
</section>

<section id="contacto">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Contacto</h2>
    <ul style="list-style: none; padding: 0;">
      <li style="margin: 15px 0;"><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/valentin-mencuchi" style="color: #00f2ff;">linkedin.com/in/valentin-mencuchi</a></li>
      <li style="margin: 15px 0;"><strong>GitHub:</strong> <a href="https://github.com/Valentin-Data" style="color: #00f2ff;">github.com/Valentin-Data</a></li>
      <li style="margin: 15px 0;"><strong>Email:</strong> <a href="mailto:analytics.valentin.mencuchi@gmail.com" style="color: #00f2ff;">analytics.valentin.mencuchi@gmail.com</a></li>
    </ul>
  </div>
</section>
