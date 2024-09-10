<template>
  <div class="banner-container">
    <div class="header">
      <img src="logo-central-eventos.png" alt="Logo Central de Eventos" class="logo" />
      <button class="create-event-btn">Crie seu evento</button>
    </div>

    <div class="banner-content">
      <div class="artists">
        <img src="artist1.png" alt="Artista 1" class="artist-img" />
        <img src="artist2.png" alt="Artista 2" class="artist-img" />
        <img src="artist3.png" alt="Artista 3" class="artist-img" />
        <img src="artist4.png" alt="Artista 4" class="artist-img" />
        <img src="artist5.png" alt="Artista 5" class="artist-img" />
      </div>

      <div class="event-details">
        <h1>ZERO31 FESTIVAL</h1>
        <p class="date">08 de Junho de 2024 - 21:00</p>
        <p class="location">Expominas, Belo Horizonte</p>
        <p class="contact">Informações: (31) 99917-9985</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.banner-container {
  background-color: #181818;
  color: white;
  padding: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  width: 150px;
}

.create-event-btn {
  background-color: #6200ee;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
}

.banner-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.artists {
  display: flex;
  gap: 15px;
  margin: 20px 0;
}

.artist-img {
  width: 120px;
  border-radius: 10px;
}

.event-details {
  text-align: center;
}

.event-details h1 {
  font-size: 3rem;
  margin-bottom: 10px;
}

.date, .location, .contact {
  margin-bottom: 5px;
  font-size: 1.2rem;
}
</style>

<script>
export default {
  data() {
    return {
      event: {
        name: "ZERO31 FESTIVAL",
        date: "08 de Junho de 2024 - 21:00",
        location: "Expominas, Belo Horizonte",
        contact: "(31) 99917-9985",
        artists: [
          { img: "artist1.png", name: "Artista 1" },
          { img: "artist2.png", name: "Artista 2" },
          { img: "artist3.png", name: "Artista 3" },
          { img: "artist4.png", name: "Artista 4" },
          { img: "artist5.png", name: "Artista 5" }
        ]
      }
    };
  }
};
</script>
