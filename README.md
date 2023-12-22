@font-face {
    font-family: 'FontAwesome';
    src: url('../fonts/fontawesome-webfont.eot?v=4.4.0');
    src: url('../fonts/fontawesome-webfont.eot?#iefix&v=4.4.0') format('embedded-opentype'), url('../fonts/fontawesome-webfont.woff2?v=4.4.0') format('woff2'), url('../fonts/fontawesome-webfont.woff?v=4.4.0') format('woff'), url('../fonts/fontawesome-webfont.ttf?v=4.4.0') format('truetype'), url('../fonts/fontawesome-webfont.svg?v=4.4.0#fontawesomeregular') format('svg');
    font-weight: normal;
    font-style: normal
}

.fa {
    display: inline-block;
    font: normal normal normal 14px/1 FontAwesome;
    font-size: inherit;
    text-rendering: auto;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.fa-lg {
    font-size: 1.33333333em;
    line-height: .75em;
    vertical-align: -15%
}

.fa-2x {
    font-size: 2em
}

.fa-3x {
    font-size: 3em
}

.fa-4x {
    font-size: 4em
}

.fa-5x {
    font-size: 5em
}

.fa-fw {
    width: 1.28571429em;
    text-align: center
}

.fa-ul {
    padding-left: 0;
    margin-left: 2.14285714em;
    list-style-type: none
}

.fa-ul > li {
    position: relative
}

.fa-li {
    position: absolute;
    left: -2.14285714em;
    width: 2.14285714em;
    top: .14285714em;
    text-align: center
}

.fa-li.fa-lg {
    left: -1.85714286em
}

.fa-border {
    padding: .2em .25em .15em;
    border: solid .08em #eee;
    border-radius: .1em
}

.fa-pull-left {
    float: left
}

.fa-pull-right {
    float: right
}

.fa.fa-pull-left {
    margin-right: .3em
}

.fa.fa-pull-right {
    margin-left: .3em
}

.pull-right {
    float: right
}

.pull-left {
    float: left
}

.fa.pull-left {
    margin-right: .3em
}

.fa.pull-right {
    margin-left: .3em
}

.fa-spin {
    -webkit-animation: fa-spin 2s infinite linear;
    animation: fa-spin 2s infinite linear
}

.fa-pulse {
    -webkit-animation: fa-spin 1s infinite steps(8);
    animation: fa-spin 1s infinite steps(8)
}

@-webkit-keyframes fa-spin {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(359deg);
        transform: rotate(359deg)
    }
}

@keyframes fa-spin {
    0% {
        -webkit-transform: rotate(0deg);
        transform: rotate(0deg)
    }

    100% {
        -webkit-transform: rotate(359deg);
        transform: rotate(359deg)
    }
}

.fa-rotate-90 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
    -webkit-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg)
}

.fa-rotate-180 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
    -webkit-transform: rotate(180deg);
    -ms-transform: rotate(180deg);
    transform: rotate(180deg)
}

.fa-rotate-270 {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
    -webkit-transform: rotate(270deg);
    -ms-transform: rotate(270deg);
    transform: rotate(270deg)
}

.fa-flip-horizontal {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
    -webkit-transform: scale(-1, 1);
    -ms-transform: scale(-1, 1);
    transform: scale(-1, 1)
}

.fa-flip-vertical {
    filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
    -webkit-transform: scale(1, -1);
    -ms-transform: scale(1, -1);
    transform: scale(1, -1)
}

:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
    filter: none
}

.fa-stack {
    position: relative;
    display: inline-block;
    width: 2em;
    height: 2em;
    line-height: 2em;
    vertical-align: middle
}

.fa-stack-1x,
.fa-stack-2x {
    position: absolute;
    left: 0;
    width: 100%;
    text-align: center
}

.fa-stack-1x {
    line-height: inherit
}

.fa-stack-2x {
    font-size: 2em
}

.fa-inverse {
    color: #fff
}

.fa-glass:before {
    content: "\f000"
}

.fa-music:before {
    content: "\f001"
}

.fa-search:before {
    content: "\f002"
}

.fa-envelope-o:before {
    content: "\f003"
}

.fa-heart:before {
    content: "\f004"
}

.fa-star:before {
    content: "\f005"
}

.fa-star-o:before {
    content: "\f006"
}

.fa-user:before {
    content: "\f007"
}

.fa-film:before {
    content: "\f008"
}

.fa-th-large:before {
    content: "\f009"
}

.fa-th:before {
    content: "\f00a"
}

.fa-th-list:before {
    content: "\f00b"
}

.fa-check:before {
    content: "\f00c"
}

.fa-remove:before,
.fa-close:before,
.fa-times:before {
    content: "\f00d"
}

.fa-search-plus:before {
    content: "\f00e"
}

.fa-search-minus:before {
    content: "\f010"
}

.fa-power-off:before {
    content: "\f011"
}

.fa-signal:before {
    content: "\f012"
}

.fa-gear:before,
.fa-cog:before {
    content: "\f013"
}

.fa-trash-o:before {
    content: "\f014"
}

.fa-home:before {
    content: "\f015"
}

.fa-file-o:before {
    content: "\f016"
}

.fa-clock-o:before {
    content: "\f017"
}

.fa-road:before {
    content: "\f018"
}

.fa-download:before {
    content: "\f019"
}

.fa-arrow-circle-o-down:before {
    content: "\f01a"
}

.fa-arrow-circle-o-up:before {
    content: "\f01b"
}

.fa-inbox:before {
    content: "\f01c"
}

.fa-play-circle-o:before {
    content: "\f01d"
}

.fa-rotate-right:before,
.fa-repeat:before {
    content: "\f01e"
}

.fa-refresh:before {
    content: "\f021"
}

.fa-list-alt:before {
    content: "\f022"
}

.fa-lock:before {
    content: "\f023"
}

.fa-flag:before {
    content: "\f024"
}

.fa-headphones:before {
    content: "\f025"
}

.fa-volume-off:before {
    content: "\f026"
}

.fa-volume-down:before {
    content: "\f027"
}

.fa-volume-up:before {
    content: "\f028"
}

.fa-qrcode:before {
    content: "\f029"
}

.fa-barcode:before {
    content: "\f02a"
}

.fa-tag:before {
    content: "\f02b"
}

.fa-tags:before {
    content: "\f02c"
}

.fa-book:before {
    content: "\f02d"
}

.fa-bookmark:before {
    content: "\f02e"
}

.fa-print:before {
    content: "\f02f"
}

.fa-camera:before {
    content: "\f030"
}

.fa-font:before {
    content: "\f031"
}

.fa-bold:before {
    content: "\f032"
}

.fa-italic:before {
    content: "\f033"
}

.fa-text-height:before {
    content: "\f034"
}

.fa-text-width:before {
    content: "\f035"
}

.fa-align-left:before {
    content: "\f036"
}

.fa-align-center:before {
    content: "\f037"
}

.fa-align-right:before {
    content: "\f038"
}

.fa-align-justify:before {
    content: "\f039"
}

.fa-list:before {
    content: "\f03a"
}

.fa-dedent:before,
.fa-outdent:before {
    content: "\f03b"
}

.fa-indent:before {
    content: "\f03c"
}

.fa-video-camera:before {
    content: "\f03d"
}

.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
    content: "\f03e"
}

.fa-pencil:before {
    content: "\f040"
}

.fa-map-marker:before {
    content: "\f041"
}

.fa-adjust:before {
    content: "\f042"
}

.fa-tint:before {
    content: "\f043"
}

.fa-edit:before,
.fa-pencil-square-o:before {
    content: "\f044"
}

.fa-share-square-o:before {
    content: "\f045"
}

.fa-check-square-o:before {
    content: "\f046"
}

.fa-arrows:before {
    content: "\f047"
}

.fa-step-backward:before {
    content: "\f048"
}

.fa-fast-backward:before {
    content: "\f049"
}

.fa-backward:before {
    content: "\f04a"
}

.fa-play:before {
    content: "\f04b"
}

.fa-pause:before {
    content: "\f04c"
}

.fa-stop:before {
    content: "\f04d"
}

.fa-forward:before {
    content: "\f04e"
}

.fa-fast-forward:before {
    content: "\f050"
}

.fa-step-forward:before {
    content: "\f051"
}

.fa-eject:before {
    content: "\f052"
}

.fa-chevron-left:before {
    content: "\f053"
}

.fa-chevron-right:before {
    content: "\f054"
}

.fa-plus-circle:before {
    content: "\f055"
}

.fa-minus-circle:before {
    content: "\f056"
}

.fa-times-circle:before {
    content: "\f057"
}

.fa-check-circle:before {
    content: "\f058"
}

.fa-question-circle:before {
    content: "\f059"
}

.fa-info-circle:before {
    content: "\f05a"
}

.fa-crosshairs:before {
    content: "\f05b"
}

.fa-times-circle-o:before {
    content: "\f05c"
}

.fa-check-circle-o:before {
    content: "\f05d"
}

.fa-ban:before {
    content: "\f05e"
}

.fa-arrow-left:before {
    content: "\f060"
}

.fa-arrow-right:before {
    content: "\f061"
}

.fa-arrow-up:before {
    content: "\f062"
}

.fa-arrow-down:before {
    content: "\f063"
}

.fa-mail-forward:before,
.fa-share:before {
    content: "\f064"
}

.fa-expand:before {
    content: "\f065"
}

.fa-compress:before {
    content: "\f066"
}

.fa-plus:before {
    content: "\f067"
}

.fa-minus:before {
    content: "\f068"
}

.fa-asterisk:before {
    content: "\f069"
}

.fa-exclamation-circle:before {
    content: "\f06a"
}

.fa-gift:before {
    content: "\f06b"
}

.fa-leaf:before {
    content: "\f06c"
}

.fa-fire:before {
    content: "\f06d"
}

.fa-eye:before {
    content: "\f06e"
}

.fa-eye-slash:before {
    content: "\f070"
}

.fa-warning:before,
.fa-exclamation-triangle:before {
    content: "\f071"
}

.fa-plane:before {
    content: "\f072"
}

.fa-calendar:before {
    content: "\f073"
}

.fa-random:before {
    content: "\f074"
}

.fa-comment:before {
    content: "\f075"
}

.fa-magnet:before {
    content: "\f076"
}

.fa-chevron-up:before {
    content: "\f077"
}

.fa-chevron-down:before {
    content: "\f078"
}

.fa-retweet:before {
    content: "\f079"
}

.fa-shopping-cart:before {
    content: "\f07a"
}

.fa-folder:before {
    content: "\f07b"
}

.fa-folder-open:before {
    content: "\f07c"
}

.fa-arrows-v:before {
    content: "\f07d"
}

.fa-arrows-h:before {
    content: "\f07e"
}

.fa-bar-chart-o:before,
.fa-bar-chart:before {
    content: "\f080"
}

.fa-twitter-square:before {
    content: "\f081"
}

.fa-facebook-square:before {
    content: "\f082"
}

.fa-camera-retro:before {
    content: "\f083"
}

.fa-key:before {
    content: "\f084"
}

.fa-gears:before,
.fa-cogs:before {
    content: "\f085"
}

.fa-comments:before {
    content: "\f086"
}

.fa-thumbs-o-up:before {
    content: "\f087"
}

.fa-thumbs-o-down:before {
    content: "\f088"
}

.fa-star-half:before {
    content: "\f089"
}

.fa-heart-o:before {
    content: "\f08a"
}

.fa-sign-out:before {
    content: "\f08b"
}

.fa-linkedin-square:before {
    content: "\f08c"
}

.fa-thumb-tack:before {
    content: "\f08d"
}

.fa-external-link:before {
    content: "\f08e"
}

.fa-sign-in:before {
    content: "\f090"
}

.fa-trophy:before {
    content: "\f091"
}

.fa-github-square:before {
    content: "\f092"
}

.fa-upload:before {
    content: "\f093"
}

.fa-lemon-o:before {
    content: "\f094"
}

.fa-phone:before {
    content: "\f095"
}

.fa-square-o:before {
    content: "\f096"
}

.fa-bookmark-o:before {
    content: "\f097"
}

.fa-phone-square:before {
    content: "\f098"
}

.fa-twitter:before {
    content: "\f099"
}

.fa-facebook-f:before,
.fa-facebook:before {
    content: "\f09a"
}

.fa-github:before {
    content: "\f09b"
}

.fa-unlock:before {
    content: "\f09c"
}

.fa-credit-card:before {
    content: "\f09d"
}

.fa-feed:before,
.fa-rss:before {
    content: "\f09e"
}

.fa-hdd-o:before {
    content: "\f0a0"
}

.fa-bullhorn:before {
    content: "\f0a1"
}

.fa-bell:before {
    content: "\f0f3"
}

.fa-certificate:before {
    content: "\f0a3"
}

.fa-hand-o-right:before {
    content: "\f0a4"
}

.fa-hand-o-left:before {
    content: "\f0a5"
}

.fa-hand-o-up:before {
    content: "\f0a6"
}

.fa-hand-o-down:before {
    content: "\f0a7"
}

.fa-arrow-circle-left:before {
    content: "\f0a8"
}

.fa-arrow-circle-right:before {
    content: "\f0a9"
}

.fa-arrow-circle-up:before {
    content: "\f0aa"
}

.fa-arrow-circle-down:before {
    content: "\f0ab"
}

.fa-globe:before {
    content: "\f0ac"
}

.fa-wrench:before {
    content: "\f0ad"
}

.fa-tasks:before {
    content: "\f0ae"
}

.fa-filter:before {
    content: "\f0b0"
}

.fa-briefcase:before {
    content: "\f0b1"
}

.fa-arrows-alt:before {
    content: "\f0b2"
}

