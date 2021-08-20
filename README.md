<div align="center">
  <br>
  <br>
  <img width="474" height="102" src="https://github.com/bpmn-io/awesome-bpmn-io/raw/master/media/logo.svg?sanitize=true" alt="Awesome">
  <br>
  <br><br>
  A curated list of <a href="https://bpmn.io">bpmn.io</a> related projects and resources. Created in the spirit of <a href="https://github.com/sindresorhus/awesome">awesome</a>.
  <br><br>
  <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.staticaly.com/gh/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge" /></a>

  <br><br>
</div>

## Contents

* [Learning Resources](#learning-resources)
* [Libraries](#libraries)
* [Extensions](#extensions)
* [Integrations](#integrations)
* [Apps](#apps)
* [Talks](#talks)


## Learning Resources

* [bpmn-js-examples](https://github.com/bpmn-io/bpmn-js-examples) - Large list of bpmn-js usage examples
* [dmn-js-examples](https://github.com/bpmn-io/dmn-js-examples) - Set of dmn-js usage examples
* [bpmn-js walkthrough](https://bpmn.io/toolkit/bpmn-js/walkthrough/) - An overview over bpmn-js, usage scenarios and its underlying architecture
* [bpmn.io demo](https://demo.bpmn.io/) - A getting started playground into the bpmn-io toolkit
* [bpmn.io community forum](https://forum.bpmn.io/) - A friendly place to ask about all things related to our project


## Libraries

#### Core

* [bpmn-js](https://github.com/bpmn-io/bpmn-js) - BPMN 2.0 process and collaboration diagram renderer/editor
* [cmmn-js](https://github.com/bpmn-io/cmmn-js) - CMMN 1.2 case diagram renderer/editor
* [dmn-js](https://github.com/bpmn-io/dmn-js) - DMN DRD, decision table and literal expression renderer/editor

#### Community Maintained

* [chor-js](https://github.com/jan-ladleif/chor-js) - BPMN 2.0 choreography diagram renderer/editor

#### Infrastructure / Foundation

* [bpmn-moddle](https://github.com/bpmn-io/bpmn-moddle) - Read, modify and write BPMN 2.0 diagrams from JavaScript
* [dmn-moddle](https://github.com/bpmn-io/dmn-moddle) - Read, modify and write DMN 1.3 diagrams from JavaScript
* [diagram-js](https://github.com/bpmn-io/diagram-js) - A toolbox for displaying and modifying diagrams on the web


## Extensions

#### [diagram-js](https://github.com/bpmn-io/diagram-js)

* [diagram-js-origin](https://github.com/bpmn-io/diagram-js-origin) - Render a canvas origin cross
* [diagram-js-minimap](https://github.com/bpmn-io/diagram-js-minimap) - Render a minimap of your diagram
* [diagram-js-direct-editing](https://github.com/bpmn-io/diagram-js-direct-editing) - A direct editing box for diagram-js

#### [bpmn-js](https://github.com/bpmn-io/bpmn-js)

* [bpmn-js-signavio-compat](https://github.com/bpmn-io/bpmn-js-signavio-compat) - Expand and collapse sub-processes exported by Signavio
* [bpmn-js-token-simulation](https://github.com/bpmn-io/bpmn-js-token-simulation) - Simulate tokens running through your process
* [bpmn-js-in-color](https://github.com/bpmn-io/bpmn-js-in-color) - A extension that makes bpmn-js implement the [BPMN in color proposal](https://github.com/bpmn-miwg/bpmn-in-color)
* [bpmn-js-sketchy](https://github.com/bpmn-io/bpmn-js-sketchy) - A sketchy renderer for BPMN diagrams
* [bpmn-js-nyan](https://github.com/bpmn-io/bpmn-js-nyan) - An extension that adds custom resize rules, theming and colors
* [bpmn-js-embedded-comments](https://github.com/bpmn-io/bpmn-js-embedded-comments) - Add, edit, and persist comments on BPMN diagrams
* [bpmn-js-cli](https://github.com/bpmn-io/bpmn-js-cli) - Model diagrams without the mouse
* [bpmn-js-copy-paste-example](https://github.com/nikku/bpmn-js-copy-paste-example) - An example illustrating how to copy and paste BPMN diagram elements across browser tabs
* [camunda-transaction-boundaries](https://github.com/bpmn-io/camunda-transaction-boundaries) - Visualize transaction boundaries, applied by the [Camunda workflow engine](https://camunda.com/)
* [bpmn-js-honkify](https://github.com/pinussilvestrus/bpmn-js-honkify) - Integrates honkify inspired duck sounds into bpmn-js
* [bpmn-js-task-resize](https://github.com/ElCondor1969/bpmn-js-task-resize) - An extension to allow tasks being resizable 
* [bpmn-js-disable-collapsed-subprocess](https://github.com/bpmn-io/bpmn-js-disable-collapsed-subprocess) - An extension which disables modeling collapsed subprocess via replace menu
* [bpmn-js-collapse-subprocess](https://github.com/bpmn-io/bpmn-js-collapse-subprocess) - An extension that re-enables to collapse sub process via replace menu
* [bpmn-js-color-picker](https://github.com/bpmn-io/bpmn-js-color-picker) - Color your BPMN elements via the context pad

#### Misc

* [@bpmn-io/add-exporter](https://github.com/bpmn-io/add-exporter) - A helper to inject `exporter` meta-data into saved BPMN, CMMN and DMN diagrams
* [@bpmn-io/align-to-origin](https://github.com/bpmn-io/align-to-origin) - Aligns your diagrams to the coordinate origin, manually triggered or on diagram save
* [bpmn-js-differ](https://github.com/bpmn-io/bpmn-js-differ) - A semantic diff tool for BPMN diagrams
* [bpmn-to-image](https://github.com/bpmn-io/bpmn-to-image) - Transform BPMN diagrams to images from the command line
* [bpmn-js-i18n](https://github.com/bpmn-io/bpmn-js-i18n) - Internationalization resources for bpmn-js
* [bpmn-font](https://github.com/bpmn-io/bpmn-font) - A BPMN 2.0 icon font
* [bpmnlint](https://github.com/bpmn-io/bpmnlint) - An extensible and configurable BPMN 2.0 diagram validator
* [eslint-plugin-bpmn-io](https://github.com/bpmn-io/eslint-plugin-bpmn-io) - Common lint rules for bpmn.io projects
* [dmnlint](https://github.com/bpmn-io/dmnlint) - Validate DMN diagrams based on configurable lint rules
* [dmn-migrate](https://github.com/bpmn-io/dmn-migrate) - Migrate your DMN diagrams to the latest DMN version


## Integrations

* [react-bpmn](https://github.com/bpmn-io/react-bpmn) - Render BPMN 2.0 diagrams in a [React](https://reactjs.org/) application
* [vue-bpmn](https://github.com/bpmn-io/vue-bpmn) - Render BPMN 2.0 diagrams in a [Vue.js](https://vuejs.org) application
* [bpmn-js-example-angular](https://github.com/bpmn-io/bpmn-js-example-angular) - An integration of bpmn-js with [Angular](https://angular.io/)
* [svelte-bpmn](https://github.com/bpmn-io/svelte-bpmn) - Render BPMN 2.0 diagrams in a [Svelte](https://svelte.dev) application


## Apps

* [Cawemo](https://cawemo.com/) - A web-based, collaborative modeling solution that uses bpmn-js for process modeling
* [Camunda Modeler](https://github.com/camunda/camunda-modeler) - An integrated modeling solution for BPMN, DMN and CMMN based on bpmn.io
* [Zeebe Modeler](https://github.com/zeebe-io/zeebe-modeler) - The visual workflow editor for Zeebe based on bpmn.io
* [bpmn-io-vs-code](https://github.com/bpmn-io/vs-code-bpmn-io) - Display and edit BPMN diagrams in VS Code using bpmn.io tools
* [postit-js](https://github.com/pinussilvestrus/postit-js) - Create Post-it boards on a canvas editor
* [Duckflow](https://duckflow.app) - Lightweight BPMN process designer application, based on bpmn.io
* [bpmn-diff-bitbucket-plugin](https://github.com/domclick/bpmn-diff-bitbucket-plugin) - Bitbucket Server plugin for BPMN file versions visual comparison during pull-requests
* [Cammand](https://github.com/StephenOTT/Cammand) - alternative UI for Camunda Platform. Check out for bpmn-js embedded in Blazor (C#).

## Talks

* [Roll your own BPMN editor](https://github.com/nikku/roll-your-own-bpmn-editor) - An introduction to bpmn-js and its friends
* [Making of token simulation](https://github.com/nikku/2021-token-simulation) - A dive into bpmn-js extensibility and the inner workings of [bpmn-js-token-simulation](https://github.com/bpmn-io/bpmn-js-token-simulation)

## Contribute

Would you like to contribute to this list? [Propose your addition](https://github.com/bpmn-io/awesome-bpmn-io/edit/master/README.md).


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
