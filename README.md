# SIE formation Pack d’Apprentissage Numérique pour Doctorant Astucieux (PANDA)

## How to contribute ? 

Contributions are welcome! This site is built with the Hugo framework (Hugo Extended) and uses `pnpm` for frontend tooling and `mermaid-cli` to render Mermaid diagrams.

Please follow the steps below to get your environment ready and run the site locally.

### Prerequisites
- Git installed
- Node.js LTS (18+ recommended)
- Hugo Extended (latest)
- Go (for Hugo Modules; 1.19+ recommended)
- pnpm
- Mermaid CLI (`mmdc`)

### Install on Linux (Debian/Ubuntu)
- Install Hugo Extended (via Snap is the easiest way):
  - `sudo snap install hugo --channel=extended`
  - If Snap is unavailable, use your package manager or download a release from Hugo. Ensure it’s the “extended” build.
- Install Go:
  - `sudo snap install go --classic`
  - Or: `sudo apt-get update && sudo apt-get install -y golang`
- Install Node.js + npm (choose one method):
  - Debian/Ubuntu packages: `sudo apt-get update && sudo apt-get install -y nodejs npm`
  - Or NodeSource (usually newer): follow NodeSource instructions for LTS.
- Install pnpm:
  - `sudo npm i -g pnpm`
  - Or with Corepack: `corepack enable && corepack prepare pnpm@latest --activate`
- Install Mermaid CLI globally:
  - `pnpm add -g @mermaid-js/mermaid-cli` (or `npm i -g @mermaid-js/mermaid-cli`)

### Install on macOS
- Install Hugo Extended:
  - `brew install hugo` (Homebrew installs the extended variant by default)
- Install Go:
  - `brew install go`
- Install Node.js LTS:
  - `brew install node` (or use the official installer)
- Enable pnpm (choose one):
  - `corepack enable && corepack prepare pnpm@latest --activate`
  - Or: `npm i -g pnpm`
- Install Mermaid CLI globally:
  - `pnpm add -g @mermaid-js/mermaid-cli` (or `npm i -g @mermaid-js/mermaid-cli`)

### Install on Windows
- Install Hugo Extended:
  - `winget install Hugo.Hugo.Extended` (or `choco install hugo-extended`)
- Install Go:
  - `winget install GoLang.Go` (or `choco install golang`)
- Install Node.js LTS:
  - `winget install OpenJS.NodeJS.LTS` (or `choco install nodejs-lts`)
- Enable pnpm (choose one):
  - `corepack enable && corepack prepare pnpm@latest --activate`
  - Or: `npm i -g pnpm`
- Install Mermaid CLI globally:
  - `pnpm add -g @mermaid-js/mermaid-cli` (or `npm i -g @mermaid-js/mermaid-cli`)
- Restart your terminal so PATH updates take effect.

### Project setup - run locally
- Clone the repository and install dependencies:
  - `git clone <your-fork-or-this-repo>`
  - `cd SIE_formation_PANDA`
  - `pnpm install && hugo server`
  - Open http://localhost:1313 in your browser.


### Contribution workflow
- :TODO: Add details on branching, PRs, reviews, etc.


Thank you for contributing and helping improve PANDA!
