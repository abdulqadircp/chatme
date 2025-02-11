# PixelNet

## Overview
This project aims to develop a Django-based backend for a social media platform similar to Instagram. The backend will handle user authentication, media uploads, user interactions, and API endpoints for frontend integration. It ensures scalability, security, and high performance for a seamless user experience.

## Features
- **User Authentication**: Secure login, registration, and user management using Django Authentication.
- **Post Creation & Media Upload**: Users can create posts with images and videos.
- **Follow System**: Users can follow and unfollow other users.
- **Likes & Comments**: Users can like and comment on posts.
- **Stories Feature**: Temporary posts that disappear after 24 hours.
- **Direct Messaging**: Private messaging between users.
- **Notifications**: Real-time notifications for likes, comments, and follows.
- **Explore & Search**: Discover new users and trending posts.

## Tech Stack
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL / MySQL
- **Media Storage**: AWS S3, Cloudinary
- **Authentication**: Django Allauth, JWT-based authentication
- **Realtime Features**: Django Channels, WebSockets
- **Deployment**: Docker, Kubernetes, Nginx, Gunicorn

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/instagram-clone-backend.git
   ```
2. Navigate to the project directory:
   ```sh
   cd instagram-clone-backend
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Configure environment variables in a `.env` file.
6. Apply database migrations:
   ```sh
   python manage.py migrate
   ```
7. Start the development server:
   ```sh
   python manage.py runserver
   ```

## Roadmap
- [ ] Backend API Development
- [ ] Post & Media Upload Features
- [ ] Follow System Implementation
- [ ] Like & Comment Features
- [ ] Stories & Direct Messaging
- [ ] Explore & Search Optimization

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`feature/your-feature`).
3. Commit your changes.
4. Submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, reach out to `your-email@example.com` or open an issue on GitHub.

