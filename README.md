[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jifalops/screen-env)

# screen-env
Differentiate screen types by size, touch ability, and more.

## Installation
```
bower install --save screen-env
```

## Usage
* Bind to the `screen-env` properties you are interested in.

## Demo
<!--
```
<custom-element-demo>
  <template is="dom-bind">
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="screen-env.html">
    <next-code-block></next-code-block>    
    <table>
      <tr><td>isTouch</td><td>[[isTouch]]</td></tr>
      <tr><td>isMobile</td><td>[[isMobile]]</td></tr>
      <tr><td>isTablet</td><td>[[isTablet]]</td></tr>
      <tr><td>isDesktop</td><td>[[isDesktop]]</td></tr>
      <tr><td>isFullscreen</td><td>[[isFullscreen]]</td></tr>
      <tr><td>windowHeight</td><td>[[windowHeight]]</td></tr>
      <tr><td>windowWidth</td><td>[[windowWidth]]</td></tr>
      <tr><td>windowAspect</td><td>[[windowAspect]]</td></tr>
      <tr><td>screenHeight</td><td>[[screenHeight]]</td></tr>
      <tr><td>screenWidth</td><td>[[screenWidth]]</td></tr>
      <tr><td>screenAspect</td><td>[[screenAspect]]</td></tr>
      <tr><td>mediaHandheld</td><td>[[mediaHandheld]]</td></tr>
      <tr><td>mediaScreen</td><td>[[mediaScreen]]</td></tr>
      <tr><td>mediaPrint</td><td>[[mediaPrint]]</td></tr>
      <tr><td>mediaTv</td><td>[[mediaTv]]</td></tr>
      <tr><td>portrait</td><td>[[portrait]]</td></tr>
      <tr><td>landscape</td><td>[[landscape]]</td></tr>
      <tr><td>windowExtraSmall</td><td>[[windowExtraSmall]]</td></tr>
      <tr><td>windowSmall</td><td>[[windowSmall]]</td></tr>
      <tr><td>windowMedium</td><td>[[windowMedium]]</td></tr>
      <tr><td>windowLarge</td><td>[[windowLarge]]</td></tr>
      <tr><td>windowExtraLarge</td><td>[[windowExtraLarge]]</td></tr>
      <tr><td>mobileSmallPortrait</td><td>[[mobileSmallPortrait]]</td></tr>
      <tr><td>mobileMediumPortrait</td><td>[[mobileMediumPortrait]]</td></tr>
      <tr><td>mobileLargePortrait</td><td>[[mobileLargePortrait]]</td></tr>
      <tr><td>tabletSmallPortrait</td><td>[[tabletSmallPortrait]]</td></tr>
      <tr><td>tabletLargePortrait</td><td>[[tabletLargePortrait]]</td></tr>
      <tr><td>mobileSmallLandscape</td><td>[[mobileSmallLandscape]]</td></tr>
      <tr><td>mobileMediumLandscape</td><td>[[mobileMediumLandscape]]</td></tr>
      <tr><td>mobileLargeLandscape</td><td>[[mobileLargeLandscape]]</td></tr>
      <tr><td>tabletSmallLandscape</td><td>[[tabletSmallLandscape]]</td></tr>
      <tr><td>tabletLargeLandscape</td><td>[[tabletLargeLandscape]]</td></tr>
      <tr><td>uaIsMobile</td><td>[[uaIsMobile]]</td></tr>
      <tr><td>uaIsTablet</td><td>[[uaIsTablet]]</td></tr>
      <tr><td>uaIsDesktop</td><td>[[uaIsDesktop]]</td></tr>
    </table>
  </template>
</custom-element-demo>
```
-->

```html
(See the full demo below)
<screen-env
  is-touch="{{isTouch}}"
  is-mobile="{{isMobile}}"
  is-tablet="{{isTablet}}"
  is-desktop="{{isDesktop}}"
  is-fullscreen="{{isFullscreen}}"
  window-height="{{windowHeight}}"
  window-width="{{windowWidth}}"
  window-aspect="{{windowAspect}}"
  media-handheld="{{mediaHandheld}}"
  screen-height="{{screenHeight}}"
  screen-width="{{screenWidth}}"
  screen-aspect="{{screenAspect}}"
  media-handheld="{{mediaHandheld}}"
  media-screen="{{mediaScreen}}"
  media-print="{{mediaPrint}}"
  media-tv="{{mediaTv}}"
  portrait="{{portrait}}"
  landscape="{{landscape}}"
  window-extra-small="{{windowExtraSmall}}"
  window-small="{{windowSmall}}"
  window-medium="{{windowMedium}}"
  window-large="{{windowLarge}}"
  window-extra-large="{{windowExtraLarge}}"
  mobile-small-portrait="{{mobileSmallPortrait}}"
  mobile-medium-portrait="{{mobileMediumPortrait}}"
  mobile-large-portrait="{{mobileLargePortrait}}"
  tablet-small-portrait="{{tabletSmallPortrait}}"
  tablet-large-portrait="{{tabletLargePortrait}}"
  mobile-small-landscape="{{mobileSmallLandscape}}"
  mobile-medium-landscape="{{mobileMediumLandscape}}"
  mobile-large-landscape="{{mobileLargeLandscape}}"
  tablet-small-landscape="{{tabletSmallLandscape}}"
  tablet-large-landscape="{{tabletLargeLandscape}}"
  ua-is-mobile="{{uaIsMobile}}"
  ua-is-tablet="{{uaIsTablet}}"
  ua-is-desktop="{{uaIsDesktop}}">
</screen-env>
```

Full demo:
[webcomponents.org](https://www.webcomponents.org/element/jifalops/screen-env/demo/demo/index.html)
| [github](https://jifalops.github.io/screen-env/components/screen-env/demo/).

API: [webcomponents.org](https://www.webcomponents.org/element/jifalops/screen-env/screen-env)
| [github](https://jifalops.github.io/screen-env).

## Contributing

1. Fork it on Github.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT](https://opensource.org/licenses/MIT)
