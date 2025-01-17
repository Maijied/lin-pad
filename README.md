# Linpad

<img src="./lin_logo.webp" alt="Linpad Logo" width="200" height="200">

**Linpad** is a minimalist text editor for Ubuntu, featuring syntax highlighting, word count functionality, and a clean user interface. It's designed for developers and casual users alike, providing basic text editing functions with plans for continuous improvement.

## Features

- Syntax highlighting for Python keywords.
- Word count functionality.
- Replace and find functionality.
- Toggle between dark and light modes.
- Zoom in and out
- Font customization
- Open-source and available for community contributions.

## Folder Structure

![Linpad in Action](./screenshots/linpad_screenshot.png)

## Installation

### Install via `.deb` Package:

1. Clone the repository:
    ```bash
    git clone https://github.com/Maijied/linpad
    cd linpad
    ```

2. Build and install the `.deb` package:
    ```bash
    dpkg-deb --build linpad
    sudo dpkg -i linpad.deb
    ```

3. Run Linpad:
    ```bash
    linpad
    ```

4. Alternatively, launch it from your desktop applications menu.

### Manual Installation:

1. Clone the repository:
    ```bash
    git clone https://github.com/Maijied/linpad
    cd linpad
    ```

2. Install dependencies:
    ```bash
    sudo apt install python3 python3-tk
    ```

3. Run the application:
    ```bash
    python3 linpad.py
    ```

## Installation via Setup script

To install Linpad, you can use the provided `setup.sh` script.

### How to Use setup.sh

1. **Make the Script Executable:**  
   First, you need to make the `setup.sh` file executable:
   ```bash
   chmod +x setup.sh
   ```
2. **Run the Script:**  
   Then, you can run the setup script with::
   ```bash
   ./setup.sh
   ```

## Dependencies

The application requires the following packages to be installed:

- `python3`
- `python3-tk`
- `python3-pil`
- `python3-pil.imagetk`

### Installation

You can install these dependencies using the following command:

```bash
sudo apt update
sudo apt install python3 python3-tk python3-pil
```

## Contributing

This project is open-source and welcomes contributions from developers! We encourage developers to suggest new features, report issues, and improve functionality. Let me know if you have some good ideas to make Linpad even better.

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to your branch: `git push origin feature-name`.
5. Open a pull request, and we'll review it.

Check out the [CONTRIBUTING.md](CONTRIBUTING.md) file for more details on contributing.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Future Roadmap

- Add more syntax highlighting languages.
- Improve the user interface.
- Add plugin support for developers to expand Linpad's functionality.

---

## Contact

If you encounter any issues or have suggestions for improvement, feel free to open an issue or reach out.

---

*Linpad is designed to be lightweight and functional, with many features planned for the future. Join us in developing and improving Linpad!*
