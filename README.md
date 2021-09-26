# adonisjs-components

## fileUpload.edge

File upload field with image preview. ([inspired from Vemto](https://vemto.app/blog/how-to-create-an-image-upload-viewer-with-alpinejs)

required: include alpinejs script.

example:

```html
  @!component('components/fileUpload', {
    src: formValues.picture ? await driveUrl(formValues.picture) : "",
    name: 'picture',
    accept: 'image/*'
  })
```
