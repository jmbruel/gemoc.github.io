---
layout: default

---

<!-- Page Heading/Breadcrumbs -->
<div class="row">
    <div class="col-lg-12">
        <h1 class="page-header">CNRS GDR GPL Action Spécifique GEMOC
            <small>2011</small>
        </h1>
        <ol class="breadcrumb">
            <li><a href="{{ site.baseurl }}/index.html">Home</a>
            </li>
            <li><a href="{{ site.baseurl }}/projects.html">Projects</a></li>
            <li class="active">AS2011</li>
        </ol>
    </div>
</div>
<!-- /.row -->

<!-- Content Row -->
<div class="row">
    <div class="col-lg-12">

				<div class="post-meta clearfix">


            <span class="updated">
            	<span class="value-title" title="2012-10-12T21:29" />
            </span>

					</div>

				<div class="entry-content clearfix">


                        <h2>Ingénierie du logiciel pour les systèmes hétérogènes
<em>bilan, verrous et défis</em></h2>
<p style="text-align: center;">
  <img src="{{ site.baseurl }}{% link pub/as/logo-as2011.png%}" alt="IRISA et I3S (UMR CNRS)" width="210" align="middle" />
  <a href="http://gdr-gpl.cnrs.fr/">
    <img src="{{ site.baseurl }}{% link logo/logo-gdr-gpl.jpg%}" alt="Avec le soutien du GDR GPL" width="200" align="middle" />
  </a>
