
# Special-Diagramation

Component that allows use and manage grids from backoffice 

## Configuration

### Step 1 

Add to your `manifest.json` the dependency `itgloberspartnercl.special-diagramation`

### Step 2

To declare this component you must configure the following properties.

```json
{
  "custom-grid": {
        "props": {
            "gridType": 3,
            "gap":14,
            "marginTop":10,
            "marginBottom":40
        },
        "children": [
            "flex-layout.row#item1",
            "flex-layout.row#item2",
            "flex-layout.row#item3",
            "flex-layout.row#item4",
            "flex-layout.row#item5",
            "flex-layout.row#item6"
        ]
    }
}
```


### `custom-grid` props

| Prop name    | Type            | Description    | Default value                                                                                                                               |
| ------------ | --------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | 
| `gridType`      | `enum`       | Allowed numbers of columns for the grid values(1 to 12)|`1`        |
| `gap`      | `number`       | Pixelof differenc between elements        | `5`        |
| `marginTop`      | `number`       | Top margin of this elemnt         | `10`        |
| `marginBottom`      | `number`       | Bottom margin of this element         | `10`        |

