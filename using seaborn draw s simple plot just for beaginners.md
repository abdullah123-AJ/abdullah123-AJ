- 👋 Hi, I’m @abdullah123-AJ
- 👀 I’m interested in ... coding,Data Science,Machine Learning,Deep Learning
- 🌱 I’m currently learning ... dataanylysis,data visualization,data extraction,python and its packges,machine learning,deep learning
- 💞️ I’m looking to collaborate on ... high platform compnies 
- 📫 How to reach me ... https://github.com/abdullah123-AJ/abdullah123-AJ.git



import seaborn as sns

# Load example dataset
tips = sns.load_dataset("tips")

# Create a scatter plot
sns.scatterplot(data=tips, x="total_bill", y="tip", hue="sex", style="time")

# Set plot title and labels
plt.title("Scatter Plot of Total Bill vs. Tip")
plt.xlabel("Total Bill")
plt.ylabel("Tip")

# Show the plot
plt.show()



