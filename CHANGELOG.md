CHANGELOG
===

Version: 4.0
Date: 2014-09-21
This is the first version of the MT Enhancement to this theme. All of the changes below apply to this initial version.

Added Files
---
|Control Assets|Panel Assets|
|--------|--------|
|close.svg|applet-box-active-hover.svg|
|close-hover.svg|applet-box-active-hover-2.svg|
|on.svg|applet-box-attention.svg|
|plus.svg|
|plus-hover.svg|

Deprecated Files
----
|Background Assets|Control Assets|Misc Assets|Panel Assets|
|--------|--------|
|hightlight.png|close.png|corner-ripple.png|applet-box-active.png|
|popup-1.png|close-hover.png|popup-menu-item-hover.png|applet-box-active-hover.png|
|popup-2.png|on.png|sub-menu-item-active.png|applet-box-active-2.png|
|popup-3.png|plus.png||applet-box-active-hover-2.png|
|popup-4.png|plus-hover.png||applet-box-attention.png|

CSS Changes
---
**.toggle-switch-us:checked, .toggle-switch-intl:checked** || **.workspace-add-button** || **.workspace-add-button:hover** || **.workspace-close-button** || **.workspace-close-button:hover** || **.window-close** || **.window-close:hover** || **.window-list-item-demands-attention** || **.workspace-button:outlined:hover** || **.stopwatch-day-exceeded** || **.stopwatch-running-day-exceeded** || **.stopwatch-paused-day-exceeded** || **.numa-alert** || **.numa-limit-exceeded**
> converted asset to SVG

**.notification-button:active, .notification-icon-button:active, .hotplug-notification-item:active, .hotplug-resident-eject-button:active, .modal-dialog-button:active, .modal-dialog-button:pressed** || **.window-caption#selected** || **.modal-dialog-button:active, .modal-dialog-button:checked** || **.keyboard-key:active** || **.menu-favorites-button:hover** || **.menu-application-button-selected** || **.menu-application-button-selected:highlighted** || **.menu-category-button-selected** || **.sound-button:active** || **.expo-workspaces-name-entry#selected:focus** || **.soundbox-buttonMenu:active, .soundbox-buttonMenu:pressed** || **.soundbox-soundButton:active, .soundbox-soundButton:pressed** || **.calc-button:active** || **.settings-button:activate** || **.xCenter-menu .popup-menu-item:active**
> Changed color value to blend better with the highlight value for easier customization.

**.popup-submenu-menu-item:open** || **.popup-menu-item:active** || **.ripple-box** || **.ripple-box:rtl** || **.menu-application-button:highlighted** || **.window-list-item-box:active, .window-list-item-box:checked, .window-list-item-box:focus** || **.window-list-item-box:checked:hover, .window-list-item-box:focus:hover, .window-list-item-box:active:hover** || **.workspace-button:outlined** || **.expo-workspaces-name-entry** || **.expo-workspaces-name-entry#selected** || **.expo-workspaces-name-entry#selected:focus** || **.expo-workspaces-name-entry:focus** || **.stopwatch-running** || **.stopwatch-paused**
> Replaced the image asset call to just pure CSS