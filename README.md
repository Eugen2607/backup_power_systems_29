<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Резервные энергосистемы</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
 /* Фоновое изображение генератора */
    background-image: url('generator.jpg'); /* Замените на ваш путь к изображению */
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  } 
 }
  header {
    background-color: #000; /* Черный фон */
    color: #fff; /* Белый текст */
    padding: 250px;
    text-align: center;
  }
  /* Логотип */
  .logo {
    max-height: 150px;
    margin-bottom: 50px;
  }
  header h1 {
    margin: 0;
    font-size: 2em;
  }


  /* Вкладки */
  .tabs {
    display: flex;
    justify-content: center;
    margin: 40px 0;
  }
  .tab {
    padding: 30px 30px;
    cursor: pointer;
    background-color: #000; /* Цвет вкладки */
    color: #fff; /* Цвет текста вкладки */
    border: none;
    outline: none;
    margin: 0 5px;
    border-radius: 4px 4px 0 0;
    transition: background-color 0.3s;
  }
  .tab.active {
    background-color: #555; /* Активная вкладка */
  }

  /* Контент вкладок */
  .tab-content {
    display: none;
    max-width: 700px;
    margin: 0 auto 30px auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }
  .tab-content.active {
    display: block;
  }

  h2 {
    color: #000;
  }

  ul {
    list-style: none;
    padding-left: 0;
  }
  li {
    margin: 10px 0;
    padding-left: 25px;
    position: relative;
  }
  li::before {
    content: "🏘";
    position: absolute;
    left: 0;
  }

  #bottom-banner {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;
    font-size: 1.8em;
    padding: 15px 20px;
    text-align: center;
    z-index: 9999;
    box-sizing: border-box;
  }

  @media(max-width: 600px) {
    body { padding: 100px; }
    .tabs { flex-direction: column; }
    .tab { margin: 5px 0; }
    header {
      flex-direction: column;
      align-items: start;
      padding: 10px;
    }
    .logo {
      max-height: 80px;
      margin-bottom: 10px;
    }
  }
</style>
</head>
<body>

<header>
  <img src="logo.jpg" alt="Логотип компании" class="logo" />
 
</header>

<!-- Вкладки -->
<div class="tabs">
  <button class="tab active" data-tab="1">Почему выбирают нас?</button>
  <button class="tab" data-tab="2">Что мы предлагаем </button>
  <button class="tab" data-tab="3">Связаться с нами</button>
</div>

<!-- Контент для вкладок -->
<div id="tab1" class="tab-content active">
<h2>В вашем частном доме или даче часто отключают электричество?!? 
Снова авария на электросетях?!? 
Или Вы, как сознательный хозяин, заранее обеспокоены этим?

Мы обеспечим надежное бесперебойное электроснабжение вашего дома!
</h2>
  <ul>
</div>
<div id="tab1" class="tab-content active">
     <h2>Предлагаем профессиональную установку систем резервного питания, для стабильной работы вашего дома в любых условиях.</li>
    <h2>Почему выбирают нас???</h2>
    <ul>
      <li>Быстрый монтаж и настройка</li>
      <li>Официальный договор</li>
      <li>Фиксированная стоимость, без скрытых платежей</li>
      <li>Гарантия качества и надежности</li>
      <li>Полный цикл работ: от консультации до запуска системы

</li><br>
    </ul>
  </ul>
 <ul> <h2>   </h2></ul>
</div>

<div id="tab2" class="tab-content">
  <h2>Что мы предлагаем для Вас</h2>
  <li>Мощный генератор на 9 кВт. </li>
<p>Этого хватит что бы без ограничения пользоваться всеми бытовыми приборами.</p>

  <li>АВР (автоматический ввод резерва) </li>
<p>Автоматика которая запусктит генератор в случае прекращения подачи электричества от сети и сама заглушит его, когда электричество вновь появится </p>

  <li>Бетонированная площадка под генератор </li>
<p> Фундамент снизит вибрации генератора, а так же убережет его от негативного влияния грунта</p>

  <li>Короб для генератора </li>
<p>Короб оснащен дополнительным глушителем, для снижения уровня шума от генератора, системой принудительной вентиляции с автоматикой для обеспечения оптимального температурного режима работы генератора.</p>
<p>В случае необходимости  мы можем установить дополнительную вибро-шумопоглащающий материал для еще большего снижения уровня шума</p>
 <li>Только качественные материалы и комплектующие</li>
<p>Все необходимые материалы уже входят в стоимость при размещении генератора на удалении до 10 м от дома.</p><br>
</div>

<div id="tab3" class="tab-content">
  <h2>Связаться с нами</h2>
  <p><a href="https://www.avito.ru/karpogory/predlozheniya_uslug/ustanovka_generatora_v_dom_7759720698?utm_campaign=native&utm_medium=item_page_android&utm_source=soc_sharing_seller" target="_blank" rel="noopener noreferrer">
    Перейти на страницу объявления на Авито
  </a></p>
 <p> Номер для связи +7 911 </p>
</div>

<div id="bottom-banner">
  Обеспечьте бесперебойное электроснабжение для вашего дома уже сегодня!
</div>

<script>
  const tabs = document.querySelectorAll('.tab');
  const contents = document.querySelectorAll('.tab-content');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      tab.classList.add('active');

      const target = tab.getAttribute('data-tab');
      contents.forEach(c => {
        c.classList.remove('active');
        if (c.id === 'tab' + target) {
          c.classList.add('active');
        }
      });
    });
  });
</script>



</body>
</html>
