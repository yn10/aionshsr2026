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

# Arbiters

### Lan the Hunt
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Lan.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"With no end to hate and no boundaries to war, how much concern do you shoulder? With determined eyes and the arrow drawn, the Reignbow Arbiter needs not turn back hither."*~~
><div align="right"><s>— Worlds History as a Mirror, <i>Xianzhou</i></s></div><br>
>L'The Cruising Aeon known as the Reignbow Arbiter roams endlessly between worlds to eradicate the undead scourges that once ravaged THEIR homeworld.\
>Lan's Hunt, ever heedless of cost, often blurs the lines between salvation and ruin.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Banque de données, Aiôns</div>

Lan harbors an intense hatred towards Yaoshi the Abundance and the Denizens of Abundance supported by THEM. THEY tirelessly hunt them down, driven by the devastation the Abundance caused on THEIR homeworld.

In contrast with the other Aeons, Lan pays close attention to mortals. Although the Simulated Universe Index says that Lan often appears before mortals, Fu Xuan says that THEY rarely appear before mortals and "the only portents of THEIR presence are vestiges of the Lux Arrow tearing across the sky." The Record of Reignbow's Road says that "Reignbow would never speak to any mortal... THEY only let their Lux Arrow do all the talking." According to Welt, Lan does not rank among the more powerful Aeons as THEIR path is very narrow, but THEY pay close attention to mortals. THEY grant strength to the Xianzhou Alliance without reservation, allowing their marshal and six generals to stand on par with the Lord Ravagers, Emanators of Nanook the Destruction.

Lan is described as a tall, valiant prince with a crown in the Simulated Universe. THEY have light blue skin and long, flowing sky-blue hair with periwinkle accents that reaches past THEIR waist. Lan's face is obscured by a black mask with a white star in the middle, which extends to THEIR black headpiece. THEY possess centaur like features, taking form of a man combined with an equine below the waist, while the hind legs are replaced by blue fire-like wheels of a chariot.

---
### Qlipoth the Preservation
**Status:** Alive

<div style="text-align: center;"><img src="/aionshsr/images/aions/Qlipoth.webp" alt="Aha l'Allégresse" style="width: 50%; height: auto;"></div><br>

>~~*"The philosopher gazes upon the stars trying to find the ultimate goal of civilization — 'Build a wall.' A majestic voice echoed in his head. 'Build a wall.'"*~~
><div align="right"><s>— Fables About the Stars <i>by Adrian Spencer Smith</i></s></div><br>
>The builder of the Celestial Comet Wall, the Subspace Crystalline Barrier, and the Great Attractor Base. Followers call THEM the "Amber Lord," one of the oldest and most tenacious Aeons, having survived the "Dusk Wars."\
>Aware of the imminence of THEIR mortal enemy's devouring, the Amber Lord forged a powerful light-years-long seal that would isolate and protect the living worlds.
>
>---
><div align="right" style="font-style: italic;"><img alt="Banque de données icône" src="https://static.wikia.nocookie.net/houkai-star-rail/images/2/2f/Icon_Data_Bank.png" width="30" height="30" style="background: #262626; padding: min(max(calc(15%), 2px), 5px); border-radius: 9999px; vertical-align: middle; margin-right: 8px;">Data Bank, Aeons</div>

They are called the "Amber Lord" by their followers. They preside over the Path of Preservation, and are one of the oldest and most tenacious Aeons.

Qlipoth strives to isolate contact between planets. The celestial-sized structures THEY'VE built — the Subspace Crystalline Barrier — separates and protects the living worlds from being devoured by their enemy. The nine initial Xianzhou ships witnessed the barrier separating the world from the endless void: the Celestial Comet Wall, dubbed the Echidna Skywall by the Xianzhou.

Despite being the main faction aligned with the Amber Lord, the IPC goes against the desires of the Aeon, facilitating civilized trade and contact between the stars. No remonstration or censure has been directed towards them because of this.

There is a theory called "Catastrophe Theory" that states that when the hammer swings and a new amber era begins, a catastrophy is imminent.

Qlipoth is a legless golem littered with cracks, composed of an unknown type of rock and amber. Both of THEIR hands have four fingers, and the arms are connected to the torso by two bright yellow stars. The torso is composed of a larger star with a much darker orange color which is covered by rocks, and the head is composed of another star, which possesses a halo of inner and outer ring of broken rocks.
