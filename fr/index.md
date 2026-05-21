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

## Introduction

_Honkai: Star Rail_ est un jeu de rôle tactique développé par miHoYo (connu en dehors de Chine sous le nom de HoYoverse). Il s'agit du quatrième volet de la série Honkai, utilisant de nouveaux personnages ainsi que des versions alternatives des mêmes personnages de _Honkai Impact 3rd_. Il est sorti officiellement le 26 avril 2023 sur Microsoft Windows, Android et iOS.

Dans _Honkai: Star Rail_, les Aiôns sont des êtres mystérieux de dimension supérieure qui sont semblables à des dieux. Ce sont eux qui dirigent l'univers.. Chaque Aiôn est associé à une Voie, par lequel ils peuvent utiliser son énergie à leur guise, mais ils y sont également liés pour le reste de leur vie. Les mortels partageant le même objectif se réunissent pour mettre en pratique leur compréhension des Aiôns et des Voies, et se réunissent en Factions, tandis que ceux qui arpentent les Voies sont surnommés des « Éclaireurs », et exécutent la volonté de la Voie. Dans cette immensité stellaire vide, un petit nombre de mortels peut également faire usage du pouvoir des Voies avec la permission des Aiôns. On les appelle des « Émanateurs ».

## Description

>Les gens en savent très peu sur la vie mystérieuse parmi les vastes mers stellaires. Les connaissances limitées des formes de vie intelligentes leur permettent seulement de discerner, au travers de croyances, les Aiôns qui arpentent des voies imperceptibles pour les mortels et qui déploient des pouvoirs incompréhensibles. Avec le temps, les Aiôns devinrent l'incarnation de concepts philosophiques condensés, au travers des légendes répandues par le bouche-à-oreille.
>
>Quiconque se trouve sur la Voie d'un Aiôn finira par se sentir submergé par une sensation lointaine, comme si la glace l'avait emprisonné dans le cosmos à des années-lumière. Nombreux sont ceux qui croient que c'est le seul lien possible entre Aiôns et mortels.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

## Profil

La naissance d'un Aiôn fait naître une Voie sur laquelle l'Aiôn possède alors un pouvoir. Les Aiôns ont également la possibilité de donner accès à leur pouvoir, faisant d'un mortel un Émanateur de leur Voie. Les Aiôns ne peuvent agir que selon leur « Primum Mobile », ce qui les rend incapables de faire quoi que ce soit de contraire à leur Voie.

### Mortalité

Selon Kafka, une Chasseuse de Stellaron, il existe trois façons pour un Aiôn de mourir. Cependant, elle s'échappera avant de révéler la troisième méthode.

1. Par la collision de Voies issues de concepts qui se chevauchent. C'est ainsi qu' [Ena l'Ordre](/nonclasses.md#ena-lordre) a été absorbée par [Xipe l'Harmonie](/nonclasses.md#xipe-lharmonie) dans un processus comparable à la « sélection naturelle ».
Toutefois, il existe des exemples de Voies « similaires » coexistant pendant des périodes de temps différentes, comme la Préservation avec le [Souvenir](/sacrosaints.md#fuli-le-souvenir), et l'[Abondance](/instigateurs.md#yaoshi-labondance) avec la [Propagation](/instigateurs.md#tayzzyronth-la-propagation).
2. Par l'élimination d'un Aiôn par un autre Aiôn. [Tayzzyronth la Propagation](/instigateurs.md#tayzzyronth-la-propagation) a été utilisé comme exemple, mais il est révélé plus tard qu'il a simplement été scellé dans de l'ambre et emprisonné, ce qui réfute cette méthode.

### Apparence

Les formes des Aiôns que les mortels peuvent voir à l'œil nu sont supposées être des projections depuis une dimension supérieure.

### Catégories

La Commission de divination de Xianzhou classe les Aiôns en trois catégories.

1. Les « [Seigneurs](seigneurs.md) » qui déterminent la naissance et la mort des mortels et sont étroitement liés à la montée et à la chute des civilisations.
2. Les « [Sacrosaints](sacrosaints.md) » qui sont difficiles à classer comme bons ou mauvais, et dont les objectifs ultimes sont souvent impossibles à cerner. 
3. Les « [Instigateurs de calamités](instigateurs.md) » qui sont les principaux responsables de tous les désastres.