.fa-group:before,
.fa-users:before {
    content: "\f0c0"
}

.fa-chain:before,
.fa-link:before {
    content: "\f0c1"
}

.fa-cloud:before {
    content: "\f0c2"
}

.fa-flask:before {
    content: "\f0c3"
}

.fa-cut:before,
.fa-scissors:before {
    content: "\f0c4"
}

.fa-copy:before,
.fa-files-o:before {
    content: "\f0c5"
}

.fa-paperclip:before {
    content: "\f0c6"
}

.fa-save:before,
.fa-floppy-o:before {
    content: "\f0c7"
}

.fa-square:before {
    content: "\f0c8"
}

.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
    content: "\f0c9"
}

.fa-list-ul:before {
    content: "\f0ca"
}

.fa-list-ol:before {
    content: "\f0cb"
}

.fa-strikethrough:before {
    content: "\f0cc"
}

.fa-underline:before {
    content: "\f0cd"
}

.fa-table:before {
    content: "\f0ce"
}

.fa-magic:before {
    content: "\f0d0"
}

.fa-truck:before {
    content: "\f0d1"
}

.fa-pinterest:before {
    content: "\f0d2"
}

.fa-pinterest-square:before {
    content: "\f0d3"
}

.fa-google-plus-square:before {
    content: "\f0d4"
}

.fa-google-plus:before {
    content: "\f0d5"
}

.fa-money:before {
    content: "\f0d6"
}

.fa-caret-down:before {
    content: "\f0d7"
}

.fa-caret-up:before {
    content: "\f0d8"
}

.fa-caret-left:before {
    content: "\f0d9"
}

.fa-caret-right:before {
    content: "\f0da"
}

.fa-columns:before {
    content: "\f0db"
}

.fa-unsorted:before,
.fa-sort:before {
    content: "\f0dc"
}

.fa-sort-down:before,
.fa-sort-desc:before {
    content: "\f0dd"
}

.fa-sort-up:before,
.fa-sort-asc:before {
    content: "\f0de"
}

.fa-envelope:before {
    content: "\f0e0"
}

.fa-linkedin:before {
    content: "\f0e1"
}

.fa-rotate-left:before,
.fa-undo:before {
    content: "\f0e2"
}

.fa-legal:before,
.fa-gavel:before {
    content: "\f0e3"
}

.fa-dashboard:before,
.fa-tachometer:before {
    content: "\f0e4"
}

.fa-comment-o:before {
    content: "\f0e5"
}

.fa-comments-o:before {
    content: "\f0e6"
}

.fa-flash:before,
.fa-bolt:before {
    content: "\f0e7"
}

.fa-sitemap:before {
    content: "\f0e8"
}

.fa-umbrella:before {
    content: "\f0e9"
}

.fa-paste:before,
.fa-clipboard:before {
    content: "\f0ea"
}

.fa-lightbulb-o:before {
    content: "\f0eb"
}

.fa-exchange:before {
    content: "\f0ec"
}

.fa-cloud-download:before {
    content: "\f0ed"
}

.fa-cloud-upload:before {
    content: "\f0ee"
}

.fa-user-md:before {
    content: "\f0f0"
}

.fa-stethoscope:before {
    content: "\f0f1"
}

.fa-suitcase:before {
    content: "\f0f2"
}

.fa-bell-o:before {
    content: "\f0a2"
}

.fa-coffee:before {
    content: "\f0f4"
}

.fa-cutlery:before {
    content: "\f0f5"
}

.fa-file-text-o:before {
    content: "\f0f6"
}

.fa-building-o:before {
    content: "\f0f7"
}

.fa-hospital-o:before {
    content: "\f0f8"
}

.fa-ambulance:before {
    content: "\f0f9"
}

.fa-medkit:before {
    content: "\f0fa"
}

.fa-fighter-jet:before {
    content: "\f0fb"
}

.fa-beer:before {
    content: "\f0fc"
}

.fa-h-square:before {
    content: "\f0fd"
}

.fa-plus-square:before {
    content: "\f0fe"
}

.fa-angle-double-left:before {
    content: "\f100"
}

.fa-angle-double-right:before {
    content: "\f101"
}

.fa-angle-double-up:before {
    content: "\f102"
}

.fa-angle-double-down:before {
    content: "\f103"
}

.fa-angle-left:before {
    content: "\f104"
}

.fa-angle-right:before {
    content: "\f105"
}

.fa-angle-up:before {
    content: "\f106"
}

.fa-angle-down:before {
    content: "\f107"
}

.fa-desktop:before {
    content: "\f108"
}

.fa-laptop:before {
    content: "\f109"
}

.fa-tablet:before {
    content: "\f10a"
}

.fa-mobile-phone:before,
.fa-mobile:before {
    content: "\f10b"
}

.fa-circle-o:before {
    content: "\f10c"
}

.fa-quote-left:before {
    content: "\f10d"
}

.fa-quote-right:before {
    content: "\f10e"
}

.fa-spinner:before {
    content: "\f110"
}

.fa-circle:before {
    content: "\f111"
}

.fa-mail-reply:before,
.fa-reply:before {
    content: "\f112"
}

.fa-github-alt:before {
    content: "\f113"
}

.fa-folder-o:before {
    content: "\f114"
}

.fa-folder-open-o:before {
    content: "\f115"
}

.fa-smile-o:before {
    content: "\f118"
}

.fa-frown-o:before {
    content: "\f119"
}

.fa-meh-o:before {
    content: "\f11a"
}

.fa-gamepad:before {
    content: "\f11b"
}

.fa-keyboard-o:before {
    content: "\f11c"
}

.fa-flag-o:before {
    content: "\f11d"
}

.fa-flag-checkered:before {
    content: "\f11e"
}

.fa-terminal:before {
    content: "\f120"
}

.fa-code:before {
    content: "\f121"
}

.fa-mail-reply-all:before,
.fa-reply-all:before {
    content: "\f122"
}

.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
    content: "\f123"
}

.fa-location-arrow:before {
    content: "\f124"
}

.fa-crop:before {
    content: "\f125"
}

.fa-code-fork:before {
    content: "\f126"
}

.fa-unlink:before,
.fa-chain-broken:before {
    content: "\f127"
}

.fa-question:before {
    content: "\f128"
}

.fa-info:before {
    content: "\f129"
}

.fa-exclamation:before {
    content: "\f12a"
}

.fa-superscript:before {
    content: "\f12b"
}

.fa-subscript:before {
    content: "\f12c"
}

.fa-eraser:before {
    content: "\f12d"
}

.fa-puzzle-piece:before {
    content: "\f12e"
}

.fa-microphone:before {
    content: "\f130"
}

.fa-microphone-slash:before {
    content: "\f131"
}

.fa-shield:before {
    content: "\f132"
}

.fa-calendar-o:before {
    content: "\f133"
}

.fa-fire-extinguisher:before {
    content: "\f134"
}

.fa-rocket:before {
    content: "\f135"
}

.fa-maxcdn:before {
    content: "\f136"
}

.fa-chevron-circle-left:before {
    content: "\f137"
}

.fa-chevron-circle-right:before {
    content: "\f138"
}

.fa-chevron-circle-up:before {
    content: "\f139"
}

.fa-chevron-circle-down:before {
    content: "\f13a"
}

.fa-html5:before {
    content: "\f13b"
}

.fa-css3:before {
    content: "\f13c"
}

.fa-anchor:before {
    content: "\f13d"
}

.fa-unlock-alt:before {
    content: "\f13e"
}

.fa-bullseye:before {
    content: "\f140"
}

.fa-ellipsis-h:before {
    content: "\f141"
}

.fa-ellipsis-v:before {
    content: "\f142"
}

.fa-rss-square:before {
    content: "\f143"
}

.fa-play-circle:before {
    content: "\f144"
}

.fa-ticket:before {
    content: "\f145"
}

.fa-minus-square:before {
    content: "\f146"
}

.fa-minus-square-o:before {
    content: "\f147"
}

.fa-level-up:before {
    content: "\f148"
}

.fa-level-down:before {
    content: "\f149"
}

.fa-check-square:before {
    content: "\f14a"
}

.fa-pencil-square:before {
    content: "\f14b"
}

.fa-external-link-square:before {
    content: "\f14c"
}

.fa-share-square:before {
    content: "\f14d"
}

.fa-compass:before {
    content: "\f14e"
}

.fa-toggle-down:before,
.fa-caret-square-o-down:before {
    content: "\f150"
}

.fa-toggle-up:before,
.fa-caret-square-o-up:before {
    content: "\f151"
}

.fa-toggle-right:before,
.fa-caret-square-o-right:before {
    content: "\f152"
}

.fa-euro:before,
.fa-eur:before {
    content: "\f153"
}

.fa-gbp:before {
    content: "\f154"
}

.fa-dollar:before,
.fa-usd:before {
    content: "\f155"
}

.fa-rupee:before,
.fa-inr:before {
    content: "\f156"
}

.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
    content: "\f157"
}

.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
    content: "\f158"
}

.fa-won:before,
.fa-krw:before {
    content: "\f159"
}

.fa-bitcoin:before,
.fa-btc:before {
    content: "\f15a"
}

.fa-file:before {
    content: "\f15b"
}

.fa-file-text:before {
    content: "\f15c"
}

.fa-sort-alpha-asc:before {
    content: "\f15d"
}

.fa-sort-alpha-desc:before {
    content: "\f15e"
}

.fa-sort-amount-asc:before {
    content: "\f160"
}

.fa-sort-amount-desc:before {
    content: "\f161"
}

.fa-sort-numeric-asc:before {
    content: "\f162"
}

.fa-sort-numeric-desc:before {
    content: "\f163"
}

.fa-thumbs-up:before {
    content: "\f164"
}

.fa-thumbs-down:before {
    content: "\f165"
}

.fa-youtube-square:before {
    content: "\f166"
}

.fa-youtube:before {
    content: "\f167"
}

.fa-xing:before {
    content: "\f168"
}

.fa-xing-square:before {
    content: "\f169"
}

.fa-youtube-play:before {
    content: "\f16a"
}

.fa-dropbox:before {
    content: "\f16b"
}

.fa-stack-overflow:before {
    content: "\f16c"
}

.fa-instagram:before {
    content: "\f16d"
}

.fa-flickr:before {
    content: "\f16e"
}

.fa-adn:before {
    content: "\f170"
}

.fa-bitbucket:before {
    content: "\f171"
}

.fa-bitbucket-square:before {
    content: "\f172"
}

.fa-tumblr:before {
    content: "\f173"
}

.fa-tumblr-square:before {
    content: "\f174"
}

.fa-long-arrow-down:before {
    content: "\f175"
}

.fa-long-arrow-up:before {
    content: "\f176"
}

.fa-long-arrow-left:before {
    content: "\f177"
}

.fa-long-arrow-right:before {
    content: "\f178"
}

.fa-apple:before {
    content: "\f179"
}

.fa-windows:before {
    content: "\f17a"
}

.fa-android:before {
    content: "\f17b"
}

.fa-linux:before {
    content: "\f17c"
}

.fa-dribbble:before {
    content: "\f17d"
}

.fa-skype:before {
    content: "\f17e"
}

.fa-foursquare:before {
    content: "\f180"
}

.fa-trello:before {
    content: "\f181"
}

.fa-female:before {
    content: "\f182"
}

.fa-male:before {
    content: "\f183"
}

.fa-gittip:before,
.fa-gratipay:before {
    content: "\f184"
}

.fa-sun-o:before {
    content: "\f185"
}

.fa-moon-o:before {
    content: "\f186"
}

.fa-archive:before {
    content: "\f187"
}

.fa-bug:before {
    content: "\f188"
}

.fa-vk:before {
    content: "\f189"
}

.fa-weibo:before {
    content: "\f18a"
}

.fa-renren:before {
    content: "\f18b"
}

.fa-pagelines:before {
    content: "\f18c"
}

.fa-stack-exchange:before {
    content: "\f18d"
}

.fa-arrow-circle-o-right:before {
    content: "\f18e"
}

.fa-arrow-circle-o-left:before {
    content: "\f190"
}

.fa-toggle-left:before,
.fa-caret-square-o-left:before {
    content: "\f191"
}

.fa-dot-circle-o:before {
    content: "\f192"
}

.fa-wheelchair:before {
    content: "\f193"
}

.fa-vimeo-square:before {
    content: "\f194"
}

.fa-turkish-lira:before,
.fa-try:before {
    content: "\f195"
}

.fa-plus-square-o:before {
    content: "\f196"
}

.fa-space-shuttle:before {
    content: "\f197"
}

.fa-slack:before {
    content: "\f198"
}

.fa-envelope-square:before {
    content: "\f199"
}

.fa-wordpress:before {
    content: "\f19a"
}

.fa-openid:before {
    content: "\f19b"
}

.fa-institution:before,
.fa-bank:before,
.fa-university:before {
    content: "\f19c"
}

.fa-mortar-board:before,
.fa-graduation-cap:before {
    content: "\f19d"
}

.fa-yahoo:before {
    content: "\f19e"
}

.fa-google:before {
    content: "\f1a0"
}

.fa-reddit:before {
    content: "\f1a1"
}

.fa-reddit-square:before {
    content: "\f1a2"
}

.fa-stumbleupon-circle:before {
    content: "\f1a3"
}

.fa-stumbleupon:before {
    content: "\f1a4"
}

.fa-delicious:before {
    content: "\f1a5"
}

.fa-digg:before {
    content: "\f1a6"
}

.fa-pied-piper:before {
    content: "\f1a7"
}

.fa-pied-piper-alt:before {
    content: "\f1a8"
}

.fa-drupal:before {
    content: "\f1a9"
}

.fa-joomla:before {
    content: "\f1aa"
}

