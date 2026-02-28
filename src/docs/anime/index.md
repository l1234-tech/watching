<div class="md-typeset" style="text-align: center; margin: 3rem 0;">
  <h1 style="font-size: 3.5rem; color: var(--md-primary-fg-color); text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
     АНИМЕ
  </h1>
</div>

<div class="movie-grid">

<a href="anime/attack-on-titan.md" class="anime-card">
  <div class="anime-poster">
    <img src="../images/anime/AOT.jpg" alt="Атака титанов">
  </div>
  <div class="anime-info">
    <h3>Атака титанов</h3>
    <p class="year">📅Год: 2013</p>
    <p class="seasons">⭐Сезонов: 4</p>
        <p class="finish">✅Закончено?: Да</p>
    <p class="description">Человечество борется за выживание против гигантских титанов.</p>
  </div>
</a>

<a href="anime/hero-academia.md" class="anime-card">
  <div class="anime-poster">
    <img src="../images/anime/Hero_Academia.jpeg" alt="Моя геройская академия">
  </div>
  <div class="anime-info">
    <h3>Моя геройская академия</h3>
    <p class="year">📅Год: 2016</p>
    <p class="seasons">⭐Сезонов: 8</p>
    <p class="finish">✅Закончено?: Да</p>
    <p class="description">В мире неожиданно появляются причуды и профессия героя.</p>
  </div>
</a>

<a href="anime/solo-leveling.md" class="anime-card">
  <div class="anime-poster">
    <img src="../images/anime/solo-level.jpg" alt="Соло-левелинг">
  </div>
  <div class="anime-info">
    <h3>Соло-левелинг</h3>
    <p class="year">📅 2024</p>
    <p class="seasons">⭐Сезонов: 2</p>
    <p class="finish">❌Закончено?: Нет</p>
    <p class="description">Челик прокачивается в одиночку ...</p>
  </div>
</a>

<a href="anime/kaidzu.md" class="anime-card">
  <div class="anime-poster">
    <img src="../images/anime/kaidzu.jpg" alt="Кайдзю №8">
  </div>
  <div class="anime-info">
    <h3>Кайдзю №8</h3>
    <p class="year">📅 2024</p>
    <p class="seasons">⭐Сезонов: 2</p>
    <p class="finish">❌Закончено?: Нет</p>
    <p class="description">Мир, где постоянно появляются монстры-кайдзю.</p>
  </div>
</a>

<a href="anime/dandadan.md" class="anime-card">
  <div class="anime-poster">
    <img src="../images/anime/dandadan.png" alt="Дандадан">
  </div>
  <div class="anime-info">
    <h3>Дандадан</h3>
    <p class="year">📅 2021</p>
    <p class="seasons">⭐Сезонов: 2</p>
    <p class="finish">❌Закончено?: Нет</p>
    <p class="description">Момо и консперун учаться вместе, а дальше ...</p>
  </div>
</a>




</div>

<style>
.anime-grid {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin: 2rem 0;
}

.anime-card {
  display: flex;
  gap: 1.5rem;
  background: var(--md-default-bg-color);
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  text-decoration: none;
  color: inherit;
}

.anime-card:hover {
  transform: translateX(5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.anime-poster {
  flex-shrink: 0;
  width: 200px;
  height: 350px;
  overflow: hidden;
}

.anime-poster img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}

.anime-info {
  padding: 1.5rem;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}

.anime-info h3 {
  margin: 0 0 1rem 0;
  color: var(--md-primary-fg-color);
  font-size: 1.5rem;
}

.anime-info .year,
.anime-info .seasons {
  margin: 0.5rem 0;
  font-size: 1rem;
}

.anime-info .year {
  color: #ff9800;
  font-weight: bold;
}

.anime-info .seasons {
  color: #ffc107;
  font-weight: bold;
}

.anime-info .finish {
  color: #c0c0c0;
  font-weight: bold;
}

.anime-info .description {
  margin-top: 1rem;
  color: #c0c0c0;
  line-height: 1.6;
  max-width: 600px;
}

/* Адаптивность для мобильных */
@media (max-width: 768px) {
  .anime-card {
    flex-direction: column;
  }
  
  .anime-poster {
    width: 100%;
    height: 300px;
  }
  
  .anime-info {
    align-items: center;
    text-align: center;
  }
  
  .anime-info .description {
    max-width: 100%;
  }
}
</style>