# Chen Quantum Engineering Lab Website

Welcome to the repository for the Chen Quantum Engineering Lab website! This project aims to provide a easy-to-maintain, easy-to-update website for multiple group members to collaborate on.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Customization](#customization)
- [License](#license)

## Introduction

The Chen Quantum Engineering Lab website is built using [Hugo Blox](https://docs.hugoblox.com/getting-started/install-hugo/), a fast and flexible static site generator. Our site features information about our research, team members, publications, and available positions.

## Installation

### Steps

1. Clone the repository:

Make sure you have access to the repository

```
git clone https://github.com/CQElab/CQE.git
```

2. Install dependencies:

Follow instruction on [Hugo Blox](https://docs.hugoblox.com/getting-started/install-hugo/)

## Usage

### Running Locally

To start the Hugo server and view the site locally:

```
cd your_local_path
hugo server
```

Open your browser and visit http://localhost:1313 to see the site.

### Building for Production

To build the site for production:

```
hugo
```

The generated files will be in the public/ directory.

### Deployment

To deploy the site, you can use platforms like Netlify, GitHub Pages, or any static site hosting service. For example, to deploy with GitHub Pages:

- Change `baseURL` in `hugo.yaml` to your custom url.
- Add the following lines to `package.json`
```
"scripts": {
    "deploy": "hugo -D && gh-pages -d public"
  }
```
- Push your repository to GitHub.
- Set up GitHub Pages to `Source: Deploy form a branch`, and set `Branch` to `gh-pages`
- In command line, run 
```
npm run deploy
```

Also read [this](https://jedyang.com/post/how-to-build-academic-research-group-website-in-2021/) for automatic deployment.

## File Structure

```
chen-quantum-engineering-lab/
├── _vendor/
├── assets/
├── config/
├── content/
├── public/
├── resources/
├── README.md
├── LICENSE.md
```
- \_vendor/: Custom block and all-access styles.
- config/: The main configuration file for the site.
- assets/: Images.
- config/: The main configuration files for the site.
- content/: The content of the site (e.g., posts, pages).
- public/: 
- resources/: 

## Customization

### Customizing Styles

To customize styles, edit or add new html files in the `_vendor/github.com/HugoBlox/all-access/blox-all-access/blox` directory.

### Adding Content

## License

This project is licensed under the MIT License - see the LICENSE file for details.


