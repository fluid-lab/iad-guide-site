# IAD Guide Site Demo

## Installation

1. Install Hugo. For instructions, visit the [Hugo install guide](https://gohugo.io/getting-started/installing/) on gohugo.io.
2. After installing Hugo, clone this repository:
        git clone https://github.com/fluid-lab/iad-guide-site
3. Clone the `iad-guide-theme` into the Hugo `themes/` directory:
        git clone https://github.com/fluid-lab/iad-guide-theme ./iad-guide-site/themes/iad-guide-theme

## Set Up the Site

1. Change directories to `iad-guide-site`.
2. Open the `config.toml` file in a text editor and confirm the following values:
        baseURL = "http://localhost:1313"
        theme = "iad-guide-theme"
*Note:* the theme value should match the directory name for the theme.
3. Save any changes and quit the text editor.
4. From the command prompt, run `hugo server` to start the Hugo web server.
5. Open http://localhost:1313 in a web browser.
6. The IAD Guide demo site should be displayed.

## License and Copyright

IAD Guide Theme &copy; 2017 OCAD University, [BSD-3-Clause](https://github.com/fluid-lab/iad-guide-theme/blob/master/LICENSE).

Portions:
Hugo &copy; 2013 - 2017 Steve Francia, [Apache 2.0](https://github.com/gohugoio/hugo/blob/master/LICENSE.md).
