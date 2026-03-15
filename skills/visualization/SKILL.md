---
name: visualization
description: Create charts and visualizations — bar, line, scatter, heatmap, histogram using matplotlib, seaborn, or plotly
license: MIT
allowed-tools: Read Bash
metadata:
  version: "1.0.0"
  category: data-engineering
---

# Visualization

## Instructions

### Chart Selection Guide
| Data Type | Chart |
|-----------|-------|
| Categories (comparison) | Bar chart |
| Time series (trend) | Line chart |
| Two numeric variables | Scatter plot |
| Distribution | Histogram or box plot |
| Correlation matrix | Heatmap |
| Parts of a whole | Stacked bar (avoid pie charts) |

### Standards
- Always include a title, axis labels, and units
- Use colorblind-friendly palettes (e.g., seaborn "colorblind" or viridis)
- Sort bar charts by value, not alphabetically
- Start y-axis at 0 for bar charts
- Add gridlines for readability
- Annotate key data points when helpful
- Save charts as PNG at 150+ DPI

### Code Pattern
```python
import matplotlib.pyplot as plt
import seaborn as sns

fig, ax = plt.subplots(figsize=(10, 6))
# ... plot code ...
ax.set_title("Title")
ax.set_xlabel("X Label")
ax.set_ylabel("Y Label")
plt.tight_layout()
plt.savefig("chart.png", dpi=150)
plt.show()
```