</p>
<hr />
<h2>L&#8217;Action Spécifique CNRS GEMOC s&#8217;est terminée en décembre 2011. <BR>Voir <a href="resources/gemoc_as2011-rapportgdrgpl.pdf">le rapport d&#8217;activité</a>.</h2>
<hr />
<h2>News</h2>
<ul>
<li>juin 2012 : <a href="resources/20120620_gdrgpl12.pdf">présentation de l&#8217;AS</a> aux journées nationales du GDR GPL</li>
<li>janvier 2012 : <a href="resources/gemoc_as2011-rapportgdrgpl.pdf">le rapport d&#8217;activité de l&#8217;AS est en ligne</a></li>
<li>décembre 2011 : <a href="#program">les présentations de la journée nationale de travail sont en ligne</a></li>
<li>25 novembre 2011 : <a href="#workshop">journée nationale de travail à Paris</a></li>
<li>23 et 24 novembre 2011 : journées de travail à Paris</li>
<li>14 novembre 2011 : journée de travail à Sophia Antipolis</li>
<li>14 septembre 2011 : journée de travail en visio-conférence</li>
<li>28 juin 2011 : journée de travail en visio-conférence</li>
<li>15 mai 2011 : page web en ligne !</li>
<li>13 mai 2011 : l&#8217;AS est acceptée par le GDR GPL</li>
</ul>
<h2>Participants</h2>
<p>Deux équipes sont principalement impliquées dans cette action spécifique :</p>
<ul>
<li><a href="http://www.irisa.fr/triskell/">Equipe TRISKELL</a> (<a href="http://www.irisa.fr">IRISA</a>) : <a href="http://www.irisa.fr/triskell/perso_pro/bbaudry/" target="_blank">Benoit Baudry</a>, et <a href="http://www.irisa.fr/triskell/perso_pro/combemale/" target="_blank">Benoit Combemale</a>.</li>
<li><a href="http://www-sop.inria.fr/aoste/">Equipe AOSTE</a> (<a href="http://www.i3s.unice.fr">I3S</a>) : <a href="http://www-sop.inria.fr/members/Julien.Deantoni/" target="_blank">Julien DeAntoni</a>, et <a href="http://www-sop.inria.fr/members/Frederic.Mallet/" target="_blank">Frédéric Mallet</a>.</li>
</ul>
<p>L’ensemble des acteurs français sont également convié à participer à <a href="#workshop">la journée nationale de travail à Paris</a>.</p>
<h2>Contexte</h2>
<p>La complexité grandissante des systèmes embarqués actuels nécessite une communication forte entre les différents acteurs métiers du développement. Chacun de ces acteurs utilisent des langages et des formalismes différents, issu de leur domaine d’activité et avec leur propre sémantique. Ces différents langages reposent sur des modèles  formels différents qui permettent de répondre d’une manière spécifique à certaines contraintes comme des contraintes de sûreté, d’accessibilité, de respect d’exigences temporelles, de sécurité, etc. Ces modèles formels reposent sur des modèles de calcul décrivant précisément la façon dont les différents processus s’exécutent, communiquent et se synchronisent. Ils contribuent à donner la sémantique d&#8217;exécution et de synchronisation de l&#8217;entité sur laquelle ils sont appliqués. Puisque un même système embarqué est conçu à partir de plusieurs langages ayant chacun leur propre modèle de calcul, il est nécessaire de savoir les composer de manière fiable. Un des freins majeur à cette composition est du au fait que le modèle de calcul est fondu dans le modèle fonctionnel métier. Ceci est notamment dû à l’absence d’un langage spécifique pour la description explicite du modèle de calcul et ce malgré le nombre abondant, en France et à l’étranger, de travaux théoriques sur la composition de modèles de calcul.</p>
<p>L’ingénierie dirigée par les modèles fournis des techniques et des outils pour manipuler les modèles directement, raisonner sur leur composition, les transformer et générer le code d’implantation. Ceci permet en particulier d’avoir un flot intégré où modèles d’analyse et de conception sont traités dans le même espace technologique. Appliquée à la conception et l’analyse de systèmes hétérogènes à logiciel prépondérant, il est fondamental de dissocier les modèles fonctionnels (et leurs sémantiques associées) de ceux qui caractérisent la sémantique calcul, de communication et de synchronisation. Chacun de ces modèles doit pouvoir être manipulé séparément avant assemblage/tissage, vérification et déploiement par génération ou interprétation.</p>
<h2>Objectif de l’Action Spécifique</h2>
<p>L&#8217;objectif de cette action spécifique est d’avoir une réflexion sur les efforts actuellement menés en France pour la définition de systèmes logiciels hétérogènes au regard de la compétition internationale. En particulier, nous proposons de faire un bilan sur l&#8217;état de l&#8217;art et de la pratique ainsi que sur les verrous restant à lever en terme de techniques et d’outils pour la composition formelle de modèles métiers et de leurs modèles de calcul associés.</p>
<p>Il s’agit donc d’identifier les acteurs et les actions en cours, d’établir un bilan sur les résultats obtenus et de répertorier les verrous technologiques et scientifiques qui doivent être levés. Même s’il est très clair que la modélisation et la programmation de systèmes hétérogènes à logiciel prépondérant relèvent directement du GDR GPL, nous anticipons que le groupe de travail puisse aller au delà et être constitué d’équipes impliquées dans plusieurs GDRs. C&#8217;est justement l’objectif de l’action de rédiger un rapport qui identifie les acteurs, les verrous et dresse un bilan des actions menées jusqu’à lors. En fonction de cela, il s’agit d’<strong>identifier précisément le périmètre d’un groupe de travail entre les acteurs français</strong> et de déterminer s’il s’agit d’une action spécifique ou transverse à plusieurs GDRs. Nous souhaitons également diffuser ces résultats sous la forme d’un <strong>article de synthèse qui présente une cartographie des actions internationales en cours sur ce thème et les futurs challenges</strong>.</p>
<p>La mission du groupe de travail constitué est d’encourager les échanges entre équipes et notamment de :</p>
<ul>
<li>coordonner les efforts nationaux ;</li>
<li>organiser des manifestations scientifiques ;</li>
<li>encourager l’intégration d’outils pour constituer une plate-forme logicielle open-source ;</li>
<li>coordonner les réponses à des appels à projets nationaux ou internationaux.</li>
</ul>
<h2>Atelier de travail à Paris le 25 novembre 2011</h2>
<h3>Objectifs</h3>
<p>La complexité des systèmes logiciels modernes entraine très souvent une hétérogénéité dans le cycle de développement qui requiert une agilité et une sûreté de plus en plus accrue des techniques de modélisation et de programmation. En particulier, nous proposons au cours de cette journée de travail d&#8217;explorer les initiatives visant à faire coopérer différents points de vue hétérogènes : de la conception, &#8230; à la simulation, &#8230; à l&#8217;exécution.</p>
<p>Parmi les sujets de discussions :</p>
<ul>
<li>Modélisation hétérogène : ingénierie des langages, composition de modèle, variabilité</li>
<li>Simulation hétérogène : modèle de calcul, test et vérification, &#8230;</li>
<li>Plate-forme d&#8217;exécution hétérogène : création et configuration dynamique de plate-forme d&#8217;exécution, models@runtime, processus d&#8217;entreprise</li>
<li>Domaine d&#8217;application : système de systèmes, système réactif, système embarqué, système autonome, &#8230;</li>
</ul>
<p>Cette journée de travail a pour objectif de rassembler les acteurs majeurs de l&#8217;ingénierie du logiciel en France afin de faire émerger un groupe de travail sur le thème des systèmes hétérogènes.</p>
<p>Cette journée a en particulier l&#8217;objectif d&#8217;identifier le périmètre d&#8217;un groupe de travail ainsi que ses axes scientifiques structurant. Concrètement, il s&#8217;agit d&#8217;établir un document à destination du GDR GPL faisant des propositions en vue de structurer l&#8217;activité de recherche et de développement sur le thème de l&#8217;ingénierie du logiciel pour les systèmes hétérogènes.</p>
<p><a name="program"></a></p>
<h3>Programme</h3>
<ul>
<ul>
<li>09h00-09h30 : accueil / café</li>
<li>09h30-10h00 : <a href="http://gemoc.org/as/20111125_workshop.pdf">présentation de l&#8217;AS</a> et tour de table</li>
<li>10h00-12h00 : exposés
<ul>
<li>Valerie Issarny (INRIA) : <a href="http://gemoc.org/as/issarny.pdf">Interopérabilité dans les systèmes de l&#8217;Internet du futur : des modèles aux middlewares émergents</a></li>
<li > <a class="accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseOne">Jacques Malenfant (LIP6)</a> : <a href="http://gemoc.org/as/malenfant.pdf">Composabilité et interfaces riches</a><em><span style="font-size: small;"><br />
     <div id="collapseOne" class="panel-collapse collapse">
                    <div class="panel-body">
