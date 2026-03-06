# FastAPI Assignment -- Day 1

## Description

This project is part of FastAPI Internship Training. It demonstrates
building REST APIs using FastAPI in Python for a simple e‑commerce
store.

## Technologies Used

-   Python
-   FastAPI
-   Uvicorn
-   Swagger UI

## How to Run

Install dependencies: pip install fastapi uvicorn

Run the server: uvicorn main:app --reload

Open Swagger UI: http://127.0.0.1:8000/docs

## API Endpoints

GET /products\
Returns all products and total count.

GET /products/category/{category_name}\
Returns products filtered by category.

GET /products/instock\
Returns products that are in stock.

GET /store/summary\
Returns store summary including total products, in‑stock count,
out‑of‑stock count, and categories.

GET /products/search/{keyword}\
Search products by keyword (case‑insensitive).

GET /products/deals\
Returns cheapest and most expensive products.

## Project Structure

YOUR_UNIQUE_INTERNID_FASTAPI └── ASSIGNMENT 1 ├── main.py ├──
Q1_Output.png ├── Q2_Output.png ├── Q3_Output.png ├── Q4_Output.png ├──
Q5_Output.png └── README.md
