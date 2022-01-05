# APM466_ASS2_Price_Protection_Plan
**Objective:**
- There's a price protection insurance in the form of a 4-upswing option with strike price $1.
- Use recombining trees, calculate the price of the price protection plan and decide optimal exercise nodes.

**Process:**
- First derive the 1-upswing option tree (equivalently one American call option) from the underlying asset's price tree.
![alter text](https://github.com/elenayinyin/APM466_ASS2_Price_Protection_Plan/blob/main/tree.png)

- Then derive the 2-upswing, 3-upswing, and 4-upswing option trees in order.
- Use of five trees in total and four times of backward propagation, get the price of the protection plan.

**Findings:**
- Find the pattern that almost all of optimal exercise nodes appear in the last four time periods.
- The later exercising call option is the better especially for non-dividend paying asset due to the maximum principle.
