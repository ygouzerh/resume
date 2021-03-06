# Yohan Gouzerh's Resume


This is a modification of an [Hugo port](https://github.com/aerohub/hugo-orbit-theme) made by Pavel Kanyshev, of [Orbit](//github.com/xriley/Orbit-Theme) - great looking resume/CV template designed for developers by Xiaoying Riley.

## Where to find the website

You can visualize the website on [yohan.gouzerh.com](https://yohan.gouzerh.com)

## Current Status

[![Build Status](https://dev.azure.com/ygouzerh/resume/_apis/build/status/ygouzerh.resume?branchName=master&jobName=Deploy%20to%20https%3A%2F%2Fyohan.gouzerh.com)](https://dev.azure.com/ygouzerh/resume/_build/latest?definitionId=2&branchName=master)

## Contents

- [Installation](#installation)
- [Getting started](#getting-started)
    - [Configuring](#configuring)
    - [Test your site](#test-your-site)
	- [Build your site](#build-your-site)
- [Contributing](#contributing)
- [License](#license)


## Installation

This repository use a [submodule](https://github.com/ygouzerh/hugo-orbit-theme) for the theme.

In order to clone the submodule too, run : 

    $ git clone --recurse-submodules -j8 git@github.com:ygouzerh/resume.git

## Getting started

### Configuring

Open your just-copied `config.toml` and fill it with your data. All the page content may be configured throw one file.

### Test your site

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server -w

Now enter `localhost:1313` in the address bar of your browser.

### Build your site

Just run

	$ hugo

You'll find your resume files in `public` folder in the root of Hugo project.

## Contributing

Did you found a bug or got an idea? Feel free to use the [issue tracker](//github.com/ygouzerh/resume/issues). Or make directly a [pull request](//github.com/ygouzerh/resume/pulls).

## License

The original template is released under the Creative Commons Attribution 3.0 License. Please keep the original attribution link when using for your own project. If you'd like to use the template without the attribution, you can check out other license options via template author's website: themes.3rdwavemedia.com

As for Hugo port you may rewrite the "Ported for..." line with setting your name at the end of `config.toml`
	
	[params.footer]
        copyright = ""

