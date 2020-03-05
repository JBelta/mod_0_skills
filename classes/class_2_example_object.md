object omallys

attributes -

taps = ["Guinness", "Smithwicks", "Harp"]

happ_hour = false

bar_token = 20

kegs = ["Guinness", "Smithwicks", "Harp"]

methods -

kicked: taps.delete("Harp")
 taps = ["Guinness", "Smithwicks"]

tap_in: taps << kegs[2]
 taps = ["Guinness", "Smithwicks", "Harp"]

after_five: happy_hour = true

give_token: bar_token -= 1 = 19
