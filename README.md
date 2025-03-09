# Universal Color Translator

This is a simple web tool that converts color names into their hexadecimal codes. It works dynamically without any hardcoded color values, using the browser’s built-in color recognition.

To use it, open `index.html` in the browser, enter a color name, and the hex code will be displayed along with a color preview.

### Setup and Execution

Download or clone the repository, then open `index.html` in any web browser. No additional setup or installation is needed.

### How It Works

This tool uses HTML, CSS, and JavaScript. Instead of storing a list of color names, it checks if the browser recognizes a given color, extracts the corresponding hex code, and displays it. Multi-word color names are automatically adjusted so they can be processed correctly.

### Testing

To check if it works, try entering a common color name like "blue" or "red." It should display the correct hex code and show a color preview. You can also enter multi-word colors like "sky blue" as "skyblue" (no spaces) to see if they work. If you enter an invalid color, you will see an error message.


