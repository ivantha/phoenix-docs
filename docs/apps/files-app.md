## Files App

Files App provide the browsing functionality in the Phoenix client.

Its file hierarchy can be identified as,

```
--files
----icon
----js
----src
------components
--------File-Details.vue
--------File-Details-Buttonrow.vue
--------Files-App.vue
--------Tile.vue
------default.js
------mixins.js
```

* default.js - Loads the **files** app

### Sub components

| Name        | Function           |
| ------------- |:-------------|
| Files-App.vue      | Parent component |
| Files-Details.vue       | Right side menu when single/multiple files(s) is/are selected |
| Files-Details-Buttonrow.vue      | Button component containing options for **Download, Moving and Deleting** of the selected file(s) |
| Tile.vue      | Single row representing a file/directory |

