# CKAS Official Website

 Official website of project CKAS, you can view the site on http://www.x-lab.info.

## Prerequisites

* **Software**: [Git][git-install], and [Hugo][hugo-install]. As an example of working configuration:
```bash
$ git --version
$ git version 2.30.1
$ hugo version
$ hugo v0.85.0+extended darwin/amd64
```

* **Hardware**: At least 2 CPU cores, 8GB memory RAM.

## Getting started

Make sure that you have installed `Git` and `Hugo`, **in particular**, you must install Hugo with its [extended_0.65+ version][hugo-version]. And then set

Steps:

1. Clone this project
```bash
$ git clone git@github.com:gonggongjohn/ckas-website.git
```

2. Go to the project folder
```
$ cd ckas-website
```

3. Run the following command:
```bash
$ rm -r themes/academic/
$ git submodule update --init --recursive
$ hugo server
```

The site will be ready after a while in `http://localhost:1313`.

## Support

If you have any questions or feature requests, please feel free to submit an issue.

For developers, the `Git` is **necessary**, but the `Hugo` is **not necessary** if you do not want to view the site locally or generate some pages automatically, follow our [Contributing Guide][CONTRIBUTING] will undoubtedly lead you making changes to our site!


[git-install]: https://git-scm.com/downloads

[hugo-install]: https://gohugo.io/getting-started/installing/#quick-install

[hugo-version]: https://github.com/gohugoio/hugo/releases

[CONTRIBUTING]: ./CONTRIBUTING.md
