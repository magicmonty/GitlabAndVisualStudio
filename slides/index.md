- title : Git/GitLab und Visual Studio
- description : Einführung in Git mit VS 2017
- author : Martin Gondermann
- theme : beige
- transition : slide

***

## Git/GitLab und Visual Studio

<br />
<br />

### Einführung in Git mit VS 2017

<br />
<br />
Martin Gondermann - [@magicmonty](http://www.twitter.com/magicmonty)

***

## Ersteinrichtung Git

### Installation
- Git sollte bereits mit der Installation von VS2017 auf dem Rechner sein
- **Test:**
  - Kommandozeile (cmd oder PowerShell) öffnen
  - ```git --version``` eingeben

---

## Ersteinrichtung Git

### Konfiguration

Folgende Befehle auf der Kommandozeile eingeben:

```shell
C:\> git config --global user.name "Klaus Mustermann"
C:\> git config --global user.name "kmustermann@company.com"
C:\> git config --global core.editor 'C:/Program Files (x86)/Notepad++/notepad++.exe'
C:\> git config --global http.sslverify false
```

<span style="font-size:14px">*Das <code>http.sslverify false</code> deshalb, weil das SSL-Zertifikat self-signed ist</span>

***
- data-background : images/demo-time.gif

***

### Danke

* https://book.git-scm.com/book/en/v2
* https://roadtoalm.com/2013/07/19/a-starters-guide-to-git-for-tfs-gitwits/
* https://about.gitlab.com/2014/09/29/gitlab-flow/
