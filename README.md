# How to style the month cell in the Flutter Calendar?

A quick-start example to help you to style the month cell in the Flutter Calendar.

You can add active dates to the Flutter Event Calendar by using the reverse concept of the [blackoutDates](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/SfCalendar/blackoutDates.html).

In this example, active dates are stored in a collection, and the [onViewChanged](https://pub.dev/documentation/syncfusion_flutter_calendar/latest/calendar/SfCalendar/onViewChanged.html) callback is used to verify that the mentioned active dates match the visible dates. If they are equal, they are added to the active dates and can be selected. Otherwise, the remaining dates are considered the collection of blackout dates.

For more details, refer to this [KB](https://www.syncfusion.com/kb/12090/how-to-style-the-month-cell-in-the-flutter-calendar).

## Requirements to run the demo
* [VS Code](https://code.visualstudio.com/download)
* [Flutter SDK v1.22+](https://flutter.dev/docs/development/tools/sdk/overview)
* [For more development tools](https://flutter.dev/docs/development/tools/devtools/overview)

## How to run this application
To run this application, you need to first clone or download the ‘create a flutter maps widget in 10 minutes’ repository and open it in your preferred IDE. Then, build and run your project to view the output.

## Further help
For more help, check the [Syncfusion Flutter documentation](https://help.syncfusion.com/flutter/introduction/overview),
 [Flutter documentation](https://flutter.dev/docs/get-started/install).