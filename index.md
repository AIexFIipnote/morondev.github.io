@import url(https://nfld99.github.io/Better-Discord/Source_Code/Addons/Use_Fonts/DiscordFont.css);

theme-dark,
.theme-dark {
    --header-primary: #fff;
    --header-secondary: #b9bbbe;
    --text-normal: #dcddde;
    --text-muted: #72767d;
    --text-link: #00b0f4;
    --channels-default: #8e9297;
    --interactive-normal: #b9bbbe;
    --interactive-hover: #dcddde;
    --interactive-active: #fff;
    --interactive-muted: #4f545c;
    --background-primary: #36393f;
    --background-secondary: #2f3136;
    --background-secondary-alt: #292b2f;
    --background-tertiary: #202225;
    --background-accent: #4f545c;
    --background-floating: #18191c;
    --background-mobile-primary: #36393f;
    --background-mobile-secondary: #2f3136;
    --background-modifier-hover: rgba(79,84,92,0.16);
    --background-modifier-active: rgba(79,84,92,0.24);
    --background-modifier-selected: rgba(79,84,92,0.32);
    --background-modifier-accent: hsla(0,0%,100%,0.06);
    --background-mentioned: rgba(250,166,26,0.05);
    --background-mentioned-hover: rgba(250,166,26,0.08);
    --background-message-hover: rgba(4,4,5,0.07);
    --background-help-warning: rgba(250,166,26,0.1);
    --background-help-info: rgba(0,176,244,0.1);
    --scrollbar-thin-thumb: #202225;
    --scrollbar-thin-track: transparent;
    --scrollbar-auto-thumb: #202225;
    --scrollbar-auto-track: #2e3338;
    --scrollbar-auto-scrollbar-color-thumb: #202225;
    --scrollbar-auto-scrollbar-color-track: #2f3136;
    --elevation-stroke: 0 0 0 1px rgba(4,4,5,0.15);
    --elevation-low: 0 1px 0 rgba(4,4,5,0.2),0 1.5px 0 rgba(6,6,7,0.05),0 2px 0 rgba(4,4,5,0.05);
    --elevation-medium: 0 4px 4px rgba(0,0,0,0.16);
    --elevation-high: 0 8px 16px rgba(0,0,0,0.24);
    --logo-primary: #fff;
    --focus-primary: #00b0f4;
    --radio-group-dot-foreground: #8ea1e1;
    --guild-header-text-shadow: 0 1px 1px rgba(0,0,0,0.4);
    --channeltextarea-background: #40444b;
    --activity-card-background: #202225;
    --textbox-markdown-syntax: #8e9297;
    --deprecated-card-bg: rgba(32,34,37,0.6);
    --deprecated-card-editable-bg: rgba(32,34,37,0.3);
    --deprecated-store-bg: #36393f;
    --deprecated-quickswitcher-input-background: #72767d;
    --deprecated-quickswitcher-input-placeholder: hsla(0,0%,100%,0.3);
    --deprecated-text-input-bg: rgba(0,0,0,0.1);
    --deprecated-text-input-border: rgba(0,0,0,0.3);
    --deprecated-text-input-border-hover: #040405;
    --deprecated-text-input-border-disabled: #202225;
    --deprecated-text-input-prefix: #dcddde;
}

/*Change watermark to Enola*/
.wordmark-2iDDfm:after {
  content: "Put Text Here";
  font-size: 14px;
  font-weight: 700;
  white-space: nowrap;
  font-family: "Discord";
  color: white;
}

.wordmark-2iDDfm svg {
  display: none;
}

.wordmark-2iDDfm {
  max-width: 90vw;
  text-overflow: ellipsis;
}

/*Chat bubbles*/
:root {
  --bubble-color: var(--background-tertiary);
  --bubble-padding: 5px 8px;
  --bubble-arrow-size: 5px;
}

/*User Messages*/
[data-is-author-self="true"].cozyMessage-3V1Y8y .contents-2mQqc9>.markup-2BOw-j:not(:empty) {
  background-color: #3F778A;
  display: inline-block;
  max-width: 100%;
  margin: 0;
  padding: var(--bubble-padding);
  border-radius: 5px;
  position: relative;
  overflow: visible;
}

/*Other Messages*/
[data-is-author-self="false"].cozyMessage-3V1Y8y .contents-2mQqc9>.markup-2BOw-j:not(:empty) {
  background-color: #203A43;
  display: inline-block;
  max-width: 100%;
  margin: 0;
  padding: var(--bubble-padding);
  border-radius: 5px;
  position: relative;
  overflow: visible;
}

.cozyMessage-3V1Y8y .contents-2mQqc9>.markup-2BOw-j blockquote, .cozyMessage-3V1Y8y .contents-2mQqc9>.markup-2BOw-j pre {
  max-width: unset;
}

.container-3w7J-x {
  background-color: var(--background-primary);
}

.panels-j1Uci_ {
  background-color: var(--background-primary);
}

.scrollableContainer-2NUZem {
  background-color: #203A43;
  border-radius: 25px;
}

.contentRegionScroller-26nc1e::-webkit-scrollbar-track,
.auto-Ge5KZx::-webkit-scrollbar-track,
.addGamePopout-2RY8Ju {
  background-color: var(--background-secondary) !important;
}

.theme-dark .container-3ayLPN {
  background-color: #3F778A;
}

.theme-dark .scrollerThemed-2oenus.themedWithTrack-q8E3vB .scroller-2FKFPG::-webkit-scrollbar-thumb,
.phoneFieldScroller-2IJUdK::-webkit-scrollbar-thumb,
.infoScroller-3EYYns::-webkit-scrollbar-thumb,
.listScroller-2_vlfo::-webkit-scrollbar-thumb,
.CodeMirror-vscrollbar::-webkit-scrollbar-thumb,
.scrollerThemed-2oenus.themeDark-2cjlUp .scroller-2FKFPG::-webkit-scrollbar-thumb,
.theme-dark .scrollerWrap-2lJEkd .scroller-2FKFPG::-webkit-scrollbar-thumb,
.contentRegionScroller-26nc1e::-webkit-scrollbar-thumb,
.sidebarRegionScroller-3MXcoP::-webkit-scrollbar-thumb,
.CodeMirror-hscrollbar::-webkit-scrollbar-thumb,
.scrollerBase-289Jih::-webkit-scrollbar-thumb,
.scroller-1IfWg_::-webkit-scrollbar-thumb,
.scroller-2wx7Hm::-webkit-scrollbar-thumb,
.popout-2sKjHu::-webkit-scrollbar-thumb,
.auto-Ge5KZx::-webkit-scrollbar-thumb {
  background-color: #3F778A;
  border-color: transparent !important;
}

.powercord-spotify .spotify-buttons button {
  display: none;
}

.circleIconButton-jET_ig:hover {
  background-color: #3F778A;
}

.circleIconButton-jET_ig {
  color: #3F778A;
}

.sprite-2iCowe {
  filter: grayscale(0) !important;
}

.messagesPopout-24nkyi {
  background-color: var(--background-primary);
}

.image-2JDb81 {
  display: none;
}

.channel-2QD9_O:hover {
  background-color: #3F778A;
}

.theme-dark .notches-1sAcEM.gray-3_LNYR {
  background: url("data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='8' height='20' fill='%23141414'%3E%3Cpath fill-rule='evenodd' d='M0 0h8v20H0V0zm4 2a2 2 0 00-2 2v12a2 2 0 104 0V4a2 2 0 00-2-2z'/%3E%3C/svg%3E");
}

.theme-dark .userSettingsVoice-iwdUCU .previewOverlay-2O7_KC {
  background-color: var(--background-secondary);
  border: none;
}

.theme-dark .uploadModal-2ifh8j {
  background-color: var(--background-primary);
}

.uploadModal-2ifh8j .inner-3nWsbo {
  background-color: var(--background-primary);
}

.uploadModal-2ifh8j .footer-3mqk7D.hasSpoilers-1IRtQC {
  background-color: var(--background-secondary);
}

.placeholder-37qJjk, .slateTextArea-1Mkdgw .hljs-comment, .slateTextArea-1Mkdgw .hljs-quote {
  color: white;
}

.container-3auIfb:not([style*="125"]) {
  background-color: #3F778A !important;
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div>div>nav>ul>div.scroller-2TZvBN.none-2Eo-qx.scrollerBase-289Jih>div:nth-child(4)>div.wrapper-21YSNc.selected>div>div:nth-child(2)>div>svg>foreignObject>div>div {
  background-color: #3F778A !important;
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div>div>nav>ul>div.scroller-2TZvBN.none-2Eo-qx.scrollerBase-289Jih>div:nth-child(4)>div.wrapper-21YSNc.selected.expanded>div>div:nth-child(2)>div>svg>foreignObject>div>div>div>svg {
  color: white !important;
}

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9, .wrapper-1BJsBx:hover .childWrapper-anI2G9 {
  background-color: #3F778A !important;
}

.theme-dark .container-1D34oG {
  background-color: var(--background-primary);
}

.theme-dark .outer-1AjyKL.active-1xchHY, .theme-dark .outer-1AjyKL.interactive-3B9GmY:hover {
  background-color: #3F778A !important;
}

.theme-dark .inset-3sAvek {
  background-color: var(--background-secondary);
}

.theme-dark .popout-38lTFE {
  background-color: var(--background-secondary);
}

.theme-dark .separator-XqIyoz {
  display: none;
}

.wrapper-3Rixsz:hover {
  background-color: #3F778A !important;
}

.memberListContainer-13tNU9:hover {
  background-color: #3F778A !important;
}

.icon-22AiRD {
  color: white !important;
}

.searchBar-6Kv8R2 .searchBarComponent-32dTOx {
  color: white;
}

.onlineFriends-counter {
  color: white;
}

.header-3msK0M {
  background-color: var(--background-primary);
}

.templatesList-2E6rTe {
  background-color: #203A43;
  height: 325px;
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div>div>div>div>div.container-1D34oG>section>div.children-19S4PO>div.tabBar-ZmDY9v.topPill-30KHOu>div:nth-child(5) {
  background-color: #3F778A !important;
}

.theme-dark .pageWrapper-1PgVDX {
  background-color: var(--background-primary);
}

.circleIconButton-jET_ig.selected-ugP_am {
  background-color: #3F778A !important;
}

.title-3w8xhj {
  color: white;
}

#app-mount>div.layerContainer-yqaFcK>div.layer-2KE1M9>div>div>div>div>div>div {
  border: none;
  background-color: var(--background-secondary);
  margin-top:10px;
}

.theme-light .footer-2gL1pp {
  background-color: var(--background-secondary);
  -webkit-box-shadow: none;
}

.lookFilled-1Gx00P.colorGrey-2DXtkV {
  background-color: var(--background-primary);
}

.lookFilled-1Gx00P.colorGrey-2DXtkV:hover {
  background-color: #3F778A;
}

.theme-light .root-1gCeng {
  -webkit-box-shadow: none;
  box-shadow: none;
}

.theme-dark .footer-1fjuF6 {
  background-color: var(--background-primary);
}

.theme-dark .body-3iLsc4, .theme-dark .footer-1fjuF6 {
  background-color: var(--background-primary);
}

.headerPlaying-j0WQBV {
  background-color: var(--background-primary);
}

.colorDefault-2K3EoJ.focused-3afm-j {
  background-color: var(--background-secondary);
}

.autocompleteInner-zh20B_ {
  background-color: var(--background-secondary);
}

.base-1pYU8j:hover {
  background-color: #3F778A;
}

.theme-dark .description-11DmNu, .theme-dark .descriptionUsername-J_75O8 {
  color: white;
}

.theme-dark .selected-1Tbx07 {
  background-color: #3F778A;
}

.textarea-2r0oV8 {
  color: white;
}

.input-cIJ7To {
  border: none;
  color: white;
}

.theme-dark .headerNormal-T_seeN {
  background-color: var(--background-primary);
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div>div>nav>ul>div.scroller-2TZvBN.none-2Eo-qx.scrollerBase-289Jih>div:nth-child(4)>div.wrapper-21YSNc>div>div:nth-child(2)>div>svg>foreignObject>div>div {
  background-color: #3F778A !important;
}

.theme-dark .notDetected-33MY4s, .theme-light .notDetected-33MY4s {
  background-color: #3F778A !important;
}

.theme-dark .card-FDVird:before {
  background-color: #3F778A !important;
  border-color: #3F778A !important;
}

.theme-dark .lastPlayed-3bQ7Bo, .theme-dark .overlayStatusText-L2IACa {
  color: white;
}

.theme-dark .overlayToggleIconOn-3UNmty .fill-1ugeBG {
  fill: white;
}

.theme-dark .game-1ipmAa {
  -webkit-box-shadow: none;
}

.theme-dark .paginator-166-09 {
  background-color: var(--background-secondary) !important;
}

.theme-dark .bottomDivider-1K9Gao {
  background-color: var(--background-secondary) !important;
  border-bottom: none;
}

.theme-dark .expandedInfo-3kfShd {
  background-color: #3F778A !important;
}

.theme-dark .paymentHeader-3QlZQi {
  border: none;
}

.lookFilled-1Gx00P.colorBrand-3pXr91 {
  background-color: #3F778A !important;
}

.clickable-1JJAn8:hover .layout-2DM8Md {
  background-color: rgba(32, 58, 67, 0.75)
}

.theme-dark .headerClickable-2IVFo9, .theme-dark .headerDefault-1wrJcN {
  background-color: rgba(32, 58, 67, 0.75);
  border-radius: 25px !important;
}

.theme-dark .streamPreview-2-WUWT {
  background-color: var(--background-secondary);
  margin: 0;
}

#channels>div>div:nth-child(9)>div.list-2luk8a.list-SuzGBZ.listDefault-3ir5aS>div:nth-child(1)>div>div>div.icons-1dXQdz>div>div {
  background-color: #3F778A !important;
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div>div>nav>ul>div.scroller-2TZvBN.none-2Eo-qx.scrollerBase-289Jih>div:nth-child(4)>div.wrapper-21YSNc.expanded>div>div:nth-child(2)>div>svg>foreignObject>div>div>div>svg {
  color: white !important;
}

.newMessagesBar-265mhP {
  background-color: #3F778A !important;
}

.botTagRegular-2HEhHi {
  background: #3F778A;
}

.colorDefault-2K3EoJ:hover {
  background: #3F778A;
  background-color: var(--background-secondary);
}

.theme-dark .root-1gCeng {
  background-color: var(--background-secondary);
}

.theme-dark .footer-2gL1pp {
  background-color: var(--background-secondary);
}

.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
  background-color: #3F778A;
}

.styleFlexible-wGDiIL {
  background-color: var(--background-primary);
}

.scroller-3BxosC {
  background-color: var(--background-primary);
}

.headerSpotify-zpWxgT {
  background-color: var(--background-primary);
}

.topSectionPlaying-1J5E4n {
  background-color: var(--background-primary);
}

.barFill-23-gu- {
  background-color: #3F778A;
}

.theme-dark .bar-2Qqk5Z {
  background-color: var(--background-secondary);
}

.theme-dark .option-96V44q.selected-rZcOL- {
  background-color: #3F778A;
}

.resultsGroup-r_nuzN {
  background-color: var(--background-primary);
}

.theme-dark .option-96V44q:after {
  display: none;
}

.guildNick-3uAm3i, .listName-3w10cx {
  display: none;
}

.listAvatar-1NlAhb {
  margin-right: 0;
}

.infoScroller-3EYYns {
  width: auto;
}

.note-QfFU8y {
  max-width: 296px;
}

.topSectionPlaying-1J5E4n, .root-SR8cQa {
  border-radius: 25px;
  min-height: 375px !important;
  max-height: 500px !important;
  height: auto;
  width: auto;
  min-width: 600px;
}

.lookFilled-1Gx00P .contents-18-Yxp, .lookInverted-2D7oAl .contents-18-Yxp, .lookLink-9FtZy- .contents-18-Yxp, .lookOutlined-3sRXeN .contents-18-Yxp {
  color: white;
}

.lookInverted-2D7oAl.colorBrand-3pXr91:hover {
  background-color: #3F778A;
}

.lookInverted-2D7oAl.colorBrand-3pXr91 {
  background-color: var(--background-secondary);
}

.lookFilled-1Gx00P.colorGreen-29iAKY {
  background-color: var(--background-secondary);
}

.lookFilled-1Gx00P.colorGreen-29iAKY:hover {
  background-color: #3F778A;
}

.Normal-2-vo2m {
  min-height: 375px !important;
  max-height: 500px !important;
  height: auto;
  border-radius: 25px;
}

.infoScroller-3EYYns::-webkit-scrollbar {
  display: none;
}

.modal-3c3bKg {
  position: absolute;
  width: 100%
}

.root-SR8cQa {
  display: flex;
  flex-direction: row;
  width: auto;
  background: transparent;
  overflow: visible;
}

.body-3ND3kc::-webkit-scrollbar {
  display: none;
}

.body-3ND3kc {
  position: relative;
  max-width: 296px;
  margin-left: 10px;
  overflow: hidden visible;
  min-height: 375px !important;
  max-height: 489.01px !important;
  height: auto !important;
  border-radius: 25px;
}

.tabBarContainer-1s1u-z {
  display: flex;
  justify-content: center;
  border-color: var(--background-primary);
  z-index: 1;
  border-radius: 25px !important;
}

.theme-dark .emptyIconFriends-BrjhY9 {
  margin: 15px;
}

.listScroller-2_vlfo {
  min-height: 375px !important;
  max-height: 489.4px !important;
  height: auto !important;
}

.search-2oPWTC .DraftEditor-root .public-DraftStyleDefault-block span {
  background-color: var(--background-primary);
}

.theme-dark .focused-2bY0OD {
  background-color: var(--background-primary);
}

.theme-dark .dim-1l4L4y span {
  color: #ffffff;
  background-color: var(--background-secondary);
}

.theme-dark .queryContainer-RKFJW- {
  background-color: var(--background-secondary);
}

.theme-dark .keybindShortcut-1BD6Z1 {
  background: var(--background-secondary);
}

.fade-18lLrh.didRender-33z1u8 {
  border-radius: 25px;
  background-color: var(--background-primary);
}

.container-2dqNWc {
  background-color: var(--background-secondary);
  margin-left: 0;
  border-radius: 25px;
}

#channels>div>div:nth-child(9)>div.list-2luk8a.list-SuzGBZ.listDefault-3ir5aS>div:nth-child(2)>div>div>div.icons-1dXQdz>div>div {
  background-color: #3F778A !important;
}

.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6 {
  background-color: #3F778A !important;
}

.selectorButtonSelected-t5V9On {
  background-color: #3F778A !important;
}

.selectorButtonSelected-t5V9On:hover {
  background-color: #3F778A !important;
}

.selectorButton-EEUWed:not(.selectorButtonPremiumRequired-mKMbIu):hover {
  background-color: #3F778A !important;
}

.theme-dark .perksModal-fSYqOq {
  background-color: var(--background-primary);
}

.theme-dark .perk-2WeBWW {
  background-color: var(--background-secondary);
}

.theme-dark .tierBody-16Chc9 {
  background-color: var(--background-secondary);
}

.theme-dark .tierHeaderLocked-1s2JJz {
  background-color: #3F778A !important;
}

.tierTitle-y7BLPl {
  color: white;
}

.theme-dark .tierLock-3CSxSX {
  color: white;
}

.tierRequirements-dGesMA {
  color: white;
}

.tierIcon-2qSKGj {
  color: white;
}

.theme-dark .barBackground-2EEiLw {
  background-color: #3F778A !important;
}

.theme-dark .tierMarkerBackground-3q29am {
  background-color: #3F778A !important;
}

#app-mount>div.layerContainer-yqaFcK>div>div.perksModal-fSYqOq.auto-Ge5KZx.scrollerBase-289Jih>div.perksModalContentWrapper-2HU6uL>div:nth-child(1)>div.progressBarWrapper-15RqAy.progressBarWrapperVisible-3L7cSB>div>div.tierMarkerContainer-2BmgqV>div.tierMarkerGroup-xg6A1d.selectedTier-1JkO7i>div:nth-child(2)>div {
  background-color: #3F778A !important;
}

.activity-11LB_k {
  border-radius: 25px;
  background-color: #3F778A !important;
  margin: 10px;
  padding: 16px;
}

#app-mount>div:nth-child(7)>div.modal-3c3bKg>div>div>div.topSectionPlaying-1J5E4n>div>div.activityProfile-2bJRaP.activity-1ythUs {
  border-radius: 25px;
  background-color: #3F778A !important;
  margin: 10px;
}

