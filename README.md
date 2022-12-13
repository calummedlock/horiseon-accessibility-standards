# Improving Horiseon's website to meet accessibility standards

## Description

The marketing agency, Horiseon, wanted a codebase that follows accessibility standards to optimise their own site for search engines.

I modified the existing webpage to not only follow SEO best practices but also to make it accessible to disabled users.

### Design Changes

Initially, Horiseon wanted to retain the same website design and only improve the code.

However, after reviewing the website and considering Horiseon's requirements, I noticed that the color contrast was not sufficient in the Benefits sidebar, which would not make the website fully accessible as it would fail to meet WCAG 2.1 requirements.

Therefore, I changed the background color to white and the text to black.

### Coding changes

- Added HTML semantic elements to improve the structure and meaning of the content.
- Consolidated CSS selectors to make the code more efficient and easier to maintain.
- Ensured proper headings structure to improve the hierarchy and organisation of the content.
- Added comments to the CSS elements to make it easier for future developers to understand the code.
- Changed the title and meta description for better SEO.
- Removed emoji to improve accessibility for screen reader users.
- Added a line of script code to ensure that the copyright text uses the current year.
- Added a hidden selector to present proper heading structures to screen reader users without changing the website design too much.
- Sized down and optimised images for better website loading, this will also help with SEO as search engines prefer fast-loading websites.

## Installation

N/A

## Usage

The Horiseon website provides information about the services they offer and the benefits their clients can gain. The website was recently updated to meet WCAG 2.1 standards for better SEO and accessibility. Users can use the website to learn about Horiseon's services and the benefits they offer.

The comments can be viewed by accessing DevTools (`Ctrl+Shift+I` on Windows and Linux, `Command+Option+I` on macOS).

[Visit the website](https://calummedlock.github.io/horiseon-accessibility-standards/)

![A screenshot of Horiseon's website](assets/images/updated-website-screenshot.png)

## Credits

N/A

## License

Please Refer to the LICENSE in the repository.