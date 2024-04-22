<h2>Justine's Portfolio </h2>

<pre>
⭐ 
Bienvenue sur mon GitHub ! Ici, vous trouverez un projet qui incarne ma passion pour la création et l'innovation dans le domaine de la technologie. Explorez ce repository pour découvrir en détail un projet sur lequel j'ai investi temps et énergie, mettant en œuvre mes compétences et ma créativité pour aboutir à un résultat significatif. Que vous soyez intéressé par la technologie sous-jacente, curieux de voir mon processus de développement ou simplement à la recherche d'inspiration, je vous invite à plonger dans ce projet et à en découvrir les détails. Merci de votre visite, et n'hésitez pas à me contacter pour toute question ou commentaire sur ce projet ! ⭐ 
</pre>

<br/>

<h3>:eye_speech_bubble: Live demo</h3>

<img width="100%" src="https://justinetdrs.github.io/my-portfolio/" alt="react frontend dev portfolio preview"/>

<img width="100%" src="https://github.com/Dorota1997/react-frontend-dev-portfolio/blob/images/images/react_portfolio_about.png" alt="react frontend dev portfolio preview"/>

<h3>:books: Getting started</h3>

1. Clone or fork project.
2. Install required dependencies with `npm install`.
3. Remove `homepage` entirely from `package.json` or set it to single dot. 

```
// package.json
{
  "name": "react-frontend-dev-portfolio",
  "version": "0.1.0",
  "private": true,
  "dependencies": {
  ...
}
```

4. `npm start` project and customize it.
5. Deploy on github-pages using `npm run deploy` command.

<pre>
⚠️ Note that:
- if you want to have portfolio on different repository than `{username}.github.io`, 
set `homepage` in `package.json` to `https://{username}.github.io/{repository-name}/` 
before deploying portfolio.
- if you want to run it locally with <strong>npm run start</strong>, make sure that you have edited 
homepage property or json data won't load.
</pre>

<h3>:star: Inspirations</h3>

<a href="https://github.com/stephane-monnot/react-vertical-timeline">React Vertical Timeline</a> <br/>
<a href="https://github.com/rcaferati/react-awesome-slider">React Awesome Slider</a> <br/>
<a href="https://github.com/markusenglund/react-switch">React Switch</a> <br/>
<a href="https://github.com/catalinmiron/react-typical">React Typical</a> <br/>
<a href="https://iconify.design/icon-sets/?query=angular">Iconify Design</a> <br/>
<a href="https://www.w3docs.com/snippets/css/how-to-create-polaroid-image-with-css.html#">Polaroid effect</a> <br/>
<a href="https://tholman.com/github-corners/">GitHub Ref Corner</a>

<h3>:memo: Changelog</h3>
<details>
<summary>[ 05.03.2022, contributor: <a href="https://github.com/mangelarilla">@mangelarilla</a> ]</summary>
<pre>
- update DevIcon stylesheet to latest one
</pre>
</details>
<details>
<summary>[ 03.10.2021, contributor: <a href="https://github.com/shahednasser">@shahednasser</a> ]</summary>
<pre>
- updated sass dependency.
</pre>
</details>
<details>
<summary>[ 26.05.2021, contributor: <a href="https://github.com/DavidMatalik">@DavidMatalik</a> ]</summary>
<pre>
- removed nonexisting logos references: logo192 and logo512.  
</pre>
</details>
<details>
<summary>[ 17.01.2021, contributor: <a href="https://github.com/igorperic17">@igorperic17</a> ]</summary>
<pre>
- wrapped the Typical component into a fixed height div due to the bad transitions for a brief moment between two titles when the string is empty (the content bellow jumps up-down very quickly).
- removed the title from the page document.title due to the increased title length.
</pre>
</details>
<details>
<summary>[ 30.11.2020, contributor: <a href="https://github.com/dorota1997">@dorota1997</a> ]</summary>
<pre>
- updated readme section
- fixed problem of json files not being read
</pre>
</details>
<details>
<summary>[ 29/30.11.2020, contributor: <a href="https://github.com/trolit">@trolit</a> ]</summary>
<pre>
- changed resume files names to more "universal"
- moved languages names to global variables
- moved section names to json files
- added target="_blank" for footer links
- added startDate property for projects
- excluded common json data to portfolio_shared_data file
- added header section height calculation based on formula: window.innerHeight - 140
- small changes to vertical timeline item (color/font-size)
- project link in modal is not shown if empty
- changed slider preloader bar color
- wrapped each skill into tile
- footer fullname is fetched from json now
- added mising "px" for avatar in About.js component
- updated json files content
- page title is fetched from json data
- added GitHub reference corner "label"
- edited page meta
- added margin, padding 0 for html tag
- excluded light theme ref from theme-dark file
- slightly changed Header.js section look
- made some changes to App.js to apply global variables/shared json etc.
- centered fullname/pos/theme toggler in Header section
</pre>
</details>
