# Payment Test Cases

1. Valid payment
Steps:
- Add product to cart
- Enter valid credit card
- Click Pay
Expected: Payment succeeds, confirmation email sent

2. Expired card
Steps:
- Enter expired credit card details
- Click Pay
Expected: Error message about expired card appears

3. Insufficient funds
Steps:
- Enter credit card with insufficient balance
- Click Pay
Expected: Payment declined message appears
