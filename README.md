<!--
╔══════════════════════════════════════════════════════════════════════════╗
║  README ПРОФИЛЯ: ToxicStyle-DevXplorer  ·  тема: Сатору Годжо (JJK)      ║
╚══════════════════════════════════════════════════════════════════════════╝

КАК ЭТО ЗАПУСТИТЬ:
1. Создай публичный репозиторий с ИМЕНЕМ, ТОЧНО СОВПАДАЮЩИМ С ТВОИМ НИКОМ:
   ToxicStyle-DevXplorer/ToxicStyle-DevXplorer
2. Положи этот файл в корень репозитория как README.md — он появится на странице профиля.
3. Всё, что нужно заменить, помечено словами YOUR_... или REPLACE_... (ищи по Ctrl+F).

ВАЖНО ПРО СТИЛИ:
GitHub вырезает атрибуты style="..." (box-shadow, border-radius и т.д.) в README.
Я оставил их в тегах, потому что они работают в других рендерерах (GitHub Pages, VS Code, превью),
но на самом GitHub свечение и скругление нужно «запекать» в саму картинку/GIF
(например, через ezgif.com или Photoshop). Атрибуты align, width, height работают везде.

ПАЛИТРА: фиолетовый #8A2BE2 · циан #00FFFF · фон #0D1117
-->

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Анимированный баннер-волна «Capsule Render» (Размер: 100% ширины, высота 230px).
     Роль: верхняя «шапка» профиля, задаёт градиент фиолетовый → циан и мерцание звёзд (twinkling).
     Как изменить: правь параметры в src — text= (надпись), height= (высота), fontSize= (размер текста),
     color=0:8A2BE2,100:00FFFF (градиент от первого цвета ко второму), type= (waving, wave, cylinder, soft, slice, rect, venom...),
     animation= (twinkling, fadeIn, scaleIn, blink). Конструктор и все параметры: https://github.com/kyechan99/capsule-render -->
<div align="center">
  <img width="100%" height="230" alt="Satoru Gojo Banner" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:00FFFF&height=230&section=header&text=SATORU%20GOJO%20%C2%B7%20DEV&fontSize=58&fontColor=FFFFFF&animation=twinkling&fontAlignY=38&desc=ToxicStyle-DevXplorer&descSize=22&descAlignY=60" />
</div>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: GIF Сатору Годжо (Hollow Purple / Бесконечность) (Размер: 420×236 px, по центру).
     Роль: главный визуальный акцент шапки — «лицо» профиля и тематический якорь всего оформления.
     Как заменить: 1) найди GIF на https://giphy.com или https://tenor.com по запросу «Gojo Hollow Purple» / «Gojo Infinity»;
     2) скопируй прямую ссылку, оканчивающуюся на .gif, и вставь её в src;
     3) либо загрузи свой GIF в репозиторий в папку assets/ и оставь относительный путь как ниже.
     Неоновое свечение: на GitHub style не работает, поэтому запеки рамку/свечение в сам GIF
     (в style оставлено для других рендерерров: box-shadow фиолетовый + циан, border-radius 18px). -->
<div align="center">
  <img src="assets/gojo-hollow-purple.gif" alt="Satoru Gojo — Hollow Purple" width="420" height="236"
       style="border-radius: 18px; box-shadow: 0 0 25px #8A2BE2, 0 0 50px #00FFFF;" />
</div>

<br/>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Интерактивный Typing SVG (Размер: 720×50 px, по центру).
     Роль: «печатающаяся» строка с четырьмя слоганами, по очереди сменяющимися — оживляет шапку.
     Как изменить: в параметре lines= строки разделены знаком «;», пробелы пишутся как «+», двоеточие — %3A, запятая — %2C, & — %26.
     color=00FFFF — цвет текста, font= — шрифт, size= — размер, duration= — время печати строки (мс), pause= — пауза (мс).
     Генератор с предпросмотром: https://readme-typing-svg.demolab.com -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img width="720" height="50" alt="Typing SVG" src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=1000&color=00FFFF&center=true&vCenter=true&repeat=true&width=720&height=50&lines=%E2%9A%A1+Domain+Expansion%3A+Infinite+Code;%F0%9F%92%BB+Full-Stack+Developer+%26+UI%2FUX+Sorcerer;%F0%9F%8C%80+Turning+Cursed+Energy+Into+Clean+Open-Source;%F0%9F%9A%80+Always+Learning%2C+Always+Building" />
  </a>