#app-mount>div:nth-child(7)>div.modal-3c3bKg>div>div>div.topSectionSpotify-1lI0-P>div>div.activityProfile-2bJRaP.activity-1ythUs {
  border-radius: 25px;
  background-color: #3F778A !important;
  margin: 10px;
}

.lookInverted-2D7oAl.colorGreen-29iAKY {
  background-color: #3F778A !important;
}

.topSectionSpotify-1lI0-P {
  min-height: 375px !important;
  max-height: 489.4px !important;
  height: auto !important;
  border-radius: 25px;
  background-color: var(--background-primary);
}

.powercord-spotify .spotify-seek-bar-progress {
  background-color: #3F778A !important;
}

.headerFill-adLl4x {
  background-color: var(--background-primary) !important;
  border-radius: 25px !important;
}

.topSectionNormal-2-vo2m {
  width: auto;
  min-width: 600px;
  border-radius: 25px;
}

.content-2M3n_H a {
  color: white;
}

.theme-dark .invite-18yqGF {
  background-color: rgba(32, 58, 67, .6);
  border-color: var(--background-secondary);
}

.lookFilled-1Gx00P.colorGrey-2DXtkV:disabled {
  background-color: #3F778A;
}

.theme-dark .changeDetails-bk98pu {
  background-color: rgba(32, 58, 67, .3);
  transform: scale(0.95);
}

