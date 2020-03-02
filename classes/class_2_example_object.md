object back_bar

attributes -

taps = ("Fat Tire", "New Castle", "Stella")

ice_machine = true

tab = {wine: 8, cocktail: 6}

happy_hour = false

methods -

kicked("New Castle")
  taps = ("Fat Tire", "Stella")

after_five?
  the time is 17:01
  happy_hour = true

order("Stella")
  tab = {wine: 8, cocktail: 6, draft: 4}

ice_switch
  ice_machine = true
