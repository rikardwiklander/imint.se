# imint.se
Website for imint.se

The site is built with [Hugo](http://gohugo.io/) and deployed to Github Pages.

Changes to the repository will trigger a [Wercker](http://wercker.com/) script that builds and deploys the site automatically.

## Editing
#### Markdown
The main content is placed in the content folder into markdown files.
There are templates for different content types called archetypes, to use them run ```hugo new path/to/file/my-new-file.md --kind="archetype-to-use"```.
#### Other Content
Images and other content is placed in static. Create folders corresponding to the path and the name of the content file they belong to and place the files there.

## To run this site on a local computer follow these steps

1. Clone the repository to your computer with ```git clone https://github.com/imintsystems/imint.se --recursive```.
2. If Hugo is not installed go to https://github.com/spf13/hugo/releases and download the latest release. (v0.14 was used to build this site)
3. Stand in the root folder of the cloned repository and run ```hugo server -w -t hugo-vidhance-theme``` to start a local webserver hosting the site and that refreshes the site when a file is edited.

## To-do /Eric
### Bilder
- Originalbilder i bättre/större upplösning
- Rättigheter till bilder
- Bildtexter
- Bildformatering (alla kanske inte ska ligga till höger)
  - vissa som ligger dubbelt blir konstiga - man vill ha dem bredvid varandra

### Länkar
- ska funka till allt
- kolla särskilt "Services"

### Formulär
- cognito (Jonathan har ett konto med formulär fn)
- Se till att de har rätt innehåll
- lägg på rätt plats i mappstrukturen

### Innehåll
- Services finns inte alls men länkas från minst ett ställe
