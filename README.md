# International Phone Field Package in French
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

![Pub](https://img.shields.io/pub/v/intl_phone_field)

A customised Flutter TextFormField to input international phone number along with country code.

This widget can be used to make customised text field to take phone number input for any country along with an option to choose country code from a dropdown.

## Screenshots

<img src="https://github.com/vanshg395/intl_phone_field/blob/master/1.png?raw=true" height="500px"> <img src="https://github.com/vanshg395/intl_phone_field/blob/master/2.png?raw=true" height="500px"> <img src="https://github.com/vanshg395/intl_phone_field/blob/master/3.png?raw=true" height="500px">

## Installing

To use this package:

Run this command:

```yaml
flutter pub add intl_phone_field_localized
```

Or, add the following to your `pubspec.yaml` file:

```yaml
dependencies:
  intl_phone_field_localized: ^3.1.0
```

## How to Use

Simply create a `IntlPhoneField` widget, and pass the required params:

```dart
IntlPhoneField(
    decoration: InputDecoration(
        labelText: 'Phone Number',
        border: OutlineInputBorder(
            borderSide: BorderSide(),
        ),
    ),
    initialCountryCode: 'IN',
    onChanged: (phone) {
        print(phone.completeNumber);
    },
)
```

Use `initialCountryCode` to set an initial Country Code.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

Comment on Issue or Pull Request, asking @all-contributors to add a contributor:

```shell
@all-contributors please add @<username> for <contributions>
```

**\<contributions>**: See the [Emoji Key (Contribution Types Reference)](https://allcontributors.org/docs/en/emoji-key) for a list of valid contribution types.

## Maintainers
- [Iwaju Tech](https://github.com/iwaju/)

## Contributors
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## LICENSE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
