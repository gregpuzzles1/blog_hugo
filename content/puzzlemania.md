---
title: "Puzzlemania"
date: 2026-05-13T00:00:00-05:00
draft: false
---

<style>
.puzzlemania-wrap {
  display: grid;
  gap: 1.25rem;
  margin-top: 1rem;
}

.puzzle-showcase {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  border: 1px solid rgba(120, 120, 120, 0.25);
  border-radius: 14px;
  padding: 0.85rem;
  background: linear-gradient(165deg, rgba(240, 238, 230, 0.45), rgba(255, 255, 255, 0.9));
}

.puzzle-showcase img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 10px 24px rgba(0, 0, 0, 0.2);
  object-fit: cover;
}

.puzzle-meta {
  display: grid;
  gap: 0.35rem;
  font-size: 1rem;
  color: #111827;
}

.puzzle-title {
  margin: 0;
  font-size: 1.2rem;
  line-height: 1.3;
}

.puzzle-line strong {
  display: inline-block;
  min-width: 92px;
  color: #111827;
}

.puzzle-line {
  color: #111827;
  font-weight: 600;
}

.puzzle-status {
  font-weight: 600;
}

.puzzle-status.active {
  color: #a05a00;
}

.puzzle-status.done {
  color: #1f6e3d;
}

.lego-city-group {
  margin-top: 1.4rem;
}

.lego-city-title {
  margin: 0 0 0.6rem;
  font-size: 1.2rem;
  line-height: 1.25;
  color: #111827;
}

.lego-city-grid {
  display: grid;
  gap: 0.9rem;
  grid-template-columns: repeat(1, minmax(0, 1fr));
}

.lego-item {
  margin: 0;
}

.lego-item img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 8px 18px rgba(0, 0, 0, 0.18);
}

.lego-item figcaption {
  margin-top: 0.35rem;
  font-weight: 600;
  color: #2563eb;
}

@media (prefers-color-scheme: dark) {
  .puzzle-meta {
    color: #f3f4f6;
  }

  .puzzle-line,
  .puzzle-line strong {
    color: #f3f4f6;
  }

  .lego-city-title,
  .lego-item figcaption {
    color: #93c5fd;
  }
}

