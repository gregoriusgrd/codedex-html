# Welp! Review Form 📝
This project simulates a review form for the "Welp!" website, a platform where users can review various things such as books, movies, and public parks.

## How It Works
The form collects the following information from the user:
1. Reviewer's Name: The name of the person submitting the review.
2. Item Being Reviewed: The name of the item being reviewed (e.g., a book, movie, or park).
3. Would You Try Again?: A set of ```radio``` buttons to ask if the reviewer would try the item again.
4. Rating: An ```<input>``` field where the reviewer can give a rating (1 to 5).
5. Comments: A ```<textarea>``` where the reviewer can write up to 250 characters of feedback.
6. Submit Review: A ```button``` to submit the review.

## Form Validation:
- The Reviewer's Name, Item Being Reviewed, and Rating are required fields.
- The Rating ```<input>``` ensures the value is between 1 and 5.
- The Comments ```<textarea>``` restricts the input to 250 characters.

Check out the implementation in welp.html
