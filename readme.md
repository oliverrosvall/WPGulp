<div align="center">


  <small><p><em>๐ Learn to <a href="https://nodecli.com/?utm_source=github.com&utm_medium=referral&utm_campaign=ahmadawais/WPGulp" rel="nofollow">build CLI DevTools</a>, like WPGulp with me at <a href="https://nodecli.com/?utm_source=github.com&utm_medium=referral&utm_campaign=ahmadawais/WPGulp">NodeCLI.com</a>.</em></p></small>
  <p><strong>Only works with Node.js < v14</strong></p>

  <img src="https://a.cl.ly/o0uy14NY/c" alt="WP Gulp ยท WordPress Gulp" />

  <h1><code>WordPress Gulp Workflow</code></h1>

[![GitHub](https://img.shields.io/wordpress/v/akismet.svg?colorA=D14543&colorB=21759B&maxAge=2592000&style=flat&label=WordPress)](https://github.com/ahmadawais/WPGulp/)
[![emoji-log](https://img.shields.io/badge/๐%20Emoji-Log-gray.svg?colorA=D14543&colorB=21759B&style=flat)](https://github.com/ahmadawais/Emoji-Log/) [![GitHub stars](https://img.shields.io/github/stars/ahmadawais/WPGulp.svg?style=social&label=Stars)](https://github.com/ahmadawais/WPGulp/stargazers) [![GitHub followers](https://img.shields.io/github/followers/ahmadawais.svg?style=social&label=Follow)](https://github.com/ahmadawais?tab=followers)  [![Tweet for help](https://img.shields.io/twitter/follow/mrahmadawais.svg?style=social&label=Tweet%20@MrAhmadAwais)](https://twitter.com/mrahmadawais/) [![VSCode.pro](https://img.shields.io/badge/Supported%20by-VSCode%20Power%20User%20Course%20%E2%86%92-gray.svg?colorA=D14543&colorB=21759B)](https://VSCode.pro "This open source project is supported by VSCode.pro")

</div>

<table width='100%' align="center">
    <tr>
        <td align='left' width='100%' colspan='2'>
            <strong>WPGulp (WordPress Gulp)</strong><br />
            ๐ฏ An advanced & extensively documented Gulp WordPress workflow. Kick-start a build-workflow for your WordPress plugins and themes with Gulp.
        </td>
    </tr>
    <tr>
        <td>
            A FOSS (Free & Open Source Software) project. Maintained by <a href='https://github.com/ahmadawais'>@AhmadAwais</a>.
        </td>
        <td align='center'>
            <a href='https://twitter.com/MrAhmadAwais/'>
                <img src='https://img.shields.io/badge/โ-AHMAD%20AWAIS-gray.svg?colorA=D14543&colorB=21759B&style=flat' width='100' />
            </a>
        </td>
    </tr>
</table>

<br>

## ๐ฆ WPGulp Can Do `THATโข`

`WPGulp` is an advanced & extensively documented `Gulp.js` + `WordPress` workflow. It can help you kick-start a build-workflow for your WordPress plugins and themes with `Gulp.js`, save you a lot of grunt work time, follow the DRY (Don't Repeat Yourself) principle, and `#0CJS` Zero-config JavaScript startup but still configurable via `wpgulp.config.js` file. It is:

- ๐ฅ Versioned โ
- ๐ค? Updatable โ
- ๐ Set of sane-defaults โ

<br>

๐ป **DEV ENVIRONMENT**

>- _Live reload browser with BrowserSync_
>- _Hotloading styles with CSS Injection_

๐จ **STYLES**

>- _Sass to CSS conversion_
>- _Merging media queries_
>- _Error handling_
>- _Auto-prefixing_
>- _Minification_
>- _Sourcemaps_

๐ **JavaScript**

>- _Concatenation_
>- _Minification/uglification_
>- _Separate vendor and custom JS files handling_

๐ **IMAGES**

>- _Minification/optimization of images_
>- _File types: `.png`, `.jpg`, `.jpeg`, `.gif`, `.svg`_

๐ฏ **TRANSLATION**

>- _Generates `.pot` translation file for i18n and l10n_

๐ **WATCHING**

>- _For changes in files to recompile_
>- _File types: `.css`, `.html`, `.php`, `.js`_

<br>

![Start](https://a.cl.ly/83f7dd38eb83/c)

## Getting Started

#### โก๏ธ Quick Overview

Run step `#1`, `#2`, and `#3` quickly in one go โ Run inside local WP install's theme/plugin folder E.g. `/wp.local/wp-content/plugins/your-plugin` or `/wp.local/wp-content/themes/your-theme` directory.

```sh
# 1โ Install WPGulp in your WordPress theme/plugin.
npx wpgulp
# 2โ Now configure variables inside the `wpgulp.config.js` file.
# 3โ Start your npm build workflow.
npm start
```

([npx](https://blog.npmjs.org/post/162869356040/introducing-npx-an-npm-package-runner) is a package runner tool that comes with npm 5.2+ and higher).

> ๐   _If you want to study the detailed installation of step `#1` , `#2`,  and `#3` โ then take a look at the steps below_.

<br>
<details>
 <summary><strong><code>STEP #0</code></strong> โ Don't have <code>Node.js</code> + <code>npm</code> installed? Read this. (CLICK TO EXPAND!)</summary>

In case you are an absolute beginner to the world of `Node.js`, JavaScript, and `npm` packages โ all you need to do is go to the Node's site [download + install](https://nodejs.org/en/download/) Node on your system. This will install both `Node.js` and `npm`, i.e., node package manager โ the command line interface of Node.js.

You can verify the install by opening your terminal app and typing...

```sh
node -v
# Results into v9.11.2 โ make sure you have Node >= 8 installed.

npm -v
# Results into 6.2.0 โ make sure you have npm >= 5.3 installed.
```

</details>

### โ `STEP #1` โ Download the Required Files

1. In the terminal go to the root folder of your WordPress plugin/theme
2. Run the following command to download all the files in the [WPGulp/src](/src) folder

_It'll take a couple of minutes to install._

```sh
npx wpgulp
```

([npx](https://blog.npmjs.org/post/162869356040/introducing-npx-an-npm-package-runner) is a package runner tool that comes with npm 5.2+ and higher).

![wpgulp install gif](https://a.cl.ly/c846c265e03a/c)

> โ?๏ธ  I'm assuming that there are no previously present similar files in the root of your folder. Otherwise, you need to merge these very carefully. E.g. You can include the `scripts`, `devDependencies` in your current `package.json` file and so on for other files. If you run the above command all similar files will be overwritten.

### โ `STEP #2` โ Editing the Project Variables

Configure the project paths and other variables inside the `wpgulp.config.js` file. This is a compulsory step.

![wpgulp config](https://a.cl.ly/f2ca9bb4a740/c)

### โ `STEP #3` โ Start your project

Once the installation is done, you can open your project (WordPress plugin/theme) folder and run the start script.

```sh
npm start

# To stop press CTRL (โ) + C
```

![wpgulp start](https://a.cl.ly/d64abd87de1f/c)

### โ `OPTIONAL STEP #4` โ More Scripts/Tasks

To optimize images and generate WP POT translation file, or generate a RTL stylesheet you can run the following commands

```sh
# To optimize images.
npm run images

# To generate WP POT translation file.
npm run translate

# To generate RTL stylesheets and Sourcemap.
npm run styles-rtl

# To generate theme/plugin zip file without extranious files.
npm run zip
```

<br>

![Update](https://a.cl.ly/d0b586da13cc/c)

## How to Update?

1. Download all the latest files in the [WPGulp/src](/src) folder inside the root folder of your WordPress plugin/theme by running `npx install-wpgulp` it will overwrite all the wpgulp files.
2. Open terminal and Install WPGulp's node dependencies by running the `npm install` commands in the root folder of your WordPress plugin/theme.

<br>

![Log](https://a.cl.ly/61b20ca44b08/c)

## Changelog

Read what's ๐ฆ new, ๐ improved, ๐ fixed, and if ๐ docs got updated.

๐ Go read the entire changelog at this link โ [WPGulp Changelog โ](/CHANGELOG.md)

Nothing's ever complete, so bear with us while we keep iterating towards a better future.

> ```html
> 'Coz every night I lie in bed
> The brightest colors fill my head
> A million dreams are keeping me awake
> I think of what the world could be
> A vision of the one I see
> A million dreams is all it's gonna take
> A million dreams for the world we're gonna make ...
> ```
> ... _listen to โ [A million dreams!](https://www.youtube.com/watch?v=pSQk-4fddDI)_

<br>

![Hello](https://a.cl.ly/4guJenpQ/c)

## Sponsor

Me ([Ahmad Awais](https://twitter.com/mrahmadawais/)) and my incredible wife ([Maedah Batool](https://twitter.com/MaedahBatool/)) are two engineers who fell in love with open source and then with each other. You can read more [about me here](https://ahmadawais.com/about). If you or your company use any of my projects or like what Iโm doing then consider backing me. I'm in this for the long run. An open-source developer advocate.

[![Ahmad on Twitter](https://img.shields.io/twitter/follow/mrahmadawais.svg?style=social&label=Follow%20@MrAhmadAwais)](https://twitter.com/mrahmadawais/)

### [NodeCLI.com][n] โ Learn to build Node.js CLI Automation

> This repository is part of the [NodeCLI.com][n] course.

After building hundreds of developer automation tools used by millions of developers, I am sharing exactly how you can do it yourself with minimum effective effort. Learn to build Node.js & JavaScript based CLI (Command Line Interface) apps. Automate the grunt work, do more in less time, impress your manager, and help the community.
โ I'm sharing it all in this online video course. [Node CLI Automation
without wasting a 1,000 hours][n] โ</p>

[![Node CLI Course](https://raw.githubusercontent.com/ahmadawais/stuff/master/nodecli/featured.jpg)][n]

[![Node CLI](https://img.shields.io/badge/-NodeCLI.com%20%E2%86%92-gray.svg?colorB=488640&style=flat)][n]

[![Awais on Twitter](https://raw.githubusercontent.com/ahmadawais/stuff/master/sponsor/sponsor.jpg)](https://github.com/AhmadAwais/sponsor)

### ๐ [THEDEVCOUPLE PARTNERS](https://TheDevCouple.com/partners)

This open source project is maintained by the help of awesome businesses listed below. What? [Read more about it โ](https://TheDevCouple.com/partners)

<table width='100%'>
	<tr>
		<td width='500'><a target='_blank' href='https://kinsta.com/?kaid=WMDAKYHJLNJX&utm_source=TheDevCouple&utm_medium=Partner'><img src='https://a.cl.ly/4guJenp9' /></a>
		<td width='500'><a target='_blank' href='https://ipapi.com/?utm_source=TheDevCouple&utm_medium=Partner'><img src='https://a.cl.ly/z8uYQO2O'/></a></td>
	</tr>
</table>
<br>

![Update](https://a.cl.ly/NQu1joGO)

## License & Attribution

MIT ยฉ [Ahmad Awais](https://twitter.com/MrAhmadAwais/).

This project is inspired by the work of many awesome developers especially those who contribute to this project, Gulp.js, Babel, and many other dependencies as listed in the `package.json` file. FOSS (Free & Open Source Software) for the win.

[<img alt="ahmadawais" src="https://avatars1.githubusercontent.com/u/960133?v=4&s=117" width="117">](https://github.com/ahmadawais) |[<img alt="MaedahBatool" src="https://avatars2.githubusercontent.com/u/12712988?v=4&s=117" width="117">](https://github.com/MaedahBatool) |[<img alt="akmur" src="https://avatars2.githubusercontent.com/u/957841?v=4&s=117" width="117">](https://github.com/akmur) |[<img alt="marianrick" src="https://avatars0.githubusercontent.com/u/20360130?v=4&s=117" width="117">](https://github.com/marianrick) |[<img alt="asharirfan" src="https://avatars2.githubusercontent.com/u/8023941?v=4&s=117" width="117">](https://github.com/asharirfan) |[<img alt="JeremyEnglert" src="https://avatars2.githubusercontent.com/u/6110968?v=4&s=117" width="117">](https://github.com/JeremyEnglert) |
:---: |:---: |:---: |:---: |:---: |:---: |
[ahmadawais](https://github.com/ahmadawais) |[MaedahBatool](https://github.com/MaedahBatool) |[akmur](https://github.com/akmur) |[marianrick](https://github.com/marianrick) |[asharirfan](https://github.com/asharirfan) |[JeremyEnglert](https://github.com/JeremyEnglert) |

[<img alt="ajitbohra" src="https://avatars2.githubusercontent.com/u/1039236?v=4&s=117" width="117">](https://github.com/ajitbohra) |[<img alt="noplanman" src="https://avatars3.githubusercontent.com/u/9423417?v=4&s=117" width="117">](https://github.com/noplanman) |[<img alt="cdils" src="https://avatars0.githubusercontent.com/u/3099408?v=4&s=117" width="117">](https://github.com/cdils) |[<img alt="selrond" src="https://avatars1.githubusercontent.com/u/6603389?v=4&s=117" width="117">](https://github.com/selrond) |[<img alt="EugenioPetulla" src="https://avatars3.githubusercontent.com/u/3589467?v=4&s=117" width="117">](https://github.com/EugenioPetulla) |[<img alt="FrankM1" src="https://avatars0.githubusercontent.com/u/1177638?v=4&s=117" width="117">](https://github.com/FrankM1) |
:---: |:---: |:---: |:---: |:---: |:---: |
[ajitbohra](https://github.com/ajitbohra) |[noplanman](https://github.com/noplanman) |[cdils](https://github.com/cdils) |[selrond](https://github.com/selrond) |[EugenioPetulla](https://github.com/EugenioPetulla) |[FrankM1](https://github.com/FrankM1) |

[<img alt="isaacdanielanderson" src="https://avatars3.githubusercontent.com/u/22652927?v=4&s=117" width="117">](https://github.com/isaacdanielanderson) |[<img alt="JeffMatson" src="https://avatars2.githubusercontent.com/u/6805601?v=4&s=117" width="117">](https://github.com/JeffMatson) |[<img alt="AdnanMuhib" src="https://avatars0.githubusercontent.com/u/18069154?v=4&s=117" width="117">](https://github.com/AdnanMuhib) |[<img alt="mauryaratan" src="https://avatars3.githubusercontent.com/u/1505631?v=4&s=117" width="117">](https://github.com/mauryaratan) |[<img alt="richtabor" src="https://avatars2.githubusercontent.com/u/1813435?v=4&s=117" width="117">](https://github.com/richtabor) |[<img alt="saqibameen" src="https://avatars1.githubusercontent.com/u/31374163?v=4&s=117" width="117">](https://github.com/saqibameen) |
:---: |:---: |:---: |:---: |:---: |:---: |
[isaacdanielanderson](https://github.com/isaacdanielanderson) |[JeffMatson](https://github.com/JeffMatson) |[AdnanMuhib](https://github.com/AdnanMuhib) |[mauryaratan](https://github.com/mauryaratan) |[richtabor](https://github.com/richtabor) |[saqibameen](https://github.com/saqibameen) |

[<img alt="slushman" src="https://avatars0.githubusercontent.com/u/2255645?v=4&s=117" width="117">](https://github.com/slushman) |
:---: |
[slushman](https://github.com/slushman) |

[![Ahmad on Twitter](https://img.shields.io/twitter/follow/mrahmadawais.svg?style=social&label=Follow%20@MrAhmadAwais)](https://twitter.com/mrahmadawais/)

[n]: https://nodecli.com/?utm_source=github.com&utm_medium=referral&utm_campaign=ahmadawais/WPGulp