</div>

<div align="center">
  <h3><i>«Не волнуйся, я самый сильный.»</i></h3>
  <sub>— Сатору Годжо</sub>
</div>

<br/>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Счётчик просмотров профиля — Profile Views (Размер: авто, высота ~28px).
     Роль: показывает, сколько раз открывали твой профиль; сочетается с палитрой (фиолетовый бейдж).
     Как изменить: color=8A2BE2 — цвет, label= — подпись, style= (flat, flat-square, for-the-badge, plastic).
     Сервис: https://github.com/antonkomarev/github-profile-views-counter -->
<p align="center">
  <img alt="Profile Views" src="https://komarev.com/ghpvc/?username=ToxicStyle-DevXplorer&color=8A2BE2&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Трофеи GitHub — тема dracula (Размер: ~ 100% ширины, 1 ряд × 7 трофеев).
     Роль: витрина достижений (звёзды, коммиты, PR, issues, репозитории, подписчики и т.д.).
     Как изменить: theme= (dracula, darkhub, onedark, radical, tokyonight, gruvbox, nord...), row= / column= — размер сетки,
     no-bg=true — прозрачный фон, no-frame=true — без рамок вокруг трофеев.
     Сервис и все темы: https://github.com/ryo-ma/github-profile-trophy -->
<p align="center">
  <img width="100%" alt="GitHub Trophies" src="https://github-profile-trophy.vercel.app/?username=ToxicStyle-DevXplorer&theme=dracula&no-frame=true&no-bg=true&margin-w=12&margin-h=8&row=1&column=7" />
</p>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Неоновый разделитель-линия (Размер: 100% ширины × 4px).
     Роль: визуально отделяет секции друг от друга. Повторяется между блоками.
     Как изменить: height= — толщина линии, color=0:8A2BE2,100:00FFFF — градиент. -->
<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">🎧 SPOTIFY NOW PLAYING</h2>

<!--
═══ ИНСТРУКЦИЯ: КАК ПРИВЯЗАТЬ СВОЙ SPOTIFY ═══
1. Открой https://spotify-github-profile.kittinunf.com и войди через Spotify (кнопка Login / Authorize).
2. Сервис выдаст твой uid и готовую ссылку для вставки в README.
3. Замени YOUR_SPOTIFY_USER_ID в ссылке ниже на свой uid (можно просто вставить всю ссылку из сервиса и дописать параметры цвета).
4. Виджет показывает текущий трек, а если ничего не играет — последний прослушанный (show_offline=true).
5. Альтернатива с собственным Vercel-деплоем: https://github.com/novatorem/novatorem
   (создаёшь приложение на https://developer.spotify.com/dashboard, получаешь CLIENT_ID / CLIENT_SECRET / REFRESH_TOKEN
   и добавляешь их как Environment Variables в Vercel).
-->

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Живая карточка Spotify Now Playing (Размер: 500px по ширине, по центру).
     Роль: показывает, что ты слушаешь прямо сейчас, — «живой» элемент профиля.
     Как изменить: замени YOUR_SPOTIFY_USER_ID на свой uid; bar_color=8A2BE2 — цвет эквалайзера;
     background_color=0D1117 — фон; theme= (default, novatorem, natemoo-re, karaoke); cover_image=true — показывать обложку.
     Пока uid не подставлен, виджет не загрузится — ниже есть статичная карточка-запасной вариант. -->
<p align="center">
  <a href="https://open.spotify.com/user/YOUR_SPOTIFY_USER_ID">
    <img width="500" alt="Spotify Now Playing" src="https://spotify-github-profile.kittinunf.com/api/view?uid=YOUR_SPOTIFY_USER_ID&cover_image=true&theme=novatorem&show_offline=true&background_color=0D1117&interchange=false&bar_color=8A2BE2&bar_color_cover=false" />
  </a>
</p>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Статичная карточка трека по умолчанию (Размер: авто, высота ~40px).
     Роль: запасной вариант и «образец» трека, пока Spotify API не подключён.
     Как изменить: текст трека — между «Now_Playing-» и «-8A2BE2» (пробелы = «_», апостроф = %27, скобки = %28 и %29,
     дефис нужно писать как «--»). Цвета: color / labelColor / logoColor. Конструктор: https://shields.io -->
