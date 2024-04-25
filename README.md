# Amazon Kindle Books Dataset Project

## Project Aim
- To clean, analyse and visualise the Amazon Kindle Books dataset.

## Objectives
This project answers the following questions:
- How many books have had more than 10,000 reviews?
- What are the 10 most expensive books on Amazon Kindle?
- How many books are there for each category?

Visualisations are also created to get insights on the following:
- The 10 categories with the most number of books.
- The frequency of ratings within different ranges.
- The relationships between the number of stars, number of reviews and prices.

## Data Understanding
The dataset contains the records for over 130,000 Kindle books available on Amazon. The dataset was originally created in October 2023, and was subsequently made available on Kaggle. This dataset was collected from Kaggle on 21st April 2024. Here is the link for it: https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books.

## Data Analysis
These are the first five and last five books with the highest number of reviews:
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/238a8bc2-7907-49f1-b8cc-c95ba8d732e1)

Here are the 10 most expensive books, starting with the most expensive book first:
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/6e1ab92e-995d-475e-a518-8c4f64867b4d)

The number of books in each category is listed as follows:
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/b485629e-8275-4593-a384-5c78bab6b039)

## Visualisations
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/8bf94772-a8fb-4d42-9726-391a4e0f258d)
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/a1ef9811-d4c5-4b53-b47b-81f50e9c0297)
![image](https://github.com/saemeqamar2024/amazon_kindle_books/assets/163443584/fdd0f777-2c09-4570-ac7e-85a5df5f90e0)

## Technologies Used
The Python libraries used were Pandas, Numpy, Matplotlib and Seaborn in Google Colab.

## Outcomes
Here is a summary of the findings from this project:

- There are 1834 books that have had more than 10,000 reviews. The most reviewed book is "Where the Crawdads Sing" by Delia Owens, with 618227 reviews.
- The most expensive book is "Drugs in Litigation: Damage Awards Involving Prescription and Nonprescription Drugs 2023 Edition" by LexisNexis Editorial Staff, which costs $682.00.
- Mystery, Thriller & Suspense, Engineering & Transportation and Science & Math are the top three categories containing the highest number of books.
- There are almost 120,000 books with a star rating of 4.0-5.0 stars.
- The pair plots reveal the following:
    - the price of a book is not correlated with the number of stars (rating).
    - The lower the price of a book, the more reviews it will have.
    - As the rating goes up, the number of reviews a book receives goes up.

## Note
The data used is from October 2023.
