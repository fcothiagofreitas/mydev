# Packages


## Package Control

```
ctrl+` or ctrl+'
```

Past this

```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) 
```

## On Package Control

### Theme

```
Material Theme

User Config:

"theme": "Material-Theme.sublime-theme",
"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
```

### List of others

* [Emmet](http://emmet.io/)
* [Git](https://github.com/kemayo/sublime-text-git)
* [GitGutter](https://github.com/jisaacks/GitGutter)
* [AllAutocomplete](https://github.com/alienhard/SublimeAllAutocomplete)
* [Terminal](https://github.com/wbond/sublime_terminal)
* [SublimeREPL](https://github.com/wuub/SublimeREPL)
* [ColorPicker](http://weslly.github.io/ColorPicker/)
* [SublimeLinter](https://github.com/titoBouzout/SideBarEnhancements/tree/st3)