# Pano Viewer

> A beautiful, high-res way to explore and share your panorma photos.

## Running Locally

You can run this repo locally to explore the examples and play around with the options.

To run this project, start it like you would any Jekyll site. eg:

    bundle exec jekyll serve -w

It runs in a subfolder to match the deployment location. You can open the page at:

    http://localhost:4000/pano-viewer/

## Adding images

1. Drop new panoramas in `panos/full-size`.
2. run `_sh/make-thumbs.sh panos/full-size panos/thumbs` (OSX only, uses `sips`) to generate thumbnails.

## TODO

- [x] Show a list of panorma urls
- [x] Support thumbnails/zoom in to full res
- [ ] Detect vertical panoramas, show them differently
- [ ] Support both list and full screen pano