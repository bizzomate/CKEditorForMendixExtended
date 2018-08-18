# CKEditorForMendixExtended
An extended version of Mendix CKEditor Widget  


# New Features:

## 1. Set IntervalAction with Notifications

* Repeatedly trigger/execute a microflow/action with a fixed time delay between each call. (e.g. save your editor's content every five minutes) 

* **Enable/Disable** Notification. after a successful execution of the microflow/action a notification will be triggered to notify the user that the action has been executed successfully (+ you can customize notification message)

### Here a guide on how you can style your notifications in order to match your theme requirements:

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


## Issues : 

If you encountered any issues in regard to the newly added features you can report it [here](https://github.com/bizzomate/CKEditorForMendixExtended/issues).





