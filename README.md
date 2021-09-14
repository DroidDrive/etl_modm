# etl_modm

This is a modm repository (+module) containing the [etl library](https://www.etlcpp.com/).



## How to use?

* include the repository in your modm project.xml

  ```xml
  <repository>
      <path>../libs/etl_modm/repo.lb</path>
  </repository>
  ```

* include the module in your modm project.xml

```xml
<module>etl_modm:etl</module>
```

* inside your porject, do 
  * `lbuild build`
  * `scons`