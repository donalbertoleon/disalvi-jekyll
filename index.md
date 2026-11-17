---
layout: default
title: Vidrio, cancelería y canceles de cristal templado en CDMX
description: En Disalvi tenemos sus soluciones en cancelería, canceles de aluminio y de cristal templado en CDMX y zona metropolitana.
---

<section class="hero">
  <p class="lema">La excelencia en servicio</p>
  <h1>Diseño y soluciones en <span>Aluminio y Vidrio</span></h1>
  <p class="hero-texto">En DISALVI tenemos soluciones en cancelería, canceles de aluminio y cristal templado. Diseñamos espacios que combinan funcionalidad, estética y seguridad.</p>
  <div class="hero-botones">
    <a class="boton" href="#servicios">Descubrir servicios ›</a>
    <a class="boton boton-claro" href="#contacto">Solicitar cotización</a>
  </div>
</section>

<section class="franja" id="servicios">
  <h2>Cumplimos tus proyectos</h2>
  <ul class="servicios">
    {% for s in site.data.servicios %}
    <li>
      <a href="{{ s.url | relative_url }}" style="--img: url('{{ s.imagen | relative_url }}')">
        <strong class="svc-titulo">{{ s.titulo }}</strong>
        <span>Ver más ›</span>
      </a>
    </li>
    {% endfor %}
  </ul>
</section>

<section class="seccion seccion-tinta">
  <h2>Compromiso y calidad</h2>
  <p class="checks"><span>✓ Somos profesionales</span> <span>✓ Los mejores materiales</span></p>
  <div class="tres">
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M20 13c0 5-3.5 7.5-7.66 8.95a1 1 0 0 1-.67-.01C7.5 20.5 4 18 4 13V6a1 1 0 0 1 1-1c2 0 4.5-1.2 6.24-2.72a1.17 1.17 0 0 1 1.52 0C14.51 3.81 17 5 19 5a1 1 0 0 1 1 1z"/><path d="m9 12 2 2 4-4"/></svg></span>
      <h3>Compromiso</h3>
      <p>Garantizamos el correcto funcionamiento de nuestro trabajo para asegurar su inversión.</p>
    </div>
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="m15.477 12.89 1.515 8.526a.5.5 0 0 1-.81.47l-3.58-2.687a1 1 0 0 0-1.197 0l-3.586 2.686a.5.5 0 0 1-.81-.469l1.514-8.526"/><circle cx="12" cy="8" r="6"/></svg></span>
      <h3>Calidad</h3>
      <p>Contamos con el equipo necesario que el trabajo requiera. Nuestro sello distintivo en cada trabajo entregado.</p>
    </div>
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M15 14c.2-1 .7-1.7 1.5-2.5 1-.9 1.5-2.2 1.5-3.5A6 6 0 0 0 6 8c0 1 .2 2.2 1.5 3.5.7.7 1.3 1.5 1.5 2.5"/><path d="M9 18h6"/><path d="M10 22h4"/></svg></span>
      <h3>Innovación</h3>
      <p>¿Alguna idea en mente? ¡Le ayudamos a realizarla! Estamos en constante actualización ante las nuevas tendencias del mercado.</p>
    </div>
  </div>
</section>

<section class="seccion">
  <div class="tres tarjetas">
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6 22V4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v18Z"/><path d="M6 12H4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h2"/><path d="M18 9h2a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2h-2"/><path d="M10 6h4"/><path d="M10 10h4"/><path d="M10 14h4"/><path d="M10 18h4"/></svg></span>
      <h3>Proyectos empresariales</h3>
      <p>Una amplia variedad de productos exclusivos. Hacemos que el delimitar espacios se convierta en algo funcional, duradero y estético.</p>
    </div>
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M10 10V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v5"/><path d="M14 6a6 6 0 0 1 6 6v3"/><path d="M4 15v-3a6 6 0 0 1 6-6"/><rect x="2" y="15" width="20" height="4" rx="1"/></svg></span>
      <h3>Construcción</h3>
      <p>Diseño y estilo acorde a las necesidades de grandes y medianos proyectos. Damos el detalle necesario para su trabajo.</p>
    </div>
    <div>
      <span class="icono"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M15 21v-8a1 1 0 0 0-1-1h-4a1 1 0 0 0-1 1v8"/><path d="M3 10a2 2 0 0 1 .709-1.528l7-5.999a2 2 0 0 1 2.582 0l7 5.999A2 2 0 0 1 21 10v9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/></svg></span>
      <h3>Proyectos individuales</h3>
      <p>Amplia variedad de perfiles y acabados, la solución que más se adapte a su espacio y diseño sin dejar de lado la practicidad, comodidad y seguridad que merece.</p>
    </div>
  </div>
</section>

<section class="seccion seccion-contacto" id="contacto">
  <h2>Contáctanos</h2>
  <p>Pide tu cotización o envíanos tus dudas.</p>
  {% include formulario-contacto.html %}
</section>
