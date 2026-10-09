# wate-model-data-L50

> 🔒 **Внутренний документ** — только для проектной команды ООО «ГОРИЗОНТ». Не для внешних материалов.

**Артикул:** L50  
**Наименование (EN):** Smart Spiral Line-side Warehouse  
**Наименование (RU):** Интеллектуальный спиральный складской шкаф (компакт)  
**Тип:** Спиральный компакт (master-only)  
**Источник каталога v1:** `Wate technology v1.pdf` (скан, 1 стр.), верхняя полоса ~40% — файл `Wate technology v1.jpg` → кроп `wate-model-img-L50-1.png` (1188×649, RGB)  
**Источник паспорта:** `02__passport-wate-spiral-l50-ru-v3.pdf` (7 стр.) — ТТХ полные, рендер — линейный чертеж с выносками  
**В каталоге v2:** **ОТСУТСТВУЕТ** (нет ни текста, ни изображения модели L50)

---

## §1 Technical Specifications (EN — оригинал паспорта 02, §3.1–3.3)

```
Name: Intelligent Spiral Line-side Warehouse
Model: L50
Overall dimensions (length x depth x height):
950 × 755 × 1220 mm (excluding caster wheels)
Weight: Approx. 200 kg
Colour: White with industrial grey (powder polymer coating)
Cabinet material: SPCC cold-rolled steel, 1.0–1.5 mm thickness
Number of cargo channels: 50 spiral channels (5 shelves × 10 channels)
Cargo channel dimensions:
• Tier 1 (10 channels): 70 × 30 × 140 mm (L×D×H), 12 slots per channel
• Tiers 2–5 (40 channels): 70 × 20 × 140 mm (L×D×H), 17 slots per channel
Load capacity: Max 10 kg per spiral channel
Power supply: AC 220 V ± 10%, 50 Hz

Operating System: Android 7.1
CPU: Rockchip RK3288, 4× Cortex-A17, 1.6 GHz
RAM: 2 GB DDR3
Storage: 8 GB eMMC
Display: 10.1 inch, IPS, capacitive multi-touch, 1280×800
USB: 4× USB 2.0 Host
Network: RJ45 Ethernet (10/100/1000) + Wi-Fi 2.4G/5G
Audio: Built-in speaker
Authentication: FaceID / IC/ID card / login-password

Label Printer: Thermal, roll diameter 30–58 mm ± 0.05 mm, thickness 0.05–0.1 mm
FaceID Camera: 1920×1080 Full HD, WDR
Card Reader: Multi-format IC (13.56 MHz) / ID (125 kHz)
Spiral Drives: Industrial DC motor-reducers with rotary feedback sensors
Pick-up Window: Spring-loaded protective shutter
```

---

## §2 Service / Product Features (EN — оригинал паспорта 02, §4.2)

```
• Multimodal authentication: FaceID with anti-spoofing (Liveness Detection), RFID cards, passwords
• Thermal label printing: Instant label printing for quick identification of returned and recuperated tools
• 2D scanning: Fast nomenclature verification during loading and write-off, eliminating re-sorting
```

В каталоге v1 (скан) текстового слоя нет — Service Features не извлечены.

---

## §3 Перевод на русский

### Технические спецификации (паспорт 02)

| Параметр | Значение |
|----------|----------|
| Наименование | Интеллектуальный спиральный складской шкаф (Smart Spiral Line-side Warehouse) |
| Модель | L50 |
| Габариты (Д × Г × В) | 950 × 755 × 1220 мм (без опорных колёс) |
| Масса | ~200 кг |
| Цвет | Белый с индустриальным серым (порошковое покрытие) |
| Материал корпуса | Холоднокатаная сталь SPCC, 1.0–1.5 мм |
| Количество каналов | 50 спиральных каналов (5 полок × 10 каналов) |
| Размеры каналов | 1-й ярус (10 кн.): 70×30×140 мм, 12 слотов/кн.; 2–5-й ярусы (40 кн.): 70×20×140 мм, 17 слотов/кн. |
| Грузоподъёмность | До 10 кг на канал |
| Питание | AC 220 В ±10%, 50 Гц |
| ОС / CPU / RAM / Flash | Android 7.1 / RK3288 4×1.6 ГГц / 2 ГБ DDR3 / 8 ГБ eMMC |
| Дисплей | 10.1" IPS, ёмкостной мультитач, 1280×800 |
| Интерфейсы | 4× USB 2.0, RJ45 1GbE, Wi-Fi 2.4/5 ГГц |
| Аутентификация | FaceID, IC/ID карта, логин/пароль |
| Принтер | Термопринтер, рулон 30–58 мм |
| Камера FaceID | 1920×1080, WDR |
| Считыватель карт | IC (13.56 МГц) / ID (125 кГц) |
| Приводы спиралей | Пром. мотор-редукторы DC с датчиками обратной связи |
| Окно выдачи | Пружинная защитная шторка |

### Функциональные особенности

- **Мультимодальная аутентификация:** FaceID с защитой от спуфинга (Liveness), RFID-карты, пароли
- **Термопечать этикеток:** Мгновенная печать для быстрой идентификации возвращаемого и рекуперируемого инструмента
- **2D-сканирование:** Быстрая верификация номенклатуры при загрузке и списании, исключающая пересортицу

---

## §4 Общие параметры для всей серии

> Аналогично L8050 (§4 в `wate-model-data-L8050.md`). Значения из паспорта L50 и маркетингового PDF.

---

## §5 Ведомость расхождений (Каталог v1 (скан) ↔ Паспорт 02 ↔ Roadmap)

| Параметр | Каталог v1 (скан, 1 стр.) | Паспорт 02 (L50) | Roadmap §5 /Презентация | Статус |
|----------|---------------------------|------------------|--------------------------|--------|
| Наличие в каталоге v2 | **НЕТ** | — | — | ❌ Модели нет в v2 |
| Габариты (Д×Г×В) | Нечитаемо (скан) | 950 × 755 × 1220 мм | 950 × 755 × 1220 мм | ✅ Паспорт = Roadmap |
| Масса | Нечитаемо | ~200 кг | ~200 кг | ✅ |
| Каналы | Нечитаемо | 50 (5×10) | 50 | ✅ |
| Экран | Нечитаемо | 10.1" 1280×800 | 10.1" | ✅ |
| Питание / климат | Нечитаемо | AC 220±10%, +5…+40°C | ~230В (170–250В), 0…+40°C | ✅ Учтено в §4 |
| Рендер | Скан (посредственное качество) | **Линейный чертеж с выносками** (не фотореалистичен) | Нужен фотореалистичный рендер | ⚠️ **Для презентации — генерация** |
| FaceID / Принтер | Нечитаемо | Есть (нативная платформа Wate) | **Удалены** per roadmap | ⚠️ Не в наш ПТК |

> **Вывод:** L50 отсутствует в каталоге v2. Единственный источник ТТХ — паспорт 02. Рендер в паспорте — технический чертеж (не подходит для hero-слайдов). Извлечённый из v1 скан `wate-model-img-L50-1.png` — посредственное качество (скан). Для презентации потребуется генерация фотореалистичного рендера на базе L80 (как предусмотрено медиа-планом §11).