# irene_plugin_boltalka2_openai
Плагин для разговора с OpenAI нейросетью ChatGPT с поддержанием контекста.

В сравнении с оригинальной болталкой https://github.com/janvarev/irene_plugin_boltalka_openai
Плюсы:
- более дешевая нейросеть "gpt-3.5-turbo"
- поддержка контекста диалога
- возможность задавать стиль разговора с собеседником (параметр system в конфиге)
Минусы:
- по ощущениям эта нейросеть работает медленнее, ответа приходится ждать дольше 

## Установка

1. Скопировать `plugin_boltalka2_openai.py` в plugins
2. Установить пакет openai (pip install openai)
3. Запустить Ирину первый раз
4. После первого запуска в `options/plugin_boltalka2_openai.json` установить API ключ OpenAI

## Использование
Команда "ирина поболтаем" или "ирина поговорим"

После этого Ирина входит в контекст, в котором все фразы пересылается опенаи - говорите что угодно, опенаи будет отвечать.

Выход из контекста автоматический или по команде "пока", "отмена".