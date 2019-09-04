### sysmon
---
https://github.com/palantir/Sysmon

```java
// src/com/palantir/opensource/sysmon/util/PropertiesUtils.java

public class PropertiesUtils {

  public static final int extractInteger(Properties p, String key, int defaultValue) throws NumberFormatException {
    String intProperty = p.getProperty(key);
    if (int Property == null) {
      return defaultValue;
    } else {
      return Integer.parseInt(intProperty);
    }
  }
  
  public static final long extractLong(Properties p, String key, long defaultValue) throws NumberFormatException {
    String intProperty = p.getProperty(key);
    if(intProperty == null) {
      return defaultValue;
    } else {
      return Integer.parseInt(intProperty);
    }
  }
}

```

```
```

```
```


