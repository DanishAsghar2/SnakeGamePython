# Snake Game in Python

## How to Run the Game

1. Clone the Repository:

    ```bash
    git clone https://github.com/DanishAsghar2/SnakeGamePython.git
    ```

2. Navigate to the Project Directory:

    ```bash
    cd SnakeGamePython
    ```

3. Run the Game:

    ```bash
    python snake_game.py
    ```

    This command starts the game. Use the arrow keys to control the snake.

## Game Controls

- Arrow Keys: Control the direction of the snake.
- Esc: Exit the game.

## Customization

1. Change Snake Speed

    To adjust the speed of the snake, modify the following line in the `snake_game.py` file:

    ```python
    delay = 0.1  # Lower value increases speed
    ```

2. Change Colors

    You can customize the colors of the snake, food, and background by editing the corresponding variables:

    ```python
    snake_color = "green"
    food_color = "red"
    bg_color = "black"
    ```

3. Adjust Game Area

    The game area size can be modified by changing the screen setup:

    ```python
    screen.setup(width=600, height=600)
    ```

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.

2. Create a new branch:

    ```bash
    git checkout -b feature-name
    ```

3. Make your changes and commit:

    ```bash
    git commit -m 'Add a new feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature-name
    ```

5. Submit a Pull Request.