La capacité à construire des systèmes embarqués corrects par composition de composants eux-mêmes corrects est l&#8217;un des objectifs les plus importants mais aussi les plus ambitieux du domaine. L&#8217;une des difficultés rencontrées réside dans le grand nombre d&#8217;aspects internes aux composants qui peuvent entrer en conflit au sein des assemblages réalisés. Pour s&#8217;attaquer à ce problème, nous proposons de réifier au sein d&#8217;interfaces riches à la Henzinger l&#8217;ensemble de ces aspects aux frontières des composants sous la forme de contraintes les plus déclaratives possibles. Ces contraintes permettent de vérifier la composabilité par l&#8217;implication des contraintes requises par les contraintes offertes lors de la connexion des composants, mais également de construire l&#8217;ensemble de contraintes commune à l&#8217;assemblage obtenu. Cette approche par interfaces riches doit cependant être complétée par des opérateurs de composition relativement intrusifs sur les composants, pour produire par exemple un ordonnancement combiné respectant l&#8217;ensemble des contraintes temporelles et des contraintes d&#8217;accès aux ressources synchronisées. Un premier système prototype a été réalisé dans le cadre d&#8217;une thèse soutenue en 2010.<br />
                    </div>
     </div>
</span></em></li>
<li> <a class="accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseTwo"> Cécile Hardebolle (Supélec)</a> : <a href="http://gemoc.org/as/hardebolle.pdf">Modèles hétérogènes et adaptation sémantique dans ModHel&#8217;X</a><em><span style="font-size: small;"><br />
<div id="collapseTwo" class="panel-collapse collapse">
                    <div class="panel-body">
