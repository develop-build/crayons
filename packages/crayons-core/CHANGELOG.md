# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [3.0.0-beta.2](https://github.com/freshworks/crayons/compare/@freshworks/crayons@3.0.0-beta.1...@freshworks/crayons@3.0.0-beta.2) (2021-11-03)

### Bug Fixes

- **fw-modal:** modal -  focus lock issue fix ([34edf7f](https://github.com/freshworks/crayons/commit/34edf7fd98999c642c7972085fe187084546d46c))

### Features

- **fw-list-options:** added fw-list-options ([e01f70f](https://github.com/freshworks/crayons/commit/e01f70f15405d3dfdfc97e02386ae2806906313b))
- **fw-popover:** added popover to select and datepicker ([21bed13](https://github.com/freshworks/crayons/commit/21bed1371fe1cc4b7668cf01425f8993d4ceba52))
- **fw-list-options:** added props to parent so that same props need not be repeated in child ([9e5b712](https://github.com/freshworks/crayons/commit/9e5b7120245745b9a95147ba4a3ebbb5b10c73f3))
- **fw-popover:** added fw-popover component ([dfbf462](https://github.com/freshworks/crayons/commit/dfbf4623ae2c749a4cf83a6c31e5fc6abbc1b285))
- **fw-tabs:** changing structure of fw-tabs children components to enable yeilding headers ([#247](https://github.com/freshworks/crayons/issues/247)) ([c8055a4](https://github.com/freshworks/crayons/commit/c8055a4a41806fec917b3c3e3ccc93eb94aaef85))
- **fw-modal:** improving modal composibility by introducing modal-title, modal-content, modal-footer ([#248](https://github.com/freshworks/crayons/issues/248)) ([4390b02](https://github.com/freshworks/crayons/commit/4390b021fc521d2c2c23648c791268dfe6cd71be))
- **fw-modal:** modal - adding open method to the modal ([c550f21](https://github.com/freshworks/crayons/commit/c550f219ec4581421afad2faf59128b2ecd1e299))
- **custom-react-wrapper:** use Custom React Wrapper instead of Stencil's react wrapper ([3ae8667](https://github.com/freshworks/crayons/commit/3ae866717d763337acd42f1e13a2155275746022))
- **fw-list-options:** base for fw-list-options ([9126aaa](https://github.com/freshworks/crayons/commit/9126aaaefb4271f3dbe7fba1a16092ae2150aee7))
- **fw-select-option:** added variants of select-option ([6b04d16](https://github.com/freshworks/crayons/commit/6b04d1683191a6ad28f1f160d9e2fac6650765a1))
- **fw-select-option:** renamed props ([09a1811](https://github.com/freshworks/crayons/commit/09a1811496edb31ae80091aaca558b21f0b6f7df))

### BREAKING CHANGES

- **fw-tab:** fw-tab-header attribute is now removed, instead use fw-tab children for using html content for tab header and use fw-tab-panel for panel content
- **fw-modal:** Changing visibility property to is-open property.


# [3.0.0-beta.1](https://github.com/freshworks/crayons/compare/@freshworks/crayons@3.0.0-beta.0...@freshworks/crayons@3.0.0-beta.1) (2021-10-22)

### Refactor

* **root:** move .github to the root folder and remove from each packages ([#244](https://github.com/freshworks/crayons/issues/244)) ([56eeeb8](https://github.com/freshworks/crayons/commit/56eeeb84179e39001d9f6f2837e98cc063188e66))


# [3.0.0-beta.0](https://github.com/freshworks/crayons/compare/v2.13.2...@freshworks/crayons@3.0.0-beta.0) (2021-10-20)

### Features

*  **react wrapper:** added React wrapper to Crayons ([0c9a42d](https://github.com/freshworks/crayons/commit/0c9a42db21b7e3f80df3adb3e55fd4899c12acb8))
*  **monorepo:** ([abc48c8](https://github.com/freshworks/crayons/commit/abc48c88f025d13dd321b75bb00782a62361aaf9))
*  styling architecture changes: ([291832d](https://github.com/freshworks/crayons/commit/291832d6c29b2ae8258f584d6745eb0fe3f85dcf))
*  tooling setup and stylelint changes: ([098dee5](https://github.com/freshworks/crayons/commit/098dee50fb47ea25b9dc3cedfd65cdf2a495a684))
*  crayons-commons package to reuse common functionality: ([ce5d5e9](https://github.com/freshworks/crayons/commit/ce5d5e99e21e7237b8fe117d43db30f36b340603))
*  **crayons-datatable** init setup: ([e4c7fb2](https://github.com/freshworks/crayons/commit/e4c7fb254d3ca8daac2de64094b46362d8679df8))
*  styles and storybook init setup: ([7a54a45](https://github.com/freshworks/crayons/commit/7a54a4548b979039cb421027b93721be4e41131d))
*  setup global storybook and remove package level storybook config: ([38c5f33](https://github.com/freshworks/crayons/commit/38c5f336d2426107ba3a274ec577899254275fb9))
*  a11y runtime check in dev: ([a19e7e0](https://github.com/freshworks/crayons/commit/a19e7e067c91348a1f127598b823a5227a748485))
*  storybook global setup and package level dev run: ([b43bc9d](https://github.com/freshworks/crayons/commit/b43bc9dccb4a138c32357c6c5504334126958bac))
*  storybook global and package level dev setup: ([25cf303](https://github.com/freshworks/crayons/commit/25cf3032fa3607fae1f1de746bb5a397d3a0a3d7))
*  css global styles setup: ([bed2b16](https://github.com/freshworks/crayons/commit/bed2b168d7648b44706ae962fbbdea957ba257a8))
*  **fw-checkbox** add keyboard nav support and a11y support (#215) ([6e596c8](https://github.com/freshworks/crayons/commit/6e596c88a477b6476a91104cbbfef95157a0f803))
*  **fw-radio** add keyboard nav support and a11y support (#216) ([ec1d913](https://github.com/freshworks/crayons/commit/ec1d913436c98e6e1d6d9efec7f32a6b45305018))
*  **fw-toggle** adding support for showicon and keyboard navigation (#220) ([535381c](https://github.com/freshworks/crayons/commit/535381c4962654a1a02d65dcbfff5455292c9039))
*  a11y changes and ally related test cases update ([6245ade](https://github.com/freshworks/crayons/commit/6245ade16e5dbf999ade26178dfdb26245aafdb9))

### Bug Fixes
* stylelint and eslint fixes: ([44a8aca](https://github.com/freshworks/crayons/commit/44a8aca57e669f8263d491bcb5034a8f1b0649c2))
* jsx-a11y/click-events-have-key-events and ally issues: ([55b3339](https://github.com/freshworks/crayons/commit/55b333984034ada20d78b50bc0a7f80369cb3425))
* no-noninteractive-element-interactions fix for dropdown-button: ([de8e0ce](https://github.com/freshworks/crayons/commit/de8e0ce240b101c734e4b576984c1e8ffb1a1126))
* react wrapper import fix for extended components: ([3d6c49a](https://github.com/freshworks/crayons/commit/3d6c49a3bd525577583ce302d5dc0dd84c732234))
*  **fw-button** fix a11y issues and standardise attributes (#218) ([96c2a69](https://github.com/freshworks/crayons/commit/96c2a6971315718f7402309ac719ff3d00fa74e3))
*  **vuepress:** fix Vuepress live preview plugin configuration based on latest version ([1e8d8ca](https://github.com/freshworks/crayons/commit/1e8d8ca33ddaff308a6c4ae4b1bebe2b8ee077dd))
*  accessibility issue fixes ([56ee9f7](https://github.com/freshworks/crayons/commit/56ee9f7baec0800a83973f60b43c6ee9683364fa))

## 2.13.2 (2021-07-16)

### Bug Fixes

- **main.yml:** changes to upgrade remove validations ([de111ca](https://github.com/freshworks/crayons/commit/de111ca3f2ebed57a905d84436d878ed301a58fb))

## 2.13.1 (2021-04-14)

### Bug Fixes

- **fw-input:** adds a new event for clearing input ([271a20f](https://github.com/freshworks/crayons/commit/271a20ffe8b17901815d6db512c0f81c1bdd7882)), closes [#185](https://github.com/freshworks/crayons/issues/185)

## 2.13.0 (2021-03-18)

### Features

- **fw-label:** introduce css variables for label padding ([c7ef767](https://github.com/freshworks/crayons/commit/c7ef76723c748f455a8132822ca711ad2f24deb9)), closes [#181](https://github.com/freshworks/crayons/issues/181)

## 2.12.2 (2021-03-16)

### Bug Fixes

- **radio.tsx, checkbox.tsx:** fixes checked value change to reflect in UI when disabled ([0cc6f70](https://github.com/freshworks/crayons/commit/0cc6f7087e31b2378deb3757f5b7ae513641a06a)), closes [#154](https://github.com/freshworks/crayons/issues/154)

## 2.12.1 (2021-03-09)

### Bug Fixes

- **select.tsx:** fixes emitting fwChange before initialization for multiselect ([3d11ba5](https://github.com/freshworks/crayons/commit/3d11ba5d323343d7876bab185759c144abee2d28))

## 2.12.0 (2021-02-03)

### Features

- **input, button, radio-group, textarea, datepicker, timepicker, checkbox:** added form support ([58a7d25](https://github.com/freshworks/crayons/commit/58a7d257d6c28a146cc444f81bc64ccd6cc4934d)), closes [#104](https://github.com/freshworks/crayons/issues/104) [#170](https://github.com/freshworks/crayons/issues/170)

## 2.11.1 (2021-01-06)

### Bug Fixes

- **dropdown-button:** make only list scrollable ([09ee194](https://github.com/freshworks/crayons/commit/09ee19491aadc6fc0d4953e1333bf580ee11eeb2)), closes [#168](https://github.com/freshworks/crayons/issues/168)

## 2.11.0 (2020-12-21)

### Features

- **select.tsx:** added `max` for multselect ([e297873](https://github.com/freshworks/crayons/commit/e297873ba6ba8be53de069556b11132c6f35bc97)), closes [#156](https://github.com/freshworks/crayons/issues/156)

## 2.10.2 (2020-12-21)

### Bug Fixes

- **input.scss:** hides arrows in input type number ([cb91f0d](https://github.com/freshworks/crayons/commit/cb91f0d0ba0bee542f5aadd976f6e5fd23739fb2)), closes [#150](https://github.com/freshworks/crayons/issues/150)
- **toast:** fix toast icon not loading ([f4b69d8](https://github.com/freshworks/crayons/commit/f4b69d82c60e2e97e2c8795b4adbd04522253244)), closes [#164](https://github.com/freshworks/crayons/issues/164)
- **toast:** review comments ([f434514](https://github.com/freshworks/crayons/commit/f4345141d75413b1ab7dfa5d368a5253a76592b8)), closes [#164](https://github.com/freshworks/crayons/issues/164)

## 2.10.1 (2020-12-11)

### Bug Fixes

- **select.tsx:** fixed placeholder problem in select ([123a15a](https://github.com/freshworks/crayons/commit/123a15abbb84d704cc23a161fa64c8da247c49af)), closes [#157](https://github.com/freshworks/crayons/issues/157)

## 2.10.0 (2020-12-07)

### Features

- **textarea:** change textarea var desc ([4ef8b78](https://github.com/freshworks/crayons/commit/4ef8b78aa1c345231e7fff6111c2ac898a45f0e8)), closes [#152](https://github.com/freshworks/crayons/issues/152)
- **textarea:** introduced text color for textarea as scss var ([7e4af5b](https://github.com/freshworks/crayons/commit/7e4af5b7ce2bebdc2ffe325b75bbc7492188c12c)), closes [#152](https://github.com/freshworks/crayons/issues/152)

## 2.9.1 (2020-12-02)

### Bug Fixes

- **search.svg:** fixes color issue in svg file ([fbd1d18](https://github.com/freshworks/crayons/commit/fbd1d188fe3deecc11cea38b1ca7106318581943)), closes [#147](https://github.com/freshworks/crayons/issues/147)

## 2.9.0 (2020-11-04)

### Features

- **dropdown-button:** add disabled prop ([0aeca90](https://github.com/freshworks/crayons/commit/0aeca90fa74d8b39575f832de8c2325d72d77521)), closes [#145](https://github.com/freshworks/crayons/issues/145)

## 2.8.1 (2020-10-28)

### Bug Fixes

- **icon:** add gulp task to test ([d84eaa3](https://github.com/freshworks/crayons/commit/d84eaa3ad6c15ef0a26596ae27fd6902b0249b92)), closes [#143](https://github.com/freshworks/crayons/issues/143)
- **icon:** fixes icon url path error ([c20bdd8](https://github.com/freshworks/crayons/commit/c20bdd8f5dc3a98f29cbd244a86853eb10cb5017)), closes [#143](https://github.com/freshworks/crayons/issues/143)
- **icon:** minor gulp file fix ([db2d920](https://github.com/freshworks/crayons/commit/db2d920fc9ca62c52c1dd46ef939c3a7e42d190b)), closes [#143](https://github.com/freshworks/crayons/issues/143)

## 2.8.0 (2020-10-14)

### Features

- **components/select/select.tsx:** add a method to set selected values in fw-select component ([1ea13de](https://github.com/freshworks/crayons/commit/1ea13dea040316db62fdddd597ea5a6bb7bdcd1a)), closes [#132](https://github.com/freshworks/crayons/issues/132)

## 2.7.1 (2020-10-05)

### Bug Fixes

- fix datapicker false events trigger ([318f554](https://github.com/freshworks/crayons/commit/318f55479941df2837adc06c393420ad39e1ad36))

## 2.7.0 (2020-09-30)

### Features

- **button:** fix type change ([429e7dc](https://github.com/freshworks/crayons/commit/429e7dca05153a25491cc15214ea92a1feba9ea5)), closes [#112](https://github.com/freshworks/crayons/issues/112)
- **dropdown button:** add missing css prop ([36c157f](https://github.com/freshworks/crayons/commit/36c157f9b7cfff9ae6186b1dc81ed8ffec919cec)), closes [#112](https://github.com/freshworks/crayons/issues/112)
- **dropdown button:** dropdown button adhering to Freshworks Design System ([43e8bda](https://github.com/freshworks/crayons/commit/43e8bda94a06ecc95baae72225bff8515fa7480d)), closes [#112](https://github.com/freshworks/crayons/issues/112)
- **dropdown button:** dropdown button small fix ([003a937](https://github.com/freshworks/crayons/commit/003a9372f9ae0250c0a3d7ab9cd4a2d699e7c5c0)), closes [#122](https://github.com/freshworks/crayons/issues/122)
- **dropdown button:** review comments ([43923cd](https://github.com/freshworks/crayons/commit/43923cd35cd90337aca023e9f2aa3945ba6d949d)), closes [#112](https://github.com/freshworks/crayons/issues/112)
- **dropdown button:** review comments - 2 ([b8bfe71](https://github.com/freshworks/crayons/commit/b8bfe7187861973e817d6128d9df5f094a4deaf0)), closes [#112](https://github.com/freshworks/crayons/issues/112)

## 2.6.3 (2020-09-30)

### Bug Fixes

- **fw-button:** fixes CSS issues with external CSS ([ba327de](https://github.com/freshworks/crayons/commit/ba327defb0ddc2ea6358c0af69fd9e109e5c07f0)), closes [#134](https://github.com/freshworks/crayons/issues/134)

## 2.6.2 (2020-09-30)

### Bug Fixes

- **select:** fixed tag not getting disabled ([3723830](https://github.com/freshworks/crayons/commit/37238304453ab073e0700395d8eeb8a5b2710321)), closes [#137](https://github.com/freshworks/crayons/issues/137)

## 2.6.1 (2020-09-28)

### Bug Fixes

- **toast.scss, toast.scss, readme.md:** added z-index for toast messages, increased default timeout ([99d6b9d](https://github.com/freshworks/crayons/commit/99d6b9d91655487f4c1657351bdaba3d3dd8f6b2))

## 2.6.0 (2020-09-25)

### Features

- toast Component ([3db87dc](https://github.com/freshworks/crayons/commit/3db87dc486b644560ab60d372fddc540acab55c1)), closes [#111](https://github.com/freshworks/crayons/issues/111)

## 2.5.0 (2020-09-17)

### Features

- **input select textarea:** adds new prop - autofocus ([bd88d2b](https://github.com/freshworks/crayons/commit/bd88d2b8a0ade316dd6c652442e11c409f9f0cdc)), closes [#129](https://github.com/freshworks/crayons/issues/129)

## 2.4.0 (2020-08-28)

### Features

- **fw-modal:** added events and `hide-footer` attribute ([a4bd59c](https://github.com/freshworks/crayons/commit/a4bd59c7b3ac79fa7e89124c69590bf81ac75fa2))
- **fw-modal:** introduces modals to crayons ([1725f86](https://github.com/freshworks/crayons/commit/1725f864a9b246d99204b662e7c3620399728486)), closes [#113](https://github.com/freshworks/crayons/issues/113)

## 2.3.4 (2020-08-18)

### Bug Fixes

- **fw-tabs:** fixes Multi-Level Nesting in Tabs ([8e312f2](https://github.com/freshworks/crayons/commit/8e312f24bd252c89b287ca9bad3a9a2396c588ab)), closes [#109](https://github.com/freshworks/crayons/issues/109)

## 2.3.3 (2020-08-14)

### Bug Fixes

- **fw-tabs:** fwChange fires twice ([0135302](https://github.com/freshworks/crayons/commit/0135302f0964c9e64229f11fd4aa789cf232af0a)), closes [#106](https://github.com/freshworks/crayons/issues/106)

## 2.3.2 (2020-07-24)

### Bug Fixes

- **datepicker:** fixes closing the datepicker as designed ([19eec6d](https://github.com/freshworks/crayons/commit/19eec6d2c64bc1fc6ce0f761f46b33acfaeb5832)), closes [#98](https://github.com/freshworks/crayons/issues/98)

## 2.3.1 (2020-07-23)

### Bug Fixes

- close popup on click outside ([a88efc1](https://github.com/freshworks/crayons/commit/a88efc18a89952a240de4b8a78d17d5f0c798a2e)), closes [#98](https://github.com/freshworks/crayons/issues/98)

## 2.3.0 (2020-07-14)

### Bug Fixes

- review comments ([2556171](https://github.com/freshworks/crayons/commit/255617113413207f9d2a15540597dffa5cf97802))
- review comments - 2 ([7dbdf98](https://github.com/freshworks/crayons/commit/7dbdf984f55097e71a012daec56b41a722b109fb))

### Features

- style fix ([71a0794](https://github.com/freshworks/crayons/commit/71a07943a7559d787ee699b5e5e0400a699fed0d))
- **select:** added back readonly ([c78ae16](https://github.com/freshworks/crayons/commit/c78ae16acac8acb5871b935daa54d9444e3dbfc4))
- **select:** review comments  -4 ([7501ff8](https://github.com/freshworks/crayons/commit/7501ff8891762ee561fbfedbd3c83479f57dceda))
- **select:** review comments - 3 ([b72687e](https://github.com/freshworks/crayons/commit/b72687ede2f8b9591e8ecb2ac0f3476470737684))
- **textarea, timepicker, select:** improvements in textarea, select, timepicker ([ce02f62](https://github.com/freshworks/crayons/commit/ce02f62eaebc17a6fd5777fe408ce48bb9a5a1f9))

## 2.2.4 (2020-06-23)

### Bug Fixes

- **tabs:** adds active index as an attribute/prop ([6f5cefb](https://github.com/freshworks/crayons/commit/6f5cefb07183314fae1c3e16c14bb27eabaf4581))

## 2.2.3 (2020-06-22)

### Bug Fixes

- **checkbox, radio:** adds reflect property to keep sync of attributes and properties ([57bd15e](https://github.com/freshworks/crayons/commit/57bd15ec8b21beb20c64ef5320819954907fa5f3))

## 2.2.2 (2020-06-19)

### Bug Fixes

- **tabs:** add customizations for color ([96bfac0](https://github.com/freshworks/crayons/commit/96bfac098fe2780d7bca9467e41985f226b28c4e))

## 2.2.1 (2020-06-17)

### Bug Fixes

- **tab:** fixes rendering when props of fw-tab is changed ([4d6a7f3](https://github.com/freshworks/crayons/commit/4d6a7f3417f196101afd73fb3d7a775a3cf74ca7))

## 2.2.0 (2020-06-17)

### Bug Fixes

- **tabs:** re-render on attribute change in `fw-tab` ([cc53bd4](https://github.com/freshworks/crayons/commit/cc53bd4ba8c385541558aad97268e1c6db8a8746))

### Features

- **tabs:** added disable and tabHeaderHtml capability ([4ec6be8](https://github.com/freshworks/crayons/commit/4ec6be8ab60855466a09b756fabd0de181399c68))

## 2.1.1 (2020-05-27)

### Bug Fixes

- **select.tsx, select.scss:** fixed UI bugs for next line input ([151671d](https://github.com/freshworks/crayons/commit/151671d9791169be9ef0740f477dec542743554f))

## 2.1.0 (2020-05-22)

### Bug Fixes

- **tabs:** react to changes within fw-tabs ([c1fe804](https://github.com/freshworks/crayons/commit/c1fe804dc27b38333ebf9fa01e3b4df038425c0a))
- month Year Dropdown ([8ac0322](https://github.com/freshworks/crayons/commit/8ac0322895e4c91e381b9a3e425478c303f9923e))
- select component default value fix ([7be93c5](https://github.com/freshworks/crayons/commit/7be93c5d5f1e5e5c94604d58d4c84afd2d36260f))
- style and default value fix ([dda833f](https://github.com/freshworks/crayons/commit/dda833f3f5440a3fde480131f861f0d11b39f4f1))

### Features

- **datepicker:** adding Datepicker component ([9208e76](https://github.com/freshworks/crayons/commit/9208e765ce161edbce3ca497521c8c06bc946f1f))

## 2.0.5 (2020-05-22)

### Bug Fixes

- **tabs:** react to changes within fw-tabs ([c1fe804](https://github.com/freshworks/crayons/commit/c1fe804dc27b38333ebf9fa01e3b4df038425c0a))

## 2.0.5 (2020-05-19)

### Bug Fixes

- **tabs:** react to changes within fw-tabs ([cbd2895](https://github.com/freshworks/crayons/commit/cbd2895c940708ddee50f7634a276b44b4478fca))

## 2.0.4 (2020-05-07)

### Bug Fixes

- **textarea:** fixes default textarea width to be 100% ([b475c35](https://github.com/freshworks/crayons/commit/b475c3585755a901865429afeb761bc92f99194e)), closes [#30](https://github.com/freshworks/crayons/issues/30)

## 2.0.3 (2020-05-06)

### Bug Fixes

- **select:** fixes select ([93cea4f](https://github.com/freshworks/crayons/commit/93cea4f9aed40f0d08b936eefe7f35cee4a65290))

## 2.0.2 (2020-05-06)

### Bug Fixes

- **select:** fixes error and warning css for select ([c9739fe](https://github.com/freshworks/crayons/commit/c9739fe35e921a18ecbc660413e70a11b05dbffa)), closes [#74](https://github.com/freshworks/crayons/issues/74)

## 2.0.1 (2020-05-06)

### Bug Fixes

- **select:** fixes Select bug that caused `fwChange` not to be fired for last multi-select option ([650c205](https://github.com/freshworks/crayons/commit/650c205022a148697235594eeb223fc2b03a2ce8)), closes [#68](https://github.com/freshworks/crayons/issues/68)

## 2.0.0 (2020-05-06)

### Documentation

- documents ([42055c2](https://github.com/freshworks/crayons/commit/42055c202ea1dc34601c9c2ffc3bf924b09dcee1))

### BREAKING CHANGES

- documents

## 1.1.0 (2020-04-29)

### Features

- **fw-select-options, fw-select, fw-tag:** added 'disabled' state to fw-select options ([d15eb0f](https://github.com/freshworks/crayons/commit/d15eb0fb5900f8839cd8a3887e70246d3990eef4))

## 1.0.1 (2020-04-15)

### Bug Fixes

- **tabs:** fixes initial render for Tabs component ([7ffe365](https://github.com/freshworks/crayons/commit/7ffe365e166455ce0bf06358da7607b517c7985a))

## 1.0.0 (2020-04-15)

### Bug Fixes

- **tab, tabs:** fixes querying nested components ([0f7e9e2](https://github.com/freshworks/crayons/commit/0f7e9e2a4ab784b8d00a3db7956f2f587891a34f))

### Reverts

- reverting Tokens ([e2f2b9a](https://github.com/freshworks/crayons/commit/e2f2b9aa425e6292213697ba835ba876fb3d338c))