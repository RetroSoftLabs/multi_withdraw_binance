# multi_withdraw_binance
GUI for fast Binance API withdrawals.

Before launching

Installation requirements(install using cmd/console):
1. pip install python-binance

Configure your api keys and api secret by editing "config.py" file:

  1. api_key = 'YOUR_API_KEY'
  2. api_secret = 'YOUR_API_SECRET'
  3. randomisation_percent = 

Features:
  1. Multiaddresses text entry. Addresses must be splited by new line!
  2. Random percentage customisation to each new withdraw
  3. Delay Option (works in seconds)
  4. Working on all listed active cryptocurrencies and all networks available on Binance
  5. No need to make a confirmation from mobile phone mail 2FA
  

Open using: python main.py

Ру установка:
Для установки софта необходимо:

🦾 Сгенерированные Binance API ключи с галочкой выводов

🐍Python

🫡Прямые руки
—————————————————————-
Установка:

1️⃣ Качаем сам софт https://github.com/RetroSoftLabs/multi_withdraw_binance/archive/refs/heads/main.zip и распаковываем где удобно.

2️⃣ В cmd, terminal, console прописываем:
pip install python-binance

3️⃣ API Keys прописываем в config.py

4️⃣ Запускаете через своё IDE или в командной строке: python main.py

Параметры:

Coin: Название монеты
Network: Сеть монеты
Addresses: Каждый новый адрес должен быть введен с новой строки без запятых точек и прочего
Delay: Задержка в секундах
Rand: включение добавочного доп. процента к сумме вывода
