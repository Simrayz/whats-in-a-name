---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: /hi-my-name-is.jpg
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

<div class="bg-gray-900 bg-opacity-30 p-2 rounded-md">
  <h1 class="text-blue-200">Our name is what?</h1>

  <h3 class="text-green-300">The Sim Slidies on P-names</h3>
</div>

---

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

# Metodologi

- 📝 **Request For Information** - Ane forespurte teamnavn
- 🧠 **Brainstorming** - Initielt med teamet og tok helt av alene
- 📤 **Shaping** - Gruppering etter type navn og tilhørende beskrivelse/slogan
- 🤖 **Name Retrospective** - Review av forslag, må ha mer beskrivelser og tydeligere kravspesifikasjon. Forslag om litt mer wildcards og lekenhet.
- 🎉 **Name Review** - Presentasjon av forslag

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
level: 2
---

# The Animals

Hvilket dyr kunne vi vært?

<div class="grid grid-cols-3 gap-4 justify-center">

<PictureCard 
  v-click
  title="Podengo" 
  slogan="Brilliant's Best Friend"
  tag="Loyalty"
  image="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcHNyamY3MjBubDlneGNrdjN3Z3kyaWNqaW02MmdrdjNwM3QxOHN6YyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MT9dJhvWLo1CL8D74x/giphy.gif"
/>

<PictureCard 
  v-click
  title="Platypus" 
  slogan="Unexpected Excellence"
  description="It shouldn't work but it does."
  tag="Versatility"
  image="https://i.pinimg.com/originals/78/c8/85/78c885323c5db9435081804a57d49558.gif" 
/>

<PictureCard 
  v-click
  title="Porcupine" 
  slogan="Small but Packs a Punch"
  tag="Resiliience"
  image="https://64.media.tumblr.com/ef7c65181d0506ba81c1553dc7d70280/tumblr_o7c3k02uCd1qfthy3o2_400.gif"
/>

<PictureCard 
  v-click
  title="Pangolin" 
  slogan="Upping the Scale"
  tag="Adaptability"
  image="https://i.pinimg.com/originals/93/ce/da/93cedadc3d7cdd2f5a57386b29b4650b.gif"
/>

<PictureCard  
  v-click
  title="Panda" 
  tag="Diligence" 
  slogan="Keeper of the Forest of Ideas" 
  image="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/532ac8fa-5d42-4cd0-823a-13c07e3a7350/dfum52o-bc984501-a741-4402-8cd2-99bbd361317b.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzUzMmFjOGZhLTVkNDItNGNkMC04MjNhLTEzYzA3ZTNhNzM1MFwvZGZ1bTUyby1iYzk4NDUwMS1hNzQxLTQ0MDItOGNkMi05OWJiZDM2MTMxN2IuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.gnf6zud7Z66_7nPGBZ5PYSreQmKA-5wmAXJsuhIXZBQ"
/>

<PictureCard v-click title="Possum" image="https://j.gifs.com/VArv5O.gif" description="The (o)Possum stays in one area as long as there is food and water, and favor dark, secure areas. Can play possum to avoid uncomfortable situations." />

</div>

---
layout: image-right
image: https://miro.medium.com/v2/resize:fit:1400/1*9uuSCTtam462aYwDSeQECg.jpeg
---

## Mythical Beasts
<span class="text-4xl bg-gradient-to-r from-orange-600 via-yellow-500 to-red-400 bg-clip-text text-transparent">Phoenix</span>

<span class="bg-gradient-to-r from-yellow-600 via-cyan-500 to-green-400 bg-clip-text text-transparent">Trust the Cycle</span>

<ul>
  <li v-click>Embracing the cyclical nature of innovation</li>
  <li v-click>Rising form the ashes of setbacks and failure</li>
  <li v-click>Soaring high with unwavering confidence</li>
</ul>

---
layout: image-left
image: https://oldworldgods.com/wp-content/uploads/2023/11/pegasus1.jpg
---

## Mythical Beasts
<span class="text-4xl! bg-gradient-to-r from-yellow-600 via-cyan-500 to-green-400 bg-clip-text text-transparent">Pegasus</span>

<span class="bg-gradient-to-r from-white via-cyan-500 to-blue-400 bg-clip-text text-transparent">Soaring towards the horizon</span>

<ul>
  <li v-click>Keen eyes on difficult problems</li>
  <li v-click>Facing obstacles with precision and foresight</li>
  <li v-click>Challenges are opportunities for success</li>
</ul>

---
layout: image-right
image: https://qph.cf2.quoracdn.net/main-qimg-6e67a770e4e9948a1d1398da6ce0ed94
---

## Mythical Beasts
<span class="text-4xl! bg-gradient-to-r from-green-300 via-green-500 to-green-700 bg-clip-text text-transparent">Pixie</span>

<span class="bg-gradient-to-r from-teal-500 to-white bg-clip-text text-transparent">Playful Innovation</span>