.theme-dark .auditLog-3jNbM6 {
  border-color: transparent;
}

.theme-dark .headerExpanded-CUEwZ5 {
  background-color: rgba(32, 58, 67, .6);
}

.theme-dark .divider-1pnAR2 {
  display: none;
}

.theme-dark .headerExpanded-CUEwZ5, .theme-dark .changeDetails-bk98pu {
  border-radius: 25px;
  margin: 5px;
}

.updateIconForeground-3tnNZn {
  fill: #3F778A;
}

#app-mount>div.app-1q1i1E>div>div.layers-3iHuyZ.layers-3q14ss>div:nth-child(2)>div>div.contentRegion-3nDuYy>div>div>div.toolsContainer-1edPuj>div>div>div.closeButton-1tv5uR>svg>path {
  fill: #3F778A;
}

.theme-dark .closeButton-1tv5uR {
  border-color: #3F778A;
}

.theme-dark .keybind-KpFkfr {
  color: #3F778A;
}

.theme-dark .message-2qRu38 {
  background-color: var(--background-secondary);
}

.theme-dark .codeRedemptionRedirect-1wVR4b {
  background-color: var(--background-secondary);
  border-color: transparent;
  border-radius: 25px;
}

.theme-dark .paymentPane-3bwJ6A {
  border-radius: 25px;
}