<p align="center">
  <img alt="Current Track" src="https://img.shields.io/badge/%F0%9F%8E%B5_Now_Playing-they%27ll_post_it_online_%28slowed%29-8A2BE2?style=for-the-badge&logo=spotify&logoColor=00FFFF&labelColor=0D1117" />
</p>

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">🖥️ TERMINAL · ARCH LINUX</h2>

<!-- Это обычный блок кода (не картинка): ASCII-логотип Arch и «вывод neofetch». Меняй строки справа как угодно. -->

```bash
┌──[ sorcerer@gojo-arch ]─[~]
└──╼ $ neofetch

                   -`                     sorcerer@gojo-arch
                  .o+`                    ──────────────────────────────
                 `ooo/                    OS ........ Arch Linux x86_64
                `+oooo:                   Shell ..... zsh / Hyprland
               `+oooooo:                  Editor .... Neovim / VS Code
               -+oooooo+:                 Technique . Domain Expansion: Infinite Code
             `/:-:++oooo+:                Status .... Unlimited Expansion Active ♾️
            `/++++/+++++++:               Eyes ...... Six Eyes (6/6 online)
           `/++++++++++++++:              Palette ... #8A2BE2 · #00FFFF · #0D1117
          `/+++ooooooooooooo/`            Current Track:
         ./ooosssso++osssssso+`           ♪ "they'll post it online (slowed)"
        .oossssso-````/ossssss+`
       -osssssso.      :ssssssso.         ████████████████████████████████
      :osssssss/        osssso+++.
     /ossssssss/        +ssssooo/-
   `/ossssso+/:-        -:/+osssso+-
  `+sso+:-`                 `.-/+oso:
 `++:.                           `-/+/
 .`                                 `/

┌──[ sorcerer@gojo-arch ]─[~]
└──╼ $ _
```

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">👁️ ABOUT ME &amp; PHILOSOPHY</h2>

```typescript
// 🌀 sorcerer.ts — паспорт мага
const sorcerer = {
  alias: "ToxicStyle-DevXplorer",
  grade: "Special Grade Developer",
  role: ["Full-Stack Developer", "UI/UX Sorcerer", "Open-Source Enjoyer"],

  cursedTechniques: {
    limitless: "Чистая архитектура без лишней связности",
    hollowPurple: "Рефакторинг, который стирает легаси",
    domainExpansion: "Infinite Code — состояние потока, где время замирает",
  },

  setup: { os: "Arch Linux", wm: "Hyprland", shell: "zsh", editor: ["Neovim", "VS Code"] },

  currentlyLearning: ["Rust", "System Design", "WebGL / Three.js"], // ← замени на своё
  funFact: "Люблю, когда интерфейс выглядит как заклинание, а работает как швейцарские часы.",

  motto: "Always Learning, Always Building",
  isStrongest(): boolean {
    return true; // «Не волнуйся, я самый сильный.»
  },
};
```

### ⚡ WHO I AM

Я разработчик, который не делит мир на «красиво» и «работает» — для меня это одно и то же. Пришёл в код через любопытство: хотелось понять, что происходит под капотом интерфейсов, а остался потому, что созидать из пустоты — лучшее чувство на свете. Привык брать проект с нуля и вести его до продакшена: от идеи и макета в Figma до деплоя и поддержки. Живу в терминале, настраиваю окружение под себя и верю, что хороший инструмент — продолжение мысли.

### 🛠️ WHAT I DO

- **🌐 Front-End** — быстрые, доступные и адаптивные интерфейсы на React / Next.js, TypeScript и Tailwind CSS.
- **🎨 UI/UX** — прототипы и дизайн-системы в Figma: от wireframe до пиксель-перфектной вёрстки.
- **🏗️ Архитектура** — продуманная структура проектов, API-контракты, чистые границы модулей, читаемый код.
- **⚙️ Back-End** — REST API на Node.js / Express и Python, работа с PostgreSQL и MongoDB.
- **🌍 Open Source** — делюсь наработками, оформляю документацию, принимаю PR и учусь у сообщества.

### 🔮 VISION &amp; BEYOND CODE

