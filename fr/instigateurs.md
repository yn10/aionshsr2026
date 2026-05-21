<div id="header"></div>
<script>
    fetch('header.html')
        .then(response => response.text())
        .then(data => {
            document.getElementById('header').innerHTML = data;
        })
        .catch(error => console.error('Error loading header:', error));
</script>

<div class="lang-switch">
  <a href="#" class="switch" onclick="switchLang('en')">English</a>
</div>

<script>
function switchLang(lang) {
  let path = window.location.pathname;

  const parts = path.split("/").filter(Boolean);

  const repo = "aionshsr";

  const repoIndex = parts.indexOf(repo);

  if (repoIndex === -1) {
    window.location.href = "/" + repo + "/" + lang + "/";
    return;
  }

  const afterRepo = parts.slice(repoIndex + 1);

  if (afterRepo[0] === "en" || afterRepo[0] === "fr") {
    afterRepo.shift();
  }

  const newUrl =
    "/" + repo + "/" + lang + "/" + afterRepo.join("/");

  window.location.href = newUrl;
}
</script>

# Les Instigateurs de calamités

### Nanook la Destruction
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Nanook.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Si la croissance de l'entropie est une loi fondamentale de l'univers, alors la mort thermique devrait être le destin inévitable du monde matériel. Par conséquent, pourquoi lutter pour survivre ? L'univers s'étend, fusionne, puis sera anéanti. Si nous voulons accueillir une nouvelle vie, nous devons d'abord accepter sa fin. »*~~
><div align="right"><i><s>— Paroles d'un scientifique juste avant qu'il n'appuie sur le bouton déclenchant une explosion nucléaire, 2152 E. A.</s></i></div><br>
>La naissance de l'univers est une erreur. Si la civilisation est un cancer né de l'immensité stellaire, alors la guerre est le seul langage commun connu de toute forme de vie intelligente.\
>Pour corriger le tir et laver l'univers de cette tache, Nanook est devenu l'avatar de l'entropie.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Après avoir été témoin de la destruction d'Adlivun par l'Essaim et l'Empire des machines à sa naissance, Nanook estime que la création de l'univers est une erreur et cherche à tout détruire. Après son ascension en tant qu'Aiôn, Nanook aurait prétendument incendié son monde d'origine.

Bien qu'il soit le dernier Aiôn à s'être élevé, Nanook et ses serviteurs peuvent déjà être considérées comme la plus grande menace de toute la galaxie.

Nanook apparaît fréquemment sous la forme d'un homme à la peau brune, avec de longs cheveux blancs et deux tresses, ainsi que des yeux dorés. Une immense cicatrice, ainsi que de multiples autres plus petites, sont visibles sur sa poitrine, d'où s'échappe de l'ichor doré. Un quart de ses bras flotte et la moitié de ses membres inférieurs sont couverts de flammes dorées et de fumée noire, illustrant son désir de destruction.

---
### Tayzzyronth la Propagation
**Statut :** Inactif ; scellé dans une prison d'ambre

<div style="text-align: center;"><img src="/aionshsr/images/aions/Tayzzyronth.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Si des ombres surgissent à l'horizon en pleine journée, fermez vite vos portes et vos volets, car ce n'est pas le crépuscule qui arrive, mais bien l'Essaim affamé. »*~~
><div align="right"><s>— Fables sur les étoiles <i>par Adrian Spencer Smith</i></s></div><br>
>Tayzzyronth, également connu comme l'Imperator Insectorum, le Roi des sables ou le créateur du Désastre de l'Essaim.\
>En tant que dernier membre des Coléoptères, qui régnaient sur la terre, c'est la solitude qui lança Tayzzyronth sur sa Voie, qui se transforma en une horreur auto-duplicatrice, un torrent de propagation infinie. Tayzzyronth, ou plutôt les Tayzzyronths traversèrent les mondes jusqu'au moment où leur avancée fut stoppée.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Tayzzyronth est un Aiôn uniquement animé par le besoin de se propager et de se répandre dans l'univers. Il est responsable de l'apparition de l'Essaim et de sa propagation dans l'univers durant le Désastre de l'Essaim.

Tayzzyronth se présente sous la forme d'un large insecte doté de six pattes et de deux grandes ailes. Au sommet de son corps se trouve une marionnette humanoïde sans visage pourvue de deux petites ailes dans son dos.

Lorsqu'il apparaît dans l'Univers simulé, il émet un cri strident accompagné d'un battement d'ailes, tandis que d'autres cris se font entendre au loin

---
### Yaoshi l'Abondance
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Yaoshi.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Les fleurs éclosent, oublieuses, dans l'attente de leur inévitable destin : faner. Les oiseaux déploient leurs ailes et chantent, volant vers leur chute certaine. Les ruisseaux coulent, pleins de vie, vers un lieu où ils s'assécheront inévitablement. Pourquoi tout doit-il dépérir ? Sûrement, un miracle dans l'univers peut soigner cette maladie appelée fatalité. »*~~
><div align="right"><s>— La vie est trop courte <i>par un anonyme</i></s></div><br>
>Demandez avec cœur et vous recevrez.\
>Yaoshi nourrit la vie, il est le dieu du paradis éternel. Son idéal est d'assurer la présence perpétuelle de la vie.\
>Yaoshi est un Aiôn qui répond à toutes les prières et ne supporte pas le spectacle de la mort et de la douleur liée à la maladie.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

La nature bienveillante de Yaoshi l'a amené à accorder sa bénédiction à tous ceux en quête d'immortalité. Cependant, les conséquences de ces bénédictions se soldent souvent par un destin pire que la mort.

Dans l'Univers simulé, Yaoshi est décrit comme un être doté de six bras, d'une queue crochue semblable à celle d'un scorpion, et de cheveux semblables à une plume de pie. Il possède des bois ressemblant à des branches jaillissant de sa tête ainsi que des yeux rouges fendus, ainsi que des sclères noires sur certaines parties de son corps.

Dans la culture foxienne, il est dit que Yaoshi porte un bâton.