ModHel&#8217;X est un framework qui permet de décrire et de simuler le comportement de modèles qui utilisent conjointement plusieurs formalismes de modélisation. L&#8217;hétérogénéité entre formalismes y est traitée hiérarchiquement, c&#8217;est-à-dire qu&#8217;on ne peut changer de formalisme qu&#8217;en changeant de niveau de description du système modélisé. La structure des modèles est exprimée à l&#8217;aide d&#8217;un méta-modèle générique qui décrit l&#8217;interface des composants, leur interconnexion dans un modèle, ainsi que la composition hiérarchique des modèles. Les composants sont considérés comme des boîtes noires, et l&#8217;objectif est de combiner les comportements que l&#8217;on observe à leur interface. Pour chaque modèle élémentaire, les règles de combinaison du comportement des composants sont données par un modèle de calcul qui indique dans quel ordre les composants sont observés,et comment l&#8217;information est propagée entre les composants. Un moteur d&#8217;exécution générique interprète ces règles et les applique à la structure des modèles pour calculer leur comportement. À la frontière entre des modèles de sous-systèmes qui utilisent des modèles de calcul différents, ModHel&#8217;X permet de spécifier explicitement l&#8217;adaptation sémantique, c&#8217;est-à-dire la manière dont les données, le temps et le contrôle sont transformés en passant d&#8217;un modèle à l&#8217;autre. L&#8217;adaptation sémantique du temps et du contrôle fait appel aux notions d&#8217;horloge utilisées par exemple dans l&#8217;approche synchrone.<br />
                    </div>
     </div>

</span></em></li>
<li><a class="accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#collapseThree">  Laurent Rioux (THALES Research &amp; Technology) </a> <a href="http://gemoc.org/as/rioux.pdf">Vers une IDM pour des architectures «hybrides» </a><em><span style="font-size: small;"><br />
<div id="collapseThree" class="panel-collapse collapse">
                    <div class="panel-body">

Les systèmes embarqués tels que ceux qui sont conçus et développés chez THALES ont des architectures systèmes et logiciels très variées. Ces architectures doivent faire face à une  complexité croissante des exigences fonctionnelles et non-fonctionnelles des systèmes. Il n’est plus possible aujourd’hui de sur-contraindre l’ensemble du système avec des exigences  temps-réel et critique juste parce que certaines fonctions l’exigent. Sur-contraindre un système peut simplement rendre le système infaisable. Il nous faut donc utiliser des architectures capables d’intégrer des sous-systèmes qui ont des propriétés non-fonctionnelles intrinsèquement différentes. Nous définissons généralement ces architectures comme des architectures hybrides. Ces architectures hybrides posent le problème de l’intégration de ces sous-systèmes sans qu’ils perdent leurs propriétés non-fonctionnelles (comme la sureté de fonctionnement, la performance, etc…) car ils dépendent désormais de sous-systèmes n’ayant pas des propriétés  non-fonctionnelles identique.</span></em>L’approche IDM (Ingénierie Dirigée par les Modèles) nous permet de maitriser la complexité des fonctionnalités de ces systèmes et d’analyser, de vérifier différentes propriétés non-fonctionnelles. Elle nous permet même de faire de la réutilisation et de l’intégration de fonctionnalités (par exemple : composants). Cependant, les standards de l’IDM ne nous permettent pas de modéliser d’une manière précise les interconnections entre ces sous-systèmes hybrides (par exemple : modèles de temps différents, etc) pour pouvoir les analyser, les vérifier et finalement les optimiser pour s’assurer que le système complet rempli les exigences à la fois fonctionnelles mais aussi  non-fonctionnelles.</li>

                    </div>
     </div>