Мой принцип — **«Бесконечность в деталях»**: код должен быть понятен тому, кто придёт после меня, а интерфейс — приятен тому, кто никогда не увидит исходники. Не гонюсь за модными технологиями ради них самих: сначала задача, потом инструмент. Верю в маленькие итерации, честные ревью и постоянное обучение.

Вне кода: аниме и манга (конечно, Jujutsu Kaisen), музыка (slowed / phonk / lo-fi), кастомизация Linux-окружения, механические клавиатуры и хороший звук.

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">🧿 ПРОКЛЯТЫЕ ТЕХНИКИ · TECH STACK</h2>

<!-- Все бейджи ниже — картинки Shields.io. Формат ссылки:
     https://img.shields.io/badge/ИМЯ-ЦВЕТ_ПРАВОЙ_ЧАСТИ?style=for-the-badge&logo=SLUG&logoColor=ЦВЕТ_ЛОГО&labelColor=ЦВЕТ_ЛЕВОЙ_ЧАСТИ
     • logo=SLUG — название иконки из https://simpleicons.org (если иконки нет, бейдж просто покажется без неё);
     • чтобы добавить технологию — скопируй любую строку и поменяй ИМЯ и SLUG;
     • стили: for-the-badge (крупный), flat, flat-square, plastic, social. -->

<h3 align="center">🌐 Frontend &amp; UI/UX</h3>

<!-- 🖼️ ИЗОБРАЖЕНИЯ: Бейджи фронтенд-стека (JavaScript, TypeScript, React, Next.js, HTML5, CSS3, Tailwind CSS, Figma).
     Роль: быстро показывают, чем ты владеешь. Бейджи выровнены по центру, фиолетовая правая часть и циановые иконки.
     Как изменить: правь имя и slug иконки в каждой ссылке, цвет — после «?style=...» в параметрах color/logoColor. -->
<p align="center">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-8A2BE2?style=for-the-badge&logo=javascript&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-8A2BE2?style=for-the-badge&logo=typescript&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="React" src="https://img.shields.io/badge/React-8A2BE2?style=for-the-badge&logo=react&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-8A2BE2?style=for-the-badge&logo=nextdotjs&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-8A2BE2?style=for-the-badge&logo=html5&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-8A2BE2?style=for-the-badge&logo=css3&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-8A2BE2?style=for-the-badge&logo=tailwindcss&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Figma" src="https://img.shields.io/badge/Figma-8A2BE2?style=for-the-badge&logo=figma&logoColor=00FFFF&labelColor=0D1117" />
</p>

<h3 align="center">⚙️ Backend &amp; Database</h3>

<!-- 🖼️ ИЗОБРАЖЕНИЯ: Бейджи бэкенда и баз данных (Python, Node.js, Express, PostgreSQL, MongoDB, REST API).
     Роль: показывают серверную часть стека. Как изменить: см. общую инструкцию над секцией. -->
<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-8A2BE2?style=for-the-badge&logo=python&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-8A2BE2?style=for-the-badge&logo=nodedotjs&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Express" src="https://img.shields.io/badge/Express-8A2BE2?style=for-the-badge&logo=express&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-8A2BE2?style=for-the-badge&logo=postgresql&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-8A2BE2?style=for-the-badge&logo=mongodb&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="REST API" src="https://img.shields.io/badge/REST_API-8A2BE2?style=for-the-badge&logo=json&logoColor=00FFFF&labelColor=0D1117" />
</p>

<h3 align="center">💻 OS &amp; Tools</h3>

<!-- 🖼️ ИЗОБРАЖЕНИЯ: Бейджи ОС и инструментов (Linux, Arch Linux, Windows, Git, GitHub, VS Code, Docker).
     Роль: показывают рабочее окружение. Как изменить: см. общую инструкцию над секцией. -->
