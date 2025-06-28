# Juegos-de-ESI-
<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Explorá la Sexualidad con ESI</title>
  <style>
    * { box-sizing: border-box; }
    body { font-family: Arial, sans-serif; background-color: #f7f7fb; margin: 0; padding: 0; }
    header { background-color: #4e73df; color: white; padding: 20px; text-align: center; }
    section { padding: 20px; max-width: 1000px; margin: auto; }
    .game-card { background: white; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 20px; margin: 20px 0; }
    h2 { color: #4e73df; font-size: 1.4em; }
    button { background-color: #1cc88a; color: white; padding: 10px 15px; border: none; border-radius: 5px; cursor: pointer; font-size: 1em; width: 100%; max-width: 300px; display: block; margin: 10px auto 0; }
    button:hover { background-color: #17a673; }
    footer { background-color: #eaeaea; text-align: center; padding: 15px; margin-top: 40px; font-size: 0.9em; }.modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); justify-content: center; align-items: center; z-index: 1000; padding: 10px; }
.modal-content { background: white; padding: 20px; border-radius: 10px; max-width: 500px; width: 100%; text-align: left; position: relative; box-shadow: 0 4px 10px rgba(0,0,0,0.2); }
.close { position: absolute; top: 10px; right: 15px; font-size: 20px; cursor: pointer; }
@media screen and (max-width: 600px) {
  h2 { font-size: 1.2em; }
  .modal-content { padding: 15px; }
  button { font-size: 0.95em; padding: 8px 12px; }
}

  </style>
</head>
<body>  <header>
    <h1>Explorá la Sexualidad con Perspectiva Integral</h1>
    <p>Juegos interactivos para aprender sobre la ESI de forma lúdica y respetuosa</p>
  </header>  <section>
    <div class="game-card">
      <h2>Juego 1: Cuerpos Diversos</h2>
      <p>Reconocé la diversidad en los cuerpos humanos: sexo biológico, identidad de género y expresión de género. Explorá qué significa ser cis, trans, intersex y cómo cada persona se identifica.</p>
      <button onclick="showModal('modal1')">Jugar</button>
    </div><div class="game-card">
  <h2>Juego 2: Mi Historia, Mi Identidad</h2>
  <p>Elegí un personaje y acompañalo en decisiones importantes sobre su sexualidad, emociones y vínculos. Abordá los aspectos psicológicos, sociales y culturales de la sexualidad.</p>
  <button onclick="showModal('modal2')">Jugar</button>
</div>

<div class="game-card">
  <h2>Juego 3: Afectividad en Juego</h2>
  <p>Conectá situaciones con emociones. Aprendé a identificar y expresar sentimientos, respetar límites y valorar el consentimiento en las relaciones.</p>
  <button onclick="showModal('modal3')">Jugar</button>
</div>

<div class="game-card">
  <h2>Juego 4: Salud y Autocuidado</h2>
  <p>Respondé preguntas sobre cuidado del cuerpo, higiene, prevención de infecciones, visitas médicas y más. Un juego para cuidar nuestro cuerpo y el de las demás personas.</p>
  <button onclick="showModal('modal4')">Jugar</button>
</div>

<div class="game-card">
  <h2>Juego 5: ¿Qué es la Sexualidad?</h2>
  <p>Una trivia para reflexionar sobre la sexualidad como un concepto complejo que incluye lo biológico, psicológico, social, cultural y emocional. ¡Poné a prueba tus conocimientos!</p>
  <button onclick="showModal('modal5')">Jugar</button>
</div>

  </section>  <footer>
    <p>© 2025 Explorá con ESI | Educación Sexual Integral para todas las edades</p>
  </footer>  <!-- Modals (Juegos interactivos) -->  <div class="modal" id="modal1">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal1')">&times;</span>
      <h3>Cuerpos Diversos</h3>
      <p>¿Qué diferencia hay entre sexo biológico e identidad de género?</p>
      <button onclick="alert('Correcto: No son lo mismo.')">No son lo mismo</button>
      <button onclick="alert('Incorrecto. Intentalo otra vez.')">Son iguales</button>
    </div>
  </div>  <div class="modal" id="modal2">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal2')">&times;</span>
      <h3>Mi Historia, Mi Identidad</h3>
      <p>Sofía se siente diferente al sexo asignado al nacer. ¿Qué debe hacer?</p>
      <button onclick="alert('Correcto: Puede explorar su identidad con libertad.')">Explorar su identidad</button>
      <button onclick="alert('Incorrecto. Intentalo otra vez.')">Ignorarlo</button>
    </div>
  </div>  <div class="modal" id="modal3">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal3')">&times;</span>
      <h3>Afectividad en Juego</h3>
      <p>Martina dijo que no quiere un beso. ¿Qué hacés?</p>
      <button onclick="alert('Correcto: Respetar su decisión.')">Respetar su decisión</button>
      <button onclick="alert('Incorrecto. Intentalo otra vez.')">Insistir</button>
    </div>
  </div>  <div class="modal" id="modal4">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal4')">&times;</span>
      <h3>Salud y Autocuidado</h3>
      <p>¿Cuándo es importante visitar al médico?</p>
      <button onclick="alert('Correcto: Regularmente y si algo preocupa.')">Siempre que haya dudas o cada tanto</button>
      <button onclick="alert('Incorrecto. Intentalo otra vez.')">Solo cuando me siento muy mal</button>
    </div>
  </div>  <div class="modal" id="modal5">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal5')">&times;</span>
      <h3>¿Qué es la Sexualidad?</h3>
      <p>¿La sexualidad incluye solo lo biológico?</p>
      <button onclick="alert('Correcto: Incluye aspectos psicológicos, culturales, sociales y emocionales.')">No, incluye mucho más</button>
      <button onclick="alert('Incorrecto. Intentalo otra vez.')">Sí, solo es lo biológico</button>
    </div>
  </div>  <script>
    function showModal(id) {
      document.getElementById(id).style.display = 'flex';
    }
    function closeModal(id) {
      document.getElementById(id).style.display = 'none';
    }
    window.onclick = function(event) {
      document.querySelectorAll('.modal').forEach(modal => {
        if (event.target === modal) modal.style.display = 'none';
      });
    }
  </script></body>
</html>
