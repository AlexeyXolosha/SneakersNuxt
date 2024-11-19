<script setup lang="ts">

</script>

<template>
  <section class="section">
    <div class="product">
      <div class="product__inner">
        <div class="product__search">
          <h3 class="product__title">Все кроссовки</h3>
          <div class="input">
            <img src="../assets/static/search.svg" alt="" class="search__image"/>
            <input type="text" class="search__input" placeholder="Поиск..." />
          </div>
        </div>
        <list-card-list></list-card-list>
      </div>
    </div>
  </section>

</template>

<style lang="scss">
.product {

  &__search {
    margin-bottom: 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  &__title {
    font-size: 32px;
    font-weight: 700;
  }
}

.input {
  border: 2px solid #f3f3f3;
  border-radius: 10px;
  display: flex;
  align-items: center;
  height: 45px;
  column-gap: 12px;
  padding: 10px 10px;
}

.search__input{
  padding: 0;
  border: none;

  input::placeholder{
    color: #c4c4c4;
  }


}

</style>