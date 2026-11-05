<!-- PROJECT LOGO -->
<div align="center">
  <img src="public/img/Dunk Sb Pixel Art/Silver Box/takashi_rotate.png" alt="Logo" width="80" height="43">

  <h3 align="center" style="font-size: 2.1em; font-weight: bolder;">dunkhead</h3>

  <p align="center">
    Exploring the history, culture, and releases of Nike Dunk SBs.
    <br />
    <br />
    <a href="https://github.com/ninoestrada/dunkhead/issues/new?labels=bug&template=bug_report.md">Report Bug</a>
    ·
    <a href="https://github.com/ninoestrada/dunkhead/issues/new?labels=enhancement&template=feature_request.md">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->

## 📖 About the Project

![dunkhead home](./public/img/Screenshots/dunkhead-home.png)

**dunkhead** is a web application dedicated to the history, culture, and releases of Nike Dunk SBs. It brings together a curated sneaker collection, release news, and information about sneaker culture in an interactive, retro-inspired experience.

The project was inspired by an interest in sneakers and their connection to skateboarding, art, and streetwear. Rather than focusing on buying and selling sneakers, dunkhead explores their history and cultural significance through a creative, visually engaging interface.

### ✨ Features

- Browse a curated collection of Nike Dunk SBs, featuring sneaker artwork, nicknames, and box designs.
- Explore upcoming, popular, and past sneaker releases using information retrieved from external sources.
- Discover information about Nike Dunk SB history, terminology, and skate shops.
- Explore animated sneaker collections and interactive shoe previews through a retro-inspired interface.

### **🛠️ Tech Stack**

|                    Frontend                     |                 Template Engine                 |                   Backend                    |
| :---------------------------------------------: | :---------------------------------------------: | :------------------------------------------: |
| [![JavaScript][JavaScript.com]][JavaScript-url] | [![Handlebars][Handlebars.com]][Handlebars-url] |    [![Node.js][Node.js.com]][Node.js-url]    |
|       [![JQuery][JQuery.com]][JQuery-url]       |                                                 |    [![Express][Express.com]][Express-url]    |
|  [![Bootstrap][Bootstrap.com]][Bootstrap-url]   |                                                 |    [![Mongodb][Mongodb.com]][Mongodb-url]    |
|       [![Nescss][Nescss.com]][Nescss-url]       |                                                 |  [![Mongoose][Mongoose.com]][Mongoose-url]   |
|          [![GSAP][GSAP.com]][GSAP-url]          |                                                 | [![Puppeteer][Puppeteer.com]][Puppeteer-url] |
| [![Animatecss][Animatecss.com]][Animatecss-url] |                                                 | [![SneaksAPI][SneaksAPI.com]][SneaksAPI-url] |
|                                                 |                                                 |  [![MomentJS][MomentJS.com]][MomentJS-url]   |

<!-- GETTING STARTED -->

## 📦 Getting Started

### **💾 Installation**

1. Clone the repository
   ```sh
   git clone https://github.com/ninoestrada/dunkhead.git
   cd dunkhead
   ```
2. Install the dependencies
   ```sh
   npm install
   ```
3. Configure the MongoDB connection in modules/credentials.js using the mongo.connectionString setting. Keep database credentials private and out of version control.
4. Populate the database with the initial sneaker collection:
   ```sh
   node database.js
   ```

### **▶️ Running the Program**

```sh
node server.js
```

The application runs on port 3000 by default, or the port specified by the PORT environment variable.

The news page requires an internet connection to retrieve sneaker release information from KicksonFire.

<!-- LICENSE -->

## 📜 License

Distributed under the MIT License. See [`LICENSE.txt`](LICENSE.txt) for more information.

<!------- MARKDOWN LINKS & IMAGES ------->

[Button Click]: https://img.shields.io/badge/Click_Me!-37a779?style=for-the-badge
[JavaScript.com]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[JavaScript-url]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
[Handlebars.com]: https://img.shields.io/badge/Handlebars-FC8019?style=for-the-badge&logo=handlebars
[Handlebars-url]: https://handlebarsjs.com/
[Node.js.com]: https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white
[Node.js-url]: https://nodejs.org/en
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com/
[Express.com]: https://img.shields.io/badge/Express.js-404D59?style=for-the-badge
[Express-url]: https://expressjs.com/
[Nescss.com]: https://img.shields.io/badge/NES.css-100000?style=for-the-badge&logo=nes
[Nescss-url]: https://nostalgic-css.github.io/NES.css/
[Mongodb.com]: https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white
[Mongodb-url]: https://www.mongodb.com/
[Mongoose.com]: https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white
[Mongoose-url]: https://mongoosejs.com/
[Animatecss.com]: https://img.shields.io/badge/Animate.css-430098?style=for-the-badge&logo=Animatecss
[Animatecss-url]: https://animate.style/
[SneaksAPI.com]: https://img.shields.io/badge/Sneaks%20API-30363D?style=for-the-badge&logo=SneaksAPI
[SneaksAPI-url]: https://github.com/druv5319/Sneaks-API
[Puppeteer.com]: https://img.shields.io/badge/Puppeteer-21C25E?style=for-the-badge&logo=Puppeteer
[Puppeteer-url]: https://pptr.dev/
[GSAP.com]: https://img.shields.io/badge/GSAP-000000?style=for-the-badge&logo=GSAP
[GSAP-url]: https://gsap.com/
[MomentJS.com]: https://img.shields.io/badge/Moment.js-00C7B7?style=for-the-badge&logo=MomentJS
[MomentJS-url]: https://momentjs.com/
