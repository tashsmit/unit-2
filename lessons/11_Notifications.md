## Notifications

### Objective

Students will become familiar with the Android notification system and practice implementing their own complex
notifications.

### Do Now (Morning)

Create a timer app. The app should take in some number of seconds before a "reminder" comes up. Use `handler.PostDelayed` and open a new activity (can just be an activity that displays "New Activity") when the countdown has finished.

### Lesson (Morning)

#### Notifications in Android

Notifications are tricky because they are displayed outside of your application. Then notification drawer and notifications are controlled by the Android system. 

#### Notification Builder

### Exercises (Morning)

### Do Now (Afternoon)

### Lesson (Afternoon)

#### Actions

##### PendingIntent

#### Lock Screen

#### Updating and Removing

#### Expanded Notifications

Notifications can be expanded to a larger view so that you can see more detailed info in the notification drawer. In order to expand notifications, you can use `NotificationCompat.Builder.setStyle()`, which takes in a layout that can be displayed in the expanded view.

#### User Experience

Notifcations have strict design guidelines since they appear outside the application. When creating notifications, be sure to look at the [notifications design guide](http://developer.android.com/design/patterns/notifications.html). Some other things to keep in mind is that users may turn off notifications or even uninstall an app; be mindful of how you use notifications in your app.

### Exercises (Afternoon)

Fork this [Meme Project](https://github.com/MadelynTav/MemeProject). If you already have a fork of this project, work off a new branch. Add a notification that does **TODO**

### Assessment

### Resources

[Android Asset Studio](https://romannurik.github.io/AndroidAssetStudio/) 
