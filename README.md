# Pinha - Collaborative Board Painting

Welcome to the **Pinha**, a Django-based web application where users can login and collaboratively change the color of small squares on a grid, creating artwork together in real-time!

## Features

- **Interactive Grid**: The board is divided into small squares, which users can click to change the color.
- **User Authentication**: Users must sign up and login to change the colors of the squares.
- **Public View**: Unauthenticated users can view the board but need to sign up or log in to participate in painting.
- **Collaborative Environment**: Anyone can log in and contribute to the evolving artwork.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/fthenri/pinha_project.git
   cd pinha
   ```
   
2. **Create a virtual environment** (optional but recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install the dependencies**:
   
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**:

   ```bash
   python manage.py migrate
   ```

5. **Run the Django development server**:

   ```bash
   python manage.py runserver
   ```

6. **Access the application**: Open your browser and go to http://127.0.0.1:8000/.

## Usage

- View the board: Anyone can access the board and see the current artwork.
- Login to interact: To start changing colors and contributing, you’ll need to sign up or log in.
- Start painting: After logging in, click on any square to change its color and start creating!

## Future Features (Planned)

User Roles: Different access levels for moderation or advanced users.
Color Palette: Let users choose from a wider range of colors.
Undo Feature: Allow users to revert changes made to the grid.
Real-Time Updates: Instantly update the board for all users as changes are made.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome!

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes and commit (git commit -m "Add some feature").
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.
   
## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, feel free to contact the project maintainer:

- **Henrique Tefile - henritefile@gmail.com**
- **GitHub: fthenri**
   
