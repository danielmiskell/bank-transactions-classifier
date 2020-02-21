# bank-transactions-classifier
A person who uses their bank account actively will have several regularly recurring transactions, due to bill payments, salary payments, subscriptions or habits in purchasing behavior. The objective is to create code that takes bank transaction data as input and returns a data structure which summarizes a single user’s regularly recurring transactions as output. The definition of a regularly recurring transaction is any debit or credit transaction to or from the same entity that happens at regular intervals. An example of the desired output of the final code is shown below:


recurring = get_recurring_transactions(transactions)

[
{
"entity_name": "Fake Company Salary", "income": true,
"period_days": 28.0, "typical_amount_cents": 85000
}, {
}, {
"entity_name": "Phone Subscription", "income": false,
"period_days": 27.5, "typical_amount_cents": 3499
1
} ]
