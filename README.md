# Kanji Vault

A web-based tool for exploring and learning Japanese Kanji. Kanji Vault provides a clean, searchable, and filterable interface to a comprehensive database of over 13,000 Kanji characters, making it an ideal resource for students of the Japanese language.

Users can easily filter Kanji by their Japanese Language Proficiency Test (JLPT) level, from N5 to N1, or browse the entire collection. The application is built with vanilla HTML, CSS, and JavaScript, ensuring it is lightweight, fast, and easy to modify.

## Features

-   **JLPT Level Filtering**: Interactively filter Kanji by JLPT levels (N1, N2, N3, N4, N5) as well as other common-use Kanji.
-   **Comprehensive Kanji Data**: Displays detailed information for each Kanji, including:
    -   Stroke count
    -   School grade
    -   Frequency of use
    -   On'yomi (音読み) and Kun'yomi (訓読み) readings
    -   English meanings
    -   JLPT level
-   **Live Search**: A powerful search bar that allows users to find Kanji by character, meaning, or reading (kana/romaji).
-   **Responsive Design**: A clean and modern user interface that is fully responsive and works on both desktop and mobile browsers.
-   **Client-Side Operation**: Runs entirely in the browser. No server-side backend is required, making it easy to host on any static web hosting service like GitHub Pages.
-   **Color-Coded Levels**: Each JLPT level is color-coded for quick visual identification.

## Technology Stack

-   **Frontend**: HTML5, CSS3, JavaScript (ES6+)
-   **Data**: JSON for storing and managing Kanji information.

## Setup and Usage

To run this project locally, you can simply open the `Kanjinew.html` file in your web browser.

For best results and to avoid potential CORS issues with `fetch()` when loading the JSON files, it is recommended to run it through a local web server.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/NajmusAdib/Kanji_Tool.git](https://github.com/NajmusAdib/Kanji_Tool.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Kanji_Tool
    ```

3.  **Start a local web server.** If you have Python 3 installed, you can run:
    ```bash
    python -m http.server
    ```
    If you have Node.js installed, you can use a package like `live-server`:
    ```bash
    npm install -g live-server
    live-server
    ```

4.  **Open your browser** and navigate to `http://localhost:8000` (or the address provided by your local server).

## Data Source

The Kanji data is sourced from a comprehensive JSON database, which includes information aggregated from various sources, aligned with JLPT levels and general use frequency. The data files are self-contained within the `data/` directory.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
