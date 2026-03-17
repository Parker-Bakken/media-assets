Media assets for SorcererCraft and other branches of that domain

## Note to self:

- To veiw raw file the URL needs to be in this order:

- https://raw.githubusercontent.com/
- [username]/
- [repo]/
- [branch]/
- [path/to/file]

## Once raw url is confirmed working by checking in an incognito browser (Url should take you to a page that only shows the image)

- Copy URL and add it to Google Sheet
- Then use the following JSON

{
  "type": "image",
  "src": "{{logo_url}}",
  "x": "95%",
  "y": "95%",
  "width": "15%",
  "opacity": 0.75
}
