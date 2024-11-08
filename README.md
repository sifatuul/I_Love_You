
# Love Prank Button

A fun prank webpage where a "Reject" button dodges attempts to be clicked, making the "Accept" button the only viable option! This project was created as a playful way to prank someone by forcing them to "accept" a declaration of love.

## Demo
When the user tries to click the "Reject" button, it moves to a random position on the screen. The "Accept" button, when clicked, redirects to a Facebook Messenger link.

## Features
- **Interactive UI**: The "Reject" button moves around dynamically, evading the user's cursor.
- **Playful Animation**: Smooth, sliding animation for button movements.
- **Personalized Link**: Clicking "Accept" redirects to a custom Messenger link.

## Getting Started

### Prerequisites
To run this project, you only need a web browser.

### Installation
1. Clone the repository or download the project files:
    ```bash
    git clone https://github.com/yourusername/love-prank-button.git
    ```
2. Navigate to the project folder:
    ```bash
    cd love-prank-button
    ```
3. Open `index.html` in your preferred web browser.

### Usage
- Open `index.html` in a web browser.
- Hover over the "Reject" button to see it move.
- Click the "Accept" button to be redirected to the custom link.

### Customization
- **Messenger Link**: To change the redirect link, update the URL in the `accept()` function in the `<script>` tag of `index.html`:
  ```javascript
  function accept() {
      window.location.href = "https://m.me/yourcustomlink";
  }
  ```
- **Styling**: Modify colors, fonts, and animations in the `<style>` section of `index.html` to customize the look.

## Built With
- **HTML** for structure
- **CSS** for styling and animations
- **JavaScript** for button movement logic

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Screenshot
![Screenshot](screenshot.png)

Have fun with this prank!
