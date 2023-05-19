# My Personal Portfolio and Blog

This repository contains the source code and content for my personal portfolio and blog website built with Hugo, a fast and flexible static site generator. This website showcases my work, projects, and blog posts.

## Features

- Clean and minimalist design.
- Responsive layout for optimal viewing on different devices.
- Portfolio section to showcase my projects and work.
- Blog section to share my thoughts, ideas, and tutorials.
- Easy-to-use content management using Markdown.
- Integration of Bootstrap for enhanced styling and components.

## Prerequisites
To run and modify this website locally, you need to have the following installed on your machine:

- Hugo
- Git

## Getting Started

Follow the steps below to set up the website locally:

- Clone this repository to your local machine using the following command:

```
git clone https://github.com/your-username/hugo-portfolio-blog.git
```
- Navigate to the project's root
```
cd hugo-portfolio-blog
```
- Install the required dependencies by running:
```
hugo mod get -u ./...
```
- Start the local development server:
```
hugo server
```
Open your web browser and visit http://localhost:1313 to see the website.

## Customization

To customize the website according to your preferences, you can modify the following files and directories:

- config.toml: Update this file to change site-wide configurations such as site title, description, and social media links.
- content/: Add or modify Markdown files in this directory to create new pages, portfolio items, or blog posts.
- static/: Add your own static assets (images, CSS, JavaScript, etc.) in this directory.
- layouts/: Modify the HTML files in this directory to customize the website's layout and structure. You can use Bootstrap classes and components to enhance the design.

## Deployment
To deploy your website to a production server, you can follow these steps:

- Build the static files for deployment:
```
hugo --minify
```
- Copy the generated files from the public/ directory to your server or hosting provider.

## Contributing
Contributions are welcome! If you find any issues or want to suggest improvements, please submit an issue or create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

This website was built using the Hugo static site generator and incorporates Bootstrap for styling and components. Special thanks to the Hugo community and its contributors for their excellent work.

## Contact

If you have any questions or inquiries, feel free to reach out to me at guptaaryan16@gmail.com.