<ul>
  <li v-click>Unconvential ideas are tomorrow's products</li>
  <li v-click>A mischievous team spirit</li>
  <li v-click>Challenging the status quo</li>
</ul>

---

## Time for Gods

<div grid="~ cols-3 gap-2" m="t-2">
  <div class="space-y-4" v-click>
    <h1>Poseidon</h1>
    <p>Braving the Storm</p>
    <img border="rounded" class="aspect-video" src="https://cdn.thecollector.com/wp-content/uploads/2022/02/jean-antoine-theodore-gudin-shipping-storm.jpg?width=1400&quality=55" alt="">
    <ul>
      <li>Olympian God of the Sea</li>
      <li>Exploring Unchartered Waters</li>
      <li>Adaptating to Emerging Technologies</li>
    </ul>
  </div>
  <div class="space-y-4" v-click>
    <h1>Pele</h1>
    <p>Crucible of Innovation</p>
    <img border="rounded" class="aspect-video object-cover object-top" src="https://miro.medium.com/v2/resize:fit:1024/1*f-AQYbRsRlKnnWfSbUQTVQ@2x.jpeg" alt="">
    <ul>
      <li>Polynesian Goddess of Volcanoes</li>
      <li>Creation and Destruction</li>
      <li>Fueling the Pursuit of Excellence</li>
    </ul>
  </div>
  <div class="space-y-4" v-click>
    <h1>Pangu</h1>
    <p>Forging Tomorrow</p>
    <img border="rounded" class="aspect-video object-cover object-top" src="https://mythologysource.com/wp-content/uploads/2020/11/pangu.png" alt="">
    <ul>
      <li>Chinese God of Creation</li>
      <li>Pushing the Boundaries of Possibility</li>
      <li>Collaboration and Meticulous Craftmanship</li>
    </ul>
  </div>
</div>

---

# Exploring the Digital Frontier

<div grid="~ cols-3 gap-4" m="t-20">
  <div v-click class="rounded-md p-4 bg-lime-900">
    <h3>Pioneer, Pathfinder</h3>
    <p>Trailblazingly Fast</p>
    <ul>
      <li>Mapping Uncharted Territories and Uncovering Opportunities</li>
      <li>Failing First so Others Wont</li>
    </ul>
  </div>
  <div v-click class="rounded-md bg-green-900 p-4">
    <h3>Pulse</h3>
    <p>The Heartbeat of Fast-Paced Innovation.</p>
    <ul>
      <li>Staying Ahead of the Curve.</li>
      <li>Rapid Response to Challenge and Opportunity.</li>
    </ul>
  </div>
  <div v-click class="rounded-md p-4 bg-cyan-900">
    <h3>Paradox</h3>
    <p>The Balance between Tradition and Innovation.</p>
    <ul>
      <li>Pragmatic Perfection</li>
      <li>Harmony in Contrast</li>
      <li>Pushing the Boundaries of Unconvential Thinking</li>
    </ul>
  </div>
</div>

---

# Mindmap

<div class="p-2 pt-0 -mt-4">
```mermaid
mindmap
  id((🏷️ Name <br /> Suggestons))
    (🐙 Animals)
      Podengo
      Platypus
      Porcupine
      Pangolin
      Panda
      Possum
    (🐦‍🔥 Mythical Beasts)
      Phoenix
      Pegasus
      Pixie
    (🙏 Gods)
      Poseidon
      Pele
      Pangu
    (💭 Concepts)
      Pioneer
      Pathfinder
      Pulse
      Pathfinder
```
</div>

---

# BONUS: Et Lynkurs i Nordmørsk

AKA: Ordbok for å forstå meg bedre på mandag.

<div class="grid grid-cols-4 gap-4 w-full mt-6">
  <WordCard word="Mjøk" translation="Melk" />
  <Youtube id="62Xgnx0oy-Q" class="aspect-video w-full rounded-md" />
  <WordCard word="Svåltinj/Svolta" translation="Sulten (hankjønn)/Sulten (hokjønn)" />
  <WordCard word="Sykjå, Akjå, Nikjå" translation="17, 18, 19" />
  <WordCard word="E tykkje ta e kjøle" translation="Jeg synes det er ugreit / forferdelig / urimelig /overdrevent / unødvendig" />
  <WordCard word="Bakels å græt" translation="Vafler med smørgrøt fra Sunndal" />
  <WordCard word="Hæmbakakak" translation="Hjemmebakt brød" />
  <WordCard word="Kjøle klar" translation="Veldig sliten" />
  <WordCard word="Farsk" translation="Ugagn. Feks. 'Guten e farskåt!'" />
  <WordCard word="Ketta" translation="Kiler. 'Ikkje kett me!!!'" />
  <WordCard word="Bleinkje" translation="Blinke. 'Sjå, den både bleinkje og skin!'" />
  <Youtube id="lczN213021Y" class="aspect-video w-full rounded-md" />
</div>