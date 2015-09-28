# bitmonk_java-cookbook

This is an example wrapper cookbook for java and tomcat.

## Supported Platforms

Technically, anything with OpenJDK 8 and Tomcat 8 packages, currently tested against:

  * Ubuntu 15.04
  * Debian 8.2
  * CentOS 7.1

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['java']['jdk_version']</tt></td>
    <td>Integer</td>
    <td>Major Java version number</td>
    <td><tt>8</tt></td>
  </tr>
  <tr>
    <td><tt>['tomcat']['base_version']</tt></td>
    <td>Integer</td>
    <td>Major Tomcat version number</td>
    <td><tt>8</tt></td>
  </tr>
</table>

## Usage

### bitmonk_java::default

Include `bitmonk_java` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[bitmonk_java::default]"
  ]
}
```

## License and Authors

Author:: Justin Alan Ryan (<bitmonk@icloud.com>)
