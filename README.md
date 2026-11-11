# Dynamic Island Media Player for Windows

A customizable Dynamic Island overlay for Windows that transforms into an interactive media player when music or video is playing.

This project is based on the original [Dynamic Island for Windows](https://github.com/devcode90/Dynamic-Island-for-Windows) by Himanshu (devcode90). It removes unrelated dashboard modules and focuses on media playback, while adding new customization options and functionality.

**Languages:** [English](#english) · [Українська](#українська)

![Dynamic Island Preview](assets/preview.png)

---

## English

![English](https://thumb.wikimedia.org/wikipedia/commons/thumb/a/a5/Flag_of_the_United_Kingdom_%281-2%29.svg/250px-Flag_of_the_United_Kingdom_%281-2%29.svg.png?utm_source=ru.wikipedia.org&utm_campaign=parser&utm_content=thumbnail)

### Features

#### Media playback
- Reads the current media session through Windows System Media Transport Controls.
- Displays track title, artist, album, source application, album artwork, and playback state.
- Provides play/pause, previous-track, and next-track controls.
- Supports playback progress display and scrubbing.
- Offers two track-transition styles: **Fade** (crossfade) and **Slide** (horizontal slide).
- Keeps track-transition animations independent of the option that disables the island's hover and movement animations.
- Refreshes album artwork when the track, artist, or album changes and scales large images for display.

#### Interaction and window behavior
- Expands on hover with configurable behavior.
- Supports click-through mode. Hold **Ctrl** to interact with the island.
- Provides configurable hotkeys for showing/hiding the island, changing tracks, and controlling playback.
- Supports per-application saved positions, allowing the island to appear in different locations depending on the active application.
- Includes always-on-top, above-games, taskbar-layering, and fullscreen options.
- Provides a right-click context menu for quick access to settings and playback controls.

#### Appearance and customization
- Multiple island shapes: the default pill, a Windows 11-style rounded box, and a top-edge notch.
- Adjustable size, text scale, font, target monitor, and screen offsets.
- Theme presets and independently configurable background, primary-text, and secondary-text colors.
- Accent color modes: automatic color extraction from album artwork, system accent color, or a custom color.
- Customizable color-morphing palette with add, remove, and reset controls, as well as adjustable animation speed.
- Configurable button styles, shadows, and window opacity.
- Interface available in Ukrainian, Russian, and English.
- Optional media-source filtering.

### Installation

1. Install [Windhawk](https://windhawk.net/).
2. Download the [`dynamic-island-media-player.wh.cpp`](dynamic-island-media-player.wh.cpp) source file from this repository.
3. Open Windhawk and create a new mod using the downloaded source code.
4. Save and apply the mod.

### Context menu and settings

Right-click the island to open its context menu.

The menu provides access to window behavior, idle and paused visibility, opacity, color settings, color morphing, track-transition styles, button styles, language, animation and shadow options, hotkeys, media-source filtering, and per-application position controls.

**Note:** The **Disable player animations** option affects the island's hover and movement animations. It does not disable Fade or Slide transitions between tracks.

### Credits

- **Himanshu (devcode90):** Original Dynamic Island for Windows framework, rendering foundation, and core interface design.
- **BOG090909:** Standalone media-player adaptation, per-application positioning, customization features, localization, playback integration, and performance improvements.

---

## Українська

![Ukraine](https://thumb.wikimedia.org/wikipedia/commons/thumb/4/49/Flag_of_Ukraine.svg/250px-Flag_of_Ukraine.svg.png?utm_source=ru.wikipedia.org&utm_campaign=parser&utm_content=thumbnail)

### Можливості

#### Відтворення медіа
- Отримання інформації про поточну медіасесію через Windows System Media Transport Controls.
- Відображення назви треку, виконавця, альбому, вихідної програми, обкладинки та стану відтворення.
- Кнопки відтворення/паузи, попереднього та наступного треків.
- Відображення прогресу відтворення та перемотування.
- Два стилі переходу між треками: **Fade** (плавне згасання) та **Slide** (горизонтальний зсув).
- Анімації переходу між треками працюють незалежно від налаштування, яке вимикає анімації наведення та переміщення острова.
- Оновлення обкладинки при зміні треку, виконавця або альбому, а також масштабування великих зображень.

#### Взаємодія та поведінка вікна
- Розгортання при наведенні з можливістю налаштування поведінки.
- Режим ігнорування кліків (click-through). Утримуйте **Ctrl**, щоб взаємодіяти з островом.
- Настроювані гарячі клавіші для показу/приховування острова, перемикання треків та керування відтворенням.
- Збереження окремих позицій для різних програм, завдяки чому острів може відображатися в різних місцях залежно від активної програми.
- Налаштування відображення поверх усіх вікон, поверх ігор, над панеллю завдань та у повноекранному режимі.
- Контекстне меню, яке відкривається правою кнопкою миші та надає швидкий доступ до налаштувань і керування відтворенням.

#### Зовнішній вигляд та кастомізація
- Кілька форм острова: стандартна пігулка, заокруглений блок у стилі Windows 11 та виріз на верхньому краї екрана.
- Налаштування розміру, масштабу тексту, шрифту, цільового монітора та зміщення на екрані.
- Готові теми та окреме налаштування кольорів фону, основного й додаткового тексту.
- Режими акцентного кольору: автоматичне визначення з обкладинки, системний акцент або власний колір.
- Власна палітра плавного переливання кольорів із можливістю додавання, видалення та скидання кольорів, а також налаштування швидкості анімації.
- Налаштування стилю кнопок, тіні та прозорості вікна.
- Українська, російська та англійська мови інтерфейсу.
- Додаткова фільтрація джерел медіа.

### Встановлення

1. Встановіть [Windhawk](https://windhawk.net/).
2. Завантажте файл [`dynamic-island-media-player.wh.cpp`](dynamic-island-media-player.wh.cpp) із цього репозиторію.
3. Відкрийте Windhawk та створіть новий мод, використовуючи завантажений вихідний код.
4. Збережіть та застосуйте мод.

### Контекстне меню та налаштування

Клацніть правою кнопкою миші по острову, щоб відкрити контекстне меню.

У ньому доступні налаштування поведінки вікна, видимості під час паузи або відсутності активного відтворення, прозорості, кольорів, переливання кольорів, стилю переходу між треками, стилю кнопок, мови, анімацій і тіней, гарячих клавіш, фільтрації джерел медіа та позицій для окремих програм.

**Примітка:** Опція **Disable player animations** впливає на анімації наведення та переміщення острова. Вона не вимикає переходи Fade або Slide між треками.

### Подяки та автори

- **Himanshu (devcode90):** оригінальний фреймворк Dynamic Island for Windows, основа системи рендерингу та дизайн інтерфейсу.
- **BOG090909:** адаптація самостійного медіаплеєра, позиціонування для окремих програм, функції кастомізації, локалізація, інтеграція відтворення та покращення продуктивності.
