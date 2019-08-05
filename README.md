# FlutterShoppingApplication
Shopping application using Material Component widgets and scoped model for cart state mgmt.

## Goals

* Show how to customize Flutter's Material Component widgets to produce
  a unique design for an app.
* Show how to use `scoped_model` to manage an app's state and access it
  across different routes and in different widgets.

This is a modified version of the app featured in Flutter's
[Material codelabs](https://codelabs.developers.google.com/?cat=Flutter).

## Important points

### `/model/app_state_model.dart`

The model object representing the state of the app. It holds the
available products as well as what's in the shopping cart.

### `/supplemental`

A bunch of widgets that customize Material to produce the look and feel
of the app.

### `shopping_cart.dart`

The shopping cart widgets. They access the app state model via
`ScopedModelDescendant`, display the contents of the shopping cart, and
allow the user to edit them.