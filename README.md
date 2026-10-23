# Бул Брокер ООД — website concept

Separate public design demo using the existing six insurance pages. Forms only prepare a local preview and do not send inquiries.

Live preview: https://Lumina-StudioBG.github.io/bulbroker-demo/

## Company information

Бул Брокер ООД

ул. „Победа“ 15А, Пловдив

0888 148 911

Source: https://www.bulbroker.bg/contacts

Logo: https://www.bulbroker.bg/images/logo.svg

## Local preview

Run `python -m http.server 8080 --directory dist`.

## Publish

Run `powershell -ExecutionPolicy Bypass -File scripts/publish.ps1`. Set `git config core.hooksPath .githooks` to publish future commits automatically.
