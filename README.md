<div align="center">
 <img src="https://content.2000ad.com/Alpha_NoBZGradient_Horizontal.png" alt="logo" width="80%" height="auto" />
<!--  <img src="img\logo.png" alt="logo" width="150" height="auto" /> -->
 <h1>Battlezone II GameWatch</h1>
   <p align="center">
   <a href = ""><img src="https://img.shields.io/github/languages/top/BattlezoneScrapField/BZCC-Website" alt="Languages" /></a>
   <a href = ""><img src="https://img.shields.io/github/repo-size/BattlezoneScrapField/BZCC-Website" alt="Code Size" /></a>
   <a href = ""><img src="https://img.shields.io/github/last-commit/BattlezoneScrapField/BZCC-Website" alt="Last Commit" /></a>
  </p>
</div>

Website to pull multiplayer game data for [Battlezone: Combat Commander](https://store.steampowered.com/app/624970/Battlezone_Combat_Commander/), hosted by the Battlezone and BZ2 Strategy Discord Communities.

## Tech Stack 👾
- Styled using [Bootstrap](http://getbootstrap.com/docs/).
- Generates Discord-friendly URLs using the [Short.IO](https://short.io/) API.

## Features 🎯
<table>
  <tr>
    <td><strong>Live Game Feed</strong><br>Automatically populates with live game data as soon as games are created, providing users with real-time updates and game information without needing to be in-game.</td>
    <td><img src="img\opengraph.png" alt="Image 1" width="300"/></td>
  </tr>
  <tr>
    <td><strong>Map Browser</strong><br>Explore a catalog of maps with their attributes, letting users filter and view map details to make informed decisions about gameplay or strategy.</td>
    <td><img src="img\opengraph-map.png" alt="Image 2" width="300"/></td>
  </tr>
  <tr>
    <td><strong>ODF Lookup</strong><br>Allows users to access Object Definition Files (ODFs) for all game objects, providing detailed attributes and data for in-depth game analysis and strategy development.</td>
    <td><img src="img\opengraph-odf.png" alt="Image 3" height="150" width="300"/></td>
  </tr>
  <!--
  <tr>
    <td><strong>Real Time Stats</strong><br>Tracks and displays live statistics from recorded strategy games, including map counts and commander win rates, giving users current state of strategy game.</td>
    <td><img src="img\opengraph-stats.png" alt="Image 4" height="150" width="300"/></td>
  </tr>
  -->
</table>

## Getting Started 🚀
We'd be happy to have you contribute to this project! Here's how you can contribute:

### Local Environment

The site uses a `<base>` tag for GitHub Pages, which requires a local web server to work correctly. Opening `index.html` directly via a browser (`file://`) will result in missing CSS and images.

#### Prerequisites
- **Node.js 18 or newer** (includes `npx`)  
  Download from [Node.js](https://nodejs.org)

Verify installation:
```bash
node -v
npx -v
```

#### Running the Site Locally
```bash
git clone https://github.com/BattlezoneScrapField/BZCC-Website.git
cd path/to/BZCC-Website/..
npx serve .
```
You should see output like:
```bash
Serving!
Local: http://localhost:3000
```

### Pushing Changes
> Note: the branching process looks like: `your-dev-branch → master → prod`

- Commit your changes to a **new** branch, sourced from `master`. You may call your branch whatever you like (i.e., `"dev-john-cooke"`).
- Create a **Pull Request** to the `master` branch from your newly developed branch. Make sure to give it an adequate title, description, and label!
- Now, sit back and relax! 🏖️ _From here: a code reviewer will review your commits and changes to complete the merge. If your changes look great, your PR to `master` will be approved, which means your new branch `"dev-john-cooke"` will be squashed. A member of the team will create a new PR to merge your changes (that are now in `master`) into `prod`. This will trigger the automated deployment to GitHub Pages!_

## Credits 💪
- Honoring the original foundation built by Sev. 💪
- Game Data API created by Nielk1 ([Github](https://github.com/Nielk1) | [Twitter](https://x.com/nielk1)). ⚙️
- ODF data provided by [AI_Unit](https://discord.com/users/125055986632228865). 📄
- Map size data provided by [VTrider](https://github.com/VTrider) ([Github](https://github.com/VTrider) | [Steam](https://steamcommunity.com/id/vtrider/)). 🗺️
- Map scrap loose data provided by [Blue Banana](https://www.twitch.tv/blue_banana_bz2). 📍
- Website maintained by the Battlezone Community. 💖
