## Techniki Internetowe, 2018

> *Uważaj na człowieka, którego nie interesują szczegóły.*
>
> — William Feather

### Front-End vs. Back-End Development

* [Back-End Developer Interview Questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions).
* [Front-End Interview Handbook](https://github.com/yangshun/front-end-interview-handbook).

Front-End – podstawy:

* [Learn web development](https://developer.mozilla.org/en-US/docs/Learn) – MDN Web Docs.
* [Front-End Checklist](https://github.com/thedaviddias/Front-End-Checklist) –
  for modern websites and meticulous developers.


### Jak napisać poprawne README

* [A template to make good README.md](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
* Uwagi do naszych README: używamy notacji Markdown albo AsciiDoctor,
  wpisujemy swoje dane (imię + nazwisko, studia zaoczne).

Zapoznać się z notacją Markdown:

* [GitHub Flavored Markdown](http://guides.github.com/overviews/mastering-markdown/),
  [Mastering Markdown](http://guides.github.com/overviews/mastering-markdown/) i
  [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

i AsciiDoc:

* [AsciiDoctor](http://asciidoctor.org/) – a fast text processor & publishing
  toolchain for converting AsciiDoc to HTML5, DocBook & more.

W repozytoriach z rozwiązaniami zadań, w pliku _README.md_ (Markdown)
i _README.adoc_ (AsciiDoctor) krótko opisać rozwiązanie każdego zadania.

<!--
  Przeczytać [AsciiDoc New tables]( http://www.methods.co.nz/asciidoc/newtables.html).
-->

### Wykłady

1. [My Gulp 101](https://github.com/h5c3j/my_gulp_101).
    1. [Modern CSS & JavaScript for Dinosaurs](https://github.com/h5c3j/my_gulp_101/tree/master/static).


### Zadania na zaliczenie

#### 1. [deadline 16.03.2018]

1. Zapoznać się z programem [gulp](http://gulpjs.com) ułatwiającym pracę
  z projektami HTML+CSS+JavaScript.
2. Do kodu [pierwszej strony WWW](http://info.cern.ch/hypertext/WWW/TheProject.html)
  dodać mapkę okolic CERN. Użyć ostatniej wersji biblioteki
  [Leaflet](http://leafletjs.com); zob. też
  [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github).

Livereload z _Browsersync_

W pliku [gulpfile.js](https://github.com/h5c3j/my_gulp_101/blob/master/gulpfile.js)
domyślne zadanie (ang. _task_) uruchamia tzw. _livereload_ korzystające z
[Browsersync](https://www.browsersync.io/docs/gulp).
Plik _gulpfile.js_ zawiera kilka innych zadań: html, images, sass, lint.
Ich funkcjonalnośc jest minimalna. Należy uzupełnić ich funkcjonalność.

Zamienić zawartość katalogu [src](https://github.com/h5c3j/my_gulp_101) na swoją.
Umieścić w niej pliki z punktu 2. powyżej.
Proces dodawania mapki powinien być zautomatyzowany za pomocą programu _gulp_.

Przykładowa lista rzeczy poprawiających funkcjonalność _gulpfile.js_:

- [ ] skorzystać z transpliacji: Babel + ES6
- [ ] concat and minify assets SCSS/CSS
- [ ] skorzystać z [Webpack](https://webpack.js.org)
- [ ] images management
- [ ] szablony HTML
- [ ] copy only changed files
- [ ] [delete generated folders](https://github.com/gulpjs/gulp/blob/master/docs/recipes/delete-files-folder.md)
- [ ] [gulp-markdown](https://www.npmjs.com/package/gulp-markdown)
- [ ] [gulp-asciidoctor](https://github.com/asciidoctor/gulp-asciidoctor)


### 2. [deadline 24.03.2018]

Moje portfolio 5 × 6.

* Co to jest portfolio? Przykład [David Cam. Strona Fotografa](https://www.wix.com/website-template/view/html/1264/?siteId=4cc25780-53f1-4094-8612-14e29d393474&metaSiteId=94f3e1f0-4ce3-429c-8aff-0907cf7a9e76&originUrl=https%3A%2F%2Fpl.wix.com%2Fwebsite%2Ftemplates%2Fhtml%2Fportfolio-cv).


### 3. [deadline 14.04.2018]

Przygotować stronę z kilkoma tabelkami.

1. Dodać responsywność do tabelek.

    - [Responsive Tables](https://codepen.io/collection/AdGVYP/).

1. Użyć Grid Layout.

    - [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/).
    - [Grid Garden](http://cssgridgarden.com)

1. O ile jest to możliwe użyć Flexible Box Layout; jeśli nie – napisać dlaczego.

    - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).
    - [Flexbox Froggy](http://flexboxfroggy.com/).

W HTML tabelę budujemy z następujących elementów: *table*, *tr*, *td*,
*caption*, *thead*, *tbody*, *tfoot*, *colgroup*, *col* (9 znaczników)
oraz z dwóch atrybutów *colspan* i *rowspan* (2 atrybuty).
W tabelach należy użyć **wszystkich** wymienionych elementów i atrybutów.

Przeczytać artykuł Matthew Ström’a
[Design Better Data Tables](https://medium.com/mission-log/design-better-data-tables-430a30a00d8c).
W swoich tabelkach zastosować się do „3½ simple rules” z tego artykułu.


### JavaScriptowe inspiracje [deadline 12.05.2018, projekt zespołowy]

> [presentations/projects/solutions needs] <br>
> … words, sentences & clarity, honesty
>
> [Joseph Blitzstein](https://youtu.be/dzFf3r1yph8) na Think Big 4.

Przygotować projekt inspirując się projektami ze strony
[30 Day Vanilla JS Coding Challenge](https://javascript30.com).

* Link do [repozytorium z _starter files_](https://github.com/wesbos/JavaScript30).


<!--

### 4. [deadline]

Responsywne obrazki

  - [Responsive Images Community Group](https://responsiveimages.org).

Przygotować stronę z kilkoma obrazkami następnie dodać responsywność
do obrazków. Jak responywność wpływa na czas ładowania strony?


#### 9. [deadline 6.04.2017] (GeoJSON)

Przejrzeć dokumentację [_GeoJSON_](http://geojson.org/). Napisać
kilka geojsonów i przetestować je na tej stronie:
[Simply edit GeoJSON map data](http://geojson.io).

Utworzyć stronę z mapką korzystającą biblioteki [Leaflet](http://leafletjs.com/).
W kodzie mapki użyć następujących [Geometry Objects](http://geojson.org/geojson-spec.html#geometry-objects): _Point_, _LineString_ i _Polygon_.

* Przeczytać rozdział [Websites. Abandon five obsolete habits](http://practicaltypography.com/websites.html)
  z książki M. Butterick’a [Practical Typography](http://practicaltypography.com);
  zob. też [Google Fonts](https://fonts.google.com/?subset=latin-ext).
* Zapoznać się z elementami, atrybutem i formatem:
  - [figure](http://caniuse.com/#search=figure), [picture](http://caniuse.com/#search=picture)
  - [srcset](http://caniuse.com/#search=srcset)
  - [webfont](http://caniuse.com/#search=webfont)
* [<picture> Element Sample](https://googlechrome.github.io/samples/picture-element/)
* [:japanese_ogre: – dummy image generator](http://satyr.io) –
  może ułatwić przygotowanie prototypu strony z responsywnymi obrazkami

----

4\. [deadline 06.05.2017]

1. Przygotować stronę ze wzorami matematycznymi.
Matematykę na stronach wpisać w notacji
[MathJax](http://docs.mathjax.org/en/latest/index.html).
2. Użyć modułu [CSS Grid Layout](https://www.w3.org/TR/css3-grid-layout/);
zob. też [Grid Garden](http://cssgridgarden.com/).

Przykładowe repozytorium z GitHub Pages + MathJax –
[RedQueen: An Online Algorithm for Smart Broadcasting in Social Networks](http://learning.mpi-sws.org/redqueen/).
W stopce u dołu strony linki do repozytorium z kodem źródłowym.
-->

<!--
[Carnegie, Mellon](https://github.com/brendano/ark-tweet-nlp/). [tChat](http://www.cs.cmu.edu/~ark/TweetNLP/).

5\. [GitHub Pages](https://pages.github.com) |
  [About GitHub Pages and Jekyll](https://help.github.com/articles/about-github-pages-and-jekyll/) |
  [Firebase](https://firebase.google.com).

W stronach przygotowanych w pkt. 1. (lub nowych) wykorzystać
jeden z frameworków wymienionych poniżej:

* [Bootstrap](http://getbootstrap.com) –
  the most popular HTML, CSS, and JS framework for developing
  responsive, mobile first projects on the web.
* [Material Design Lite](http://www.getmdl.io/).
  Material Design Lite lets you add a Material Design look and feel to your
  websites. It doesn’t rely on any JavaScript frameworks and aims to optimize for
  cross-device use, gracefully degrade in older browsers, and offer an experience
  that is immediately accessible.

-->

<!--
#### Inspiracje [WebAssembly](http://webassembly.org/)

. [WebAssembly 101: a developer's first steps](http://blog.openbloc.fr/webassembly-first-steps/)
. [React](https://facebook.github.io/react/index.html) –
  . [Getting Started](https://facebook.github.io/react/docs/getting-started.html),
  . [Tutorial](https://facebook.github.io/react/docs/tutorial.html),
  . [React for Beginners](https://reactforbeginners.com/).
-->


## JavaScript 2018 → ∞

- Marijn Haverbeke.
  [Eloquent JavaScript](http://eloquentjavascript.net/)
- Kyle Simpson.
  [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS);
  [polskie tłumaczenia](http://helion.pl/search?szukaj=Simpson)
- Nicholas C. Zakas.
  [Understanding ECMAScript 6](https://leanpub.com/understandinges6/read/)
- John Resig.
  - [Learning Advanced JavaScript](http://ejohn.org/apps/learn/)
  - [Secrets of the JavaScript Ninja, Second Edition](https://www.manning.com/books/secrets-of-the-javascript-ninja-second-edition)
- [JavaScript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference) –
  Mozilla Developer Network (MDN)

ES6+

- Sindre Sorhus.
  [ES.next showcase](https://github.com/sindresorhus/esnext-showcase)
- Matt Greer.
  [JavaScript Promises ... In Wicked Detail](http://mattgreer.org/articles/promises-in-wicked-detail/)
- Aidan Feldman.
  [Advanced JavaScript](http://advanced-js.github.io/deck/)
- David Leonard. [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet)
– [Minimalist examples of ES6 functionalities](https://github.com/hemanth/paws-on-es6)


## CSS3 2018 → ∞

- [Less](http://lesscss.org)
- [Sass](http://sass-lang.com)

Small frameworks:

- [Bulma](http://bulma.io/) – Sass based
