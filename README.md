# safe-client-gateway

Place a `.env` file in the root of the project containing URL pointing to the environment in which you want the gateway to run.

The contents of the file should be the following:

```.env
TRANSACTION_SERVICE_URL=<Transaction service host>
``` 

(NOTE: don't include any form of quotation marks)

Useful links:
- Staging(rinkeby): https://safe-transaction.staging.gnosisdev.com/
- Production(rinkeby): https://safe-transaction.rinkeby.gnosis.io/
- Production(mainnet): https://safe-transaction.gnosis.io/