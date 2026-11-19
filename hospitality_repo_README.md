# Hospitality trading dashboard (Power BI)

A two-page Power BI report for a food-led pub, built to show where a small venue loses money and where demand outgrows capacity. All numbers are **sample data for illustration**, not a real business's figures.

## Page 1: Bar yield
![Bar yield page](images/page1-bar-yield.png)

- **Question:** which beer lines lose the most stock between keg and glass?
- **Finding (sample data):** rotating taps lose over twice as much beer as core lines, about £2,000 above a 4% target in 12 weeks.
- **Shows:** sales, gross margin, labour cost %, yield loss by tap, £ lost above target, weekly trend for core vs rotating lines.

## Page 2: Kitchen capacity and demand
![Kitchen capacity page](images/page2-kitchen-capacity.png)

- **Question:** is the kitchen turning away weekend demand?
- **Finding (sample data):** the kitchen sold out on 27 of 36 weekend days, turning away an estimated 360 covers (about £6.7k) in 12 weeks.
- **Shows:** average covers served vs kitchen capacity by day, estimated covers turned away, upstairs room hire by month, and sales on live-music nights vs other nights.

## How it was built
- Power BI and Power Query, using a star schema of sales, product, stock and kitchen tables.
- Each page leads with its finding as the title, so a manager gets the answer before reading the charts.

Built by Gana Cariappa.
