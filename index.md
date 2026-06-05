---
layout: default
---

<div style="position: fixed; top: 20px; left: 20px; z-index: 1000;">
<button onclick="toggleMenu()" style="position:fixed; top:20px; left:20px; z-index:9999;">MENU</button>

<div id="nav-menu">
    <a onclick="showSection('inicio')">Inicio</a>
    <a onclick="showSection('acerca')">Acerca de mí</a>
    <a onclick="showSection('proyectos')">Proyectos</a>
    <a onclick="showSection('contacto')">Contacto</a>
</div>

<section id="inicio" style="display: flex;">
    <img src="tu_logo.png" alt="Logo">
</section>

<section id="acerca">
    <h2>Acerca de mí</h2>
    <p>Soy un profesional en formación...</p>
</section>

<script>
  function toggleMenu() {
    var menu = document.getElementById('nav-menu');
    menu.style.display = (menu.style.display === 'none') ? 'block' : 'none';
  }

  function showSection(sectionId) {
    // 1. Ocultamos TODAS las secciones
    document.getElementById('inicio').style.display = 'none';
    document.getElementById('acerca').style.display = 'none';
    document.getElementById('proyectos').style.display = 'none';
    document.getElementById('contacto').style.display = 'none';

    // 2. Mostramos SOLO la que queremos
    document.getElementById(sectionId).style.display = 'flex';
    
    // 3. Cerramos el menú
    document.getElementById('nav-menu').style.display = 'none';
  }
</script>

<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <img src="{{ '/assets/img/Logo.png' | relative_url }}" alt="Mi Logo" style="width: 300px;">
</div>

<section id="acerca">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Acerca de mí</h2>
    <p>Soy un profesional en formación apacionado por el mundo de los datos, enfocado en desarrollar habilidades sólidas          para transformar informacion bruta en soluciones estratégicas. Cuento con una base técnica de 3 años en la carrera         de Ingenieria en Sistemas, lo que me ha proporcionado una mentalidad analítica y estructurada para la resolución de        problemas.
       Actualmente, estoy profundizando mis conocimientos en Data Analytics, motivando por el desafio de extraer valor a          partir de datos complejos, la capacidad de automatizar procesos mediante código y el impacto positivo que tiene una        visualización clara en la toma de decisiones informadas.
    </p>
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
