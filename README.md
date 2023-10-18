# :zap: HTML CSS Card

* Optimised HTML-CSS contact card to achieve a perfect lighthouse score
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/html-css-card?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/html-css-card?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/html-css-card?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/html-css-card?style=plastic)

## :page_facing_up: Table of contents

* [:zap: HTML CSS Card](#zap-html-css-card)
  * [:page\_facing\_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal\_strength: Technologies](#signal_strength-technologies)
  * [:floppy\_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status \& To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file\_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Built with just HTML and CSS
* Nearly perfect performance, Perfect scores on accessibility, best practices and SEO.
* CSS is minimised to reduce initial render/First Contentful Paint time.

## :camera: Screenshots

![Example screenshot](./imgs/card.png).

## :signal_strength: Technologies

* [HyperText Markup Language HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML)
* [Cascading Style Sheets CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) styling
* [JPG to WebP Converter](https://www.freeconvert.com/jpg-to-webp) to create new image format that results in a higher Lighthouse score
* [PurifyCSS Online](https://purifycss.online/) - remove unused CSS code from your stylesheets
* [Online CSS Minifier Tool and Compressor](https://www.toptal.com/developers/cssminifier)

## :floppy_disk: Setup

* Open index.html using [Visual Studio Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). Changes are updated automatically on server.

## :computer: Code Examples

* index.html extract showing how new format webp images are marked up in HTML

```html
      <picture>
        <source type="image/webp" width="340" height="227" srcset="assets/mountains.webp" alt="Mountains"
          loading="lazy" />
        <source type="image/jpeg" width="340" height="227" srcset="assets/mountains.jpg" alt="Mountains"
          loading="lazy" />
        <img src="assets/mountains.jpg" intrinsicsize="340x227" width="340" height="227" alt="Mountains"
          loading="lazy" />
      </picture>
```

## :cool: Features

* Excellent lighthouse score

## :clipboard: Status & To-Do List

* Status: Working
* To-Do: Correctly size image. Improve card content.

## :clap: Inspiration

* [Anna Monus: 9 tricks to eliminate render blocking resources](https://blog.logrocket.com/9-tricks-eliminate-render-blocking-resources/)

## :file_folder: License

* This project is licensed under the MIT License - see the LICENSE file for details.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: `gomezbateman@yahoo.com`
