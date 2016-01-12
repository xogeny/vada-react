# Vada + React

This repository contains a small NPM module that provides additional
functionality when using [`vada`](http://github.com/xogeny/vada) in
combination with React.

Specifically, this module includes the `bindClass` functionality.
This offers very similar functionality to `connect` in the
`react-redux` module.  However, it is written in TypeScript and it is
easier to express the type constraints associated with `bindClass`.

In addition, this module provides both a `Provider` and a `Route`
component.  These are similar to capabilities provided by
`react-router` except that they are tied to routing functionality
provided in `vada`.

## TODO

Change `RouteProps` to include a `RouteId` object from `vada.

Avoid the `routeStore` property for the provider and simply provide a
function that extracts the route information from the main store's
state.
