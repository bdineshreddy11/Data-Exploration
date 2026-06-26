# Excel Data Exploration

## Overview

This project demonstrates the use of fundamental Microsoft Excel functions for data analysis, logical operations, conditional calculations, and text manipulation. These functions are widely used to organize, summarize, and transform data efficiently.

---

## Concepts 

### Statistical Functions

Statistical functions help summarize numerical data and provide meaningful insights.

* **SUM()** – Adds all numeric values in a selected range.
* **COUNT()** – Counts the number of cells containing numeric values.
* **AVERAGE()** – Calculates the arithmetic mean of a range of values.

---

### Minimum and Maximum Functions

These functions identify the smallest and largest values in a dataset.

* **MIN()** – Returns the lowest value.
* **MAX()** – Returns the highest value.

---

### Logical Functions

Logical functions evaluate conditions and return different results based on whether the condition is true or false.

* **IF()** – Performs conditional checks and categorizes data based on specified criteria.

Example:

```excel
=IF(C2>=500,"High Price","Standard Price")
```

---

### Conditional Functions

Conditional functions perform calculations only when specific conditions are met.

* **SUMIF()** – Adds values that satisfy a given condition.
* **COUNTIF()** – Counts cells that meet a specified condition.

Examples:

```excel
=SUMIF(B:B,"Electronics",C:C)

=COUNTIF(C:C,"<100")
```
---

### Text Functions
Text functions extract or manipulate specific portions of text.

* **LEFT()** – Extracts characters from the beginning of a text string.
* **RIGHT()** – Extracts characters from the end of a text string.
* **MID()** – Extracts characters from the middle of a text string by specifying the starting position and length.

Examples:

```excel
=LEFT(A2,2)

=RIGHT(A2,2)

=MID(A2,3,3)
```

---
## Excel Functions Used

* SUM()
* COUNT()
* AVERAGE()
* MIN()
* MAX()
* IF()
* SUMIF()
* COUNTIF()
* LEFT()
* RIGHT()
* MID()

---
## Conclusion

This project highlights the practical use of essential Excel functions for analyzing, organizing, and transforming data. Mastering these concepts builds a strong foundation for data analysis, reporting, and business decision-making using Microsoft Excel.
