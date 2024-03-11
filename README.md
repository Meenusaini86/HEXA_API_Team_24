https://medium.com/@bhattacharyasudeshna/integrating-postman-collections-with-github-repository-and-running-in-github-actions-workflows-b3af2061b7d9



Setting Up Postman API backup in Github
1) Integerate Postman with Github
  https://learning.postman.com/docs/integrations/available-integrations/github/ 

Setting Up CI / CD  Pipeline  with Postman-cli.
 1) Go to collection on postman
 2) Double Click on Collection and go to 'PostMann CLI Configuration' TAB.
 3) Find CI/CD configuration
 4) Select Github Actions in dropdown
 5) Select Operating Systen based on your Github setup.
 6) For this project it is linux.
 7) Copy Configurations from textbox.
 8) In Github go to Actions tab.
 9) Click on 'set up a workflow yourself' link and paste content from point 7.
 10) Replace API key for our collection below line
     postman login --with-api-key PMAK-65ee236ae71bce0001cb8f38-365d50805b5844f2b75e40c689a893cada


Setting Up CI / CD  Pipeline  with node/newman.