@media (min-width: 900px) {
  .puzzle-showcase {
    display: grid;
    grid-template-columns: minmax(420px, 1.15fr) minmax(260px, 0.85fr);
    align-items: center;
    gap: 1.1rem;
  }

  .puzzle-showcase:nth-child(even) {
    grid-template-columns: minmax(260px, 0.85fr) minmax(420px, 1.15fr);
  }

  .puzzle-showcase:nth-child(even) .puzzle-photo {
    order: 2;
  }

  .puzzle-showcase:nth-child(even) .puzzle-meta {
    order: 1;
  }

  .lego-city-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (min-width: 1200px) {
  .lego-city-grid {
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }
}
</style>

{{< tabs >}}

{{< tab label="Jigsaw Puzzles" md="false" >}}
This tab showcases completed and in-progress wooden puzzles in a photo-first layout.

<div class="puzzlemania-wrap">
  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/12_Winterlands.jpg" alt="Picture of Winterlands by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">12. Winterlands</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 524</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Status:</strong> <span class="puzzle-status active">Currently working</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/11_After_Dark.jpg" alt="Picture of After Dark by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">11. After Dark</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 97</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2026-02-23</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/10_Train.jpg" alt="Picture of Locomotive by Quordel Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">10. Train, Locomotive</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> Approx 100</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Quordel Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2026-02-23</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/09_3D_Universe.jpg" alt="Picture of 3D Universe by Kaayee Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">09. 3D Universe</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 100</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Kaayee</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2026-02-20</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/08_Kite-Eating_Tree.jpg" alt="Picture of Kite-Eating Tree by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">08. Kite-Eating Tree</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 419</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-11-05</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/07_Colorado_Columbine.jpg" alt="Picture of Colorado Columbine by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">07. Colorado Columbine</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 108</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-08-03</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/06_Oh_the_Places_Youll_Go.jpg" alt="Picture of Oh the Places Youll Go by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">06. Oh The Places You'll Go!</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 499</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-06-09</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/05_Spaldings_Baseball_Guide.jpg" alt="Picture of Spaldings Baseball Guide by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">05. Spalding's Baseball Guide</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 411</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-03-28</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/04_Old_Woman_in_Shoe.jpg" alt="Picture of Old Woman in Shoe by Little Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">04. Old Woman in Shoe</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 81</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-03-01</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/03_American_Express_Train.jpg" alt="Picture of American Express Train by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">03. American Express Train</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 530</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2024-02-10</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/02_Turkey_Derby.jpg" alt="Picture of Turkey Derby by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">02. Turkey Derby</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 227</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2023-12-02</span></div>
    </div>
  </section>

  <section class="puzzle-showcase">
    <img class="puzzle-photo" src="/blog_hugo/images/Puzzles/20260513/01_German_Butterflies.jpg" alt="Picture of German Butterflies by Liberty Puzzles">
    <div class="puzzle-meta">
      <h3 class="puzzle-title">01. German Butterflies</h3>
      <div class="puzzle-line"><strong>Pieces:</strong> 251</div>
      <div class="puzzle-line"><strong>Type:</strong> wooden / Liberty Puzzles</div>
      <div class="puzzle-line"><strong>Completed:</strong> <span class="puzzle-status done">2023-10-14</span></div>
    </div>
  </section>
</div>
{{< /tab >}}

{{< tab label="LEGO Architecture" md="false" >}}
LEGO Architecture photos grouped by city.

<section class="lego-city-group">
  <h3 class="lego-city-title">New York City</h3>
  <div class="lego-city-grid">
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/08_New_York_City.jpg" alt="Picture of New York City LEGO Architecture">
      <figcaption>New York City</figcaption>
    </figure>
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/09_New_York_City.jpg" alt="Picture of New York City LEGO Architecture">
      <figcaption>New York City</figcaption>
    </figure>
  </div>
</section>

<section class="lego-city-group">
  <h3 class="lego-city-title">Paris</h3>
  <div class="lego-city-grid">
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/06_Paris.jpg" alt="Picture of Paris LEGO Architecture">
      <figcaption>Paris</figcaption>
    </figure>
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/07_Paris.jpg" alt="Picture of Paris LEGO Architecture">
      <figcaption>Paris</figcaption>
    </figure>
  </div>
</section>

<section class="lego-city-group">
  <h3 class="lego-city-title">Tokyo</h3>
  <div class="lego-city-grid">
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/04_Tokyo.jpg" alt="Picture of Tokyo LEGO Architecture">
      <figcaption>Tokyo</figcaption>
    </figure>
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/05_Tokyo.jpg" alt="Picture of Tokyo LEGO Architecture">
      <figcaption>Tokyo</figcaption>
    </figure>
  </div>
</section>

<section class="lego-city-group">
  <h3 class="lego-city-title">London</h3>
  <div class="lego-city-grid">
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/03_London.jpg" alt="Picture of London LEGO Architecture">
      <figcaption>London</figcaption>
    </figure>
  </div>
</section>

<section class="lego-city-group">
  <h3 class="lego-city-title">San Francisco</h3>
  <div class="lego-city-grid">
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/02_San_Francisco.jpg" alt="Picture of San Francisco LEGO Architecture">
      <figcaption>San Francisco</figcaption>
    </figure>
    <figure class="lego-item">
      <img src="/blog_hugo/images/LEGO/20260513/01_San_Francisco.jpg" alt="Picture of San Francisco LEGO Architecture">
      <figcaption>San Francisco</figcaption>
    </figure>
  </div>
</section>
{{< /tab >}}

{{< /tabs >}}

