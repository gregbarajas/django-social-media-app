# Simple Social Media App

This is a simple social media app built with Django that replicates some of the core functionalities of Twitter. Users can create accounts, post tweets, follow other users, and engage with tweets through likes and comments.

## Features

- **User Authentication**: Users can create an account, log in, and log out. Each user has a unique username and password.

- **Follow/Unfollow**: Users can follow and unfollow other users to see their tweets on their feed.

- **Post Tweets**: Users can post tweets with a character limit, similar to Twitter.

- **Like Tweets**: Users can like tweets to show their appreciation or agreement.

- **Comment on Tweets**: Users can comment on tweets to provide feedback or engage in discussions.

## Technologies Used

- **Backend**: Python, Django

- **Frontend**: HTML, CSS, JavaScript

## Setup Instructions

1. Clone the repository:

```
git clone https://github.com/gregbarajas/djangosmapp.git
```

2. Install dependencies:

```
cd djangosmapp
pip install -r requirements.txt
```

3. Set up the database:

Ensure you have PostgreSQL installed and running. Update the database configurations in `settings.py` to match your PostgreSQL settings.

4. Run database migrations:

```
python manage.py migrate
```

5. Start the development server:

```
python manage.py runserver
```

6. Open the app in your browser:

```
http://localhost:8000
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project was inspired by Twitter and its functionality.

Feel free to modify this README file according to your specific project requirements, additional instructions, or any other details you'd like to include.
