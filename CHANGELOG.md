# [2.0.0-beta.21](https://github.com/jiverson/floating-vue/compare/14d1d32679fa39caea5e7a021d8dc94aa506f928...v2.0.0-beta.21) (2023-04-14)


### Bug Fixes

* `boundariesElement` prop allowed types ([#122](https://github.com/jiverson/floating-vue/issues/122)) ([617ab8c](https://github.com/jiverson/floating-vue/commit/617ab8cd3d68143dfaa75b1a49f3ef26aaf3d71a))
* $refs.popper can be null initially ([4c7f4b9](https://github.com/jiverson/floating-vue/commit/4c7f4b930aa6fc8bd9db87cf6e1eb821bc09d80e))
* allow container = false ([86ab044](https://github.com/jiverson/floating-vue/commit/86ab044206e682c6c960143025e57fb9243d52ee))
* applyModifier ([6f54d1b](https://github.com/jiverson/floating-vue/commit/6f54d1bd270b60e7666e4bc598a6b2745332dc1e))
* aria-describedby only when open ([1c63f16](https://github.com/jiverson/floating-vue/commit/1c63f16b1643c7037cc6709c696b7cc2acbf37a8))
* arrow hidding ([d9644c2](https://github.com/jiverson/floating-vue/commit/d9644c2cd5f24188d72e9cfa6fd5d6030e5d0812))
* arrow position ([6ffb743](https://github.com/jiverson/floating-vue/commit/6ffb743c20474b4a48760102def12f62cb9385a8))
* arrow position ([844bc98](https://github.com/jiverson/floating-vue/commit/844bc981aedb854ec9adbb124c19025c559e1e47))
* arrow regression ([067aa4b](https://github.com/jiverson/floating-vue/commit/067aa4ba459a568af43f70f968dc64b8aa680076))
* arrow selector ([402eedb](https://github.com/jiverson/floating-vue/commit/402eedba962b9e4519346e0ace98f3c9b5f68fa7))
* **assign:** remove debugger ([f64a720](https://github.com/jiverson/floating-vue/commit/f64a720601ec2dae810df76f4f9fb7bfa8582b20))
* autoMaxSize - reset size to allow bestFit ([40dae98](https://github.com/jiverson/floating-vue/commit/40dae98d01932beee568db0e071c6e77f2c83882))
* babel not transpiling vue files ([9fb5723](https://github.com/jiverson/floating-vue/commit/9fb5723dbfbdc599b47e93c02fb83dc260d37fb8))
* better global close logic, fixes v-close-popper ([3939fe0](https://github.com/jiverson/floating-vue/commit/3939fe0ef80d1c39c40b5478fa1ba1596bd977e5))
* bigger inner arrow to prevent visual seams between the arrow and the background ([5b2e76f](https://github.com/jiverson/floating-vue/commit/5b2e76f5f787edffef8c37c6bf8b5bde721c073c))
* call _setContent after popper instance is created, closes [#254](https://github.com/jiverson/floating-vue/issues/254) ([4fd943b](https://github.com/jiverson/floating-vue/commit/4fd943b141f065a6f1d01389005e7ab890b984e0))
* check for contains before requestAnimationFrame, closes [#253](https://github.com/jiverson/floating-vue/issues/253) ([1a486f2](https://github.com/jiverson/floating-vue/commit/1a486f277f0f5688c83e80fd5dd02bccf8727ac0))
* cleanup ([4d356c2](https://github.com/jiverson/floating-vue/commit/4d356c2b75487cb3921211e6bf37ae9c1a792704))
* close-popper not working in nested submenu ([980e42b](https://github.com/jiverson/floating-vue/commit/980e42b29dba901dddc3d476126ed31f977c052d))
* **config:** don't autohide by default for tooltip theme ([cf4593c](https://github.com/jiverson/floating-vue/commit/cf4593c057bb3e2c9ef2c0d7e616fea232ccee4d))
* contains error fix [#80](https://github.com/jiverson/floating-vue/issues/80) ([c226544](https://github.com/jiverson/floating-vue/commit/c226544a4a71e13b2737c7913355fd01935f42ec))
* contentHtml default to false + docs ([3cc96b7](https://github.com/jiverson/floating-vue/commit/3cc96b7e0f35f678e98034f892c012a58f927e7a))
* createTooltip().show() ([56bc9d2](https://github.com/jiverson/floating-vue/commit/56bc9d29d77cb88346d39357f81749284ade0dc8))
* css file name ([476e05a](https://github.com/jiverson/floating-vue/commit/476e05ae793d0b5ec50cbf4efe22f81473196c90))
* default Dropdown padding too big ([a89155f](https://github.com/jiverson/floating-vue/commit/a89155f0449aae2583598b552401d8e98a4d1704))
* default for instantMove ([58793d6](https://github.com/jiverson/floating-vue/commit/58793d6dac0bbd268b1587d23e2c77aa184dd41a))
* default offset for arrow ([dc4462c](https://github.com/jiverson/floating-vue/commit/dc4462cfd11b659cd88ffcbd62b5a0f28145d099))
* disposeTimeout not working, closes [#941](https://github.com/jiverson/floating-vue/issues/941) ([#947](https://github.com/jiverson/floating-vue/issues/947)) ([64fb0ec](https://github.com/jiverson/floating-vue/commit/64fb0ecc28c398729c9692d98b545b12675f4a22))
* don't auto hide parent if contains click ([98d9449](https://github.com/jiverson/floating-vue/commit/98d94492c5232c68d20498e9dca52eb79140f4c6))
* don't compute position on scroll if hidden, closes [#835](https://github.com/jiverson/floating-vue/issues/835) ([f2199da](https://github.com/jiverson/floating-vue/commit/f2199da0f113dcdfb6a43382acf6bc17a8733727))
* don't hide on target click if trigger contains 'click' ([d568e79](https://github.com/jiverson/floating-vue/commit/d568e7921cd998a325855bbebcff30f45c3546a9))
* don't use $el ([29e9992](https://github.com/jiverson/floating-vue/commit/29e99924f681e2b77fdfd7c87da2e5ea62ab7a50))
* duplicate classes ([9740a35](https://github.com/jiverson/floating-vue/commit/9740a3546fa98bcff28d019ba4502411a5c1589a))
* duplicate hide events, closes [#376](https://github.com/jiverson/floating-vue/issues/376) ([5a4ff05](https://github.com/jiverson/floating-vue/commit/5a4ff05f6c15a2f9ea91b664c2322d047ce20554))
* dynamic options update fix [#101](https://github.com/jiverson/floating-vue/issues/101) ([ed1dfb7](https://github.com/jiverson/floating-vue/commit/ed1dfb7acfaf1b4c6c05357d11a8502ea127a2a7))
* eagerMount for tooltip directive ([46cba72](https://github.com/jiverson/floating-vue/commit/46cba72f04fac2019f249b7e9c5978ea70d403a3))
* exclude popper content from target nodes ([dcd6159](https://github.com/jiverson/floating-vue/commit/dcd61598f8294394883d0565159a3cffc3126c39))
* getAttribute is not a function error ([97930b9](https://github.com/jiverson/floating-vue/commit/97930b9f4cb4c74881e026ee2aa40551df8c8ac7))
* getTargetNodes ([abe7272](https://github.com/jiverson/floating-vue/commit/abe7272861e9e34fbbab2036c583e2877d5582d6))
* handle vnodes might be in scoped slot ([066602a](https://github.com/jiverson/floating-vue/commit/066602ad1ad3c84ef3fea82e78861383abd4904f))
* handleGlobalClose ([45bc800](https://github.com/jiverson/floating-vue/commit/45bc80058963337bce56bdb2fd3608ae20209c0b))
* has v-tooltip CSS class name ([fa8b30f](https://github.com/jiverson/floating-vue/commit/fa8b30f1601921c69c2b7c16f2744cd11c60edcf))
* hide v-tooltip apps from vue-devtools 6 ([c21c8c8](https://github.com/jiverson/floating-vue/commit/c21c8c8da16398cee6c697e82756a65ef34074e7))
* ignore tests for npm fix [#96](https://github.com/jiverson/floating-vue/issues/96) ([e0ef9d6](https://github.com/jiverson/floating-vue/commit/e0ef9d61331d0fe265a5d899f245b5f6a8d6e55b))
* inner content behind inner arrow ([3ed3d30](https://github.com/jiverson/floating-vue/commit/3ed3d302a9c4ea5b32d88eba7d4acb9fb265e737))
* **instantMove:** don't trigger if no popper was open at all ([ce0db83](https://github.com/jiverson/floating-vue/commit/ce0db835c57c9dbd27707c22caa20769f36c6eb4))
* lazily create popper content ([77d2927](https://github.com/jiverson/floating-vue/commit/77d292755d4f0518a069b13d4c713d33197630cb))
* manual tooltip closing on document touch, closes [#158](https://github.com/jiverson/floating-vue/issues/158) ([1659ce5](https://github.com/jiverson/floating-vue/commit/1659ce5eb3706da60046a789ad4d03dabc728d1c))
* max-size on inner > div ([3699726](https://github.com/jiverson/floating-vue/commit/3699726e214e5b5dcfaf027037f6a5280f9505e2))
* merge modifiers ([9d7eb0f](https://github.com/jiverson/floating-vue/commit/9d7eb0fbec067fd6030ea6e87100f78558d81ef2))
* missing export ([b2428f1](https://github.com/jiverson/floating-vue/commit/b2428f1f9189add3f9b9c770ca87d1799f312158))
* missing Menu export ([7848884](https://github.com/jiverson/floating-vue/commit/7848884b6bf4217fd062c34bd40fbaf8c5bcd0fc))
* modifier.options undefined ([984b825](https://github.com/jiverson/floating-vue/commit/984b825194a20abf928eb2c22adb0b1673c4a22b))
* mounting errors between directive and components ([7d0ce5d](https://github.com/jiverson/floating-vue/commit/7d0ce5d1d4d0f3f59a0e43c73062024c07ce2a41))
* move test to tests ([48a0f5b](https://github.com/jiverson/floating-vue/commit/48a0f5bbe5f3d6ad979a39510ad2d5ef97a776af))
* nodejs compatibility fix [#59](https://github.com/jiverson/floating-vue/issues/59) ([650e057](https://github.com/jiverson/floating-vue/commit/650e057fc7b0b32cfe36a9b6e0c360e6dedea9f5))
* null error ([6fb80b3](https://github.com/jiverson/floating-vue/commit/6fb80b3be87e4946279f54e9e905599780001ef4))
* null fallback tooltip ([adbec36](https://github.com/jiverson/floating-vue/commit/adbec36bda6d7a5eabb953435a4946fe7bc5c198))
* popover focus trigger fix [#85](https://github.com/jiverson/floating-vue/issues/85) ([305c235](https://github.com/jiverson/floating-vue/commit/305c23557694ba8fd37f597d9023962ee7a14ffe))
* popover resizer style ([4bab09f](https://github.com/jiverson/floating-vue/commit/4bab09f47e1a8ce6ad3d80904103b8ec91fa4259))
* **Popover:** hide when deactivated ([cf37ca3](https://github.com/jiverson/floating-vue/commit/cf37ca3464b92aceb4f50aaea5a766ebacca74c8))
* **Popover:** use div instead of span, closes [#123](https://github.com/jiverson/floating-vue/issues/123) ([63cebfe](https://github.com/jiverson/floating-vue/commit/63cebfe1b503104bfc180e6889679f8083ca66d4))
* **Popper:** add attrs to root div ([4391e5c](https://github.com/jiverson/floating-vue/commit/4391e5c2f5e454b00fb7754d3e374c4fd95c264a))
* **Popper:** auto show on activated ([1ac069a](https://github.com/jiverson/floating-vue/commit/1ac069a25561c66e21433ecfef83630355588a73))
* popperClass prop type ([9ffd7a4](https://github.com/jiverson/floating-vue/commit/9ffd7a43683ce7c01de6e7c9dacdc495bf194a49))
* **PopperContent:** remove unnecessary attribute ([7abc87c](https://github.com/jiverson/floating-vue/commit/7abc87c0ba094a2fe926d9b7d29d17ef0ecca913))
* **Popper:** disabled now call init() and dispose() instead of just showing/hidding the popper ([cc689e6](https://github.com/jiverson/floating-vue/commit/cc689e68580e654845d66ee7c914b8c02047f7ed))
* **Popper:** errors on handleGlobalClose if popper parent component is destroyed ([f16bc84](https://github.com/jiverson/floating-vue/commit/f16bc849c3fef1a4d200d9eda5ef5ae075f2d21c))
* **Popper:** skipDelay not working ([70043d3](https://github.com/jiverson/floating-vue/commit/70043d3850dfe0f3bf0b32b9f5878fe70f40549a))
* **Popper:** triggerNode & popperNode references ([9c0a2f7](https://github.com/jiverson/floating-vue/commit/9c0a2f7bbc14f8a5de7b6ad3d79286d6fc621013))
* **PopperWrapper:** remove inline-block, closes [#160](https://github.com/jiverson/floating-vue/issues/160) ([8b4441f](https://github.com/jiverson/floating-vue/commit/8b4441f51619bb1fdbf5a41d8aa5807f55de21d4))
* prevent multiple init() ([dc2600d](https://github.com/jiverson/floating-vue/commit/dc2600dcec3d73d7b6bd0a736d33d8b076555137))
* prevent popovers from staying open when moving mouse too quickly ([#228](https://github.com/jiverson/floating-vue/issues/228)) ([6095472](https://github.com/jiverson/floating-vue/commit/60954725804fb2bc4028f21dd310f61f6de7a6cb))
* publish sources fix [#102](https://github.com/jiverson/floating-vue/issues/102) ([47175b3](https://github.com/jiverson/floating-vue/commit/47175b3f0957f8253e1ef11e86eaae79eff1db9f))
* remove applyModifier ([7064757](https://github.com/jiverson/floating-vue/commit/70647574b817db0bf0e58008efa3c1291f82fb35))
* remove browser outline on dropdown, fix [#848](https://github.com/jiverson/floating-vue/issues/848) ([48508c4](https://github.com/jiverson/floating-vue/commit/48508c47a84319efd5ebebdc596b32de51fdb528))
* remove duplicate component registration ([a27d1a3](https://github.com/jiverson/floating-vue/commit/a27d1a38cdef8d6eb1588aecb516876c60e94821))
* remove internal style on `.v-popper` ([2698d84](https://github.com/jiverson/floating-vue/commit/2698d849807e19c001c5e2f11f9b6ae9d37028ca))
* restore nuxt 3 support, closes [#820](https://github.com/jiverson/floating-vue/issues/820) ([f6397ea](https://github.com/jiverson/floating-vue/commit/f6397ea2adcb54241393f928a239a4f8fe70f04e))
* rollup-plugin-vue generated code not transpiled by babel, closes [#239](https://github.com/jiverson/floating-vue/issues/239) ([2d23585](https://github.com/jiverson/floating-vue/commit/2d23585ac0235529c6c0f6df385f2043bc9ad7a5))
* scoped CSS not working ([0524082](https://github.com/jiverson/floating-vue/commit/05240825e0f0191d8b30bea650bd7a0aeddd709e))
* silence popperNode() errors, closes [#828](https://github.com/jiverson/floating-vue/issues/828) ([490600c](https://github.com/jiverson/floating-vue/commit/490600c3fc0d90cfb5666c6ac26817a757acfb6c))
* some directive tooltips not working ([d3c3b3d](https://github.com/jiverson/floating-vue/commit/d3c3b3d2d2d0c0cff3d50a0f643b4a922314f0d9))
* strategy prop not taken into account ([ab840b2](https://github.com/jiverson/floating-vue/commit/ab840b2c0ef78729455520fb988c8dc210b2a404))
* SVGElement doesn't prototype, closes [#246](https://github.com/jiverson/floating-vue/issues/246) ([975e04b](https://github.com/jiverson/floating-vue/commit/975e04b5e4c2eba07dbfb0a99cd0d3c4ee1e5be3))
* swap title attr to data-original-title ([77ee61f](https://github.com/jiverson/floating-vue/commit/77ee61f4019020e3e6bca7c631555cce6ddf34bf))
* theme null on .v-popper ([25db8e8](https://github.com/jiverson/floating-vue/commit/25db8e8d403a8991a911ebf725154bee3cb3e4ac))
* tooltip not closing when aiming it, closes [#851](https://github.com/jiverson/floating-vue/issues/851) ([f2a9018](https://github.com/jiverson/floating-vue/commit/f2a90187155974e764e648e8feef1cadbcaafe03))
* tooltip style with transparent background ([233af18](https://github.com/jiverson/floating-vue/commit/233af18aa01d2b65c5425cd3bd968fa790ec4148))
* **Tooltip:** bind show and hide methods, fix _hide is not a function ([77755b7](https://github.com/jiverson/floating-vue/commit/77755b7f17d3cd020dded27c12d7b0089dc8b3ff))
* **Tooltip:** properly remove aria-describedby when tooltip is removed from DOM, closes [#191](https://github.com/jiverson/floating-vue/issues/191) ([a5512f1](https://github.com/jiverson/floating-vue/commit/a5512f132f1ea840088f1c4802e456343cc69fc8))
* Transform arrow functions into class methods ([#152](https://github.com/jiverson/floating-vue/issues/152)) ([8f38a5e](https://github.com/jiverson/floating-vue/commit/8f38a5e4bb7045a3137b7ae13d63f63d8b6c2363))
* typo in module entry ([1b972d8](https://github.com/jiverson/floating-vue/commit/1b972d8939aaf7851408f830966a23b4010789ce))
* unit test ([79a435c](https://github.com/jiverson/floating-vue/commit/79a435c2a24a5cbd48cff4c64cdab77f51f23444))
* update popper position on window resize ([5f5aa5d](https://github.com/jiverson/floating-vue/commit/5f5aa5d2014100e585f9a3b56fc8d841284f7917))
* use capture for autohide fix [#93](https://github.com/jiverson/floating-vue/issues/93) ([2b6309c](https://github.com/jiverson/floating-vue/commit/2b6309c995535f8d23902849ad9a7f33cdd706f3))
* use latest lodash, closes [#209](https://github.com/jiverson/floating-vue/issues/209) ([d04ce8f](https://github.com/jiverson/floating-vue/commit/d04ce8f99543ff67a2295912c58fb6e693c79ec3))
* use passive: true for events, closes [#776](https://github.com/jiverson/floating-vue/issues/776) ([6f9e7d1](https://github.com/jiverson/floating-vue/commit/6f9e7d1823543c629e75bcf81a3b80d7ac372ac8))
* use Popper.placements ([818e028](https://github.com/jiverson/floating-vue/commit/818e0289eef58b561979e3b05d84c0eed9c3d705))
* use prepublishOnly ([62f2111](https://github.com/jiverson/floating-vue/commit/62f211182f69fe5b19fa3ad7e49fb65e44152ea7))
* **v-tooltip:** async content improvements ([3a7a9e3](https://github.com/jiverson/floating-vue/commit/3a7a9e3975c74ed81a98eea3986b610f85d020fa))
* **v-tooltip:** async content resize ([590aba0](https://github.com/jiverson/floating-vue/commit/590aba0f5479e57b3fe5c64060aaa62d86eb0f87))
* **v-tooltip:** content type Number ([90d5c23](https://github.com/jiverson/floating-vue/commit/90d5c2332026a46f6ed1cf5528eb450014a25633))
* **v-tooltip:** reactivity ([ae052dc](https://github.com/jiverson/floating-vue/commit/ae052dce06768bc50bb8acb21c1d32904edee163))
* **v-tooltip:** separate props from attrs to prevent options mutation ([c20c092](https://github.com/jiverson/floating-vue/commit/c20c0929070ef16be106afca1e35756ab809642d))
* **v-tooltip:** update popper on nextTick ([56431a9](https://github.com/jiverson/floating-vue/commit/56431a9fafa44ad2acb6d281cb0da030d021fabd))
* VClosePopper export ([de12ff4](https://github.com/jiverson/floating-vue/commit/de12ff450ff1d5f1ca822fd2d82eeecff296b5f3))
* window not defined in non-browser envs ([4e12598](https://github.com/jiverson/floating-vue/commit/4e125984b0e75dc18309461ad91ce340988c492d))


### Code Refactoring

* rename contentHtml to html ([da648a3](https://github.com/jiverson/floating-vue/commit/da648a3009206c2cfd4c1cfa1329c420142fd7b0))
* triggers ([dd967f0](https://github.com/jiverson/floating-vue/commit/dd967f08ad8cbeba931a8ad3433f89817661daac))
* unify words to show/hide ([9c17bea](https://github.com/jiverson/floating-vue/commit/9c17bea3d9436d74b6656b3fca1862aebad4cc12))
* use popperjs 2 ([8ccd62d](https://github.com/jiverson/floating-vue/commit/8ccd62d0b99b1e57902d85b78c4d9937548f62ef))


### Features

* add aiming expiration delay ([01ef6f8](https://github.com/jiverson/floating-vue/commit/01ef6f86aadc43488ade03cffd2158f2825cb416))
* add open popper classes on body ([29c9d78](https://github.com/jiverson/floating-vue/commit/29c9d7862b02aa330c22c582b1e119cd7d86ff90))
* add Plugin.version ([74f6969](https://github.com/jiverson/floating-vue/commit/74f6969a04a26f56422d817400f94ef06c940e74))
* Add popoverOpenClass prop + default value ([#156](https://github.com/jiverson/floating-vue/issues/156)) ([fa672f6](https://github.com/jiverson/floating-vue/commit/fa672f6d6d2004d9cb285ce4551f12c9ca1f6540))
* add popper methods show/hide to createTooltip() ([bf2bb49](https://github.com/jiverson/floating-vue/commit/bf2bb494743fb01601881ab927cac6772bb06cd2))
* add props to default slot ([1f003f4](https://github.com/jiverson/floating-vue/commit/1f003f4808e87c75006f4a3eac1f120464f24e69))
* apply-show and apply-hide events fix [#118](https://github.com/jiverson/floating-vue/issues/118) ([99ff244](https://github.com/jiverson/floating-vue/commit/99ff244a20e519be915da98118d462f3d6dcd7db))
* ariaId prop + better random ID ([573dbd7](https://github.com/jiverson/floating-vue/commit/573dbd7ffb4cc703172ac11008513de58068eb03))
* arrowOverflow prop ([0ed3801](https://github.com/jiverson/floating-vue/commit/0ed3801863b4654ef89d438ecb2b016fe6aad9ee))
* autofocus popper node ([0a39097](https://github.com/jiverson/floating-vue/commit/0a39097bb99da8f3e1fd6a9595fbf6468ea17a21))
* autoHide function prop ([ec3313d](https://github.com/jiverson/floating-vue/commit/ec3313d9921a1f14bc1614e3341edbb997aa44fa))
* autoMinSize ([f45b95a](https://github.com/jiverson/floating-vue/commit/f45b95a4406a2a93b10182661facda1a7455d1f4))
* autoMinSize => autoSize, autoMaxSize => autoBoundaryMaxSize, closes [#834](https://github.com/jiverson/floating-vue/issues/834) ([b198353](https://github.com/jiverson/floating-vue/commit/b198353f781a4a1552c2bf23b6fcf8ad48810536))
* backdrop element to improve autohide on mobile ([803dcca](https://github.com/jiverson/floating-vue/commit/803dcca0bb655ab6201a6ab6063308bae91842a6))
* border + arrow border ([73c3a1e](https://github.com/jiverson/floating-vue/commit/73c3a1e07a9b6f85757cf8b6cd5b6cf94c89035a))
* computeTransformOrigin ([49cd871](https://github.com/jiverson/floating-vue/commit/49cd87128f625942577950e20cb9a8b86384c732))
* eagerMount ([8b21daf](https://github.com/jiverson/floating-vue/commit/8b21daf6b7f57888ea3cef9c2e591fe3624bd47d))
* expose isOpen to slot ([44b6a6d](https://github.com/jiverson/floating-vue/commit/44b6a6d3946dc99b72b8f644288d5548c206f8ba))
* handle diagonal submenu (aim) ([df5e9e9](https://github.com/jiverson/floating-vue/commit/df5e9e9f65b2805a0e2d091deddefc02c9661216))
* hide tooltip on target click ([433f07b](https://github.com/jiverson/floating-vue/commit/433f07bf0b9e94e38ba1a27baf4df07c59609701))
* hideAllPoppers ([a29afe5](https://github.com/jiverson/floating-vue/commit/a29afe5cf3c4a39de7813e8d58e1907277fdbd1c))
* html option fix [#110](https://github.com/jiverson/floating-vue/issues/110) ([a905189](https://github.com/jiverson/floating-vue/commit/a9051899d4a66fd9ceb326c673ac2553189de122))
* improved classes for animations ([d901326](https://github.com/jiverson/floating-vue/commit/d901326e9e99f659a940f9a4c3fe3abc78f1fe35))
* instantMove prop ([8e3c246](https://github.com/jiverson/floating-vue/commit/8e3c246baa8f50a7b3badab867f8e5f7e11d5667))
* nested poppers auto lock ([75694ae](https://github.com/jiverson/floating-vue/commit/75694aefde5bf2442c219ecae7c5a767d7c525de))
* new `data-popper-shown` to help apply styles to v-tooltip targets ([94ed925](https://github.com/jiverson/floating-vue/commit/94ed9250aa1c8df3c1d0b2e97d7b86472fec0b4d))
* noAutoFocus ([919df7c](https://github.com/jiverson/floating-vue/commit/919df7c71c7c058e36be0e04121adbdc2a8939b9))
* **Popover:** close with [esc] ([76c5f69](https://github.com/jiverson/floating-vue/commit/76c5f69b5660b4b9c500c60ff352e9c3110d3b92))
* popper self triggers ([24e0272](https://github.com/jiverson/floating-vue/commit/24e02724756a12e349b5256190a9e92f61110db9))
* popper slot: hide prop ([14000eb](https://github.com/jiverson/floating-vue/commit/14000eb2675414294a73c22547fb92a36ad9d8f6))
* popperClass ([6e5b319](https://github.com/jiverson/floating-vue/commit/6e5b3190457b4e1321a4de3ed47918637ee32add))
* **PopperWrapper:** support title prop ([59d9d53](https://github.com/jiverson/floating-vue/commit/59d9d53e506fbe45ba5952e5b0569e2d03c15b61))
* positioningDisabled + mobile example ([433118a](https://github.com/jiverson/floating-vue/commit/433118a54be7762941c1eb09fec1a8e8e39dc556))
* single app for v-tooltip directives ([649c38d](https://github.com/jiverson/floating-vue/commit/649c38d650fe32a9f5433f9b0349fe6a588dde12))
* support 'touch' trigger ([02e3255](https://github.com/jiverson/floating-vue/commit/02e32555779598f7a7d18ec26f85d6624789db45))
* switch classes to v-popper__arrow-inner and v-popper__arrow-outer ([3f48173](https://github.com/jiverson/floating-vue/commit/3f48173ca02202b8b500cc7060d8ef40ba5bfeb6))
* switch to floating-ui ([e28f594](https://github.com/jiverson/floating-vue/commit/e28f5946c83904763b222cf9f6c7b56c4720f3e2))
* **Tooltip:** remove title attribute, closes [#183](https://github.com/jiverson/floating-vue/issues/183) ([2c8adac](https://github.com/jiverson/floating-vue/commit/2c8adac30dfd8a55a2b8f29786cf992feda8b154))
* triggerShow, triggerHide, array trigger ([a9a8ee2](https://github.com/jiverson/floating-vue/commit/a9a8ee2076e9217f50a5b9f46a001a2d8276b041))
* update package ([#1](https://github.com/jiverson/floating-vue/issues/1)) ([91876fb](https://github.com/jiverson/floating-vue/commit/91876fbf8a4d1d4a9faa37f9ecc2b7d6f7e70a7e))
* v-close-popper only close closest nested popper ([81af5e5](https://github.com/jiverson/floating-vue/commit/81af5e544962613cf5355e3a32848f94fb8a5348))
* v-tooltip-open class fix [#87](https://github.com/jiverson/floating-vue/issues/87) ([2fbbcc4](https://github.com/jiverson/floating-vue/commit/2fbbcc4ab2a5fd237bf6bcef0dd676c596dafde3))
* **v-tooltip:** support async content ([122be6f](https://github.com/jiverson/floating-vue/commit/122be6f8ca03d3d47c48ef036951cd8a652101c1))
* vue3 version ([872feef](https://github.com/jiverson/floating-vue/commit/872feef42f01e44ce522b960b8eaf973b43649a3))


### Reverts

* Revert "Better event performance by using mouseover" ([14d1d32](https://github.com/jiverson/floating-vue/commit/14d1d32679fa39caea5e7a021d8dc94aa506f928))
* don't put divs for v-tooltip directive ([cf463c4](https://github.com/jiverson/floating-vue/commit/cf463c48de8dfaa4814b8c78932adf420e103e5c))


### BREAKING CHANGES

* - The following internal style on `.v-popper` has been removed:
```css
.v-popper {
  width: max-content;
}
```
* - replace all `v-popper__arrow-border` to `v-popper__arrow-outer`
- replace all `v-popper__arrow` to `v-popper__arrow-inner`
* - `open` prop renamed to `shown`
- `openGroup` prop renamed to `showGroup`
- `isOpen` slot prop renamed to `shown`
* - `trigger` renamed to `triggers`
- `trigger` must now be an array of strings
- `triggerShow` renamed to `showTriggers`
- `triggerHide` renamed to `hideTriggers`
* - (Directive) `contentHtml` property was renamed to simply `html`
* - Popperjs API changed with breaking changes (notably the modifiers API)
- `offset` is now an array: [skidding, distance]
- `boundariesElement` was renamed to `boundary` to match popperjs 2
- Modifiers should be customized using the `modifiers` prop instead of `popperOptions`



# [2.0.0-beta.20](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.19...v2.0.0-beta.20) (2022-09-08)


### Features

* noAutoFocus ([919df7c](https://github.com/Akryum/v-tooltip/commit/919df7c71c7c058e36be0e04121adbdc2a8939b9))



# [2.0.0-beta.19](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.18...v2.0.0-beta.19) (2022-08-02)


### Bug Fixes

* $refs.popper can be null initially ([4c7f4b9](https://github.com/Akryum/v-tooltip/commit/4c7f4b930aa6fc8bd9db87cf6e1eb821bc09d80e))



# [2.0.0-beta.18](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.17...v2.0.0-beta.18) (2022-08-02)


### Bug Fixes

* duplicate classes ([9740a35](https://github.com/Akryum/v-tooltip/commit/9740a3546fa98bcff28d019ba4502411a5c1589a))
* remove duplicate component registration ([a27d1a3](https://github.com/Akryum/v-tooltip/commit/a27d1a38cdef8d6eb1588aecb516876c60e94821))



# [2.0.0-beta.17](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.16...v2.0.0-beta.17) (2022-05-30)


### Bug Fixes

* remove browser outline on dropdown, fix [#848](https://github.com/Akryum/v-tooltip/issues/848) ([48508c4](https://github.com/Akryum/v-tooltip/commit/48508c47a84319efd5ebebdc596b32de51fdb528))
* scoped CSS not working ([0524082](https://github.com/Akryum/v-tooltip/commit/05240825e0f0191d8b30bea650bd7a0aeddd709e))



# [2.0.0-beta.16](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.15...v2.0.0-beta.16) (2022-04-29)


### Bug Fixes

* **Popper:** add attrs to root div ([4391e5c](https://github.com/Akryum/v-tooltip/commit/4391e5c2f5e454b00fb7754d3e374c4fd95c264a))



# [2.0.0-beta.15](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.14...v2.0.0-beta.15) (2022-04-11)


### Features

* autoHide function prop ([ec3313d](https://github.com/Akryum/v-tooltip/commit/ec3313d9921a1f14bc1614e3341edbb997aa44fa))



# [2.0.0-beta.14](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.13...v2.0.0-beta.14) (2022-04-08)


### Bug Fixes

* tooltip not closing when aiming it, closes [#851](https://github.com/Akryum/v-tooltip/issues/851) ([f2a9018](https://github.com/Akryum/v-tooltip/commit/f2a90187155974e764e648e8feef1cadbcaafe03))



# [2.0.0-beta.13](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.12...v2.0.0-beta.13) (2022-04-05)


### Bug Fixes

* createTooltip().show() ([56bc9d2](https://github.com/Akryum/v-tooltip/commit/56bc9d29d77cb88346d39357f81749284ade0dc8))



# [2.0.0-beta.12](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.15...v2.0.0-beta.12) (2022-03-30)


Included changes from `v1.0.0-beta.15`:


### Features

* add open popper classes on body ([29c9d78](https://github.com/Akryum/v-tooltip/commit/29c9d7862b02aa330c22c582b1e119cd7d86ff90))
* autofocus popper node ([0a39097](https://github.com/Akryum/v-tooltip/commit/0a39097bb99da8f3e1fd6a9595fbf6468ea17a21))



# [2.0.0-beta.11](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.14...v2.0.0-beta.11) (2022-03-23)

Included changes from `v1.0.0-beta.14`:


### Bug Fixes

* close-popper not working in nested submenu ([980e42b](https://github.com/Akryum/v-tooltip/commit/980e42b29dba901dddc3d476126ed31f977c052d))


### Features

* v-close-popper only close closest nested popper ([81af5e5](https://github.com/Akryum/v-tooltip/commit/81af5e544962613cf5355e3a32848f94fb8a5348))



# [2.0.0-beta.10](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.13...v2.0.0-beta.10) (2022-03-23)

Included changes from `v1.0.0-beta.13`:


### Bug Fixes

* don't auto hide parent if contains click ([98d9449](https://github.com/Akryum/v-tooltip/commit/98d94492c5232c68d20498e9dca52eb79140f4c6))



# [2.0.0-beta.9](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.12...v2.0.0-beta.9) (2022-03-23)


### Bug Fixes

* don't use $el ([29e9992](https://github.com/Akryum/v-tooltip/commit/29e99924f681e2b77fdfd7c87da2e5ea62ab7a50))

---

Included changes from `v1.0.0-beta.12`:


### Features

* add aiming expiration delay ([01ef6f8](https://github.com/Akryum/v-tooltip/commit/01ef6f86aadc43488ade03cffd2158f2825cb416))
* handle diagonal submenu (aim) ([df5e9e9](https://github.com/Akryum/v-tooltip/commit/df5e9e9f65b2805a0e2d091deddefc02c9661216))
* nested poppers auto lock ([75694ae](https://github.com/Akryum/v-tooltip/commit/75694aefde5bf2442c219ecae7c5a767d7c525de))



# [2.0.0-beta.8](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.7...v2.0.0-beta.8) (2022-03-11)


### Bug Fixes

* theme null on .v-popper ([25db8e8](https://github.com/Akryum/v-tooltip/commit/25db8e8d403a8991a911ebf725154bee3cb3e4ac))



# [2.0.0-beta.7](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.11...v2.0.0-beta.7) (2022-03-11)


### Bug Fixes

* restore nuxt 3 support, closes [#820](https://github.com/Akryum/v-tooltip/issues/820) ([f6397ea](https://github.com/Akryum/v-tooltip/commit/f6397ea2adcb54241393f928a239a4f8fe70f04e))

---

Included changes from `v1.0.0-beta.10` and `v1.0.0-beta.11`:


### Bug Fixes

* remove internal style on `.v-popper` ([2698d84](https://github.com/Akryum/v-tooltip/commit/2698d849807e19c001c5e2f11f9b6ae9d37028ca))
* don't compute position on scroll if hidden, closes [#835](https://github.com/Akryum/v-tooltip/issues/835) ([f2199da](https://github.com/Akryum/v-tooltip/commit/f2199da0f113dcdfb6a43382acf6bc17a8733727))
* duplicate hide events, closes [#376](https://github.com/Akryum/v-tooltip/issues/376) ([5a4ff05](https://github.com/Akryum/v-tooltip/commit/5a4ff05f6c15a2f9ea91b664c2322d047ce20554))
* silence popperNode() errors, closes [#828](https://github.com/Akryum/v-tooltip/issues/828) ([490600c](https://github.com/Akryum/v-tooltip/commit/490600c3fc0d90cfb5666c6ac26817a757acfb6c))


### Features

* autoMinSize => autoSize, autoMaxSize => autoBoundaryMaxSize, closes [#834](https://github.com/Akryum/v-tooltip/issues/834) ([b198353](https://github.com/Akryum/v-tooltip/commit/b198353f781a4a1552c2bf23b6fcf8ad48810536))


### BREAKING CHANGES

* The following internal style on `.v-popper` has been removed:
```css
.v-popper {
  width: max-content;
}
```
* `autoMinSize` is deprecated, use `autoSize="min"` instead
* `autoMaxSize` is deprecated, use `autoBoundaryMaxSize` instead



# [2.0.0-beta.6](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.9...v2.0.0-beta.6) (2022-02-09)

Included changes from `v1.0.0-beta.8` and `v1.0.0-beta.9`:

### Bug Fixes

* autoMaxSize - reset size to allow bestFit ([40dae98](https://github.com/Akryum/v-tooltip/commit/40dae98d01932beee568db0e071c6e77f2c83882))
* max-size on inner > div ([3699726](https://github.com/Akryum/v-tooltip/commit/3699726e214e5b5dcfaf027037f6a5280f9505e2))



# [2.0.0-beta.5](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.7...v2.0.0-beta.5) (2022-02-01)

Included changes from `v1.0.0-beta.7`:


### Features

* backdrop element to improve autohide on mobile ([803dcca](https://github.com/Akryum/v-tooltip/commit/803dcca0bb655ab6201a6ab6063308bae91842a6))



# [2.0.0-beta.4](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.6...v2.0.0-beta.4) (2022-02-01)

Included changes from `v1.0.0-beta.6`:

### Features

* positioningDisabled + mobile example ([433118a](https://github.com/Akryum/v-tooltip/commit/433118a54be7762941c1eb09fec1a8e8e39dc556))



# [2.0.0-beta.3](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2022-01-20)


### Bug Fixes

* some directive tooltips not working ([d3c3b3d](https://github.com/Akryum/v-tooltip/commit/d3c3b3d2d2d0c0cff3d50a0f643b4a922314f0d9))



# [2.0.0-beta.2](https://github.com/Akryum/v-tooltip/compare/v2.0.0-beta.1...v2.0.0-beta.2) (2022-01-18)


### Features

* single app for v-tooltip directives ([649c38d](https://github.com/Akryum/v-tooltip/commit/649c38d650fe32a9f5433f9b0349fe6a588dde12))



# [2.0.0-beta.1](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.5...v2.0.0-beta.1) (2022-01-15)


### Features

* vue3 version ([872feef](https://github.com/Akryum/v-tooltip/commit/872feef42f01e44ce522b960b8eaf973b43649a3))



# [1.0.0-beta.15](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.14...v1.0.0-beta.15) (2022-03-30)


### Features

* add open popper classes on body ([29c9d78](https://github.com/Akryum/v-tooltip/commit/29c9d7862b02aa330c22c582b1e119cd7d86ff90))
* autofocus popper node ([0a39097](https://github.com/Akryum/v-tooltip/commit/0a39097bb99da8f3e1fd6a9595fbf6468ea17a21))



# [1.0.0-beta.14](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.13...v1.0.0-beta.14) (2022-03-23)


### Bug Fixes

* close-popper not working in nested submenu ([980e42b](https://github.com/Akryum/v-tooltip/commit/980e42b29dba901dddc3d476126ed31f977c052d))


### Features

* v-close-popper only close closest nested popper ([81af5e5](https://github.com/Akryum/v-tooltip/commit/81af5e544962613cf5355e3a32848f94fb8a5348))



# [1.0.0-beta.13](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.12...v1.0.0-beta.13) (2022-03-23)


### Bug Fixes

* don't auto hide parent if contains click ([98d9449](https://github.com/Akryum/v-tooltip/commit/98d94492c5232c68d20498e9dca52eb79140f4c6))




# [1.0.0-beta.12](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.11...v1.0.0-beta.12) (2022-03-23)


### Features

* add aiming expiration delay ([01ef6f8](https://github.com/Akryum/v-tooltip/commit/01ef6f86aadc43488ade03cffd2158f2825cb416))
* handle diagonal submenu (aim) ([df5e9e9](https://github.com/Akryum/v-tooltip/commit/df5e9e9f65b2805a0e2d091deddefc02c9661216))
* nested poppers auto lock ([75694ae](https://github.com/Akryum/v-tooltip/commit/75694aefde5bf2442c219ecae7c5a767d7c525de))



# [1.0.0-beta.11](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.10...v1.0.0-beta.11) (2022-03-11)


### Bug Fixes

* remove internal style on `.v-popper` ([2698d84](https://github.com/Akryum/v-tooltip/commit/2698d849807e19c001c5e2f11f9b6ae9d37028ca))


### BREAKING CHANGES

* - The following internal style on `.v-popper` has been removed:
```css
.v-popper {
  width: max-content;
}
```



# [1.0.0-beta.10](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.9...v1.0.0-beta.10) (2022-03-11)

### BREAKING CHANGES

- `autoMinSize` is deprecated, use `autoSize="min"` instead
- `autoMaxSize` is deprecated, use `autoBoundaryMaxSize` instead


### Bug Fixes

* don't compute position on scroll if hidden, closes [#835](https://github.com/Akryum/v-tooltip/issues/835) ([f2199da](https://github.com/Akryum/v-tooltip/commit/f2199da0f113dcdfb6a43382acf6bc17a8733727))
* duplicate hide events, closes [#376](https://github.com/Akryum/v-tooltip/issues/376) ([5a4ff05](https://github.com/Akryum/v-tooltip/commit/5a4ff05f6c15a2f9ea91b664c2322d047ce20554))
* silence popperNode() errors, closes [#828](https://github.com/Akryum/v-tooltip/issues/828) ([490600c](https://github.com/Akryum/v-tooltip/commit/490600c3fc0d90cfb5666c6ac26817a757acfb6c))


### Features

* autoMinSize => autoSize, autoMaxSize => autoBoundaryMaxSize, closes [#834](https://github.com/Akryum/v-tooltip/issues/834) ([b198353](https://github.com/Akryum/v-tooltip/commit/b198353f781a4a1552c2bf23b6fcf8ad48810536))




# [1.0.0-beta.9](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.8...v1.0.0-beta.9) (2022-02-09)


### Bug Fixes

* autoMaxSize - reset size to allow bestFit ([40dae98](https://github.com/Akryum/v-tooltip/commit/40dae98d01932beee568db0e071c6e77f2c83882))



# [1.0.0-beta.8](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.7...v1.0.0-beta.8) (2022-02-04)


### Bug Fixes

* max-size on inner > div ([3699726](https://github.com/Akryum/v-tooltip/commit/3699726e214e5b5dcfaf027037f6a5280f9505e2))



# [1.0.0-beta.7](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.6...v1.0.0-beta.7) (2022-02-01)


### Features

* backdrop element to improve autohide on mobile ([803dcca](https://github.com/Akryum/v-tooltip/commit/803dcca0bb655ab6201a6ab6063308bae91842a6))



# [1.0.0-beta.6](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.5...v1.0.0-beta.6) (2022-02-01)


### Features

* positioningDisabled + mobile example ([433118a](https://github.com/Akryum/v-tooltip/commit/433118a54be7762941c1eb09fec1a8e8e39dc556))



# [1.0.0-beta.5](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.4...v1.0.0-beta.5) (2022-01-15)


### Bug Fixes

* strategy prop not taken into account ([ab840b2](https://github.com/Akryum/v-tooltip/commit/ab840b2c0ef78729455520fb988c8dc210b2a404))



# [1.0.0-beta.4](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.3...v1.0.0-beta.4) (2022-01-15)


### Bug Fixes

* typo in module entry ([1b972d8](https://github.com/Akryum/v-tooltip/commit/1b972d8939aaf7851408f830966a23b4010789ce))



# [1.0.0-beta.3](https://github.com/Akryum/v-tooltip/compare/v1.0.0-beta.2...v1.0.0-beta.3) (2022-01-15)


### Bug Fixes

* inner content behind inner arrow ([3ed3d30](https://github.com/Akryum/v-tooltip/commit/3ed3d302a9c4ea5b32d88eba7d4acb9fb265e737))



# [1.0.0-beta.2](https://github.com/Akryum/v-tooltip/compare/v3.0.0-beta.20...v1.0.0-beta.2) (2022-01-15)


### Bug Fixes

* arrow hidding ([d9644c2](https://github.com/Akryum/v-tooltip/commit/d9644c2cd5f24188d72e9cfa6fd5d6030e5d0812))
* remove applyModifier ([7064757](https://github.com/Akryum/v-tooltip/commit/70647574b817db0bf0e58008efa3c1291f82fb35))


### Features

* arrowOverflow prop ([0ed3801](https://github.com/Akryum/v-tooltip/commit/0ed3801863b4654ef89d438ecb2b016fe6aad9ee))
* switch to floating-ui ([e28f594](https://github.com/Akryum/v-tooltip/commit/e28f5946c83904763b222cf9f6c7b56c4720f3e2))



# [1.0.0-beta.1](https://github.com/Akryum/v-tooltip/compare/v3.0.0-beta.19...v1.0.0-beta.1) (2022-01-13)

- Renamed from `v-tooltip` to `floating-vue`
- Switched to floating-ui
