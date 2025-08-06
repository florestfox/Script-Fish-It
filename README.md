*don't forget to give this repository stars!*

<a name="readme-top"></a>

<br />
<div align="center">
  <a href="https://github.com/florestfox/Script-Fish-It">
    <img src="https://telegra.ph/file/10715f5ad0b92c955b69c.png">
  <h3 align="center">Script Fish It</h3>
  <p align="center">
    Created By Bsnl_18
 <p/>
</div>

<img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges"/>
<a href="https://github.com/florestfox/Script-Fish-It"><img src="https://img.shields.io/github/watchers/florestfox/Domge_MD.svg"</a>
<a href="https://github.com/florestfox/Script-Fish-It"><img src="https://img.shields.io/github/stars/florestfox/Domge_MD.svg"</a>
<a href="https://github.com/florestfox/Script-Fish-It"><img src="https://img.shields.io/github/forks/florestfox/Domge_MD.svg"</a>
<a href="https://github.com/florestfox/Script-Fish-It"><img src="https://img.shields.io/github/repo-size/florestfox/Domge_MD.svg"></a>
<a href="https://github.com/florestfox/Script-Fish-It/issues"><img src="https://img.shields.io/github/issues/florestfox/Domge_MD"></a>
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png"/>

JOIN WITH MY CHANNEL FOR MORE INFORMATION UPDATE

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=fff&style=flat)](https://whatsapp.com/channel/0029Vaeb4ZhG3R3gkD4DX414)

### About
This Script created by Bsnl_18, a beginner programmer. This Script was created with the aim of making everyday activities easier, I am very grateful And can't forget the support you have given me all this time
 
## Types and Programming Languages 

This script is of the Lua type

### Tutorial on How to Use the Send Button Function
<details close="close">
<summary><i><b>Send Button Message</b></i></summary>

***
```js
/**
  * ©Nanda-Dev
  **/
let buttons = [{ text: '', id: '' }]

conn.sendButtonMsg(jid, 'text', 'footer', buttons, quoted)
// Or
conn.sendButtonMsg(jid, 'text', 'footer', [{ text: '', id: '' }], quoted)
```
***
</details></details>
<details close="close"><summary><i><b>Send Button Message With Image</b></i></summary>

***
```js
/**
  * ©Nanda-Dev
  * The imageUrl part must be a string of url
  **/
let buttons = [{ text: '', id: '' }]
conn.sendButtonImg(jid, 'text', 'footer', buttons, imageUrl, quoted)
// or
conn.sendButtonImg(jid, 'text', 'footer', [{ text: '', id: '' }], imageUrl, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send List Message</b></i></summary>

  ***
```js
/**
  * ©Nanda-Dev
  **/
let sections = [{
  title: 'title',
  rows: [{
  header: 'header',
  title: 'title',
  description: 'description',
  id: 'id' 
}] 
}]

conn.sendListMsg(jid, 'text', 'footer', 'titleButton', sections, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send List Message With Image</b></i></summary>

***
```js
/**
  * ©Nanda-Dev
  * The imageUrl part must be a string of url
  **/
let sections = [{
  title: 'title',
  rows: [{
  header: 'header',
  title: 'title',
  description: 'description',
  id: 'id' 
}] 
}]

conn.sendListImg(jid, 'text', 'footer', 'titleButton', sections, imageUrl, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send Button Card</b></i></summary>

***
```js
/**
  * ©Nanda-Dev
  * The imageUrl part must be a string of url
  * [cards] Must follow the example below
  * type = ['buttons', 'url']
  **/
  let cards = [
    {
      header: 'header',
      body: 'body',
      footer: 'footer',
      imageUrl: 'string',
      buttons: [
        {
          type: 'url',
          text: "text of buttons url",
          url: "https://example.com"
        },
        {
          type: 'buttons',
          text: "text of buttons",
          id: "quick_reply_id_1"
        }
      ]
    }
  ];

  await conn.sendButtonCard(jid, 'text', 'footer', cards, quoted);
```
***
</details></details>

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact Me
If you find a bug/error in the script, you can contact me directly via:

[On WhatsApp](https://wa.me/6285812273035)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Javascript.js]: https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square
[Javascript-url]: https://nodejs.org