<p align="center">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-8A2BE2?style=for-the-badge&logo=linux&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Arch Linux" src="https://img.shields.io/badge/Arch_Linux-8A2BE2?style=for-the-badge&logo=archlinux&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Windows" src="https://img.shields.io/badge/Windows-8A2BE2?style=for-the-badge&logo=windows11&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Git" src="https://img.shields.io/badge/Git-8A2BE2?style=for-the-badge&logo=git&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-8A2BE2?style=for-the-badge&logo=github&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="VS Code" src="https://img.shields.io/badge/VS_Code-8A2BE2?style=for-the-badge&logo=visualstudiocode&logoColor=00FFFF&labelColor=0D1117" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-8A2BE2?style=for-the-badge&logo=docker&logoColor=00FFFF&labelColor=0D1117" />
</p>

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">📂 ЗАПЕЧАТАННЫЕ ХРАНИЛИЩА · SPOILERS</h2>

<details>
<summary>🛠 <b>[Нажмите, чтобы открыть] Мой рабочий сетап &amp; Dotfiles (Arch + Hyprland)</b></summary>
<br/>

| Компонент | Выбор |
|:--|:--|
| 🐧 Дистрибутив | Arch Linux (x86_64) |
| 🪟 Композитор / WM | Hyprland (Wayland) |
| 🐚 Шелл | zsh + prompt (замени: starship / powerlevel10k) |
| 📟 Терминал | kitty / alacritty / foot — *(замени на свой)* |
| ✍️ Редакторы | Neovim (основной) · VS Code |
| 📊 Бар / лаунчер | waybar / rofi / wofi — *(замени на свои)* |
| 🎨 Тема | неон: `#8A2BE2` · `#00FFFF` · `#0D1117` |

**Dotfiles:** [github.com/ToxicStyle-DevXplorer/dotfiles](https://github.com/ToxicStyle-DevXplorer/dotfiles) *(создай репозиторий `dotfiles` и поменяй ссылку)*

```bash
# Быстрая установка (пример — подгони под свою структуру)
git clone https://github.com/ToxicStyle-DevXplorer/dotfiles.git ~/.dotfiles
cd ~/.dotfiles && ./install.sh
```

</details>

<details>
<summary>⌨️ <b>[Нажмите, чтобы открыть] Кастомный кастом (Hardware, Split Keyboard, Audio)</b></summary>
<br/>

- 🖥️ **Машина:** *(CPU / GPU / RAM — впиши свои данные)*
- ⌨️ **Клавиатура:** сплит-клавиатура *(модель, свитчи, кейкапы, раскладка — впиши свои)*
- 🖱️ **Мышь:** *(модель)*
- 🎧 **Аудио:** *(наушники / ЦАП / колонки)* — музыка: slowed, phonk, lo-fi
- 🖼️ **Мониторы:** *(модель, диагональ, разрешение)*
- 🪑 **Рабочее место:** *(стол, свет, неоновая подсветка 💜💙)*

</details>

<details>
<summary>📚 <b>[Нажмите, чтобы открыть] Источники вдохновения (Любимые тайтлы, Манга &amp; Ранобэ)</b></summary>
<br/>

- 🌀 **Jujutsu Kaisen** (манга / аниме) — Сатору Годжо, конечно
- 🎬 *(добавь любимые аниме-тайтлы)*
- 📖 *(добавь любимую мангу)*
- 📕 *(добавь любимые ранобэ)*
- 🎮 *(игры, вдохновляющие на дизайн)*

> «Если у тебя есть цель — иди вперёд, не останавливаясь» — делай свои закладки и обновляй список. ✨

</details>

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">📊 GITHUB ANALYTICS, WAKATIME &amp; 3D METRICS</h2>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: GitHub Readme Stats — общая статистика (Размер: ~ 49% ширины, слева).
     Роль: звёзды, коммиты, PR, issues, общий ранг. Цвета подогнаны под неон: title_color=8A2BE2, icon_color=00FFFF, bg_color=0D1117.
     Как изменить: theme= (tokyonight, radical, dracula, synthwave, merko...), hide_border=true, show_icons=true.
     Приватные вклады: подключи count_private=true (нужен собственный деплой с PAT). Документация: https://github.com/anuraghazra/github-readme-stats -->
<!-- 🖼️ ИЗОБРАЖЕНИЕ: Top Languages Card — топ языков (Размер: ~ 49% ширины, справа).
     Роль: показывает, на каких языках написан твой код. Как изменить: layout= (compact, donut, donut-vertical, pie),
     langs_count= (сколько языков показать), exclude_repo= / hide= (скрыть репозитории/языки). -->
<p align="center">
  <img width="49%" alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=ToxicStyle-DevXplorer&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8A2BE2&icon_color=00FFFF&text_color=C9D1D9&ring_color=8A2BE2&include_all_commits=true" />
  <img width="49%" alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ToxicStyle-DevXplorer&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8A2BE2&text_color=C9D1D9&langs_count=8" />
</p>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: GitHub Streak Stats — серия активных дней (Размер: 100% ширины, макс. 700px, по центру).
     Роль: текущая и самая длинная серия коммитов; огонь и кольцо в неоновых цветах (fire=00FFFF, ring=8A2BE2).
     Как изменить: параметры цветов пишутся БЕЗ «#»; theme= (tokyonight, dark, radical...); hide_border=true.
     Документация: https://github.com/DenverCoder1/github-readme-streak-stats -->
<p align="center">
  <img width="100%" style="max-width: 700px;" alt="GitHub Streak" src="https://streak-stats.demolab.com?user=ToxicStyle-DevXplorer&theme=tokyonight&hide_border=true&background=0D1117&ring=8A2BE2&fire=00FFFF&currStreakLabel=00FFFF&sideLabels=8A2BE2&currStreakNum=FFFFFF&sideNums=FFFFFF&dates=C9D1D9" />
</p>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: WakaTime Coding Activity — часы программирования (Размер: ~ 100% ширины, макс. 500px).
     Роль: сколько времени и на каких языках/редакторах ты кодил за неделю.
     Подключение: 1) зарегистрируйся на https://wakatime.com; 2) поставь плагин в Neovim (vim-wakatime) и VS Code;
     3) в настройках WakaTime включи «Display languages publicly» и «Display coding activity publicly»;
     4) замени YOUR_WAKATIME_USERNAME на свой ник. Параметры оформления — те же, что у Readme Stats (layout=compact). -->
