# Nomes web app

<a href="https://nomes.info">

  ![Logo]
</a>

## Table of Contents

- [Introduction]
- [Demo]
- [Screenshots & PageSpeed Insights scores]
- [Built With]
- [Contributing]
- [License]


## Intro

✨🙋‍♀️ Meaning, origin, popularity and curiosities of names web app (Portuguese). Linux, Apache, MariaDB, PHP stack.


## Demo
[Nomes.info]


## Screenshots & PageSpeed Insights scores

### Homepage (💻 desktop, ☀ light mode)
<img align="center" src="/documentation/screenshots/home-desktop.jpg" height="500"/>

Starts with an hero section with search bar, followed by a search by initial, trending topics, top 10 most popular male and female names and last searched names.
<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score home desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score home mobile]
</details>
</details>

### Topic page (💻 desktop, ☀ light mode)
<img align="center" src="/documentation/screenshots/tema-desktop.jpg" height="500"/>

Listing of names related to a topic. In the example the topic is the top trending names. Other topics are the origin or language of the name.

<!-- On desktop the viewport width is shared between the names listing and the aside containing the top trending names of the given topic and other trending topics. On the other hand, on mobile devices both sections are full width with the names listing below the aside which contains a smaller top trending and no related topics as space is scarce in these devices. -->
<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score topic desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score topic mobile]
</details>
</details>

### Name's initial/gender page (💻 desktop, ☀ light mode)
<img align="center" src="/documentation/screenshots/inicial-genero-desktop.jpg" height="500"/>

This page contains the listing of names by initial and/or gender.
<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score initial desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score initial mobile]
</details>
</details>

### Trending topics page (💻 desktop, ☀ light mode)
<img align="center" src="/documentation/screenshots/temas-populares-desktop.jpg" height="500"/>

Here are listed the most popular name topics.
<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score trending topics desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score trending topics mobile]
</details>
</details>

### Search page (💻 desktop, 🌙 dark mode)
<img align="center" src="/documentation/screenshots/pesquisa-desktop.jpg" height="500"/>

Search results lead either directly to the matching name or, as shown above, to a listing of lookalike search results.
<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score search desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score search mobile]
</details>
</details>

### Name page (📱 mobile, 🌙 dark mode)
  <img width=29% src="/documentation/screenshots/nome-mobile-1.jpg"/>&nbsp;&nbsp;<img width=29% src="/documentation/screenshots/nome-mobile-2.jpg"/>&nbsp;&nbsp;<img  width=29% src="/documentation/screenshots/nome-mobile-3.jpg"/>


<details open>
  <summary>PageSpeed Insights scores</summary>
<details open>
  <summary>Desktop</summary>
  <br/>

  ![PageSpeed Insights score name desktop]
</details>

<details open>
  <summary>Mobile</summary>
  <br/>

  ![PageSpeed Insights score name mobile]
</details>
</details>


## Built With
- Linux, Apache, MariaDB, PHP stack
- [Composer](https://getcomposer.org/) - A Dependency Manager for PHP
- [Bootstrap](https://getbootstrap.com) - CSS framework
- [scssphp](https://github.com/scssphp/scssphp) - Compiler for SCSS
- [matthiasmullie/minify](https://github.com/matthiasmullie/minify) - CSS & JS minifier
- [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) - Browser API which observes the intersection between elemets and viewport. Used in this project for lazy load with buffer, infinite scroll with buffer, scroll back to top, and animations
- [PHP Image](https://github.com/kus/php-image) - Wrapper for PHP's GD Library for easy image manipulation. Used in this project to create dinamic photos for each name


## Contributing

Contributions are welcome! Follow the contribution guidelines.

Wish there was another feature? Feel free to open an [feature request issue](/../../issues/new?assignees=Correia-jpv&labels=enhancement&template=feature-request.md&title=%5BREQUEST%5D) with your suggestion!

If you find a bug, kindly open an [bug report issue](/../../issues/new?assignees=Correia-jpv&labels=bug&template=bug_report.md&title=%5BBUG%5D) as described in the contribution guidelines.


## License
[Licensed Under MIT]

<!-- Links -->
  <!-- Header hero image -->
  [Logo]:/documentation/screenshots/devices-mockup.jpg

  <!-- Table of Contents -->
  [Introduction]:#Intro
  [Demo]:#demo
  [Screenshots & PageSpeed Insights scores]:#Screenshots--PageSpeed-Insights-scores
  [Built With]:#built-with
  [Contributing]:#contributing
  [License]:#License

  <!-- Demo -->
  [Nomes.info]:https://nomes.info

  <!-- PSI scores -->
  [PageSpeed Insights score home desktop]:./documentation/reports/psi-audit-desktop-1.svg
  [PageSpeed Insights score home mobile]:./documentation/reports/psi-audit-mobile-1.svg
  [PageSpeed Insights score topic desktop]:./documentation/reports/psi-audit-desktop-2.svg
  [PageSpeed Insights score topic mobile]:./documentation/reports/psi-audit-mobile-2.svg
  [PageSpeed Insights score initial desktop]:./documentation/reports/psi-audit-desktop-5.svg
  [PageSpeed Insights score initial mobile]:./documentation/reports/psi-audit-mobile-5.svg
  [PageSpeed Insights score trending topics desktop]:./documentation/reports/psi-audit-desktop-3.svg
  [PageSpeed Insights score trending topics mobile]:./documentation/reports/psi-audit-mobile-3.svg
  [PageSpeed Insights score search desktop]:./documentation/reports/psi-audit-desktop-4.svg
  [PageSpeed Insights score search mobile]:./documentation/reports/psi-audit-mobile-4.svg
  [PageSpeed Insights score name desktop]:./documentation/reports/psi-audit-desktop-6.svg
  [PageSpeed Insights score name mobile]:./documentation/reports/psi-audit-mobile-6.svg

  <!-- License -->
  [Licensed Under MIT]:/LICENSE
