# X-lab Official Website

 Official website of X-lab open laboratory, you can view the site on http://www.x-lab.info.

 ![avatar](./static/img/xlab.png)

## Prerequisites

* **Software**: [Git][git-install], and [Hugo][hugo-install]. As an example of working configuration:
```bash
$ git --version
$ hugo version
```

* **Hardware**: 2 CPUs, 8GB memory RAM.

## Getting started

Make sure that you have installed `Git` and `Hugo`, **in particular**, you must install Hugo with its [extended_0.65+ version][hugo-version]. And then set

Steps:

1. Clone this project
```bash
$ git clone git@github.com:X-lab2017/xlab-website.git
```

2. Go to the project folder
```
$ cd xlab-website
```

3. Run the following command:
```bash
$ git submodule update --init --recursive
$ git clone https://github.com/gcushen/hugo-academic.git themes/academic
$ hugo server
```

The site will be ready after a while in `http://localhost:1313`.

4. Git commit:
Since the **Git cache of theme `academic`** comflict with the **Git of our main part `master`**, we need to remove it for `git commit`.
```bash
$ rm -r themes/academic/
$ git add .
$ git commit -m "<your commit name>"
$ git push
```

## Support

If you have any questions or feature requests, please feel free to submit an issue.

For developers, the `Git` is **necessary**, but the `Hugo` is **not necessary** if you do not want to view the site locally or generate some pages automatically, follow our [Contributing Guide][CONTRIBUTING] will undoubtedly lead you making changes to our site!


[git-install]: https://git-scm.com/downloads

[hugo-install]: https://gohugo.io/getting-started/installing/#quick-install

[hugo-version]: https://github.com/gohugoio/hugo/releases

[CONTRIBUTING]: ./CONTRIBUTING.md
