# Windows 7 Fix: Rundll32.dll and Startup Games Program

![Windows 7 Fix](https://github.com/user-attachments/assets/2a695448-ba4e-45b7-96cf-0aca5015a0b4)

## 🇷🇺 Описание (Russian)

Простой RegFile который исправляет проблемы с запуском программ и игр на Windows 7, связанные с отключенными службами статистики Microsoft и Rundll32.dll. При этом у вас будет максимальный комфорт на Windows 7.

### Что исправляет этот патч?

Этот реестровый файл настраивает параметры GameUX в реестре Windows, которые:
- Включает установку игр по умолчанию (OOBGameInstalled)
- Настраивает параметры обновления игр (GameUpdateOptions)
- Активирует первый запуск диалога (FirstRunDialogLaunched)
- Включает загрузку информации об играх (DownLoadGameInfo)
- Настраивает список недавно сыгранных игр (ListRecentlyPlayed)

### Установка

1. Скачайте файл `Windows 7 Fix Rundll32.reg`
2. Щелкните правой кнопкой мыши на файле
3. Выберите "Слияние" или "Объединить"
4. Подтвердите добавление записей в реестр
5. Перезагрузите компьютер

### ⚠️ Предупреждение

**ВНИМАНИЕ:** Редактирование реестра Windows может быть опасным, если выполнено неправильно. Рекомендуется создать резервную копию реестра перед применением этого исправления.

Для создания резервной копии реестра:
1. Нажмите Win+R, введите `regedit` и нажмите Enter
2. Выберите "Файл" > "Экспорт"
3. Сохраните резервную копию в безопасном месте

---

## 🇬🇧 Description (English)

A simple registry file that fixes problems with launching programs and games on Windows 7 related to disabled Microsoft statistics services and Rundll32.dll. This patch provides maximum comfort when using Windows 7.

### What does this patch fix?

This registry file configures GameUX parameters in the Windows registry that:
- Enables default game installation (OOBGameInstalled)
- Configures game update options (GameUpdateOptions)
- Activates first run dialog (FirstRunDialogLaunched)
- Enables game information download (DownLoadGameInfo)
- Configures recently played games list (ListRecentlyPlayed)

### Installation

1. Download the file `Windows 7 Fix Rundll32.reg`
2. Right-click on the file
3. Select "Merge"
4. Confirm adding entries to the registry
5. Restart your computer

### ⚠️ Warning

**CAUTION:** Editing the Windows registry can be dangerous if done incorrectly. It is recommended to create a backup of the registry before applying this fix.

To create a registry backup:
1. Press Win+R, type `regedit` and press Enter
2. Select "File" > "Export"
3. Save the backup to a safe location

---

## 🔧 System Requirements

- Operating System: Windows 7 (all editions)
- Administrator privileges required for registry modification

## 📝 Technical Details

The registry file modifies the following registry keys:
- `HKEY_CLASSES_ROOT\Local Settings\Software\Microsoft\Windows\GameUX`
- Related GameStats and ServiceLocation subkeys

## 👤 Author

**Aristarh Ucolov (Аристарх Уколов)**

## 📄 License

This project is provided as-is for free use. Use at your own risk.

---

![Screenshot](https://github.com/user-attachments/assets/b1ac1cc3-984a-4174-a81c-e0c0ac5d6b19)
