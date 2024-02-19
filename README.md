<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fgjbae1212%2Fhit-counter&count_bg=%23000000&title_bg=%23000000&icon=hugo.svg&icon_color=%23FFFFFF&title=Profile+Views+Hanzelkaaragac&edge_flat=false" align="right"/></a>
<br>

<p align="center"><img src="https://i.imgur.com/A6bWGFl.gif"/>
<img src="https://komarev.com/ghpvc/?username=BEYZAASLAN&&style=plastics&&color=yellow" align="right"/> </p>

<h2 align="center"> 
 </h2> 

<img align="center" width="400" src="https://github.com/BEYZAASLAN/BEYZAASLAN/assets/113600705/aa422c7a-3357-446c-8faf-3225d1af1342" />
<a href="https://discord.gg/venelopi_">
<strong>Discord ⬅️ </a>

<!-- %7C -> alttaki yaziya | eklememize yariyor -->
![Typing SVG](https://readme-typing-svg.herokuapp.com?color=%CC00FF&lines=Welcome+BEYZA+ASLAN+Channel;+Click+image+to+join+our+server)
<!--   
<h3 align="left">Skills: Java | Selenium | JUnit | TestNG | Cucumber | Git - GitHub | Html - Css | JIRA | PostgreSQL | LAMBDA | JDBC | API | </h3>
<img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" /> -->
## <img src="https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width ="25"><b> Languages and Tools:</b>
<p>
<a>
<a href="https://www.python.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original-wordmark.svg" alt="python" width="40" height="40"/>
 <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"><a href="https://www.w3schools.com/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> </p> </a>
 <img src="https://www.animatedimages.org/data/media/562/animated-line-image-0184.gif" width="1920" />
 </p>

<br>

 <div align="center"> 
  <a href="https://www.youtube.com/channel/UCfIbv5ZAgVPbh70OlpAmI7Q" target="_blank">
    <img src="https://img.shields.io/badge/-Youtube-%23333?style=for-the-badge&logo=youtube&logoColor=red" target="_blank">
  </a>
  <a href="https://www.linkedin.com/in/beyza-aslan-a93113250/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%23333?style=for-the-badge&logo=linkedin&logoColor=blue" target="_blank">
  </a>
  <a href = "mailto:aslanbeyza@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=reed" target="_blank">
  </a>
  <a href="https://medium.com/@aslanbeyza3413">
   <img src="https://img.shields.io/badge/Medium-%23333?style=for-the-badge&logo=medium&logoColor=white" target="_blank"/>
  </a>
  <a href="https://www.instagram.com/_beyza_aslan_/?hl=tr" target="_blank">
   <img alt="Instagram" src="https://img.shields.io/badge/instagram-%23333?&style=for-the-badge&logo=instagram&logoColor=#E1306C "/>
  </a>
</div>

 
![](./profile-3d-contrib/profile-night-rainbow.svg)



name: GitHub-Profile-3D-Contrib

on:
  schedule: # 03:00 JST == 18:00 UTC
    - cron: "0 18 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: generate-github-profile-3d-contrib
    steps:
      - uses: actions/checkout@v3
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          USERNAME: ${{ github.BEYZAASLAN }}
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          git commit -m "generated"
          git push


