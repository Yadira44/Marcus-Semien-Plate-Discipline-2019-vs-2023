import matplotlib.pyplot as plt

# Sample data 2019-2023
years = [2019, 2020, 2021, 2022, 2023, 2024]
bb_rate = [11.6, 10.6, 9.1, 7.3, 9.6, 8.9]  # Walk rate (BB%)
k_rate = [13.7, 21.2, 20.2, 16.6, 14.6, 14.6]  # Strikeout rate (K%)

# Create the graph
plt.figure(figsize=(10, 6))
plt.plot(years, bb_rate, marker='o', linestyle='-', label='Walk Rate (BB%)', color='blue')
plt.plot(years, k_rate, marker='s', linestyle='-', label='Strikeout Rate (K%)', color='red')

#label the points
for i, txt in enumerate(bb_rate):
    plt.text(years[i], bb_rate[i] + 0.3, f"{txt}%", ha='center', color='blue', fontsize=10)
for i, txt in enumerate(k_rate):
    plt.text(years[i], k_rate[i] + 0.3, f"{txt}%", ha='center', color='red', fontsize=10)

# Labels and title
plt.xlabel('Year')
plt.ylabel('Rate (%)')
plt.title('Walk Rate vs Strikeout Rate from 2019-2024')
plt.legend()
plt.grid(True)

#show only whole number years
plt.xticks(years)

plt.show()
