# computergreek.github.io
### Anxiety Flowchart




Created using https://twinery.org/.


Big shout out to https://happycoding.io/tutorials/html/hosting and http://jmcglone.com/guides/github-pages/ for teaching me how to use Github Pages create my own website (!) to host the .html project file Twinery exported. The domain used for this project ([anxietyflowchart.com](anxietyflowchart.com)) was bought from https://porkbun.com/ because it was cheap and I loved that this particular domain registrar is a small & indie player in the space. As a really big bonus, they made it REALLY easy to connect the domain to Github Pages from this article in their knowledge base https://kb.porkbun.com/article/64-how-to-connect-your-domain-to-github-pages.


I made it mobile friendly by doing what user *greywolf* suggested from [here](http://twinery.org/questions/35558/font-changing-size-based-on-amount-of-text-on-mobile?show=35558#q35558). Basically insert `<meta name="viewport" content="width=device-width,initial-scale=1" />` in the top head section of the .html file by editing it with a text editor.


The top of the code should basically look like this:  
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>The name of the Story project</title>
...
```