.fa-language:before {
    content: "\f1ab"
}

.fa-fax:before {
    content: "\f1ac"
}

.fa-building:before {
    content: "\f1ad"
}

.fa-child:before {
    content: "\f1ae"
}

.fa-paw:before {
    content: "\f1b0"
}

.fa-spoon:before {
    content: "\f1b1"
}

.fa-cube:before {
    content: "\f1b2"
}

.fa-cubes:before {
    content: "\f1b3"
}

.fa-behance:before {
    content: "\f1b4"
}

.fa-behance-square:before {
    content: "\f1b5"
}

.fa-steam:before {
    content: "\f1b6"
}

.fa-steam-square:before {
    content: "\f1b7"
}

.fa-recycle:before {
    content: "\f1b8"
}

.fa-automobile:before,
.fa-car:before {
    content: "\f1b9"
}

.fa-cab:before,
.fa-taxi:before {
    content: "\f1ba"
}

.fa-tree:before {
    content: "\f1bb"
}

.fa-spotify:before {
    content: "\f1bc"
}

.fa-deviantart:before {
    content: "\f1bd"
}

.fa-soundcloud:before {
    content: "\f1be"
}

.fa-database:before {
    content: "\f1c0"
}

.fa-file-pdf-o:before {
    content: "\f1c1"
}

.fa-file-word-o:before {
    content: "\f1c2"
}

.fa-file-excel-o:before {
    content: "\f1c3"
}

.fa-file-powerpoint-o:before {
    content: "\f1c4"
}

.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
    content: "\f1c5"
}

.fa-file-zip-o:before,
.fa-file-archive-o:before {
    content: "\f1c6"
}

.fa-file-sound-o:before,
.fa-file-audio-o:before {
    content: "\f1c7"
}

.fa-file-movie-o:before,
.fa-file-video-o:before {
    content: "\f1c8"
}

.fa-file-code-o:before {
    content: "\f1c9"
}

.fa-vine:before {
    content: "\f1ca"
}

.fa-codepen:before {
    content: "\f1cb"
}

.fa-jsfiddle:before {
    content: "\f1cc"
}

.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
    content: "\f1cd"
}

.fa-circle-o-notch:before {
    content: "\f1ce"
}

.fa-ra:before,
.fa-rebel:before {
    content: "\f1d0"
}

.fa-ge:before,
.fa-empire:before {
    content: "\f1d1"
}

.fa-git-square:before {
    content: "\f1d2"
}

.fa-git:before {
    content: "\f1d3"
}

.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
    content: "\f1d4"
}

.fa-tencent-weibo:before {
    content: "\f1d5"
}

.fa-qq:before {
    content: "\f1d6"
}

.fa-wechat:before,
.fa-weixin:before {
    content: "\f1d7"
}

.fa-send:before,
.fa-paper-plane:before {
    content: "\f1d8"
}

.fa-send-o:before,
.fa-paper-plane-o:before {
    content: "\f1d9"
}

.fa-history:before {
    content: "\f1da"
}

.fa-circle-thin:before {
    content: "\f1db"
}

.fa-header:before {
    content: "\f1dc"
}

.fa-paragraph:before {
    content: "\f1dd"
}

.fa-sliders:before {
    content: "\f1de"
}

.fa-share-alt:before {
    content: "\f1e0"
}

.fa-share-alt-square:before {
    content: "\f1e1"
}

.fa-bomb:before {
    content: "\f1e2"
}

.fa-soccer-ball-o:before,
.fa-futbol-o:before {
    content: "\f1e3"
}

.fa-tty:before {
    content: "\f1e4"
}

.fa-binoculars:before {
    content: "\f1e5"
}

.fa-plug:before {
    content: "\f1e6"
}

.fa-slideshare:before {
    content: "\f1e7"
}

.fa-twitch:before {
    content: "\f1e8"
}

.fa-yelp:before {
    content: "\f1e9"
}

.fa-newspaper-o:before {
    content: "\f1ea"
}

.fa-wifi:before {
    content: "\f1eb"
}

.fa-calculator:before {
    content: "\f1ec"
}

.fa-paypal:before {
    content: "\f1ed"
}

.fa-google-wallet:before {
    content: "\f1ee"
}

.fa-cc-visa:before {
    content: "\f1f0"
}

.fa-cc-mastercard:before {
    content: "\f1f1"
}

.fa-cc-discover:before {
    content: "\f1f2"
}

.fa-cc-amex:before {
    content: "\f1f3"
}

.fa-cc-paypal:before {
    content: "\f1f4"
}

.fa-cc-stripe:before {
    content: "\f1f5"
}

.fa-bell-slash:before {
    content: "\f1f6"
}

.fa-bell-slash-o:before {
    content: "\f1f7"
}

.fa-trash:before {
    content: "\f1f8"
}

.fa-copyright:before {
    content: "\f1f9"
}

.fa-at:before {
    content: "\f1fa"
}

.fa-eyedropper:before {
    content: "\f1fb"
}

.fa-paint-brush:before {
    content: "\f1fc"
}

.fa-birthday-cake:before {
    content: "\f1fd"
}

.fa-area-chart:before {
    content: "\f1fe"
}

.fa-pie-chart:before {
    content: "\f200"
}

.fa-line-chart:before {
    content: "\f201"
}

.fa-lastfm:before {
    content: "\f202"
}

.fa-lastfm-square:before {
    content: "\f203"
}

.fa-toggle-off:before {
    content: "\f204"
}

.fa-toggle-on:before {
    content: "\f205"
}

.fa-bicycle:before {
    content: "\f206"
}

.fa-bus:before {
    content: "\f207"
}

.fa-ioxhost:before {
    content: "\f208"
}

.fa-angellist:before {
    content: "\f209"
}

.fa-cc:before {
    content: "\f20a"
}

.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
    content: "\f20b"
}

.fa-meanpath:before {
    content: "\f20c"
}

.fa-buysellads:before {
    content: "\f20d"
}

.fa-connectdevelop:before {
    content: "\f20e"
}

.fa-dashcube:before {
    content: "\f210"
}

.fa-forumbee:before {
    content: "\f211"
}

.fa-leanpub:before {
    content: "\f212"
}

.fa-sellsy:before {
    content: "\f213"
}

.fa-shirtsinbulk:before {
    content: "\f214"
}

.fa-simplybuilt:before {
    content: "\f215"
}

.fa-skyatlas:before {
    content: "\f216"
}

.fa-cart-plus:before {
    content: "\f217"
}

.fa-cart-arrow-down:before {
    content: "\f218"
}

.fa-diamond:before {
    content: "\f219"
}

.fa-ship:before {
    content: "\f21a"
}

.fa-user-secret:before {
    content: "\f21b"
}

.fa-motorcycle:before {
    content: "\f21c"
}

.fa-street-view:before {
    content: "\f21d"
}

.fa-heartbeat:before {
    content: "\f21e"
}

.fa-venus:before {
    content: "\f221"
}

.fa-mars:before {
    content: "\f222"
}

.fa-mercury:before {
    content: "\f223"
}

.fa-intersex:before,
.fa-transgender:before {
    content: "\f224"
}

.fa-transgender-alt:before {
    content: "\f225"
}

.fa-venus-double:before {
    content: "\f226"
}

.fa-mars-double:before {
    content: "\f227"
}

.fa-venus-mars:before {
    content: "\f228"
}

.fa-mars-stroke:before {
    content: "\f229"
}

.fa-mars-stroke-v:before {
    content: "\f22a"
}

.fa-mars-stroke-h:before {
    content: "\f22b"
}

.fa-neuter:before {
    content: "\f22c"
}

.fa-genderless:before {
    content: "\f22d"
}

.fa-facebook-official:before {
    content: "\f230"
}

.fa-pinterest-p:before {
    content: "\f231"
}

.fa-whatsapp:before {
    content: "\f232"
}

.fa-server:before {
    content: "\f233"
}

.fa-user-plus:before {
    content: "\f234"
}

.fa-user-times:before {
    content: "\f235"
}

.fa-hotel:before,
.fa-bed:before {
    content: "\f236"
}

.fa-viacoin:before {
    content: "\f237"
}

.fa-train:before {
    content: "\f238"
}

.fa-subway:before {
    content: "\f239"
}

.fa-medium:before {
    content: "\f23a"
}

.fa-yc:before,
.fa-y-combinator:before {
    content: "\f23b"
}

.fa-optin-monster:before {
    content: "\f23c"
}

.fa-opencart:before {
    content: "\f23d"
}

.fa-expeditedssl:before {
    content: "\f23e"
}

.fa-battery-4:before,
.fa-battery-full:before {
    content: "\f240"
}

.fa-battery-3:before,
.fa-battery-three-quarters:before {
    content: "\f241"
}

.fa-battery-2:before,
.fa-battery-half:before {
    content: "\f242"
}

.fa-battery-1:before,
.fa-battery-quarter:before {
    content: "\f243"
}

.fa-battery-0:before,
.fa-battery-empty:before {
    content: "\f244"
}

.fa-mouse-pointer:before {
    content: "\f245"
}

.fa-i-cursor:before {
    content: "\f246"
}

.fa-object-group:before {
    content: "\f247"
}

.fa-object-ungroup:before {
    content: "\f248"
}

.fa-sticky-note:before {
    content: "\f249"
}

.fa-sticky-note-o:before {
    content: "\f24a"
}

.fa-cc-jcb:before {
    content: "\f24b"
}

.fa-cc-diners-club:before {
    content: "\f24c"
}

.fa-clone:before {
    content: "\f24d"
}

.fa-balance-scale:before {
    content: "\f24e"
}

.fa-hourglass-o:before {
    content: "\f250"
}

.fa-hourglass-1:before,
.fa-hourglass-start:before {
    content: "\f251"
}

.fa-hourglass-2:before,
.fa-hourglass-half:before {
    content: "\f252"
}

.fa-hourglass-3:before,
.fa-hourglass-end:before {
    content: "\f253"
}

.fa-hourglass:before {
    content: "\f254"
}

.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
    content: "\f255"
}

.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
    content: "\f256"
}

.fa-hand-scissors-o:before {
    content: "\f257"
}

.fa-hand-lizard-o:before {
    content: "\f258"
}

.fa-hand-spock-o:before {
    content: "\f259"
}

.fa-hand-pointer-o:before {
    content: "\f25a"
}

.fa-hand-peace-o:before {
    content: "\f25b"
}

.fa-trademark:before {
    content: "\f25c"
}

.fa-registered:before {
    content: "\f25d"
}

.fa-creative-commons:before {
    content: "\f25e"
}

.fa-gg:before {
    content: "\f260"
}

.fa-gg-circle:before {
    content: "\f261"
}

.fa-tripadvisor:before {
    content: "\f262"
}

.fa-odnoklassniki:before {
    content: "\f263"
}

.fa-odnoklassniki-square:before {
    content: "\f264"
}

.fa-get-pocket:before {
    content: "\f265"
}

.fa-wikipedia-w:before {
    content: "\f266"
}

.fa-safari:before {
    content: "\f267"
}

.fa-chrome:before {
    content: "\f268"
}

.fa-firefox:before {
    content: "\f269"
}

.fa-opera:before {
    content: "\f26a"
}

.fa-internet-explorer:before {
    content: "\f26b"
}

.fa-tv:before,
.fa-television:before {
    content: "\f26c"
}

.fa-contao:before {
    content: "\f26d"
}

.fa-500px:before {
    content: "\f26e"
}

.fa-amazon:before {
    content: "\f270"
}

.fa-calendar-plus-o:before {
    content: "\f271"
}

.fa-calendar-minus-o:before {
    content: "\f272"
}

.fa-calendar-times-o:before {
    content: "\f273"
}

.fa-calendar-check-o:before {
    content: "\f274"
}

.fa-industry:before {
    content: "\f275"
}

.fa-map-pin:before {
    content: "\f276"
}

.fa-map-signs:before {
    content: "\f277"
}

.fa-map-o:before {
    content: "\f278"
}

.fa-map:before {
    content: "\f279"
}

.fa-commenting:before {
    content: "\f27a"
}

.fa-commenting-o:before {
    content: "\f27b"
}

.fa-houzz:before {
    content: "\f27c"
}

.fa-vimeo:before {
    content: "\f27d"
}

.fa-black-tie:before {
    content: "\f27e"
}