<p align="center">
  <img width="100%" style="max-width: 500px;" alt="WakaTime Stats" src="https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_WAKATIME_USERNAME&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8A2BE2&text_color=C9D1D9&icon_color=00FFFF&layout=compact" />
</p>

<!--
═══ 3D / ИЗОМЕТРИЧЕСКИЙ ГРАФ АКТИВНОСТИ — НАСТРОЙКА ═══
Картинка ниже не появится, пока Action не сгенерирует её в твоём репозитории профиля.
Создай файл .github/workflows/profile-3d.yml:

name: GitHub-Profile-3D-Contrib
on:
  schedule: [{ cron: "0 18 * * *" }]
  workflow_dispatch:
permissions:
  contents: write
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.repository_owner }}
      - name: Commit & push
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "github-actions[bot]@users.noreply.github.com"
          git add -A profile-3d-contrib
          git commit -m "chore: update 3D contrib" || exit 0
          git push

(проверь актуальную версию Action на https://github.com/yoshi389111/github-profile-3d-contrib)
Запусти workflow вручную (Actions → Run workflow) — файлы появятся в папке profile-3d-contrib/.
Другие варианты оформления: profile-night-view.svg, profile-gitblock.svg, profile-green-animate.svg, profile-season-animate.svg.
-->

<!-- 🖼️ ИЗОБРАЖЕНИЕ: 3D / изометрический график активности (Размер: 100% ширины).
     Роль: объёмная визуализация твоих вкладов за год — самый «киберпанковый» элемент статистики.
     Как изменить: замени имя файла на другой вариант (profile-night-view.svg, profile-gitblock.svg и т.д.);
     цвета можно кастомизировать через settings.json в Action (см. документацию репозитория). -->
<p align="center">
  <img width="100%" alt="3D Contribution Graph" src="profile-3d-contrib/profile-night-rainbow.svg" />
</p>

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">♾️ БЕСКОНЕЧНАЯ ПУСТОТА &amp; AUTOFED</h2>

<!--
═══ SNAKE — НАСТРОЙКА ═══
Создай файл .github/workflows/snake.yml:

name: Generate Snake
on:
  schedule: [{ cron: "0 */12 * * *" }]
  workflow_dispatch:
  push:
    branches: [main]
permissions:
  contents: write
jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake-dark.svg?palette=github-dark&color_snake=00FFFF&color_dots=161b22,4b2a7a,6a2fb5,8A2BE2,b366ff
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

Запусти workflow вручную — Action создаст ветку output с файлом SVG. Документация: https://github.com/Platane/snk
-->

<!-- 🖼️ ИЗОБРАЖЕНИЕ: SVG-анимация змейки, поедающей сетку коммитов (Размер: 100% ширины).
     Роль: живая анимация активности внизу страницы — «пожирает» твои коммиты на фиолетово-циановой сетке.
     Как изменить: пока Action не отработал, картинка будет пустой. Цвета задаются в workflow
     (color_snake — змейка, color_dots — 5 оттенков клеток от пустой до самой яркой).
     Ссылка строится по шаблону: https://raw.githubusercontent.com/ТВОЙ_НИК/ТВОЙ_РЕПОЗИТОРИЙ/output/github-snake-dark.svg -->
<p align="center">
  <img width="100%" alt="Snake Animation" src="https://raw.githubusercontent.com/ToxicStyle-DevXplorer/ToxicStyle-DevXplorer/output/github-snake-dark.svg" />
</p>

<h3 align="center">⚡ Recent Activity</h3>

<!--
═══ АВТО-ЛЕНТА АКТИВНОСТИ — НАСТРОЙКА ═══
Блок между маркерами START_SECTION / END_SECTION Action будет перезаписывать сам. Не удаляй маркеры!
Создай файл .github/workflows/activity.yml:

name: Update README with recent activity
on:
  schedule: [{ cron: "0 */6 * * *" }]
  workflow_dispatch:
permissions:
  contents: write
jobs:
  update:
    runs-on: ubuntu-latest
    steps:
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          COMMIT_MSG: "chore: update recent activity ⚡"
          MAX_LINES: 8

Документация: https://github.com/jamesgeorge007/github-activity-readme
-->

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<h2 align="center">💜 ПОДДЕРЖАТЬ МАГА</h2>

<p align="center"><i>Если мои проекты были тебе полезны — можешь подкинуть немного проклятой энергии.</i></p>

<!-- 🖼️ ИЗОБРАЖЕНИЯ: Кнопки донатов — Boosty, Ko-fi, Buy Me A Coffee (Размер: авто, по центру).
     Роль: ссылки для поддержки автора. Как изменить: в href замени YOUR_... на свои ники/страницы
     (https://boosty.to/YOUR_BOOSTY, https://ko-fi.com/YOUR_KOFI, https://www.buymeacoffee.com/YOUR_BMC);
     цвет и текст бейджей меняются в src (см. https://shields.io). -->
<p align="center">
  <a href="https://boosty.to/YOUR_BOOSTY">
    <img alt="Boosty" src="https://img.shields.io/badge/Boosty-Support_the_Sorcerer-8A2BE2?style=for-the-badge&logoColor=00FFFF&labelColor=0D1117" />
  </a>
  <a href="https://ko-fi.com/YOUR_KOFI">
    <img alt="Ko-fi" src="https://img.shields.io/badge/Ko--fi-Support_me-8A2BE2?style=for-the-badge&logo=kofi&logoColor=00FFFF&labelColor=0D1117" />
  </a>
  <a href="https://www.buymeacoffee.com/YOUR_BMC">
    <img alt="Buy Me A Coffee" src="https://img.shields.io/badge/Buy_Me_A_Coffee-Fuel_my_code-8A2BE2?style=for-the-badge&logo=buymeacoffee&logoColor=00FFFF&labelColor=0D1117" />
  </a>
</p>

<img width="100%" height="4" alt="neon divider" src="https://capsule-render.vercel.app/api?type=rect&color=0:8A2BE2,100:00FFFF&height=4" />

<div align="center">
  <h3><i>«Среди небес и земли, лишь я один достойный.»</i></h3>
  <sub>— Сатору Годжо</sub>
</div>

<!-- 🖼️ ИЗОБРАЖЕНИЕ: Нижний баннер-волна (Размер: 100% ширины, высота 140px).
     Роль: зеркальное завершение страницы — повторяет градиент шапки и «закрывает» профиль.
     Как изменить: section=footer делает волну снизу; остальные параметры — как в верхнем баннере (color, height, text). -->
<img width="100%" height="140" alt="Footer Wave" src="https://capsule-render.vercel.app/api?type=waving&color=0:8A2BE2,100:00FFFF&height=140&section=footer&reversal=false" />
