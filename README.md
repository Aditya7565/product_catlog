# ChazeFashion

ChazeFashion is a Django-based e-commerce web application for fashion products. It features a modern, responsive UI using Tailwind CSS and DaisyUI, and provides a complete shopping experience with user authentication, product catalog, filtering, cart, wishlist, and more.

## Features

- User authentication (signup, login, logout)
- Product catalog with filtering by category, season, price, fabric, and brand
- Product detail pages with reviews and ratings
- Shopping cart and wishlist functionality
- User profile management (avatar, address, wallet balance)
- Admin dashboard for managing products, orders, and users
- Responsive design with Tailwind CSS and DaisyUI

## Project Structure

```
ProductCatlog-master/
├── ChazeFashion/
│   ├── catalog/      # Product catalog app
│   ├── theme/        # Theme and UI customization
│   ├── static/       # Static files (CSS, JS, images)
│   ├── media/        # Uploaded media files
│   ├── templates/    # HTML templates
│   ├── settings.py   # Django settings
│   └── ...
├── manage.py
└── README.md
```

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/ProductCatlog-master.git
   cd ProductCatlog-master/ChazeFashion
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```

4. **Create a superuser (admin):**
   ```sh
   python manage.py createsuperuser
   ```

5. **Run the development server:**
   ```sh
   python manage.py runserver
   ```

6. **Access the app:**
   - Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## License

This project is for educational
