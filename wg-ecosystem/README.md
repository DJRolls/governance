# Ecosystem WG

Oversees the projects that make Electron app development easier.

## Membership

| Avatar | Name | Role | Time Zone |
| -------------------------------------------|----------------------|----------------------------| -------- |
| <img src="https://github.com/erickzhao.png" width=100 alt="@erickzhao">  | Erick Zhao [@erickzhao](https://github.com/erickzhao) | Chair | PT (Vancouver) |
| <img src="https://github.com/ckerr.png" width=100 alt="@ckerr">  | Charles Kerr [@ckerr](https://github.com/ckerr) | Member | CT (New Orleans) |
| <img src="https://github.com/dsanders11.png" width=100 alt="@dsanders11">  | David Sanders [@dsanders11](https://github.com/dsanders11) | Member | PT (Santa Barbara) |
| <img src="https://github.com/felixrieseberg.png" width=100 alt="@felixrieseberg">  | Felix Rieseberg [@felixrieseberg](https://github.com/felixrieseberg) | Member | PT (San Francisco) |
| <img src="https://github.com/kilian.png" width=100 alt="@kilian">  | Kilian Valkhof [@kilian](https://github.com/kilian) | Member | CET (Netherlands) |
| <img src="https://github.com/malept.png" width=100 alt="@malept">  | Mark Lee [@malept](https://github.com/malept) | Member | PT (Seattle) |
| <img src="https://github.com/marshallofsound.png" width=100 alt="@marshallofsound">  | Samuel Attard [@MarshallOfSound](https://github.com/marshallofsound) | Member | PT (Vancouver) |
| <img src="https://github.com/molant.png" width=100 alt="@molant">  | Antón Molleda [@molant](https://github.com/molant) | Member | PT (Seattle) |
| <img src="https://github.com/Toinane.png" width=100 alt="@Toinane">  | Toinane [@toinane](https://github.com/toinane) | Member | CET (France) |

## Current Objective and Key Results
**Objective:**

As a newcomer or experienced app developer, you can use Electron’s tooling and documentation to build your app well.

**Key Results:**

* [Spectron](https://github.com/electron-userland/spectron) and [Devtron](https://github.com/electron-userland/devtron) are no longer in limbo
* [Electron Forge](https://github.com/electron-userland/electron-forge) v6 to the finish line
* Website has a better information architecture

Initiatives:
* Allow access multiple versions of the docs on the website
* Identify pain points in user documentation

## Areas of Responsibility

These projects are sorted alphabetically, their order does not reflect that any of them are "better" or "more important" than others.

* Documentation across all `electron/*` repositories, primarily focusing on `electron/electron/docs` in the repo and the website
* Implementation and design of the Electron website
  * Management of Heroku apps for the site and [associated repositories](#associated-repositories)
  * Management of the Algolia search tooling
  * Management of translations via Crowdin
* Tools (Core)
  * Docs Linter
  * Download (`@electron/get`)
  * Fiddle
  * Notarize
  * osx-sign
  * Packager
  * Quickstart & API Demo repos
  * rcedit
  * Rebuild
  * Typescript Generator
  * Update server (update.electronjs.org)
  * Windows Installer (`electron-winstaller`)
* Tools (Userland)
  * Devtron
  * electron-compile
  * electron-installer-\*
  * Forge
  * Spectron

...and all other third party community based Electron tools.

## Associated Repositories

These repos are sorted alphabetically, their order does not reflect that any of them are "better" or "more important" than others.

### Electron Organization

* [`electron/algolia-indices`](https://github.com/electron/algolia-indices)
* [`electron/apps`](https://github.com/electron/apps)
* [`electron/asar`](https://github.com/electron/asar)
* [`electron/docs-parser`](https://github.com/electron/docs-parser)
* [`electron/download-stats`](https://github.com/electron/download-stats)
* [`electron/electron-api-demos`](https://github.com/electron/electron-api-demos)
* [`electron/electron-api-historian`](https://github.com/electron/electron-api-historian)
* [`electron/electron-docs`](https://github.com/electron/electron-docs)
* [`electron/electron-docs-linter`](https://github.com/electron/electron-docs-linter)
* [`electron/electron-notarize`](https://github.com/electron/electron-notarize)
* [`electron/electron-osx-sign`](https://github.com/electron/electron-osx-sign)
* [`electron/electron-packager`](https://github.com/electron/electron-packager)
* [`electron/electron-quick-start`](https://github.com/electron/electron-quick-start)
* [`electron/electron-quick-start-typescript`](https://github.com/electron/electron-quick-start-typescript)
* [`electron/electron-rebuild`](https://github.com/electron/electron-rebuild)
* [`electron/electronjs.org`](https://github.com/electron/electronjs.org)
* [`electron/fiddle`](https://github.com/electron/fiddle)
* [`electron/get`](https://github.com/electron/get)
* [`electron/hubdown`](https://github.com/electron/hubdown)
* [`electron/i18n`](https://github.com/electron/i18n)
* [`electron/node-minidump`](https://github.com/electron/node-minidump)
* [`electron/node-rcedit`](https://github.com/electron/node-rcedit)
* [`electron/rcedit`](https://github.com/electron/rcedit)
* [`electron/releases`](https://github.com/electron/releases)
* [`electron/remote`](https://github.com/electron/remote)
* [`electron/search-with-your-keyboard`](https://github.com/electron/search-with-your-keyboard)
* [`electron/semantic-release-npm-cfa`](https://github.com/electron/semantic-release-npm-cfa)
* [`electron/symbol-server`](https://github.com/electron/symbol-server)
* [`electron/symbolicate-mac`](https://github.com/electron/symbolicate-mac)
* [`electron/template`](https://github.com/electron/template)
* [`electron/typescript-definitions`](https://github.com/electron/typescript-definitions)
* [`electron/update-electron-app`](https://github.com/electron/update-electron-app)
* [`electron/update.electronjs.org`](https://github.com/electron/update.electronjs.org)
* [`electron/windows-installer`](https://github.com/electron/windows-installer)

### Electron Userland Organization

* [`electron-userland/devtron`](https://github.com/electron/devtron)
* [`electron-userland/electron-forge`](https://github.com/electron-userland/electron-forge)
* [`electron-userland/electron-installer-common`](https://github.com/electron-userland/electron-installer-common)
* [`electron-userland/electron-installer-debian`](https://github.com/electron-userland/electron-installer-debian)
* [`electron-userland/electron-installer-dmg`](https://github.com/electron-userland/electron-installer-dmg)
* [`electron-userland/electron-installer-redhat`](https://github.com/electron-userland/electron-installer-redhat)
* [`electron-userland/electron-installer-snap`](https://github.com/electron-userland/electron-installer-snap)
* [`electron-userland/electron-installer-squirrel-windows`](https://github.com/electron-userland/electron-installer-squirrel-windows)
* [`electron-userland/electron-installer-windows`](https://github.com/electron-userland/electron-installer-windows)
* [`electron-userland/electron-installer-zip`](https://github.com/electron-userland/electron-installer-zip)
* [`electron-userland/spectron`](https://github.com/electron/spectron)

...and all other repositories that the community would consider maintained by Electron.

## Meeting Schedule

**Sync Meeting** 30min every other Thursday @ [18:00 UTC](https://duckduckgo.com/?q=18%3A00+UTC&ia=answer)

Meeting notes may be viewed in [meeting-notes](meeting-notes).

## Membership

Prospective new members should reach out to an existing member to ask to be invited to the regular meetings and to be added as a Slack guest to #wg-ecosystem. That person may be added to the working group by a 2/3rds vote of WG members at a WG meeting. The prospective member should leave the meeting while the deliberation & vote is underway, and be informed only of the outcome of the vote (approved/not approved).
