import matplotlib.pyplot as plt

#Data 2019-2014
years = [2019, 2020, 2021, 2022, 2023, 2024]
zone_swing = [66.5, 70.7, 69.7, 71.7, 72.9, 75.9]
chase_rate = [19.2, 18.7, 21.3, 24.8, 21.4, 25.2]
whiff_rate = [18.3, 23.3, 21.5, 20.6, 18, 20.2]
first_pitch = [23.7, 29.2, 29.7, 29.4, 36.4, 35.6]

#create the graph
plt.figure(figsize = (10,6))
plt.plot(years, zone_swing, marker='o', linestyle='-', label='Zone Swing %', color = 'red')
plt.plot(years, chase_rate, marker='o', linestyle='-', label='Chase %', color = 'orange')
plt.plot(years, whiff_rate, marker='o', linestyle='-', label='Whiff %', color = 'green')
plt.plot(years, first_pitch, marker='o', linestyle='-', label='1st Pitch Swing %', color = 'blue')

#data labels
for i, txt in enumerate(zone_swing):
   plt.text(years[i], zone_swing[i] + 0.3, f"{txt}%", ha='center', color='red', fontsize=10)
for i, txt in enumerate(chase_rate):
   plt.text(years[i], chase_rate[i] + 0.3, f"{txt}%", ha='center', color='orange', fontsize=10)
for i, txt in enumerate(whiff_rate):
   plt.text(years[i], whiff_rate[i] + 0.3, f"{txt}%", ha='center', color='green', fontsize=10)
for i, txt in enumerate(first_pitch):
   plt.text(years[i], first_pitch[i] + 0.3, f"{txt}%", ha='center', color='blue', fontsize=10)

#axis labels and title
plt.xlabel('Year')
plt.ylabel('Rate (%)')
plt.title('Plate Discipline Rates(%) 2019-2024')
plt.legend()
plt.grid(True)

#whole number years
plt.xticks(years)

plt.show()
