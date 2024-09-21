
# Flask Blog Website

This is a simple blog website built with Flask, where users can read posts, view individual post details, and get in touch via a contact form. The blog's content is dynamically loaded from an API.

## Features

- **Home Page**: Displays all blog posts with titles, subtitles, and author information.
- **Post Details**: View a single blog post by clicking on the title.
- **About Page**: Learn more about the blog or the author.
- **Contact Page**: Users can send a message through the contact form.
- **Dynamic Content**: Blog posts are fetched from an external API.

## Technologies Used

- Flask (Python web framework)
- HTML/CSS (for the frontend)
- Bootstrap (for responsive design)
- API Integration (to load blog posts)

## Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/MuhammadAliAbbasKhan/Flask-Blog-Website.git
    ```

2. Navigate into the project directory:

    ```bash
    cd Flask-Blog-Website
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:

    ```bash
    python app.py
    ```

5. Open your browser and visit:

    ```
    http://127.0.0.1:5001
    ```

## API Integration

- The blog posts are fetched from an API. You can use your own API link by replacing the current one in `app.py`:
    ```python
    posts = requests.get("YOUR_API_ENDPOINT").json()
    ```

## License

This project is licensed under the MIT License.
