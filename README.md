# Реалізація web-застосунку медичної установи за допомогою JavaScript фреймворків.
# Орест Кулик
<h3>Frontend</h3>
Технології<br/>
•	HTML, CSS, JavaScript Bootstrat and Spring thmeleafe використано для front-end.<br/>
•	mySQL database, Spring Boot та Hibernate використано для back-end сторони. </br><br/>
Що є в проектів.<br/>

1.	Реалізовані CRUD операції для лікарів, пацієнтів, ліків, хвороб<br/>
•	Реєстрація та авторизація користувачів (пацієнтів).<br/>
•	Можливість керувати лікарями та пацієнтами для адміністраторів.<br/>

2.	Можливість завантаження історії хвороб пацієнтів <br/>
•	У форматі PDF.<br/>

3.	API <br/>
•	REST API ендпоінти для GET, POST, UPDATE, DELETE та PATCH запитів <br/>


<h3>Запуск проєкту</h3>

<p>Завантажте JDK 1.8</p><br>

<hr>
<p>Оновіть maven (pom.xml): mvn clean install.</p><br>

<hr>
<p>Налаштування для підключення БД - spring.datasource.url=jdbc:mysql://localhost:3306/app?allowPublicKeyRetrieval=true&useSSL=false&serverTimezone=UTC</br>
spring.datasource.password=root</br>
spring.datasource.username=root/p><br>

<hr>
<p>spring.jpa.hibernate.ddl-auto=create - для автоматичної генерації таблиць в БД з моделей проектування</p><br>

<hr>
<p>Запустіть веб-сервер (рекомендовано Tomcat)</p><br>
<hr>
