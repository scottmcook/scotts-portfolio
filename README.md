# Personal website using GatsbyJS

### Purpose

This build showcases my most recent projects, skills. Major kudos to [thakkaryash94](https://github.com/thakkaryash94) for his well written documentation and work. 

## Installation steps and roadblocks

### Fork this repo

Looking back, since Github doesn't recognize commits to forks, I wish I would have cloned the project down then added it into my own repo. 

### GitHub Personal Access Token

We need GitHub personal access toke to fetch data and generate content for our website using graphql api. Create personal token for this app. Learn more [here](https://help.github.com/en/articles/creating-a-personal-access-token-for-the-command-line).

* permissions
  - repo
    - public_repo
  - admin:org
    - read:org
  - user
    - read:user
    - user:email

### Install in your local development environment

1. Change into your new directory
```
cd scotts-portfolio
```
2. Install dependencies
```
yarn
```
3. Build the site and make it available on a local server
```
GITHUB_TOKEN=YOUR_GITHUB_TOKEN yarn develop
```
6. Now browse to [http://localhost:8000](http://localhost:8000)

### Publishing to my custom domain

Since the last time I updated my portfolio, Github's Type A IP addresses had been updated. I think this was actually why my domain runnincode.com was not secure under HTTPS. It took a couple of publishes before I realized I needed to update the CNAME in my project...whoops. 

## Customization

There wasn't too much to customize. I picked this theme for its simplicity. Regardless, I updated the font to one of my favorite open source Google Fonts.

#### In progress: 

- Resume.md
- Setting dark as default theme


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

