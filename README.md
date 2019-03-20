# IFTTT Dash Button
A (slightly) modified version of [Gangster45671](https://github.com/Gangster45671)'s [IFTT Dash Button](https://github.com/Gangster45671/IFTTT-Dash-Button).
## Modifications
- When constructing the querystring to submit data to remote server, be tolerant of the fact that the configured URL may already have a querystring (i.e. append an "&" if the URL already contains a "?").
 - See pull request: [IFTTT-Dash-Button/pull/1](https://github.com/Gangster45671/IFTTT-Dash-Button/pull/1)

## Future enhacements
- Add another configurable URL to dipatch a "Low battery warning" message when the battery voltage drops below a pre-determined threshold.
