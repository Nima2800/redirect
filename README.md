# redirect

A tiny GitHub Pages site that sends visitors from `task.nimalog.ir` to [https://nima280.pythonanywhere.com](https://nima280.pythonanywhere.com).

## About

`index.html` uses a meta refresh so the browser leaves this page immediately. The custom domain is set in `CNAME`.

## Usage

Publish this repository with GitHub Pages. Requests to the custom domain load `index.html`, which redirects to the destination above. To change where people land, edit the `url` in the meta refresh tag.
