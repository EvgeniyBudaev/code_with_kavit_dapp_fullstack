# Basic Sample Hardhat Project

## Содержание
- [Описание_проекта](#Описание_проекта)
- [Авторы](#Авторы)

### <a name="Описание_проекта">Описание</a>

Solidity + Next.js. Соединение с кошельком. Получение и добавление книг.

### Порядок действий

- Инициализация проекта:

```python
 npm init
```

- Установка зависимостей:

```python
 npm install --save-dev hardhat
 npm install ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers @openzeppelin/contracts dotenv
 npx hardhat accounts
```

- Инициализация hardhat:

```python
 npx hardhat
```

- Запуск тестов:

```python
 npx hardhat test
```

- Запуск скриптов:

```python
 npx hardhat run scripts/deploy.js --network rinkeby
```

- Запуск локального hardhat сервера:

```python
 npx hardhat node
``` 

- Инициализация frontend:

```python
 npx create-next-app -e with-tailwindcss client
``` 

- Установка зависимостей frontend:

```python
 cd client
 npm i axios ethers
``` 

- frontend. Создаем и описываем config.js:

```python
 config.js
``` 

- Запустить frontend:

```python
 npm run dev
``` 

### <a name="Авторы">Авторы</a>
```
 Евгений Будаев
```

![Image alt](https://github.com/EvgeniyBudaev/code_with_kavit_dapp_fullstack/raw/main/client/public/readme.jpg)
