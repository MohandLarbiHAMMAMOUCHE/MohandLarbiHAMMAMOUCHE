<!DOCTYPE html>

<html lang="fr">

<head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Mohend Hammamouche | Étudiant en Informatique</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: Arial, Helvetica, sans-serif;
        background: #0d1117;
        color: #c9d1d9;
        line-height: 1.7;
    }

    .container {
        max-width: 1100px;
        margin: auto;
        padding: 40px 25px;
    }

    h1 {
        color: white;
        font-size: 36px;
        margin-bottom: 15px;
    }

    h2 {
        color: white;
        margin-top: 45px;
        margin-bottom: 20px;
        font-size: 25px;
    }

    h3 {
        color: white;
        margin-bottom: 15px;
    }

    a {
        color: #58a6ff;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    .intro {
        font-size: 17px;
        max-width: 800px;
        margin-bottom: 12px;
    }

    .socials {
        margin: 15px 0 25px;
    }

    .socials a {
        display: inline-block;
        margin-right: 15px;
        padding: 8px 15px;
        border: 1px solid #30363d;
        border-radius: 8px;
        transition: 0.3s;
    }

    .socials a:hover {
        background: #161b22;
        text-decoration: none;
        transform: translateY(-2px);
    }

    .about {
        display: grid;
        grid-template-columns: 1fr 300px;
        gap: 40px;
        align-items: center;
    }

    .profile-image {
        width: 100%;
        border-radius: 15px;
    }

    ul {
        list-style: none;
    }

    li {
        margin: 12px 0;
    }

    .skills {
        display: flex;
        flex-wrap: wrap;
        gap: 12px;
    }

    .skill {
        background: #161b22;
        border: 1px solid #30363d;
        padding: 10px 16px;
        border-radius: 8px;
        color: #fff;
        transition: 0.3s;
    }

    .skill:hover {
        border-color: #58a6ff;
        transform: translateY(-3px);
    }

    .projects {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
    }

    .project {
        background: #161b22;
        border: 1px solid #30363d;
        padding: 22px;
        border-radius: 12px;
        transition: 0.3s;
    }

    .project:hover {
        transform: translateY(-5px);
        border-color: #58a6ff;
    }

    .project h3 {
        margin-bottom: 10px;
    }

    .project p {
        color: #8b949e;
        margin-bottom: 15px;
    }

    .buttons a {
        display: inline-block;
        padding: 8px 13px;
        border-radius: 6px;
        background: #238636;
        color: white;
        margin-right: 5px;
        font-size: 14px;
    }

    .buttons a.github {
        background: #21262d;
    }

    .stats {
        display: flex;
        gap: 20px;
        flex-wrap: wrap;
    }

    .stat {
        background: #161b22;
        border: 1px solid #30363d;
        padding: 20px;
        border-radius: 10px;
        flex: 1;
        min-width: 200px;
    }

    footer {
        text-align: center;
        margin-top: 60px;
        padding-top: 25px;
        border-top: 1px solid #30363d;
        color: #8b949e;
    }

    @media (max-width: 700px) {
        .about {
            grid-template-columns: 1fr;
        }

        h1 {
            font-size: 28px;
        }
    }
</style>

</head>

<body>

<div class="container">

<!-- PRÉSENTATION -->
<header>

    <h1>Bonjour 👋, je suis Mohend Hammamouche !</h1>

    <div class="socials">

        <a href="https://github.com/" target="_blank">
            GitHub
        </a>

        <a href="https://www.linkedin.com/" target="_blank">
            LinkedIn
        </a>

    </div>

    <p class="intro">
        🎓 Je suis actuellement étudiant en deuxième année de licence
        Informatique à l'Université Abderrahmane Mira de Béjaïa.
    </p>

    <p class="intro">
        💻 Je m'intéresse à la programmation, au développement web,
        aux systèmes informatiques et à la création de projets pratiques.
    </p>

    <p class="intro">
        🔐 Mon principal objectif professionnel est de développer
        progressivement mes compétences dans le domaine de la
        <strong>cybersécurité</strong>.
    </p>

</header>


<!-- À PROPOS DE MOI -->
<section>

    <h2>🧐 À propos de moi</h2>

    <div class="about">

        <div>

            <ul>

                <li>
                    🎓 Étudiant en deuxième année de licence Informatique
                </li>

                <li>
                    💻 Intéressé par la programmation et les systèmes informatiques
                </li>

                <li>
                    🔐 Je souhaite me spécialiser progressivement en cybersécurité
                </li>

                <li>
                    🐍 Je développe des projets avec Python
                </li>

                <li>
                    ♟️ Je travaille actuellement sur un projet de jeu d'échecs
                </li>

                <li>
                    🌐 J'apprends le développement web
                </li>

                <li>
                    🧊 Je découvre la modélisation 3D avec Blender
                </li>

                <li>
                    🐧 Je m'intéresse à Linux et aux systèmes d'exploitation
                </li>

                <li>
                    📚 J'apprends principalement à travers des projets personnels
                </li>

            </ul>

        </div>

        <div>

            <!-- Remplace cette image par ta photo -->
            <img
                class="profile-image"
                src="https://via.placeholder.com/300x300"
                alt="Photo de profil">

        </div>

    </div>

