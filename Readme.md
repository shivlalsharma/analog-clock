# Analog Clock

An interactive and visually appealing analog clock built with HTML, CSS, and JavaScript. This clock updates in real-time, displaying the current time with moving hour, minute, and second hands. The project features a modern dark theme with vibrant clock hands for enhanced visibility.

## Features

- **Real-time Clock**: The clock displays the current time with accurate real-time updates.
- **Smooth Hand Movement**: The clock hands (hour, minute, second) rotate smoothly as time passes.
- **Responsive Design**: The design is fully responsive, making the clock look great on both desktop and mobile screens.
- **Modern Design**: Uses a dark blue background with vibrant clock hands (yellow-orange for hour, blue for minute, and red for second).
- **Clock Customization**: The clock hands' colors and sizes can be customized using inline CSS variables.

## Technology Used

- **HTML**: For the basic structure of the clock and elements.
- **CSS**: For styling the clock, including layout, animations, and colors.
- **JavaScript**: For calculating and updating the clock hands' rotations based on the current time.

## How It Works

1. **HTML Structure**: The clock is contained within a `div` element with class `clock`. Each hand of the clock (hour, minute, second) is represented as a `div` with a class of `hand` and styled to rotate.
2. **CSS for Styling**: The clock background, hands, and numbers are styled using CSS. The hands rotate based on calculated degrees, which are determined by the current time.
3. **JavaScript for Real-Time Updates**: A `setInterval` function is used to update the rotation of the hands every second by calculating the appropriate angles based on the current hour, minute, and second.

## Installation

To run this project locally, follow the steps below:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/shivlalsharma/analog-clock.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd analog-clock
    ```

3. **Open the Project**:
    - Open the `index.html` file in your browser.
    - The analog clock should display on your screen.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created and deployed by **Shivlal Sharma**.  
- **GitHub**: [Shivlal Sharma's GitHub](https://github.com/shivlalsharma)
- **LinkedIn**: [Shivlal Sharma's LinkedIn](https://www.linkedin.com/in/shivlal-sharma-56ba5a284/)