/****GOOGLE/BD FONTS****/
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
@import url("https://nfld99.github.io/Better-Discord/Source_Code/Addons/Use_Fonts/DiscordFont.css");
@import url("https://fonts.googleapis.com/css2?family=Poiret+One&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Libre+Barcode+128&family=Libre+Barcode+128+Text&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Monoton&display=swap");

/****ADDONS****/
@import url("https://mwittrien.github.io/BetterDiscordAddons/Themes/BlurpleRecolor/BlurpleRecolor.css");
@import url("https://discordstyles.github.io/RadialStatus/dist/RadialStatus.css");
@import url("https://warrayquipsome.github.io/Chillax/ChillaxTag.css");
@import url("https://warrayquipsome.github.io/Chillax/Addons/SettingsModalEdited.css");
@import url("https://crearts-community.github.io/Friends-Grid/theme.css");
@import url("https://neodymium7.github.io/BetterDiscordStuff/CSS/AddServerDarkMode.css");




/***TRANSPARENT CODES***/
/**transparent part LVL I**/
/*home tab fix*/
.forumOrHome-2VTX6r{
  background: transparent;
}
/*spotify controls error background*/
.panels-3wFtMD span {
  background: transparent!important;
}
/*friends tab*/
.content-1SgpWY > div,
.panels-3wFtMD {
  background: transparent !important;
}
/*transparent scrollbar*/
::-webkit-scrollbar,
::-webkit-scrollbar-track,
::-webkit-scrollbar-track-piece {
  border-color: transparent !important;
  background: transparent !important;
}
::-webkit-scrollbar-thumb {
  border: none !important;
  background-clip: content-box !important;
  background: transparent !important;
}
/*transparent call background*/
.wrapper-1gVUIN,
.minimum-fXpVNc,
.callContainer-HtHELf {
  background: none !important;
}
.root-u9h3Ui,
.tile-2TcwiO {
  background: none;
}
.videoGrid-1tZm-F {
  background: transparent !important;
}
/**transparent part LVL II**/
/*small profile modal*/
.theme-dark .userPopout-2j1gM4 {
  background-color: rgba(0, 0, 0, 0.4);
  backdrop-filter: blur(4px);
}
.theme-dark .footer-3naVBw {
  background-color: rgba(0, 0, 0, 0) !important;
}
.theme-dark .avatar-2Vndt_ {
  border: 6px solid transparent;
  background-color: transparent;
}
.theme-dark .bodyInnerWrapper-2bQs1k {
  background: transparent;
}
/*small profile modal 2*/
.avatar-2OC07D {
  background: none;
  box-shadow: none !important;
}
.avatarHint-2g3Mcd foreignObject {
  mask: none;
}
.avatarHintInner-3gk_Yx {
  border-radius: 0px;
}
/*bd editor titlebar*/
.theme-dark .floating-window-titlebar {
  background-color: rgba(0, 0, 0, 0.575);
  backdrop-filter: blur(2px);
}
/*code block*/
.theme-dark .scrollbar-3vVt8d {
  background-color: rgba(0, 0, 0, 0.377) !important;
}
/*menu blur*/
.theme-dark .menu-1QACrS {
  /*Main class*/
  background-color: rgba(0, 0, 0, 0.3);
}
.menu-1QACrS::before,
.menu-1QACrS.submenu-1apzyU::before {
  /*Blurs the menu*/
  content: "";
  position: absolute;
  height: 100%;
  width: 100%;
  -webkit-backdrop-filter: blur(5px);
  backdrop-filter: blur(15px);
  z-index: -1;
  border-radius: 5px;
}
/*all in settings*/
.messagesPopoutWrap-3zryHW,
.drawerSizingWrapper-1txdWG {
  backdrop-filter: blur(5px) !important;
  background: #0004 !important;
}
.inspector-2A2Ch {
  backdrop-filter: blur(5px);
  background: transparent;
}
.feature-2IUcBI,
.container-2nx-BQ,
.bd-switch-body {
  background: #0007 !important;
}
.verticalFit-21XL0v,
.card-16VQ8C {
  background: #0001 !important;
}
.bottomDivider-ZmTm-j {
  background: transparent !important;
}
.bar-1Bhnl9,
.markDash-yk2kJ- {
  background: rgb(175, 175, 175) !important;
}
.popout-1KHNAq {
  backdrop-filter: blur(5px);
}
.bd-addon-card {
  background: rgba(0, 0, 0, 0.349) !important;
}
.bd-addon-header {
  background: transparent !important;
}
/*forum channel*/
.container-3wLKDe {
  background: transparent !important;
}

