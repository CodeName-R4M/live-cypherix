# live-cypherix
A web project for managing events and teams at Spartanz.

## Overview
This project serves as a platform for managing events and teams at Spartanz, providing a user-friendly interface for organizing and accessing information.

## Features
- Toggle mobile menu for easy navigation
- Interactive event and card flipping functionality
- Responsive design for desktop and mobile views

## Tech Stack / Built With
- HTML
- JavaScript
- CSS

## Installation & Setup
```shell
git clone https://github.com/CodeName-R4M/live-cypherix.git
cd live-cypherix
```

## Usage
Example of toggling the mobile menu:
```javascript
function toggleMenu() {
    const navLinks = document.querySelector('.nav-links.mobile-menu');
    navLinks.classList.toggle('active');
}
```

## Project Structure
```
live-cypherix/
├── Events.html
├── Script.js
├── Styles.css
├── Teams.html
├── images/
├── index.html
```

## Contributing
Contributions are welcome. Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.