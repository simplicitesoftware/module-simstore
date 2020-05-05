<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`SimStore` module definition
============================

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=com.simplicite.modules%3ASimStore&metric=alert_status)](https://sonarcloud.io/dashboard?id=com.simplicite.modules%3ASimStore)

### Introduction

This is a **application store** management module.

### Import

To import this module:

- Create a module named `SimStore`
- Set the settings as:

```json
{
	"type": "git",
	"origin": {
		"uri": "https://github.com/simplicitesoftware/module-simstore.git"
	}
}
```

- Click on the _Import module_ button

### Configure

The URL(s) of your store file(s) is in the `` system parameter.

### Quality

This module can be analysed by the **SonarQube** analysis tool
using this command:

```bash
mvn verify sonar:sonar
```

`StoStore` external object definition
-------------------------------------




