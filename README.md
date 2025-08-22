# Responsive Flower Photo Gallery 🌸

A beautiful and interactive photo gallery showcasing a variety of flowers. This project features a clean, responsive grid layout and an elegant lightbox effect for viewing full-size images.


## Features

-   **Responsive Grid Layout**: The gallery seamlessly adapts to any screen size, from mobile phones to desktop monitors.
-   **Interactive Lightbox**: Click on any image to open it in a beautiful, centered overlay.
-   **Easy Navigation**: Browse through images with next/previous arrows and keyboard support (arrow keys for navigation, Esc to close).
-   **Image Captions**: Each photo in the lightbox includes a title and an image counter (e.g., "Image 1 of 9").
-   **Minimalist Design**: A clean and modern UI that puts the focus on the images.
-   **Pure Frontend**: Built with only HTML, CSS, and JavaScript—no backend required.

## Technologies Used

-   **HTML5**: For the structure and content of the gallery.
-   **CSS3**: For styling, including a responsive CSS Grid layout.
-   **JavaScript (with jQuery & Lightbox2)**: For the interactive lightbox functionality.
    -   [jQuery](https://jquery.com/)
    -   [Lightbox2 Plugin](https://lokeshdhakar.com/projects/lightbox2/)

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You just need a modern web browser like Google Chrome, Firefox, or Microsoft Edge.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repository-name
    ```
3.  **Open the `index.html` file in your browser.**
    And that's it! You should see the flower gallery.

## How to Use

-   **View Images**: Click on any thumbnail in the gallery to open the lightbox view.
-   **Navigate**:
    -   Click the arrows on the left or right side of the image.
    -   Use the `Left Arrow` and `Right Arrow` keys on your keyboard.
-   **Close the Lightbox**:
    -   Click the "X" button in the corner.
    -   Press the `Escape` key on your keyboard.
    -   Click on the dark overlay outside the image.

## Customization

You can easily customize the gallery by following these steps:

1.  **Add Your Own Images**:
    -   Place your image files (e.g., in `.jpeg`, `.png` format) into the project folder.
    -   In `index.html`, add or modify the `<a>` and `<img>` tags inside the `<div class="gallery">` container.
    -   Update the `href` attribute to point to the full-resolution image and the `src` attribute to the thumbnail.
    -   Change the `data-title` attribute to set the caption for each image.

    Example:
    ```html
    <a href="path/to/your-large-image.jpg" data-lightbox="models" data-title="Your Image Caption">
        <img src="path/to/your-thumbnail.jpg">
    </a>
    ```

2.  **Change Styles**:
    -   Modify the `style.css` file to change colors, fonts, spacing, and other visual elements.
    -   The `lightbox.css` file contains the styles for the lightbox itself, which you can also customize if needed.

## License

This project is open source and available under the [MIT License](LICENSE.md).
