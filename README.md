# [Awery](https://github.com/MrBoomDeveloper/Awery) Updater ( FOR THE Alpha APK NOT ANY OTHER VERSION )

# To Download Beta or Stable Version 👇

Click > [Awery Releases](https://github.com/MrBoomDeveloper/Awery/releases)

<div>
  <table>
    <tr>
      <td>CI Build</td>
      <td><a href="https://github.com/MrBoomDeveloper/Awery/actions/workflows/Build.yml"><img src="https://img.shields.io/github/actions/workflow/status/MrBoomDeveloper/Awery/Build.yml?label=CI+Build&style=for-the-badge" alt="CI"></a></td>
    </tr>
    <tr>
      <td>Pre-release</td>
      <td><a href="https://github.com/MrBoomDeveloper/Awery/releases/pre-release"><img src="https://img.shields.io/github/downloads/MrBoomDeveloper/Awery/pre-release/total?style=for-the-badge" alt="pre-release build"></a></td>
    </tr>
    <tr>
      <td>Stable</td>
      <td><a href="https://github.com/MrBoomDeveloper/Awery/releases/latest"><img src="https://img.shields.io/github/release/MrBoomDeveloper/Awery.svg?maxAge=3600&label=download&style=for-the-badge" alt="stable release"></a></td>
    </tr>
    <tr>
      <td>Discord</td>
      <td><a href="https://discord.com/invite/yspVzD4Kbm"><img src="https://img.shields.io/discord/1255770492049162240?label=discord&labelColor=7289da&color=2c2f33&style=for-the-badge" alt="Discord"></a></td>
    </tr>
  </table>
</div>

## Usage

Download [Obtainium](https://github.com/ImranR98/Obtainium) then add this repository link to Obtainium.

Make sure to toggle these settings when you add it to Obtainium
- Verify the 'latest' tag
- Reconcile string with version detected from OS

## Note
This is a simple script that grabs the latest release from the actions artifact of the last run, downloads the zip file, grabs the pretester apk from it, then uploads it to releases.

This is written in [go](https://go.dev/) and utilizes github workflows to run the script continuously.
