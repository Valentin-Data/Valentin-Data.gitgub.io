---
layout: default
---

<button onclick="toggleMenu()" style="position:fixed; top:20px; left:20px; z-index:9999; background:#00f2ff; border:none; padding:10px; cursor:pointer;">MENU</button>

<div id="nav-menu" style="display:none; position:fixed; top:60px; left:20px; z-index:9999; background:rgba(11, 14, 20, 0.95); padding:20px; border:1px solid #00f2ff;">
    <a onclick="showSection('inicio')" style="display:block; color:#00f2ff; margin:10px 0; cursor:pointer;">Inicio</a>
    <a onclick="showSection('acerca')" style="display:block; color:#00f2ff; margin:10px 0; cursor:pointer;">Acerca de mí</a>
    <a onclick="showSection('proyectos')" style="display:block; color:#00f2ff; margin:10px 0; cursor:pointer;">Proyectos</a>
    <a onclick="showSection('contacto')" style="display:block; color:#00f2ff; margin:10px 0; cursor:pointer;">Contacto</a>
</div>

<section id="inicio" style="display: flex; justify-content: center; align-items: center; height: 100vh;">
    <img src="{{ '/assets/img/Logo.png' | relative_url }}" alt="Mi Logo" style="width: 300px;">
</section>

<section id="acerca" style="display: none; justify-content: center; align-items: center; height: 100vh;">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Acerca de mí</h2>
    <p>Soy un profesional en formación apasionado por el mundo de los datos, enfocado en desarrollar habilidades sólidas para transformar información bruta en soluciones estratégicas. Cuento con una base técnica de 3 años en la carrera de Ingeniería en Sistemas, lo que me ha proporcionado una mentalidad analítica y estructurada para la resolución de           problemas.
     Actualmente, estoy profundizando mis conocimientos en Data Analytics, motivando por el desafio de extraer valor a          partir de datos complejos, la capacidad de automatizar procesos mediante código y el impacto positivo que tiene una        visualización clara en la toma de decisiones informadas.</p>
  </div>
</section>

<section id="proyectos" style="display: none; justify-content: center; align-items: center; height: 100vh;">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Proyectos</h2>
    <h3 style="color: #00f2ff;">Análisis y Limpieza de Inventario</h3>
    <p>Transformación de un dataset con inconsistencias en información confiable mediante Python.</p>
  </div>
</section>

<section id="contacto" style="display: none; justify-content: center; align-items: center; height: 100vh;">
  <div style="max-width: 800px; background: rgba(11,14,20,0.8); padding: 30px; border-radius: 15px; border: 1px solid #00f2ff;">
    <h2>Contacto</h2>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/valentin-mencuchi" style="color: #00f2ff;">linkedin.com/in/valentin-mencuchi</a></p>
  </div>
</section>
