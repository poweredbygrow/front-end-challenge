<img src="https://www.poweredbygrow.com/assets/img/logo/grow-logo.png" alt="Grow Logo" width="250">


# Front-end Challenge

## Objective
Build a user interface to view a list of financial transactions for a user. The user should be able to do the following:

- See their transactions for multiple accounts under a single list.
- Filter their transactions by account.
- Filter their transactions by multiple categories.
- Sort their transactions from most recent to oldest and vice versa.
- See their total balance across all accounts.
- Reset all applied filters.

## API
`GET http://demo7235469.mockable.io/transactions`
Returns a list of accounts, categories, and transactions.

The response shortened:
```JSON
{
  "accounts": [
    {
      "accountId": "ID",
      "institutionName": "Bank",
      "accountName": "TSFA SAVINGS",
      "transitNumber": "1234",
      "accountNumber": "1234",
      "balance": 100,
      "balanceUpdated": "2017-02-22"
    },
    {
      "accountId": "ID",
      "institutionName": "Bank",
      "accountName": "SAVINGS ACCOUNT",
      "transitNumber": "1234",
      "accountNumber": "1234",
      "balance": 100,
      "balanceUpdated": "2017-02-22"
    }
  ],
  "transactionData": {
    "earliestTransactionDate": "2015-12-12",
    "latestTransactionDate": "2016-12-12",
    "daysSpanByTransaction": 100,
    "transactionCount": 100,
    "transactions": [
      {
        "accountId": "ID",
        "transactionDate": "2016-12-12",
        "description": "Overdraft Protection Fee - Pay as you go MAR/16/2016",
        "amount": -100,
        "withdrawal": 100,
        "runningBalance": 1000,
        "category": "CATEGORY",
        "transactionId": "ID"
      },
      {
        "accountId": "ID",
        "transactionDate": "2016-12-12",
        "description": "CANADA FED",
        "amount": 100,
        "deposit": 100,
        "runningBalance": 100,
        "category": "CATEGORY",
        "transactionId": "ID"
      }
    ]
  },
  "categories": [
    "CATEGORY",
    "CATEGORY",
    "CATEGORY",
    "CATEGORY",
    "CATEGORY",
    "CATEGORY",
    "CATEGORY",
  ]
}
```

## Remarks
- Feel free to use any boilerplates or frameworks as long as you can explain why you used one.
- Don't hesitate to ask any questions regarding the challenge.

## Bonus
- Filter transactions by a "from" and "to" date (ex. January 1st 2017 to January 18th 2017)
- Animations, transitions, other interactivity

## Good luck
We wish you the best of luck and can't wait to see what you create!
