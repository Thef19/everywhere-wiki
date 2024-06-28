# Everywhere Wiki Skin
Welcome to the Everywhere Wiki Skin repository! This repository contains the custom skin designed specifically for the "Everywhere" game wiki. Our goal is to provide a visually appealing and user-friendly interface for all wiki visitors and contributors.

## Features
Custom Design: Tailored to match the aesthetic and theme of the "Everywhere" game.
Responsive Layout: Ensures a seamless experience on both desktop and mobile devices.
Enhanced Navigation: Improved menus and search functionality for easier access to content.
Customization Options: Allows for easy modifications and updates to the skin's appearance.

## Installation
To use the Everywhere Wiki Skin, follow these steps:

## Download the Skin:

1. Clone the repository to your MediaWiki installation's skins directory:
```sh
git clone https://github.com/your-repo/everywhere-wiki-skin.git skins/Everywhere
```

2. Enable the Skin:

Add the following line to your LocalSettings.php file:

```php
wfLoadSkin( 'Everywhere' );
```
3. Update Composer:

Run Composer to ensure all dependencies are installed:

```sh
composer update --no-dev
```
4. Clear Cache:

Clear MediaWiki's cache to apply the new skin:

```sh
php maintenance/update.php
```

## Usage
Once the skin is installed and enabled, it will be available for use on your wiki. You can set it as the default skin by adding the following line to your LocalSettings.php file:


```php
$wgDefaultSkin = 'Everywhere';
```

## Contributing
We welcome contributions to improve the Everywhere Wiki Skin. Here’s how you can contribute:

Fork the Repository:
Fork the repository on GitHub and clone it to your local machine.

Create a Branch:
Create a new branch for your feature or bug fix:

```sh
git checkout -b feature/your-feature-name
````
1. Make Your Changes:

Implement your changes and test them thoroughly.


2. Commit and Push:

Commit your changes and push them to your forked repository:

```sh
git add .
git commit -m "Description of your changes"
git push origin feature/your-feature-name
```

3. Create a Pull Request:

Open a pull request on GitHub, describing your changes and the problem they solve or the feature they add.

4. Code Style

Please follow the existing code style in the repository. Consistent formatting helps maintain readability and ease of maintenance.

## Issues
If you encounter any issues or have suggestions for improvements, please open an issue on GitHub. Provide as much detail as possible to help us understand and address your concern.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

Thank you for contributing to the Everywhere Wiki Skin! Together, we can make the wiki a better place for all "Everywhere" game enthusiasts.

