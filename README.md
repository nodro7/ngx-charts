# ngx-charts

<a href="https://www.npmjs.com/package/@nodro7/ngx-charts">
  <img src="https://img.shields.io/npm/v/@nodro7/ngx-charts?logo=npm&logoColor=green&style=for-the-badge" alt="NPM Package" />
</a>

---

**Note:** This repository was originally forked from [`@swimlane/ngx-charts`](https://github.com/swimlane/ngx-charts), this fork was detached to fix an issue that has persisted in the original, despite attempts to submit PRs.

Original README below...

---

Declarative Charting Framework for Angular!

ngx-charts is unique because we don't merely wrap d3, nor any other chart engine for that matter. It is using Angular to render and animate the SVG elements with all of its binding and speed goodness, and uses d3 for the excellent math functions, scales, axis and shape generators. By having Angular do all of the rendering it opens us up to endless possibilities the Angular platform provides such as AoT, SSR, etc.

Data visualization is a science but that doesn't mean it has to be ugly. One of the big efforts we've made while creating this project is to make the charts aesthetically pleasing. The styles are also completely customizable through CSS, so you can override them as you please.

Also, constructing custom charts is possible by leveraging the various ngx-charts components that are exposed through the ngx-charts module.

For more info, check out the [documentation](https://swimlane.gitbook.io/ngx-charts) and the [demos](https://swimlane.github.io/ngx-charts/).

## Features

### Chart Types

- Horizontal & Vertical Bar Charts (Standard, Grouped, Stacked, Normalized)
- Line
- Area (Standard, Stacked, Normalized)
- Pie (Explodable, Grid, Custom legends)
- Bubble
- Donut
- Gauge (Linear & Radial)
- Heatmap
- Treemap
- Number Cards

### Customization

- Autoscaling
- Timeline Filtering
- Line Interpolation
- Configurable Axis Labels
- Legends (Labels & Gradient)
- Advanced Label Positioning
- Real-time data support
- Advanced Tooltips
- Data point Event Handlers
- Works with ngUpgrade

## Install

To use ngx-charts in your project install it via [npm](https://www.npmjs.com/package/@swimlane/ngx-charts):

```
npm i @swimlane/ngx-charts --save
```

## Custom Charts

To learn how to use the ngx-charts components to build custom charts and find examples, please refer to our [Custom Charts Page](https://github.com/swimlane/ngx-charts/blob/master/docs/custom-charts.md).

## Release

- Checkout master (`git checkout master`)
- Pull master (`git pull`)
- Refresh node modules (`npm ci`)
- Run tests (`npm test`)
- Examine log to determine next version (X.Y.Z)
- Run `git checkout -b release/X.Y.Z`
- Update version in `projects/swimlane/ngx-charts/package.json`.
- Update changelog in `projects/docs/changelog.md`
- Run `git commit -am "(release): X.Y.Z"`
- Run `git tag X.Y.Z`
- Run `git push origin HEAD --tags`
- Run `npm run publish:lib`
- Submit PR

## Credits

`ngx-charts` is a [Swimlane](http://swimlane.com) open-source project; we believe in giving back to the open-source community by sharing some of the projects we build for our application. Swimlane is an automated cyber security operations and incident response platform that enables cyber security teams to leverage threat intelligence, speed up incident response and automate security operations.

[SecOps Hub](http://secopshub.com) is an open, product-agnostic, online community for security professionals to share ideas, use cases, best practices, and incident response strategies.
