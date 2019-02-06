# Text Indent 

Plugin for Ckeditor that add the ability to indent the first line of a paragraph by clicking the icon or bind a key to the plugin

## Getting Started

First you will need to download the plugin at ... 

### Prerequisites

You only need Ckeditor running

### Installing

After downloading the plugin you will need to extract it in the plugins folders of Ckeditor and add the following

```
  CKEDITOR.config.extraPlugins = 'textindent';
```

Or you just need to download Ckeditor with the plugin selected and it will be working out of the box 

## Options

You can choose the indentation value using the var indentation and sending a value acpetable by the text-indent property, the default is 50px.

```
  CKEDITOR.replace("text", {
     indentation: 10px,
  });
```                    

You can choose the key to bind to the plugin, or none at all, using the var indentationKey seding the name of the key or the keyCode, the default is the tab key.

By key name:
```
  CKEDITOR.replace("text", {
   indentation: 'a',
  });
```
By KeyCode:
```
  CKEDITOR.replace("text", {
    indentation: 65,
  });
```
Disabling the key bind functionality:
```
  CKEDITOR.replace("text", {
    indentation: false,
  });
```  
For knowing the [KeyCode](https://keycode.info/) map.

## Authors

* **Gabriel Lorenzo** - *Initial work* - [Teteruga](https://github.com/Teteruga)

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
