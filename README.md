# Strapi application
https://strapi.io/blog/how-to-change-the-default-wysiwy-to-quill-editor

https://quilljs.com/docs/formats/

# Действия
yarn strapi generate:plugin wysiwyg

cd plugins/wysiwyg
yarn add react-quill

### MediaLib
Create a 
./plugins/wysiwyg/admin/src/components/MediaLib/index.js
./plugins/wysiwyg/admin/src/components/Wysiwyg/index.js
./plugins/wysiwyg/admin/src/components/QuillEditor/index.js

Replace the content of your ./plugins/wysiwyg/admin/src/index.js
