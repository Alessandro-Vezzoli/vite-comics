<template>
  <div class="card" style="width: 18rem">
    <img :src="src" class="card-img-top" />
    <div class="card-body">
      <h5 class="card-title">{{ titolo }}</h5>
      <p class="card-text">{{ tipo }} <br /></p>
      <a class="btn btn-primary"> Prezzo: {{ prezzo }} min</a>
    </div>
  </div>
</template>
<script>
export default {
  name: "ProductCard",
  props: {
    src: String,
    titolo: String,
    tipo: String,
    prezzo: String,
  },
};
</script>
<style scoped>
.card {
  margin: 20px;
  border: 1px solid #dee2e6;
  border-radius: 0.25rem;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.125);
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
}

.card-img-top {
  width: 100%;
  height: 15vw;
  object-fit: contain;
}

.card-body {
  padding: 1.25rem;
  width: 100%;
}

.card-title {
  font-size: 1.25rem;
  font-weight: 500;
  color: white;
}

.card-text {
  margin-bottom: 1rem;
  color: white;
}

.btn-primary {
  color: #fff;
  background-color: #007bff;
  border-color: #007bff;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  cursor: pointer;
}

.btn-primary:hover {
  background-color: #0056b3;
  border-color: #0056b3;
}
</style>
