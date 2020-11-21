# FlorenceBenbaali_3_29102020
<h1 >Contexte</h1>
<p>Projet n°3 du parcours "Développeur web" dispensé par OpenClassRooms, il s’agit de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques et intégre des animations CSS, pour le compte d'une jeune startup (ohmyfood).</p>
<h1>Cahier des  charges</h1>
<ul>
<li>L’intégration doit se faire en HTML et CSS, sans framework, l’utilisation de SASS serait un plus.</li>
<li>Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.</li>
<li>Le site sera développé en utilisant l’approche mobile-first. Pour cette raison, seules des maquettes mobiles seront réalisées.</li>
<li>L’ensemble du site devra être responsive sur mobile, tablette et desktop.</li> 
<li>Les pages devront passer la validation W3C en HTML et CSS sans erreur.</li>
<li>Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome, Firefox et Safari.</li>
<li>Les couleurs de la charte sont primaire #9356DC, secondaire #FF79DA et tertiaire #99E2D0.</li>
 <li>La police du site est Shrikhand pour le logo et les titres, et Roboto pour le texte.</li>
</ul>
<h2>Livrables</h2>
<h3>Contenu des pages</h3>
<h4>Page d’accueil (x1)</h4>
<ul>
<li>Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.</li>
<li>Une courte présentation de l’entreprise.</li>
<li>Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.</li>
</ul>
<h4>Pages de menu (x4)</h4>
<ul>
<li>4 pages contenant chacune le menu d’un restaurant.</li>
</ul>
<h4>Footer</h4>
<ul>
<li>Le footer est identique sur toutes les pages.</li>
<li>Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.</li>
</ul>
<h4>Header</h4>
<ul>
<li>Le header est présent sur toutes les pages.</li>
<li>Sur la page d’accueil, il contient le logo du site.</li>
<li> Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.</li>
</ul>
<h3>Effets graphiques et animation</h3>
<p>Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.</p>
<h4>Boutons</h4>
<ul>
<li>Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.</li>
<li>À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.</li>
</ul>
<h4>Page d'accueil</h4>
<ul>
<li>Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.</li>
</ul>
<h4>Page de menu</h4>
<ul>
<li>À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.</li>
<li>Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.</li>
</ul>
<h1>Notes</h1>
<p>Utilisation de l’éditeur de texte Visual Studio Code avec les plugins Live Server, Prettier, et Autoprefixer. Utilisation du préprocesseur Sass.</p>