.topSectionNormal-2-vo2m .tabBarContainer-1s1u-z {
  border-top: none;
}

.streamPreviewWrapper-2DSWOK.mounted-26niXS {
  background-color: transparent;
}

.videoGrid-1khsrF {
  background-color: #0F2229;
}

.videoWrapper-2v09vt {
  background-color: #203A43;
}

.flexCenter-2Y_vCg {
  background-color: #0F2229;
}

.video-xBa92B {
  background-color: #203A43;
}

.input-2VB9rf {
  background-color: #0F2229;
}

.participantsButton-KYW-IW {
  background: #0F2229;
}

.participantsButton-KYW-IW:hover {
  background: #203A43;
}

.subtitle-Nw1LLR {
  margin-top: 8px;
  margin-bottom: 12px;
}

.container-UC8Ug1:hover {
  background-color: #3F778A;
}

.header-1Xr5FO {
  background-color: #203A43;
}

.colorHeaderPrimary-26Jzh-, .sampleLink-2NLvZg {
  color: white;
}

.scroller-3__pG8 {
  background-color: var(--background-primary);
}

.selectedIcon-3uS11H {
  color: #3F778A;
}

.theme-dark.authBox-hW6HRx {
  background-color: #0F2229;
}

.fallbackImage-31Sk4m {
  display: none;
}

.copyInput-1T2hfb {
  margin: 10px;
}

.lookOutlined-3sRXeN.colorGreen-29iAKY {
  color: #3F778A;
  border-color: #3F778A;
}

.cta-3gK0Pu {
  background-color: #203A43;
}

.cta-3gK0Pu:hover {
  background-color: #3F778A;
}

.theme-dark .separator-2-RRj_ {
  border-top: 0;
}

.theme-dark .searchOption-zQ-1l6 .answer-1n6g43 {
  color: #fff;
}
