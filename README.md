# postcss-sprites

> without svg-sprite

## declare

the original postcss plugin (repo [https://github.com/2createStudio/postcss-sprites](https://github.com/2createStudio/postcss-sprites)) depend on svg-sprite [https://github.com/jkphl/svg-sprite](https://github.com/jkphl/svg-sprite) for format image/svg , which relies on phantomjs-prebuilt , PhantomJS is quite a heavy dependency , make the installation process really slowly , so much as cause an error sometimes ,
in most cases we probably don't need svg-sprite , so i fork from postcss-sprites and abandon this part , that means this plugin won't support svg any more . someone need svg support should install postcss-sprites instead of this plugin .