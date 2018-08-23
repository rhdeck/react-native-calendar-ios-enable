# react-native-calendar-ios-enable

Adds security message to allow use of the calendar without requiring XCode intervention

# Usage

```bash
yarn add react-native-calendar-ios-enable
```

**Note** You can determine the text for the calendar permission message via the `IOSCalendarPrivacyText` property of your `package.json` file. To set text, just set the value like so before adding the package. :

```
{
    ...
    dependencies: {
        ...
    },
    IOSCalendarPrivacyText: "Please let me use the camera!"
}
```
