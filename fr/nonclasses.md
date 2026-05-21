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

# Les non classés

### Ena l'Ordre
**Statut :** Absorbé par [Xipe l'Harmonie](/nonclasses.md#xipe-lharmonie)

<div style="text-align: center;"><img src="/aionshsr/images/aions/Ena.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Ena était l'un des plus anciens Aiôns, qualifié d'être de justice et de magnificence. Elle surveillait attentivement les actions des mortels pour assurer l'ordre de l'univers, tout en faisant preuve d'intolérance à l'égard de toute forme de chaos ou de conflit. Avant sa chute, sa Voie avait éliminé de nombreuses calamités, telles que le Désastre de l'Essaim.

Sa voix est composée de syllabes qui suivent l'ascension et la chute des civilisations en accord avec la Voie de l'Aiôn. Elle fut absorbée lors du Désastre de l'Essaim par Xipe lorsque cette dernière devint un Aiôn, en raison du chevauchement de l'Harmonie avec le concept de l'Ordre.

Ena prend la forme d'un œil géant observant et manipulant une marionnette blanche et dorée sans tronc, voilée d'un tissu en lambeaux également blanc et doré, et couronnée d'une auréole d'or. La marionnette tient et contemple un orbe renfermant le cosmos.

---
### HooH l'Équilibre
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/HooH.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« J'ai volé les poids en or et les répercussions ont fait ma fierté. L'Aiôn déjoue toujours mes tours et les étoiles remettent les comptes à zéro. »*~~
><div align="right"><s>— Fables sur les étoiles <i>par Adrian Spencer Smith</i></s></div><br>
>La chaîne du karma, qui obsède tant les mortels, n'est qu'une approximation grossière de la complexité présidant aux choses. HooH a dissous sa volonté dans la logique de l'univers pour maintenir à jamais l'équilibre et la stabilité de toute chose.\
>Les mortels les plus audacieux recherchent des failles dans le mouvement de l'univers, car ils croient que leur intelligence dépasse celle des Aiôns. Mais ils sont loin d'imaginer qu'ils ne sont que de simples fils d'un système de surveillance, incapables d'échapper au réseau de précision tissé par HooH.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Sa forme n'est connue de personne.

HooH et ses Émanateurs influencent subrepticement l'univers afin d'atteindre l'équilibre parfait.

---
### IX la Nihilité
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/IX.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Vous pouvez plonger le regard dans l'immensité des étoiles, mais ne regardez pas le gouffre du néant ... car il ne contient rien, sauf sa capacité à égarer l'esprit des mortels. »*~~
><div align="right"><i><s>— Murong, Docteur du chaos</s></i></div><br>
>L'existence de la Nihilité est en soi un mystère, et sa forme est enveloppée de brume.\
>IX n'interagit jamais avec les autres Aiôns et croit que l'essence du multivers est de plonger dans le néant, et que l'existence n'a donc aucune valeur.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

IX est un Aiôn indifférent, persuadé que l'existence n'a aucun sens et qu'il est donc inutile de faire quoi que ce soit. Il n'interagit pas avec les autres Aiôns et son existence est un mystère. Le simple fait de se trouver à proximité de la forme de IX peut susciter un état d'engourdissement et de découragement.

IX ressemble à un gros blob violet avec deux yeux blancs attirant vers lui de nombreux astéroïdes et planètes. Ce qui paraît être son corps est une nébuleuse tourbillonnante d'étoiles magenta et bleues enveloppées par un grand gaz violet. Il est possible que la forme de IX ressemble volontairement au chiffre 9, ce qui correspond à la signification de son nom en chiffres romains.

---
### Long la Permanence
**Statut :** Décédé

<div style="text-align: center;"><img src="/aionshsr/images/aions/Long.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Il y a un nombre incalculable d'ères de l'Ambre, Long parcourut l'univers avec pour principal objectif de trouver le sens de la vie elle-même. Au terme de sa vie, il trouva sa réponse, qui devint connue sous le nom de révélation de la Permanence. Nul ne connaît précisément les véritables idéaux de l'Aiôn, mais le scribe du Candélagraphe de la Guilde de l'intelligentsia, Oppenheimer, est arrivé à certaines conclusions.

Il est possible que Long ait défini le sens de l'existence comme étant « la nature intemporelle de la grandeur de chacun ». Sa décision de se réincarner, abhorrant l'immortalité biologique, a également conduit le scribe à se demander si la révélation postulait la « continuité de la lignée familiale ». Par ailleurs, la décision des Grands anciens des Vidyadhariens de se joindre à l'Alliance Xianzhou témoigne de leur inclinaison en faveur d'une « noble ambition qui garantit la sécurité de l'univers ».

Long était le « Père des dragons », et prenait autrefois la forme d'un dragon géant. Il laisse derrière lui un grand nombre de descendants appelés « scions de Long ».

---
### Mythus l'Enigmata
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Mythus.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Arrêter de se poser des questions, ça revient à demander à la pluie de renoncer à sa foi envers les étoiles scintillantes. Ouvrez-vous à la rivière rugissante des métaphores et vous trouverez la vérité qui se cache à l'extrémité du ciel étoilé, dans les tempêtes idylliques d'un âge révolu. »*~~
><div align="right"><i><s>— Sharon Leighton, poétesse lauréate galactique (autoproclamée)</s></i></div><br>
>C'est un mensonge de dire que toute chose peut-être vécue et reconnue. Les vivants cherchent à écrire des prophéties sur l'inconnu en se reposant sur leur sens limité de l'ordre de l'univers. Cependant, ils sont loin d'imaginer que celui-ci est infini et que la vérité n'est qu'une illusion trompeuse.
>
>Dans le but d'empêcher la certitude que [l'Érudition](/sacrosaints.md#sagesse-lérudition) apportait en détruisant les possibilités défendues par Mythus, ce dernier a invoqué le Brouillard de la pensée et la Pluie de sensations afin de révéler aux mortels l'inexplicable vérité à l'aide de quatre agents : Transformation, Écran, Énigme et Mirage.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>


Il considère que la perception surpasse tout et que les entités limitées sont incapables de concevoir l'infini tel qu'il est, ce qui fait que toute chose est énigmatique.

Mythus ressemble à une une méduse brisée et déchirée, semblable à une version délibérément détruite du centre « cognitif » du cerveau humain. Il a une apparence humanoïde entourée d'un escalier.

---
### Ouroboros la Voracité
**Statut :** Inactif ; a disparu durant le Désastre de l'Essaim

<div style="text-align: center;"><img src="/aionshsr/images/aions/Ouroboros.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Les insectes sont aux oiseaux ce que les lièvres sont aux loups. Les étoiles sont aux trous noirs, ce que les mondes sont à la voracité. »*~~
><div align="right"><s>— L'histoire des mondes comme un miroir<i>, Xianzhou</i></s></div><br>
>Le buveur de mondes, le devoreur insatiable, le trou noir qui pense. Il est à la fois un Aiôn et un Léviathan.\
>Aux yeux d'Ouroboros, la vie est un fragment vacillant qui flotte dans la mer du néant, destiné à retourner dans les ténèbres avec les étoiles qui les ont engendrées. Ces ténèbres se trouvent au fin fond de ses gosiers.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Il dévore les mondes insatiablement. Les légendes racontent qu'il aurait également la forme d'une sorte de créature ancestrale appelée Léviathan.

---
### Terminus la Finalité
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/inconnu.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Terminus voyage dans le temps depuis le futur. IL apparaît à chaque moment de la Finalité, apportant des prophéties à propos de l'avenir. Selon Élégie, membre des Exequaturs du Credo, la Finalité est la fin des autres Aiôns et Voies. [La Destruction](/instigateurs.md#nanook-la-destruction) elle-même ne peut être épargnée. Pourtant, la Finalité n'est pas la fin de tout ce qui est. Toutes les choses naîtront là et se dirigeront vers la Finalité suivante.

---
### Xipe l'Harmonie
**Statut :** En vie

<div style="text-align: center;"><img src="/aionshsr/images/aions/Xipe.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*« Le monde est en harmonie et les étoiles brillent de mille feux. Louée soit son Éminence ! Tout est connecté et le vent de la bénédiction souffle à travers les terres ! »*~~
><div align="right"><s>— Odes de l'Harmonie<i>, I</i></s></div><br>
>Un Aiôn multiple venu de plusieurs mondes harmonieux. La glorieuse Xipe aux mille visages entonne des chants de joie et d'unité.\
>Pour combattre la brutalité des lois de l'univers, les formes de vie intelligentes doivent oublier leur lâche égoïsme et les différences entre les êtres pour fusionner en un chant harmonieux, et pousser les forts à aider les faibles et protéger la vie avec la mort.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Xipe est l'amalgame de milliers d'entités en provenance de multiples mondes célestes harmonieux qui prêchent la joie de l'harmonie et de l'unité humaine. Lorsqu'elle s'est élevée au rang d'Aiôn vers la fin du Désastre de l'Essaim, elle a absorbé [Ena l'Ordre](/nonclasses.md#ena-lordre) suite à la collision de leurs Voies.

Xipe se présente comme une humanoïde à l'apparence sereine, à la peau pervenche et possédant trois visages, dont un devant et deux de chaque côté de la tête. Les visages sont encadrés par de longues franges blanches et sont tous ornés d'un diadème. Xipe possède une longue chevelure d'un dégradé blanc-violet foncé scintillant. Un mélange de couleurs vives flamboie derrière sa tête, à la manière d'une auréole.

Son corps semble constitué de pièces de puzzle dispersées. Il est recouvert d'un vêtement semblable à une robe ajustée décorée de motifs bleus et violets représentant le cosmos. Le vêtement descend jusqu'à ses pieds, tandis que son cou et son torse sont fermement encerclés d'un entrelacement de dorures.
