
# 🧹 ESPHome BEAM vacuum cleaner — полная замена штатного контроллера

![ESPHome Ready](https://img.shields.io/badge/ESPHome-Ready-000000?logo=esphome)
![GitHub release](https://img.shields.io/github/v/release/ananyevgv/esphome-beam)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

**Полноценная замена оригинальной платы управления центрального пылесоса BEAM на базе ESPHome.**  

<p align="center">
  <b style="font-size: 25px;">Проект родился из за выхода из строя PIC контроллера на оригинальной плате. 
  <b style="font-size: 35px;">😠 Стоимость платы превысила все ожидания 😠</b>
</p>

---

## 🎯 Что делает этот проект

Замена «мозга» встроенного пылесоса BEAM на ESP8266 или ESP32 с прошивкой ESPHome.  
После замены вы получаете:

- Полный локальный контроль без облачных сервисов
- Умные сценарии через Home Assistant
- Чтение обратной связи от системы

---

### Компоненты на новой плате:
- **LTV-4N35** — оптопара для безопасного управления силовой частью  
- **LM339** — компаратор для обработки сигналов обратной связи  

Все даташиты приложены в репозитории.

---

## ⚡ Возможности

- ✅ Включение / выключение пылесоса
- ✅ Обратная связь о состоянии
- ✅ OTA-обновления через ESPHome
- ✅ Готовые сенсоры и переключатели в Home Assistant

---

![vacuum](/images/beam.jpg)
![board](/images/beam-board.jpg)