</section>


<!-- LANGAGES ET OUTILS -->
<section>

    <h2>🔨 Langages et outils</h2>

    <div class="skills">

        <div class="skill">🐍 Python</div>

        <div class="skill">⚙️ C</div>

        <div class="skill">💻 C++</div>

        <div class="skill">🌐 HTML</div>

        <div class="skill">🎨 CSS</div>

        <div class="skill">⚡ JavaScript</div>

        <div class="skill">🗄️ SQL</div>

        <div class="skill">🐘 PHP</div>

        <div class="skill">🐧 Linux</div>

        <div class="skill">🔧 Git</div>

        <div class="skill">🐙 GitHub</div>

        <div class="skill">🎮 Pygame</div>

        <div class="skill">🧊 Blender</div>

        <div class="skill">🖌️ Illustrator</div>

        <div class="skill">💻 Visual Studio Code</div>

    </div>

</section>


<!-- STATISTIQUES -->
<section>

    <h2>📊 Mon parcours</h2>

    <div class="stats">

        <div class="stat">

            <h3>🎓 Formation</h3>

            <p>
                Licence Informatique — deuxième année
            </p>

        </div>


        <div class="stat">

            <h3>💻 Projets</h3>

            <p>
                Projets personnels en Python, C/C++, Web et 3D.
            </p>

        </div>


        <div class="stat">

            <h3>🔐 Objectif</h3>

            <p>
                Développer mes compétences et poursuivre
                mes études dans le domaine de la cybersécurité.
            </p>

        </div>

    </div>

</section>


<!-- PROJETS -->
<section>

    <h2>🛠️ Mes projets</h2>

    <div class="projects">


        <!-- CHESS -->
        <div class="project">

            <h3>♟️ Jeu d'échecs</h3>

            <p>
                Développement d'un jeu d'échecs avec Python
                et Pygame. Le projet me permet de travailler
                la logique de programmation, les interfaces
                graphiques et les règles du jeu.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    GitHub
                </a>

            </div>

        </div>


        <!-- WEB -->
        <div class="project">

            <h3>🌐 Projets Web</h3>

            <p>
                Création de différents projets web avec
                HTML, CSS et JavaScript afin de développer
                mes compétences en développement frontend.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    GitHub
                </a>

                <a href="#">
                    Démo
                </a>

            </div>

        </div>


        <!-- PYTHON -->
        <div class="project">

            <h3>🐍 Projets Python</h3>

            <p>
                Développement de petites applications et
                projets Python pour améliorer mes compétences
                en programmation et en résolution de problèmes.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    GitHub
                </a>

            </div>

        </div>


        <!-- C / C++ -->
        <div class="project">

            <h3>⚙️ Projets C / C++</h3>

            <p>
                Réalisation de projets universitaires autour
                des algorithmes, structures de données,
                programmation et gestion des données.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    GitHub
                </a>

            </div>

        </div>


        <!-- BLENDER -->
        <div class="project">

            <h3>🧊 Blender & 3D</h3>

            <p>
                Découverte de la modélisation 3D et création
                de scènes et environnements avec Blender.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    Projets
                </a>

            </div>

        </div>


        <!-- CYBERSECURITE -->
        <div class="project">

            <h3>🔐 Cybersécurité</h3>

            <p>
                Apprentissage progressif des systèmes Linux,
                des réseaux, des systèmes d'exploitation et
                des fondamentaux de la cybersécurité.
            </p>

            <div class="buttons">

                <a href="#" class="github">
                    GitHub
                </a>

            </div>

        </div>

    </div>

</section>


<!-- CENTRES D'INTÉRÊT -->
<section>

    <h2>❤️ Centres d'intérêt</h2>

    <div class="skills">

        <div class="skill">♟️ Échecs</div>

        <div class="skill">🎨 Dessin</div>

        <div class="skill">🖌️ Peinture</div>

        <div class="skill">🧊 3D & Blender</div>

        <div class="skill">💻 Matériel informatique</div>

        <div class="skill">🏊 Natation</div>

        <div class="skill">🥾 Randonnée</div>

    </div>

</section>


<!-- PIED DE PAGE -->
<footer>

    <p>
        © 2026 Mohend Hammamouche
    </p>

    <p>
        Étudiant en Informatique — Béjaïa, Algérie
    </p>

    <p>
        Apprendre • Créer • Progresser 🚀
    </p>

</footer>

</div>

</body>

</html>
