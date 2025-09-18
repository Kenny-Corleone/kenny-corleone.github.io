# ORDINA - Your Life Order Assistant

<div align="center">
  <img src="logo ORDINA.png" alt="ORDINA Logo" width="200" height="auto">
  
  **Управляйте своими финансами с легкостью** | **Manage your finances with ease** | **Maliyyələrinizi asanlıqla idarə edin**
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![Language](https://img.shields.io/badge/Language-JavaScript-blue.svg)](https://javascript.info/)
  [![Framework](https://img.shields.io/badge/Framework-Vanilla%20JS-green.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
</div>

## 📋 О проекте | About | Haqqında

**ORDINA** — это современное веб-приложение для управления личными финансами, которое поможет вам организовать свою финансовую жизнь. Приложение предоставляет полный набор инструментов для отслеживания расходов, управления долгами, планирования задач и ведения календаря.

**ORDINA** is a modern web application for personal finance management that will help you organize your financial life. The application provides a complete set of tools for tracking expenses, managing debts, planning tasks, and maintaining a calendar.

**ORDINA** — şəxsi maliyyə idarəetməsi üçün müasir veb tətbiqidir ki, maliyyə həyatınızı təşkil etməyə kömək edəcək. Tətbiq xərcləri izləmək, borcları idarə etmək, tapşırıqları planlaşdırmaq və təqvim saxlamaq üçün tam alət dəsti təqdim edir.

## ✨ Основные функции | Key Features | Əsas funksiyalar

### 💰 Финансовое управление | Financial Management | Maliyyə idarəetməsi
- **Управление долгами** | **Debt Management** | **Borcları idarə etmə**
- **Ежемесячные расходы** | **Recurring Expenses** | **Aylıq xərclər**
- **Отслеживание расходов** | **Expense Tracking** | **Xərcləri izləmə**
- **Валютная поддержка** | **Currency Support** | **Valyuta dəstəyi** (AZN, USD)

### 📊 Аналитика и отчеты | Analytics & Reports | Analitika və hesabatlar
- **Интерактивные графики** | **Interactive Charts** | **İnteraktiv qrafiklər**
- **Месячная сводка** | **Monthly Dashboard** | **Aylıq ümumi**
- **Статистика по категориям** | **Category Statistics** | **Kateqoriya statistikası**

### ✅ Планирование задач | Task Planning | Tapşırıq planlaşdırması
- **Ежедневные задачи** | **Daily Tasks** | **Günlük tapşırıqlar**
- **Месячные задачи** | **Monthly Tasks** | **Aylıq tapşırıqlar**
- **Годовые задачи** | **Yearly Tasks** | **İllik tapşırıqlar**

### 📅 Календарь событий | Event Calendar | Tədbir təqvimi
- **Планирование событий** | **Event Planning** | **Tədbir planlaşdırması**
- **Дни рождения** | **Birthdays** | **Ad günləri**
- **Встречи и свадьбы** | **Meetings & Weddings** | **Görüşlər və toylar**

### 🌍 Многоязычность | Multilingual | Çoxdilli
- **Русский** | **Russian** | **Rus**
- **English** | **Английский** | **İngilis**
- **Azərbaycan** | **Азербайджанский** | **Azərbaycan**

## 🚀 Технологии | Technologies | Texnologiyalar

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js
- **Styling**: Tailwind CSS
- **Backend**: Firebase (Firestore, Authentication)
- **Icons**: Custom SVG icons
- **Responsive Design**: Mobile-first approach

## 📱 Скриншоты | Screenshots | Ekran görüntüləri

### Страница входа | Login Page | Giriş səhifəsi
![Login Page](screenshots/login.png)

### Главная панель | Dashboard | Əsas panel
![Dashboard](screenshots/dashboard.png)

### Управление долгами | Debt Management | Borc idarəetməsi
![Debts](screenshots/debts.png)

## 🛠️ Установка и запуск | Installation & Setup | Quraşdırma və işə salma

### Предварительные требования | Prerequisites | Tələblər
- Современный веб-браузер | Modern web browser | Müasir veb brauzer
- Активное интернет-соединение | Active internet connection | Aktiv internet bağlantısı

### Быстрый старт | Quick Start | Sürətli başlanğıc

1. **Клонируйте репозиторий** | **Clone the repository** | **Repozitoriyanı klonlayın**
   ```bash
   git clone https://github.com/yourusername/ordina.git
   cd ordina
   ```

2. **Откройте в браузере** | **Open in browser** | **Brauzerdə açın**
   ```bash
   # Просто откройте index.html в браузере
   # Simply open index.html in your browser
   # Sadəcə index.html-i brauzerdə açın
   ```

3. **Настройте Firebase** | **Configure Firebase** | **Firebase-i konfiqurasiya edin**
   - Создайте проект в [Firebase Console](https://console.firebase.google.com/)
   - Включите Authentication и Firestore
   - Скопируйте конфигурацию в код

### Настройка Firebase | Firebase Setup | Firebase quraşdırması

1. Создайте новый проект в Firebase Console
2. Включите следующие сервисы:
   - **Authentication** (Email/Password, Google)
   - **Firestore Database**
3. Скопируйте конфигурацию и вставьте в `index.html`

## 📖 Использование | Usage | İstifadə

### Регистрация и вход | Registration & Login | Qeydiyyat və giriş
1. Нажмите "Зарегистрироваться" | Click "Register" | "Qeydiyyat" düyməsini basın
2. Введите email и пароль | Enter email and password | Email və parol daxil edin
3. Или войдите через Google | Or sign in with Google | Və ya Google ilə daxil olun

### Основные функции | Main Features | Əsas funksiyalar

#### 💰 Управление финансами | Financial Management | Maliyyə idarəetməsi
- **Добавление долгов**: Создайте запись о долге с указанием суммы и должника
- **Ежемесячные расходы**: Настройте повторяющиеся платежи
- **Отслеживание расходов**: Записывайте все траты по категориям

#### ✅ Планирование задач | Task Planning | Tapşırıq planlaşdırması
- **Ежедневные**: Задачи на сегодня
- **Месячные**: Долгосрочные планы
- **Годовые**: Стратегические цели

#### 📅 Календарь | Calendar | Təqvim
- **События**: Планируйте важные встречи
- **Дни рождения**: Не забудьте поздравить близких
- **Свадьбы**: Отмечайте особые даты

## 🔧 Конфигурация | Configuration | Konfiqurasiya

### Валюты | Currencies | Valyutalar
- **AZN** (Азербайджанский манат)
- **USD** (Доллар США)

### Языки | Languages | Dillər
- **Русский** (ru)
- **English** (en)
- **Azərbaycan** (az)

## 🤝 Вклад в проект | Contributing | Layihəyə töhfə

Мы приветствуем вклад в развитие ORDINA! | We welcome contributions to ORDINA development! | ORDINA-nın inkişafına töhfəni qarşılayırıq!

### Как помочь | How to Help | Necə kömək edə bilərsiniz
1. **Сообщения об ошибках** | **Bug Reports** | **Xəta məlumatları**
2. **Предложения функций** | **Feature Requests** | **Funksiya təklifləri**
3. **Улучшения кода** | **Code Improvements** | **Kod təkmilləşdirmələri**
4. **Переводы** | **Translations** | **Tərcümələr**

### Процесс разработки | Development Process | İnkişaf prosesi
1. Fork репозитория | Fork the repository | Repozitoriyanı fork edin
2. Создайте ветку | Create a branch | Budaq yaradın
3. Внесите изменения | Make changes | Dəyişikliklər edin
4. Создайте Pull Request | Create Pull Request | Pull Request yaradın

## 📄 Лицензия | License | Lisenziya

Этот проект лицензирован под MIT License. | This project is licensed under the MIT License. | Bu layihə MIT Lisenziyası altında lisenziyalaşdırılıb.

См. файл [LICENSE](LICENSE) для подробностей. | See the [LICENSE](LICENSE) file for details. | Təfərrüatlar üçün [LICENSE](LICENSE) faylına baxın.

## 📞 Поддержка | Support | Dəstək

- **Email**: support@ordina.app
- **GitHub Issues**: [Создать issue](https://github.com/yourusername/ordina/issues)
- **Документация**: [Wiki](https://github.com/yourusername/ordina/wiki)

## 🙏 Благодарности | Acknowledgments | Təşəkkürlər

Спасибо всем, кто помог в разработке ORDINA! | Thanks to everyone who helped develop ORDINA! | ORDINA-nın inkişafında kömək edən hər kəsə təşəkkürlər!

### Особые благодарности | Special Thanks | Xüsusi təşəkkürlər
- **Chart.js** - за отличную библиотеку графиков
- **Tailwind CSS** - за современный CSS фреймворк
- **Firebase** - за надежную backend платформу

---

<div align="center">
  <p>Сделано с ❤️ для организации вашей жизни | Made with ❤️ to organize your life | Həyatınızı təşkil etmək üçün ❤️ ilə hazırlanıb</p>
  
  [![GitHub stars](https://img.shields.io/github/stars/yourusername/ordina?style=social)](https://github.com/yourusername/ordina)
  [![GitHub forks](https://img.shields.io/github/forks/yourusername/ordina?style=social)](https://github.com/yourusername/ordina)
</div>
