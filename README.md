# NOVA Island

Динамический остров для Windows 11: капсула сверху экрана, которая плавно превращается в плеер, тексты песен, системный центр, уведомления и голосовые ответы. Всё работает на вашем компьютере.

*A Dynamic Island for Windows 11: a capsule at the top of the screen that morphs into a player, lyrics, a system center, notifications and voice answers. Everything runs on your PC.*

Здесь публикуются только готовые подписанные пакеты. NOVA проверяет этот репозиторий на обновления, только если вы включите это в настройках.

## Установка

1. Откройте последний [релиз](../../releases/latest) и скачайте в одну папку все файлы: `NovaIsland-…-x64.msix`, `NovaIsland.cer`, `Install.cmd`, `Install.ps1`.
2. Запустите `Install.cmd`. Один раз Windows попросит права администратора, чтобы доверять сертификату NOVA Island (`CN=NovaIsland Dev`, отпечаток `784A44CC9743B80100C95C3852142647B53DD8B3`). Потом пакет установится и NOVA запустится.
3. Обновления: «Настройки → О программе → Обновления» (по умолчанию выключены). Новую версию ставит установщик Windows после вашего подтверждения.

Проверить файлы можно по `SHA256SUMS.txt` в каждом релизе.

## Требования

- Windows 11, x64.
- [.NET 10 Desktop Runtime x64](https://dotnet.microsoft.com/download/dotnet/10.0).
- [Windows App Runtime 2.7](https://learn.microsoft.com/windows/apps/windows-app-sdk/downloads).
- Для статуса в Discord — приложение Discord; для текстов из интернета, голосовой модели и обложек в Discord — интернет (только после вашего разрешения в настройках).

## Что NOVA отправляет в интернет

Только по вашему разрешению: поиск текстов песен (LRCLIB), загрузку голосовой модели (Hugging Face), обложки для статуса Discord (каталоги Apple и Deezer: исполнитель и название), проверку обновлений (этот репозиторий). Обложки, визуалы, уведомления, голос и настройки остаются на компьютере.

Лицензии сторонних компонентов — `THIRD-PARTY-NOTICES.txt` в каждом релизе.
