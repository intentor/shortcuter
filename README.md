# ![Shortcuter](https://cloud.githubusercontent.com/assets/5340818/13428577/200885be-df9a-11e5-8eeb-e948ced30dee.png)

**Simple shortcut utility for Unity**

Currently the project is **DISCONTINUED**. However, feel free to fork it and continue its development!

[![Unity Asset Store](https://cloud.githubusercontent.com/assets/5340818/6855739/9e14c9e0-d3d9-11e4-9171-594941ed056f.png)](https://www.assetstore.unity3d.com/#!/content/57191)
 [![Donate](https://cloud.githubusercontent.com/assets/5340818/12418027/9434b3ea-be93-11e5-8395-253a3a1aade5.png)](http://donate.intentor.com.br/)
 
## Contents

1. <a href="#introduction">Introduction</a>
2. <a href="#features">Features</a>
3. <a href="#quick-start">Quick start</a>
3. <a href="#notes">Notes</a>
3. <a href="#changelog">Changelog</a>
4. <a href="#support">Support</a>
5. <a href="#license">License</a>

## <a id="introduction"></a>Introduction

*Shortcuter* is an easy to use simple shortcut utility for Unity.

It features a dockable window which can be configured with shortcuts to most frequently used scenes and project objects.

Compatible with Unity 5 and 4.

## <a id="features"></a>Features

* Quick access to your most used scenes and objects from a dockable window.
* Easy to use toggle based interface to select shortcuts.
* Configure shortcuts for most common Unity objects (Scenes, Scripts, Prefabs and more).
* Create shortcuts for custom objects.
* Persistent shortcuts data.

## <a id="quick-start"></a>Quick start

1\. Open *Shortcuter* by going to `Window/Shortcuter` or by using the keyboard shortcut (`CTRL + ALT + S` on Windows and `CMD + OPTION + S` on Mac).

![01](https://cloud.githubusercontent.com/assets/5340818/13431828/c57ca020-dfa9-11e5-9d38-b93d8378ac8c.png)

2\. When opening the *Shortcuter* window for the first time, no shortcuts are available. Click on `Edit shortcuts` to bring the shortcuts editor.

![02](https://cloud.githubusercontent.com/assets/5340818/13432397/27b50df2-dfac-11e5-82ba-c468ef4bf921.png)

**Hint:**  at any moment, you can also open the shortcuts editor by accessing the *Shortcuter* window context menu.

![03](https://cloud.githubusercontent.com/assets/5340818/13431827/c57a2886-dfa9-11e5-975a-78188943a376.png)

3\. From the shortcuts editor, you can add as many shortcuts as you want based on types available on your project and also configure the quantity and title of the columns displayed on the *Shortcuter* window.

![04](https://cloud.githubusercontent.com/assets/5340818/13431896/0845715c-dfaa-11e5-8e81-ba100da160bd.png)

![05](https://cloud.githubusercontent.com/assets/5340818/13431895/083db46c-dfaa-11e5-8e93-36895a149694.png)

4\. After selecting your most frequently used shortcuts, they'll be available on the *Shortcuter* window!

![06](https://cloud.githubusercontent.com/assets/5340818/13432396/27b26476-dfac-11e5-8f46-f3c6c4da64e3.png)

## <a id="notes"></a>Notes

1. The shortcuts data is stored at `Editor Default Resources/Shortcuts.asset`.
2. Custom objects should inherit from `UnityEngine.ScriptableObject` in order to be available on the type selection popup.

## <a id="changelog"></a>Changelog

Please see [CHANGELOG.txt](src/Assets/Plugins/Editor/Shortcuter/CHANGELOG.txt).

## <a id="support"></a>Support

Found a bug? Please create an issue on the [GitHub project page](https://github.com/intentor/shortcuter/issues) or send a pull request if you have a fix or extension.

You can also send me a message at support@intentor.com.br to discuss more obscure matters about *Shortcuter*.

## <a id="license"></a>License

Licensed under the [The MIT License (MIT)](http://opensource.org/licenses/MIT). Please see [LICENSE](LICENSE) for more information.
