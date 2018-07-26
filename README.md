# CKEditorForMendixExtended
An extended version of Mendix CKEditor Widget  


**New Features:**

**1. Set IntervalAction with Notificdations (trigger an action after a predefined time interval):**

* In order to customize notification look and feel (color, font, background ...etc) use add these css classes:

```css
.cke_extended .cke_notification{
    /* your css rules go here*/
} 
.cke_extended .cke_notification{
    /* example */
    color : #000000;
    background : #00ff00;
} 

```

* In order to customize notification position add these css classes to override the default position options (default, top-right, top-left, bottom-right, bottom-left) :
     
     
```css
.cke_extended.cke_interval_action_notification_pos_top_right .cke_notifications_area[style]{ 
   /* your css rules go here*/ 
}

.cke_extended.cke_interval_action_notification_pos_top_left .cke_notifications_area[style]{
   /* your css rules go here*/ 
}

.cke_extended.cke_interval_action_notification_pos_bottom_right .cke_notifications_area[style]{ 
   /* your css rules go here*/
}

.cke_extended.cke_interval_action_notification_pos_left_bottom .cke_notifications_area[style]{ 
   /* your css rules go here*/ 
}

.cke_extended.cke_interval_action_notification_pos_bottom_right .cke_notifications_area[style]{
    /* example */
    position: fixed !important;
    top: unset !important; 
    left: unset !important;
    bottom: 75px !important;
    right : 75px !important;
 }
```