.fa-fonticons:before {
    content: "\f280"
}



	body {
		-ms-behavior: url("assets/js/backgroundsize.min.htc");
	}



	h1.major, h2.major, h3.major, h4.major, h5.major, h6.major {
		border-bottom: solid 2px #ffffff;
	}

	blockquote {
		border-left: solid 4px #ffffff;
	}

	code {
		border: solid 2px #ffffff;
	}

	hr {
		border-bottom: solid 2px #ffffff;
	}



	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		position: relative;
		-ms-behavior: url("assets/js/ie/PIE.htc");
		border: solid 2px #ffffff;
	}

		input[type="submit"].special,
		input[type="reset"].special,
		input[type="button"].special,
		button.special,
		.button.special {
			border: 0;
		}



	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	select,
	textarea {
		position: relative;
		-ms-behavior: url("assets/js/ie/PIE.htc");
		background: transparent;
		border: solid 2px #ffffff;
	}



	table tbody tr {
		border: solid 1px #ffffff;
		border-left: 0;
		border-right: 0;
	}

	table.alt tbody tr td {
		border: solid 1px #ffffff;
		border-left-width: 0;
		border-top-width: 0;
	}

		table.alt tbody tr td:first-child {
			border-left-width: 1px;
		}

	table.alt tbody tr:first-child td {
		border-top-width: 1px;
	}

	table.alt thead {
		border-bottom: 0;
	}

	table.alt tfoot {
		border-top: 0;
	}



	.features article {
		-ms-behavior: url("assets/js/ie/PIE.htc");
		position: relative;
		width: 44%;
	}

		.features article .image {
			margin-top: 0;
			margin-left: 0;
			width: 100%;
		}



	#menu {
		background: #2e3141;
	}

		#menu h2 {
			border-bottom: solid 2px #ffffff;
		}



	#header {
		background-color: #353849;
	}



	.wrapper {
		margin: 0;
	}

		.wrapper:before, .wrapper:after {
			display: none;
		}

		.wrapper.spotlight .image {
			-ms-behavior: url("assets/js/ie/PIE.htc");
		}

			.wrapper.spotlight .image img {
				position: relative;
				-ms-behavior: url("assets/js/ie/PIE.htc");
			}



	#banner .logo .icon {
		border: solid 2px #ffffff;
		-ms-behavior: url("assets/js/ie/PIE.htc");
	}

	#banner h2 {
		border-bottom: solid 2px #ffffff;
	}



	#footer .inner .copyright {
		border-top: solid 2px #ffffff;
	}

		#footer .inner .copyright li {
			border-left: solid 2px #ffffff;
		}

  

	body {
		background-color: #2e3141;
		background-image: url("../../images/bg.jpg");
		background-size: cover;
		background-attachment: fixed;
		background-position: center;
	}

		body:before {
			background: rgba(46, 49, 65, 0.8);
			content: '';
			display: block;
			height: 100%;
			left: 0;
			position: fixed;
			top: 0;
			width: 100%;
		}

		body > * {
			position: relative;
			z-index: 1;
		}



	.features article {
		display: inline-block;
		width: 45%;
	}



	#menu .inner {
		margin: 4em auto;
	}



	#wrapper > header {
		background: none !important;
	}

	.wrapper.spotlight .inner {
		text-align: left !important;
	}

	.wrapper.spotlight .image {
		display: inline-block;
		margin: 0 3em 2em 0 !important;
		vertical-align: middle;
		width: 24%;
	}

	.wrapper.spotlight .content {
		display: inline-block;
		vertical-align: middle;
		width: 70%;
	}



	#banner {
		background: none !important;
	}



	#footer {
		background: none !important;
	}

		#footer .inner form {
			display: inline-block;
			width: 45%;
		}

		#footer .inner .contact {
			display: inline-block;
			width: 45%;
		}

  @import url(font-awesome.min.css);
