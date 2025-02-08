# Global Internet Usage Analysis (2000-2023)
## 📊 Project Overview
This project analyzes global internet usage patterns from 2000 to 2023, exploring the digital divide between nations and tracking the evolution of internet adoption worldwide. The analysis includes visualizations of usage trends, growth rates, and geographical distributions of internet penetration.

## 🎯 Objectives
- Track and analyze global internet usage patterns over a 23-year period
- Identify regions and countries with significant growth in internet adoption
- Highlight persistent digital divides and areas needing improvement
- Provide insights into the factors influencing internet adoption rates

## 💾 Data Description
The primary dataset (`internet_usage.csv`) contains yearly internet usage statistics for countries worldwide from 2000 to 2023.

### Data Structure
| Column Name | Description |
|------------|-------------|
| Country Name | Name of the country |
| Country Code | Three-character country code |
| 2000-2023 | Percentage of population using the internet for each year |

## 📈 Visualizations
The project includes six key visualizations:
1. Line graph of high-performing countries' internet usage
2. Line graph of countries with lower internet penetration
3. Bar chart of top 20 countries with rapid growth
4. World map showing internet usage in 2000
5. World map showing internet usage in 2023
6. World map displaying growth rates

## 🔑 Key Findings
1. **Global Progress**
   - Most developed nations achieved >95% internet penetration by 2023
   - Gulf states showed the most dramatic improvement
   - Nordic countries maintained consistently high usage rates

2. **Digital Divide**
   - Central African nations continue to have <20% penetration
   - Significant disparities persist between developed and developing nations
   - Some regions show minimal growth over the 23-year period

3. **Regional Patterns**
   - Europe and North America: Early and consistent high adoption
   - Middle East: Fastest growth rates
   - Africa: Continuing challenges with digital access
   - Asia: Mixed results varying by economic development

## 🛠️ Tools & Technologies
- Python for data analysis
- Pandas for data manipulation
- Matplotlib/Seaborn for visualizations
- Geographical plotting libraries for world maps

## 📁 Repository Structure
```
├── data/
│   └── internet_usage.csv
├── visualizations/
│   ├── line_graphs/
│   ├── bar_charts/
│   └── world_maps/
├── analysis/
│   └── notebook.ipynb
└── README.md
```

## 🚀 Getting Started
1. Clone the repository
```bash
git clone https://github.com/QKData/global-internet-analysis.git
```

2. Install required dependencies
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook
```bash
jupyter notebook analysis/internet_analysis.ipynb
```

## 📊 Usage Examples
```python
# Load the dataset
import pandas as pd
df = pd.read_csv('data/internet_usage.csv')

# Basic analysis example
yearly_averages = df.mean(numeric_only=True)
```

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors
- Tran Quang Kien

## 📧 Contact
For any queries regarding this analysis, please contact:
- Email: quangkiendata@gmail.com
- GitHub: [@QKData](https://github.com/QKData)

## 🙏 Acknowledgments
- Data sources and any third-party resources used
- Contributors and reviewers
- Organizations that provided support or resources