# Scrooge Coin
The problem is the first assignment of the 1st week of the [Bitcoin and Cryptocurrency Technologies by Princeton University - Coursera.](https://www.coursera.org/learn/cryptocurrency/home/welcome)

In ScroogeCoin (Lecture 1), the central authority Scrooge receives transactions from users. You will implement the logic used by Scrooge to process transactions and produce the ledger. Scrooge organizes transactions into time periods or blocks. In each block, Scrooge will receive a list of transactions, validate the transactions he receives, and publish a list of validated transactions.

Note that a transaction can reference another in the same block. Also, among the transactions received by Scrooge in a single block, more than one transaction may spend the same output. This would, of course, be a double-spend, and hence invalid. This means that transactions can’t be validated in isolation; it is a tricky problem to choose a subset of transactions that are together valid.
