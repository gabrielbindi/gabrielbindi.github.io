---
layout: page
title: Zweite Seite
permalink: /second_page.md/
nav_order: 2

# Du hast es zu meiner 2ten Seite geschafft :D
## Jetzt erklär ich dir wie man eine Seite wie diese schnell erstellt.
---

### 1. Erstelle ein neues Repo in deinem Github-Account
![Github_Repo](../images/Github_Jekyll_1.png)

### 2. Der Name deines Repos muss dein username sein
> als Beispiel: `username.github.io`

### 3. Repository visibility und Add README sollte auf *On* sein

### 4. Erstelle dein Repository und clicke dann auf *Settings*

### 5. Clicke unter "Code automation" auf *Pages*

### 6. Wähle unter "Build and deployment" unter "Source" *Deploy from branch* aus. 

### 7. Unter "Branch" kannst du eine publishing source auswählen

### 8. Wichtig ist dass du eine `_config.yml` datei hast. In dieser sollte circa folgendes stehen:
```
{
  "theme": "jekyll-theme-minimal"
  "title": "Meine Webseite"  
  "description": "Das ist meine eigene Website!"
}
```

zurück zur [Startseite](./index.md)
