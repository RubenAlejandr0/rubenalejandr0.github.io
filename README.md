<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rubén Alejandro | Desarrollador Android</title>

    <style>

        body{
            margin:0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e293b);
            color:white;
        }

        .container{
            max-width:900px;
            margin:auto;
            padding:40px 20px;
            text-align:center;
        }

        .profile-img{
    width:180px;
    height:180px;
    border-radius:50%;

    object-fit:cover;      /* CLAVE: rellena el círculo */
    object-position:center; /* centra la cara */

    display:block;
    margin:auto;

    border:4px solid #38bdf8;
    box-shadow:0px 10px 25px rgba(0,0,0,0.4);
}


        h1{
            margin-top:20px;
            font-size:2.5rem;
        }

        .subtitle{
            color:#94a3b8;
            font-size:1.2rem;
        }

        .card{
            margin-top:40px;
            background:#111827;
            padding:30px;
            border-radius:18px;
            box-shadow:0px 10px 30px rgba(0,0,0,0.3);
        }

        .button{
            display:inline-block;
            margin-top:25px;
            padding:14px 28px;
            background:#38bdf8;
            color:#0f172a;
            text-decoration:none;
            border-radius:10px;
            font-weight:bold;
            transition:0.3s;
        }

        .button:hover{
            transform:scale(1.05);
            background:#0ea5e9;
        }

        footer{
            margin-top:40px;
            color:#64748b;
            font-size:0.9rem;
        }

    </style>
</head>

<body>

    <div class="container">

        <!-- FOTO -->
        <img src="foto.png" class="profile-img">

        <!-- NOMBRE -->
        <h1>Rubén Alejandro</h1>
        <p class="subtitle">Desarrollador Android | Creador de aplicaciones útiles</p>


        <!-- SOBRE MI -->
        <div class="card">

            <h2>¿A qué me dedico?</h2>

            <p>
                Soy desarrollador de aplicaciones Android enfocado en crear soluciones reales,
                funcionales y fáciles de usar. Me apasiona la tecnología, el aprendizaje continuo
                y transformar ideas en aplicaciones que aporten valor a las personas y empresas.
            </p>

            <p>
                Actualmente soy creador de <strong>Rifa Virtual</strong>, una aplicación publicada en Google Play,
                diseñada para gestionar sorteos de manera simple, moderna y confiable.
            </p>

            <!-- BOTON -->
            <a href="https://play.google.com/store/apps/details?id=com.ruben.rifavirtual"
               class="button"
               target="_blank">
               Ver mi aplicación 🚀
            </a>

        </div>

        <footer>
            © 2026 Rubén Alejandro — Construyendo el futuro una app a la vez.
        </footer>

    </div>

</body>
</html>
