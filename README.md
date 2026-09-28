# Close Crate for Windows

Native viewer for protected `.cc` documents. This repository distributes Windows installers; it does not contain the private product source tree.

## Install once

1. Download the Windows x64 ZIP from [Releases](https://github.com/AlexiAxAxA/close-crate/releases).
2. Extract the whole archive and run `Установить.cmd`.
3. Open a `.cc` file. If Windows asks, choose **Close Crate** and **Always**.
4. Enter the recipient code sent separately by the author, or request access in the viewer.

HTML envelopes are optional. The package includes the PDF renderer and third-party license notices. Installation is per-user and does not require administrator rights. Device keys are preserved on uninstall.

## Preview limitations

This is a preview build. Executables are not Authenticode-signed, so Windows may show a publisher/SmartScreen warning. SHA256 checks detect download corruption; they do not constitute a publisher signature. Do not disable Windows security controls.

Access requires the author's configured authority to be reachable, subject to the document's offline policy. An author-local `127.0.0.1` address is not reachable from a different computer. Revocation does not erase ordinary copies already exported by a recipient.

## Установка

Скачайте ZIP из Releases, распакуйте целиком и запустите «Установить.cmd».
Дальше открывайте `.cc` двойным щелчком; при первом выборе укажите Close Crate
и «Всегда». Код получателя автор передаёт отдельно от файла. HTML не требуется.
Пакет предварительный, без подписи Authenticode. Ключи не удаляются при удалении программы.
