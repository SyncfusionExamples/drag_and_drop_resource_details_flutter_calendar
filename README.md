# How to get the dropped resource details in the Flutter Calendar (SfCalendar)?

This example demonstrates How to get the dropped resource details by using the onDragEnd callback of the calendar.

The [onDragEnd](https://help.syncfusion.com/flutter/calendar/drag-drop#ondragend) callback of the calendar can be used to get the dropped resource details in the Flutter Calendar.

## Enabling drag and drop

To perform drag-and-drop operations within the calendar, enable the [allowDragAndDrop](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/SfCalendar/allowDragAndDrop.html) property of SfCalendar.


## Getting the source details and target resource details

The [sourceResource](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/AppointmentDragEndDetails/sourceResource.html) and [targetResource](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/AppointmentDragEndDetails/targetResource.html) properties from the [AppointmentDragEndDetails](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/AppointmentDragEndDetails-class.html) can be used to get the changed target and source resource details through the onDragEnd callback.

You can also refer our UG documentation to know more about [DragandDrop](https://help.syncfusion.com/flutter/calendar/drag-drop) support in the Flutter calendar.

## Requirements to run the demo
* [VS Code](https://code.visualstudio.com/download)
* [Flutter SDK v1.22+](https://flutter.dev/docs/development/tools/sdk/overview)
* [For more development tools](https://flutter.dev/docs/development/tools/devtools/overview)

## How to run this application
To run this application, you need to first clone or download the ‘create a flutter maps widget in 10 minutes’ repository and open it in your preferred IDE. Then, build and run your project to view the output.

## Further help
For more help, check the [Syncfusion Flutter documentation](https://help.syncfusion.com/flutter/introduction/overview),
 [Flutter documentation](https://flutter.dev/docs/get-started/install).
