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

### Restart Server 
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

### Create iisnode.yml for node.js 

#### Disable all Debug info
```
loggingEnabled: false
devErrorsEnabled: false
debuggingEnabled: false
```

### Debug for nodejs on Azure
Reference: [Debug Node.js applications in Windows Azure Web Sites][1]

http://sitenam/app.js/debug/

[1]: http://tomasz.janczuk.org/2013/07/debug-nodejs-applications-in-windows.html
