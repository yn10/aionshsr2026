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
  <a href="#" class="switch" onclick="switchLang('fr')">Français</a>
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

_Honkai: Star Rail_ is a tactical role-playing game developed by miHoYo (known outside China as HoYoverse). It is the fourth installment in the Honkai series, featuring new characters as well as alternate versions of characters from Honkai Impact 3rd. It was officially released on April 26, 2023, on Microsoft Windows, Android and iOS.

In _Honkai: Star Rail_, the Aeons are mysterious higher-dimensional beings similar to gods. They are the ones who govern the universe. Each Aeon is associated with a Path, through which they can use its energy at will, but are also bound to it for the rest of their existence. Mortals who share the same goal gather to put their understanding of Aeons and Paths into practice, forming Factions, while those who follow the Paths are called "Pathstriders," and carry out the will of the Path. In this vast, empty stellar expanse, a small number of mortals can also wield the power of the Paths with the permission of the Aeons. They are called "Emanators."

## Description

>People know very little about the mysterious existence that dwells in the vast stellar seas. With the limitation of knowledge, intelligent lifeforms can only faintly discern that Aeons tread upon paths imperceptible to mortal beings and execute unfathomable powers via some form of belief. In the end, the Aeons became an embodiment of highly condensed concepts of philosophy through the word of mouth spread of their legends.
>
>If anyone finds themselves treading on the Path of an Aeon, they will be inundated by a distant sensation, like being struck by a gaze from light-years across the cosmos. Many believe that this is the only connection the Aeons and mortals can ever have.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

## Profile

The birth of an Aeon gives rise to a Path, which the Aeon then has power over. Aeons also have the ability to bestow access to THEIR power, making a mortal an Emanator of THEIR Path. Aeons can only operate according to THEIR "Primum Mobile" in such that THEY are incapable of doing anything contrary to THEIR Path.

### Mortality

According to Kafka, there are three known ways for an Aeon to die. She escapes before she can say the third.

1. Through the collision of Paths stemming from overlapping concepts. — This is how Ena was assimilated by Xipe, in a process Herta compares to a "survival of the fittest". However, there have examples of "similar" Paths co-existing for different lengths of time, such as the Preservation with the Remembrance, and the Abundance with the Propagation.
2. An Aeon killing another Aeon. — While she used Tayzzyronth as an example, it is later revealed that Tayzzyronth was merely sealed in amber and imprisoned, rendering this method dubious.

### Appearance

The forms of the Aeons that is visible to the mortal eye are assumed to be THEIR projection from a higher-dimensional plane.

### Categories

The Xianzhou's Divination Commission sorts Aeons into three categories:

1. "The [Arbiters](seigneurs.md)" — who determine mortal births and deaths, and are highly connected to the rise and fall of civilizations.
2. "The [Sacrosancts](sacrosaints.md)" — who are difficult to predict as good or evil, with THEIR ultimate destinations often unknowable. 
3. "The [Authors of Calamity](instigateurs.md)" — who are the main culprit behind all disasters. Yaoshi, Nanook, and Tayzzyronth are among these.
