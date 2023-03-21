---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: true
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
css: unocss
title: Frontend News
favicon: 'https://www.testjg.es/wp-content/uploads/2020/07/cropped-test_fav-32x32.png'
---

# Frontend News

---
transition: slide-left
---

# Loads of news!

But first, some data:

<div class="flex justify-between">
<div class="flex flex-col">
<ul>
<v-clicks>
MantTest Web
<li>
<div v-if="$slidev.nav.clicks >= 1" class="flex items-center gap-5">
  Start date: <RelativeDate :date="'Thu Feb 10 09:40:58 2022 +0100'" />   
</div>
</li>
<li>
<div v-if="$slidev.nav.clicks >= 2" class="flex items-center gap-5">
  Contributors: <AnimatedNumber :n="3" />
</div>
</li>
<li>
<div v-if="$slidev.nav.clicks >= 3" class="flex items-center gap-5">
  Number of commits: <AnimatedNumber :n="4333" />
</div>
</li>
<li>
<div v-if="$slidev.nav.clicks >= 4" class="flex items-center gap-5">
  Azure DevOps
</div>
</li>
<li>
<div v-if="$slidev.nav.clicks >= 5" class="items-center gap-5">
  Work Items closed:
  <ul>
    <li>
      New: <AnimatedNumber :n="96" />
    </li>
    <li>
      In Planning: <AnimatedNumber :n="9" />
    </li>
    <li>
      Planned: <AnimatedNumber :n="2" />
    </li>
    <li>
      In Progress: <AnimatedNumber :n="16" />
    </li>
    <li>
      To Publish: <AnimatedNumber :n="1" />
    </li>
    <li>
      To Validate: <AnimatedNumber :n="114" />
    </li>
    <li>
      Closed: <AnimatedNumber :n="164" />
    </li>
  </ul>
</div>
</li>
</v-clicks>
</ul>
</div>
<div class="text-center">
<img v-if="$slidev.nav.clicks === 4" src="/kanban_devops.png" style="height: 21rem" class="rounded-xl shadow" />
<img v-else-if="$slidev.nav.clicks > 4" src="/cfd_devops.png" style="height: 21rem" class="rounded-xl shadow" />
<div v-if="$slidev.nav.clicks >= 4" class="mt-4">
Transparency, Inspection and Adaptation
</div>
</div>

</div>

---
transition: slide-left
layout: image-right
image: /breaking-news.webp
---

# News

<div class="flex flex-col justify-around h-[80%]">

<v-clicks>

<h2> New QA <fluent-mdl2:test-auto-solid class="inline mx-2 my-auto" /> </h2>

<h2> New Team Member <carbon:user-follow class="inline mx-2 my-auto" /> </h2>

<h2> New Project <fluent-mdl2:new-team-project class="inline mx-2 my-auto" /> </h2>

</v-clicks>

</div>

---
transition: slide-left
layout: image-right
image: http://uniknow.github.io/AgileDev/site/0.1.9-SNAPSHOT/images/testing-pyramid.png
---

<h1> New QA <fluent-mdl2:test-auto-solid class="inline mx-2 my-auto" /> </h1>

<v-clicks>

- Emphasis on Testing (core)

- Continuous Integration

- Acceptance Tests

- Automate most crucial User Journeys

</v-clicks>

---
transition: slide-left
layout: image-left
image: https://sportshub.cbsistatic.com/i/r/2023/01/12/3c069acc-8ea9-4117-87b6-03429c7157a3/thumbnail/1200x675/6a7a0f70cb152d8f4c80fe24724d9c37/enigma69.jpg
---

<h1> New Team Member <carbon:user-follow class="inline mx-2 my-auto" /> </h1>

<v-clicks>

- Frontender

- Vue enthusiast

- Iris focused

- Incorporation mid April

</v-clicks>

---
transition: slide-left
---

<h1> New Project <fluent-mdl2:new-team-project class="inline mx-2 my-auto" /> </h1>

<div class="flex justify-around h-full">
<div class="flex flex-col">

<v-click>

### What?

</v-click>

<div class="flex items-center gap-4 mt-2 mb-8">
<img v-click src="/mt-icon.svg" style="height: 5rem; width: 5rem">
<img v-click="2" src="/iris-icon.svg" style="height: 5rem; width: 5rem">
<fluent-mdl2:unknown-solid v-click="14" style="height: 5rem; width: 5rem;" />
</div>

<v-click>

### How?

</v-click>

<v-clicks>

* Monorepo setup
* NX
* Azure DevOps Teams

</v-clicks>


</div>

<div class="flex flex-col">
<v-click>

### Why?

</v-click>

<v-clicks>

* Code reuse
* Fast development
* Common practices
* Avoid context switching
* Design System?

</v-clicks>

</div>

</div>

---
transition: slide-left
---

<div class="absolute top-0 right-0 bot-0 w-full h-full">
<iframe src="/graph.html" class="h-full w-full" frameborder="0"></iframe>
</div>

---
transition: slide-up
---

<h1> New Project <fluent-mdl2:new-team-project class="inline mx-2 my-auto" /> </h1>

<div v-click-hide v-if="$slidev.nav.clicks < 1" class="flex h-[80%] w-full justify-around items-center">
<Tweet id="7269997868" />
</div>

<div class="flex h-[80%] w-full justify-around items-center">
<img v-click="1" class="h-64" src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/Sekhmet.svg/1200px-Sekhmet.svg.png" />
<img v-click="3" class="h-64" src="https://images.fineartamerica.com/images/artworkimages/mediumlarge/2/incan-gods-the-great-creator-viracocha-on-white-leather-serge-averbukh.jpg" />
<img v-click="2" class="h-64" src="https://images-na.ssl-images-amazon.com/images/I/91Oj%2BsDhfpL._SL1500_.jpg" />
<img v-click="4" class="absolute h-72 animate-bounce" src="https://imgix.bustle.com/rehost/2016/9/13/83c0093d-4f3e-4a6b-ae66-994db94f8900.jpg?w=1200&h=630&fit=crop&crop=faces&fm=jpg" />
</div>


---
transition: fade-in
layout: fact
---

# Tatu

---
transition: fade-out
layout: iframe-right
url: https://sketchfab.com/models/ee81451e0a814207be57e522effd70fd/embed?autospin=1&autostart=1&ui_hint=0&ui_theme=dark&dnt=1
preload: true
---

<h1> Project Tatu <game-icons:armadillo class="inline mx-2 my-auto text-orange-400 animate-flash" /> </h1>

<ul class="gap-5 flex flex-col">

<v-clicks>
<li>
Robust
</li>
<li>
Bugs for breakfast <fluent-mdl2:bug class="text-red" />
</li>
<li>
Habitat Engineer
</li>

</v-clicks>

</ul>

---
layout: center
class: text-center
---

## Thanks 🎉
