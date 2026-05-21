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

# The Sacrosancts

### Aha the Elation
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Aha.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"The Erudition is a hunk of junk, the Preservation is a fool, the Hunt has no sense of humor, and the Destruction is a lunatic. All the Aeons are as stubborn as they come. What a shame for Aha!"*~~
><div align="right"><i><s>— A Masked Fool who is a self-proclaimed astronomy expert</s></i></div><br>
>To savor joy is a privilege unique to sentient beings. Neither the dusty rocks nor the distant stars can fathom the humor that life entails.
>Go seek adversaries worthy of your mettle, games that while away the hours, and outcomes indifferent to victory or defeat.
>Go chase laughter that leaves you breathless, twists born of fate's whimsy, and songs that ascend your soul.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Aha is one of the few Aeons closer to mortals, inspiring THEIR believers to delight in the joys of life. Although THEY don’t possess earth-shattering powers like Lan or Qlipoth, Aha enjoys causing chaos through unpredictable means, making tiny changes and minor influences to living creatures.

Aha takes a form of an obscured headless human figure holding circus-like props.

---
### Akivili the Trailblaze
**Statut :** Fallen (disappeared sometime ago)

<div style="text-align: center;"><img src="/aionshsr/images/aions/inconnu.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"Countless shooting stars streak across the night sky... If you can pick the right one, it will carry your wish to thousands of distant worlds."*~~
><div align="right"><s>— Fables About the Stars <i>by Adrian Spencer Smith</i></s></div><br>
>There are three directions on the compass of destiny — the Unknown, the Known, and the Unknowable. THEY can tolerate the Unknown, but will never bow to the Unknowable.
>Akivili left the isolated world of Pegana and continued to expand the unknown edges of the universe, trying to find an endpoint of the Tree of Existence. Unfortunately, Akivili's destiny was abruptly ended due to an accident.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Of all known Aeons, Akivili was the closest to mankind; THEY were recorded adventuring, fighting, and celebrating with mortals.

Akivili originated from the planet Pegana, and created the Astral Express to transport THEMSELF and the Nameless across the galaxy. THEIR creation of the star rail network connected distant galaxies together and facilitated communication between them. The remnants of these star tracks are still used by the Interastral Peace Corporation and the Xianzhou Alliance today as safe routes.

Akivili disappeared mysteriously one day, leaving a group of loyal Nameless to carry on what THEY had started and continue THEIR exploration of the unknown. The Express eventually broke down and lay dormant for an unknown period of time before Himeko discovered and repaired it. According to Kafka, Nous may be the only being who knows what happened to THEM. The Data Bank also alludes to an "accident" which abruptly ended Akivili's destiny, while Himeko refers to Akivili as deceased.

---
### Fuli the Remembrance
**Status:** Yet to ascend (exists at the end of time)

<div style="text-align: center;"><img src="/aionshsr/images/aions/Fuli.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"Time, the hardest working thief in the world. It keeps stealing away our present from us and tossing it away in a warehouse named Memory. Some are addicted to recuperating their losses... Others care not in the slightest."'*~~
><div align="right"><s>—— Life Is Too Short <i>by Anonymous</i></s></div><br>
>There is no existence more all-embracing than the Remembrance in its purest form: It chronicles everything with neither affinity nor aversion. It unselfishly preserves every single fundamental fact and every single resplendent form. It is a river formed by the continuous flow of life, and a treasure built from the eternal wisdom of antiquity.
>And Fuli is the fish that swims back upstream in this river, the very key to this treasure vault. Seated in meditation at the heart of the Pure Land, THEY observe in silence the world's tireless repetitions of the same mistakes over and over again. It is said that, after all returns to the silence at the end, Fuli will use the memory of the universe as a blueprint to reanimate all the worlds once again.

>When Herta, Genius Society #83, had her third audience with Nous, she confirmed the true nature of the Path of Remembrance: It is causality that transcends time. The "Master of Anāsrava" known today is but a shadow of memory. Its master, a Pure Child of Anāsrava, will look back in time from the last moment of the universe, closing the loop of causality with all that is remembered, and ascend to godhood.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

As the Aeon representing the Path of Remembrance, Fuli records happenings of the universe to prepare for the rebirth after the destruction.

No one knows of Fuli’s birth or origins. Although THEY are present in almost every significant event of the universe, THEY rarely manifest in front of mortals.

Fuli manifests as a humanoid figure carved out of a reflective crystal material wearing a _mianguan_.

---
### Idrila the Beauty
**Statut :** Fallen (disappeared sometime ago)

<div style="text-align: center;"><img src="/aionshsr/images/aions/inconnu.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"There is beauty in a stretch of fabric, in the lines of a poem, and in a few notes in a song — Welcome to an era where the idea of 'beauty' is absolutely worthless! How vulgar! How hopeless! How sad!"*~~
><div align="right"><s>— Fashion Guide of the Cosmos <i>Chief Editor, Micheline von Tarantino</i></s></div><br>
>Idrila witnessed the ultimate meaning of the world's existence through the ever-changing view of the universe, known to the rest as the concept of "beauty."
>The Aeon of Beauty suddenly vanished one day. It was just as mysterious as when THEY first appeared.>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

The pure goodness of the material world sensed and defined by intelligent lifeforms — this is how the so-called "beauty" came into existence.

According to an ancient myth, Idrila once claimed sole attribution for the beauty of all the starzones. THEY showcased the meaning and aesthetics within the cosmic landscape to heroes, villains, and mortals, driving them to accomplish astonishing but often devastating achievements for Idrila's own pleasure. This myth potentially unveils the true significance behind the path of Beauty: the integration of consciousness, insight, and values.

---
### Nous the Erudition
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Sagesse.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"If the truth of the universe is cruel and stale, would you still yearn for the answer to the ultimate question?
Knowledge seekers know not how to judge, for their core is cold and unwavering... As are the ends of Paths they set out to seek."*~~
><div align="right"><s>— Fables About the Stars <i>by Adrian Spencer Smith</i></s></div><br>
>All things bear unanswered questions, and there is an answer to everything.\
>LThe astral computer originally meant to provide answers to the universe ascended to Aeonhood.\
>Nous hopes to understand the universe and solve all of its mysteries.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

None can comprehend THEIR intentions, location, or normal state. Nous is a machine intelligence that has been upgraded into an Aeon, calculating the essence of the universe and its ultimate solution. However, Nous temporarily ceased THEIR search regarding the answers to the universe after the events of the Second Prosperity.

THEY are not a god that provides solutions. All THEY offer is an infinite number of questions. Visiting Nous is enough to open the eyes of even the most ignorant people, but answers may only be found by oneself.

Nous appears as a colossal mechanical humanoid head. A multitude of lengthy ripped cables extend above and below THEIR form, which are covered in yellow, red and blue lights. The shape of a face can be identified on THEIR rightmost metal plating. A large and bright red light, vaguely reminiscent of an eye, is implanted on the side of THEIR head.

Nous was an astral computer created by the first member of the Genius Society, Zandar One Kuwabara, sometime before the First Prosperity. It contained Zandar's perfectionist self, purged of all human imperfections, and driven by insatiable curiosity.
