# 🎬 НАШИ СМОТРЯШКИ

<div class="media-cards">

<a href="films/index.md" class="media-card">
  <img src="images/films.png" alt="Фильмы">
  <div class="card-caption">🎬 Фильмы</div>
</a>

<a href="series/index.md" class="media-card">
  <img src="images/series.png" alt="Сериалы">
  <div class="card-caption">📺 Сериалы</div>
</a>

<a href="anime/index.md" class="media-card">
  <img src="images/anime.png" alt="Аниме">
  <div class="card-caption">⛩️ Аниме</div>
</a>

<a href="cartoons/index.md" class="media-card">
  <img src="images/cartoons.png" alt="Мультфильмы">
  <div class="card-caption">🎨 Мультфильмы</div>
</a>

</div>

<style>
.media-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.media-card {
  display: block;
  text-align: center;
  text-decoration: none;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  background: var(--md-default-bg-color);
}

.media-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.media-card img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  display: block;
}

.card-caption {
  padding: 1rem;
  font-weight: bold;
  font-size: 1.1rem;
  color: var(--md-default-fg-color);
}
</style>