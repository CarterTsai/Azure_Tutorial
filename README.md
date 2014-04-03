Azure Command 
---------------------
Reference : http://www.windowsazure.com/en-us/documentation/articles/xplat-cli/

### Install Command on Mac or Linux
```
$> sudo npm install azure-cli
```

### Connect to your Windows Azure subscription
```
$> azure account download 
```
that will download publishsettings file

### Import publishsettings
```
$> azure account import {path to .publishsettings file}
```

### Restart
```
$> azure site restart [sitename]
```


### Get Server Log
```
$> azure site log tail [sitename]
```

### Deploy

```
$> git push azure master
```
