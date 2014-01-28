# About gosk-theme
======
  gosk-theme is a repo for [gosk generator](https://github.com/scottkiss/gosk).

# How to use
```bash
gosk-theme
      | - assets
            | - default-zh
            | - ...
      | - templates
            | - default-zh
            | - ...
```
under the assets and templates folder,each folder represent one theme(the folder'name is also the theme's name),and the assets folder put the css/javascript/image files,the templates folder put the golang template files.See above graphic,there is a folder named default-zh
under the assets and also a folder with the same name under the templates folder.So if you want to use the default-zh theme,do the following steps:

* copy the default-zh folder to the gosk project's assets folder.
* copy the default-zh folder to the gosk project's templates folder.
* open the config.yml file in the gosk project,and change the theme property who's old value is default to default-zh.

then rebuild the site.

# 如何使用
```bash
gosk-theme
      | - assets
            | - default-zh
            | - ...
      | - templates
            | - default-zh
            | - ...
```
如上结构图所示，在gosk-theme下有两个目录分别叫做assets和templates。其中，assets目录下存放的是
主题的css/javascrip/image文件。templates目录下存放的是对于主题的golang的模板文件。所有的文件都是以子目录的形式存放的，每个子目录的就代表一个主题，相应的目录名就是主题名称。例如，你想使用名叫default-zh的主题，那可以按照如下步骤，使得您可以应用该主题生成站点：

* 复制assets目录下的default-zh目录到gosk项目的assets目录下。
* 复杂templates目录下的default-zh目录到gosk项目的templates目录下。
* 修改gosk项目中的config.yml文件，将theme属性（原来的属性是default）修改为default-zh。

完成以上步骤，重新生成站点，就可以看到应用default-zh主题的站点了。

## License
View the [LICENSE](https://github.com/scottkiss/gosk-theme/blob/master/LICENSE) file
