<div align="center">
 <img src="img\logo.png" alt="logo" width="150" height="auto" />
 <h1>Battlezone II GameWatch</h1>
   <p align="center">
   <a href = ""><img src="https://img.shields.io/github/languages/top/BattlezoneScrapField/BZCC-Website" alt="Languages" /></a>
   <a href = ""><img src="https://img.shields.io/github/repo-size/BattlezoneScrapField/BZCC-Website" alt="Code Size" /></a>
   <a href = ""><img src="https://img.shields.io/github/last-commit/BattlezoneScrapField/BZCC-Website" alt="Last Commit" /></a>
  </p>
</div>

Website to pull multiplayer game data for [Battlezone: Combat Commander](https://store.steampowered.com/app/624970/Battlezone_Combat_Commander/), prioritizing VSR strategy matches hosted by the Battlezone and BZ2 Strategy Discord Communities.

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

## Credits:

- Game Data API created by Nielk1 ([Github](https://github.com/Nielk1) | [Twitter](https://x.com/nielk1)). ⚙️
- ODF data provided by [AI_Unit](https://discord.com/users/125055986632228865). 📄
- Map size data provided by [VTrider](https://github.com/VTrider) ([Github](https://github.com/VTrider) | [Steam](https://steamcommunity.com/id/vtrider/)). 🗺️
- Map scrap loose data provided by [Blue Banana](https://www.twitch.tv/blue_banana_bz2). 📍
- Honoring the original foundation built by Sev. 💪
- Website maintained by by [F9bomber](https://www.youtube.com/@F9bomber) and Battlezone Community. 📊

## Getting Started [WIP]

- Clone repo to your local pc
- Change useCORSProxy in main.js:line 16 to true.
- Open index.html using Open with Live Server extension.