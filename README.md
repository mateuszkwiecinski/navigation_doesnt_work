# navigation_doesnt_work

## Context
given 2 deeplinks:
- `path/{argument}`
- `path/{arguemnt}/specific`

when navigating to `path/fixture-id/specific` 

then the Navigation library navigates to the first deeplink


## Fix
the proper way to define the first link as ``path/{argument}/`, with a slash at the end
