## AMA react snippets

some personal snippets for writing react components

### Commands

command        | description
---            | ---
`plain`        | scaffolds out a plain class component extending `React.Component`
`pure`         | same as `plain`, but extends `React.PureComponent`
`withStore`    | scaffolds out a class component with a connected export using redux's `connect`
`withDispatch` | same as `withStore`, but declares a `mapDispatchToProps` as well
`withIntl`     | scaffolds out a class extending `React.PureComponent`. Addition, it imports `intlShape` and `injectIntl` HoC and exports the component as such.
