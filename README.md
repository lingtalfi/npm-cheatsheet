npm cheatsheet
===================
2016-07-22



My npm cheatsheet.



### Create package.json file using cli
```bash
npm init
```



### Install/uninstall a module globally/locally

```bash
sudo npm install -g grunt-cli
sudo npm uninstall -g grunt-cli
sudo npm install grunt-sass
sudo npm uninstall grunt-sass
```

### Install/uninstall a module locally and update the package.json
```bash
npm install --save grunt-sass
npm uninstall --save grunt-sass
```


### Recreate/remove modules based on the content of package.json
```bash
npm install
npm prune
```




### List modules globally/locally
```bash
npm list -g 
npm list 
```

### Versions

- ^1.0.0: latest stable version
- *: latest bleeding edge version


