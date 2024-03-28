<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Curriculum vitae</title>
    <meta charset="utf-8">
    <meta name="viewport"
            content="width=device-width, initial-scale=1, user-scalable=no">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,700;1,400&display=swap" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
  </head>
  <body>
    <style>
      *{
  margin: 0;
  box-sizing: border-box;
}

body{
  font-family: Roboto;
  font-weight: 300;
  font-size: .9rem;
  line-height: 1.5;
}

a{
  text-decoration: none;
  color: #365892;
}

a:hover{
  text-decoration: underline;
}

p{
  margin: 0 0 1rem;
}

h1{
  margin: 0 0 1rem;
  font-size: 2.5rem;
  margin-bottom: .5rem;
}

h2{
  margin: 0 0 1rem;
  letter-spacing: 1px;
  text-transform: uppercase;
}

.text-blue{
  color: #334d7e;
}

.text-darkblue{
  color: #002060;
}

.text-uppercase{
  text-transform: uppercase; 
}

.icon{
  margin-right: .5rem;
}

.cv-container{
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-areas: "left-column right-column right-column";
  width: 1200px;
  margin: 100px auto;
  box-shadow: 0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24);
}

.section{
  margin-bottom: 1.5rem;
}


.left-column{
  grid-area: left-column;
  padding: 50px;
  background-color: #185fd8;
  color: rgb(245, 241, 241);
}

.portait{
  border-radius: 50%;
  max-width: 150px;
  margin: auto;
  display: block;
  margin-bottom: 50px;
}

.skills{
  list-style-type: none;
  padding: 0;
  font-size: 1.1rem;
  letter-spacing: 1px;
  margin: 0 0 1rem;
}


.right-column{
  grid-area: right-column;
  display: grid;
  grid-template-rows: 250px 1fr;
  grid-template-areas: 
    "header"
    "content";
}

.header{
  grid-area: header;
  padding: 50px;
  background-color: #9fd0f0;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.infos{
  columns: 2;
  list-style-type: none;
  padding: 0;
}


.content{
  grid-area: content;
  padding: 50px;
}

.experience-list{
  list-style-type: circle;
}
    </style>
      <div class="cv-container">
        <div class="left-column">
          <img class="portait" src="430752312_1440148606612664_4076870187041770543_n.jpg" />
          <div class="section">
            <p>
              <i class="icon fas font-family text-darkblue"></i><h2>ANAS MATAICH</h2>
            </p>
          </div>
          <div class="section">
            <h2>OBJECTIVE</h2>
            <p>
              Ingénieur passionné et diplômé, j'ai 5 ans d'expérience à mon actif dans de grands groupes. Je recherche actuellement un nouvel emploi pour commencer dès le mois de juin
            </p>
            <p>
              De nature débrouillard et indépendant dans mon travail, j’aime apprendre de nouvelles technologies, passer du temps à résoudre des problèmes et réaliser du code de qualité. Mes valeurs de travail : clean code, flexibilité, performance et sérieux.
            </p>
          </div>
          <div class="section">
            <h2>COMPÉTENCES (SKILLS)</h2>
            <ul class="skills">
              <li><i class="icon fas fa-check-circle text-darkblue"></i> <strong>Angular &#124; Typescript</strong></li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> <strong>Bootstrap</strong></li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> <strong>HTML5 &#124; CSS3 &#124;</strong></li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> <strong>Javascript &#124; python &#124; C</strong></li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> <strong>npm &#124; Webpack</strong></li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> PHP</li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> Zend Framework</li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> MySQL</li>
              <li><i class="icon fas fa-check-circle text-darkblue"></i> Git &#124; Github</li>
            </ul>
          </div>
          
          <div class="section">
            <h2>Langues</h2>
            <p>
              Français, Arabic ,Amazigh
              <br>
              Anglais, compétence professionnelle
            </p>
          </div>
          <div>
            <h2> HONORS & AWARDS</h2>
            <p></p>
          </div>
          <div>
            <h2>CERTIFICATIONS</h2>
             <P>Certificat d'ingénieur en 2026</P>
            <p>Certificat de baccalauréat 2021</p>
           
          </div>
          <div class="section">
            <h2>Centres d'intérêt</h2>
            <p>
              Jeux vidéo, jouer et développer
              <br>
              Musique, écoute et composition
              <br>
              Art en général
              <br>
              Sport
              <br>
              Informatique en général
            </p>
          </div>
        </div>
        <div class="right-column">
          <div class="header">
            <h1>STEVEN <span class="text-blue text-uppercase">TERRY</span></h1>
            <p>GRAPHIC DESIGNER</p>
            <ul class="infos">
              <li><i class="icon fas fa-at text-blue"></i> <a href="mailto:anas.mataich6@gmail.com">anas.mataich6@gmail.com</a></li>
              <li><a href="tel:+212615443278"><i class="fas fa-phone"></i>Téléphone: +212 618 44 32 78</a></li>
              <li><i class="icon fas fa-map-marker-alt text-blue"></i> Ville : Maroc Nador</li>
              <li><i class="icon fas fa-check-circle text-blue"></i>Né le : 4 avril 2001</li>

            </ul>
          </div>
          <div class="content">
            <div class="section">
              <h2>Expériences <br><span class="text-blue">professionelles</span></h2>
              <p>
                <strong>2015 <i class="fas fa-long-arrow-alt-right"></i> 2021</strong>
                <br>
                Fullstack Developer à temps plein chez <em>Webadev SPRL</em>
              </p>
              
              <ul class="experience-list">
                <li>Intégration de templates Photoshop, Illustrator, Sketch, Figma</li>
                <li>Animations CSS / JS</li>
                <li>Responsive design</li>
                <li>UI / UX Design</li>
                <li>Projets sous npm et Webpack</li>
                <li>Collaboration avec d’autres studios graphique (Studio Debie, SOL,…)</li>
                <li>Optimisation des performances</li>
                <li>Développement de templates et de modules réutilisables</li>
                <li>Projets en équipe, utilisation quotidienne de SVN, Git et Github</li>
              </ul>
            </div>
            <div class="section">
              <p>
                <strong>2021</strong>
                <br>
                Freelance en activité
              </p>
              <ul class="experience-list">
                <li>Freelance Front-end Developer</li>
                <li>Unity Developer / Sound Designer</li>
              </ul>
            </div>
            <div class="section">
              <h2>Études <br><span class="text-blue">& formations</span></h2>
              <p>
                <strong>2018 <i class="fas fa-long-arrow-alt-right"></i> 2021</strong>
                <br>
                <em>Bachelier en Informatique de Gestion</em>.
              </p>
              <p>
                <strong>2018</strong>
                <br>
                <em>STE-Formations Informatiques</em>, Formation qualifiante de Web 
              </p>
           
              
            </div>
            <div class="section">
              <h2>Activités et centres d'intérêt
              </h2>
              <ul>
                <p>Coordination entre les équipes techniques et les interfaces externes pour assurer l'amélioration de la performance des plans d'actions.
                </p>
                <p>Veille sur la mise à jour des processus de l'usine
                </p>
                <p>Pilotage d'un projet de validations qualité sur lignes de conditionnement impliquant de nombreux acteurs
                </p>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
                </p>
              </ul>
             
            </div>
          </div>
        </div>
      </div>
  </body>
</html>
