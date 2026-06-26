
# 🧹 ESPHome BEAM vacuum cleaner — замена штатного контроллера
[![License][license-shield]][license]
[![ESPHome release][esphome-release-shield]][esphome-release]

[license-shield]: https://img.shields.io/static/v1?label=License&message=MIT&color=orange&logo=license
[license]: https://opensource.org/licenses/MIT
[esphome-release-shield]: https://img.shields.io/github/v/release/esphome/esphome?label=ESPHome&color=green&logo=esphome
[esphome-release]: https://esphome.io/


<p align="center">
  <b style="font-size: 25px;">Полноценная замена оригинальной платы управления центрального пылесоса BEAM на базе ESPHome.</b><br>
  <b style="font-size: 25px;">Проект родился из-за выхода из строя PIC контроллера на оригинальной плате.</b><br>
  <b style="font-size: 50px;">😠 Стоимость платы превысила все ожидания 😠</b>
</p>


## 🎯 Что делает этот проект

Замена «мозга» встроенного пылесоса BEAM на ESP8266 или ESP32 с прошивкой ESPHome.  
После замены вы получаете:

- Полный локальный контроль 
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

⭐ Поддержать проект

Если проект оказался полезным — поставьте ⭐ на GitHub!