@import url("https://fonts.googleapis.com/css?family=Raleway:200,700|Source+Sans+Pro:300,600,300italic,600italic");


	html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
		margin: 0;
		padding: 0;
		border: 0;
		font-size: 100%;
		font: inherit;
		vertical-align: baseline;
	}

	article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
		display: block;
	}

	body {
		line-height: 1;
	}

	ol, ul {
		list-style: none;
	}

	blockquote, q {
		quotes: none;
	}

	blockquote:before, blockquote:after, q:before, q:after {
		content: '';
		content: none;
	}

	table {
		border-collapse: collapse;
		border-spacing: 0;
	}

	body {
		-webkit-text-size-adjust: none;
	}



	*, *:before, *:after {
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}



	.row {
		border-bottom: solid 1px transparent;
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

	.row > * {
		float: left;
		-moz-box-sizing: border-box;
		-webkit-box-sizing: border-box;
		box-sizing: border-box;
	}

	.row:after, .row:before {
		content: '';
		display: block;
		clear: both;
		height: 0;
	}

	.row.uniform > * > :first-child {
		margin-top: 0;
	}

	.row.uniform > * > :last-child {
		margin-bottom: 0;
	}

	.row.\30 \25 > * {
		padding: 0 0 0 0em;
	}

	.row.\30 \25 {
		margin: 0 0 -1px 0em;
	}

	.row.uniform.\30 \25 > * {
		padding: 0em 0 0 0em;
	}

	.row.uniform.\30 \25 {
		margin: 0em 0 -1px 0em;
	}

	.row > * {
		padding: 0 0 0 1.75em;
	}

	.row {
		margin: 0 0 -1px -1.75em;
	}

	.row.uniform > * {
		padding: 1.75em 0 0 1.75em;
	}

	.row.uniform {
		margin: -1.75em 0 -1px -1.75em;
	}

	.row.\32 00\25 > * {
		padding: 0 0 0 3.5em;
	}

	.row.\32 00\25 {
		margin: 0 0 -1px -3.5em;
	}

	.row.uniform.\32 00\25 > * {
		padding: 3.5em 0 0 3.5em;
	}

	.row.uniform.\32 00\25 {
		margin: -3.5em 0 -1px -3.5em;
	}

	.row.\31 50\25 > * {
		padding: 0 0 0 2.625em;
	}

	.row.\31 50\25 {
		margin: 0 0 -1px -2.625em;
	}

	.row.uniform.\31 50\25 > * {
		padding: 2.625em 0 0 2.625em;
	}

	.row.uniform.\31 50\25 {
		margin: -2.625em 0 -1px -2.625em;
	}

	.row.\35 0\25 > * {
		padding: 0 0 0 0.875em;
	}

	.row.\35 0\25 {
		margin: 0 0 -1px -0.875em;
	}

	.row.uniform.\35 0\25 > * {
		padding: 0.875em 0 0 0.875em;
	}

	.row.uniform.\35 0\25 {
		margin: -0.875em 0 -1px -0.875em;
	}

	.row.\32 5\25 > * {
		padding: 0 0 0 0.4375em;
	}

	.row.\32 5\25 {
		margin: 0 0 -1px -0.4375em;
	}

	.row.uniform.\32 5\25 > * {
		padding: 0.4375em 0 0 0.4375em;
	}

	.row.uniform.\32 5\25 {
		margin: -0.4375em 0 -1px -0.4375em;
	}

	.\31 2u, .\31 2u\24 {
		width: 100%;
		clear: none;
		margin-left: 0;
	}

	.\31 1u, .\31 1u\24 {
		width: 91.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\31 0u, .\31 0u\24 {
		width: 83.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\39 u, .\39 u\24 {
		width: 75%;
		clear: none;
		margin-left: 0;
	}

	.\38 u, .\38 u\24 {
		width: 66.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\37 u, .\37 u\24 {
		width: 58.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\36 u, .\36 u\24 {
		width: 50%;
		clear: none;
		margin-left: 0;
	}

	.\35 u, .\35 u\24 {
		width: 41.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\34 u, .\34 u\24 {
		width: 33.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\33 u, .\33 u\24 {
		width: 25%;
		clear: none;
		margin-left: 0;
	}

	.\32 u, .\32 u\24 {
		width: 16.6666666667%;
		clear: none;
		margin-left: 0;
	}

	.\31 u, .\31 u\24 {
		width: 8.3333333333%;
		clear: none;
		margin-left: 0;
	}

	.\31 2u\24 + *,
	.\31 1u\24 + *,
	.\31 0u\24 + *,
	.\39 u\24 + *,
	.\38 u\24 + *,
	.\37 u\24 + *,
	.\36 u\24 + *,
	.\35 u\24 + *,
	.\34 u\24 + *,
	.\33 u\24 + *,
	.\32 u\24 + *,
	.\31 u\24 + * {
		clear: left;
	}

	.\-11u {
		margin-left: 91.66667%;
	}

	.\-10u {
		margin-left: 83.33333%;
	}

	.\-9u {
		margin-left: 75%;
	}

	.\-8u {
		margin-left: 66.66667%;
	}

	.\-7u {
		margin-left: 58.33333%;
	}

	.\-6u {
		margin-left: 50%;
	}

	.\-5u {
		margin-left: 41.66667%;
	}

	.\-4u {
		margin-left: 33.33333%;
	}

	.\-3u {
		margin-left: 25%;
	}

	.\-2u {
		margin-left: 16.66667%;
	}

	.\-1u {
		margin-left: 8.33333%;
	}

	@media screen and (max-width: 1680px) {

		.row > * {
			padding: 0 0 0 1.75em;
		}

		.row {
			margin: 0 0 -1px -1.75em;
		}

		.row.uniform > * {
			padding: 1.75em 0 0 1.75em;
		}

		.row.uniform {
			margin: -1.75em 0 -1px -1.75em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 3.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -3.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 3.5em 0 0 3.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -3.5em 0 -1px -3.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 2.625em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -2.625em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 2.625em 0 0 2.625em;
		}

		.row.uniform.\31 50\25 {
			margin: -2.625em 0 -1px -2.625em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.875em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.875em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.875em 0 0 0.875em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.875em 0 -1px -0.875em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.4375em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.4375em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.4375em 0 0 0.4375em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.4375em 0 -1px -0.4375em;
		}

		.\31 2u\28xlarge\29, .\31 2u\24\28xlarge\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28xlarge\29, .\31 1u\24\28xlarge\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28xlarge\29, .\31 0u\24\28xlarge\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28xlarge\29, .\39 u\24\28xlarge\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28xlarge\29, .\38 u\24\28xlarge\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28xlarge\29, .\37 u\24\28xlarge\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28xlarge\29, .\36 u\24\28xlarge\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28xlarge\29, .\35 u\24\28xlarge\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28xlarge\29, .\34 u\24\28xlarge\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28xlarge\29, .\33 u\24\28xlarge\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28xlarge\29, .\32 u\24\28xlarge\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28xlarge\29, .\31 u\24\28xlarge\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28xlarge\29 + *,
		.\31 1u\24\28xlarge\29 + *,
		.\31 0u\24\28xlarge\29 + *,
		.\39 u\24\28xlarge\29 + *,
		.\38 u\24\28xlarge\29 + *,
		.\37 u\24\28xlarge\29 + *,
		.\36 u\24\28xlarge\29 + *,
		.\35 u\24\28xlarge\29 + *,
		.\34 u\24\28xlarge\29 + *,
		.\33 u\24\28xlarge\29 + *,
		.\32 u\24\28xlarge\29 + *,
		.\31 u\24\28xlarge\29 + * {
			clear: left;
		}

		.\-11u\28xlarge\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28xlarge\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28xlarge\29 {
			margin-left: 75%;
		}

		.\-8u\28xlarge\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28xlarge\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28xlarge\29 {
			margin-left: 50%;
		}

		.\-5u\28xlarge\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28xlarge\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28xlarge\29 {
			margin-left: 25%;
		}

		.\-2u\28xlarge\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28xlarge\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 1280px) {

		.row > * {
			padding: 0 0 0 1.75em;
		}

		.row {
			margin: 0 0 -1px -1.75em;
		}

		.row.uniform > * {
			padding: 1.75em 0 0 1.75em;
		}

		.row.uniform {
			margin: -1.75em 0 -1px -1.75em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 3.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -3.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 3.5em 0 0 3.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -3.5em 0 -1px -3.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 2.625em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -2.625em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 2.625em 0 0 2.625em;
		}

		.row.uniform.\31 50\25 {
			margin: -2.625em 0 -1px -2.625em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.875em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.875em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.875em 0 0 0.875em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.875em 0 -1px -0.875em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.4375em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.4375em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.4375em 0 0 0.4375em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.4375em 0 -1px -0.4375em;
		}

		.\31 2u\28large\29, .\31 2u\24\28large\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28large\29, .\31 1u\24\28large\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28large\29, .\31 0u\24\28large\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28large\29, .\39 u\24\28large\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28large\29, .\38 u\24\28large\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28large\29, .\37 u\24\28large\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28large\29, .\36 u\24\28large\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28large\29, .\35 u\24\28large\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28large\29, .\34 u\24\28large\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28large\29, .\33 u\24\28large\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28large\29, .\32 u\24\28large\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28large\29, .\31 u\24\28large\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28large\29 + *,
		.\31 1u\24\28large\29 + *,
		.\31 0u\24\28large\29 + *,
		.\39 u\24\28large\29 + *,
		.\38 u\24\28large\29 + *,
		.\37 u\24\28large\29 + *,
		.\36 u\24\28large\29 + *,
		.\35 u\24\28large\29 + *,
		.\34 u\24\28large\29 + *,
		.\33 u\24\28large\29 + *,
		.\32 u\24\28large\29 + *,
		.\31 u\24\28large\29 + * {
			clear: left;
		}

		.\-11u\28large\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28large\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28large\29 {
			margin-left: 75%;
		}

		.\-8u\28large\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28large\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28large\29 {
			margin-left: 50%;
		}

		.\-5u\28large\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28large\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28large\29 {
			margin-left: 25%;
		}

		.\-2u\28large\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28large\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 980px) {

		.row > * {
			padding: 0 0 0 1.75em;
		}

		.row {
			margin: 0 0 -1px -1.75em;
		}

		.row.uniform > * {
			padding: 1.75em 0 0 1.75em;
		}

		.row.uniform {
			margin: -1.75em 0 -1px -1.75em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 3.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -3.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 3.5em 0 0 3.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -3.5em 0 -1px -3.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 2.625em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -2.625em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 2.625em 0 0 2.625em;
		}

		.row.uniform.\31 50\25 {
			margin: -2.625em 0 -1px -2.625em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.875em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.875em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.875em 0 0 0.875em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.875em 0 -1px -0.875em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.4375em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.4375em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.4375em 0 0 0.4375em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.4375em 0 -1px -0.4375em;
		}

		.\31 2u\28medium\29, .\31 2u\24\28medium\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28medium\29, .\31 1u\24\28medium\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28medium\29, .\31 0u\24\28medium\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28medium\29, .\39 u\24\28medium\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28medium\29, .\38 u\24\28medium\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28medium\29, .\37 u\24\28medium\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28medium\29, .\36 u\24\28medium\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28medium\29, .\35 u\24\28medium\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28medium\29, .\34 u\24\28medium\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28medium\29, .\33 u\24\28medium\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28medium\29, .\32 u\24\28medium\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28medium\29, .\31 u\24\28medium\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28medium\29 + *,
		.\31 1u\24\28medium\29 + *,
		.\31 0u\24\28medium\29 + *,
		.\39 u\24\28medium\29 + *,
		.\38 u\24\28medium\29 + *,
		.\37 u\24\28medium\29 + *,
		.\36 u\24\28medium\29 + *,
		.\35 u\24\28medium\29 + *,
		.\34 u\24\28medium\29 + *,
		.\33 u\24\28medium\29 + *,
		.\32 u\24\28medium\29 + *,
		.\31 u\24\28medium\29 + * {
			clear: left;
		}

		.\-11u\28medium\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28medium\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28medium\29 {
			margin-left: 75%;
		}

		.\-8u\28medium\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28medium\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28medium\29 {
			margin-left: 50%;
		}

		.\-5u\28medium\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28medium\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28medium\29 {
			margin-left: 25%;
		}

		.\-2u\28medium\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28medium\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 736px) {

		.row > * {
			padding: 0 0 0 1.25em;
		}

		.row {
			margin: 0 0 -1px -1.25em;
		}

		.row.uniform > * {
			padding: 1.25em 0 0 1.25em;
		}

		.row.uniform {
			margin: -1.25em 0 -1px -1.25em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 2.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -2.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 2.5em 0 0 2.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -2.5em 0 -1px -2.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 1.875em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -1.875em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 1.875em 0 0 1.875em;
		}

		.row.uniform.\31 50\25 {
			margin: -1.875em 0 -1px -1.875em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.625em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.625em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.625em 0 0 0.625em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.625em 0 -1px -0.625em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.3125em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.3125em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.3125em 0 0 0.3125em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.3125em 0 -1px -0.3125em;
		}

		.\31 2u\28small\29, .\31 2u\24\28small\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28small\29, .\31 1u\24\28small\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28small\29, .\31 0u\24\28small\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28small\29, .\39 u\24\28small\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28small\29, .\38 u\24\28small\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28small\29, .\37 u\24\28small\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28small\29, .\36 u\24\28small\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28small\29, .\35 u\24\28small\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28small\29, .\34 u\24\28small\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28small\29, .\33 u\24\28small\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28small\29, .\32 u\24\28small\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28small\29, .\31 u\24\28small\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28small\29 + *,
		.\31 1u\24\28small\29 + *,
		.\31 0u\24\28small\29 + *,
		.\39 u\24\28small\29 + *,
		.\38 u\24\28small\29 + *,
		.\37 u\24\28small\29 + *,
		.\36 u\24\28small\29 + *,
		.\35 u\24\28small\29 + *,
		.\34 u\24\28small\29 + *,
		.\33 u\24\28small\29 + *,
		.\32 u\24\28small\29 + *,
		.\31 u\24\28small\29 + * {
			clear: left;
		}

		.\-11u\28small\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28small\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28small\29 {
			margin-left: 75%;
		}

		.\-8u\28small\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28small\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28small\29 {
			margin-left: 50%;
		}

		.\-5u\28small\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28small\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28small\29 {
			margin-left: 25%;
		}

		.\-2u\28small\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28small\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 640px) {

		.row > * {
			padding: 0 0 0 1.25em;
		}

		.row {
			margin: 0 0 -1px -1.25em;
		}

		.row.uniform > * {
			padding: 1.25em 0 0 1.25em;
		}

		.row.uniform {
			margin: -1.25em 0 -1px -1.25em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 2.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -2.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 2.5em 0 0 2.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -2.5em 0 -1px -2.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 1.875em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -1.875em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 1.875em 0 0 1.875em;
		}

		.row.uniform.\31 50\25 {
			margin: -1.875em 0 -1px -1.875em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.625em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.625em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.625em 0 0 0.625em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.625em 0 -1px -0.625em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.3125em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.3125em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.3125em 0 0 0.3125em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.3125em 0 -1px -0.3125em;
		}

		.\31 2u\28xsmall\29, .\31 2u\24\28xsmall\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28xsmall\29, .\31 1u\24\28xsmall\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28xsmall\29, .\31 0u\24\28xsmall\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28xsmall\29, .\39 u\24\28xsmall\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28xsmall\29, .\38 u\24\28xsmall\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28xsmall\29, .\37 u\24\28xsmall\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28xsmall\29, .\36 u\24\28xsmall\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28xsmall\29, .\35 u\24\28xsmall\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28xsmall\29, .\34 u\24\28xsmall\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28xsmall\29, .\33 u\24\28xsmall\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28xsmall\29, .\32 u\24\28xsmall\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28xsmall\29, .\31 u\24\28xsmall\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28xsmall\29 + *,
		.\31 1u\24\28xsmall\29 + *,
		.\31 0u\24\28xsmall\29 + *,
		.\39 u\24\28xsmall\29 + *,
		.\38 u\24\28xsmall\29 + *,
		.\37 u\24\28xsmall\29 + *,
		.\36 u\24\28xsmall\29 + *,
		.\35 u\24\28xsmall\29 + *,
		.\34 u\24\28xsmall\29 + *,
		.\33 u\24\28xsmall\29 + *,
		.\32 u\24\28xsmall\29 + *,
		.\31 u\24\28xsmall\29 + * {
			clear: left;
		}

		.\-11u\28xsmall\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28xsmall\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28xsmall\29 {
			margin-left: 75%;
		}

		.\-8u\28xsmall\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28xsmall\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28xsmall\29 {
			margin-left: 50%;
		}

		.\-5u\28xsmall\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28xsmall\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28xsmall\29 {
			margin-left: 25%;
		}

		.\-2u\28xsmall\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28xsmall\29 {
			margin-left: 8.33333%;
		}

	}

	@media screen and (max-width: 360px) {

		.row > * {
			padding: 0 0 0 1.25em;
		}

		.row {
			margin: 0 0 -1px -1.25em;
		}

		.row.uniform > * {
			padding: 1.25em 0 0 1.25em;
		}

		.row.uniform {
			margin: -1.25em 0 -1px -1.25em;
		}

		.row.\32 00\25 > * {
			padding: 0 0 0 2.5em;
		}

		.row.\32 00\25 {
			margin: 0 0 -1px -2.5em;
		}

		.row.uniform.\32 00\25 > * {
			padding: 2.5em 0 0 2.5em;
		}

		.row.uniform.\32 00\25 {
			margin: -2.5em 0 -1px -2.5em;
		}

		.row.\31 50\25 > * {
			padding: 0 0 0 1.875em;
		}

		.row.\31 50\25 {
			margin: 0 0 -1px -1.875em;
		}

		.row.uniform.\31 50\25 > * {
			padding: 1.875em 0 0 1.875em;
		}

		.row.uniform.\31 50\25 {
			margin: -1.875em 0 -1px -1.875em;
		}

		.row.\35 0\25 > * {
			padding: 0 0 0 0.625em;
		}

		.row.\35 0\25 {
			margin: 0 0 -1px -0.625em;
		}

		.row.uniform.\35 0\25 > * {
			padding: 0.625em 0 0 0.625em;
		}

		.row.uniform.\35 0\25 {
			margin: -0.625em 0 -1px -0.625em;
		}

		.row.\32 5\25 > * {
			padding: 0 0 0 0.3125em;
		}

		.row.\32 5\25 {
			margin: 0 0 -1px -0.3125em;
		}

		.row.uniform.\32 5\25 > * {
			padding: 0.3125em 0 0 0.3125em;
		}

		.row.uniform.\32 5\25 {
			margin: -0.3125em 0 -1px -0.3125em;
		}

		.\31 2u\28xxsmall\29, .\31 2u\24\28xxsmall\29 {
			width: 100%;
			clear: none;
			margin-left: 0;
		}

		.\31 1u\28xxsmall\29, .\31 1u\24\28xxsmall\29 {
			width: 91.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 0u\28xxsmall\29, .\31 0u\24\28xxsmall\29 {
			width: 83.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\39 u\28xxsmall\29, .\39 u\24\28xxsmall\29 {
			width: 75%;
			clear: none;
			margin-left: 0;
		}

		.\38 u\28xxsmall\29, .\38 u\24\28xxsmall\29 {
			width: 66.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\37 u\28xxsmall\29, .\37 u\24\28xxsmall\29 {
			width: 58.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\36 u\28xxsmall\29, .\36 u\24\28xxsmall\29 {
			width: 50%;
			clear: none;
			margin-left: 0;
		}

		.\35 u\28xxsmall\29, .\35 u\24\28xxsmall\29 {
			width: 41.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\34 u\28xxsmall\29, .\34 u\24\28xxsmall\29 {
			width: 33.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\33 u\28xxsmall\29, .\33 u\24\28xxsmall\29 {
			width: 25%;
			clear: none;
			margin-left: 0;
		}

		.\32 u\28xxsmall\29, .\32 u\24\28xxsmall\29 {
			width: 16.6666666667%;
			clear: none;
			margin-left: 0;
		}

		.\31 u\28xxsmall\29, .\31 u\24\28xxsmall\29 {
			width: 8.3333333333%;
			clear: none;
			margin-left: 0;
		}

		.\31 2u\24\28xxsmall\29 + *,
		.\31 1u\24\28xxsmall\29 + *,
		.\31 0u\24\28xxsmall\29 + *,
		.\39 u\24\28xxsmall\29 + *,
		.\38 u\24\28xxsmall\29 + *,
		.\37 u\24\28xxsmall\29 + *,
		.\36 u\24\28xxsmall\29 + *,
		.\35 u\24\28xxsmall\29 + *,
		.\34 u\24\28xxsmall\29 + *,
		.\33 u\24\28xxsmall\29 + *,
		.\32 u\24\28xxsmall\29 + *,
		.\31 u\24\28xxsmall\29 + * {
			clear: left;
		}

		.\-11u\28xxsmall\29 {
			margin-left: 91.66667%;
		}

		.\-10u\28xxsmall\29 {
			margin-left: 83.33333%;
		}

		.\-9u\28xxsmall\29 {
			margin-left: 75%;
		}

		.\-8u\28xxsmall\29 {
			margin-left: 66.66667%;
		}

		.\-7u\28xxsmall\29 {
			margin-left: 58.33333%;
		}

		.\-6u\28xxsmall\29 {
			margin-left: 50%;
		}

		.\-5u\28xxsmall\29 {
			margin-left: 41.66667%;
		}

		.\-4u\28xxsmall\29 {
			margin-left: 33.33333%;
		}

		.\-3u\28xxsmall\29 {
			margin-left: 25%;
		}

		.\-2u\28xxsmall\29 {
			margin-left: 16.66667%;
		}

		.\-1u\28xxsmall\29 {
			margin-left: 8.33333%;
		}

	}



	@-ms-viewport {
		width: device-width;
	}

	body {
		-ms-overflow-style: scrollbar;
	}

	@media screen and (max-width: 640px) {

		html, body {
			min-width: 320px;
		}

	}

	body {
		background-color: #2e3141;
		background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
		background-size: auto, cover;
		background-attachment: fixed, fixed;
		background-position: center, center;
	}

		body.is-loading *, body.is-loading *:before, body.is-loading *:after {
			-moz-animation: none !important;
			-webkit-animation: none !important;
			-ms-animation: none !important;
			animation: none !important;
			-moz-transition: none !important;
			-webkit-transition: none !important;
			-ms-transition: none !important;
			transition: none !important;
		}



	body, input, select, textarea {
		color: #ffffff;
		font-family: "Source Sans Pro", Helvetica, sans-serif;
		font-size: 16.5pt;
		font-weight: 300;
		line-height: 1.65;
	}

		@media screen and (max-width: 1680px) {

			body, input, select, textarea {
				font-size: 13pt;
			}

		}

		@media screen and (max-width: 1280px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 980px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 736px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

		@media screen and (max-width: 640px) {

			body, input, select, textarea {
				font-size: 12pt;
			}

		}

	a {
		-moz-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-webkit-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		-ms-transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		transition: color 0.2s ease-in-out, border-bottom-color 0.2s ease-in-out;
		border-bottom: dotted 1px rgba(255, 255, 255, 0.35);
		color: #ffffff;
		text-decoration: none;
	}

		a:hover {
			border-bottom-color: transparent;
			color: #ffffff !important;
		}

		a.special:not(.button) {
			text-decoration: none;
			border-bottom: 0;
			display: block;
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 0.8em;
			font-weight: 700;
			letter-spacing: 0.1em;
			margin: 0 0 2em 0;
			text-transform: uppercase;
		}

			a.special:not(.button):before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				font-family: FontAwesome;
				font-style: normal;
				font-weight: normal;
				text-transform: none !important;
			}

			a.special:not(.button):before {
				-moz-transition: background-color 0.2s ease-in-out;
				-webkit-transition: background-color 0.2s ease-in-out;
				-ms-transition: background-color 0.2s ease-in-out;
				transition: background-color 0.2s ease-in-out;
				border-radius: 100%;
				border: solid 2px rgba(255, 255, 255, 0.125);
				content: '\f105';
				display: inline-block;
				font-size: 1.25em;
				height: 2em;
				line-height: 1.65em;
				margin-right: 0.85em;
				text-align: center;
				text-indent: 0.15em;
				vertical-align: middle;
				width: 2em;
			}

			a.special:not(.button):hover:before {
				background-color: rgba(255, 255, 255, 0.025);
			}

			a.special:not(.button):active:before {
				background-color: rgba(255, 255, 255, 0.075);
			}

	strong, b {
		color: #ffffff;
		font-weight: 600;
	}

	em, i {
		font-style: italic;
	}

	p {
		margin: 0 0 2em 0;
	}

	h1, h2, h3, h4, h5, h6 {
		color: #ffffff;
		font-family: Raleway, Helvetica, sans-serif;
		font-weight: 700;
		letter-spacing: 0.1em;
		margin: 0 0 1em 0;
		text-transform: uppercase;
	}

		h1 a, h2 a, h3 a, h4 a, h5 a, h6 a {
			color: inherit;
			text-decoration: none;
		}

		h1 span, h2 span, h3 span, h4 span, h5 span, h6 span {
			font-weight: 200;
		}

		h1.major, h2.major, h3.major, h4.major, h5.major, h6.major {
			padding-bottom: 1em;
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		}

	h2 {
		font-size: 1.2em;
	}

	h3 {
		font-size: 0.9em;
	}

	h4 {
		font-size: 0.7em;
	}

	h5 {
		font-size: 0.7em;
	}

	h6 {
		font-size: 0.7em;
	}

	@media screen and (max-width: 736px) {

		h2 {
			font-size: 1em;
		}

		h3 {
			font-size: 0.8em;
		}

	}

	sub {
		font-size: 0.8em;
		position: relative;
		top: 0.5em;
	}

	sup {
		font-size: 0.8em;
		position: relative;
		top: -0.5em;
	}

	blockquote {
		border-left: solid 4px rgba(255, 255, 255, 0.125);
		font-style: italic;
		margin: 0 0 2em 0;
		padding: 0.5em 0 0.5em 2em;
	}

	code {
		background: rgba(255, 255, 255, 0.025);
		border-radius: 5px;
		border: solid 2px rgba(255, 255, 255, 0.125);
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0.25em;
		padding: 0.25em 0.65em;
	}

	pre {
		-webkit-overflow-scrolling: touch;
		font-family: "Courier New", monospace;
		font-size: 0.9em;
		margin: 0 0 2em 0;
	}

		pre code {
			display: block;
			line-height: 1.75em;
			padding: 1em 1.5em;
			overflow-x: auto;
		}

	hr {
		border: 0;
		border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		margin: 2.5em 0;
	}

		hr.major {
			margin: 4em 0;
		}

	.align-left {
		text-align: left;
	}

	.align-center {
		text-align: center;
	}

	.align-right {
		text-align: right;
	}



	section.special, article.special {
		text-align: center;
	}



	form {
		margin: 0 0 2em 0;
	}

		form .field {
			margin: 0 0 2em 0;
		}

			form .field label {
				margin-top: -1.5em;
			}

			form .field:first-child label {
				margin-top: 0;
			}

		form > :last-child {
			margin-bottom: 0;
		}

	label {
		color: #ffffff;
		display: block;
		font-family: Raleway, Helvetica, sans-serif;
		font-size: 0.8em;
		font-weight: 700;
		letter-spacing: 0.1em;
		margin: 0 0 0.7em 0;
		text-transform: uppercase;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	input[type="tel"],
	select,
	textarea {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		background: rgba(255, 255, 255, 0.025);
		border-radius: 5px;
		border: none;
		border: solid 2px rgba(255, 255, 255, 0.125);
		color: inherit;
		display: block;
		outline: 0;
		padding: 0 1em;
		text-decoration: none;
		width: 100%;
	}

		input[type="text"]:invalid,
		input[type="password"]:invalid,
		input[type="email"]:invalid,
		input[type="tel"]:invalid,
		select:invalid,
		textarea:invalid {
			box-shadow: none;
		}

		input[type="text"]:focus,
		input[type="password"]:focus,
		input[type="email"]:focus,
		input[type="tel"]:focus,
		select:focus,
		textarea:focus {
			border-color: #5b6ba6;
		}

	.select-wrapper {
		text-decoration: none;
		display: block;
		position: relative;
	}

		.select-wrapper:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			font-family: FontAwesome;
			font-style: normal;
			font-weight: normal;
			text-transform: none !important;
		}

		.select-wrapper:before {
			color: rgba(255, 255, 255, 0.125);
			content: '\f078';
			display: block;
			height: 2.75em;
			line-height: 2.75em;
			pointer-events: none;
			position: absolute;
			right: 0;
			text-align: center;
			top: 0;
			width: 2.75em;
		}

		.select-wrapper select::-ms-expand {
			display: none;
		}

	select option {
		color: #ffffff;
		background: #2e3141;
	}

	input[type="text"],
	input[type="password"],
	input[type="email"],
	select {
		height: 2.75em;
	}

	textarea {
		padding: 0.75em 1em;
	}

	input[type="checkbox"],
	input[type="radio"] {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		display: block;
		float: left;
		margin-right: -2em;
		opacity: 0;
		width: 1em;
		z-index: -1;
	}

		input[type="checkbox"] + label,
		input[type="radio"] + label {
			text-decoration: none;
			color: #ffffff;
			cursor: pointer;
			display: inline-block;
			font-size: 1em;
			font-family: "Source Sans Pro", Helvetica, sans-serif;
			text-transform: none;
			letter-spacing: 0;
			font-weight: 300;
			padding-left: 2.4em;
			padding-right: 0.75em;
			position: relative;
		}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				-moz-osx-font-smoothing: grayscale;
				-webkit-font-smoothing: antialiased;
				font-family: FontAwesome;
				font-style: normal;
				font-weight: normal;
				text-transform: none !important;
			}

			input[type="checkbox"] + label:before,
			input[type="radio"] + label:before {
				background: rgba(255, 255, 255, 0.025);
				border-radius: 5px;
				border: solid 2px rgba(255, 255, 255, 0.125);
				content: '';
				display: inline-block;
				height: 1.65em;
				left: 0;
				line-height: 1.58125em;
				position: absolute;
				text-align: center;
				top: 0;
				width: 1.65em;
			}

		input[type="checkbox"]:checked + label:before,
		input[type="radio"]:checked + label:before {
			background: #ffffff;
			border-color: #ffffff;
			content: '\f00c';
			color: #2e3141;
		}

		input[type="checkbox"]:focus + label:before,
		input[type="radio"]:focus + label:before {
			border-color: #4c5c96;
		}

	input[type="checkbox"] + label:before {
		border-radius: 5px;
	}

	input[type="radio"] + label:before {
		border-radius: 100%;
	}

	::-webkit-input-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	:-moz-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	::-moz-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	:-ms-input-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}

	.polyfill-placeholder {
		color: rgba(255, 255, 255, 0.35) !important;
		opacity: 1.0;
	}



	.box {
		border-radius: 5px;
		border: solid 2px rgba(255, 255, 255, 0.125);
		margin-bottom: 2em;
		padding: 1.5em;
	}

		.box > :last-child,
		.box > :last-child > :last-child,
		.box > :last-child > :last-child > :last-child {
			margin-bottom: 0;
		}

		.box.alt {
			border: 0;
			border-radius: 0;
			padding: 0;
		}



	.icon {
		text-decoration: none;
		border-bottom: none;
		position: relative;
	}

		.icon:before {
			-moz-osx-font-smoothing: grayscale;
			-webkit-font-smoothing: antialiased;
			font-family: FontAwesome;
			font-style: normal;
			font-weight: normal;
			text-transform: none !important;
		}

		.icon > .label {
			display: none;
		}



	.image {
		border-radius: 5px;
		border: 0;
		display: inline-block;
		position: relative;
	}

		.image img {
			border-radius: 5px;
			display: block;
		}

		.image.left, .image.right {
			max-width: 40%;
		}

			.image.left img, .image.right img {
				width: 100%;
			}

		.image.left {
			float: left;
			padding: 0 1.5em 1em 0;
			top: 0.25em;
		}

		.image.right {
			float: right;
			padding: 0 0 1em 1.5em;
			top: 0.25em;
		}

		.image.fit {
			display: block;
			margin: 0 0 2em 0;
			width: 100%;
		}

			.image.fit img {
				width: 100%;
			}

		.image.main {
			display: block;
			margin: 0 0 3em 0;
			width: 100%;
		}

			.image.main img {
				width: 100%;
			}



	ol {
		list-style: decimal;
		margin: 0 0 2em 0;
		padding-left: 1.25em;
	}

		ol li {
			padding-left: 0.25em;
		}

	ul {
		list-style: disc;
		margin: 0 0 2em 0;
		padding-left: 1em;
	}

		ul li {
			padding-left: 0.5em;
		}

		ul.alt {
			list-style: none;
			padding-left: 0;
		}

			ul.alt li {
				border-top: solid 1px rgba(255, 255, 255, 0.125);
				padding: 0.5em 0;
			}

				ul.alt li:first-child {
					border-top: 0;
					padding-top: 0;
				}

		ul.icons {
			cursor: default;
			list-style: none;
			padding-left: 0;
		}

			ul.icons li {
				display: inline-block;
				padding: 0 1em 0 0;
			}

				ul.icons li:last-child {
					padding-right: 0;
				}

				ul.icons li .icon:before {
					font-size: 1.25em;
				}

		ul.actions {
			cursor: default;
			list-style: none;
			padding-left: 0;
		}

			ul.actions li {
				display: inline-block;
				padding: 0 1em 0 0;
				vertical-align: middle;
			}

				ul.actions li:last-child {
					padding-right: 0;
				}

			ul.actions.small li {
				padding: 0 0.5em 0 0;
			}

			ul.actions.vertical li {
				display: block;
				padding: 1em 0 0 0;
			}

				ul.actions.vertical li:first-child {
					padding-top: 0;
				}

				ul.actions.vertical li > * {
					margin-bottom: 0;
				}

			ul.actions.vertical.small li {
				padding: 0.5em 0 0 0;
			}

				ul.actions.vertical.small li:first-child {
					padding-top: 0;
				}

			ul.actions.fit {
				display: table;
				margin-left: -1em;
				padding: 0;
				table-layout: fixed;
				width: calc(100% + 1em);
			}

				ul.actions.fit li {
					display: table-cell;
					padding: 0 0 0 1em;
				}

					ul.actions.fit li > * {
						margin-bottom: 0;
					}

				ul.actions.fit.small {
					margin-left: -0.5em;
					width: calc(100% + 0.5em);
				}

					ul.actions.fit.small li {
						padding: 0 0 0 0.5em;
					}

			@media screen and (max-width: 640px) {

				ul.actions {
					margin: 0 0 2em 0;
				}

					ul.actions li {
						padding: 1em 0 0 0;
						display: block;
						text-align: center;
						width: 100%;
					}

						ul.actions li:first-child {
							padding-top: 0;
						}

						ul.actions li > * {
							width: 100%;
							margin: 0 !important;
						}

					ul.actions.small li {
						padding: 0.5em 0 0 0;
					}

						ul.actions.small li:first-child {
							padding-top: 0;
						}

			}

		ul.contact {
			list-style: none;
			padding: 0;
		}

			ul.contact li {
				text-decoration: none;
				margin: 2.5em 0 0 0;
				padding: 0 0 0 3.25em;
				position: relative;
			}

				ul.contact li:before {
					-moz-osx-font-smoothing: grayscale;
					-webkit-font-smoothing: antialiased;
					font-family: FontAwesome;
					font-style: normal;
					font-weight: normal;
					text-transform: none !important;
				}

				ul.contact li:before {
					border-radius: 100%;
					border: solid 2px rgba(255, 255, 255, 0.125);
					display: inline-block;
					font-size: 0.8em;
					height: 2.5em;
					left: 0;
					line-height: 2.35em;
					position: absolute;
					text-align: center;
					top: 0;
					width: 2.5em;
				}

				ul.contact li:first-child {
					margin-top: 0;
				}

			@media screen and (max-width: 736px) {

				ul.contact li {
					margin: 1.5em 0 0 0;
				}

			}

	dl {
		margin: 0 0 2em 0;
	}

		dl dt {
			display: block;
			font-weight: 600;
			margin: 0 0 1em 0;
		}

		dl dd {
			margin-left: 2em;
		}



	.table-wrapper {
		-webkit-overflow-scrolling: touch;
		overflow-x: auto;
	}

	table {
		margin: 0 0 2em 0;
		width: 100%;
	}

		table tbody tr {
			border: solid 1px rgba(255, 255, 255, 0.125);
			border-left: 0;
			border-right: 0;
		}

			table tbody tr:nth-child(2n + 1) {
				background-color: rgba(255, 255, 255, 0.025);
			}

		table td {
			padding: 0.75em 0.75em;
		}

		table th {
			color: #ffffff;
			font-size: 0.9em;
			font-weight: 600;
			padding: 0 0.75em 0.75em 0.75em;
			text-align: left;
		}

		table thead {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
		}

		table tfoot {
			border-top: solid 2px rgba(255, 255, 255, 0.125);
		}

		table.alt {
			border-collapse: separate;
		}

			table.alt tbody tr td {
				border: solid 1px rgba(255, 255, 255, 0.125);
				border-left-width: 0;
				border-top-width: 0;
			}

				table.alt tbody tr td:first-child {
					border-left-width: 1px;
				}

			table.alt tbody tr:first-child td {
				border-top-width: 1px;
			}

			table.alt thead {
				border-bottom: 0;
			}

			table.alt tfoot {
				border-top: 0;
			}



	input[type="submit"],
	input[type="reset"],
	input[type="button"],
	button,
	.button {
		-moz-appearance: none;
		-webkit-appearance: none;
		-ms-appearance: none;
		appearance: none;
		-moz-transition: background-color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out;
		background-color: transparent;
		border-radius: 5px;
		border: 0;
		box-shadow: inset 0 0 0 2px rgba(255, 255, 255, 0.125);
		color: #ffffff !important;
		cursor: pointer;
		display: inline-block;
		font-family: Raleway, Helvetica, sans-serif;
		font-size: 0.8em;
		font-weight: 700;
		height: 3.75em;
		letter-spacing: 0.1em;
		line-height: 3.75em;
		padding: 0 2.25em;
		text-align: center;
		text-decoration: none;
		text-transform: uppercase;
		white-space: nowrap;
	}

		input[type="submit"]:hover,
		input[type="reset"]:hover,
		input[type="button"]:hover,
		button:hover,
		.button:hover {
			background-color: rgba(255, 255, 255, 0.025);
		}

		input[type="submit"]:active,
		input[type="reset"]:active,
		input[type="button"]:active,
		button:active,
		.button:active {
			background-color: rgba(255, 255, 255, 0.075);
		}








		input[type="submit"].icon:before,
		input[type="reset"].icon:before,
		input[type="button"].icon:before,
		button.icon:before,
		.button.icon:before {
			margin-right: 0.5em;
			color: rgba(255, 255, 255, 0.35);
		}

		input[type="submit"].special,
		input[type="reset"].special,
		input[type="button"].special,
		button.special,
		.button.special {
			background-color: #4c5c96;
			box-shadow: none;
		}

			input[type="submit"].special:hover,
			input[type="reset"].special:hover,
			input[type="button"].special:hover,
			button.special:hover,
			.button.special:hover {
				background-color: #53639e;
			}

			input[type="submit"].special:active,
			input[type="reset"].special:active,
			input[type="button"].special:active,
			button.special:active,
			.button.special:active {
				background-color: #45558d;
			}

			input[type="submit"].special.icon:before,
			input[type="reset"].special.icon:before,
			input[type="button"].special.icon:before,
			button.special.icon:before,
			.button.special.icon:before {
				color: #7884b0;
			}

		input[type="submit"].fit,
		input[type="reset"].fit,
		input[type="button"].fit,
		button.fit,
		.button.fit {
			display: block;
			margin: 0 0 1em 0;
			width: 100%;
		}

		input[type="submit"].small,
		input[type="reset"].small,
		input[type="button"].small,
		button.small,
		.button.small {
			font-size: 0.6em;
		}

		input[type="submit"].big,
		input[type="reset"].big,
		input[type="button"].big,
		button.big,
		.button.big {
			font-size: 1em;
		}

		input[type="submit"].disabled, input[type="submit"]:disabled,
		input[type="reset"].disabled,
		input[type="reset"]:disabled,
		input[type="button"].disabled,
		input[type="button"]:disabled,
		button.disabled,
		button:disabled,
		.button.disabled,
		.button:disabled {
			opacity: 0.25;
		}

		@media screen and (max-width: 640px) {

			input[type="submit"],
			input[type="reset"],
			input[type="button"],
			button,
			.button {
				padding: 0;
			}

		}



	.features {
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		margin: 0 0 2em 0;
	}

		.features article {
			padding: 1.75em 1.75em 0.1em 1.75em ;
			background-color: #353849;
			border-radius: 5px;
			margin: 1.5em 3em 1.5em 0;
			width: calc(50% - 1.5em);
		}

			.features article:nth-child(2n) {
				margin-right: 0;
			}

			.features article .image {
				border-radius: 5px 5px 0 0;
				display: block;
				margin-bottom: 1.75em;
				margin-left: -1.75em;
				margin-top: -1.75em;
				position: relative;
				width: calc(100% + 3.5em);
			}

				.features article .image img {
					border-radius: 5px 5px 0 0;
					width: 100%;
				}

		@media screen and (max-width: 980px) {

			.features article {
				margin: 1em 2em 1em 0;
				width: calc(50% - 1em);
			}

		}

		@media screen and (max-width: 736px) {

			.features article {
				padding: 1.5em 1.5em 0.1em 1.5em ;
				margin: 0.875em 1.75em 0.875em 0;
				width: calc(50% - 0.875em - 1px);
			}

				.features article .image {
					margin-bottom: 1.5em;
					margin-left: -1.5em;
					margin-top: -1.5em;
					width: calc(100% + 3em);
				}

		}

		@media screen and (max-width: 640px) {

			.features {
				display: block;
			}

				.features article {
					width: 100%;
					margin: 0 0 2em 0 !important;
				}

		}



	#header {
		-moz-transition: background-color 0.2s ease-in-out;
		-webkit-transition: background-color 0.2s ease-in-out;
		-ms-transition: background-color 0.2s ease-in-out;
		transition: background-color 0.2s ease-in-out;
		background-color: rgba(53, 56, 73, 0.95);
		height: 3.5em;
		left: 0;
		line-height: 3.5em;
		padding: 0 1.25em;
		position: fixed;
		top: 0;
		width: 100%;
		z-index: 10000;
	}

		#header h1 {
			-moz-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			-webkit-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			-ms-transition: opacity 0.2s ease-in-out, visibility 0.2s;
			transition: opacity 0.2s ease-in-out, visibility 0.2s;
			border-bottom: 0;
			font-size: 0.8em;
			margin-bottom: 0;
			opacity: 1;
			visibility: visible;
		}

			#header h1 a {
				border: 0;
			}

		#header nav {
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 0.8em;
			font-weight: 700;
			height: 3em;
			letter-spacing: 0.1em;
			line-height: 3em;
			position: absolute;
			right: 0.7em;
			text-transform: uppercase;
			top: 0.7em;
		}

			#header nav a {
				border: 0;
				display: inline-block;
				padding: 0 1em;
			}

				#header nav a:before {
					float: right;
					margin-left: 0.75em;
				}

				#header nav a[href="#menu"] {
					text-decoration: none;
					-moz-transition: background-color 0.2s ease-in-out;
					-webkit-transition: background-color 0.2s ease-in-out;
					-ms-transition: background-color 0.2s ease-in-out;
					transition: background-color 0.2s ease-in-out;
					border-radius: 5px;
					box-shadow: inset 0 0 0 2px rgba(255, 255, 255, 0.125);
					padding: 0 1.35em;
				}

					#header nav a[href="#menu"]:before {
						-moz-osx-font-smoothing: grayscale;
						-webkit-font-smoothing: antialiased;
						font-family: FontAwesome;
						font-style: normal;
						font-weight: normal;
						text-transform: none !important;
					}

					#header nav a[href="#menu"]:before {
						content: '\f0c9';
					}

					#header nav a[href="#menu"]:hover {
						background-color: rgba(255, 255, 255, 0.025);
					}

					#header nav a[href="#menu"]:active {
						background-color: rgba(255, 255, 255, 0.075);
					}

		#header.alt {
			background-color: transparent;
		}

			#header.alt h1 {
				opacity: 0;
				visibility: hidden;
			}

		@media screen and (max-width: 736px) {

			#header {
				height: 2.75em;
				line-height: 2.75em;
			}

				#header nav {
					top: 0;
					right: 0;
					height: inherit;
					line-height: inherit;
				}

					#header nav a {
						height: inherit;
						line-height: inherit;
					}

						#header nav a[href="#menu"] {
							box-shadow: none;
							padding: 0 1em;
							border-radius: 0;
						}

							#header nav a[href="#menu"]:hover, #header nav a[href="#menu"]:active {
								background-color: inherit;
							}

		}

		@media screen and (max-width: 640px) {

			#header nav a[href="#menu"] {
				width: 4em;
				white-space: nowrap;
				text-indent: 4em;
				position: relative;
			}

				#header nav a[href="#menu"]:before {
					width: inherit;
					position: absolute;
					top: 0;
					left: 0;
					text-indent: 0;
					text-align: right;
					margin-left: 0;
					padding-right: 1.25em;
				}

		}



	#page-wrapper {
		-moz-transition: -moz-filter 0.25s ease;
		-webkit-transition: -webkit-filter 0.25s ease;
		-ms-transition: -ms-filter 0.25s ease;
		transition: filter 0.25s ease;
	}

	#menu {
		-moz-align-items: center;
		-webkit-align-items: center;
		-ms-align-items: center;
		align-items: center;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-justify-content: center;
		-webkit-justify-content: center;
		-ms-justify-content: center;
		justify-content: center;
		-moz-pointer-events: none;
		-webkit-pointer-events: none;
		-ms-pointer-events: none;
		pointer-events: none;
		-moz-transition: opacity 0.35s ease, visibility 0.35s;
		-webkit-transition: opacity 0.35s ease, visibility 0.35s;
		-ms-transition: opacity 0.35s ease, visibility 0.35s;
		transition: opacity 0.35s ease, visibility 0.35s;
		-moz-user-select: none;
		-webkit-user-select: none;
		-ms-user-select: none;
		user-select: none;
		-webkit-tap-highlight-color: transparent;
		background: rgba(46, 49, 65, 0.8);
		cursor: default;
		height: 100%;
		left: 0;
		opacity: 0;
		position: fixed;
		text-align: center;
		top: 0;
		visibility: hidden;
		width: 100%;
	}

		#menu .inner {
			padding: 2.5em 1.5em 0.5em 1.5em ;
			-moz-transform: translateY(0.5em);
			-webkit-transform: translateY(0.5em);
			-ms-transform: translateY(0.5em);
			transform: translateY(0.5em);
			-moz-transition: opacity 0.35s ease, -moz-transform 0.35s ease;
			-webkit-transition: opacity 0.35s ease, -webkit-transform 0.35s ease;
			-ms-transition: opacity 0.35s ease, -ms-transform 0.35s ease;
			transition: opacity 0.35s ease, transform 0.35s ease;
			-webkit-overflow-scrolling: touch;
			background: #4c5c96;
			border-radius: 5px;
			display: block;
			max-width: 100%;
			opacity: 0;
			position: relative;
			width: 18em;
		}

		#menu h2 {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			padding-bottom: 1em;
		}

		#menu .close {
			background-image: url("images/close.svg");
			background-position: 75% 25%;
			background-repeat: no-repeat;
			background-size: 2em 2em;
			border: 0;
			content: '';
			display: block;
			height: 4em;
			overflow: hidden;
			position: absolute;
			right: 0;
			text-align: center;
			text-indent: 4em;
			top: 0;
			width: 4em;
		}

		#menu .links {
			list-style: none;
			margin-bottom: 1.5em;
			padding: 0;
		}

			#menu .links li {
				padding: 0;
			}

				#menu .links li a {
					border-radius: 5px;
					border: 0;
					display: block;
					font-family: Raleway, Helvetica, sans-serif;
					font-size: 0.8em;
					font-weight: 200;
					letter-spacing: 0.1em;
					line-height: 1.85em;
					padding: 0.75em 0;
					text-transform: uppercase;
				}

					#menu .links li a:hover {
						background: #45558d;
					}

		@media screen and (max-width: 736px) {

			#menu .inner {
				max-height: 100%;
				overflow-y: auto;
				overflow-x: hidden;
			}

				#menu .inner .close {
					background-size: 1.5em 1.5em;
				}

		}

	body.is-menu-visible #page-wrapper {
		-moz-filter: blur(1.5px);
		-webkit-filter: blur(1.5px);
		-ms-filter: blur(1.5px);
		filter: blur(1.5px);
	}

	body.is-menu-visible #menu {
		-moz-pointer-events: auto;
		-webkit-pointer-events: auto;
		-ms-pointer-events: auto;
		pointer-events: auto;
		opacity: 1;
		visibility: visible;
	}

		body.is-menu-visible #menu .inner {
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			opacity: 1;
		}



	#banner {
		padding: 10em 0 4.75em 0 ;
	}

		#banner .inner {
			margin: 0 auto;
			width: 55em;
		}

		#banner .logo {
			-moz-transition: opacity 2s ease, -moz-transform 1s ease;
			-webkit-transition: opacity 2s ease, -webkit-transform 1s ease;
			-ms-transition: opacity 2s ease, -ms-transform 1s ease;
			transition: opacity 2s ease, transform 1s ease;
			-moz-transform: translateY(0);
			-webkit-transform: translateY(0);
			-ms-transform: translateY(0);
			transform: translateY(0);
			opacity: 1;
			margin: 0 0 1.3em 0;
		}

			#banner .logo .icon {
				border-radius: 100%;
				border: solid 2px rgba(255, 255, 255, 0.125);
				cursor: default;
				display: inline-block;
				font-size: 2em;
				height: 2.25em;
				line-height: 2.25em;
				text-align: center;
				width: 2.25em;
			}

		#banner h2 {
			-moz-transition: opacity 0.5s ease, -moz-transform 0.5s ease, -moz-filter 0.25s ease;
			-webkit-transition: opacity 0.5s ease, -webkit-transform 0.5s ease, -webkit-filter 0.25s ease;
			-ms-transition: opacity 0.5s ease, -ms-transform 0.5s ease, -ms-filter 0.25s ease;
			transition: opacity 0.5s ease, transform 0.5s ease, filter 0.25s ease;
			-moz-transform: translateX(0);
			-webkit-transform: translateX(0);
			-ms-transform: translateX(0);
			transform: translateX(0);
			-moz-transition-delay: 0.65s;
			-webkit-transition-delay: 0.65s;
			-ms-transition-delay: 0.65s;
			transition-delay: 0.65s;
			-moz-filter: blur(0);
			-webkit-filter: blur(0);
			-ms-filter: blur(0);
			filter: blur(0);
			opacity: 1;
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			font-size: 2.25em;
			margin-bottom: 0.8em;
			padding-bottom: 0.4em;
		}

		#banner p {
			-moz-transition: opacity 0.5s ease, -moz-transform 0.5s ease, -moz-filter 0.25s ease;
			-webkit-transition: opacity 0.5s ease, -webkit-transform 0.5s ease, -webkit-filter 0.25s ease;
			-ms-transition: opacity 0.5s ease, -ms-transform 0.5s ease, -ms-filter 0.25s ease;
			transition: opacity 0.5s ease, transform 0.5s ease, filter 0.25s ease;
			-moz-transform: translateX(0);
			-webkit-transform: translateX(0);
			-ms-transform: translateX(0);
			transform: translateX(0);
			-moz-transition-delay: 0.8s;
			-webkit-transition-delay: 0.8s;
			-ms-transition-delay: 0.8s;
			transition-delay: 0.8s;
			-moz-filter: blur(0);
			-webkit-filter: blur(0);
			-ms-filter: blur(0);
			filter: blur(0);
			opacity: 1;
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 1em;
			font-weight: 200;
			letter-spacing: 0.1em;
			line-height: 2;
			text-transform: uppercase;
		}

		@media screen and (max-width: 1280px) {

			#banner {
				padding: 7em 0 8.25em 0 ;
				background-color: #2e3141;
				background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
				background-size: auto, cover;
				background-position: center, center;
				margin-bottom: -6.5em;
			}

		}

		@media screen and (max-width: 980px) {

			#banner {
				padding: 12em 3em 12.375em 3em ;
				margin-bottom: -4.75em;
			}

				#banner .inner {
					width: 100%;
				}

		}

		@media screen and (max-width: 736px) {

			#banner {
				padding: 5em 2em 4.25em 2em ;
				margin-bottom: -2.5em;
			}

				#banner .logo {
					margin: 0 0 1em 0;
				}

					#banner .logo .icon {
						font-size: 1.5em;
					}

				#banner h2 {
					font-size: 1.5em;
				}

				#banner p {
					font-size: 0.8em;
				}

		}

		body.is-loading #banner .logo {
			-moz-transform: translateY(0.5em);
			-webkit-transform: translateY(0.5em);
			-ms-transform: translateY(0.5em);
			transform: translateY(0.5em);
			opacity: 0;
		}

		body.is-loading #banner h2 {
			opacity: 0;
			-moz-transform: translateX(0.25em);
			-webkit-transform: translateX(0.25em);
			-ms-transform: translateX(0.25em);
			transform: translateX(0.25em);
			-moz-filter: blur(2px);
			-webkit-filter: blur(2px);
			-ms-filter: blur(2px);
			filter: blur(2px);
		}

		body.is-loading #banner p {
			opacity: 0;
			-moz-transform: translateX(0.5em);
			-webkit-transform: translateX(0.5em);
			-ms-transform: translateX(0.5em);
			transform: translateX(0.5em);
			-moz-filter: blur(2px);
			-webkit-filter: blur(2px);
			-ms-filter: blur(2px);
			filter: blur(2px);
		}



	#wrapper > header {
		padding: 11em 0 2.25em 0 ;
	}

		#wrapper > header .inner {
			margin: 0 auto;
			width: 55em;
		}

		#wrapper > header h2 {
			border-bottom: solid 2px rgba(255, 255, 255, 0.125);
			font-size: 2em;
			margin-bottom: 0.8em;
			padding-bottom: 0.4em;
		}

		#wrapper > header p {
			font-family: Raleway, Helvetica, sans-serif;
			font-size: 1em;
			font-weight: 200;
			letter-spacing: 0.1em;
			line-height: 2;
			text-transform: uppercase;
		}

	@media screen and (max-width: 1280px) {

		#wrapper > header {
			padding: 9em 0 6.25em 0 ;
			background-color: #2e3141;
			background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
			background-size: auto, cover;
			background-position: center, 0% 30%;
			margin-bottom: -6.5em;
		}

	}

	@media screen and (max-width: 980px) {

		#wrapper > header {
			padding: 11em 3em 7.375em 3em ;
			background-size: auto, cover;
			background-position: center, 0% 0%;
			margin-bottom: -4.75em;
		}

			#wrapper > header .inner {
				width: 100%;
			}

	}

	@media screen and (max-width: 736px) {

		#wrapper > header {
			padding: 6.5em 2em 3em 2em ;
			background-size: auto, 125%;
			margin-bottom: -2.5em;
		}

			#wrapper > header h2 {
				font-size: 1.25em;
			}

			#wrapper > header p {
				font-size: 0.8em;
			}

	}

	.wrapper {
		background-color: #2e3141;
		margin: 6.5em 0;
		position: relative;
	}

		.wrapper:before, .wrapper:after {
			background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%232e3141;' /%3E%3C/svg%3E");
		}

		.wrapper:before, .wrapper:after {
			background-repeat: no-repeat;
			background-size: 100% 100%;
			content: '';
			display: block;
			height: 6.5em;
			position: absolute;
			width: 100%;
		}

		.wrapper:before {
			left: 0;
			top: -6.5em;
		}

		.wrapper:after {
			-moz-transform: scaleY(-1);
			-webkit-transform: scaleY(-1);
			-ms-transform: scaleY(-1);
			transform: scaleY(-1);
			bottom: -6.5em;
			left: 0;
		}

		.wrapper.alt:before {
			-moz-transform: scaleX(-1);
			-webkit-transform: scaleX(-1);
			-ms-transform: scaleX(-1);
			transform: scaleX(-1);
		}

		.wrapper.alt:after {
			-moz-transform: scaleY(-1) scaleX(-1);
			-webkit-transform: scaleY(-1) scaleX(-1);
			-ms-transform: scaleY(-1) scaleX(-1);
			transform: scaleY(-1) scaleX(-1);
		}

		.wrapper .inner {
			padding: 3em 0 1em 0 ;
			margin: 0 auto;
			width: 55em;
		}

		.wrapper.style2 {
			background-color: #353849;
		}

			.wrapper.style2:before, .wrapper.style2:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23353849;' /%3E%3C/svg%3E");
			}

		.wrapper.style3 {
			background-color: #3d4051;
		}

			.wrapper.style3:before, .wrapper.style3:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%233d4051;' /%3E%3C/svg%3E");
			}

		.wrapper.style4 {
			background-color: #454858;
		}

			.wrapper.style4:before, .wrapper.style4:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23454858;' /%3E%3C/svg%3E");
			}

		.wrapper.style5 {
			background-color: #4d5060;
		}

			.wrapper.style5:before, .wrapper.style5:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%234d5060;' /%3E%3C/svg%3E");
			}

		.wrapper.style6 {
			background-color: #555867;
		}

			.wrapper.style6:before, .wrapper.style6:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23555867;' /%3E%3C/svg%3E");
			}

		.wrapper.spotlight {
			background-color: #4c5c96;
		}

			.wrapper.spotlight:before, .wrapper.spotlight:after {
				background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%234c5c96;' /%3E%3C/svg%3E");
			}

			.wrapper.spotlight .inner {
				display: -moz-flex;
				display: -webkit-flex;
				display: -ms-flex;
				display: flex;
				-moz-align-items: center;
				-webkit-align-items: center;
				-ms-align-items: center;
				align-items: center;
				-moz-flex-direction: row;
				-webkit-flex-direction: row;
				-ms-flex-direction: row;
				flex-direction: row;
			}

			.wrapper.spotlight .image {
				border-radius: 100%;
				margin: 0 3em 2em 0;
				width: 22em;
				overflow: hidden;
				-ms-flex: 1;
			}

				.wrapper.spotlight .image img {
					border-radius: 100%;
					width: 100%;
				}

			.wrapper.spotlight .content {
				width: 100%;
				-ms-flex: 2;
			}

			.wrapper.spotlight:nth-child(2n - 1) .inner {
				-moz-flex-direction: row-reverse;
				-webkit-flex-direction: row-reverse;
				-ms-flex-direction: row-reverse;
				flex-direction: row-reverse;
				text-align: right;
			}

			.wrapper.spotlight:nth-child(2n - 1) .image {
				margin: 0 0 2em 3em;
			}

			.wrapper.spotlight.style2 {
				background-color: #45558d;
			}

				.wrapper.spotlight.style2:before, .wrapper.spotlight.style2:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%2345558d;' /%3E%3C/svg%3E");
				}

			.wrapper.spotlight.style3 {
				background-color: #3f4e85;
			}

				.wrapper.spotlight.style3:before, .wrapper.spotlight.style3:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%233f4e85;' /%3E%3C/svg%3E");
				}

			.wrapper.spotlight.style4 {
				background-color: #39477c;
			}

				.wrapper.spotlight.style4:before, .wrapper.spotlight.style4:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%2339477c;' /%3E%3C/svg%3E");
				}

			.wrapper.spotlight.style5 {
				background-color: #324072;
			}

				.wrapper.spotlight.style5:before, .wrapper.spotlight.style5:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%23324072;' /%3E%3C/svg%3E");
				}

			.wrapper.spotlight.style6 {
				background-color: #2d3a69;
			}

				.wrapper.spotlight.style6:before, .wrapper.spotlight.style6:after {
					background-image: url("data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 100 100' preserveAspectRatio='none'%3E%3Cpolygon points='0,100 100,0 100,100' style='fill:%232d3a69;' /%3E%3C/svg%3E");
				}

		@media screen and (max-width: 980px) {

			.wrapper {
				margin: 4.75em 0;
			}

				.wrapper:before, .wrapper:after {
					height: 4.75em;
				}

				.wrapper:before {
					top: -4.75em;
				}

				.wrapper:after {
					bottom: -4.75em;
					left: 0;
				}

				.wrapper .inner {
					padding: 3em 3em 1em 3em ;
					width: 100%;
				}

				.wrapper.spotlight .image {
					margin: 0 2em 2em 0;
					width: 32em;
				}

				.wrapper.spotlight:nth-child(2n - 1) .image {
					margin: 0 0 2em 2em;
				}

		}

		@media screen and (max-width: 736px) {

			.wrapper {
				margin: 2.5em 0;
			}

				.wrapper:before, .wrapper:after {
					height: 2.5em;
				}

				.wrapper:before {
					top: -2.5em;
				}

				.wrapper:after {
					bottom: -2.5em;
					left: 0;
				}

				.wrapper .inner {
					padding: 2em 2em 0.1em 2em ;
				}

				.wrapper.spotlight .inner {
					-moz-align-items: -moz-flex-start;
					-webkit-align-items: -webkit-flex-start;
					-ms-align-items: -ms-flex-start;
					align-items: flex-start;
				}

				.wrapper.spotlight .image {
					width: 19em;
					margin: 0 1.75em 2em 0;
				}

				.wrapper.spotlight:nth-child(2n - 1) .image {
					margin: 0 0 2em 1.75em;
				}

		}

		@media screen and (max-width: 640px) {

			.wrapper.spotlight .inner {
				display: block;
			}

			.wrapper.spotlight .image {
				margin: 0 0 1em 0 !important;
				max-width: 85%;
				width: 12em;
			}

		}

		@media screen and (max-width: 360px) {

			.wrapper .inner {
				padding: 2em 1.5em 0.1em 1.5em ;
			}

		}



	#footer .inner {
		padding: 5em 0 3em 0 ;
		display: -moz-flex;
		display: -webkit-flex;
		display: -ms-flex;
		display: flex;
		-moz-flex-direction: row;
		-webkit-flex-direction: row;
		-ms-flex-direction: row;
		flex-direction: row;
		-moz-flex-wrap: wrap;
		-webkit-flex-wrap: wrap;
		-ms-flex-wrap: wrap;
		flex-wrap: wrap;
		margin: 0 auto;
		width: 55em;
	}

		#footer .inner > * {
			width: 100%;
		}

		#footer .inner form {
			margin: 0 3em 0 0;
			width: calc(50% - 1.5em);
		}

		#footer .inner .contact {
			width: calc(50% - 1.5em);
		}

		#footer .inner .copyright {
			border-top: solid 2px rgba(255, 255, 255, 0.125);
			list-style: none;
			margin: 4em 0 2em 0;
			padding: 2em 0 0 0;
			width: 100%;
		}

			#footer .inner .copyright li {
				border-left: solid 2px rgba(255, 255, 255, 0.125);
				color: rgba(255, 255, 255, 0.35);
				display: inline-block;
				font-size: 0.9em;
				line-height: 1;
				margin-left: 1em;
				padding: 0;
				padding-left: 1em;
			}

				#footer .inner .copyright li:first-child {
					border-left: 0;
					margin-left: 0;
					padding-left: 0;
				}

				#footer .inner .copyright li a {
					color: inherit;
				}

	@media screen and (max-width: 1280px) {

		#footer {
			background-color: #2e3141;
			background-image: linear-gradient(to top, rgba(46, 49, 65, 0.8), rgba(46, 49, 65, 0.8)), url("../../images/bg.jpg");
			background-size: auto, cover;
			background-position: center, center;
			margin-top: -6.5em;
			padding-top: 6.5em;
		}

	}

	@media screen and (max-width: 980px) {

		#footer {
			margin-top: -4.75em;
			padding-top: 4.75em;
		}

			#footer .inner {
				padding: 3em 3em 1em 3em ;
				display: block;
				width: 100%;
			}

				#footer .inner form {
					width: 100%;
					margin: 0 0 4em 0;
				}

				#footer .inner .contact {
					width: 100%;
					margin: 0 0 4em 0;
				}

				#footer .inner .copyright {
					margin: 4em 0 2em 0;
				}

	}

	@media screen and (max-width: 736px) {

		#footer {
			margin-top: -2.5em;
			padding-top: 2.5em;
		}

			#footer .inner {
				padding: 2em 2em 0.1em 2em ;
			}

				#footer .inner form {
					margin: 0 0 3em 0;
				}

				#footer .inner .contact {
					margin: 0 0 3em 0;
				}

	}

	@media screen and (max-width: 640px) {

		#footer .inner .copyright li {
			border-left: 0;
			display: block;
			margin: 1em 0 0 0;
			padding-left: 0;
		}

			#footer .inner .copyright li:first-child {
				margin-top: 0;
			}

	}

	@media screen and (max-width: 360px) {

		#footer .inner {
			padding: 2em 1.5em 0.1em 1.5em ;
		}

	}
