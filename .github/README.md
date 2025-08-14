![Avatar](/assets/img/avatar.jpg)
## Hi there 👋

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# Test

*Test is used a Jekyll theme for GitHub Pages. You can [preview after applying this theme what it looks like](https://zuhasite.github.io/Test).*
![Thumbnail of Test](thumbnail.png)

## Usage

To use the Minimal theme:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: pages-themes/minimal@v0.2.0
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
    ```

## Customizing

### Configuration variables

Minimal will respect the following variables, if set in your site's `_config.yml`:

```yml
title: [The title of your site]
description: [A short description of your site's purpose]
```

Additionally, you may choose to set the following optional variables:

```yml
show_downloads: ["true" or "false" (unquoted) to indicate whether to provide a download URL]
google_analytics: [Your Google Analytics tracking ID]
```

### Stylesheet

If you'd like to add your own custom styles:

1. Create a file called `/assets/css/style.scss` in your site
2. Add the following content to the top of the file, exactly as shown:
    ```scss
    ---
    ---

    @import "{{ site.theme }}";
    ```
3. Add any custom CSS (or Sass, including imports) you'd like immediately after the `@import` line

*Note: If you'd like to change the theme's Sass variables, you must set new values before the `@import` line in your stylesheet.*

### Layouts

If you'd like to change the theme's HTML layout:

1. For some changes such as a custom `favicon`, you can add custom files in your local `_includes` folder. The files [provided with the theme](https://github.com/pages-themes/minimal/tree/master/_includes) provide a starting point and are included by the [original layout template](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html).
2. For more extensive changes, [copy the original template](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html) from the theme's repository<br />(*Pro-tip: click "raw" to make copying easier*)
3. Create a file called `/_layouts/default.html` in your site
4. Paste the default layout content copied in the first step
5. Customize the layout as you'd like

### Customizing Google Analytics code

Google has released several iterations to their Google Analytics code over the years since this theme was first created. If you would like to take advantage of the latest code, paste it into `_includes/head-custom-google-analytics.html` in your Jekyll site.

### Overriding GitHub-generated URLs

Templates often rely on URLs supplied by GitHub such as links to your repository or links to download your project. If you'd like to override one or more default URLs:

1. Look at [the template source](https://github.com/pages-themes/minimal/blob/master/_layouts/default.html) to determine the name of the variable. It will be in the form of `{{ site.github.zip_url }}`.
2. Specify the URL that you'd like the template to use in your site's `_config.yml`. For example, if the variable was `site.github.url`, you'd add the following:
    ```yml
    github:
      zip_url: https://zuhasite.github.io/Test/download.zip
      another_url: another value
    ```
3. When your site is built, Jekyll will use the URL you specified, rather than the default one provided by GitHub.

*Note: You must remove the `site.` prefix, and each variable name (after the `github.`) should be indent with two space below `github:`.*

For more information, see [the Jekyll variables documentation](https://jekyllrb.com/docs/variables/).

## Roadmap

See the [open issues](https://github.com/pages-themes/minimal/issues) for a list of proposed features (and known issues).

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Welcome to the ZwSite Org Bangladesh! A vibrant hub of creativity, learning, and growth. Our community is dedicated to fostering innovation and collaboration among individuals from diverse backgrounds. Whether you're a tech enthusiast, a creative artist, or a curious learner, you'll find a welcoming space here. We are a collaborative team dedicated to creating innovative solutions and fostering knowledge sharing.

## Features
- **Feature 1**: Description of feature 1.
- **Feature 2**: Description of feature 2.
- **Feature 3**: Description of feature 3.

## Installation
To get started with the ZuhaWorldSite, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/zuhasite/test.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd test
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Run the project**:
   ```bash
   npm start
   ```

## Usage
Provide detailed information on how to use the project. Include code snippets, examples, and screenshots if necessary.

## Contributing
We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Submit a pull request.

Please ensure your code follows our [coding standards](link-to-coding-standards) and [contribution guidelines](link-to-contribution-guidelines).

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any questions, feel free to [reach out to the team](mailto:info@zuha.site).
