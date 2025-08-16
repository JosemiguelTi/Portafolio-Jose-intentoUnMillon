<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portafolio - Jose Miguel Tosta</title>
  <style>
    /* === ESTILOS GLOBALES === */
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9fbfd;
      color: #333;
      line-height: 1.6;
      overflow-x: hidden;
    }

    h1, h2, h3 {
      color: #1E90FF;
      margin-bottom: 10px;
    }

    a {
      color: #1E90FF;
      text-decoration: none;
      transition: color 0.3s;
    }
    a:hover {
      color: #4682B4;
      text-decoration: underline;
    }

    /* === HEADER === */
    header {
      text-align: center;
      padding: 40px 20px;
      background: linear-gradient(to right, #1E90FF, #4682B4);
      color: white;
      animation: fadeIn 1.2s ease-in-out;
    }
    header img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid white;
      margin-bottom: 15px;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
    }
    header img:hover {
      transform: scale(1.08);
      box-shadow: 0 0 20px rgba(255,255,255,0.8);
    }
    header h1 {
      font-size: 2.5rem;
      animation: slideDown 1s ease-in-out;
    }

    /* === SECCIONES === */
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      opacity: 0;
      transform: translateY(30px);
      animation: fadeUp 1s ease forwards;
    }
    section:nth-of-type(1) { animation-delay: 0.3s; }
    section:nth-of-type(2) { animation-delay: 0.6s; }
    section:nth-of-type(3) { animation-delay: 0.9s; }
    section:nth-of-type(4) { animation-delay: 1.2s; }
    section:nth-of-type(5) { animation-delay: 1.5s; }
    section:nth-of-type(6) { animation-delay: 1.8s; }

    section h2 {
      border-left: 5px solid #1E90FF;
      padding-left: 10px;
    }

    /* === LISTAS === */
    ul {
      list-style: none;
      padding: 0;
    }
    ul li::before {
      content: "✔️ ";
      color: #1E90FF;
    }

    /* === FOOTER === */
    footer {
      text-align: center;
      padding: 20px;
      background: #1E90FF;
      color: white;
      margin-top: 40px;
      animation: fadeIn 1.5s ease-in-out;
    }

    /* === ANIMACIONES === */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideDown {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <!-- === HEADER === -->
  <header>
    <img src="Foto.jpg" alt="Foto de Jose Miguel Tosta">
    <h1>Jose Miguel Tosta Inestroza</h1>
    <p>📍 Francisco Morazán, Valle de Ángeles, Honduras</p>
    <p>
      📧 <a href="mailto:josemiguelti@hotmail.com">josemiguelti@hotmail.com</a> | 
      📱 +504 8766 6436
    </p>
    <p>
      🔗 <a href="https://linkedin.com/in/jose-tosta-46249a303">LinkedIn</a> | 
      💼 <a href="https://upwork.com/freelancers/~0194213b9389acb0cf">Upwork</a>
    </p>
  </header>

  <!-- === PERFIL === -->
  <section>
    <h2>Perfil Profesional</h2>
    <p>
      Profesional bilingüe (Inglés C1-C2 / Español nativo) con experiencia en asistencia virtual, asistencia legal, 
      atención al cliente y soporte técnico. Destaco por mi responsabilidad, manejo de herramientas digitales (CRM y EMR) 
      y excelentes relaciones interpersonales. Conocimientos en leyes de Personal Injury, Workers Compensation y VAWA Immigration.
    </p>
  </section>

  <!-- === EXPERIENCIA === -->
  <section>
    <h2>Experiencia Laboral</h2>
    <h3>Legal Assistant – Alonso & Alonso Law Firm / Upwork</h3>
    <p><em>Noviembre 2024 – Actualidad</em></p>
    <ul>
      <li>Elaboración y envío de solicitudes FOIA.</li>
      <li>Gestión de notas en Salesforce (Litify).</li>
      <li>Supervisión de tiempos de procesamiento en portales federales.</li>
    </ul>

    <h3>Virtual Assistant – Dr. Ali Najafi Neurosurgeon & Mendez and Sanchez Law Firm / IMPACTBPO</h3>
    <p><em>Noviembre 2023 – Noviembre 2024</em></p>
    <ul>
      <li>Coordinación de citas médicas (30–50 pacientes diarios).</li>
      <li>Gestión de expedientes médicos y comunicación con aseguradoras.</li>
    </ul>

    <h3>CSR Shared Agent – Market Force Information / ICCBPO</h3>
    <p><em>Septiembre 2021 – Noviembre 2023</em></p>
    <ul>
      <li>Atención de 80+ llamadas diarias.</li>
      <li>Clasificación y enrutamiento de casos en CRM.</li>
    </ul>
  </section>

  <!-- === EDUCACIÓN === -->
  <section>
    <h2>Formación Académica</h2>
    <ul>
      <li>Ingeniería en Informática (en curso) – Universidad Metropolitana de Honduras.</li>
      <li>Estudiante de Odontología – Universidad Nacional Autónoma de Honduras (UNAH).</li>
      <li>Bachiller en Ciencias y Letras con orientación en Inglés.</li>
    </ul>
  </section>

  <!-- === HABILIDADES === -->
  <section>
    <h2>Habilidades</h2>
    <ul>
      <li>Manejo de CRM y EMR: Salesforce, Filevine, CASEpeer, Google Workspace, Litify.</li>
      <li>Microsoft Office Suite (Word, Excel, PowerPoint, Outlook, OneDrive).</li>
      <li>Gestión de tiempo, multitasking y trabajo en equipo.</li>
      <li>Excelentes relaciones interpersonales y comunicación.</li>
    </ul>
  </section>

  <!-- === IDIOMAS === -->
  <section>
    <h2>Idiomas</h2>
    <ul>
      <li>Español: Nativo</li>
      <li>Inglés: Avanzado (C1-C2)</li>
    </ul>
  </section>

  <!-- === PROYECTOS === -->
  <section>
    <h2>Proyectos y Portafolio</h2>
    <p>
      Freelance en asistencia virtual y gestión administrativa en Upwork.  
      <a href="https://upwork.com/freelancers/~0194213b9389acb0cf">Ver mi perfil de Upwork</a>
    </p>
  </section>

  <!-- === FOOTER === -->
  <footer>
    <p>© 2025 Jose Miguel Tosta | Portafolio Digital</p>
  </footer>

</body>
</html>
