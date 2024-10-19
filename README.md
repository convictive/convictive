name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}



<p align="center" href="https://www.animatedimages.org/cat-lines-562.htm"><img src="https://www.animatedimages.org/data/media/562/animated-line-image-0313.gif" border="0" alt="animated-line-image-0313" /></p>
<p align="center">

</p>

<p align="center">
  <strong>Welcome to my GitHub profile!</strong><br>
  Hello! My name is convict (conv1), and I'm a Senior Offensive Security Consultant with an interest in enterprise networking, cryptography, OS internals, and pen
  
  <br><br>
  Feel free to reach out to me for collaboration or any queries you might have. I'm always open to discussing new projects and opportunities. 
  If you want a pentest, contact me via mail, I do not publish my workplace
  <br><br>
</p>
<p align="center">
  <a href="https://twitter.com/kayte" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-%23A020F0.svg?style=for-the-badge&logo=Twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="ethical.infos@proton.me">
    <img src="https://img.shields.io/badge/Email-%2300FFFF.svg?style=for-the-badge&logo=GMail&logoColor=white" alt="Email">
  </a>
</p>


<p align="center" href="https://www.animatedimages.org/cat-lines-562.htm"><img src="https://www.animatedimages.org/data/media/562/animated-line-image-0313.gif" border="0" alt="animated-line-image-0313" /></p>
<p align="center">
  <strong>More about me:</strong><br>
Visit oathnet:(https://oathnet.ru/) </p>

### 📊 GitHub Stats:

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=convictive-01&show_icons=true&theme=radical" alt="GitHub Stats" width="400"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=N3ll4-01&theme=radical" alt="GitHub Streak" width="400"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=convictive-01&layout=compact&theme=radical" alt="Top Languages" width="400"/>
</p>

