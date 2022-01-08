# TECH SAVIOURS wiki
The wiki is powered by [DokuWiki](https://www.dokuwiki.org/dokuwiki) in combination with the [Bootstrap3](https://www.dokuwiki.org/template:bootstrap3?s[]=bootstrap3) template.

# Contributing to wiki
Like any open source project, it lives from the efforts of its users.  
The documentation can always be improved, or you can create more tutorials. But they must be easy to read and generally understandable to a complete newcomer who wants to achieve more digital privacy but don't know how to achieve it.

## GitHub or registration
The normal procedure fork/pull requests on [GitHub](https://github.com/TECH-SAVIOURS-ORG/wiki/) or send us an [email](mailto:wiki@techsaviours.org?subject=Registration_Request) if you prefer to register on the [wiki website](https://wiki.techsaviours.org) itself, as we do not have registration enabled.

## Syntax
You can use [DokuWiki's syntax](https://wiki.techsaviours.org/en:wiki:syntax). We tried to implement [Markdown](https://www.markdownguide.org/cheat-sheet/), but unfortunately it doesn't really work. Too many failures with plugins or core. 

## Structure
The wiki is mainly structured in 4 parts ([namespaces](https://www.dokuwiki.org/namespaces)):
1. Server
 - Operating Systems
 - Services
2. Phone
 - Operating Systems
 - Apps
3. Desktop
 - Operating Systems
 - Services
4. Extras

There is also `faq` and probably more will follow. 
  
If the tutorials are the same (e.g. desktop and server), create the page and add a link to it
```
{{page>en:server:services:name}}
```
> Note:  
> Always add the link from the desktop to the server. This makes it easier to change the tutorials in the future.

# License

See [LICENSE](LICENSE.md)
