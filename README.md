<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Centro de Capacitaciones Nurselife</title>
<style>
:root{
--primary:#6a00ff;
--secondary:#00e5a8;
--accent:#ff2d95;
--dark:#0b0b1f;
--light:#f4f6ff;
}
*{box-sizing:border-box}
body{
margin:0;
font-family:'Segoe UI',Arial,sans-serif;
background:linear-gradient(135deg,#0b0b1f,#1b0f3a);
color:#fff;
}
header{
background:linear-gradient(135deg,var(--primary),var(--accent));
padding:70px 20px;
text-align:center;
position:relative;
overflow:hidden;
}
header::after{
content:"";
position:absolute;
width:600px;height:600px;
background:radial-gradient(circle,var(--secondary),transparent 70%);
top:-300px;right:-300px;
opacity:.4;
}
header img{max-width:190px;margin-bottom:20px}
header h1{font-size:2.8em;margin:0}
header p{font-size:1.2em;opacity:.95}
section{
max-width:1200px;
margin:auto;
padding:70px 20px;
}
h2{
font-size:2.3em;
margin-bottom:30px;
text-align:center;
background:linear-gradient(90deg,var(--secondary),var(--accent));
-webkit-background-clip:text;
-webkit-text-fill-color:transparent;
}
.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:30px;
}
.card{
background:rgba(255,255,255,0.08);
border-radius:18px;
overflow:hidden;
backdrop-filter:blur(10px);
box-shadow:0 20px 40px rgba(0,0,0,.35);
transition:.4s;
}
.card:hover{transform:translateY(-15px) scale(1.02)}
.card img{width:100%;height:200px;object-fit:cover}
.card h3{margin:15px;font-size:1.3em}
.card p{margin:0 15px 15px;line-height:1.5}
.btn{
display:block;
margin:15px;
padding:14px;
background:linear-gradient(90deg,var(--secondary),var(--accent));
border-radius:30px;
text-align:center;
color:#000;
font-weight:bold;
text-decoration:none;
transition:.3s;
}
.btn:hover{filter:brightness(1.1)}
.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}
.gallery img{
width:100%;
border-radius:18px;
box-shadow:0 15px 30px rgba(0,0,0,.4);
transition:.4s;
}
.gallery img:hover{transform:scale(1.08)}
.contact{
background:rgba(255,255,255,.1);
border-radius:20px;
padding:40px;
max-width:600px;
margin:auto;
}
input,textarea{
width:100%;
padding:14px;
border-radius:12px;
border:none;
margin-bottom:15px;
font-size:1em;
}
footer{
background:#050510;
padding:25px;
text-align:center;
opacity:.8;
}
.whatsapp-float{
position:fixed;
bottom:25px;
right:25px;
background:linear-gradient(135deg,#25d366,#00ff99);
padding:16px 20px;
border-radius:50px;
color:#000;
font-weight:bold;
text-decoration:none;
box-shadow:0 15px 30px rgba(0,0,0,.4);
}
</style>
</head>
<body>
<script>
function abrirWhatsApp(curso){
  const mensajes={
    enfermeria:'Hola, deseo información del curso Auxiliar en Enfermería (10 meses).',
    farmacia:'Hola, deseo información del curso Auxiliar en Farmacia (10 meses).',
    parvulo:'Hola, deseo información del curso Auxiliar en Párvulo (10 meses).',
    veterinaria:'Hola, deseo información del curso Auxiliar en Veterinaria (8 meses).',
    belleza:'Hola, deseo información del curso Belleza Integral (8 meses).',
    contable:'Hola, deseo información del curso Auxiliar Contable (3 meses).',
    prehospitalaria:'Hola, deseo información del curso Atención Prehospitalaria (8 meses).'
  };
  const url='https://wa.me/593969580321?text='+encodeURIComponent(mensajes[curso]);
  window.open(url,'_blank');
}
</script>
<header>
<img src="logo-nurselife.png" alt="Nurselife" />
<h1>Centro de Capacitaciones Nurselife</h1>
<p>Formación presencial • Certificación avalada • Alta empleabilidad</p>
<div style="margin-top:30px">
<a class="btn" href="#cursos">Ver Cursos</a>
</div>
<div class="carousel" style="margin-top:40px;display:flex;gap:20px;overflow-x:auto;scroll-snap-type:x mandatory;padding-bottom:20px">
<img src="https://images.unsplash.com/photo-1584515933487-779824d29309" style="height:220px;border-radius:20px;scroll-snap-align:center">
<img src="https://images.unsplash.com/photo-1517849845537-4d257902454a" style="height:220px;border-radius:20px;scroll-snap-align:center">
<img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9" style="height:220px;border-radius:20px;scroll-snap-align:center">
<img src="https://images.unsplash.com/photo-1600959907703-125ba1374a12" style="height:220px;border-radius:20px;scroll-snap-align:center">
</div>
</header>
<section>
<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px;text-align:center;">
<div><h2 style="font-size:3em">+3.500</h2><p>Estudiantes formados</p></div>
<div><h2 style="font-size:3em">98%</h2><p>Inserción laboral</p></div>
<div><h2 style="font-size:3em">10+</h2><p>Años de experiencia</p></div>
<div><h2 style="font-size:3em">100%</h2><p>Modalidad presencial</p></div>
</div>
</section>
<section id="cursos">
<h2>Nuestros Cursos</h2>
<p style="text-align:center;max-width:800px;margin:0 auto 40px;opacity:.9">Programas prácticos de alta demanda laboral, con certificación universitaria y aval del Ministerio del Trabajo.</p>
<div class="services">
<div class="card"><img src="https://images.unsplash.com/photo-1584515933487-779824d29309"><h3>Auxiliar en Enfermería</h3><p>⏱ 10 meses<br>Alta demanda laboral • Prácticas reales</p><a class="btn" onclick="abrirWhatsApp('enfermeria')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1579154204601-01588f351e67"><h3>Auxiliar en Farmacia</h3><p>⏱ 10 meses<br>Farmacia clínica y comercial</p><a class="btn" onclick="abrirWhatsApp('farmacia')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1588075592446-6b3b4b1f1c7d"><h3>Auxiliar en Párvulo</h3><p>⏱ 10 meses<br>Educación y estimulación infantil</p><a class="btn" onclick="abrirWhatsApp('parvulo')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1517849845537-4d257902454a"><h3>Auxiliar en Veterinaria</h3><p>⏱ 8 meses<br>Clínica y cuidado animal</p><a class="btn" onclick="abrirWhatsApp('veterinaria')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9"><h3>Belleza Integral</h3><p>⏱ 8 meses<br>Estética profesional y salón</p><a class="btn" onclick="abrirWhatsApp('belleza')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40"><h3>Auxiliar Contable</h3><p>⏱ 3 meses<br>Contabilidad y oficina</p><a class="btn" onclick="abrirWhatsApp('contable')">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1600959907703-125ba1374a12"><h3>Atención Prehospitalaria</h3><p>⏱ 8 meses<br>Emergencias médicas</p><a class="btn" onclick="abrirWhatsApp('prehospitalaria')">Inscribirme</a></div>
</div>
<div class="card"><img src="https://images.unsplash.com/photo-1579154204601-01588f351e67"><h3>Auxiliar en Farmacia</h3><p>⏱ 10 meses<br>Atención y dispensación farmacéutica.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1588075592446-6b3b4b1f1c7d"><h3>Auxiliar en Párvulo</h3><p>⏱ 10 meses<br>Educación y cuidado infantil.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1517849845537-4d257902454a"><h3>Auxiliar en Veterinaria</h3><p>⏱ 8 meses<br>Cuidado y asistencia animal.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9"><h3>Belleza Integral</h3><p>⏱ 8 meses<br>Estética y salón profesional.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40"><h3>Auxiliar Contable</h3><p>⏱ 3 meses<br>Gestión contable y administrativa.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
<div class="card"><img src="https://images.unsplash.com/photo-1600959907703-125ba1374a12"><h3>Atención Prehospitalaria</h3><p>⏱ 8 meses<br>Emergencias médicas.</p><a class="btn" href="https://wa.me/593969580321">Inscribirme</a></div>
</div>
</section>
<section>
<h2>Galería Real Nurselife</h2>
<p style="text-align:center;max-width:800px;margin:0 auto 40px;opacity:.9">Nuestros estudiantes se forman con prácticas reales desde el primer mes.</p>
<div class="gallery">
<img src="galeria-enfermeria-1.jpg">
<img src="galeria-enfermeria-2.jpg">
<img src="galeria-nurselife-evento.jpg">
<img src="galeria-nurselife-aula.jpg">
</div>
</section>
<section>
<h2>Contáctanos</h2>
<div class="contact">
<form onsubmit="window.open('https://wa.me/593969580321','_blank');return false;">
<input placeholder="Nombre completo" required>
<input type="email" placeholder="Correo" required>
<textarea placeholder="Curso de interés" required></textarea>
<button class="btn" type="submit">Enviar por WhatsApp</button>
</form>
</div>
</section>
<a class="whatsapp-float" href="https://wa.me/593969580321">WhatsApp</a>
<section>
<h2>Certificaciones</h2>
<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:30px;text-align:center">
<div style="background:rgba(255,255,255,.08);padding:30px;border-radius:20px;max-width:260px">🎓<h3>Certificación Universitaria</h3><p>Respaldo académico de alto nivel.</p></div>
<div style="background:rgba(255,255,255,.08);padding:30px;border-radius:20px;max-width:260px">🏛️<h3>Ministerio del Trabajo</h3><p>Aval para inserción laboral.</p></div>
<div style="background:rgba(255,255,255,.08);padding:30px;border-radius:20px;max-width:260px">💼<h3>Alta Empleabilidad</h3><p>Cursos diseñados para el trabajo real.</p></div>
</div>
</section>
<section>
<h2>Testimonios</h2>
<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:30px">
<div class="card"><p>"Gracias a Nurselife hoy trabajo en el área de la salud."</p><strong>- Ex alumna Enfermería</strong></div>
<div class="card"><p>"Las prácticas reales marcaron la diferencia."</p><strong>- Estudiante Prehospitalaria</strong></div>
<div class="card"><p>"Recomiendo totalmente el instituto."</p><strong>- Auxiliar Veterinaria</strong></div>
</div>
</section>
<section>
<h2>Formas de Pago</h2>
<div style="display:flex;flex-wrap:wrap;justify-content:center;gap:30px;text-align:center">
<div class="card"><h3>Transferencia Bancaria</h3><p>Pago seguro y directo.</p></div>
<div class="card"><h3>Pago por WhatsApp</h3><p>Asistencia personalizada inmediata.</p></div>
</div>
</section>
<section>
<h2 style="text-align:center">¿Lista para cambiar tu futuro?</h2>
<p style="text-align:center;max-width:700px;margin:auto">Inscríbete hoy en uno de los institutos de capacitación más completos y modernos del país.</p>
<div style="text-align:center;margin-top:30px">
<a class="btn" onclick="window.open('https://wa.me/593969580321','_blank')">Hablar con un asesor ahora</a>
</div>
</section>
<footer>© 2026 Centro de Capacitaciones Nurselife</footer>
</body>
</html>
