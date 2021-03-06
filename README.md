# Angular X File Upload [![Build Status](https://travis-ci.org/uniprank/ngxfileuploader.svg?branch=master)](https://travis-ci.org/uniprank/ngxfileuploader)

---

## About

**Angular ngx File Upload** is a module for the [@Angular](https://angular.io/) framework. Supports drag-n-drop upload, upload progress, validation filters and a file upload queue. It supports native HTML5 uploads. Works with any server side platform which supports standard HTML form uploads.

When files are selected or dropped into the component/directive, one or more filters are applied. Files which pass all filters are added to the queue. When file is added to the queue, for him is created instance of `{FileManager}` and uploader options are used for this object. After, items in the queue (queue$) are ready for uploading.

## Package managers
### NPM
```
npm install @uniprank/ngx-file-uploader --save
```
You could find this module in npm like [_angular ngx file uploader_](https://www.npmjs.com/search?q=uniprank%20ngxfileuploader).

### Module Dependency

Add `import { FileUploaderModule } from '@uniprank/ngx-file-uploader';` to your module header:

```
@NgModule({
    declarations: [ ],
    imports: [
       FileUploaderModule
    ],
    exports: [ ]
})
export class ExampleModule {
}
```

<p align="center">
  <img src="test-code/images/advanced-fileuploader.png" style="width:100%; height: auto;"/>
</p>

## Demos
1. [Simple example](http://uniprank.github.io/ngxfileuploader/example/#simple)
2. [Advanced example](http://uniprank.github.io/ngxfileuploader/example/#advanced)
3. [FileDrop Component example](http://uniprank.github.io/ngxfileuploader/example/#filedropexample)

## More Info

1. [Introduction](https://github.com/uniprank/ngxfileuploader/wiki/Introduction)
2. [Module API](https://github.com/uniprank/ngxfileuploader/wiki/Module-API)
3. [FAQ](https://github.com/uniprank/ngxfileuploaderwiki/FAQ)

## Browser compatibility
You could check out features of target browsers using http://caniuse.com/. For example, the [File API](http://caniuse.com/#feat=fileapi) feature.

| Feature/Browser  | IE 8-9 |  IE10+ | Firefox 28+ | Chrome 38+ | Safari 6+ | 
|----------|:---:|:---:|:---:|:---:|:---:|
| `<input type="file"/>` | + | + | + | + | + |
| `<input type="file" multiple/>` | - | + | + | + | + |
| Drag-n-drop | - | + | + | + | + |
| XHR transport (multipart,binary) | - | + | + | + | + |
| AJAX headers | - | + | + | + | + |

## Cloud testing systems

<p align="center">
  <a href="https://browserstack.com" target="_blank">
    <img src="https://uniprank.github.io/ngx-file-uploader/test/browserstack.svg?w=280px&h=auto" style="width:280px; height: auto;"/>
  </a>
</p>
Thanks to <a href="https://browserstack.com" target="_blank">BrowserStack</a> for allowing our team to test on thousands of browsers.