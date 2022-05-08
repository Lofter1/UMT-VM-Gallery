# UTM Image Repository

[![github pages](https://github.com/Lofter1/UMT-VM-Gallery/actions/workflows/gh-pages.yml/badge.svg)](https://github.com/Lofter1/UMT-VM-Gallery/actions/workflows/gh-pages.yml)

A static web page built with [Hugo](https://gohugo.io) that collects UTM Images.

> DISCLAIMER  VMs on this site are user produced content. Any use of the provided files is at your own risk. If you have concerns about an image, please open an issue.

## Contributing

In order to contribute, create a markdown file inside `content/utf-images` and open a pull request.

Keep in minde that the actual image is not being stored in this project, so you need to have a place to store it online, such as GitHub Releases or public accessible cloud storage.

### The markdown file

The easiest way to create the md file is using the [Hugo CLI](https://gohugo.io/getting-started/installing/) using 

```sh
hugo new content/{name}.md
```

This will automatically use the `utf-images` archetype for the file and create it with a ready-to-go boiler plate.

#### File naming convention

The file should be named in simple kebab-case. You should avoid characters like `()[]/\_`. 

### Thumbnails and images

Images are stored in `static/images/{name}/` and you only need to specify the filenames of the images. The path will be added automatically. In order for that to work, however, you must name the directory exactly the same as you markdown-file. So if you markdown-file is called `arch-linux-arm.md`, your images need to be stored inside `static/images/arch-linux-arm`.

Also keep in mind that the images will be shown in 16:9, so while it is possible to add images with another ratios, they will most likely look slightly distorted on the website.

### Testing your markdown file

If you want to see how your entry would look like online, you can run this repository using 

```sh
hugo server
```

### Pull Request naming conventions

If you add an image, your PR should start with the word `add`, if you edit one `update`, followed by the name of the image you want to add or change.