</ul>
</li>
</ul>
</ul>
<ul>
<li>12h00-14h00 : déjeuner</li>
<li>14h00-14h30 : <a href="http://gemoc.org/as/20111125_workshop.pdf">présentation des résultats de l&#8217;AS</a></li>
<li>14h30-15h30 : discussion sur les résultats de l&#8217;AS</li>
<li>15h30-16h00 : pause café</li>
<li>16h00-17h30 : discussions pour l&#8217;identification d&#8217;un groupe de travail et des verrous scientifiques</li>
</ul>
<h3>Organisation</h3>
<p>L&#8217;atelier a lieu dans la salle <em><a href="resources/INRIA_PlaceItalie_etage5.pdf">verte (1 &amp; 2)</a></em> de l&#8217;<a href="http://www.inria.fr/centre/paris-rocquencourt/presentation/comment-venir">antenne parisienne de l&#8217;INRIA</a> (<a href="http://maps.google.fr/maps?q=23+avenue+d%27Italie,+75214+Paris+Cedex+13&amp;hl=fr&amp;ie=UTF8&amp;ll=48.828919,2.356675&amp;spn=0.007797,0.021136&amp;hnear=23+Avenue+d%27Italie,+75013+Paris,+%C3%8Ele-de-France&amp;t=m&amp;z=16&amp;vpsrc=0&amp;iwloc=A" target="_blank">23 avenue d&#8217;Italie, Paris</a>). Le déjeuner est pris en charge par l&#8217;AS.</p>
<h3>Organisateurs</h3>
<ul>
<li>Benoit Baudry (INRIA)</li>
<li>Benoit Combemale (IRISA)</li>
<li>Julien De Antoni (I3S)</li>
<li>Frédéric Mallet (I3S)</li>
</ul>
<h3>Participants</h3>
<ul>
<li>Idir Ait Sadoune (Supélec)</li>
<li>Christian Attiogbe (LINA)</li>
<li>Benoit Baudry (INRIA)</li>
<li>Nelly Bencomo (INRIA)</li>
<li>Réda Bendraou (LIP6)</li>
<li>Mireille Blay (I3S)</li>
<li>Frédéric Boulanger (Supélec)</li>
<li>Pierre Boulet (LIFL)</li>
<li>Joël Champeau (ENSTA-Bretagne)</li>
<li>Cauê A. Clasen (EMN)</li>
<li>Benoit Combemale (IRISA)</li>
<li>Xavier Crégut (IRIT)</li>
<li>Julien De Antoni (I3S)</li>
<li>Jérome Delatour (ESEO)</li>
<li>Sophie Ebersold (IRIT)</li>
<li>Mahmoud El Hamlaoui (IRIT)</li>
<li>Nikolaos Georgantas (INRIA)</li>
<li>Sébastien Gerard (CEA)</li>
<li>Marie-Pierre Gervais (LIP6)</li>
<li>Cécile Hardebolle (Supélec)</li>
<li>Valerie Issarny (INRIA)</li>
<li>Ali Koudri (THALES Research &amp; Technology)</li>
<li>Jean-Christophe Le Lann (ENSTA-Bretagne)</li>
<li>Jacques Malenfant (LIP6)</li>
<li>Frédéric Mallet (I3S)</li>
<li>Marc Pantel (IRIT)</li>
<li>Laurent Rioux (THALES Research &amp; Technology)</li>
<li>Jean-Pierre Talpin (INRIA)</li>
<li>Xavier Thirioux (IRIT)</li>
</ul>

    </div>
    <!-- /.col-lg-12 -->
</div>
<!-- /.row -->
