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

# The Non-classified

### Ena the Order
**Status:** Fallen (assimilated into Xipe)

<div style="text-align: center;"><img src="/aionshsr/images/aions/Ena.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Ena was one of the most ancient Aeons, characterized as a just and magnificent being. THEY thoroughly observed the actions of mortals to ensure the order of the universe, while displaying intolerance to any form of chaos or strife. Before THEIR fall, THEIR path had suppressed numerous calamities, such as the Swarm Disaster.

THEIR voice is composed of syllables sequencing the rise and fall of civilizations in accordance with the Aeon's path. During the Swarm Disaster, Ena was assimilated by Xipe as the latter ascended.

Ena takes the form of a giant eye observing and puppeteering a trunkless puppet veiled with tattered cloth and crowned with a golden halo. The halo is attached to a golden frame, framing the puppets face. Both the puppet itself and the cloth are white with golden accents. The puppet is holding and crystal-gazing into an orb containing the cosmos.

---
### HooH the Equilibrium
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/HooH.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~"I stole away the golden weights, and felt proud of the ripples stirred up. The Aeon always sees right through my tricks, and the stars reset the balance to zero."*~~
><div align="right"><s>— Fables About the Stars <i>by Adrian Spencer Smith</i></s></div><br>
>The chain of karma that mortals obsess over is nothing but a rough approximation of the complicated topology behind all things — HooH dissolved THEIR will into the web of logic behind the universe's movement, maintaining the balance and stability of all things in perpetuity.
Adventurous mortals tirelessly seek out flaws in this system, believing their intellect to be superior to that of the Aeon. However, little could they imagine that they have already been reduced to strings inside a surveillance system, unable to escape the meticulous network woven by HooH.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Their form is unknown.

HooH and their Emanators influence the universe surreptitiously, trying to achieve an ideal balance

---
### IX the Nihility
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/IX.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"You may gaze deep into the vast grandeur of the stars, but do not glance at the abyss of the void... for it holds nothing except for the ability to make mortals lose all reason and thought."*~~
><div align="right"><i><s>— Murong, Doctor of Chaos</s></i></div><br>
>LThe existence of Nihility is a mystery itself, THEIR form enshrouded by layers of mist.\
>IX doesn't interact with the other Aeons. THEY believe that the ultimate fate of the multiverse is nothingness, and therefore, worthless.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

IX is an apathetic Aeon, believing existence is absolutely meaningless, so doing anything is worthless. THEY don’t interact with other Aeons and THEIR existence is a mystery. Just being near IX’s form can make one feel numbed and dejected.

IX resembles a large purple blob with two white eyes, with a large collection of asteroids and planets being pulled towards THEM. What appears to be THEIR body is a swirling nebula of magenta and blue stars enveloped by a large purple gas.

---
### Long the Permanence
**Status:** Fallen

<div style="text-align: center;"><img src="/aionshsr/images/aions/Long.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Long traversed the universe an untold number of Amber Eras ago with the primary goal of seeking the meaning to life itself. At some point, THEY found their answer, which became known as the Revelation of the Permanence. After that, Long's scions also emerged. No one knows exactly the true ideals of the Aeon, but the penman of the Candelagraphos of the Intelligentsia Guild, Oppenheimer, came to certain conclusions..

Long could have defined the meaning of existence to be the "timeless nature of one's greatness." THEIR decision to reincarnate, abhorring biological immortality, also led the penman to question if the revelation postulates the "continuance of bloodline." Alternatively, the decision of the High Elders of the Vidyadhara to ally with the Xianzhou Alliance signifies their inclination towards "a noble ambition that ensures the safety of the universe."

THEY used to appear in the form of a giant dragon. THEY left behind a large number of descendants known as Long's Scions

---
### Mythus the Enigmata
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Mythus.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"To stop questioning is to ask pouring rain to relinquish its faith in the glittering stars. Open yourself to the roaring river of metaphors, and you will find truth awaits, hiding at the end of the night sky, in the swirling rosy storm of a bygone age."*~~
><div align="right"><i><s>—Sharon Leighton, Galactic Laureate Poet (Self-Proclaimed)</s></i></div><br>
>It is a fallacy that all things can be experienced and recognized. The living seek to produce prophecies of the unknown based on their limited grasp of order, but little do they know that the universe has no end and that the truth is but a fevered dream.
>
>To prevent the certainty that Erudition brought about from destroying the possibilities championed by Mythus, Mythus conjured the Fog of Thought and the Rain of Sensation to reveal to the mortals the inexplicable truth through the four agents: Morph, Screen, Riddle, and Mirage.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>


THEY believe that things-in-themselves are beyond perception, and that finite entities are incapable of envisioning true infinity, and therefore everything is an enigma.

Mythus resembles a broken and torn jellyfish, akin to a deliberately destroyed version of the cognitive center of the human brain. THEY have a humanoid body surrounded by a staircase.

---
### Ouroboros the Voracity
**Status:** Sealed within Ahatopia

<div style="text-align: center;"><img src="/aionshsr/images/aions/Ouroboros.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"Insects are to birds, as hares are to wolves. The stars are to the black hole, as the worlds are to the voracity."*~~
><div align="right"><s>— Worlds History as a Mirror, <i> Xianzhou</i></s></div><br>
>The drinker of worlds, the unsatisfied devourer, the black hole with thought. THEY are an Aeon and a Leviathan at the same time.\
>In the eyes of Oroboros, life is a flickering fragment floating in the sea of void, destined to return to the darkness along with the stars which birthed THEM — This darkness is within the depths of THEIR mouths.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

The unsatisfied devourer of worlds. Legends say THEY are an Aeon as well as a kind of ancient beings named Leviathans.

---
### Terminus the Finality
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/inconnu.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

Terminus travels against time from the future, having split THEIR divine corpus into a pack of black cats, empowering each cat with a part of THEIR divine power. According to Elegy, a member of the Creed Exequy, THEY appear at every moment of Finality, bringing prophecies of the future. Terminus is described as being asleep, and the words heard are simply somniloquy, commonly known as sleep-talking. As THEIR words are merely murmurs, time has to be taken to decipher the information behind THEIR words, often driving some mad.

---
### Xipe The Harmony
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Xipe.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"The world is in harmony and the stars shine bright. Praise the Lord! All are connected and the wind of blessing breathes across the lands!"*~~
><div align="right"><s>— Odes of Harmony, <i>, I</i></s></div><br>
>A plural Aeon from multiple harmonious worlds. The glorious Xipe of thousand faces is chanting songs of joy and happiness.\
>To battle the brutality of the laws of the universe, intelligent lifeforms must discard their cowardly selfishness and the differences between individuals, fusing into one singular melody — to have the strong help the weak, and to protect life with death.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Xipe is the amalgamation of thousands of entities that preaches the joy of human harmony and unity hailing from multiple harmonious celestial worlds. THEY absorbed Ena the Order when the former ascended into an Aeon due to THEIR colliding Paths nearing the end of the Swarm Disaster.

Xipe presents as a serene, periwinkle-skinned humanoid with three faces — two on either side of THEIR head and one on the front. The faces are framed with lengthy white curtain bangs and are each adorned with a circlet. Xipe's extensive swathe of hair is colored white with a twinkling dark purple ombre, aloft a polychromatic flare reminiscent of a halo.

The substance of Xipe's body flays into jigsaw-like fragments, covering it in a form-fitting dress that is decorated with nebular expressions of the cosmos. The dress’ lower part flows past THEIR feet, with firm lattices in gold wrapping around the collar and torso.
