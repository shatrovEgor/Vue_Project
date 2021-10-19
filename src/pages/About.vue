<template>
  <div class="container">
    <h1 class="main">Приложение создано на Vue</h1>
    <h1 class="main">Функционал и методы:</h1>
    <div class="text">
    <li>Создание\получение\удаление</li>
    <li>Поиск</li>
    <li>Сортировка</li>
    <li>Пагинация</li>
    <li>Переиспользуемый функционал</li>
    <li>Декомпозиция</li>
    </div>
    <p>Данные приходят с сервера jsonplaceholder</p>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.main {
  text-align: center;
}
.text {
  font-size: 20px;
  width: 400px;
  margin-left: auto;
  margin-right: auto;
  margin-top: 20px;
}
.container p {
  text-align: center;
  font-size: 24px;
  margin: 30px;
}
</style>
