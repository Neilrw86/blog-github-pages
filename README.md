<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Cloud Native Journey Blog

Welcome to the Cloud Native Journey Blog repository! This repository contains the source code and content for my personal blog, where I document my technical learning journey in the realms of CI/CD, Kubernetes, Ansible, and Infrastructure as Code (IaC).

## Purpose

The purpose of this blog is to:

- Share tutorials and how-tos on setting up and using various tools and technologies.
- Provide insights and updates on my ongoing projects, including my homelab and cloud setups.
- Reflect on the challenges and successes I encounter along the way.
- Offer tips and best practices for working with CI/CD, Kubernetes, Ansible, and IaC.

## Repository Structure

- `_posts/`: Contains the markdown files for individual blog posts.
- `_pages/`: Contains additional pages for the blog, such as the front page and about page.
- `assets/`: Contains images and other static assets used in the blog.
- `_config.yml`: Configuration file for the Jekyll site.

## Continuous Integration (CI)

This repository leverages Continuous Integration (CI) to ensure that all posts and updates are thoroughly tested before being published. The CI pipeline includes:

- **Linting**: Ensuring that all markdown files adhere to consistent formatting and style guidelines.
- **Build Testing**: Verifying that the Jekyll site builds successfully without errors.
- **Deployment**: Automatically deploying the site to GitHub Pages upon successful completion of tests.

## Getting Started

To get started with this repository, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/blog-github-pages.git
    cd blog-github-pages
    ```

2. **Install dependencies**:
    ```bash
    bundle install
    ```

3. **Serve the site locally**:
    ```bash
    bundle exec jekyll serve
    ```

4. **Open your browser** and navigate to `http://localhost:4000` to see the site.

## Contributing

If you have suggestions or improvements, feel free to open an issue or submit a pull request. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2025 Neil Wylie &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
