object waiters

attributes -

water_full = false

greet = "Good afternoon, may I take your order?"

menu = {steak: 13, fish: 10, soup: 5}

bill = 0

methods -

pitcher
  water_full = true

order
  p greet
    "Good afternoon, may I take your order?"

total
  menu[:steak] * 2 + menu[:soup]
    31

tax
  bill = 31 + (31 * 0.15)
    bill = 35.65
