---
layout: about
title: about
permalink: /
subtitle: UPC, La FabricaW, AI Facil<br>Menos tiempo, mas resultados con AI

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
Profesional y docente apasionado por la innovación, la transformación digital y la inteligencia artificial, con experiencia en la Escuela de Posgrado de la Universidad Peruana de Ciencias Aplicadas (UPC).

Comparto conocimiento también desde La FábricaW y mi academia Aprende AI Fácil (aprendeaifacil.com), acercando la inteligencia artificial a profesionales que buscan aprender, experimentar y aplicar.

En este GitHub comparto proyectos, recursos y experimentos que conectan tecnología, academia y práctica profesional bajo una idea simple: "Menos tiempo, más resultados."

<style>
  .contact-icons a[title="LinkBio"] img {
    transition: opacity 0.15s ease-in-out;
  }
</style>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var linkbioLink = document.querySelector('.contact-icons a[title="LinkBio"]');
    if (linkbioLink) {
      var img = linkbioLink.querySelector('img');
      if (img) {
        var defaultSrc = img.getAttribute('src');
        var hoverSrc = defaultSrc.replace('linkbio_logo.png', 'linkbio_logo_hover.png');
        linkbioLink.addEventListener('mouseenter', function () {
          img.setAttribute('src', hoverSrc);
        });
        linkbioLink.addEventListener('mouseleave', function () {
          img.setAttribute('src', defaultSrc);
        });
      }
    }
  });
</script>
