<template>
  <div style="background: linear-gradient(357deg, rgba(175,175,175,1) 0%, rgba(8,8,8,1) 100%); height: 100vh; margin: 0px">
    <div style="display: flex; justify-content: center; position: fixed;
    width: -webkit-fill-available; background: #1f1f1f;">
      <div style="border: 1px solid black; width: 100%; height: 100px; box-shadow: 10px 5px 5px black; padding: 15px; display: flex; justify-content: space-between;">
        <div>
          <div>
            <h3 class="mt-0" style="color: white; text-shadow: 1px 1px 1px #000;">
              Интернет-технологии
            </h3>
          </div>
          <div style="display: flex; flex-direction: row;">
            <div class="mx-2 txt-link" style="width: max-content">
                  <h4 style="color: white; text-shadow: 1px 1px 1px #000;">
                    <a href="#part1" style="text-decoration: none;">Задачи</a>
                  </h4>
            </div>
            <div class="mx-2 txt-link">
              <v-menu offset-y>
                <template v-slot:activator="{ on, attrs }">
                  <div
                  style="width: max-content"
                    color="primary"
                    dark
                    v-bind="attrs"
                    v-on="on"
                  >
                    <h4 style="color: white; text-shadow: 1px 1px 1px #000;">
                      <a>Лабораторные работы</a>
                    </h4>
                    
                  </div>
                </template>
                <v-list>
                  <v-list-item
                    v-for="(item, index) in items"
                    :key="index"
                  >
                    <v-list-item-title><a :href="item.link">{{ item.title }}</a></v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-menu>
            </div>
            <div class="mx-2 txt-link" style="width: max-content">
                  <h4 style="color: white; text-shadow: 1px 1px 1px #000;">
                    <a href="#part5" style="text-decoration: none;">Подготовка к экзамену</a>
                  </h4>
            </div>
          </div>
        </div>
        <div>
            <h3 class="mt-0" style="color: white; text-shadow: 1px 1px 1px #000;">
              Салимов Фирдавс ИДМ-22-06
            </h3>
        </div>
      </div>
    </div>
    <div style="display: flex; justify-content: center; height: 100%;">
      <div style="width: 90%; height: 100%; background: white;">
        <div class="mx-5 px-3" style="border-left: 2px solid black; border-right: 2px solid black; height: 100%; padding-top: 115px;">
          <div  class="px-3 py-3 my-3" style="border: 2px solid black; border-radius: 5px;">
            <h2 id="part1">
              Задачи
            </h2>
            <hr>
            <h3 class="py-2 my-0">Лабораторная работа №1</h3>
            <p>
              Экосистема разработки программ с открытым кодом": Создание персональной страницы-отчета на github и работа с git.
            </p>
            <h3 class="py-2 my-0">Лабораторная работа №2</h3>
            <p>
              Разработка простого веб-приложения": Проектирование и разработка индивидуального или коллективного веб-приложения (SPA) с использованием html,css,js + json,xml.
            </p>
            <h3 class="py-2 my-0">Лабораторная работа №3</h3>
            <p>
              "Настройка локальной сети передачи данных": Настройка коммутаторов и маршрутизаторов.
            </p>
            <h3 class="py-2 my-0">Подготовка к экзамену</h3>
            <p>
              Самооценка прохождения теста по инновациям, формулировка одного вопроса по теме "Интернет-технологии" в одной из форм, встречающихся в тесте (выбор одного, выбор многих, упорядочивание, соответствие).
            </p>
          </div>
          <div class="px-3 py-3 my-3" style="border: 2px solid black; border-radius: 5px;">
            <h2 id="part2">
              Лабораторная работа №1
            </h2>
            <hr>
            <h3 class="py-2 my-0">Регистрация на github</h3>
            <p>
              <a href="https://github.com/Artam0noff" target="_blank">Страница пользователя</a>    
            </p>
            <h3 class="py-2 my-0">Создать персональную веб страницу-отчет с использованием html, css, js.</h3>
            <p>
              <a href="">Персональная страница-отчет</a>
            </p>
            <h3 class="py-2 my-0">Загрузить персональную веб страницу-отчет в репозиторий ИДМ-22 по курсу "Интернет-технологии" на GitHub.</h3>
            <p>
              <a href="https://github.com/Artam0noff/IT" target="_blank">Папка с исходными кодами в репозитории</a>
            </p>
          </div>
          <div class="px-3 py-3 my-3" style="border: 2px solid black; border-radius: 5px;">
            <h2 id="part3">
              Лабораторная работа №2
            </h2>
            <hr>
            <h3 class="py-2 my-0">1. Сформировать команду и распредилить роли</h3>
            <p>
              <a href="https://docs.google.com/spreadsheets/d/1ypxgDUpNsaAK5PH90dTfGKdtDnWaeEDWfupEbDokN6A/edit#gid=1327184368" target="_blank">Команда и роли</a>
            </p>
            <h3 class="py-2 my-0">2. Выбрать идею для создания приложения</h3>
            <p>
             <a>Идея</a>
            </p>
            <h3 class="py-2 my-0">3. Смакетировать эскиз приложения</h3>
            <p>
              <a>Эскиз</a>
            </p>
            <h3 class="py-2 my-0">4. Выбрать стек технологий для разработки</h3>
            <p>
              <a>Стек</a>
            </p>
            <h3 class="py-2 my-0">5. Написание кода</h3>
            <p>
              <a>Код</a>
            </p>
          </div>
          <div class="px-3 py-3 my-3" style="border: 2px solid black; border-radius: 5px;">
            <h2 id="part4">
              Лабораторная работа №3
            </h2>
            <hr>
            <h3 class="py-2 my-0">1.Настроить сеть в Сisco Packet Tracer. Packet Tracer.</h3>
            <h3 class="py-2 my-0">2.Отчет по лабораторной работе доступен по ссылке: Отчет.</h3>
          </div>
          <div class="px-3 py-3 my-3" style="border: 2px solid black; border-radius: 5px;">
            <h2 id="part5">
              Подготовка к экзамену
            </h2>
            <hr>
            <h3 class="py-2 my-0">Билет №25</h3>
            <p>
              Подгтовить реферат: <a href="https://github.com/stankin/inet-2022/wiki/exam25" target="_blank">ссылка на билет</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
  },
  data: () => ({
    items: [
      { title: 'Лабораторная работа №1', link: '#part2' },
      { title: 'Лабораторная работа №2', link: '#part3' },
      { title: 'Лабораторная работа №3', link: '#part4' },
    ],
  }),
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.txt-link:hover {
  opacity: 0.5;
}
#part2:before {
	display: block;
	content: "";
	height: 115px;
	margin: -115px 0 0;
}
#part3:before {
	display: block;
	content: "";
	height: 115px;
	margin: -115px 0 0;
}
#part4:before {
	display: block;
	content: "";
	height: 115px;
	margin: -115px 0 0;
}
#part5:before {
	display: block;
	content: "";
	height: 115px;
	margin: -115px 0 0;
}
/* #part2 {
	padding-top: 100px;
	margin-top: -100px;
	-webkit-background-clip: content-box;
	background-clip: content-box;
} */

#part1:before {
	display: block;
	content: "";
	height: 200px;
	margin: -200px 0 0;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
