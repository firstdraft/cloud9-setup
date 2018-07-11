# Cloud9 Setup
A student setup script for Cloud9


## Install

### Download the script

```
curl --remote-name https://raw.githubusercontent.com/firstdraft/cloud9-setup/master/cloud9_plugins.sh
```

### Execute the downloaded script

```
sh cloud9_plugins.sh
```

### Enable autoformatting for `.rb` and `.html.erb` files

From the `Cloud9` menu, select `Open Your Init Script` and add the following:

```
services.pluginManager.loadPackage([
  "~/.c9/plugins/formatruby/package.json",
  "~/.c9/plugins/formathtmlerb/package.json",
]);
```
