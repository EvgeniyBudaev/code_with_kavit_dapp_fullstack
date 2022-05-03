# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

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
