swagger: "2.0"
x-collection-name: Lykke
x-complete: 1
info:
  title: Wallet_Api
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/BitcoinCash/multisig/balance:
    get:
      summary: Get API Bitcoincash Multisig Balance
      description: Get api bitcoincash multisig balance.
      operationId: ApiBitcoinCashMultisigBalanceGet
      x-api-path-slug: apibitcoincashmultisigbalance-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Bitcoincash
      - Multisig
      - Balance
  /api/BitcoinCash/multisig/transaction:
    get:
      summary: Get API Bitcoincash Multisig Transaction
      description: Get api bitcoincash multisig transaction.
      operationId: ApiBitcoinCashMultisigTransactionGet
      x-api-path-slug: apibitcoincashmultisigtransaction-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: destinationAddress
      responses:
        200:
          description: OK
      tags:
      - Bitcoincash
      - Multisig
      - Transaction