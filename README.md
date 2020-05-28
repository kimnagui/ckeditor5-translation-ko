# ckeditor5 korean translation

Korean translation file for ckeditor5

## Usage

```js
// react example
import React, { Component } from "react";
import CKEditor from "@ckeditor/ckeditor5-react";
import ClassicEditor from "@ckeditor/ckeditor5-editor-classic/src/classiceditor";
import "@kimnagui/ckeditor5-translation-ko"; // <-- 1. Add
...

export default class Editor extends Component {
    <CKEditor
        ...
        editor={ClassicEditor}
        config={{
            ...
            language: "ko", // <-- 2. Config
        }}
    />
```
