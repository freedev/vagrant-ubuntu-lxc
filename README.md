# vagrant-ubuntu-lxc-cookbook

TODO: Enter the cookbook description here.

## Supported Platforms

TODO: List your supported platforms.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['vagrant-ubuntu-lxc']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### vagrant-ubuntu-lxc::default

Include `vagrant-ubuntu-lxc` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[vagrant-ubuntu-lxc::default]"
  ]
}
```

## License and Authors

Author:: Vincenzo D'Amore (<v.damore@gmail.com>)
