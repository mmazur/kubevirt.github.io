---
layout: videos
title: Talks
permalink: /videos/talks
navbar_active: Videos
order: 10
---

<div class="row">
  {% for item in site.data.videos-talks.list %}
  <div class="col-6">
    <figure class="figure">
      <iframe style="width: 400px; height: 300px;" src="https://www.youtube-nocookie.com/embed/videoseries?list=PLnLpXX8KHIYzxJzWL6Zvp9gtfi-mffHZP" frameborder="0" allow="autoplay; encrypted-media" title="KubeVirt Talks Playlist" allowfullscreen></iframe>
      <figcaption class="figure-caption">
      <h3>KubeVirt Talks Playlist</h3>
        <p>
          A playlist of the various KubeVirt talks.
        </p>
      </figcaption>
    </figure>
  </div>
  {% endfor %}
</div>
