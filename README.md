def convert_currency(amount, rat):
    return amount * rate

if __name__ == "__main__":
    amount = 100  # for example: 100 USD
    rate = 0.92   # example: USD → EUR conversion rate
    print(f"Converted amount: {convert_currency(amount, rate)}")

