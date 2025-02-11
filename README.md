# DoTweet

The GitHub repository [DoTweet](https://github.com/Ritul-Raj/DoTweet) is a Twitter clone built using Django and Django REST framework. It features user authentication, tweet creation, and a RESTful API for managing tweets. The project is designed to help developers understand how to implement a microblogging platform with Django.

**Features:**

- User authentication (registration and login)
- Create, read, update, and delete tweets
- Follow and unfollow users
- Like and unlike tweets
- RESTful API for managing tweets

**Installation:**

1. Clone the repository:

   ```bash
   git clone https://github.com/Ritul-Raj/DoTweet.git
   cd DoTweet
   ```

2. Create a virtual environment and activate it:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:

   ```bash
   python manage.py migrate
   ```

5. Create a superuser account:

   ```bash
   python manage.py createsuperuser
   ```

6. Start the development server:

   ```bash
   python manage.py runserver
   ```

7. Access the application at `http://127.0.0.1:8000/`.

**API Endpoints:**

- `/api/tweets/`
  - GET: List all tweets
  - POST: Create a new tweet

- `/api/tweets/<id>/`
  - GET: Retrieve a specific tweet
  - PUT: Update a specific tweet
  - DELETE: Delete a specific tweet

**Contributing:**

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

**License:**

This project is licensed under the MIT License.

For more details, please refer to the [GitHub repository](https://github.com/Ritul-Raj/DoTweet). 
