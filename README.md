***Image Scraper Flask Project***

---

**Introduction:**

This is a Flask web application designed to scrape images from various websites. The project leverages the Flask framework, a lightweight and versatile web application framework in Python, to provide a user-friendly interface for scraping images from URLs. Users can submit URLs of websites they want to scrape, and the application will crawl the provided URL, extract images, and display them on the webpage.

**Getting Started:**

To use this image scraper Flask project, follow the steps below:

1. Ensure you have Python and Flask installed: Make sure you have Python (version X.X or higher) and Flask installed on your system. You can install Flask using pip:

```bash
pip install Flask
```

2. Clone the repository: Clone this repository to your local machine using Git or download it as a zip file and extract it.

```bash
git clone https://github.com/slothengineer/image_scraper.git
```

3. Navigate to the project folder: Change your working directory to the location where you cloned/downloaded the repository.

```bash
cd image_scraper
```

4. Create a virtual environment (optional but recommended): It is good practice to create a virtual environment to keep your dependencies isolated from other projects.

```bash
python -m venv env
```

5. Activate the virtual environment (optional but recommended): Activate the virtual environment you just created.

```bash
# For Windows
env\Scripts\activate

# For macOS and Linux
source env/bin/activate
```

6. Install the required dependencies: Install the necessary Python libraries listed in the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

7. Run the Flask application: Start the Flask web server.

```bash
python app.py
```

8. Access the web application: In your web browser, navigate to `http://localhost:5000` to access the image scraper web application. From there, you can enter the URLs of websites you want to scrape images from.

**Project Structure:**

The project's folder structure is organized as follows:

```
image-scraper-flask/
  ├── app.py
  ├── static/
  │   ├── main.css/
  │   └── style.css
  ├── templates/
  │   └── base.html
      └── index.html
      └── result.html
  └── README.md
  └──images
  └──requirements.txt
```

- `app.py`: The main Flask application file that defines routes, handles user requests, and scrapes images from URLs.
- `static/`: A directory containing static files such as CSS and JavaScript.
- `templates/`: A directory containing HTML templates used for rendering the web pages.


