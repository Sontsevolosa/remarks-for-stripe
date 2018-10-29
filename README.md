# remarks for Stripe

token ID (example):
tok_KPte7942xySKBKyrBu11yEpf

credit card number (example):
4242 4242 4242 4242

CVV (example):
123


======================


create test token:
Stripe::Token.create(card: { number: "4242424242424242", exp_month: 10, exp_year: 2019, cvc: 314 })
