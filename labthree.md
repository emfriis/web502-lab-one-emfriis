# WEB502 - Lab Three - Emily Friis

## Child Theme Creation in Wordpress:

In WordPress, making and editing a child theme is relatively simple. A new folder must be created in themes and its name must be followed by '-child'. Within the folder, you must create stylesheet and functions files, both referencing back to the parent theme so its style can be enqueued. The style.css folder can be used to overwrite elements of the parent theme, allowing for customisability. You can also add additional functionality through libraries such as jQuery.

![phpcall](https://i.imgur.com/osII6LS.png)

![stylesheet](https://i.imgur.com/pl0NDnQ.png)

## Page Layout and Style with CSS, HTML, & JavaScript Framework:

Using WordPress, HTML can be applied through the code editor within page editing, this can be done as normal, and once the page is saved and updated, the HTML will be formatted by WordPress and displayed on the corresponding page. 

CSS styling can be applied through using themes, wherein the style.css file can be editing to format the content of your website.

JavaScript or JavaScript Frameworks can also be accessed through themes, referencing them through the theme's functions.php file.

![html](https://i.imgur.com/7qpLEnc.png)

![cssandjs](https://i.imgur.com/kxwmHsv.png)

![page](https://i.imgur.com/sXaqDGZ.png)

## jQuery in WordPress:

A jQuery library is present in the installation of WordPress. This can be accessed through a 'wp_enqueue_scripts call' in a theme's functions.php file. When writing jQuery in a theme '$' can cause conflicts and so it is best to assign it to another variable:

![php](https://i.imgur.com/eVfQ5aw.png)

![js](https://i.imgur.com/I0u1nqO.png)

## Other Approaches:

### Angular JS vs React JS

|                   | Angular JS                                                 | React JS         |
|-------------------|------------------------------------------------------------|------------------|
| Structure         | Framework (Using RxJS Library)                             | Library          |
| Architecture      | Component Based                                            | Component Based  |
| Learning Curve    | Very Steep                                                 | Moderately Steep |
| DOM               | Real DOM (Although with similar performance to Virtual DOM | Virtual DOM      |
| App Size          | Smaller App Size                                           | Larger App Size  |
| Development Speed | Faster                                                     | Slower           |