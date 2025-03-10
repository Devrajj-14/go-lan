# Real-time Collaboration Tool

A real-time collaboration tool built with Go, WebSockets, and modern web technologies. This tool allows multiple users to work on the same document simultaneously with real-time updates.

## Features

- Real-time text editing and updates
- Suggestion box for auto-completion
- Connection status indicator
- Modern and responsive design



## Getting Started

### Prerequisites

- Go 1.16+ installed
- Git installed

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Devrajj-14/real-time-collab.git
    cd real-time-collab
    ```

2. Install dependencies:
    ```bash
    go mod tidy
    ```

3. Run the application:
    ```bash
    go run main.go
    ```

4. Open your browser and navigate to `http://localhost:8080`.

### Usage

- Open the application in your browser.
- Start typing in the text area.
- Real-time updates will be shown as other users make changes.

### Suggestion Box

- The suggestion box appears when typing.
- Click on a suggestion to auto-complete the word.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some amazing feature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Acknowledgments

- [Gorilla WebSocket](https://github.com/gorilla/websocket) for WebSocket support.
- [Unsplash](https://unsplash.com/) for the background image.

---

Feel free to modify this template to better fit your project's needs. This template covers the essential sections that a good `README.md` file should have, including a project description, features, setup instructions, usage guidelines, license information, and contribution guidelines.

### Adding the README.md file

1. **Create the README.md file**:
    ```bash
    touch README.md
    ```

2. **Open the README.md file in a text editor and paste the template content**.

3. **Add the README.md file to your repository and commit it**:
    ```bash
    git add README.md
    git commit -m "Add README.md"
    git push
    ```

This will ensure that anyone visiting your GitHub repository will have a good understanding of what the project is about and how to get started with it.
