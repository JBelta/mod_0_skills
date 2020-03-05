object waiters

attributes -

on_shift = false

pay_rate = {host: 0, waiter: 0, cook: 0}

uniform_color = "White"

hours = 10

methods -

clock_in: on_shift = true

add_pay: pay_rate[:waiter] = 9

change_color: uniform_color = "Black"

pay_check: hours * pay_rate[:waiter] = 90
