[![Build Status](https://travis-ci.org/advanced-rest-client/anypoint-radio-group.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/anypoint-radio-group)  

# anypoint-radio-group

`<anypoint-radio-group>` A group of Anypoint radio buttons

`anypoint-radio-group` allows user to select at most one radio button from a set.
Checking one radio button that belongs to a radio group unchecks any
previously checked radio button within the same group. Use
`selected` to get or set the selected radio button.
The `<anypoint-radio-buttons>` inside the group must have the `name` attribute
set.

Example:
```html
<anypoint-radio-group selected="small">
  <anypoint-radio-button name="small">Small</anypoint-radio-button>
  <anypoint-radio-button name="medium">Medium</anypoint-radio-button>
  <anypoint-radio-button name="large">Large</anypoint-radio-button>
</anypoint-radio-group>
```

Radio-button-groups can be made optional, and allow zero buttons to be selected:

```html
<anypoint-radio-group selected="small" allow-empty-selection>
  <anypoint-radio-button name="small">Small</anypoint-radio-button>
  <anypoint-radio-button name="medium">Medium</anypoint-radio-button>
  <anypoint-radio-button name="large">Large</anypoint-radio-button>
</anypoint-radio-group>
```

See `anypoint-radio-buttonz for more information.

### Styling

Custom property | Description | Default
----------------|-------------|----------
`--anypoint-radio-group-item-padding` | The padding of the item | `12px`



### Events
| Name | Description | Params |
| --- | --- | --- |
| anypoint-radio-group-changed | Fired when the radio group selection changes. | __none__ |
