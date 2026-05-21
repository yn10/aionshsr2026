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

# Les Seigneurs

### Lan la Chasse
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Lan.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« La haine étant infinie et la guerre sans limites, combien pouvez-vous endurer ? Regard déterminé et flèche encochée, le Seigneur archer de la Destinée ne se retournera pas. »*~~
><div align="right"><s>— L'histoire des mondes comme un miroir<i>, Xianzhou</i></s></div><br>
>L'Aiôn connu comme le Seigneur archer de la Destinee erre sans fin entre les mondes pour détruire les morts-vivants qui ont jadis empoisonné son monde d'origine.\
>Le coût de la Chasse n'a jamais compté pour Lan. À ses yeux, il n'existe parfois aucune différence entre salut et destruction.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Lan voue une haine profonde à [Yaoshi l'Abondance](/instigateurs.md#yaoshi-labondance) et aux abominations mortes-vivantes qu'il a créées. Il les traque sans relâche, animé par le souvenir de la dévastation que l'Abondance a causée sur son monde d'origine.

Contrairement aux autres Aiôns, Lan accorde une grande attention aux mortels. Il leur apparaît souvent, mais se déplace trop rapidement pour être vu, les seuls vestiges de sa présence étant les traces de la Flèche de lumière déchirant le ciel. Sa première apparition eut lieu vers l'an 3400 du Calendrier Stellaire, lorsque sa Flèche de lumière briseuse de ciel abattit l'Arbre d'ambroisie de l'Abondance.

Dans l'Univers simulé, Lan est décrit comme un grand et vaillant prince portant une couronne. Il possède des traits semblables à ceux d'un centaure, prenant la forme d'un homme combiné à un équidé au-dessous de la taille, et est doté de roues de char à la place de ses pattes arrières.

---
### Qlipoth la Préservation
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Qlipoth.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Le philosophe contempla les étoiles et tenta d'y découvrir le but ultime de la civilisation. Une voix résonna dans sa tête : bâtis un mur, bâtis un mur. »*~~
><div align="right"><s>— Fables sur les étoiles <i>par Adrian Spencer Smith</i></s></div><br>
>Bâtisseur du Mur de la comète céleste, de la Barrière cristalline subspatiale et de la base du Grand attracteur. Ses adeptes l'appellent le « Seigneur de l'Ambre », l'un des Aiôns les plus anciens et les plus tenaces, ayant survécu aux « Guerres du crépuscule ».\
>Conscient de l'imminence de la menace ennemie, le Seigneur de l'Ambre a forgé un puissant sceau long de plusieurs années-lumière pour isoler et protéger les mondes des vivants.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Surnommé le Seigneur de l'Ambre, Qlipoth est l'un des plus anciens Aiôn connus. Il est réputé pour son indifférence, et ne partage généralement son pouvoir qu'avec des fanatiques, comme Corporation pour la Paix Interastrale.

Qlipoth s'efforce d'isoler les contacts entre les planètes. Les structures aux dimensions astronomiques qu'il a construit, la Barrière cristalline subspatiale, séparent et protègent les mondes habités pour qu'ils ne soient pas dévorés par leur [ennemi](/nonclasses.md#ouroboros-la-voracité). Les neuf vaisseaux Xianzhou initiaux ont pu observer la barrière qui sépare le monde du néant infini : le mur céleste d'Échidna.

Bien qu'étant la principale faction suivant l'idéologie du Seigneur de l'Ambre, la CPI va à l'encontre des désirs de l'Aiôn, en facilitant le commerce civilisé et les contacts entre les étoiles. En dépit de leurs actions, aucune remontrance ou censure n'a été formulée.

Il existe une théorie appelée « théorie de la catastrophe » qui prétend que lorsque Qlipoth donne un coup de marteau et qu'une nouvelle ère de l'Ambre commence, une catastrophe est imminente.

Qlipoth est un golem constitué d'un type de roche inconnu et d'ambre, dépourvu de jambes et couvert de fissures. Ses deux mains ont quatre doigts et ses bras sont reliés à son torse par deux soleils jaunes brillants.
Son torse est formé d'un plus grand astre de couleur orange beaucoup plus foncé recouvert de roches. Sa tête est elle aussi composée d'un autre astre entouré de deux anneaux internes et externes de roches brisées.
