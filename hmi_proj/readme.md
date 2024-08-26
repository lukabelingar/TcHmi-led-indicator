# Different approaches for a simple or multi-state indicators / buttons for TcHmi

Two demonstrations of a simple "indicator" element, using user control and a css-styled TcHmi button.

## Functionality

### TcHmiUserControl with a code to reflect multiple states

The [LED_indicator.usercontrol](hmi_proj/LED_indicator.usercontrol) has an additional property, which is used in a case structure to change background of its circle element.

### Custom button for 2-state indicator

Elements can be styled from the [Themes->%theme name%->%theme name.theme%](hmi_proj/Themes/Base/Base.theme) file. For the purpose of this demo, [an additional css](hmi_proj/Themes/Base/LED.css) is used to style a button.
Depicted are all 4 states: enabled, disabled, normal and active.
Add LED style to ClassNames attribute of the selected button element.

## Tested
Tested on 1.12.760.59