<div align="center">
  <img
    src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif"
    width="96"
    alt="Waving astronaut greeting animation"
  />
</div>

<h1 align="center">
  <img
    src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=24&pause=1100&color=3A6FDB&center=true&vCenter=true&width=720&lines=👋+Alexey+Kabanov;RAG+%26+AI+Automation+Engineer+·+Motion+Designer;Shipping+production+AI+systems+%2B+full-cycle+video"
    alt="Animated typing headline: Alexey Kabanov — RAG & AI Automation Engineer, Motion Designer"
  />
</h1>

<div align="center">
  <a href="https://t.me/artifico_ru">
    <img src="https://img.shields.io/badge/Primary%20Contact-Telegram-3A6FDB?style=for-the-badge&logo=telegram&logoColor=white" alt="Primary contact: Telegram" />
  </a>
  <a href="https://www.linkedin.com/in/aleksey-kabanov/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile link" />
  </a>
  <a href="https://vk.com/artifico">
    <img src="https://img.shields.io/badge/VK-Profile-0077FF?style=for-the-badge&logo=vk&logoColor=white" alt="VK profile link" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=kotleha&style=flat-square&color=3A6FDB" alt="Profile views counter" />
</div>

---

## 🧭 Навигация

- [Кто я и чем занимаюсь](#-кто-я-и-чем-занимаюсь)
- [Сейчас фокус](#-сейчас-фокус)
- [Ключевые проекты](#-key-projects)
- [Техстек и активность](#-tech-stack-и-активность)
- [Достижения](#-достижения)
- [Образование и сертификаты](#-education--certifications)
- [Generative AI & Tools](#-generative-ai--tools)
- [Тренинги и воркшопы](#-training--workshops)
- [BI & Reporting](#-bi--reporting)
- [Клиенты и партнёры](#-clients--partners)
- [Контакты](#-contact-me)

---

## 🚀 Кто я и чем занимаюсь

Я **пишу код** и **внедряю ИИ** в бизнес-процессы: RAG-ядра, поиск/ранжирование, API-сервисы, пайплайны автоматизации и QA.  
Параллельно веду **full-cycle видеопродакшен**: сценарии → раскадровки → моушен/монтаж → звук.

**Мой стиль:** системность + психология восприятия (реклама/нейромаркетинг) → решения, которые выглядят “дорого” и реально работают.

**EN TL;DR:** I build production RAG/AI automation systems and run a full-cycle video studio. I care about clarity, usability, and measurable impact.

```yaml
name: Alexey Kabanov
role: RAG & AI Automation Engineer | Prompt Engineer | Motion Designer
experience: 12+ years

focus:
  - 🔎 RAG / Search: BM25 + KNN + rerank + eval/QA
  - 🧠 Prompting & LLM pipelines: strict schemas, validators, tool-usage
  - ⚙️ FastAPI & process automation: async services, integrations, observability
  - 🎬 Motion design & post: story → motion → edit → sound

languages:
  - 🐍 Python
  - 🚀 Kotlin
  - 🗄️ SQL
  - ⚡ JavaScript

clients:
  - MY.GAMES
  - Mail.ru
  - 2GIS
  - Roscosmos
  - Mitsubishi
  - Decathlon
```

---

## 🧠 Сейчас фокус

* **RAG-платформы / ядра**: ingestion → embeddings → retrieval → rerank → генерация → eval/QA
* **Автоматизация и качество**: валидаторы, строгие JSON-контракты, воспроизводимые пайплайны
* **Инженерия + восприятие**: интерфейсы/тексты/визуал, которые проще понять и приятнее использовать

> Если хочешь обсудить задачу — проще всего написать в Telegram: [https://t.me/artifico_ru](https://t.me/artifico_ru)

---

## 🎯 Key Projects

### Q-A-System-API

* **Что:** Векторно-поисковый сервис «вопрос–ответ»
* **Как:**

  * Индекс в Elasticsearch
  * Эмбеддинги через OpenAI / GigaChat
  * Гибридный поиск: KNN + BM25 + ранжирование
  * FastAPI-эндпоинты с асинхронной обработкой
* **Результат:** Быстрые ответы по большим объёмам документов, пригодно для продакшена

---

### STRUCTURA_AI v3

* **Что:** Автоматизация разбора ТЗ и оценки бюджета
* **Как:**

  * LLM-парсер структуры
  * Логическое дополнение ролей и устранение дубликатов
  * Формирование детализированной сметы по реальным ставкам
  * Экспорт в Markdown и Excel
* **Результат:** Экономия времени на подготовку смет (в моих кейсах — **до 90%**)

---

### RAG-Core for Edu & Biz

* **Что:** Ядро Retrieval-Augmented Generation (для образования и бизнеса)
* **Как:**

  * Ingestion: PDF/DOCX/TXT → OCR → DLP/PII-masking
  * Векторизация чанков → хранение в FAISS / ClickHouse
  * `/rag/query`: BM25 + KNN + rerank + A/B-тестирование промптов
* **Результат:** Консистентные, проверяемые ответы с привязкой к источникам

---

### Secure Incident Management App

* **Что:** Android-приложение для управления инцидентами
* **Как:**

  * Kotlin + Jetpack Compose, offline-first синхронизация
  * Шифрование данных, push-уведомления, RBAC
* **Результат:** Надёжное решение для полевых команд

---

### Data Scraping & Analytics

* **Что:** Автоматизированный pipeline сбора и анализа данных
* **Как:**

  * Headless-браузинг с Selenium
  * Парсинг через BeautifulSoup
  * Flask API + EDA (pandas, matplotlib)
  * Кластеризация: PCA, KMeans, GMM
* **Результат:** Практичные инсайты по сегментам аудитории и поведению

---

## 🛠️ Tech Stack и активность

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=kotleha&show_icons=true&theme=vision-friendly-dark"
    alt="GitHub stats card"
  />
  <br/>
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=kotleha&layout=compact&theme=vision-friendly-dark"
    alt="Top languages card"
  />
</div>

---

## 🏆 Достижения

[![trophy](https://trophy.ryglcloud.net/?username=kotleha&theme=onedark)](https://github.com/ryo-ma/github-profile-trophy)


---

## 🎓 Education & Certifications

* Алтайский государственный университет — психология рекламы (обучение)
* SkillFactory Data Scientist Pro (МГУ)
* ChatGPT for Everyone (2024), SberMarket Tech (2023), Python от SkillFactory (2022)

---

## 🔮 Generative AI & Tools

* Fine-tuning GPT (создание «цифровой копии»)
* Stable Diffusion, MidJourney, Runway, D-ID, ElevenLabs, Rive, Rask

---

## 🛠️ Training & Workshops

* Проведение тренингов по внедрению нейросетевых технологий в рекламные стратегии
* Преподавательская деятельность (лицей «Медиа Холдинг»)

---

## 📊 BI & Reporting

* Сводные отчёты в Excel/Google Sheets, макросы и автоматизация рутинных отчётов

---

## 🤝 Clients & Partners

MY.GAMES, Mail.ru, 2GIS, Рос­космос, Mitsubishi, Decathlon и другие крупные заказчики

---

## 📫 Contact Me

📩 **Email:** [kabanov.lexx@gmail.com](mailto:kabanov.lexx@gmail.com)
📡 **Telegram:** [@artifico_ru](https://t.me/artifico_ru)
💼 **LinkedIn:** [Profile](https://www.linkedin.com/in/aleksey-kabanov/)
🎭 **VK:** [Profile](https://vk.com/artifico)

---

> "Sound is my air, visuals are my food." 🎬