/*--FANCY CSS CODES--*/
/*discord wordmark*/
.wordmark-2u86JB path {
  display: none !important;
}
.theme-dark .wordmark-2u86JB::before {
  content: "‏‏‎ c h i l l a x";
  font-size: 12px;
  font-family: "Poiret one" !important;
  position: fixed;
  color: rgb(255, 255, 255);
  background: var(--window-colour);
  backdrop-filter: blur(var(--window-blur));
  border-radius: 5px;
  padding: 7px 11px 7px 7px;
  margin-left: 20px;
  margin-top: 5px;
  pointer-events: all;
  transition: 0.5s ease-in-out;
}
.wordmark-2u86JB:hover:before {
  content: "‏‏‎ c h i l l a x";
  letter-spacing: 2px;
}
/* button design*/
.theme-dark .lookFilled-1H2Jvj {
  border-radius: 45px;
  background: rgb(36, 36, 36) !important;
  color: rgb(255, 255, 255) !important;
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
  font-family: "Roboto";
  font-size: 12px;
  transition: 0.2s;
}
.theme-dark .lookFilled-1H2Jvj:hover {
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.3);
}
/*channel unread pill*/
.unread-36eUEm {
  margin-left: 4px;
  border-radius: 20px;
}
/*spotify gradient thing*/
.theme-dark .timeline-UWmgAx:hover .barFill-Dhkah7 {
  background: linear-gradient(135deg, #2b2b2b, var(--accentcolorV2));
}
/*chatbox recolour*/
.input-2g-os5,
.scrollableContainer-15eg7h{
  background-color: transparent!important;
  transition: background-color 0.2s ease, border-color 0.2s ease;
  outline: none;
}
.placeholder-1rCBhr.slateTextArea-27tjG0.fontSize16Padding-XoMpjI{
  color: transparent!important;
}
.theme-dark .input-2g-os5:hover,
.theme-dark .scrollableContainer-15eg7h:hover {
  background-color: #00000023!important;
}
.theme-dark .input-2g-os5:focus-within,
.theme-dark .scrollableContainer-15eg7h:focus-within {
  background-color: #181a1d!important;
  box-shadow: 0px 8px 18px rgba(0, 0, 0, 0.2);
}
.message-2CShn3 {
  border-radius: 8px !important;
}
.mentioned-Tre-dv  {
  border-radius: 0 8px 8px 0!important
}
/*Textbox Text*/
.theme-dark .placeholder-1rCBhr {
  visibility: hidden !important;
}
.theme-dark .placeholder-1rCBhr::before {
  content: "Life is so much easier when you just take a time to chill";
  color: rgba(255, 255, 255, 0.2);
  font-family: "Poppins";
  font-size: 13px;
  visibility: visible !important;
}
/* Replace Wandering Cubes Spinner/loading discord image with gif*/
span[class="inner-26JK4f"]:after {
  background-image: url("https://multiplexurbangreen.com/images/loader.gif");
  background-size: cover;
  display: inline-block;
  width: 32px;
  height: 32px;
  content: "";
}
span[class="inner-26JK4f"] > * {
  display: none;
}
/* member list and friend DMs hover effect */
.clickable-28SzVr:hover,
.interactive-1vLZ_I:hover {
  transform: scale(1.1);
  transition: all 0.2s;
}
.clickable-28SzVr,
.interactive-1vLZ_I {
  transition: all 0.3s;
}
/*recolor search*/
.theme-dark .container-2McqkF {
  -webkit-box-shadow: var(--elevation-high) !important;
  box-shadow: var(--elevation-high) !important;
}
.theme-dark .elevationBorderHigh-3drnJX {
  box-shadow: none !important;
  background: rgba(0, 0, 0, 0.555) !important;
  backdrop-filter: blur(10px) !important;
}
.theme-dark .container-2McqkF {
  border-radius: 8px !important;
}
.theme-dark .option-2KkUJO:after {
  display: none !important;
}
.theme-dark .searchOption-351dTI .filter-5YbOzJ {
  color: var(--accentcolorV2) !important;
}

/*connected vc buttons background*/
.wrapper-3t3Yqv,
.centerButton-1IShs7.colorable-3rVGna {
  background-color: var(--accentcolorV2) !important;
  border-radius: 50px;
}
/*better mark as read button*/
@keyframes pop {
  from {
    transform: translateY(30px);
    opacity: 0.4;
  }
  to {
    transform: translateY(0);
    opacity: 1;
  }
}
.newMessagesBar-1hF-9G.barBase-3xxDXu {
  margin-left: auto;
  margin-top: auto;
  align-self: flex-end;
  justify-self: flex-end !important;
  position: absolute !important;
  z-index: 998;
  bottom: 78px;
  right: 22px;
  padding: 8px 8px !important;
  width: 25.5px;
  height: 20px;
  background-color: var(--brand-experiment);
  box-shadow: var(--elevation-high);
  border-radius: 100px;
  display: flex;
  animation: pop 0.2s ease-in;
  transition: font-size 0s, color 0.2s 0.1s, padding 0.4s, width 0.1s 50ms;
  opacity: 1;
}
.newMessagesBar-1hF-9G.barBase-3xxDXu:hover {
  padding: 8px 18px !important;
  width: 105px;
  transition: font-size 0s, color 0.2s 0.1s, padding 0.4s, width 0.1s 50ms;
}
.newMessagesBar-1hF-9G.barBase-3xxDXu > button {
  font-size: 0px;
  color: transparent !important;
  transition: color 0.3s 0.1s, padding 0.4s;
}
.newMessagesBar-1hF-9G.barBase-3xxDXu:hover > button {
  font-size: 14px;
  color: #ffffff !important;
  transition: color 0.3s 0.1s, padding 0.4s;
}
.barButtonIcon-bMvzp2 {
  order: -1;
  margin: 0;
  margin-right: 0;
  margin-left: 6.5px;
  transition: all 0.2s;
  color: #fff !important;
}
.newMessagesBar-1hF-9G.barBase-3xxDXu:hover .barButtonIcon-bMvzp2 {
  margin-right: 5px;
  margin-left: 0;
}
.barButtonBase-Sk2mdB {
  padding: 0;
}
.barButtonMain-2GIx4o,
.barButtonMain-2GIx4o * {
  display: none !important;
}
/* Better Jump To Present Button */
[class*="jumpToPresentBar"] {
  display: contents;
}
[class*="jumpToPresentBar"] > button:first-child {
  display: none;
}
[class*="jumpToPresentBar"] > button:last-child {
  position: absolute;
  z-index: 1;
  bottom: 24px;
  right: 22px;
  padding: 8px !important;
  height: auto;
  background-color: var(--accentcolorV2);
  box-shadow: var(--elevation-high);
  border-radius: 100px;
  display: flex;
  font-size: 0px;
  color: transparent;
  transition: font-size 0.2s 0.1s, color 0.2s, padding 0.4s 0.1s;
}
[class*="jumpToPresentBar"] > button svg {
  order: -1;
  margin: 0px;
  height: 24px;
  width: 24px;
  top: auto;
  margin-right: 0px;
  margin-left: 0px;
  color: #ffffff;
  transition: margin 0.6s;
}
[class*="jumpToPresentBar"]:hover > button {
  padding: 8px 18px !important;
  font-size: 14px;
  color: #ffffff;
  transition: font-size 0.2s, color 0.2s 0.1s, padding 0.4s;
}
[class*="jumpToPresentBar"]:hover > button svg {
  margin-right: 2px;
  margin-left: -6px;
}
/*menu animation*/
.container-2McqkF,
.css-1x99fvh-menu,
.css-3vaxre-menu,
.drawerSizingWrapper-1txdWG,
.layer-2aCOJ3 div[role="dialog"],
.layer-2aCOJ3 div[role="menu"],
.messagesPopoutWrap-3zryHW,
.popout-1KHNAq[role="listbox"] {
  animation: animation-top 0.25s ease;
}
.layer-2aCOJ3 .animatorLeft-3yvG13 div[role="dialog"] {
  position: relative;
  animation: animation-left 0.25s ease;
}
.layer-2aCOJ3 div[role="dialog"] .messagesPopoutWrap-3zryHW {
  animation: none;
}
.layer-2aCOJ3 .animatorRight-xAUgTY .userPopout-2j1gM4 {
  transform-origin: center left;
  animation: animation-right 0.25s ease;
}
@keyframes animation-top {
  0% {
    -webkit-transform: translate(0, calc(14px * -1));
    transform: translate(0, calc(14px * -1));
    opacity: 0;
  }

  100% {
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
    opacity: 1;
  }
}
@keyframes animation-left {
  0% {
    -webkit-transform: translate(calc(14px * -1), 0);
    transform: translate(calc(14px * -1), 0);
    opacity: 0;
  }

  100% {
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
    opacity: 1;
  }
}
@keyframes animation-right {
  0% {
    -webkit-transform: translate(14px, 0);
    transform: translate(14px, 0);
    opacity: 0;
  }

  100% {
    -webkit-transform: translate(0, 0);
    transform: translate(0, 0);
    opacity: 1;
  }
}
/*channel hover effect*/
.theme-dark .mainContent-20q_Hp {
  transition: all 0.3s;
  position: relative;
}
.theme-dark .mainContent-20q_Hp {
  transition: all 0.3s;
}
.theme-dark .mainContent-20q_Hp::before {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  opacity: 0;
  transition: all 0.3s;
  border-top-width: 1px;
  border-bottom-width: 1px;
  border-top-style: solid;
  border-bottom-style: solid;
  border-top-color: rgba(255, 255, 255, 0.733);
  border-bottom-color: rgba(255, 255, 255, 0.733);
  transform: scale(0.1, 1);
}
.theme-dark .mainContent-20q_Hp:hover {
  letter-spacing: 1px;
}
.theme-dark .mainContent-20q_Hp:hover::before {
  opacity: 1;
  transform: scale(1, 1);
}
.theme-dark .mainContent-20q_Hp::after {
  content: "";
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
  transition: all 0.3s;
  background-color: rgba(255, 255, 255, 0);
}
.theme-dark .mainContent-20q_Hp:hover::after {
  opacity: 0;
  transform: scale(0.1, 1);
}
.theme-dark .content-1gYQeQ:hover {
  animation: wave-text 1s ease-in-out infinite;
}
.theme-dark .logo.is-animetion {
  span:nth-of-type(1) {
    animation-delay: 0s;
  }
  span:nth-of-type(2) {
    animation-delay: 0.1s;
  }
  span:nth-of-type(3) {
    animation-delay: 0.2s;
  }
  span:nth-of-type(4) {
    animation-delay: 0.3s;
  }
  span:nth-of-type(5) {
    animation-delay: 0.4s;
  }
}
@keyframes wave-text {
  00% {
    transform: translateY(0em);
  }
  60% {
    transform: translateY(-0.2em);
  }
  100% {
    transform: translateY(0em);
  }
}
/*bd editor control colour*/
.theme-dark #bd-editor-controls {
  background-color: rgba(0, 0, 0, 0.575)!important;
  box-shadow: none!important;
}
#floating-editor-window {
  border-radius: 5px;
}
.theme-dark .floating-window.resizable,
.theme-dark .floating-window-content,
.theme-dark .editor-wrapper,
.theme-dark .monaco-editor,
.theme-dark .monaco-editor-background,
.theme-dark .monaco-editor .inputarea.ime-input,
.theme-dark .monaco-editor .margin {
background: rgba(0, 0, 0, 0.1) !important;
backdrop-filter: blur(5px);
}
.btn-primary {
  color: white !important;
}
/*welcome text*/
.theme-dark body:before {
  content: "Greetings " var(--user-name) "!";
  z-index: 1000000000000000000000000;
  color: #fff;
  background-color: #0000007a;
  top: 0px;
  left: 52%;
  position: absolute;
  border-radius: 5px;
  padding: 5px 15px;
  transform: translate(-60%, -100%);
  animation: chl 3s ease;
  animation-delay: 4s;
}
body,
span:not(.spinner-item) {
  -webkit-font-smoothing: antialiased;
  -webkit-backface-visibility: hidden;
}
@-webkit-keyframes chl {
  from {
    transform: translate(-60%, -100%);
  }
  20% {
    transform: translate(-60%, 20%);
  }
  80% {
    transform: translate(-60%, 20%);
  }
  to {
    transform: translate(-60%, -100%);
  }
}
@keyframes chl {
  from {
    transform: translate(-60%, -100%);
  }
  20% {
    transform: translate(-60%, 20%);
  }
  80% {
    transform: translate(-60%, 20%);
  }
  to {
    transform: translate(-60%, -100%);
  }
}
/*default avatar*/
[src="/assets/1f0bfc0865d324c2587920a7d80c609b.png"] {
  content: url(https://i.imgur.com/tYEPmPZ.png);
}
[src="/assets/c09a43a372ba81e3018c3151d4ed4773.png"] {
  content: url(https://i.imgur.com/tYEPmPZ.png);
}
[src="/assets/7c8f476123d28d103efe381543274c25.png"] {
  content: url(https://i.imgur.com/tYEPmPZ.png);
}
[src="/assets/6f26ddd1bf59740c536d2274bb834a05.png"] {
  content: url(https://i.imgur.com/tYEPmPZ.png);
}
[src="/assets/3c6ccb83716d1e4fb91d3082f6b21d77.png"] {
  content: url(https://i.imgur.com/tYEPmPZ.png);
}
/*custom mentioned colour*/
.theme-dark .mentioned-Tre-dv:before {
  background: linear-gradient(135deg, #3b3b3b, var(--accentcolorV2)) !important;
}
.theme-dark .mentioned-Tre-dv {
  background: linear-gradient(
    60deg,
    rgba(41, 41, 41, 0.3),
    rgba(var(--accentcolor), 0.9)
  ) !important;
}
.theme-dark .mentioned-Tre-dv:hover {
  background: linear-gradient(
    60deg,
    rgba(32, 32, 32, 0.5),
    rgba(var(--accentcolor))
  ) !important;
}
/*user popout animation*/
.theme-dark #app-mount [class*="userPopout"][aria-modal="true"] {
  overflow: hidden;
  opacity: 0;
  -webkit-animation: fadeIn 0.5s ease forwards;
  animation: fadeIn 0.5s ease forwards;
}
/*Hides CSS Tips*/
.markdown-hover {
  display: none;
}
/*remove limit css editor*/
#floating-editor-window.resizable {
  max-height: unset;
  max-width: unset;
}
.floating-window.resizable {
  min-width: unset;
  min-height: unset;
  max-width: unset;
  max-height: unset;
}
/* Minified search bar */
:root {
  --transitionspeed: 0.25s;
}
.search-2Mwzzq:not(.open-1F8u2c) .searchBar-jGtisZ {
  width: 20px;
  transition: var(--transitionspeed);
  background-color: transparent;
}
.search-2Mwzzq:not(.open-1F8u2c):hover .searchBar-jGtisZ {
  width: 240px;
  background-color: var(--background-tertiary);
}
.search-2Mwzzq:not(.open-1F8u2c) .iconContainer-1RqWJj {
  transform: scale(1.3);
  transition: var(--transitionspeed);
}
.search-2Mwzzq:not(.open-1F8u2c):hover .iconContainer-1RqWJj {
  transform: scale(1);
}
.search-2Mwzzq:not(.open-1F8u2c) .icon-18rqoe {
  color: var(--text-normal);
}
.search-2Mwzzq:not(.open-1F8u2c):hover .icon-18rqoe {
  color: var(--text-muted);
}
.container-ZMc96U.themed-Hp1KC_ .search-39IXmY {
  order: -1 !important;
}
/*channel resize*/
.sidebar-1tnWFu .name-28HaxV {
  font-size: 14px;
}
.sidebar-1tnWFu .icon-2W8DHg {
  width: 16px;
  height: 16px;
}
/*about me clamp*/
.clamped-2ZePhX {
  -webkit-line-clamp: 190;
  max-height: 112px;
  overflow-x: hidden;
  overflow-y: scroll;
  margin-left: 15px;
}
.clamped-2ZePhX::-webkit-scrollbar {
  width: 13px;
  margin-left: 7px;
}
.clamped-2ZePhX::-webkit-scrollbar-track {
  border-radius: 30px;
  background-color: rgba(255, 255, 255, 0.047) !important;
}
.clamped-2ZePhX::-webkit-scrollbar-thumb {
  background: linear-gradient(45deg, #cacaca, var(--accentcolorV2)) !important;
  border-radius: 30px;
}
/*chillax appearance theme*/
.theme-dark {
  --cl-appearance: "Dark";
}
#app-mount .info-3pQQBb .line-18uChy:last-child:after {
  content: "Chillax " var(--cl-appearance) " 🎮";
  display: block;
}
/*custom bd window edit*/
.floating-window {
  border-radius: 5px !important;
}
.title {
  text-align: center;
  padding-left: 60px !important;
}
/*custom popout window*/
.theme-dark #app-mount .layers-OrUESM {
  margin: var(--window-margin);
  overflow: hidden;
  border-radius: var(--window-border-radius);
  background: var(--window-colour);
  backdrop-filter: blur(var(--window-blur)) !important;
}
/*user setting icon spin*/
.button-12Fmur:nth-last-child(1):hover
  path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
  animation: Settings 1s;
  transform-origin: center;
}
.button-12Fmur:nth-last-child(1)
  path[d="M19.738 10H22V14H19.739C19.498 14.931 19.1 15.798 18.565 16.564L20 18L18 20L16.565 18.564C15.797 19.099 14.932 19.498 14 19.738V22H10V19.738C9.069 19.498 8.203 19.099 7.436 18.564L6 20L4 18L5.436 16.564C4.901 15.799 4.502 14.932 4.262 14H2V10H4.262C4.502 9.068 4.9 8.202 5.436 7.436L4 6L6 4L7.436 5.436C8.202 4.9 9.068 4.502 10 4.262V2H14V4.261C14.932 4.502 15.797 4.9 16.565 5.435L18 3.999L20 5.999L18.564 7.436C19.099 8.202 19.498 9.069 19.738 10ZM12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8C9.79086 8 8 9.79086 8 12C8 14.2091 9.79086 16 12 16Z"] {
  animation: Settings2 1s;
  transform-origin: center;
}
@keyframes Settings {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(90deg);
  }
}
@keyframes Settings2 {
  from {
    transform: rotate(180deg);
  }
  to {
    transform: rotate(0deg);
  }
}
/*custom unread style*/
.unreadPillCap-2-iI4h {
  display: none;
  right: 50%;
}
.unreadPill-3nEWYM {
  background-color: var(--background-shading);
  color: #fb5454;
  font-size: 12px;
  letter-spacing: 20px;
  right: 50%;
  left: 50%;
  width: 30px;
}
.isUnread-3Lojb- {
  --divider-color: rgb(237, 0, 255);
  border: none;
  background: linear-gradient(
    90deg,
    rgba(237, 0, 255, 1) 0%,
    #fb5454 25%,
    rgba(0, 0, 0, 0) 50%,
    #fb5454 75%,
    rgba(254, 0, 255, 1) 100%
  );
  height: 1px;
}
.unreadPill-3nEWYM {
  top: -6px;
}
/*custom channel and text area font and size*/
.channelName-3KPsGw {
  font-family: var(--font-name);
  font-size: var(--font-size) !important;
}
.messageContent-2t3eCI,
.contents-2MsGLg {
  font-family: var(--font-name);
  font-size: var(--font-size) !important;
}
/*custom public servers and create server buttons*/
.theme-dark .guilds-2JjMmN .scroller-3X7KbA .circleIconButton-1VxDrg {
  border-radius: 50px;
  background: rgba(255, 255, 255, 0.1);
  color: rgb(255, 255, 255);
  transition: all 0.4s;
  border: dashed 1px rgba(255, 255, 255, 0.4);
}
.theme-dark .guilds-2JjMmN .scroller-3X7KbA .circleIconButton-1VxDrg:hover {
  color: #ffffff;
  background: transparent;
}
.pill-1NRFie {
  display: none;
}
/* colored links */
/* YouTube */
[href*="youtu.be"],
[href*="youtube.com"] {
  color: #c4302b !important;
}
/* Twitch */
[href*="twitch.tv"] {
  color: #b700ff !important;
}
/* Discord */
[href*="discord.com/channels/"] {
  color: #7289da !important;
}
[href*="discord.com/channels/"]::before {
  color: #603cff;
}
[href*="betterdiscord.app/"],
[href*="discord.gg/"],
[href*="discord.com/"],
[href*="media.discordapp.net/"],
[href*="cdn.discordapp.com/"] {
  color: #7289da !important;
}
/* Twitter */
[href*="twitter.com/"] {
  color: #00acee !important;
}
/* GitHub */
[href*="github.com"] {
  color: #00f0a8 !important;
}
/* Imgur */
[href*="i.imgur.com"] {
  color: #89c623 !important;
}
/* Steam */
[href*="store.steampowered.com"],
[href*="https://s.team"],
[href*="steamcommunity.com/"] {
  color: #1b2838 !important;
}
/* Spotify */
[href*="spotify.com"],
[href*="open.spotify.com"] {
  color: #13b94a !important;
}
/* SoundCloud */
[href*="soundcloud.com"] {
  color: #ff5500 !important;
}

/* Center profile badge, avatar and name */
.avatarWrapperNormal-ahVUaC {
  position: absolute;
  transform: translate(-50%);
  left: 50%;
}

.headerText-1-WmDq {
  text-align: center;
  position: relative;
  max-width: 100%;
  right: 0px;
  top: -7px;
}

.profileBadges-2pItdR {
  justify-content: center;
  position: relative;
  max-width: 100%;
  right: 0px;
  top: -10px;
}

.userPopout-2j1gM4 .bannerSVGWrapper-qc0szY > mask > circle {
  cx: 150;
  r: 47;
  cy: 57;
}
/* Center profile badge, avatar and name 2*/
.avatarPositionNormal-V4Mjtq {
  position: absolute;
  transform: translate(-50%);
  left: 50%;
}
.userText-148fun {
  text-align: center;
}
.profileBadges-31rDHI {
  max-width: 40%;
}
.divider-1tWBgZ {
  display: none;
}
.section-3FmfOT.lastSection-3_1yKt {
  visibility: hidden;
  margin-top: -65px !important;
}
/*remove unread with date*/ /*it causes issue with the theme*/
.hasContent-1y12-u {
  display: none;
}
/* Smaller Server */
ul[data-list-id="guildsnav"] [class^="pill-"],
ul[data-list-id="guildsnav"] [class^="pill-"] > div {
  height: 40px !important;
}
ul[data-list-id="guildsnav"] div[style*="height: 56"],
ul[id^="folder-items-"] {
  height: auto !important;
}
span[class^="expandedFolderBackground-"] {
  border-radius: 14px;
  width: 40px;
  left: 16px;
}
.wrapper-28eC3z,
[data-list-id="guildsnav"] [data-dnd-name] > div,
[data-list-id="guildsnav"] svg[width="48"] {
  width: 40px;
  height: 40px;
}
div[data-list-item-id="guildsnav___create-join-button"]:hover,
div[data-list-item-id="guildsnav___guild-discover-button"]:hover {
  opacity: 1;
}
/*glow radial status*/
div[class*="wrapper-3Un6-K"][aria-label*="Streaming"]
  > svg[class="mask-1y0tyc svg-1G_H_8"] {
  filter: drop-shadow(0 0 3px var(--rs-streaming-color)) !important;
}
div[class*="wrapper-3Un6-K"][aria-label*="Do Not Disturb"]
  > svg[class="mask-1y0tyc svg-1G_H_8"] {
  filter: drop-shadow(0 0 3px var(--rs-dnd-color)) !important;
}
div[class*="wrapper-3Un6-K"][aria-label*="Offline"]
  > svg[class="mask-1y0tyc svg-1G_H_8"] {
  filter: drop-shadow(0 0 3px var(--rs-offline-color)) !important;
}
div[class*="wrapper-3Un6-K"][aria-label*="Idle"]
  > svg[class="mask-1y0tyc svg-1G_H_8"] {
  filter: drop-shadow(0 0 3px var(--rs-idle-color)) !important;
}
div[class*="wrapper-3Un6-K"][aria-label*="Online"]
  > svg[class="mask-1y0tyc svg-1G_H_8"] {
  filter: drop-shadow(0 0 3px var(--rs-online-color)) !important;
}
/*theme background image*/
.bg-1QIAus {
  background-image: var(--background-image);
  background-attachment: var(--background-attachment, fixed);
  background-size: var(--background-size, cover);
  background-position: var(--background-position, center);
}

/*remove those annoying shadow on top of the chats*/
.searchBar-3TnChZ,
.header-3OsQeK {
  box-shadow: none;
}
.tabBody-2dgbAs:before {
  display: none;
}
.content-1jQy2l:before {
  display: none;
}
/*appearance theme preview*/
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"] {
  display: flex;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98 {
  width: 134px;
  height: 88px;
  margin-right: 20px;
  border-radius: 20px;
  box-shadow: var(--box-shadow-outer-3),
    var(--background-primary-box-shadow-border);
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98:first-child {
  background: url("https://cdn.discordapp.com/attachments/934719923735904257/990556326943932446/unknown.png?size=4096")
    center/cover;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98:nth-child(2) {
  background: url("https://cdn.discordapp.com/attachments/934719923735904257/990556326746787840/unknown.png?size=4096")
    center/cover;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98:nth-child(3) {
  background: url("https://cdn.discordapp.com/attachments/934719923735904257/990559275145384007/chillax_sync.jpg?size=4096")
      center/cover,
    var(--background-primary);
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98
  .radioBar-3w9XY-
  svg {
  display: none;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98
  .radioBar-3w9XY-
  .info-2FZci4 {
  margin-right: 0;
  grid-gap: 0;
  text-align: center;
  transform: translateY(40px);
  pointer-events: none;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98
  .radioBar-3w9XY- {
  height: 100%;
  align-items: flex-end;
  gap: 0;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98:last-child
  .info-2FZci4
  .text-md-medium-2avxhQ {
  display: none;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  [role="radiogroup"]
  .item-2idW98:last-child
  .info-2FZci4::before {
  content: "Sync";
  font-size: 16px;
  line-height: 20px;
  font-weight: 500;
}
#appearance-tab.contentColumn-1C7as6
  > :not([class]):first-child
  > .children-1xdcWE
  > div:nth-child(2)
  .container-1zDvAE.marginTop20-2T8ZJx {
  margin-top: 50px;
}
/*ping design*/
.numberBadge-37OJ3S {
  padding: 5px 10px !important;
  background-color: #fe365c;
  box-shadow: 0px 0px 10px 2px #ff2d54;
}
/*chillax squad font and colour change*/
[href="https\:\/\/github.com/warrayquipsome/Chillax#author"] {
  font-family: "Libre Barcode 128 Text";
  color: rgb(255, 161, 161) !important;
  font-weight: 400;
  font-size: 25px;
}
[href="https\:\/\/github.com/warrayquipsome/Chillax#author"]:hover {
  font-family: "Libre Barcode 128";
  color: rgb(255, 161, 161) !important;
  font-weight: 400;
  font-size: 25px;
}
/*custom group font*/
.input-1nrc5P {
  overflow: visible !important;
  font-family: "Monoton" !important;
  font-weight: 200!important;
  font-size: 25px;
  letter-spacing: 0.2px;
}
/*user setting channel hover effect*/
.theme-dark .selected-g-kMVV:after {
  background: none repeat scroll 0 0 transparent;
  bottom: 0;
  content: "";
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  background: #fff;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;
}
.selected-g-kMVV:hover:after {
  width: 100%;
  left: 0;
}
/*Connection Issue Let Me Be*/
.container-2RRFHK {
  background: transparent;
  pointer-events: none;
}
.container-2RRFHK .anchor-1MIwyf {
  pointer-events: auto;
}
.container-2RRFHK .content-3AIQZv .text-2bYgPB {
  display: none;
}
.container-2RRFHK .ready-3BZNWT {
  position: absolute;
  bottom: 44px;
  right: 244px;
  z-index: 1;
}
.container-2RRFHK img,
.container-2RRFHK video {
  display: none;
}
.container-2RRFHK .problems-CvGwpb {
  padding: 8px 16px;
  bottom: 18px;
  left: unset;
  right: 18px;
  width: fit-content;
  height: fit-content;
  background-color: var(--background-floating);
  border-radius: 8px;
  -webkit-box-shadow: var(--elevation-stroke), var(--elevation-medium);
  box-shadow: var(--elevation-stroke), var(--elevation-medium);
}
/*Better status*/
#status-picker-custom-status,
#status-picker #status-picker-custom-status + .separator-1So4YB + div {
  flex: 1 1 100%;
}
#status-picker-online,
#status-picker-idle,
#status-picker-dnd,
#status-picker-invisible {
  flex: 1 1 calc(25% - 2px);
  display: flex;
  justify-content: center;
  height: 40px;
}
#status-picker-online .statusItem-2hiCNB,
#status-picker-idle .statusItem-2hiCNB,
#status-picker-dnd .statusItem-2hiCNB,
#status-picker-invisible .statusItem-2hiCNB {
  width: fit-content;
  display: flex;
  padding: 0;
  justify-content: center;
}
#status-picker
  .item-1OdjEX:not(#status-picker-custom-status, #status-picker-switch-account)
  .status-3TYC5W {
  display: none;
}
#status-picker .description-3Cwkxk {
  display: none;
}
#status-picker .separator-1So4YB {
  display: none;
}
.statusItem-2hiCNB {
  column-gap: 5px;
}
#status-picker .mask-2Me5HY {
  height: 50%;
  width: auto;
}
.item-1OdjEX foreignObject {
  mask: none;
}
.status-2DiCMd {
  border-radius: 8px !important;
  width: 6px !important;
  height: 6px !important;
  margin-left: 2px;
  margin-top: 2px;
}
/*tooltip animation*/
.tooltip-14MtrL.tooltipTop-1wv5UJ {
  -webkit-animation: cl-tooltip-animation-1 0.2s
    cubic-bezier(0.2, 0.6, 0.5, 1.1);
  animation: cl-tooltip-animation-1 0.2s cubic-bezier(0.2, 0.6, 0.5, 1.1);
  transform-origin: 50% 100%;
}
.tooltip-14MtrL.tooltipBottom-2WzfVx {
  -webkit-animation: cl-tooltip-animation-1 0.2s
    cubic-bezier(0.2, 0.6, 0.5, 1.1);
  animation: cl-tooltip-animation-1 0.2s cubic-bezier(0.2, 0.6, 0.5, 1.1);
  transform-origin: 50% 0;
}
.tooltip-14MtrL.tooltipRight-2TSb42 {
  -webkit-animation: cl-tooltip-animation-2 0.2s
    cubic-bezier(0.2, 0.6, 0.5, 1.1);
  animation: cl-tooltip-animation-2 0.2s cubic-bezier(0.2, 0.6, 0.5, 1.1);
  transform-origin: 0 50%;
}
.tooltip-14MtrL.tooltipLeft-3H43DQ {
  -webkit-animation: cl-tooltip-animation-2 0.2s
    cubic-bezier(0.2, 0.6, 0.5, 1.1);
  animation: cl-tooltip-animation-2 0.2s cubic-bezier(0.2, 0.6, 0.5, 1.1);
  transform-origin: 100% 50%;
}
@-webkit-keyframes cl-tooltip-animation-1 {
  from {
    transform: rotateX(-90deg);
    opacity: 0;
  }
  to {
    transform: none;
    opacity: 1;
  }
}
@keyframes cl-tooltip-animation-1 {
  from {
    transform: rotateX(-90deg);
    opacity: 0;
  }
  to {
    transform: none;
    opacity: 1;
  }
}
@-webkit-keyframes cl-tooltip-animation-2 {
  from {
    transform: rotateY(-90deg);
    opacity: 0;
  }
  to {
    transform: none;
    opacity: 1;
  }
}
@keyframes cl-tooltip-animation-2 {
  from {
    transform: rotateY(-90deg);
    opacity: 0;
  }
  to {
    transform: none;
    opacity: 1;
  }
}
/*Embeds*/
:root {
  --embed-border-radius: 5px;
}
.theme-dark .embed-hKpSrO {
  border-radius: var(--embed-border-radius);
  z-index: 2;
}
.theme-dark .embed-hKpSrO code {
  background: rgb(51, 50, 53);
}
:root {
  --embed-line-width: 300px;
}
.theme-dark .embedFull-1HGV2S {
  border-top: none;
  border-right: none;
  border-bottom: none;
}
.theme-dark .embedFull-1HGV2S {
  border-left: calc(4px + var(--embed-line-width)) solid
    var(--background-accent);
  background: rgb(51, 50, 53);
  box-shadow: 2px 2px 8px rgb(42, 42, 46);
}
.theme-dark .grid-1aWVsE {
  margin-left: calc(-1 * var(--embed-line-width));
  z-index: 1;
}
.theme-dark .embedFull-1HGV2S:after,
.embedFull-1HGV2S:before {
  content: "";
  height: 100%;
  width: var(--embed-line-width);
  position: absolute;
  top: 0;
  left: calc(-1 * var(--embed-line-width));
}
.theme-dark .embedFull-1HGV2S:after {
  background: linear-gradient(to right, transparent, rgb(51, 50, 53));
  z-index: -3;
}
.theme-dark .embedFull-1HGV2S:before {
  background: rgb(51, 50, 53);
  opacity: 0.8;
  z-index: -1;
}
/* Settings/Deafen/Mute Buttons Animated */
.button-12Fmur:hover .contents-3ca1mk {
  animation: UserModalButtons 0.5s normal ease;
}

@keyframes UserModalButtons {
  0% {
    transform: translateY(0px);
  }
  50% {
    transform: translateY(-5px);
  }
  100% {
    transform: translateY(0px);
  }
}
/*guild pills glow*/
.theme-dark .item-2LIpTv {
  box-shadow: 0 0 3px rgb(255, 255, 255);
}
/*inline colour error fix*/
.theme-dark .inline {
  background: rgba(47, 49, 54, 0.5) !important;
}
/*disable and delete account button design*/
.theme-dark .children-2C96Ex .colorRed-2VFhM4 {
  width: 140px;
  height: 45px;
  font-family: "Roboto" !important;
  text-transform: uppercase;
  letter-spacing: 2.5px;
  font-weight: 500;
  color: rgb(255, 255, 255) !important;
  background-color: rgb(58, 58, 58) !important;
  border: none;
  border-radius: 45px;
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease 0s;
  cursor: pointer;
  outline: none;
}
.theme-dark .children-2C96Ex .colorRed-2VFhM4:hover {
  background-color: rgb(229, 46, 46) !important;
  box-shadow: 0px 15px 20px rgba(229, 46, 46, 0.4);
  color: rgb(37, 37, 37) !important;
  transform: translateY(-7px);
}
.theme-dark .children-2C96Ex .colorRed-2VFhM4 {
  font-size: 0px !important;
}
.theme-dark .children-2C96Ex .disableButton-3BR0Vj.colorRed-2VFhM4::before {
  content: "Disable";
  position: absolute;
  font-size: 11px !important;
}
.theme-dark .children-2C96Ex .lookOutlined-3RTC7c.colorRed-2VFhM4::before {
  content: "Delete";
  position: absolute;
  font-size: 11px !important;
}
/*seperator in settings*/
.theme-dark .separator-2wx7h6 {
  background: rgb(185, 185, 185);
  height: 5.5px !important;
  border-radius: 8px !important;
}
/*nitro buttons in settings*/
.theme-dark .button-1U79Hu {
  color: #fff !important;
  border: 4px solid #000;
  box-shadow: 0px 0px 0px 1px #000 inset !important;
  background-color: #000 !important;
  overflow: hidden;
  position: relative;
  transition: all 0.3s ease-in-out;
}
.theme-dark .button-1U79Hu:hover {
  border: 4px solid #666;
  background-color: rgb(255, 255, 255) !important;
  box-shadow: 0px 0px 0px 4px #eee inset !important;
}
.theme-dark .button-1U79Hu:after {
  background: #fff !important;
  border: 0px solid #000 !important;
  content: "";
  height: 155px;
  left: -75px;
  opacity: 0.8;
  position: absolute;
  top: -50px;
  -webkit-transform: rotate(35deg);
  transform: rotate(35deg);
  width: 50px;
  transition: all 1s cubic-bezier(0.075, 0.82, 0.165, 1); /*easeOutCirc*/
  z-index: 1;
}
.theme-dark .button-1U79Hu:hover:after {
  background: #fff !important;
  border: 20px solid #000 !important;
  opacity: 0;
  left: 120%;
  -webkit-transform: rotate(40deg);
  transform: rotate(40deg);
}
.theme-dark .giftButton-2RVWns {
  transition: all 0.2s ease-out;
  z-index: 2;
}
.theme-dark .giftButton-2RVWns:hover {
  letter-spacing: 0.13em;
  color: #333 !important;
}
/*custom min max close button*/
.theme-dark .winButtonClose-3Q8ZH5 {
  top: -3.5px;
  right: 20px;
  padding: 5px;
  margin: 5px;
  border-radius: 0px 5px 5px 0px;
  color: #fff;
  background: var(--window-colour);
  backdrop-filter: blur(var(--window-blur));
  transition: 0.2s;
}
.theme-dark .winButtonClose-3Q8ZH5:hover {
  top: -3.5px;
  right: 20px;
  padding: 5px;
  margin: 5px;
  border-radius: 0px 5px 5px 0px;
  color: #fff;
  background: transparent;
  transform: rotate(45deg) !important;
  transition: 0.1s;
  backdrop-filter: none;
}
.theme-dark .winButtonMinMax-3RsPUg:nth-child(3) {
  top: -3.5px;
  right: 10px;
  padding: 5px;
  margin: 5px;
  border-radius: 0px;
  color: #fff;
  background: var(--window-colour);
  backdrop-filter: blur(var(--window-blur));
  transition: 0.2s;
}
.theme-dark .winButtonMinMax-3RsPUg:nth-child(3):hover {
  top: -3.5px;
  right: 10px;
  padding: 5px;
  margin: 5px;
  border-radius: 0px;
  color: #fff;
  background: transparent;
  transform: rotate(45deg) !important;
  transition: 0.1s;
  backdrop-filter: none;
}
.theme-dark .winButtonMinMax-3RsPUg:nth-child(2n) {
  top: -3.5px;
  right: 0px;
  padding: 5px;
  margin: 5px;
  border-radius: 5px 0px 0px 5px;
  color: #fff;
  background: var(--window-colour);
  backdrop-filter: blur(var(--window-blur));
  transition: 0.2s;
}
.theme-dark .winButtonMinMax-3RsPUg:nth-child(2n):hover {
  top: -3.5px;
  right: 0px;
  padding: 5px;
  margin: 5px;
  border-radius: 5px 0px 0px 5px;
  color: #fff;
  background: transparent;
  transform: rotate(45deg) !important;
  transition: 0.1s;
  backdrop-filter: none;
}
/*flickering user setting icons*/
.sidebar-nqHbhN .item-2GWPIy:hover:before {
  transition: all 0.2s;
  transform: rotateY(180deg);
}
.sidebar-nqHbhN .item-2GWPIy:before {
  transition: all 0.2s;
}
/*settings user profile recolour*/
.theme-dark .accountProfileCard-lbN7n- {
  background: rgb(26, 26, 26);
}
.theme-dark .background-3d_SjE {
  background: rgb(34, 34, 34);
}
/*Better status*/
#account-edit-custom-status,
#status-picker #account-edit-custom-status + .separator-1So4YB + div {
  flex: 1 1 100%;
}
#account-status-picker--online,
#account-status-picker--dnd,
#account-status-picker--idle,
#account-status-picker--invisible {
  flex: 1 1 calc(25% - 2px);
  display: flex;
  justify-content: center;
  height: 40px;
}
.status-qmUf7L,
.description-22_U3B,
.separator-1So4YB {
  display: none;
}
#status-picker .mask-2Me5HY {
  height: 50%;
  width: auto;
}
.mask-2Me5HY foreignObject {
  mask: none;
}
.status-2DiCMd {
  border-radius: 8px !important;
  width: 6px !important;
  height: 6px !important;
  margin-left: 2px !important;
  margin-top: 2px !important;
}
.profileBody-3QbfPe {
  display: none;
}
.theme-dark .withTagAsButton-OsgQ9L:hover {
  background: rgb(49, 54, 58);
}
/*floating user controls*/
.theme-dark .panels-3wFtMD {
  background: #181a1d!important;
  box-shadow: 0 5px 8px #15171a;
  border-radius: 12px;
  margin: 10px 10px 23px;
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
}
.container-YkUktl{
background: transparent!important;
}
.sidebar-1tnWFu {
  background-color: transparent;
  position: relative;
  overflow: hidden;
}
.theme-dark .sidebar-1tnWFu .content-yjf30S:after{
content: 'this big gap is for the floating user controls, so sry if it looks ugly';
font-size: 13px;
color: rgba(255, 255, 255, 0.03);
text-align: center;
text-shadow: 0 0 15px #000;
margin-top: 50px;
height: 340px;
display: block;
}
.panels-3wFtMD > .container-YkUktl .flex-2S1XBF > :not(:last-child) {
  opacity: 0% !important;
  width: 50px;
  transition: all 0.3s;
}
.panels-3wFtMD > .container-YkUktl:hover .flex-2S1XBF > :not(:last-child) {
  opacity: 100% !important;
  width: 32px;
  margin-left: 10px;
}
.button-12Fmur[aria-label="User Settings"] {
  margin-left: 10px;
}
.container-6sXIoE .alignStretch-Uwowzr.flex-3BkGQD {
  max-width: 190px;
  min-width: 190px;
}
.details-ntX2k5 {
  max-width: 805px !important;
  min-width: 805px !important;
}
.maximized-vv2Wr0 .details-ntX2k5 {
  max-width: 190px !important;
  min-width: 190px !important;
  position: relative;
  display: block;
  left: 0px;
}
.maximized-vv2Wr0 .cover-SwJ-ck {
  border-radius: 8px 8px 0px 0px;
}
.avatarWrapper-1B9FTW {
  max-width: 36px;
  min-width: 36px;
  transition: 0.3s;
}
.avatarWrapper-1B9FTW:hover {
  max-width: 207px;
  min-width: 207px;
  transition: 0.3s;
}
/*Custom SpotifyControl in user panel*/
.container-6sXIoE.withTimeline-824fT_ {
  height: var(--playerHeight);
  border: none;
  padding: var(--paddingSides) var(--paddingSides) 10px var(--paddingSides);
  margin: 0;
  position: relative;
  display: flex;
  flex-flow: column nowrap;
  justify-content: space-between;
  overflow: hidden;
  z-index: 999;
}
.container-6sXIoE.withTimeline-824fT_.maximized-vv2Wr0 {
  --albumCoverRadius: 10px;
  --paddingSides: 15px;
  --playerHeight: 330px;
  padding-top: 10px;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0) {
  --paddingSides: 18px;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0)
  .coverWrapper-YAplwJ {
  width: calc(100% - ((var(--paddingSides) - 8px) * 2));
  height: 75px;
  margin: 0;
  position: absolute;
  inset: 10px 0 0 10px;
  overflow: hidden;
  z-index: -1;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0) .cover-SwJ-ck {
  --extraExpansion: 20px;
  width: calc(100% + var(--extraExpansion));
  height: calc(100% + var(--extraExpansion));
  position: relative;
  inset: calc((var(--extraExpansion) / 2) * -1) 0 0
    calc((var(--extraExpansion) / 2) * -1);
  filter: blur(4px) !important;
  opacity: 0.5;
  pointer-events: none;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0) .maximizer-RVu85p {
  width: 150%;
  height: 10px;
  left: -38px;
  background-color: rgba(0, 0, 0, 0.2);
  border-radius: 0;
  padding: 0;
  transform: none;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0)
  .maximizer-RVu85p
  > * {
  transform: rotate(90deg);
}
.container-6sXIoE.withTimeline-824fT_ .timeline-UWmgAx .bar-g2ZMIm:before,
.container-6sXIoE.withTimeline-824fT_ .timeline-UWmgAx .bar-g2ZMIm:after {
  content: "";
  width: 100%;
  height: 100%;
  border-radius: 5px;
  position: absolute;
  inset: 0 auto auto 0;
  transition: opacity 100ms ease-out;
}
.container-6sXIoE.withTimeline-824fT_ .timeline-UWmgAx .bar-g2ZMIm:before {
  background-color: rgba(255, 255, 255, 0.6);
  opacity: 0.4;
  z-index: -1;
}
.container-6sXIoE.withTimeline-824fT_ .timeline-UWmgAx .barFill-Dhkah7 {
  background: rgb(255, 255, 255) !important;
}
.container-6sXIoE.withTimeline-824fT_ button {
  margin: 0 !important;
  transition: transform 50ms ease-out;
}
.container-6sXIoE.withTimeline-824fT_ button:active {
  transform: translateY(2px);
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0) {
  --albumCoverRadius: 8px;
  --paddingSides: 18px;
  --playerHeight: 100px;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0) .inner-WRV6k5 {
  height: 35px;
  overflow: hidden;
}
.container-6sXIoE.withTimeline-824fT_:not(.maximized-vv2Wr0)
  .coverWrapper-YAplwJ {
  width: calc(100% - (var(--paddingSides) - 8px) * 2);
  height: calc(var(--playerHeight) - 10px);
  margin: 0;
  position: absolute;
  inset: 10px 0 0 10px;
  overflow: hidden;
  z-index: -1;
}
/*custom user setting profile position*/
.layer-86YKbF .accountProfileCard-lbN7n- .settingsBanner-2E5fAp {
  margin: 8px;
  width: unset;
  height: 90px!important;
  min-height: 0px;
  border-radius: 8px;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W {
  align-items: center;
  justify-content: center;
  width: calc(100% - 34px);
  margin-left: 17px;
  padding: 0;
  padding-top: 94px;
  padding-bottom: 9px;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .avatar-3mTjvZ {
  top: 50px;
  left: calc(50% - 43px);
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .userTag-2qPxEZ {
  margin-bottom: 2px;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .container-5SvbtF {
  justify-content: center;
  width: 100%;
  margin-bottom: 57px;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .button-ejjZWC {
  position: absolute;
  top: 53px;
  right: 295px;
  width: 76px;
  height: 76px;
  min-width: unset;
  min-height: unset;
  padding: 0;
  border-radius: 50px;
  background-color: transparent !important;
  font-size: 0;
  border: none!important;
  box-shadow: none;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .button-ejjZWC:hover {
  background-color: rgba(0, 0, 0, 0.6) !important;
  box-shadow: none;
  background-image: url('data:image/svg+xml;charset=utf-8,<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="thistle" class="bi bi-pencil-square" viewBox="0 0 16 16"><path d="M15.502 1.94a.5.5 0 0 1 0 .706L14.459 3.69l-2-2L13.502.646a.5.5 0 0 1 .707 0l1.293 1.293zm-1.75 2.456-2-2L4.939 9.21a.5.5 0 0 0-.121.196l-.805 2.414a.25.25 0 0 0 .316.316l2.414-.805a.5.5 0 0 0 .196-.12l6.813-6.814z"/><path fill-rule="evenodd" d="M1 13.5A1.5 1.5 0 0 0 2.5 15h11a1.5 1.5 0 0 0 1.5-1.5v-6a.5.5 0 0 0-1 0v6a.5.5 0 0 1-.5.5h-11a.5.5 0 0 1-.5-.5v-11a.5.5 0 0 1 .5-.5H9a.5.5 0 0 0 0-1H2.5A1.5 1.5 0 0 0 1 2.5v11z"/></svg>') !important;
  background-position: center !important;
  background-repeat: no-repeat !important;
}
/*threads background fix*/
.theme-dark .container-18GwIk {
  background: rgb(51, 49, 53);
}
/*toolbar fix [the bar when u double click ur unsent text]*/
.toolbar-37BrJ5 .inactive-3WMCpS {
  background: transparent !important;
  box-shadow: none !important;
}
/* sus links warning */
.art-3sVxAs {
  content: url("https://cdn.custom-cursor.com/packs/4105/among-us-character-in-dino-skin-pack.png");
  margin-top: -210px;
  height: 218px !important;
}
.title-2xi6Ka {
  text-indent: -1000px;
  line-height: 0;
}
.title-2xi6Ka:after {
  content: "This link is hella sus!";
  text-indent: 0;
  display: block;
  line-height: initial;
  font-size: 26px;
}
.body-1oUQrZ:after {
  content: " If you are sure it's not a virus, copy the link and paste to your browser. Wish you the best and don't get hacked that easily.";
}
.body-1oUQrZ strong {
  color: #a21fff !important;
  text-shadow: 1 12px 15px #7373ff;
  font-weight: 900 !important;
  font-size: 18px !important;
}
.focusLock-2tveLW .root-g14mjS.small-23Atuv {
  bottom: -50px !important;
}
.art-3sVxAs ~ .footer-31IekZ .contents-3ca1mk {
  display: none;
}
.art-3sVxAs ~ .footer-31IekZ > .button-f2h6uQ:after {
  content: "Back to safety";
  font-size: 12px;
}
/* pin home and add/public server */
.scroller-3X7KbA {
  display: flex;
  flex-direction: column;
  overflow: unset;
}
.scroller-3X7KbA > div[aria-label="Servers"] {
  overflow: hidden auto;
  margin: 10px 0;
}
.scroller-3X7KbA > div[aria-label="Servers"]::-webkit-scrollbar {
  width: 0px;
}
/*custom friends grid fix*/
.avatar-2MSPKk {
  left: 25px;
  bottom: -60px;
}
.theme-dark .listItemContents-2n2Uy9 {
  background: rgb(25, 25, 26);
}
.theme-dark .listItemContents-2n2Uy9:hover {
  background: rgb(43, 43, 44);
  transition: 0.2s;
}
.peopleColumn-1wMU14 .text-3j8t_e {
  width: 100% !important;
  margin-left: 0px !important;
  display: flex;
  align-items: center;
}
.peopleColumn-1wMU14 .listItemContents-2n2Uy9 .discordTag-3HiQI9 {
  margin-bottom: 10px;
}
.peopleColumn-1wMU14 .listItemContents-2n2Uy9 .activity-1KqKY2 {
  max-width: 250px;
}
/*active now*/
.heading-lg-medium-3gUJeM {
  text-align: center;
}
.theme-dark .itemCard-3Etziu.wrapper-2RrXDg {
  background: rgb(25, 25, 26);
}
.theme-dark .itemCard-3Etziu.wrapper-2RrXDg:hover {
  background: rgb(43, 43, 44);
  transition: 0.2s;
}
.section-3G9aLW {
  background: transparent;
}
/*pins inbox background fix*/
.theme-dark .messagesPopoutWrap-3zryHW,
.theme-dark .recentMentionsPopout-2bI1ZN,
.drawerSizingWrapper-1txdWG {
  background: rgb(51, 49, 53) !important;
}
/*custom new unreads*/
.bar-wDIGjg {
  padding: 14px 50px;
}
.unreadIcon-3dqgX9 {
  display: none;
}
.text-xs-medium-2LRpEj {
  margin-left: 5px !important;
}
.text-xs-medium-2LRpEj:before {
  content: "▸ ";
}
.text-xs-medium-2LRpEj:after {
  content: " ◂";
}
/*custom nsfw warning*/
.image-3HC6rC {
  content: url("https://cdn-icons-png.flaticon.com/512/4842/4842436.png");
}
.flex-2S1XBF.vertical-3aLnqW.gatedContent-31-gID
  > .flex-2S1XBF.flex-3BkGQD.horizontal-112GEH.horizontal-1Piu5-.flex-3BkGQD.directionRow-2Iu2A9.justifyCenter-rrurWZ.alignCenter-14kD11.noWrap-hBpHBz {
  background: transparent !important;
}
/*message hover small buttons fix*/
.theme-dark .wrapper-2vIMkT {
  background: rgb(51, 49, 53) !important;
}
/*custom reactions*/
.reactionMe-1PwQAc {
  border-radius: 50px !important;
  background: var(--accentcolorV2) !important;
  border: 1px solid transparent !important;
}
.reactionMe-1PwQAc:hover,
.reaction-3vwAF2:hover {
  border: 1px solid rgba(255, 255, 255, 0.5) !important;
}
.theme-dark .reaction-3vwAF2 {
  border-radius: 50px !important;
  background: rgba(255, 255, 255, 0.3);
}
/*better roles*/
.role-2TIOKu {
  transform: translate(0);
  overflow: hidden;
  --transparency: 0.4;
  border-radius: 5px;
}
.role-2TIOKu .roleRemoveIcon-387wKV {
  margin: 0;
  left: unset;
  transform: translate(50%, -50%);
}
.role-2TIOKu .roleRemoveButton-17oXnT {
  position: static;
}
.role-2TIOKu .roleCircle-3K9O3d:before {
  content: "";
  top: 0;
  left: 0;
  z-index: -1;
  width: 100%;
  height: 100%;
  position: absolute;
  background: inherit;
  opacity: var(--transparency);
}
/*spotify bar glow*/
.barFill-Dhkah7 {
  box-shadow: 4px 3px 10px #fff;
}
/*radiobar*/
#app-mount .itemFilled-1cPbtg[aria-checked="true"] .radioBar-3w9XY-::before {
  opacity: 1;
}
#app-mount .radioBar-3w9XY- {
  border: none !important;
  position: relative;
}
#app-mount .radioBar-3w9XY-::before {
  content: "";
  height: 30%;
  width: 5px;
  margin-right: 3px;
  border-radius: 8px;
  background: var(--radio-bar-accent-color);
  box-shadow: 0 0 calc(1 * 10px) var(--radio-bar-accent-color);
}
.radioBar-3w9XY- div:not([class]) {
display: none;
}
.radioIconForeground-2BMavi {
  display: none;
}
.radioBar-3w9XY- path {
  display: none;
}
/*emoji/gif/sticker tab fix*/
.theme-dark .drawerSizingWrapper-1txdWG {
  background: #18191ba6 !important;
  border-radius: 5px;
}
.theme-dark .unicodeShortcut-3N8oDe,
.standardStickerShortcut-ObSns3 {
  background: #292b2f;
}
/*better blocked message*/
@font-face {
  font-family: Blank;
  src: url("https://raw.githack.com/adobe-fonts/adobe-blank/master/AdobeBlank.ttf.woff");
  unicode-range: U+2014;
}
.blockedSystemMessage-3FmE9n .iconContainer-2rPbqG {
  display: none;
}
.theme-dark .blockedSystemMessage-3FmE9n {
  display: flex;
  justify-content: center;
  align-items: center;
  background: rgb(45, 48, 53);
  border-radius: 3px;
}
.blockedSystemMessage-3FmE9n {
  margin-left: -56px;
  margin-right: -3px;
}
.blockedSystemMessage-3FmE9n .content-vSHmMD {
  font-size: 12px !important;
  font-weight: 500;
  padding: 1px 0;
  text-transform: uppercase;
}
.blockedMessageText-3Zeg3y {
  cursor: pointer;
  pointer-events: none;
  font-family: Blank, var(--font-primary);
  color: var(--header-secondary);
  margin-right: -2.64px;
  z-index: 0;
}
.blockedAction-2cPk2G {
  pointer-events: all;
  display: block;
  position: absolute;
  width: 100%;
  height: 100%;
  left: 0;
  bottom: 0;
  color: rgba(0, 0, 0, 0%) !important;
  z-index: -1;
}
.blockedSystemMessage-3FmE9n:hover {
  box-shadow: 0 1px 3px rgb(0 0 0 / 16%);
}
.theme-dark .blockedSystemMessage-3FmE9n:hover .blockedAction-2cPk2G {
  background: rgb(37, 41, 46);
}
.groupStart-3Mlgv1.expanded-3lghlw .blockedSystemMessage-3FmE9n {
  background: none;
  border: 0;
  border-radius: 3px 3px 0 0;
  margin-left: -73px;
  margin-right: -17px;
  top: -0.125rem;
}
.theme-dark
  .groupStart-3Mlgv1.expanded-3lghlw
  .blockedSystemMessage-3FmE9n:hover {
  background: rgb(24, 25, 27);
  box-shadow: none;
}
.theme-dark .groupStart-3Mlgv1.expanded-3lghlw {
  background: rgb(45, 48, 53);
  border-radius: 3px;
  margin-left: 16px;
  margin-right: 13px;
}
.groupStart-3Mlgv1.expanded-3lghlw:hover {
  box-shadow: 0 1px 3px rgb(0 0 0 / 16%);
}
.groupStart-3Mlgv1.expanded-3lghlw .messageListItem-ZZ7v6g:last-child {
  padding-bottom: 20px;
}
.chatContent-3KubbW
  .scrollerInner-2PPAp2
  > :nth-last-child(2).groupStart-3Mlgv1.expanded-3lghlw
  + .scrollerSpacer-3AqkT9 {
  height: 10px;
}

/*add roles background fix*/
.theme-dark .container-2O1UgZ {
  background: rgb(51, 49, 53);
}
/*devilbro's dev badge fix*/
.dev-A7f2Rx.hasBadge-4rT8_u .mask-1FEkla {
  -webkit-mask: unset !important;
}
/*jump to message btn background fix*/
.theme-dark .button-cfOvv- {
  background: rgb(51, 49, 53);
}
/*edited version of bd cards in plugins and themes*/
.bd-addon-card-disabled {
  border: 2px solid #ff6f6f;
  box-shadow: 0 0 5px #f04747;
}
.bd-addon-card-disabled > *:not(#a#B) {
  background: var(--info-danger-background);
}
.bd-addon-card-disabled > :first-child {
  border-bottom: 2px solid #ff6f6f;
}
.bd-description-wrap > * {
  border: 0;
  justify-content: center;
  display: flex;
}
.bd-addon-card-disabled .banner-danger {
  display: none;
}
.bd-addon-card-disabled > .bd-addon-header > .bd-icon > path {
  d: path(
    "M11 15h2v2h-2zm0-8h2v6h-2zm.99-5C6.47 2 2 6.48 2 12s4.47 10 9.99 10C17.52 22 22 17.52 22 12S17.52 2 11.99 2zM12 20c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8z"
  );
  fill: #ff6f6f;
}
.bd-addon-card-disabled > .bd-addon-header > .bd-icon {
  width: 22px !important;
  height: 22px !important;
}
.bd-addon-header > .bd-title > .bd-name {
  text-align: center;
}
.bd-addon-card :where(.bd-title, .bd-name, .bd-meta) {
  display: block;
}
.bd-addon-card .bd-meta {
  width: 100;
  text-align: center;
  padding-top: 5px;
}
.theme-dark .bd-addon-list .bd-addon-header {
  background: rgb(22, 22, 26) !important;
}
.bd-addon-card-disabled > *:not(#a#B) {
  background: var(--info-danger-background) !important;
}
/*bd btn redesign*/
.bd-switch-body {
  border-radius: 10px !important;
}
.bd-switch-symbol {
  display: none;
}
.bd-switch-handle {
  transform: scale(0.8);
  transform-origin: center;
}
/*twitter like forum*/
.list-3FIpnh > div:first-child {
  width: 600px;
}
.container-2qVG6q {
  flex-direction: column;
  flex-grow: 1;
  padding-bottom: 40px;
  padding-left: 74px;
}
li.row-uezxzk {
  flex-direction: row;
}
.container-2qVG6q > div:last-child {
  width: 504px;
  max-width: 100%;
}
.bodyMedia-3ij3KY {
  width: 100%;
  margin-left: unset;
}
.thumbnailContainer-2XSRmY,
.thumbnailContainer-2XSRmY img {
  max-height: 504px;
  width: 100% !important;
  height: auto !important;
  object-fit: contain;
  object-position: 0;
}
.left-r1N3TH > div:last-child {
  position: absolute;
  inset: auto 0 0;
}
.header-2W779F {
  padding-bottom: 0;
}
.headerText-3MQ6n4 .channelNameSpan-2CGJt7,
.message-1zs6Od .messageContent-1SOr75 {
  font-size: initial !important;
  font-weight: normal;
  font-family: var(--font-primary);
  margin: unset;
  color: var(--text-muted);
  height: max-content;
  white-space: break-spaces;
}
.headerText-3MQ6n4 .channelNameSpan-2CGJt7 {
  color: var(--header-primary);
}
.message-1zs6Od .messageContent-1SOr75 .emoji {
  width: 18px;
}
.message-1zs6Od {
  max-height: unset;
}
.message-1zs6Od > span:first-child {
  position: absolute;
  top: 12px;
  font-size: 0;
}
.message-1zs6Od > span:first-child span {
  font-size: initial;
}
.message-1zs6Od > span:first-child span::before {
  content: "";
  width: 48px;
  height: 48px;
  background: center/contain url("https://i.imgur.com/tYEPmPZ.png");
  border-radius: 50%;
  position: absolute;
  transform: translateX(-62px);
}
.body-hCVwsC {
  padding-top: 18px;
}
.tags-2CaEuN .pill-3pRQlO {
  display: contents;
}
.tags-2CaEuN .pill-3pRQlO > div {
  font-size: initial;
  font-weight: normal;
  color: var(--text-link);
}
.tags-2CaEuN .pill-3pRQlO > div::before {
  content: "#";
  margin-left: 4px;
}
.footer-3dzxcR {
  height: 40px;
  justify-content: space-around;
  flex-direction: row-reverse;
}
.footer-3dzxcR .reaction-102jx9 {
  display: contents;
}
.footer-3dzxcR
  :is(.bullet-3kDmK0, .reaction-102jx9 img, .messageCountText-J-9pag
    + div, .typingUsers-1rTfwm),
.newBadge-1LcB6t,
.tags-2CaEuN .pill-3pRQlO[aria-label],
.tags-2CaEuN .pill-3pRQlO .emoji,
.container-27JV1h.container-1yy5xN {
  display: none;
}
.footer-3dzxcR .reaction-102jx9 .reactionCount-SWXh9W::before {
  content: "❤";
  margin-right: 4px;
}
.reactionMe-2zhiyZ .reactionCount-SWXh9W {
  color: var(--status-danger) !important;
}
.messageCountBox-XEP63e:hover * {
  color: var(--interactive-hover);
}
.chat-25x62K .scrollerContent-2SW0kQ {
  justify-content: flex-start;
}
.chat-25x62K .scrollerInner-2PPAp2 > li:nth-child(3) .message-2CShn3 {
  padding-left: unset;
}
.chat-25x62K .scrollerInner-2PPAp2 > li:nth-child(3) .header-2jRmjb {
  margin-left: 72px;
  padding-bottom: 20px;
  margin-bottom: 16px;
  display: flex;
}
.chat-25x62K
  .scrollerInner-2PPAp2
  > li:nth-child(3)
  :is(.messageContent-2t3eCI, .container-2sjPya) {
  margin-left: 16px;
  font-size: 23px;
  line-height: 28px;
  padding-left: unset;
}
.chat-25x62K .scrollerInner-2PPAp2 > li:nth-child(3) .timestampInline-_lS3aK {
  font-size: 0;
}
.chat-25x62K
  .scrollerInner-2PPAp2
  > li:nth-child(3)
  .timestampInline-_lS3aK
  > time::after {
  position: absolute;
  left: 0;
  top: 20px;
  content: attr(aria-label);
  font-size: 15px;
}
.chat-25x62K
  .scrollerInner-2PPAp2
  > li:nth-child(3)
  + .container-3YcgdM
  :is(.buttons-BK5gED, .buttons-BK5gED button > *, .reaction-102jx9) {
  display: contents;
}
.chat-25x62K
  .scrollerInner-2PPAp2
  > li:nth-child(3)
  + .container-3YcgdM
  .buttons-BK5gED
  > * {
  min-width: unset;
}
.chat-25x62K
  .scrollerInner-2PPAp2
  > li:nth-child(3)
  + .container-3YcgdM
  .buttons-BK5gED
  button {
  font-size: 0;
}
/*radial status small circle fix*/
.wrapper-1VLyxH > .svg-2azL_l circle {
  opacity: 0!important;
}
/*custom chillax theme card*/
#Chillax-card .bd-name {
  font-size: 100px;
  text-align: left;
}
#Chillax-card .bd-name::after {
  font-size: 20px;
  content: "activated";
  display: block;
  margin-top: -20px;
  margin-left: 15px;
}
.theme-dark #Chillax-card .bd-meta {
  margin-left: 15px;
  bottom: 25px;
  color: rgb(226, 226, 226);
}
#Chillax-card {
  border: 2px solid var(--accentcolorV2);
  box-shadow: 0 0 5px var(--accentcolorV2);
}
#Chillax-card .bd-addon-header{
border-bottom: 2px solid var(--accentcolorV2);
box-shadow: 0 0 5px var(--accentcolorV2);
}
#Chillax-card>*:not(#a#B) {
  background: rgba(var(--accentcolor), .2)!important;
}
#Chillax-card .bd-description {
  display: none;
}
.theme-dark #Chillax-card [href='https\:\/\/github.com/warrayquipsome/Chillax'] {
  color: #fff!important;
}
.theme-dark #Chillax-card [href='DrfX6286kF'] {
  color: #fff!important;
}
.bd-grid-view #Chillax-card .bd-name{
  font-size: 70px;
  text-align: left;
}
.bd-grid-view #Chillax-card .bd-name::after {
  font-size: 20px;
  content: "activated";
  display: block;
  margin-top: -15px;
  margin-left: 10px;
}
.theme-dark .bd-grid-view #Chillax-card .bd-meta {
  margin-left: -50px;
  bottom: 25px;
  color: rgb(226, 226, 226);
}
/*nitro badge fix*/
.profileBadge22-3GAYRy:not(#a#b),.profileBadge22-3OAigE:not(#a#b){
object-position: unset;
}
/*user setting redesign*/
.theme-dark .badgeList-b3Ajmk {
border-radius: 8px;
background-color: #333135;
margin-top: 5px;
padding: 2px;
}
.field-21XZwa:last-child {
    margin-right: 0 !important;
}
.theme-dark .field-21XZwa {
    width: calc((100%/3) - ((20/3) * 1px));
    border-radius: 8px;
    background-color: #333135;
    max-height: none;
    flex-flow: column;
    padding: 15px;
    display: inline-block;
    margin-right: 10px;
    margin-top: 0 !important;
    position: relative;
    overflow-y: scroll;
    height: 150px;
}
.field-21XZwa::-webkit-scrollbar {
    width: 0;
}
.constrainedRow-3y91Xf {
  overflow: visible;
}
.fieldButton-14lHvK.button-ejjZWC[aria-label="Edit phone number"] {
  top: 30px;
  border-radius: 8px;
}
.fieldButton-14lHvK.button-ejjZWC[aria-label="Edit username"] {
  top: 50px;
  border-radius: 8px;
}
.fieldButton-14lHvK.removeButton-v6eolJ {
  top: 30px!important;
  font-size: 12.7px;
}
.fieldButton-14lHvK.button-ejjZWC {
  top: 30px;
  border-radius: 8px;
}
.background-3d_SjE {
  background: transparent!important;
}
.settingsBanner-2E5fAp {
  border-radius: 8px;
}
#my-account-tab {
  transform: scale(0.98) translateX(-17px);
}
.fieldButton-14lHvK.button-ejjZWC[aria-label="Edit phone number"] {
  top: 50px;
  border-radius: 8px;
}
.fieldButton-14lHvK.button-ejjZWC[aria-label="Remove phone number"] {
  top: 50px!important;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W {
  align-items: center;
  justify-content: center;
  width: calc(100% - 34px);
  margin-left: 17px;
  padding: 0;
  padding-top: 94px;
  padding-bottom: 9px;
}
.layer-86YKbF .accountProfileCard-lbN7n- .userInfo-regn9W .button-f2h6uQ {
  position: absolute;
  top: 60.9px!important;
  right: 298px;
  width: 77px;
  height: 77px;
  min-width: unset;
  min-height: unset;
  padding: 0;
  border-radius: 50px;
  background-color: transparent !important;
  font-size: 0;
  border: none!important;
  box-shadow: none;
}
/*animated chat name hover*/
.username-h_Y3Us:after {
content: "";
position: absolute;
width: 100%;
transform: scaleX(0);
height: 1.5px;
bottom: 0;
left: 0;
background-color: currentColor;
transform-origin: bottom center;
transition: transform .1s;
}
.username-h_Y3Us:hover {
text-decoration: none !important;
}
.username-h_Y3Us:hover:after {
transform: scaleX(1);
transform-origin: bottom center;
}
/*channel border radius*/
.content-1gYQeQ {
  border-radius: 8px!important;
}
/*user profiles tweak*/
.userPopoutOuter-3AVBmJ .bannerSVGWrapper-qc0szY>mask>circle{
display: none;
}
.banner-2boKnS.popoutBanner-16rVDY{
    border-radius: 8px;
    margin: 7px;
    width: 95.5%;
    height: 53px;
}
.banner-2boKnS.profileBanner-2zIsK7 {
    border-radius: 8px;
    margin: 12px;
    width: 96%;
    height: 95px;
}
.root-g14mjS .avatar-1YsFQ1{
border: 8px solid transparent;
}
.root-g14mjS .bannerSVGWrapper-qc0szY>mask{
display: none;
}
.theme-dark .nameTag-2ysfG3 {
    background-color: #141414;
    padding: 10px;
    border-radius: 8px;
    width: fit-content;
}
.theme-dark .connectedAccountContainer-3aLMHJ {
border-radius: 8px;
background-color: #111111;
border: none!important;
width: 97%;
}
.connectedAccounts-2R5M4w.userInfoSection-2u2hir {
margin-top: 15px;
}
.connectedAccountsColumn-1zdyyx {
width: calc((100%/2) - 15px);
}
.pencilContainer-18TrEJ {
    display: none;
}
/*server banner design*/
.animatedContainer-2laTjx {
  transform: scale(0.9)!important;
  border-radius: 8px;
  box-shadow: 0 0 15px;
}
/*channel tab fix*/
#channelTabs-container {
  background: var(--window-colour)!important;
  margin: 20px 21px -13px 21px;
  padding: 10px!important;
  border-radius: var(--window-border-radius);
  backdrop-filter: blur(var(--window-blur));
}
html.platform-osx .typeMacOS-3V4xXE {
   position: absolute;
   width: unset;
}
.channelTabs-tabContainer {
   -webkit-app-region: drag;
}
.channelTabs-tabContainer>* {
   -webkit-app-region: no-drag;
}
html .channelTabs-newTab {
   margin-right: calc(6px + 72px);
}
/*chat box reply fix*/
.hasConnectedBar-1vN2JH {
  border-radius: 8px;
}
.theme-dark .attachedBars-2BCP3l {
padding: 10px;
margin: 20px 20px 10px 20px;
background: #181a1d;
border-radius: var(--window-border-radius)
}
/* user typing... but its edited*/
.dots-1BwzZQ {
  margin-right: 5px;
}
.base-3bcbY3 .text-3S7XCz {
    display:flex;
    align-items:center;
}
.typing-2J1mQU {
    font-size:0;
}
.typing-2J1mQU strong {
    font-size:12px;
}
.typing-2J1mQU strong:after {
    content:',';
    margin-right:4px;
}
.typing-2J1mQU strong:nth-last-child(2)::after {
    content:'and';
    margin:0 4px;
    color: rgba(255, 255, 255, 0.8);
    font-weight: 400;
    margin-top:-5px;
}
.typing-2J1mQU strong:last-child::after {
    content:'is smashing some buttons';
    color: rgba(255, 255, 255, 0.8);
    font-weight: 400;
    margin-top:-5px;
    margin-left:4px;
}
.typing-2J1mQU strong:nth-last-child()::after {
    content:'are smashing some buttons';
    color: rgba(255, 255, 255, 0.8);
    font-weight: 400;
    margin-top:-5px;
    margin-left:4px;
}
/*video control*/
.videoControls-2NzHnF {
width: auto;
margin: 15px;
padding-bottom: 0px;
border-radius: 8px;
background-color: #000000f1;
transform: none !important;
transition: 0.2s;
}
.wrapperControlsHidden-2BK8R2 .videoControls-2NzHnF{
margin-bottom: -30px;
}
/*user profile in dms design*/
.panelBanner-13bsBR {
  border-radius: 12px;
  margin: 12px;
  width: 93%;
  height: 105px;
}
.avatarPositionPanel-3P4Ted, .avatarStack-3vfSFa:before{
  left: 10%;
}
.bannerSVGWrapper-qc0szY foreignObject {
mask: none;
}
/*user profile in dms fix*/
.mutualGuildsList-37Q6HT > .collapseBtn-2sFINR, .mutualFriendsList-7kySbG > .collapseBtn-2sFINR {
  background: transparent!important;
  box-shadow: none!important;
  border-radius: 0px!important;
}
.theme-dark .mutualGuildsList-37Q6HT > .collapseBtn-2sFINR:hover, .theme-dark .mutualFriendsList-7kySbG > .collapseBtn-2sFINR:hover{
  background: rgba(255, 255, 255, 0.2)!important;
}
/*emoji tab design n fix*/
.theme-dark .nav-1zWVQw>.navList-YSb9UB>button{
flex: auto;
bottom: 20px;
line-height: 45px;
margin: 0;
border-radius: 0px;
background:#333135;
}
.inspector-2A2Chb {
  border-radius: 8px;
  margin: 10px;
  width: 95%
}
.unicodeShortcut-3N8oDe {
  border-radius: 8px;
  margin: 12px;
  margin-left: 5px;
  top: 330px!important;
  width: 85%;
}
.theme-dark .nav-1zWVQw>.navList-YSb9UB>button:hover {background: rgba(255, 255, 255, 0.2);}
.nav-1zWVQw{padding:0; }
/*custom unknown game icon*/
.theme-dark [d="M21.226 30v-4.154h-3.755V30h3.755zm-.512-8.62c3.67-1.337 5.718-2.959 5.718-6.145 0-3.272-2.36-5.235-6.088-5.235-2.589 0-4.637.825-6.344 2.048l.484 3.3c1.621-1.251 3.47-2.162 5.49-2.162 1.707 0 2.845.854 2.845 2.305 0 1.593-1.08 2.475-3.812 3.442l-.882.342.342 4.523 2.076-.455.171-1.963z"]{
  d: path("M11.354 4.646a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708l6-6a.5.5 0 0 1 .708 0zM0 3a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H3a3 3 0 0 1-3-3V3zm5.5 1a1.5 1.5 0 1 0-3 0 1.5 1.5 0 0 0 3 0zm6.5 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z");
color: white!important;
transform: scale(2.5);
opacity: 01!important;
}
.gameIcon-1mDo1J{
  color: transparent;
}
/*forum thread overlap fix*/
.chatTarget-3H6mpC.container-3XgAHv.floating-3M3WeH{
  background: rgba(26, 26, 26, 0.9)!important;
  box-shadow: 0 0 15px rgb(0, 0, 0);
}
