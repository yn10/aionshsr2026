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

# The Authors of Calamity

### Nanook the Destruction
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Nanook.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"If the increase of entropy is a fundamental law of the universe, then the heat death would be the inescapable destiny of the material world. So, why is it that we bother to struggle to survive? Expansion, fusion, and then annihilation. If we wish to welcome the new, then we must first embrace the end."*~~
><div align="right"><i><s>— From a scientist just before pressing the button for nuclear detonation, 2152 AE</s></i></div><br>
>The birth of the universe is a mistake. If civilization is a cancer emerging quietly from the boundless stars, then war is the only common language known to all intelligent life.\
>To correct this mistake and to clean up this tainted universe, Nanook became the avatar of entropy.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Witnessing the destruction of THEIR home world, Adlivun, as it was marred by the Swarm and the Machine Empire during THEIR birth, Nanook sees the creation of the universe as a mistake and seeks to destroy everything. After ascending to Aeonhood, Nanook allegedly ignited the Adlivun star system, burning THEIR world to an "obsidian hellscape."

Despite being the most recently ascended Aeon, Nanook and THEIR Antimatter Legion may already be considered the greatest menace in all the galaxy.

Nanook is depicted as a human male with long, white braided hair, brown skin, and golden eyes. A large gash along with multiple smaller wounds is seen on THEIR chest as golden ichor seeps out. On THEIR neck is a black choker with a golden clasp lining the fabric. A quarter of THEIR arms are separated into floating pieces to reveal glowing golden ichor inside, and THEY appear to be wearing black bandages with golden inscriptions that wrap around THEIR hands as makeshift fingerless gloves.

---
### Tayzzyronth the Propagation
**Status:** Fallen (sealed within an amber prison)

<div style="text-align: center;"><img src="/aionshsr/images/aions/Tayzzyronth.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~"Hurry and shut your doors and windows if shadows appear at the noontide horizon, for that is no early dusk but the hungering Swarm."*~~
><div align="right"><s>— Fables About the Stars <i>by Adrian Spencer Smith</i></s></div><br>
>Tayzzyronth, also known as the Imperator Insectorum, the Sand King, and the creator of the Swarm Disaster\
>As the last member of the Coleoptera that rules the land, THEIR Path was ignited out of a desire born from loneliness. Tayzzyronth metamorphosed into a self-duplicating horror, a torrent of infinite propagation. Tayzzyronth — Tayzzyronths rather — fluttered across the worlds until THEIR advances were halted by fate in some way.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Tayzzyronth is an Aeon motivated by nothing but the need to propagate and spread across the universe. THEY were responsible for the rise of The Swarm, and its eventual spread throughout the universe during the Swarm Disaster.

Tayzzyronth appears as a large insect in black, wine red, and other matching colors. THEY have six membranous wings, three on each side, with four tinted with white. On top of THEIR main body is a pale-skinned, faceless, puppet-like humanoid with two small wings on THEIR back.

When THEY appear in Simulated Universe, a loud screech can be heard, accompanied by the fluttering of wings. In the distance, more cries can be heard.

---
### Yaoshi the Abundance
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Yaoshi.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"The flowers share their petals without care, waiting for their inevitable withering destiny. The birds fly high in song, moving toward their inevitable crash and death. The streams flow rapidly with life, in a direction where they inevitably run dry. Why must all things come to an end? There must be a miracle somewhere in the universe that can cure the disease known as finality."*~~
><div align="right"><s>Life Is Too Short <i>by Anonymous</i></s></div><br>
>Ask with sentiment, and you shall receive.\
>Yaoshi is the nurturer of the people, the god of peace. THEIR presence ensures the existence of life.\
>Yaoshi is an Aeon who answers all prayers and cannot bear to see death and the pains of illness.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

Yaoshi's benevolent nature led THEM to grant THEIR blessing upon anyone who seeks immortality. However, the consequences of these blessings often result in a fate worse than death.

Yaoshi is described as a figure with six arms and very pale skin, along with hair similar to that of a magpie’s feather in the Simulated Universe. THEY have antlers resembling branches sprouting from THEIR head and slits of red eyes with black sclera on parts of THEIR body.

Yaoshi is described wielding a staff in Foxian culture.
