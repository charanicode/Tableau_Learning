#  Day 17 – INCLUDE LOD Expressions

Welcome to Day 17 of my Tableau Learning Journey! 🚀

Today, I explored **INCLUDE Level of Detail (LOD) Expressions** in Tableau and practiced two different real-world scenarios to understand how INCLUDE works when dimensions are not directly available in a visualization.

## 📚 Topic Covered: INCLUDE LOD

### What is INCLUDE LOD?

The INCLUDE LOD expression allows us to add an additional dimension to the level of detail of a calculation, even when that dimension is not present in the current visualization.

### Syntax

```tableau
{ INCLUDE [Dimension] : AGG([Measure]) }
```

## 🧪 Practical Examples

### Example 1: Calculating Sales Using Sub-Category

**Objective:** Calculate sales at the Sub-Category level using INCLUDE, even when Sub-Category is not included in the visualization.

**Concepts Applied:**
- INCLUDE LOD expression.
- Adding Sub-Category as an additional level of detail.
- Calculating sales at a more granular level.
- Understanding how LOD expressions work independently of the dimensions displayed in the view.

### Example 2: Finding Achieved Target Using Product Name

**Objective:** Use Product Name in an INCLUDE LOD expression to calculate product-level values and identify target achievement.

**Concepts Applied:**
- INCLUDE LOD expression with Product Name.
- Product-level calculations.
- Comparing calculated values against target values.
- Understanding how additional dimensions affect aggregation.

## 🎯 Key Learnings

- Understood the purpose of INCLUDE LOD expressions.
- Learned how to perform calculations using dimensions that are not present in the visualization.
- Practiced Sub-Category-level sales calculations.
- Explored Product Name-level calculations for target achievement.
- Understood how INCLUDE adds additional detail before aggregation.
- Improved understanding of LOD expressions through practical examples.

## 🛠️ Tool Used

- Tableau

## 📈 Learning Outcome

Gained practical experience with INCLUDE LOD expressions and learned how to perform detailed calculations without displaying every dimension in the visualization.

Continuing my journey towards mastering Tableau and becoming a skilled Data Analyst!

---

**Day 17 Completed!** ✅

#Tableau #DataAnalytics #LODExpressions #INCLUDELOD #DataVisualization
