# Product Sales Tracker

A beginner-friendly Python automation project that converts product sales data from a text file into a structured CSV report.

## What It Does

The program:

- Reads product IDs from `product_sales.txt`
- Looks up each product's name and price
- Assigns a sale ID to every record
- Adds the current date
- Exports the completed data to `product_sales.csv`

## Project Structure

```text
product-sales-tracker/
├── project_solution.py
├── project_starter.py
├── product_sales.txt
├── product_sales.csv
├── .gitignore
└── README.md
```

## Requirements

- Python 3
- No external packages are required

## Run the Project

Open a terminal in the project folder and run:

```bash
python3 project_solution.py
```

The program creates or replaces `product_sales.csv`.

## Output Columns

The generated CSV contains:

- `current_date`
- `sale_id`
- `product_id`
- `product_name`
- `product_price`

## Example

```csv
current_date,sale_id,product_id,product_name,product_price
2026-07-14,1,P005,Mobile Phone Case,15
2026-07-14,2,P001,Wireless Headphones,100
```

The date in the generated file depends on the day the program is run.

## Technologies

- Python
- CSV file handling
- Text-file processing
- Dictionaries
- Loops

## Learning Note

This repository is a learning project completed while following a guided Python automation exercise (I like to do smthng crzy haha so here we go with first ill be doing more).
