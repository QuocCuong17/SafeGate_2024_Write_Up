<!DOCTYPE html>
<!-- saved from url=(0045)https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view -->
<html lang="vi" theme="dark"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="mobile-web-app-capable" content="yes">
<meta property="og:image" content="https://hackmd.io/images/media/HackMD-og.jpg">
<meta name="codeium:type" content="codemirror5">

<meta property="fb:app_id" content="1436904003272070">
 
<meta name="realtime-register-serverurl" content="https://hackmd.io/realtime-reg">

<meta name="csrf-token" content="rzEb1HnF-b552DtX3-Jzr4IDXG48oPEqychI">
<title>Lab #1: Excessive trust in client-side controls - HackMD</title>
<link rel="icon" type="image/png" href="https://hackmd.io/favicon.png">
<link rel="apple-touch-icon" href="https://hackmd.io/apple-touch-icon.png">
<link rel="preload" href="https://hackmd.io/offline-access/offline-access-description.svg" as="image">
<link rel="preload" href="https://hackmd.io/offline-access/cloud-slash.svg" as="image">

<script type="text/javascript" async="" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/analytics.js.tải xuống" nonce=""></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/cb=gapi.loaded_1" nonce="" async=""></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/cb=gapi(1).loaded_0" nonce="" async=""></script><script type="text/javascript" async="" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/js" nonce=""></script><script async="" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/gtm.js.tải xuống"></script><script nonce="">
  window.domain = 'hackmd.io'
  window.urlpath = ''
  window.debug = false
  window.version = '1.3.0'
  window.brand = 'HackMD'

  

  window.GOOGLE_DRIVE_API_KEY = 'AIzaSyAHmcP5gL_64ZafuAYOvJruFAIaYgHQaY4'
  window.GOOGLE_DRIVE_CLIENT_ID = '65857506266-76uhhee8se8dgs1i0q8fhtj1prg0ar27.apps.googleusercontent.com'
  window.DROPBOX_APP_KEY = 'rdoizrlnkuha23r'
  
  window.PLANTUML_SERVER = 'https://ptuml.hackmd.io'

  window.ASSET_URL = 'https://assets.hackmd.io'

  window.USER_CAN_CREATE_TEAM = true
  window.USER_CAN_DELETE_ACCOUNT = true
  window.USER_DELETE_ACCOUNT_VIA_EMAIL = true
  window.PAYMENT_ENABLED = true
  window.PAYMENT_PROMOTION_BANNER_ENABLED = false
  window.GITHUB_SYNC_ENABLED = true
  window.GITLAB_SYNC_ENABLED = false
  window.GITLAB_SYNC_BASE_URL = ''
  window.VCS_SYNC_MODE = 'github'
  window.VCS_PROVIDER_NAME = 'GitHub'
  window.FREE_TEAM_NUM = 20
  window.FREE_TEAM_MEMBER_NUM = 3
  window.FREE_PUBLIC_TEAM_NUM = 10
  
  window.EE_SITE_ENABLE = false
  window.EE_SITE_NAME = 'false'
  window.EE_SITE_LINK = 'false'
  window.EESITE_INFO = false
  window.ENTERPRISE_DISCOVERY_ENABLE = false
  window.ENTERPRISE_DISCOVERY_TEAM = true
  window.ENTERPRISE_DISCOVERY_NOTE = true
  window.ENTERPRISE_DISCOVERY_VIEW_PERMISSION = 'guest'
  
  window.ALLOW_ANONYMOUS = true
  window.ALLOW_ANONYMOUS_EDIT = false
  window.ALLOW_DOWNLOAD_PDF = true
  window.PUBLIC_OVERVIEW = false
  window.INTERNAL_PUBLIC_OVERVIEW = false
  window.FULL_TEXT_SEARCH_ENABLE = false
  window.ALGOLIA_SEARCH_ENABLE = true
  window.MARKETING_EMAIL_ENABLE = true
  window.OFFLINE_ACCESS = true
  
  window.ARWEAVE_ENABLE = true
  
  
  
    window.WALLET_CONNECT_PROJECT_ID = '91d6fa182b725b5895a17a170a5878c1'
  
  window.API_MANAGEMENT_UI_ENABLE = true
  window.FEEDBACK_UI_ENABLE = true
  window.PUBLISH_ENABLE = true

  

  

  

  
  window.SHOW_OVERVIEW = true
  

  

  

  

  
  window.IS_OWNER = true
  

  
  window.IS_TEAM_ADMIN = 
  

  
  window.IS_INVITEE_ADMIN = false
  

  

  

  
  window.canEdit = true
  

  

  

  window.TRASH_NOTE_DELETE_AFTER_FREE = 3
  window.TRASH_NOTE_DELETE_AFTER_PAID = 30

  

  
    window.IS_OWNER_UPGRADED = false
  

  
    window.IMGUR_FALLBACK_CDN = 'https://imgur-backup.hackmd.io'
  

  
    window.CLOUD_META_UI = true
  
  
    window.CLOUD_META_API = true
  
  
    window.CLOUD_META_MIGRATION = false
  
  
    window.YAML_METADATA_ENABLED = false
  

  
    window.NOTE_CAPACITY_LIMIT = 50
  

  
    window.DOCUMENT_MAX_LENGTH = 100000
  

  
    window.SOCIAL_NETWORK_FEATURES_ENABLED = true
  

  
    window.PUBLISHMENT_MODERATION_ENABLED = true
  

  

  window.SUGGEST_EDIT_ENABLED = true
  

  
    window.REALTIME_CLIENT_WITH_CREDENTIALS = false
  

  

  
    window.DEBUG_DISCONNECT_SOCKET_WHEN_OFFLINE = false
  

  

  

  
    window.USE_NEW_LOGO = false
  
</script>



<!-- Google Tag Manager -->
<script nonce="">(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-KLW9Z3');</script>
<!-- End Google Tag Manager -->


 <link href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/font-vendor.ea8218d7d4f468b2c430.css" rel="stylesheet"><link href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/common-vendor.0a08ae20e14fefe857eb.css" rel="stylesheet"><link href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/index-vendor.3773b3818032440d1806.css" rel="stylesheet"><link href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/index.06da1f419ac6d204b2e7.css" rel="stylesheet">
<!-- style-loader will insert style before this div in development -->
<!-- This prevents overwriting reveal.js theme css -->
<meta id="style-tag-insertion">
<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
<!--[if lt IE 9]>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js" integrity="sha256-3Jy/GbSLrg0o9y5Z5n1uw0qxZECH7C6OQpVBgNFYa0g=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js" integrity="sha256-g6iAfvZp+nDQ2TdTR/VVKJf3bGro4ub5fvWSWVRi2NE=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/es5-shim/4.5.9/es5-shim.min.js" integrity="sha256-8E4Is26QH0bD52WoQpcB+R/tcWQtpzlCojrybUd7Mxo=" crossorigin="anonymous"></script>
<![endif]-->
 

 <script defer="" data-domain="hackmd.io" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/script.js.tải xuống"></script>
<script nonce="">
  window.plausible = window.plausible || function() { (window.plausible.q = window.plausible.q || []).push(arguments); }
  const keyboardWhiteList = ['a', 'span', 'button']

  function getTaggedEventAttributes (e) {
    const eventAttrs = { name: null, props: {} }
    if (!e || !e.classList) return eventAttrs
    const psEvent = /plausible-event-(.+)(=|--)(.+)/
    for (const className of [...e.classList]) {
      const [, key, , val] = className.match(psEvent) || []
      if (!key || !val) continue
      const value = val.replace(/\+/g, ' ')
      switch (key.toLowerCase()) {
        case 'name':
          eventAttrs.name = value
          break
        default:
          eventAttrs.props[key] = value
          break
      }
    }
    return eventAttrs
  }

  function isLocal () {
    return /^localhost$|^127(\.[0-9]+){0,2}\.[0-9]+$|^\[::1?\]$/.test(location.hostname) || location.protocol === 'file:'
  }

  function isAutomation () {
    return Boolean(window._phantom || window.__nightmare || window.navigator.webdriver || window.Cypress)
  }

  function shouldIgnore () {
    return isLocal() ||
      isAutomation() ||
      window.localStorage.getItem('plausible_ignore') === 'true'
  }

  function handler (e) {
    if (!window.plausible) return
    if (!e.target || !('className' in e.target)) return
    const ele = e.target

    const eventAttrs = getTaggedEventAttributes(ele)
    if (!eventAttrs.name) return
    if (ele?.href) eventAttrs.props.url = ele.href

    if (shouldIgnore()) {
      if (window.debug) {
        console.warn(
          `Ignoring Event: "${eventAttrs.name}"`,
          { props: eventAttrs.props },
        )
      }
      return
    }
    window.plausible(eventAttrs.name, { props: eventAttrs.props })
  }

  function keydownHandler (e) {
    if (e.key !== 'Enter') return
    if (e.target.nodeName.toLowerCase() === 'input') {
      switch (e.target.type.toLowerCase()) {
        case 'submit':
        case 'button':
        case 'reset':
        case 'checkbox':
        case 'radio':
        case 'file':
        case 'image':
        case 'color':
          break
        default:
          return
      }
    } else if (!keyboardWhiteList.includes(e.target.nodeName.toLowerCase())) {
      return
    }
    handler(e)
  }

  document.addEventListener('mousedown', handler)
  document.addEventListener('keydown', keydownHandler)
</script>


    <script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/embed.js.tải xuống"></script><style type="text/css">@keyframes index-module_spin__r2-rl{0%{transform:rotate(0deg)}to{transform:rotate(1turn)}}@keyframes index-module_wave__JTStX{0%{transform:rotate(0deg)}50%{transform:rotate(20deg)}to{transform:rotate(0deg)}}@keyframes index-module_heartBeat__Jdux6{0%{transform:scale(1)}50%{transform:scale(1.08)}to{transform:scale(1)}}@keyframes index-module_flash__BHax5{0%,50%,to{opacity:1}25%,75%{opacity:.2}}@keyframes index-module_bounce__46Q2t{0%,20%,53%,to{transform:translateZ(0)}40%,43%{transform:translate3d(0,-30px,0) scaleY(1.1)}70%{transform:translate3d(0,-15px,0) scaleY(1.05)}80%{transform:translateZ(0) scaleY(.95)}90%{transform:translate3d(0,-4px,0) scaleY(1.02)}}@keyframes index-module_rubberBand__QnP44{0%{transform:scaleX(1)}30%{transform:scale3d(1.25,.75,1)}40%{transform:scale3d(.75,1.25,1)}50%{transform:scale3d(1.15,.85,1)}65%{transform:scale3d(.95,1.05,1)}75%{transform:scale3d(1.05,.95,1)}to{transform:scaleX(1)}}@keyframes index-module_headShake__4JK7O{0%{transform:translateX(0)}6.5%{transform:translateX(-6px) rotateY(-9deg)}18.5%{transform:translateX(5px) rotateY(7deg)}31.5%{transform:translateX(-3px) rotateY(-5deg)}43.5%{transform:translateX(2px) rotateY(3deg)}50%{transform:translateX(0)}}@keyframes index-module_tada__m5Cd2{0%{transform:scaleX(1)}10%,20%{transform:scale3d(.9,.9,.9) rotate(-3deg)}30%,50%,70%,90%{transform:scale3d(1.1,1.1,1.1) rotate(3deg)}40%,60%,80%{transform:scale3d(1.1,1.1,1.1) rotate(-3deg)}to{transform:scaleX(1)}}.index-module_overlay__PyXAN{-ms-flex-pack:center;-ms-flex-align:center;align-items:center;background-color:hsla(0,0%,6%,.6);bottom:0;display:-ms-flexbox;display:flex;justify-content:center;left:0;position:fixed;right:0;top:0;z-index:1000000006}.index-module_layoutDefault__7yBRe{bottom:20px;position:fixed;right:20px;width:auto}.index-module_layoutDefault__7yBRe,.index-module_layoutModal__3-Tik{background-color:transparent;border-radius:5px;box-shadow:0 0 0 1px hsla(0,0%,6%,.05),0 3px 6px hsla(0,0%,6%,.1),0 9px 24px hsla(0,0%,6%,.2);display:-ms-flexbox;display:flex;height:auto;max-width:95vw;opacity:0;z-index:2147483000}.index-module_layoutModal__3-Tik{position:relative;width:700px}.index-module_popupContainer__R7hrk{border-radius:5px;display:-ms-flexbox;display:flex;overflow-y:auto;width:100%}.index-module_popupContainer__R7hrk iframe{border-radius:5px;max-height:95vh}.index-module_loadingIndicator__bai61{-ms-flex-align:center;-ms-flex-pack:center;align-items:center;background-color:#f5f5f5;border-radius:50%;color:#444;display:-ms-inline-flexbox;display:inline-flex;height:50px;justify-content:center;position:absolute;width:50px;z-index:2147483000}.index-module_loadingIndicatorNoOverlay__Pyhdd{bottom:10px;position:fixed;right:10px}.index-module_loadingIndicator__bai61 svg{animation:index-module_spin__r2-rl 1.618s linear infinite;height:20px;width:20px}.index-module_emoji__MDuRJ{display:inline-block;font-size:42px;left:-21px;line-height:1;position:absolute;top:-21px}.index-module_animate__wave__Rfv7x{animation:index-module_wave__JTStX 1s ease-in-out 20}.index-module_animate__heart-beat__M8Vjv{animation:index-module_heartBeat__Jdux6 1.3s ease-in-out 20}.index-module_animate__flash__zfXXt{animation:index-module_flash__BHax5 2.5s 20}.index-module_animate__bounce__YkmGJ{animation:index-module_bounce__46Q2t 1.5s 20;-ms-transform-origin:center bottom;transform-origin:center bottom}.index-module_animate__rubber-band__o0ymG{animation:index-module_rubberBand__QnP44 1.5s 20}.index-module_animate__head-shake__SgYWR{animation:index-module_headShake__4JK7O 1.5s ease-in-out 20}.index-module_animate__tada__3dUYE{animation:index-module_tada__m5Cd2 1.5s 20}.index-module_animate__spin__dJxXR{animation:index-module_spin__r2-rl 1.618s linear 20}@media (max-height:1000px){.index-module_popupContainer__R7hrk iframe{max-height:85vh}}@media (max-width:576px){.index-module_popupContainer__R7hrk iframe{max-height:70vh}.index-module_layoutDefault__7yBRe,.index-module_layoutModal__3-Tik{max-width:calc(100% - 40px)}}</style>
<style id="googleidentityservice_button_styles" nonce="">.qJTHM{-webkit-user-select:none;color:#202124;direction:ltr;-webkit-touch-callout:none;font-family:"Roboto-Regular",arial,sans-serif;-webkit-font-smoothing:antialiased;font-weight:400;margin:0;overflow:hidden;-webkit-text-size-adjust:100%}.ynRLnc{left:-9999px;position:absolute;top:-9999px}.L6cTce{display:none}.bltWBb{word-break:break-all}.hSRGPd{color:#1a73e8;cursor:pointer;font-weight:500;text-decoration:none}.Bz112c-W3lGp{height:16px;width:16px}.Bz112c-E3DyYd{height:20px;width:20px}.Bz112c-r9oPif{height:24px;width:24px}.Bz112c-uaxL4e{-webkit-border-radius:10px;border-radius:10px}.LgbsSe-Bz112c{display:block}.S9gUrf-YoZ4jf,.S9gUrf-YoZ4jf *{border:none;margin:0;padding:0}.fFW7wc-ibnC6b>.aZ2wEe>div{border-color:#4285f4}.P1ekSe-ZMv3u>div:nth-child(1){background-color:#1a73e8!important}.P1ekSe-ZMv3u>div:nth-child(2),.P1ekSe-ZMv3u>div:nth-child(3){background-image:linear-gradient(to right,rgba(255,255,255,.7),rgba(255,255,255,.7)),linear-gradient(to right,#1a73e8,#1a73e8)!important}.haAclf{display:inline-block}.nsm7Bb-HzV7m-LgbsSe{-webkit-border-radius:4px;border-radius:4px;-webkit-box-sizing:border-box;box-sizing:border-box;-webkit-transition:background-color .218s,border-color .218s;transition:background-color .218s,border-color .218s;-webkit-user-select:none;-webkit-appearance:none;background-color:#fff;background-image:none;border:1px solid #dadce0;color:#3c4043;cursor:pointer;font-family:"Google Sans",arial,sans-serif;font-size:14px;height:40px;letter-spacing:0.25px;outline:none;overflow:hidden;padding:0 12px;position:relative;text-align:center;vertical-align:middle;white-space:nowrap;width:auto}@media screen and (-ms-high-contrast:active){.nsm7Bb-HzV7m-LgbsSe{border:2px solid windowText;color:windowText}}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe{font-size:14px;height:32px;letter-spacing:0.25px;padding:0 10px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe{font-size:11px;height:20px;letter-spacing:0.3px;padding:0 8px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe{padding:0;width:40px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.pSzOP-SxQuSe{width:32px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.purZT-SxQuSe{width:20px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK{-webkit-border-radius:20px;border-radius:20px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK.pSzOP-SxQuSe{-webkit-border-radius:16px;border-radius:16px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK.purZT-SxQuSe{-webkit-border-radius:10px;border-radius:10px}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc{border:none;color:#fff}.nsm7Bb-HzV7m-LgbsSe.MFS4be-v3pZbf-Ia7Qfc{background-color:#1a73e8}.nsm7Bb-HzV7m-LgbsSe.MFS4be-JaPV2b-Ia7Qfc{background-color:#202124;color:#e8eaed}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:18px;margin-right:8px;min-width:18px;width:18px}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:14px;min-width:14px;width:14px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:10px;min-width:10px;width:10px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin-left:8px;margin-right:-4px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin:0;padding:10px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{padding:8px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{padding:4px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-top-left-radius:3px;border-top-left-radius:3px;-webkit-border-bottom-left-radius:3px;border-bottom-left-radius:3px;display:-webkit-box;display:-webkit-flex;display:flex;justify-content:center;-webkit-align-items:center;align-items:center;background-color:#fff;height:36px;margin-left:-10px;margin-right:12px;min-width:36px;width:36px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf .nsm7Bb-HzV7m-LgbsSe-Bz112c,.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin:0;padding:0}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{height:28px;margin-left:-8px;margin-right:10px;min-width:28px;width:28px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{height:16px;margin-left:-6px;margin-right:8px;min-width:16px;width:16px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-radius:3px;border-radius:3px;margin-left:2px;margin-right:0;padding:0}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-radius:18px;border-radius:18px}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-radius:14px;border-radius:14px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-radius:8px;border-radius:8px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-bN97Pc-sM5MNb{display:-webkit-box;display:-webkit-flex;display:flex;-webkit-align-items:center;align-items:center;-webkit-flex-direction:row;flex-direction:row;justify-content:space-between;-webkit-flex-wrap:nowrap;flex-wrap:nowrap;height:100%;position:relative;width:100%}.nsm7Bb-HzV7m-LgbsSe .oXtfBe-l4eHX{justify-content:center}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-BPrWId{-webkit-flex-grow:1;flex-grow:1;font-family:"Google Sans",arial,sans-serif;font-weight:500;overflow:hidden;text-overflow:ellipsis;vertical-align:top}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-BPrWId{font-weight:300}.nsm7Bb-HzV7m-LgbsSe .oXtfBe-l4eHX .nsm7Bb-HzV7m-LgbsSe-BPrWId{-webkit-flex-grow:0;flex-grow:0}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-MJoBVe{-webkit-transition:background-color .218s;transition:background-color .218s;bottom:0;left:0;position:absolute;right:0;top:0}.nsm7Bb-HzV7m-LgbsSe:hover,.nsm7Bb-HzV7m-LgbsSe:focus{-webkit-box-shadow:none;box-shadow:none;border-color:#d2e3fc;outline:none}.nsm7Bb-HzV7m-LgbsSe:hover .nsm7Bb-HzV7m-LgbsSe-MJoBVe,.nsm7Bb-HzV7m-LgbsSe:focus .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(66,133,244,.04)}.nsm7Bb-HzV7m-LgbsSe:active .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(66,133,244,.1)}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:hover .nsm7Bb-HzV7m-LgbsSe-MJoBVe,.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:focus .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.24)}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:active .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.32)}.nsm7Bb-HzV7m-LgbsSe .n1UuX-DkfjY{-webkit-border-radius:50%;border-radius:50%;display:-webkit-box;display:-webkit-flex;display:flex;height:20px;margin-left:-4px;margin-right:8px;min-width:20px;width:20px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId{font-family:"Roboto";font-size:12px;text-align:left}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .ssJRIf,.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff .fmcmS{overflow:hidden;text-overflow:ellipsis}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{display:-webkit-box;display:-webkit-flex;display:flex;-webkit-align-items:center;align-items:center;color:#5f6368;fill:#5f6368;font-size:11px;font-weight:400}.nsm7Bb-HzV7m-LgbsSe.jVeSEe.MFS4be-Ia7Qfc .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{color:#e8eaed;fill:#e8eaed}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff .Bz112c{height:18px;margin:-3px -3px -3px 2px;min-width:18px;width:18px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-top-left-radius:0;border-top-left-radius:0;-webkit-border-bottom-left-radius:0;border-bottom-left-radius:0;-webkit-border-top-right-radius:3px;border-top-right-radius:3px;-webkit-border-bottom-right-radius:3px;border-bottom-right-radius:3px;margin-left:12px;margin-right:-10px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{-webkit-border-radius:18px;border-radius:18px}.L5Fo6c-sM5MNb{border:0;display:block;left:0;position:relative;top:0}.L5Fo6c-bF1uUb{-webkit-border-radius:4px;border-radius:4px;bottom:0;cursor:pointer;left:0;position:absolute;right:0;top:0}.L5Fo6c-bF1uUb:focus{border:none;outline:none}sentinel{}</style><style type="text/css"></style><style></style><style></style><style type="text/css">.hljs-ln{border-collapse:collapse}.hljs-ln td{padding:0}.hljs-ln-n:before{content:attr(data-line-number)}</style><style>.--savior-overlay-transform-reset {
  transform: none !important;
}
.--savior-overlay-z-index-top {
  z-index: 2147483643 !important;
}
.--savior-overlay-position-relative {
  position: relative;
}
.--savior-overlay-position-static {
  position: static !important;
}
.--savior-overlay-overflow-hidden {
  overflow: hidden !important;
}
.--savior-overlay-overflow-x-visible {
  overflow-x: visible !important;
}
.--savior-overlay-overflow-y-visible {
  overflow-y: visible !important;
}
.--savior-overlay-z-index-reset {
  z-index: auto !important;
}
.--savior-overlay-display-none {
  display: none !important;
}
.--savior-overlay-clearfix {
  clear: both;
}
.--savior-overlay-reset-filter {
  filter: none !important;
  backdrop-filter: none !important;
}
.--savior-tooltip-host {
  z-index: 9999;
  position: absolute;
  top: 0;
}
/*Override css styles for Twitch.tv*/
main.--savior-overlay-z-index-reset {
  z-index: auto !important;
}
.modal__backdrop.--savior-overlay-z-index-reset {
  position: static !important;
}
main.--savior-overlay-z-index-top {
  z-index: auto !important;
}
main.--savior-overlay-z-index-top .channel-root__player-container + div,
main.--savior-overlay-z-index-top .video-player-hosting-ui__container + div {
  opacity: 0.1;
}
/*Dirty hack for facebook big video page e.g: https://www.facebook.com/abc/videos/...*/
.--savior-backdrop {
  position: fixed !important;
  z-index: 2147483642 !important;
  top: 0;
  left: 0;
  height: 100vh;
  width: 100vw !important;
  background-color: rgba(0,0,0,0.9);
}
.--savior-overlay-twitter-video-player {
  position: fixed;
  width: 80%;
  height: 80%;
  top: 10%;
  left: 10%;
}
.--savior-overlay-z-index-reset [class*="DivSideNavContainer"],
.--savior-overlay-z-index-reset [class*="DivHeaderContainer"],
.--savior-overlay-z-index-reset [class*="DivBottomContainer"],
.--savior-overlay-z-index-reset [class*="DivCategoryListWrapper"],
.--savior-overlay-z-index-reset [data-testid="sidebarColumn"],
.--savior-overlay-z-index-reset header[role="banner"],
.--savior-overlay-z-index-reset [data-testid="cellInnerDiv"]:not(.--savior-overlay-z-index-reset),
.--savior-overlay-z-index-reset [aria-label="Home timeline"]>div:first-child,
.--savior-overlay-z-index-reset [aria-label="Home timeline"]>div:nth-child(3) {
  z-index: -1 !important;
}
.--savior-overlay-z-index-reset [data-testid="cellInnerDiv"] .--savior-backdrop+div {
  z-index: 2147483643 !important;
}
.--savior-overlay-z-index-reset [data-testid="primaryColumn"]>[aria-label="Home timeline"] {
  z-index: 0 !important;
}
.--savior-overlay-z-index-reset#mtLayer,
.--savior-overlay-z-index-reset.media-layer {
  z-index: 3000 !important;
}
.--savior-overlay-position-relative [class*="SecBar_secBar_"],
.--savior-overlay-position-relative .woo-box-flex [class*="Frame_top_"] {
  z-index: 0 !important;
}
.--savior-overlay-position-relative .vue-recycle-scroller__item-view:not(.--savior-overlay-z-index-reset),
.--savior-overlay-position-relative .woo-panel-main[class*="BackTop_main_"],
.--savior-overlay-position-relative [class*="Main_side_"] {
  z-index: -1 !important;
}
/* Fix conflict css with zingmp3 */
.zm-video-modal.--savior-overlay-z-index-reset {
  position: absolute;
}
/* Dirty hack for xvideos99 */
#page #main.--savior-overlay-z-index-reset {
  z-index: auto !important;
}
/* Overlay for ok.ru */
#vp_w.--savior-overlay-z-index-reset.media-layer.media-layer__video {
  overflow-y: hidden;
  z-index: 2147483643 !important;
}
/* Fix missing controller for tv.naver.com */
.--savior-overlay-z-index-top.rmc_controller,
.--savior-overlay-z-index-top.rmc_setting_intro,
.--savior-overlay-z-index-top.rmc_highlight,
.--savior-overlay-z-index-top.rmc_control_settings {
  z-index: 2147483644 !important;
}
/* Dirty hack for douyi.com */
.swiper-wrapper.--savior-overlay-z-index-reset .swiper-slide:not(.swiper-slide-active),
.swiper-wrapper.--savior-overlay-transform-reset .swiper-slide:not(.swiper-slide-active) {
  display: none;
}
.videoWrap + div > div {
  pointer-events: unset;
}
/* Dirty hack for fpt.ai */
.mfp-wrap.--savior-overlay-z-index-top {
  position: relative;
}
.mfp-wrap.--savior-overlay-z-index-top .mfp-close {
  display: none;
}
.mfp-wrap.--savior-overlay-z-index-top .mfp-content {
  position: fixed;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
section.--savior-overlay-z-index-reset>main[role="main"].--savior-overlay-z-index-reset + nav {
  z-index: -1 !important;
}
section.--savior-overlay-z-index-reset>main[role="main"].--savior-overlay-z-index-reset section.--savior-overlay-z-index-reset div.--savior-overlay-z-index-reset ~ div {
  position: relative;
}
.watching-movie #video-player.--savior-overlay-z-index-top {
  z-index: 2147483644 !important;
}
div[class^="tiktok"].--savior-overlay-z-index-reset {
  z-index: 2147483644 !important;
}
.--savior-lightoff-fix section:not(:has([class*="--savior-overlay-"])),
.--savior-lightoff-fix section.section_video ~ section {
  z-index: -1;
  position: relative;
}
.--savior-lightoff-fix header,
.--savior-lightoff-fix footer,
.--savior-lightoff-fix .top-header,
.--savior-lightoff-fix .swiper-container,
.--savior-lightoff-fix #to_top,
.--savior-lightoff-fix #button-adblock {
  z-index: -1 !important;
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-o-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style><style nonce="">.picker-dialog-frame{width:100%;height:100%;border:0;overflow:hidden}.picker-dialog-bg{position:absolute;top:0;left:0;background-color:#fff;z-index:1000}.picker-dialog{position:absolute;top:0;left:0;background-color:#fff;border:1px solid #acacac;width:auto;padding:0;z-index:1001;overflow:auto;box-shadow:0 4px 16px rgba(0,0,0,.2)}.picker-dialog-content{font-size:0;padding:0}.picker-dialog-buttons,.picker-dialog-title{display:none}</style><style type="text/css">  @-webkit-keyframes rotate {
    from  { -webkit-transform: rotate(0deg); }
    to   { -webkit-transform: rotate(360deg); }
  }

  @keyframes rotate {
    from  { transform: rotate(0deg); }
    to   { transform: rotate(360deg); }
  }

    .dropbox-dropin-btn, .dropbox-dropin-btn:link, .dropbox-dropin-btn:hover {
      display: inline-block;
      height: 14px;
      font-family: "Lucida Grande", "Segoe UI", "Tahoma", "Helvetica Neue", "Helvetica", sans-serif;
      font-size: 11px;
      font-weight: 600;
      color: #636363;
      text-decoration: none;
      padding: 1px 7px 5px 3px;
      border: 1px solid #ebebeb;
      border-radius: 2px;
      border-bottom-color: #d4d4d4;
        background: #fcfcfc;
  background: -moz-linear-gradient(top, #fcfcfc 0%, #f5f5f5 100%);
  background: -webkit-linear-gradient(top, #fcfcfc 0%, #f5f5f5 100%);
  background: linear-gradient(to bottom, #fcfcfc 0%, #f5f5f5 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fcfcfc', endColorstr='#f5f5f5',GradientType=0);  
    }

    .dropbox-dropin-default:hover, .dropbox-dropin-error:hover {
      border-color: #dedede;
      border-bottom-color: #cacaca;
        background: #fdfdfd;
  background: -moz-linear-gradient(top, #fdfdfd 0%, #f5f5f5 100%);
  background: -webkit-linear-gradient(top, #fdfdfd 0%, #f5f5f5 100%);
  background: linear-gradient(to bottom, #fdfdfd 0%, #f5f5f5 100%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#fdfdfd', endColorstr='#f5f5f5',GradientType=0);  
    }

    .dropbox-dropin-default:active, .dropbox-dropin-error:active {
      border-color: #d1d1d1;
      box-shadow: inset 0 1px 1px rgba(0,0,0,0.1);
    }

    .dropbox-dropin-btn .dropin-btn-status {
      display: inline-block;
      width: 15px;
      height: 14px;
      vertical-align: bottom;
      margin: 0 5px 0 2px;
      background: transparent url('https://www.dropbox.com/static/metaserver/static/images/widgets/dbx-saver-status.png') no-repeat;
      position: relative;
      top: 2px;
    }

    .dropbox-dropin-default .dropin-btn-status {
      background-position: 0px 0px;
    }

    .dropbox-dropin-progress .dropin-btn-status {
      width: 18px;
      margin: 0 4px 0 0;
      background: url('https://www.dropbox.com/static/metaserver/static/images/widgets/dbx-progress.png') no-repeat center center;
        -webkit-animation-name: rotate;
        -webkit-animation-duration: 1.7s;
        -webkit-animation-iteration-count: infinite;
        -webkit-animation-timing-function: linear;
      animation-name: rotate;
      animation-duration: 1.7s;
      animation-iteration-count: infinite;
      animation-timing-function: linear;
    }

    .dropbox-dropin-success .dropin-btn-status {
      background-position: -15px 0px;
    }

    .dropbox-dropin-disabled {
      background: #e0e0e0;
      border: 1px #dadada solid;
      border-bottom: 1px solid #ccc;
      box-shadow: none;
    }

    .dropbox-dropin-disabled .dropin-btn-status {
      background-position: -30px 0px;
    }

    .dropbox-dropin-error .dropin-btn-status {
      background-position: -45px 0px;
    }

  @media only screen and (-webkit-min-device-pixel-ratio: 1.4) {
      .dropbox-dropin-btn .dropin-btn-status {
        background-image: url('https://www.dropbox.com/static/metaserver/static/images/widgets/dbx-saver-status-2x.png');
        background-size: 60px 14px;
          -webkit-background-size: 60px 14px;
      }

      .dropbox-dropin-progress .dropin-btn-status {
        background: url('https://www.dropbox.com/static/metaserver/static/images/widgets/dbx-progress-2x.png') no-repeat center center;
        background-size: 20px 20px;
          -webkit-background-size: 20px 20px;
      }
  }

    .dropbox-saver:hover, .dropbox-chooser:hover {
      text-decoration: none;
      cursor: pointer;
    }

    .dropbox-chooser, .dropbox-dropin-btn {
      line-height: 11px !important;
      text-decoration: none !important;
      box-sizing: content-box !important;
        -webkit-box-sizing: content-box !important;
        -moz-box-sizing: content-box !important;
    }
    </style><link id="googleidentityservice" type="text/css" media="all" rel="stylesheet" href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/style"><link rel="stylesheet" type="text/css" href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/fretboard.7a98c97ae43fb8ca354b.css"></head>

<body style="transition: transform 0.8s ease 0s; padding-top: 50.8px;" data-view-theme="light" class="">
    













<nav class="navbar navbar-default navbar-fixed-top unselectable hidden-print">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header hmd-navbar-header">
        
        <a class="navbar-brand pull-left !text-icon-emphasize font-brand-headline" style="float: left;" href="https://hackmd.io/">
            
            <i class="fa fa-file-text align-middle" aria-hidden="true"></i>
            
            <span class="hidden-xs align-middle"> HackMD</span>
        </a>
        

        <div id="nav-mobile-note-title" class="nav-mobile font-system"></div>

        
        

        <ul class="nav-mobile pull-right mobile-extra-menu">
            <li>
                
                    <a class="btn side-menu-button ui-guest-signin-tooltip ml-1.5 p-1.5 h-7.5 w-7.5 leading-sm">
                
                    <i class="ph ph-list"></i>
                </a>
            </li>
        </ul>
        <ul class="nav-mobile pull-right mobile-user-profile">
            <li class="ui-status-offline-mobile-portal mr-1.5" style="display: none;"><button class="p-0 m-0 border-none text-5 leading-[20px] ui-note-status-icon btn ml-1.5 bg-transparent px-2.5 py-1.5 hover:bg-gray-200 focus:bg-gray-200"></button></li>
            <li id="short-online-user-list" class="ui-host-list" style="">
                <button class="ui-short-status btn ml-1.5 online bg-transparent text-text-emphasize" data-toggle="dropdown"><i class="ph ph-users-three"></i><span class="ml-1">1</span><i class="ph ph-caret-down ml-1.5"></i></button>
                <ul class="dropdown-menu list" role="menu" aria-labelledby="menu"><li class="dropdown-header">Choose a user to host</li><li class="ui-user-item upgraded" data-upgraded="false" style="border-left: 4px solid rgb(193, 19, 13);"><span class="id" style="display:none;">UbkKg51gaJl8A06sASww</span><a class="ui-user-profile" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"><span class="pull-left"><img class="ui-user-icon user-card-popover" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085" data-toggle="popover" data-original-title="" title=""></span><span class="ui-user-name name">Cường17</span><button class="btn btn-outline btn-primary ui-host" style=""><span class="host-text">Host</span><span class="cancel-host-text">Cancel</span><span class="hosting-text"><i class="ui-live-circle" style="font-size: 12px;"></i>&nbsp;Live</span></button><span class="pull-right flex"><i class="ph-fill ph-circle ui-user-status ui-user-status-online"></i></span></a></li></ul>
            </li>
            <li>
                <a class="ui-mode btn ml-1.5 p-1.5 h-7.5 w-7.5 leading-sm border-border-default">
                    <i class="ph ph-pencil-simple"></i>
                </a>
            </li>
            <li>
                <a class="ui-share btn ml-1.5 p-1.5 h-7.5 w-7.5 leading-sm bg-background-primary-default hover:!bg-background-primary-hover focus:!bg-background-primary-focus signin" sidenav-target="sidenav-permission" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
                    <i class="ph ph-share-network !text-white"></i>
                </a>
            </li>
        </ul>
    </div>
    <div class="hmd-navbar navbar-collapse">
        <nav class="nav mode-switch navbar-nav navbar-form navbar-left text-icon-default" style="padding-right: 14px;">
            <div class="btn-group p-0.5 space-x-0.5 border border-solid border-border-default rounded" data-toggle="buttons">
                <label class="btn ui-edit !shadow-none !rounded p-1.5 h-7.5 hocus:!text-icon-default [&amp;.focus]:!text-icon-default hocus:bg-element-bg-hover [&amp;.active]:bg-element-bg-hover" title="Edit (Ctrl+Alt+E)" aria-label="Edit">
                    <input type="radio" name="mode" autocomplete="off"><i class="ph ph-pencil-simple"></i>
                </label>
                <label class="btn ui-both !shadow-none !rounded p-1.5 h-7.5 hocus:!text-icon-default [&amp;.focus]:!text-icon-default hocus:bg-element-bg-hover [&amp;.active]:bg-element-bg-hover" title="Both (Ctrl+Alt+B)" aria-label="Both">
                    <input type="radio" name="mode" autocomplete="off"><i class="ph ph-square-split-horizontal"></i>
                </label>
                <label class="btn ui-view !shadow-none !rounded p-1.5 h-7.5 hocus:!text-icon-default [&amp;.focus]:!text-icon-default hocus:bg-element-bg-hover [&amp;.active]:bg-element-bg-hover active" title="View (Ctrl+Alt+V)" aria-label="View">
                    <input type="radio" name="mode" autocomplete="off"><i class="ph ph-eye"></i>
                </label>
            </div>
        </nav>
        <ul class="nav action-group navbar-nav navbar-left">
            
            
            <li title="" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" class="mr-3.5" data-original-title="Create">
                <a class="rounded ui-new ui-new-note-menu navbar-button-icon" id="create-note-menu" href="https://hackmd.io/new" target="_blank" aria-label="Create new note" aria-haspopup="true" aria-expanded="false" tabindex="0" data-toggle="dropdown">
                    <i class="ph ph-plus"></i>
                </a>
                <ul class="dropdown-menu list" role="menu" aria-labelledby="create-note-menu">
                    <li role="presentation">
                        <a role="menuitem" class="ui-new" href="https://hackmd.io/new" target="_blank" tabindex="-1">
                            <i class="ph ph-plus"></i> Create new note
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-new-with-template" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target="#templateModal" tabindex="-1">
                            <i class="ph ph-file-image"></i> Create a note from template
                        </a>
                    </li>
                </ul>
            </li>
            
            
            <li title="" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" class="mr-3.5" data-original-title="Help">
                <a class="rounded ui-help navbar-button-icon" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target=".help-modal" aria-label="Help">
                    <i class="ph ph-question-mark"></i>
                </a>
            </li>

            
                <li id="spotlight-app" title="" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="Find notes (Cmd/Ctrl + Shift + P)"><a class="ui-spotlight navbar-button-icon rounded"><i class="ph ph-magnifying-glass"></i></a></li>
            
        </ul>

        
        

        
            
            <div id="nav-note-setting" class="nav navbar-nav h-full w-full selectable pointer-events-none flex justify-around items-center" data-workspace="My workspace"><div class="navbar-title h-full pointer-events-auto overflow-hidden flex justify-center items-center w-full px-5 gap-1"><div id="BJHUAU55A" class="m-0 text-text-default text-ellipsis whitespace-pre overflow-hidden inline-block font-semibold text-normal leading-normal flex-shrink-0" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="Lab #1: Excessive trust in client-side controls">Lab #1: Excessive trust in client-side controls</div><div id="HJlrLA855R" class="m-0 text-text-default text-[14px] leading-[16px] w-7 h-7 hover:bg-element-bg-hover rounded cursor-pointer flex justify-center items-center" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="Note settings"><i class="ph ph-info text-lg leading-sm" aria-hidden="true"></i></div><div class="cursor-pointer"><div id="S1ZrIC8qqA" class="m-0 text-text-default text-[14px] leading-[16px] flex justify-center items-center w-7 h-7 hover:bg-element-bg-hover rounded cursor-pointer" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="Add tags"><i class="ph ph-tag text-lg leading-sm" aria-hidden="true"></i></div><div class="invisible" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-12" data-state="closed"></div></div></div></div>
        

        <ul class="nav extra-menu navbar-nav navbar-right" style="margin-right: 16px;">
            <li class="ui-share-button mr-1.5" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="" title="">
                
                <button class="
                        ui-sharing signin btn px-2.5 py-[9px] !text-white leading-sm flex gap-1
                        bg-background-primary-default hover:!bg-background-primary-hover focus:!bg-background-primary-focus
                    " data-toggle="dropdown" tabindex="0">
                    <i class="ph ph-share-network !text-white"></i>
                    Share
                </button>
                

                <ul class="dropdown-menu list ui-share-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px;">
                    <li>
                        <!-- tabs -->
                        <ul class="flex list-none px-5">
                            <li>
                                <button class="bg-transparent border-0 border-border-bold text-text-subtle p-2 ui-share-tab-link border-b-1 !text-text-default">
                                    Share
                                </button>
                            </li>
                            <li>
                                <button class="bg-transparent border-0 border-border-bold text-text-subtle p-2 ui-publish-tab-link" style="">
                                    Publish
                                    <i class="ph-fill ph-globe-hemisphere-west hidden" aria-hidden="true"></i>
                                </button>
                            </li>
                        </ul>
                    </li>

                    <!-- divider -->
                    <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default mb-5"></li>

                    <!-- share tab -->
                    <li class="ui-share-tab">
                        <ul class="list-none pl-0">
                            
                                <li class="dropdown-header fill-username-banner" style="">
    Fill username to use a shorter link! <span style="white-space: nowrap;"><a href="https://hackmd.io/settings" target="_blank"><i class="fa fa-gear"></i> Settings</a></span>
</li>

                            
                            <li class="dropdown-header mb-1">
                                Sharing URL
                                <!-- <i
                                    class="ph-fill ph-question tooltip-align-left ui-first-menu-tooltip text-icon-subtle text-4"
                                    title="Share this note with below URL. Make sure your audience has the permission to access this note."
                                    data-toggle="tooltip"
                                    data-placement="bottom" data-offset="0,5"></i> -->
                                <span class="ui-share-msg" style="display: none;">
                                    Link copied
                                </span>
                            </li>
                            <li class="dropdown-header ui-share-domain" style="margin-bottom: 2px; word-break: break-all; overflow: hidden; text-overflow: ellipsis;" title="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/">https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/</li>
                            <li class="input-group" style="padding: 0px 20px;">
                                <input type="text" class="form-control ui-share-field mr-1" maxlength="200" placeholder="BydS9N55A" style="height: 28px; font-size: 13px;">
                                <div class="ui-share-edit-mode" style="position: absolute; z-index: 10; font-size: 13px; top: 5px; right: 104px; display: none;">/edit</div>
                                <span class="input-group-btn">
                                    <button class="btn ui-share-copy !ml-1" type="button" data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">Copy</button>
                                </span>
                                <span class="input-group-btn" style="display: none">
                                    <button class="btn ui-share-save !ml-1" type="button">Save</button>
                                </span>
                            </li>

                            <li class="hmd-flex hmd-justify-end hmd-items-center" style="padding: 0 20px; margin-top: 10px;">
                                <div class="hmd-flex hmd-flex-one hmd-items-center ui-publish-type">
                                    <div class="hmd-flex-one">
                                        <div class="dropdown menuitem-dropdown">
                                            <div class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                                <span class="ui-publish-type-label">
                                                        <i class="ph ph-eye" aria-hidden="true"></i> View mode
                                                    </span>
                                                <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                            </div>

                                            <ul class="dropdown-menu" role="menu">
                                                <li role="presentation">
                                                    <a role="menuitem" class="menuitem-item ui-mode-edit" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                                                        <i class="ph ph-pencil-simple" aria-hidden="true"></i> Edit mode
                                                    </a>
                                                </li>
                                                <li role="presentation">
                                                    <a role="menuitem" class="menuitem-item ui-mode-view" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                                                        <i class="ph ph-eye" aria-hidden="true"></i> View mode
                                                    </a>
                                                </li>
                                                <li role="presentation">
                                                    <a role="menuitem" class="menuitem-item ui-mode-book" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                                                        <i class="ph ph-book" aria-hidden="true"></i> Book mode
                                                    </a>
                                                </li>
                                                <li role="presentation">
                                                    <a role="menuitem" class="menuitem-item ui-mode-slide" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                                                        <i class="ph ph-monitor" aria-hidden="true"></i> Slide mode
                                                    </a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>

                                    <i class="ph-fill ph-question tooltip-align-left ui-first-menu-tooltip !text-icon-subtle text-4 p-1.5" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="Note owner decides who can read or write this note."></i>
                                </div>

                                <div class="permission-item-badge permission-item-readonly ui-publish-type-badge mr-1.5" style="display: none;">
                                    <span name="edit" style="display: none;"><i class="ph ph-pencil-simple" aria-hidden="true"></i> Edit mode</span>
                                    <span name="view" style=""><i class="ph ph-eye" aria-hidden="true"></i> View mode</span>
                                    <span name="book" style="display: none;"><i class="ph ph-book" aria-hidden="true"></i> Book mode</span>
                                    <span name="slide" style="display: none;"><i class="ph ph-monitor" aria-hidden="true"></i> Slide mode</span>
                                </div>
                                <div>
                                    <button class="btn ui-share-preview" type="button">Preview</button>
                                </div>
                            </li>

                            
                            <li role="presentation" class="flex justify-center mt-2 mx-5">
                                <div class="ui-publish-slide-options cursor-pointer" style="display: none;">
                                    <span>Customize slides</span>
                                    <i class="ph ph-caret-right"></i>
                                </div>
                            </li>
                            

                            <!-- divider -->
                            <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-4"></li>

                            <li class="dropdown-header" style="margin-bottom: 7px;">
                                Note Permission

                                <!-- <i class="ph-fill ph-question text-icon-subtle text-4 tooltip-align-left ui-first-menu-tooltip"
                                title="Note owner decides who can read or write this note."
                                    data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->
                            </li>
                            <li role="presentation" style="margin-bottom: 10px;">
                                <div class="hmd-flex" style="padding: 0 20px; height: 26px;">
                                    <span class="hmd-flex-one">
                                        <div style="display: table; width: 100%; height: 100%;">
                                            <div style="display: table-cell; vertical-align: middle;">
                                                Read
                                            </div>
                                        </div>
                                    </span>
                                    <div class="hmd-flex-two ui-note-read">
                                        <div>
                                            <div class="dropdown menuitem-dropdown">
                                                <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                                    <span class="ui-note-read-label">Only me</span>
                                                    <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                                </button>

                                                <ul class="dropdown-menu" role="menu">
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Only me</a></li>
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-signed_in_users" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-everyone" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Everyone</a></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="permission-item-badge permission-item-readonly" style="display: none;" name="read">
                                        <span name="owners" style="">Only me</span>
                                        <span name="signed_in_users" style="display: none;">Signed-in users</span>
                                        <span name="everyone" style="display: none;">Everyone</span>
                                    </div>
                                </div>
                            </li>
                            <li role="presentation" style="margin-bottom: 10px;">
                                <div style="display: flex; padding: 0 20px; height: 26px;">
                                    <span style="flex: 1;">
                                        <div style="display: table; width: 100%; height: 100%;">
                                            <div style="display: table-cell; vertical-align: middle;">
                                                Write
                                            </div>
                                        </div>
                                    </span>
                                    <div style="flex: 2" class="ui-note-write">
                                        <div>
                                            <div class="dropdown menuitem-dropdown">
                                                <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                                    <span class="ui-note-write-label">Only me</span>
                                                    <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                                </button>
                                                <ul class="dropdown-menu" role="menu">
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Only me</a></li>
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-signed_in_users disabled" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-everyone disabled" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Everyone</a></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="permission-item-badge permission-item-readonly" style="display: none;" name="write">
                                        <span name="owners" style="">Only me</span>
                                        <span name="signed_in_users" style="display: none;">Signed-in users</span>
                                        <span name="everyone" style="display: none;">Everyone</span>
                                    </div>
                                </div>
                            </li>

                            <div class="px-5 my-2 font-semibold permission-notice">
                                <small class="text-text-subtle font-medium">Private: only you can read and write.</small>
                            </div>

                            <!-- more features button -->
                            
                                <li role="presentation">
                                    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="ui-more-settings !block px-5">
                                        <div class="note-permission-button">
                                            <span class="flex flex-col">
                                                <span class="text-[16px] leading-[135%] font-semibold text-text-emphasize">
                                                    More features
                                                </span>
                                                <span class="text-[13px] leading-[14px]">
                                                    
                                                        Commenting, 
                                                    
                                                    
                                                        Suggest edit
                                                    
                                                </span>
                                            </span>

                                            <i class="ph ph-caret-right"></i>
                                        </div>
                                    </a>
                                </li>
                            

                            <!-- invitee section -->
                            
                            <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-5"></li>

                            <li class="dropdown-header ui-invitee-label" style="padding-bottom: 9px; margin-top: 15px;">
                                Invitee

                                <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left ui-second-menu-tooltip"
                                title="Admin can invite users and change note permissions."
                                data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->
                            </li>
                            <li class="ui-invitee-form" role="presentation" style="padding: 0px 20px 15px 20px;">
                                <div class="input-group" style="display: flex;">
                                    <input type="text" class="form-control search-user search-user-large ui-invitee-input" placeholder="Search user by email...">
                                    <div class="input-group-append ml-1">
                                        <button class="btn btn-default ui-invitee-invite" invite-target=".search-user-large">Invite</button>
                                    </div>
                                </div>
                            </li>
                            <li role="presentation" class="ui-no-invitee-label" style="padding: 0px 20px 10px; font-size: 12px;">
                                No invitee
                            </li>
                            <li role="presentation" style="padding: 0 20px 15px 20px;" class="ui-invitee ui-invitee-list" data-email-invitation="true">
                                <div style="font-size: 12px;" class="ui-invitee-limit-label">This note has 0 invitee(s), you can invite 3 more</div>
                            </li>
                            

                            <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default"></li>

                            <!-- copy link button -->
                            <div class="px-5 pt-4 pb-1.5">
                                <button type="button" class="btn w-full !h-auto p-2.5 !m-0 !text-white bg-background-primary-default hover:!bg-background-primary-hover focus:!bg-background-primary-focus hocus:!text-white ui-share-copy" data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">
                                    <i class="ph ph-link-simple !text-white align-middle" aria-hidden="true"></i>
                                    Copy share link
                                </button>
                            </div>
                        </ul>
                    </li>

                    <!-- publish tab -->
                    <li class="ui-publish-tab hidden">
                        <div class="public-publish-container" style="">
                            <div class="text-text-default px-5">
    <figure class="text-center py-5">
        <img class="publish-note-image" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/publish-note-dark.svg" alt="Publish Note">
    </figure>

    <h3 class="text-5">
        Publish Note
    </h3>

    <div class="text-sm mb-3">
        <div class="publish-note-description-for-public-team" style="display: none; white-space: initial;">Everyone on the web can find and read all notes of this public team.</div>
        <div class="publish-note-description" style="white-space: initial;">Once published, notes can be searched and viewed by anyone online.</div>
        <div class="how-to-publish-note-description mt-1.5" style="white-space: initial;"><a target="_blank" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/">See published notes</a></div>
    </div>

    <div class="mb-3 community-guideline-container text-3">
        <label class="font-normal mb-0.5 flex">
            <input type="checkbox" class="!mt-0 !mr-1.5">
            <span>I agree to HackMD’s <a href="https://hackmd.io/@hackmd/community-guidelines" target="_blank">Community Guideline</a>.</span>
        </label>
        <span class="error-message text-state-danger-text hidden">Please check the box to agree to the Community Guidelines.</span>
    </div>

    <div class="flex justify-center public-published-toggle my-2 disabled" data-published="false">
        <button type="button" class="
                btn w-full p-2.5 !m-0 !h-auto
                bg-transparent border border-state-danger-border
                hocus:!bg-state-danger-bg-hover text-state-danger-text hocus:!text-white
                disabled:!bg-element-bg-disabled disabled:!border-element-border-disabled disabled:!text-icon-disabled disabled:!cursor-not-allowed
                publish
            " disabled="">
            Unpublish
        </button>

        <button type="button" class="
                btn w-full p-2.5 !m-0 !h-auto
                !text-white bg-background-primary-default
                hover:!bg-background-primary-hover focus:!bg-background-primary-focus hocus:!text-white disabled:!bg-background-primary-disabled disabled:cursor-not-allowed
                unpublish
            " disabled="">
            <i class="ph-fill ph-globe-hemisphere-west !text-white align-middle" aria-hidden="true"></i>
            Publish the note
        </button>
    </div>

    <!-- copy link button -->
    <div class="mb-2">
        <button type="button" class="
                btn w-full !h-auto p-2.5 !m-0
                bg-transparent hocus:!bg-background-primary-default !text-text-primary hocus:!text-white
                group ui-share-copy change-inlined
            " data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">
            <i class="ph ph-link-simple !text-text-primary align-middle group-hover:!text-white group-focus:!text-white" aria-hidden="true"></i>
            Copy link
        </button>
    </div>
</div>

                        </div>
                    </li>
                </ul>

                <!-- more features tab -->
                <ul class="dropdown-menu list ui-more-settings-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px; padding-top: 0px; padding-bottom: 0px; display: none">
                    <li role="presentation">
                        <button class="ui-more-settings-menu-back text-left p-3.5 w-full bg-transparent border-none">
                            <span class="text-[14px] leading-[135%]">
                                <i class="ph ph-caret-left" style="width:auto; margin-right: 10px;"></i>
                                More features
                            </span>
                        </button>
                    </li>

                    <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default mb-4"></li>

                    
                    <li class="dropdown-header mt-4.5 !px-4.5 !py-0">
                        Commenting
                        <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left ui-second-menu-tooltip"
                        title="Note owner decides who can give comments."
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->

                        <div class="permission-item-badge permission-item-readonly mt-2.5" style="display: none;" name="comment">
                            Permission

                            <div>
                                <span name="disabled" style="display: none;">Disabled</span>
                                <span name="forbidden" style="display: none;">Forbidden</span>
                                <span name="owners" style="display: none;">Owners</span>
                                <span name="signed_in_users" style="">Signed-in users</span>
                                <span name="everyone" style="display: none;">Everyone</span>
                            </div>
                        </div>
                    </li>
                    <li class="px-4.5 flex items-center my-2.5">
                        <span class="ui-comment-permission-toggle flex flex-row justify-between w-full">
                            <span>
                                Enable
                            </span>
                            <span class="w-[180px]">
                                <label class="switch" style="vertical-align: middle;" aria-label="Enable">
                                    <input type="checkbox">
                                    <span class="slider round"></span>
                                </label>
                            </span>
                        </span>
                    </li>
                    <li class="ui-comment-permission-comment mb-4.5 px-4.5 h-[28px]" role="presentation">
                        <span class="flex flex-row justify-between w-full">
                            <span class="flex flex-row items-center">
                                Permission
                            </span>
                            <div class="w-[180px]">
                                <div>
                                    <div class="dropdown menuitem-dropdown">
                                        <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                            <span class="ui-comment-write-label">Signed-in users</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                        </button>
                                        <ul class="dropdown-menu" role="menu">
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-forbidden" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Forbidden</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Owners</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-signed_in_users" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-everyone" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Everyone</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </span>
                    </li>

                    <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-4"></li>
                    

                    
                    <li class="dropdown-header mt-4.5 !px-4.5 !py-0">
                        <div class="flex items-center gap-2.5">
                            Suggest edit

                            <a href="https://hackmd.io/@docs/suggest-edit-en" class="hover:no-underline" target="_blank" rel="noopener noreferrer">
                                <button class="
                                        text-sm leading-sm border border-solid border-border-primary-default text-text-primary hocus:bg-background-primary-default hocus:border-background-primary-default hocus:!text-white
                                        flex flex-row gap-0.5 px-1.5 py-0.5 rounded bg-transparent items-center group
                                    ">
                                    Beta
                                    <i class="ph ph-arrow-square-out !text-text-primary group-hover:!text-white group-focus:!text-white"></i>
                                </button>
                            </a>
                        </div>

                        <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left ui-second-menu-tooltip"
                        title="Note owner decides who can suggest edit this note."
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->

                        <div class="permission-item-badge permission-item-readonly mt-2.5" style="display: none;" name="suggest-edit">
                            Permission

                            <div>
                                <span name="disabled" style="display: none;">Disabled</span>
                                <span name="forbidden" style="display: none;">Forbidden</span>
                                <span name="owners" style="display: none;">Owners</span>
                                <span name="signed_in_users" style="">Signed-in users</span>
                                <span name="everyone" style="display: none;">Everyone</span>
                            </div>
                        </div>
                    </li>
                    <li class="px-4.5 flex items-center my-2.5">
                        <span class="ui-suggest-edit-permission-toggle flex flex-row justify-between w-full">
                            <span>
                                Enable
                            </span>
                            <span class="w-[180px]">
                                <label class="switch" style="vertical-align: middle;" aria-label="Enable">
                                    <input type="checkbox">
                                    <span class="slider round"></span>
                                </label>
                            </span>
                        </span>
                    </li>
                    <li class="ui-suggest-edit-permission mb-4.5 px-4.5 h-[28px]" role="presentation">
                        <span class="flex flex-row justify-between w-full">
                            <span class="flex flex-row items-center">
                                Permission
                            </span>
                            <div class="w-[180px]">
                                <div>
                                    <div class="dropdown menuitem-dropdown">
                                        <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                            <span class="ui-suggest-edit-write-label">Signed-in users</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                        </button>
                                        <ul class="dropdown-menu" role="menu">
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-forbidden" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Forbidden</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Owners</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-signed_in_users" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </span>
                    </li>
                    
                </ul>

                <!-- slide options tab -->
                <ul class="dropdown-menu list ui-customize-slide-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px; padding-top: 0px; padding-bottom: 0px; display: none">
                    <li role="presentation">
                        <button class="ui-customize-slide-menu-back p-3.5 text-left w-full bg-transparent border-none">
                            <i class="ph ph-caret-left" style="width:auto; margin-right: 15px;"></i>
                            Customize slides options
                        </button>
                    </li>

                    <li role="presentation" aria-hidden="true" class="h-[1px] bg-border-default"></li>

                    <li role="presentation" class="ui-customize-slide-menu-options"><div class="p-5 text-text-default flex flex-col gap-[9px]"><div class="font-semibold text-3 leading-[14px]">Slides option</div><div class="text-3 leading-[16px]">Customize the slides in YAML.<br>See the<a class="underline text-text-subtle hocus:text-text-subtle" href="https://revealjs.com/config/" target="_blank" rel="noreferrer">documentation</a>for available options.</div><textarea class="text-5 leading-[20px] border rounded outline-none border-solid
      min-w-full max-w-full min-h-[160px] px-[11px] py-[10px]
      text-[#333] border-gray-300
      placeholder:text-[#777]
      focus:border-[#5AAED1]
      focus:shadow-[0px_0px_6px_#5AAED1]
      hover:border-[#5AAED1]
      hover:shadow-[0px_0px_6px_#5AAED1]
      disabled:cursor-not-allowed disabled:bg-zinc-200 disabled:border-zinc-400
     text-4 leading-[18px] !text-text-default bg-transparent hocus:!border-border-primary-subtler hocus:shadow-none min-h-[209px] grow resize-none" style="font-family: &quot;Source Code Pro&quot;, monospace;"></textarea><div class="flex justify-end gap-1.5"><button disabled="" class="ui-meta-slide-options-edit-cancel btn p-2.5 !h-auto bg-transparent text-text-default hocus:bg-element-bg-hover hocus:text-text-default !font-semibold !my-0">Cancel</button><button disabled="" class="ui-meta-slide-options-edit-update btn p-2.5 !h-auto bg-background-primary-default hover:!bg-background-primary-hover focus:!bg-background-primary-focus text-white hocus:text-white !font-semibold !my-0">Update</button></div></div></li>
                </ul>
            </li>

            <!-- Extra Menu -->
            <li title="" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" aria-label="Menu" class="ui-extra-menu" data-original-title="Menu">
                <a class="rounded ui-menu navbar-button-icon" data-toggle="dropdown" tabindex="0" aria-expanded="false">
                    <i class="ph-fill ph-dots-three-outline"></i>
                </a>
                <span class="ui-menu-popover-target" style="left: 50%; position: absolute;"></span>
                <ul class="dropdown-menu list ui-extra-menu" role="menu" aria-label="Menu">
                    <li class="dropdown-header">
                        Options
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-extra-revision" data-toggle="modal" data-target="#namedRevisionModal" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-clock-counter-clockwise"></i>
                            Versions and GitHub Sync
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-transfer-note" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-arrows-left-right"></i>
                            Transfer ownership
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-delete-note" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-trash"></i>
                            Delete this note
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-note-settings" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1" style="">
                            <i class="ph ph-info"></i>
                            Note settings
                        </a>
                    </li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header ui-menu-template-header">
                        Template
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-template-save" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-floppy-disk"></i>
                            Save as template
                        </a>
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-template-insert" data-toggle="modal" data-target="#templateModal" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-plus"></i>
                            Insert from template
                        </a>
                    </li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Export
                    </li>
                    
                    <li role="presentation">
                        
                        <a role="menuitem" class="ui-download-pdf-beta" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank" tabindex="-1">
                            <i class="ph ph-file-pdf"></i>
                            PDF
                            
                            <span class="text-sm leading-sm text-text-primary font-medium rounded border border-solid border-border-primary-default py-0.5 px-1.5">
                                Limited trial
                            </span>
                            
                        </a>
                        
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-dropbox" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self" tabindex="-1">
                            <i class="ph ph-dropbox-logo"></i>
                            Dropbox
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-google-drive" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self" tabindex="-1">
                            <i class="ph ph-google-drive-logo"></i>
                            Export to Google Drive
                        </a>
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-gist" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg/gist" target="_blank" tabindex="-1">
                            <i class="fa fa-github fa-20 w-5 h-5 text-center" style="line-height: 20px;"></i>
                            Gist</a>
                        </li>
                    
                    
                    
                    
                    <li role="presentation" class="arweave-export-item"><a role="menuitem" class="focus:outline-none ui-save-arweave" tabindex="-1" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-0" data-state="closed"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/arweave-logo-dark.svg" alt="arweave logo">Arweave</a></li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Import
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-dropbox" target="_self" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-dropbox-logo"></i>
                            Dropbox
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-google-drive" target="_self" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-google-drive-logo"></i>
                            Import from Google Drive
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-gist" data-toggle="modal" data-target="#gistImportModal" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="fa fa-github fa-20 w-5 h-5 text-center" style="line-height: 20px;"></i>
                            Gist
                        </a>
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-clipboard" data-toggle="modal" data-target="#clipboardModal" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">
                            <i class="ph ph-clipboard-text"></i>
                            Clipboard
                        </a>
                    </li>
                    
                    <li role="presentation" class="arweave-import-item"><a role="menuitem" class="focus:outline-none ui-import-arweave" tabindex="-1" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-6" data-state="closed"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/arweave-logo-dark.svg" alt="arweave logo">Arweave</a></li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Download
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-download-markdown" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank" tabindex="-1">
                            <i class="ph ph-file-md"></i>
                            Markdown
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-download-html" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank" tabindex="-1">
                            <i class="ph ph-file-html"></i>
                            HTML
                        </a>
                    </li>
                    <li role="presentation"><a role="menuitem" class="ui-download-raw-html" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank" tabindex="-1">
                            <i class="ph ph-file-html"></i>
                            Raw HTML
                        </a>
                    </li>
                </ul>
            </li>
            <!-- End Extra Menu -->
        </ul>
        <ul class="nav user-profile navbar-nav navbar-right">
            <div class="ui-status-offline-root hidden"></div>
            <li class="ui-status-offline-portal mr-1.5" style="display: none;"><button class="p-0 m-0 border-none text-5 leading-[20px] ui-note-status-icon btn ml-1.5 bg-transparent px-2.5 py-1.5 hover:bg-gray-200 focus:bg-gray-200"></button></li>
            <li id="online-user-list" class="ui-host-list mr-2.5" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" data-original-title="Online user" title="" style="">
                <button class="ui-status btn online bg-transparent text-text-emphasize" data-toggle="dropdown"><i class="ph ph-users-three"></i><span class="ml-1">1</span><i class="ph ph-caret-down ml-1.5"></i></button>
                <ul class="dropdown-menu list" role="menu" aria-labelledby="menu"><li class="dropdown-header">Choose a user to host</li><li class="ui-user-item upgraded" data-upgraded="false" style="border-left: 4px solid rgb(193, 19, 13);"><span class="id" style="display:none;">UbkKg51gaJl8A06sASww</span><a class="ui-user-profile" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"><span class="pull-left"><img class="ui-user-icon user-card-popover" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085" data-toggle="popover" data-original-title="" title=""></span><span class="ui-user-name name">Cường17</span><button class="btn btn-outline btn-primary ui-host" style=""><span class="host-text">Host</span><span class="cancel-host-text">Cancel</span><span class="hosting-text"><i class="ui-live-circle" style="font-size: 12px;"></i>&nbsp;Live</span></button><span class="pull-right flex"><i class="ph-fill ph-circle ui-user-status ui-user-status-online"></i></span></a></li></ul>
            </li>
            
                <li title="" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" class="mr-2.5" data-original-title="Cường17">
                    <a class="rounded ui-profile-label" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" tabindex="0">
                        <img class="ui-avatar" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085" alt="Profile photo">
                    </a>
                    <ul id="profile-dropdown" class="dropdown-menu" aria-labelledby="profileLabel">
                        <li><a href="https://hackmd.io/settings" target="_blank" tabindex="-1"><i class="ph ph-gear" aria-hidden="true"></i> Settings</a></li>
                        
                            <li><a href="https://hackmd.io/profile" target="_blank" tabindex="-1"><i class="ph ph-user-circle" aria-hidden="true"></i> Profile</a></li>
                        
                        <li><a href="https://hackmd.io/?nav=myTeams" target="_blank" tabindex="-1"><i class="ph ph-users" aria-hidden="true"></i> My teams</a></li>
                        
                            <li><a href="https://hackmd.io/?nav=billing" target="_blank" tabindex="-1"><i class="ph ph-credit-card" aria-hidden="true"></i> Billing</a></li>
                        
                        <li role="presentation" aria-hidden="true" class="divider"></li>
                        <li>
                            <a href="https://hackmd.io/logout" class="ui-signout" tabindex="-1"><i class="ph ph-sign-out" aria-hidden="true"></i> Sign out</a>
                        </li>
                    </ul>
                </li>
            
        </ul>
    </div>

    <div class="sidenav main-sidenav" style="display: none;">
        
        <a class="sidenav-item sidenav-trigger ui-profile-menu dark-border" sidenav-target="sidenav-profile">
            <img class="ui-avatar rounded-full" width="22" height="22" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085" alt="Profile photo">
            <span>
                Cường17
            </span>
            <i class="ph ph-caret-right"></i>
        </a>
        
        <a class="sidenav-item sidenav-trigger ui-menu" sidenav-target="sidenav-menu" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"><i class="ph-fill ph-dots-three-outline"></i>
            <span>
                Menu
            </span>
            <i class="ph ph-caret-right"></i>
        </a>

        
            <a class="sidenav-item sidenav-trigger ui-note-settings-mobile" sidenav-target="sidenav-note-setting" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" style="">
                <i class="ph ph-info"></i>
                <span>
                    Note settings
                </span>
                <i class="ph ph-caret-right"></i>
            </a>
        

        <a class="sidenav-item sidenav-trigger ui-share" sidenav-target="sidenav-permission" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"><i class="ph ph-share-network"></i>
            <span>
                Sharing URL
            </span>
            <i class="ph ph-caret-right"></i>
        </a>
        
            
            <a class="sidenav-item sidenav-trigger ui-create" sidenav-target="sidenav-create" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"><i class="ph ph-plus"></i>
                <span>
                    Create
                </span>
                <i class="ph ph-caret-right"></i>
            </a>
            
        


        
            <a class="sidenav-item ui-spotlight" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" title="Find notes (Cmd/Ctrl + Shift + P)"><i class="ph ph-magnifying-glass"></i>
                <span>
                        Find notes
                </span>
            </a>
        

        <a class="sidenav-item ui-help dark-border" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target=".help-modal"><i class="ph ph-question-mark"></i>
            <span>
                    Help
            </span>
        </a>
    </div>


    
    
    <div class="sidenav sidenav-create" style="display: none;">
        <a class="sidenav-item sidenav-back ui-create-back" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
            <i class="ph ph-caret-left" style="width:auto"></i>
            <i class="ph ph-plus" style="margin: 0px 0px 0px 15px;"></i>
            <span>Create</span>
        </a>
        <a class="sidenav-item ui-new" tabindex="-1" href="https://hackmd.io/new" target="_blank"><i class="ph ph-plus"></i>
            <span>Create new note</span></a>
        <a class="sidenav-item ui-new-with-template" tabindex="-1" data-toggle="modal" data-target="#templateModal"><i class="ph ph-file-image"></i>
            <span>Create a note from template</span></a>
    </div>
    
    
    <div class="sidenav sidenav-menu" style="display: none;">
        <a class="sidenav-item sidenav-back ui-menu-back" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
            <i class="ph ph-caret-left" style="width:auto"></i>
            <i class="ph-fill ph-dots-three-outline" style="margin: 0px 0px 0px 15px;"></i>
            <span>Menu</span>
        </a>
        <div class="divider-header">Options</div>
        <a class="sidenav-item ui-extra-revision" tabindex="-1" data-toggle="modal" data-target="#namedRevisionModal"><i class="ph ph-clock-counter-clockwise"></i>
            <span>
                Versions and GitHub Sync
            </span>
        </a>
        <a class="sidenav-item ui-transfer-note"><i class="ph ph-arrows-left-right"></i>
            <span>Transfer ownership</span></a>
        <a class="sidenav-item ui-delete-note"><i class="ph ph-trash"></i>
            <span>Delete this note</span></a>
        <div class="divider-header">Export</div>
        
            
            <a class="sidenav-item ui-download-pdf-beta" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank">
                <i class="ph ph-file-pdf"></i>
                <span>PDF</span>
                
                    <span class="text-sm leading-sm text-text-primary font-medium rounded border border-solid border-border-primary-default py-0.5 px-1.5">
                        Limited trial
                    </span>
                
            </a>
            
        
        <a class="sidenav-item ui-save-dropbox" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self"><i class="ph ph-dropbox-logo"></i><span>Dropbox</span></a>
        <a class="sidenav-item ui-save-google-drive" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self">
            <i class="ph ph-google-drive-logo"></i>
            <span>Export to Google Drive</span>
        </a>
        
            <a class="sidenav-item ui-save-gist" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg/gist" target="_blank"><i class="fa fa-github fa-20 w-[22px] h-[22px] !leading-normal text-center"></i><span>Gist</span></a>
        
        
        
        <a class="sidenav-item ui-save-arweave sidenav-arweave-export-item"><div class="focus:outline-none ui-save-arweave" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-3" data-state="closed"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/arweave-logo-dark.svg" class="w-[22px] h-[22px]" alt="arweave logo"><span class="ml-2">Arweave</span></div></a>
        
        <div class="divider-header">Import</div>
        <a class="sidenav-item ui-import-dropbox" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self"><i class="ph ph-dropbox-logo"></i><span>Dropbox</span></a>
        <a class="sidenav-item ui-import-google-drive" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_self">
            <i class="ph ph-google-drive-logo"></i>
            <span>Import from Google Drive</span>
        </a>
        <a class="sidenav-item ui-import-gist" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target="#gistImportModal"><i class="fa fa-github fa-20 w-[22px] h-[22px] !leading-normal text-center"></i><span>Gist</span></a>
        
        <a class="sidenav-item ui-import-clipboard" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target="#clipboardModal"><i class="ph ph-clipboard"></i><span> Clipboard</span></a>
        
        <a class="sidenav-item ui-import-arweave sidenav-arweave-import-item"><div class="focus:outline-none ui-import-arweave" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-9" data-state="closed"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/arweave-logo-dark.svg" class="w-[22px] h-[22px]" alt="arweave logo"><span class="ml-2">Arweave</span></div></a>
        
        <div class="divider-header">Download</div>
        <a class="sidenav-item ui-download-markdown" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank"><i class="ph ph-file-md"></i><span>Markdown</span></a>
        <a class="sidenav-item ui-download-html" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank"><i class="ph ph-file-html"></i><span>HTML</span></a>
        <a class="sidenav-item ui-download-raw-html" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" target="_blank"><i class="ph ph-file-html"></i><span> Raw HTML</span></a>
    </div>
    <div class="sidenav sidenav-profile" style="display: none;">
        
            <a class="sidenav-item sidenav-back ui-profile-menu-back dark-border">
                <i class="ph ph-caret-left" style="width: auto;"></i>
                <img class="ui-avatar" width="22" height="22" style="border-radius: 100%; margin: 0px 0px 0px 18px;" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085">
                <span>Cường17</span>
            </a>
            
                <a href="https://hackmd.io/profile" target="_blank" class="sidenav-item ui-profile"><i class="ph ph-user-circle"></i><span>Profile</span></a>
            
            <a href="https://hackmd.io/features" target="_blank" class="sidenav-item ui-features"><i class="ph-fill ph-dot"></i><span>Features</span></a>
            
                <a href="https://hackmd.io/pricing" target="_blank" class="sidenav-item ui-pricing"><i class="ph ph-magic-wand"></i><span>Pricing</span></a>
            
            
                <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="sidenav-item" data-toggle="modal" data-target=".feedback-modal" style="color: #5cb85c">
                    <i class="ph ph-paper-plane-tilt"></i>
                    <span>Feedback</span>
                </a>
            
            <a href="https://hackmd.io/settings" target="_blank" class="sidenav-item ui-settings"><i class="ph ph-gear"></i><span>Settings</span></a>
            <a href="https://hackmd.io/logout" class="sidenav-item ui-signout"><i class="ph ph-sign-out"></i><span>Sign out</span></a>
        
    </div>

    <!-- mobile share dropdown -->
    <div class="sidenav full sidenav-permission permission-dropdown" style="display: none;">
        <a class="sidenav-item sidenav-back ui-share-back !text-text-default !border-none" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
            <i class="ph ph-caret-left" style="width: auto;"></i>
        </a>

        <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default"></div>

        <!-- tabs -->
        <ul class="flex list-none px-5 mt-4 mb-0">
            <li>
                <button class="bg-transparent border-0 border-border-bold text-text-subtle p-2 ui-share-tab-link border-b-1 !text-text-default">
                    Share
                </button>
            </li>
            <li>
                <button class="bg-transparent border-0 border-border-bold text-text-subtle p-2 ui-publish-tab-link" style="">
                    Publish
                    <i class="ph-fill ph-globe-hemisphere-west hidden" aria-hidden="true"></i>
                </button>
            </li>
        </ul>

        <!-- divider -->
        <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default mb-5"></div>

        
            <li class="dropdown-header fill-username-banner" style="">
    Fill username to use a shorter link! <span style="white-space: nowrap;"><a href="https://hackmd.io/settings" target="_blank"><i class="fa fa-gear"></i> Settings</a></span>
</li>

        

        <!-- share tab -->
        <div class="ui-share-tab">
            <div class="dropdown-header">
                Sharing URL
                <!-- <i
                    class="ph-fill ph-question text-text-default text-4 tooltip-align-left"
                    title="Share this note with below URL. Make sure your audience has the permission to access this note."
                    data-toggle="tooltip"
                    data-placement="bottom"
                    data-offset="0,5"></i> -->
                <span class="ui-share-msg" style="display: none;">
                    Link copied
                </span>
            </div>
            <div class="ui-share-domain" style="margin-bottom: 5px; padding: 0 15px; font-size: 12px; word-break: break-all; overflow: hidden; text-overflow: ellipsis;" title="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/">https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/</div>
            <div class="input-group" style="padding: 0px 15px;">
                <input type="text" class="form-control ui-share-field" maxlength="200" placeholder="BydS9N55A" style="height: 28px; font-size: 13px;">
                <div class="ui-share-edit-mode" style="position: absolute; z-index: 10; font-size: 13px; top: 5px; right: 100px; display: none;">/edit</div>
                <span class="input-group-btn">
                    <button class="btn ui-share-copy !ml-1" type="button" data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">Copy</button>
                </span>
                <span class="input-group-btn" style="display: none">
                    <button class="btn ui-share-save !ml-1" type="button">Save</button>
                </span>
            </div>
            <div style="display: flex; padding: 0px 15px; margin-top: 10px; align-items: center; justify-content: flex-end;">
                <div class="ui-publish-type" style="flex: 1; display: flex; align-items: center;">
                    <div style="flex: 1">
                        <div>
                            <div class="dropdown menuitem-dropdown">
                                <div class="menuitem-dropdown-trigger">
                                    <span class="ui-publish-type-label">
                                                        <i class="ph ph-eye" aria-hidden="true"></i> View mode
                                                    </span>
                                    <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                </div>
                                <ul class="dropdown-menu" role="menu">
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-edit"><i class="ph ph-pencil-simple" aria-hidden="true"></i> Edit mode</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-view"><i class="ph ph-eye" aria-hidden="true"></i> View mode</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-book"><i class="ph ph-book" aria-hidden="true"></i> Book mode</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-slide"><i class="ph ph-monitor" aria-hidden="true"></i> Slide mode</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left p-1.5"
                    title="Note owner decides who can read or write this note."
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->
                </div>
                <div class="permission-item-badge permission-item-readonly ui-publish-type-badge mr-1.5" style="display: none;">
                    <span name="edit" style="display: none;"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Edit mode</span>
                    <span name="view" style=""><i class="fa fa-eye" aria-hidden="true"></i> View mode</span>
                    <span name="book" style="display: none;"><i class="fa fa-book" aria-hidden="true"></i> Book mode</span>
                    <span name="slide" style="display: none;"><i class="fa fa-television" aria-hidden="true"></i> Slide mode</span>
                </div>
                <div>
                    <button class="btn btn-default ui-share-preview" type="button">Preview</button>
                </div>
            </div>

            
            <div class="flex justify-center mt-2 mx-5">
                <div class="ui-publish-slide-options mobile" style="display: none;">
                    <span>Customize slides</span>
                    <i class="ph ph-caret-right"></i>
                </div>
            </div>
            

            <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-4"></div>

            <div class="dropdown-header">
                Note Permission

                <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left" style="color: #CDCDCD" title="Note owner decides who can read or write this note." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->
            </div>
            <div class="note-permission-item">
                <div style="display: flex; height: 26px;">
                    <span style="flex: 1;">
                        <div style="display: table; width: 100%; height: 100%;">
                            <div style="display: table-cell; vertical-align: middle;">
                                Read
                            </div>
                        </div>
                    </span>
                    <div style="flex: 2" class="ui-note-read">
                        <div>
                            <div class="dropdown menuitem-dropdown">
                                <div class="menuitem-dropdown-trigger"><span class="ui-note-read-label">Only me</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                                <ul class="dropdown-menu" role="menu">
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-owners">Only me</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-signed_in_users">Signed-in users</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-everyone">Everyone</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="permission-item-badge permission-item-readonly" style="display: none;" name="read">
                        <span name="owners" style="">Only me</span>
                        <span name="signed_in_users" style="display: none;">Signed-in users</span>
                        <span name="everyone" style="display: none;">Everyone</span>
                    </div>
                </div>
            </div>
            <div class="note-permission-item">
                <div style="display: flex; height: 26px;">
                    <span style="flex: 1;">
                        <div style="display: table; width: 100%; height: 100%;">
                            <div style="display: table-cell; vertical-align: middle;">
                                Write
                            </div>
                        </div>
                    </span>
                    <div style="flex: 2" class="ui-note-write">
                        <div>
                            <div class="dropdown menuitem-dropdown">
                                <div class="menuitem-dropdown-trigger"><span class="ui-note-write-label">Only me</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                                <ul class="dropdown-menu" role="menu">
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-owners">Only me</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-signed_in_users disabled">Signed-in users</a></li>
                                    <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-everyone disabled">Everyone</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="permission-item-badge permission-item-readonly" style="display: none;" name="write">
                        <span name="owners" style="">Only me</span>
                        <span name="signed_in_users" style="display: none;">Signed-in users</span>
                        <span name="everyone" style="display: none;">Everyone</span>
                    </div>
                </div>
            </div>

            <div class="my-2 font-semibold hmd-ph-3/2 permission-notice">
                <small class="text-text-subtle font-medium">Private: only you can read and write.</small>
            </div>

            <!-- more features button -->
            
            <div class="note-permission-item" style="text-align: right; height: auto;">
                <span class="sidenav-trigger" sidenav-target="sidenav-note-more">
                    <div class="note-permission-button">
                        <span class="flex flex-col">
                            <span class="text-[16px] leading-[135%] font-semibold text-text-emphasize">
                                More features
                            </span>
                            <span class="text-[13px] leading-[14px]">
                                
                                    Commenting, 
                                
                                
                                    Suggest edit
                                
                            </span>
                        </span>

                        <i class="ph ph-caret-right"></i>
                    </div>
                </span>
            </div>
            

            <!-- invitee section -->
            
            <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-5"></div>

            <div class="ui-invitee-label dropdown-header">
                Invitee

                <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left" title="Admin can invite users and change note permissions." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->
            </div>
            <div class="ui-invitee-form" style="padding-bottom: 10px;">
                <div class="input-group" style="display: flex; padding: 0 15px;">
                    <input type="text" class="form-control search-user search-user-small ui-invitee-input" placeholder="Search user by email...">
                    <div class="input-group-append ml-1">
                        <button class="btn btn-default ui-invitee-invite" invite-target=".search-user-small">Invite</button>
                    </div>
                </div>
            </div>
            <div style="padding: 0 15px;" class="ui-invitee ui-invitee-list" data-email-invitation="true">
            </div>
            <div class="ui-no-invitee-label" style="padding: 0px 15px 10px; font-size: 12px;">
                No invitee
            </div>
            <div class="ui-invitee-limit-label" style="padding: 0px 15px; font-size: 12px;">This note has 0 invitee(s), you can invite 3 more</div>
            

            <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-4"></div>

            <!-- copy link button -->
            <div class="px-5">
                <button type="button" class="btn w-full !h-auto p-2.5 !m-0 !text-white bg-background-primary-default hover:!bg-background-primary-hover focus:!bg-background-primary-focus hocus:!text-white ui-share-copy" data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">
                    <i class="ph ph-link-simple !text-white align-middle" aria-hidden="true"></i>
                    Copy share link
                </button>
            </div>
        </div>

        <!-- publish tab -->
        <div class="ui-publish-tab hidden">
            <div class="public-publish-container" style="">
                <div class="text-text-default px-5">
    <figure class="text-center py-5">
        <img class="publish-note-image" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/publish-note-dark.svg" alt="Publish Note">
    </figure>

    <h3 class="text-5">
        Publish Note
    </h3>

    <div class="text-sm mb-3">
        <div class="publish-note-description-for-public-team" style="display: none; white-space: initial;">Everyone on the web can find and read all notes of this public team.</div>
        <div class="publish-note-description" style="white-space: initial;">Once published, notes can be searched and viewed by anyone online.</div>
        <div class="how-to-publish-note-description mt-1.5" style="white-space: initial;"><a target="_blank" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/">See published notes</a></div>
    </div>

    <div class="mb-3 community-guideline-container text-3">
        <label class="font-normal mb-0.5 flex">
            <input type="checkbox" class="!mt-0 !mr-1.5">
            <span>I agree to HackMD’s <a href="https://hackmd.io/@hackmd/community-guidelines" target="_blank">Community Guideline</a>.</span>
        </label>
        <span class="error-message text-state-danger-text hidden">Please check the box to agree to the Community Guidelines.</span>
    </div>

    <div class="flex justify-center public-published-toggle my-2 disabled" data-published="false">
        <button type="button" class="
                btn w-full p-2.5 !m-0 !h-auto
                bg-transparent border border-state-danger-border
                hocus:!bg-state-danger-bg-hover text-state-danger-text hocus:!text-white
                disabled:!bg-element-bg-disabled disabled:!border-element-border-disabled disabled:!text-icon-disabled disabled:!cursor-not-allowed
                publish
            " disabled="">
            Unpublish
        </button>

        <button type="button" class="
                btn w-full p-2.5 !m-0 !h-auto
                !text-white bg-background-primary-default
                hover:!bg-background-primary-hover focus:!bg-background-primary-focus hocus:!text-white disabled:!bg-background-primary-disabled disabled:cursor-not-allowed
                unpublish
            " disabled="">
            <i class="ph-fill ph-globe-hemisphere-west !text-white align-middle" aria-hidden="true"></i>
            Publish the note
        </button>
    </div>

    <!-- copy link button -->
    <div class="mb-2">
        <button type="button" class="
                btn w-full !h-auto p-2.5 !m-0
                bg-transparent hocus:!bg-background-primary-default !text-text-primary hocus:!text-white
                group ui-share-copy change-inlined
            " data-permalink="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A" data-clipboard-text="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A/BydS9N55A">
            <i class="ph ph-link-simple !text-text-primary align-middle group-hover:!text-white group-focus:!text-white" aria-hidden="true"></i>
            Copy link
        </button>
    </div>
</div>

            </div>
        </div>
    </div>

    <!-- mobile more features tab -->
    <div class="sidenav full sidenav-note-more permission-dropdown" style="display: none;">
        <a class="sidenav-item sidenav-back ui-note-more-back bg-transparent !border-none !text-text-default" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
            <span class="text-[14px] leading-[135%]">
                <i class="ph ph-caret-left" style="width:auto; margin-right: 10px;"></i>
                More features
            </span>
        </a>

        <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default mb-4"></div>

        
        <div class="dropdown-header mt-4.5 !px-4.5 !pt-0">
            Commenting
            <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left ui-second-menu-tooltip"
            title="Note owner decides who can give comments."
            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->

            <div class="permission-item-badge permission-item-readonly mt-2.5" style="display: none;" name="comment">
                Permission

                <div>
                    <span name="disabled" style="display: none;">Disabled</span>
                    <span name="forbidden" style="display: none;">Forbidden</span>
                    <span name="owners" style="display: none;">Owners</span>
                    <span name="signed_in_users" style="">Signed-in users</span>
                    <span name="everyone" style="display: none;">Everyone</span>
                </div>
            </div>
        </div>
        <div class="px-4.5 flex items-center mb-2.5">
            <span class="ui-comment-permission-toggle flex flex-row flex-1 justify-between w-full">
                <span class="flex-1">
                    Enable
                </span>
                <span class="flex-[2_2_0%]">
                    <label class="switch" style="vertical-align: middle;" aria-label="Enable">
                        <input type="checkbox">
                        <span class="slider round"></span>
                    </label>
                </span>
            </span>
        </div>
        <div class="ui-comment-permission-comment mb-4.5 px-4.5 h-[28px]" role="presentation">
            <span class="flex flex-row justify-between w-full">
                <span class="flex flex-row flex-1 items-center">
                    Permission
                </span>
                <div class="flex-[2_2_0%]">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                <span class="ui-comment-write-label">Signed-in users</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                            </button>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-forbidden" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Forbidden</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Owners</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-signed_in_users" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-everyone" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Everyone</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </span>
        </div>

        <div role="presentation" aria-hidden="true" class="h-[1px] bg-border-default my-4"></div>
        

        
        <div class="dropdown-header mt-4.5 !px-4.5 !pt-0">
            <div class="flex items-center gap-2.5">
                Suggest edit

                <a href="https://hackmd.io/@docs/suggest-edit-en" class="hover:no-underline" target="_blank" rel="noopener noreferrer">
                    <button class="
                            text-sm leading-sm border border-solid border-border-primary-default text-text-primary hocus:bg-background-primary-default hocus:border-background-primary-default hocus:!text-white
                            flex flex-row gap-0.5 px-1.5 py-0.5 rounded bg-transparent items-center group
                        ">
                        Beta
                        <i class="ph ph-arrow-square-out !text-text-primary group-hover:!text-white group-focus:!text-white"></i>
                    </button>
                </a>
            </div>

            <!-- <i class="ph-fill ph-question text-text-default text-4 tooltip-align-left ui-second-menu-tooltip"
            title="Note owner decides who can suggest edit this note."
            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i> -->

            <div class="permission-item-badge permission-item-readonly mt-2.5" style="display: none;" name="suggest-edit">
                Permission

                <div>
                    <span name="disabled" style="display: none;">Disabled</span>
                    <span name="forbidden" style="display: none;">Forbidden</span>
                    <span name="owners" style="display: none;">Owners</span>
                    <span name="signed_in_users" style="">Signed-in users</span>
                    <span name="everyone" style="display: none;">Everyone</span>
                </div>
            </div>
        </div>
        <div class="px-4.5 h-[28px] flex flex-1 items-center mb-2.5">
            <span class="ui-suggest-edit-permission-toggle flex flex-row justify-between w-full">
                <span class="flex-1">
                    Enable
                </span>
                <span class="flex-[2_2_0%]">
                    <label class="switch" style="vertical-align: middle;" aria-label="Enable">
                        <input type="checkbox">
                        <span class="slider round"></span>
                    </label>
                </span>
            </span>
        </div>
        <div class="ui-suggest-edit-permission-mobile mb-4.5 px-4.5 h-[28px]" role="presentation">
            <span class="flex flex-row justify-between w-full">
                <span class="flex flex-row flex-1 items-center">
                    Permission
                </span>
                <div class="flex-[2_2_0%]">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                <span class="ui-suggest-edit-write-label">Signed-in users</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                            </button>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-forbidden" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Forbidden</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-owners" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Owners</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-suggest-edit-write-signed_in_users" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" tabindex="-1">Signed-in users</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </span>
        </div>
        
    </div>

    <div class="modal-backdrop dim ui-more-menu-back" style="display: none; margin-top: 51px;"></div>
</nav>
<div class="ui-spinner unselectable hidden-print" style="display: none;"><div class="spinner" role="progressbar" style="position: absolute; width: 0px; z-index: 2000000000; left: 50%; top: 50%;"><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-0-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(0deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-1-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(32deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-2-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(65deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-3-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(98deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-4-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(130deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-5-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(163deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-6-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(196deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-7-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(229deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-8-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(261deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-9-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(294deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-10-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(327deg) translate(30px, 0px); border-radius: 0px;"></div></div></div></div>

    <div class="row ui-content comment-panel" style="--hmd-comment-panel-width: 348px;" theme="light">
    <div class="ui-edit-area unselectable ui-resizable" theme="dark" style="display: none;">
        <textarea id="textit" style="display: none;"></textarea><div><div class="editor-top-banner-react-root" style="display: none;"></div><div class="
    tool-bar
    font-brand
    bg-background-subtler
    border-0 border-solid border-b-1 border-border-default
    flex flex-row gap-1.5 justify-start items-center overflow-auto pt-0.5 pb-[1px] px-2.5
    [&amp;_a]:text-icon-default [&amp;_a]:min-w-[28px] [&amp;_a]:w-7 [&amp;_a]:h-7 [&amp;_a]:p-1.5 [&amp;_a]:cursor-pointer [&amp;_a]:rounded
    [&amp;_a:hover]:text-icon-emphasize [&amp;_a:hover]:bg-element-bg-hover [&amp;_a:hover]:no-underline
    [&amp;_a:focus]:text-icon-emphasize [&amp;_a:focus]:bg-element-bg-hover [&amp;_a:focus]:no-underline
">
    <a title="Undo" data-i18n="[title]toolbar.undo" tabindex="-1" class="ph ph-arrow-arc-left ui-editor-toolbar-undo"></a>
    <a title="Redo" data-i18n="[title]toolbar.redo" tabindex="-1" class="ph ph-arrow-arc-right ui-editor-toolbar-redo"></a>
    <i class="separator border-solid border-0 border-l-1 border-border-default w-0">&nbsp;</i>
    <a title="Bold" data-i18n="[title]toolbar.bold" tabindex="-1" class="ph ph-text-b ui-editor-toolbar-bold"></a>
    <a title="Italic" data-i18n="[title]toolbar.italic" tabindex="-1" class="ph ph-text-italic ui-editor-toolbar-italic"></a>
    <a title="Strikethrough" data-i18n="[title]toolbar.strikethrough" tabindex="-1" class="ph ph-text-strikethrough ui-editor-toolbar-strikethrough hidden-xs"></a>
    <a title="Heading" data-i18n="[title]toolbar.heading" tabindex="-1" class="ph ph-text-h ui-editor-toolbar-heading"></a>
    <i class="separator border-solid border-0 border-l-1 border-border-default w-0">&nbsp;</i>
    <a title="Code" data-i18n="[title]toolbar.code" tabindex="-1" class="ph ph-code ui-editor-toolbar-code"></a>
    <a title="Quote" data-i18n="[title]toolbar.quote" tabindex="-1" class="ph ph-quotes ui-editor-toolbar-quote hidden-sm hidden-xs"></a>
    <a title="Generic List" data-i18n="[title]toolbar.generic-list" tabindex="-1" class="ph ph-list-dashes ui-editor-toolbar-unordered-list"></a>
    <a title="Numbered List" data-i18n="[title]toolbar.numbered-list" tabindex="-1" class="ph ph-list-numbers ui-editor-toolbar-ordered-list"></a>
    <a title="Check List" data-i18n="[title]toolbar.check-list" tabindex="-1" class="ph ph-check-square ui-editor-toolbar-check-list"></a>
    <i class="separator border-solid border-0 border-l-1 border-border-default w-0">&nbsp;</i>
    <a title="Create Link" data-i18n="[title]toolbar.create-link" tabindex="-1" class="ph ph-link ui-editor-toolbar-link"></a>
    <a title="Insert Image" data-i18n="[title]toolbar.insert-image" tabindex="-1" class="ph ph-image ui-editor-toolbar-image relative">
        <span class="btn-file">
            <label aria-label="Insert Image">
                <!-- available value for 'accept' can be found in `lib/constants/image` -->
                <input data-i18n="[title]toolbar.insert-image" type="file" accept="image/png, image/jpeg, image/bmp, image/tiff, image/gif, image/svg+xml" name="upload" multiple="" title="toolbar.insert-image">
            </label>
        </span>
    </a>
    <a title="Insert Table" data-i18n="[title]toolbar.insert-table" tabindex="-1" class="ph ph-table ui-editor-toolbar-table hidden-xs"></a>
    <a title="Insert Horizontal Line" data-i18n="[title]toolbar.insert-horizontal-line" tabindex="-1" class="ph ph-minus ui-editor-toolbar-horizontal-line hidden-sm hidden-xs"></a>
    <a title="Leave Comment" data-i18n="[title]toolbar.leave-comment" tabindex="-1" class="ph ph-chat-circle ui-editor-toolbar-comment"></a>
    <span class="table-tools hidden-xs text-icon-emphasize flex flex-row justify-start items-center" style="display: none;">
        <i class="separator border-solid border-0 border-l-1 border-border-default mr-2.5 w-0">&nbsp;</i>
        <span data-i18n="toolbar.row">Row</span>
        <a title="Insert Row" data-i18n="[title]toolbar.insert-row" tabindex="-1" class="ph ph-plus-circle ui-editor-toolbar-insert-row"></a>
        <a title="Delete Row" data-i18n="[title]toolbar.delete-row" tabindex="-1" class="ph ph-minus-circle ui-editor-toolbar-delete-row"></a>
        <a title="Move Row Up" data-i18n="[title]toolbar.move-row-up" tabindex="-1" class="ph ph-arrow-up ui-editor-toolbar-move-row-up"></a>
        <a title="Move Row Down" data-i18n="[title]toolbar.move-row-down" tabindex="-1" class="ph ph-arrow-down ui-editor-toolbar-move-row-down"></a>
        <i class="separator border-solid border-0 border-l-1 border-border-default mr-2.5 w-0">&nbsp;</i>
        <span data-i18n="toolbar.column">Column</span>
        <a title="Insert Column" data-i18n="[title]toolbar.insert-column" tabindex="-1" class="ph ph-plus-circle ui-editor-toolbar-insert-column"></a>
        <a title="Delete Column" data-i18n="[title]toolbar.delete-column" tabindex="-1" class="ph ph-minus-circle ui-editor-toolbar-delete-column"></a>
        <a title="Move Column Left" data-i18n="[title]toolbar.move-column-left" tabindex="-1" class="ph ph-arrow-left ui-editor-toolbar-move-column-left"></a>
        <a title="Move Column Right" data-i18n="[title]toolbar.move-column-right" tabindex="-1" class="ph ph-arrow-right ui-editor-toolbar-move-column-right"></a>
        <i class="separator border-solid border-0 border-l-1 border-border-default mr-2.5 w-0">&nbsp;</i>
        <span data-i18n="toolbar.alignment">Alignment</span>
        <a title="Align Left" data-i18n="[title]toolbar.align-left" tabindex="-1" class="ph ph-text-align-left ui-editor-toolbar-align-left"></a>
        <a title="Align Center" data-i18n="[title]toolbar.align-center" tabindex="-1" class="ph ph-text-align-center ui-editor-toolbar-align-center"></a>
        <a title="Align Right" data-i18n="[title]toolbar.align-right" tabindex="-1" class="ph ph-text-align-right ui-editor-toolbar-align-right"></a>
        <a title="Align None" data-i18n="[title]toolbar.align-none" tabindex="-1" class="ph ph-prohibit ui-editor-toolbar-align-none"></a>
    </span>
</div><div class="CodeMirror cm-s-neo-dark CodeMirror-wrap CodeMirror-overlayscroll" translate="no" style="height: 678px;"><div style="overflow: hidden; position: relative; width: 3px; height: 0px; top: 0px; left: 0px;"><textarea autocorrect="off" autocapitalize="off" spellcheck="false" tabindex="0" style="position: absolute; bottom: -1em; padding: 0px; width: 1000px; height: 1em; min-height: 1em; outline: none;"></textarea></div><div class="CodeMirror-overlayscroll-horizontal" cm-not-content="true" style="display: none;"><div></div></div><div class="CodeMirror-overlayscroll-vertical" cm-not-content="true" style="display: block; bottom: 0px;"><div style="height: 10px; top: 0px;"></div></div><div class="CodeMirror-scrollbar-filler" cm-not-content="true"></div><div class="CodeMirror-gutter-filler" cm-not-content="true"></div><div class="CodeMirror-scroll" tabindex="-1" style="height: 678px;" draggable="false"><div class="CodeMirror-sizer" style="margin-left: 0px; padding-right: 10px; padding-bottom: 0px; margin-bottom: 0px; border-right-width: 50px; min-height: 1479px;"><div style="position: relative; top: 0px;"><div class="CodeMirror-lines" role="presentation" style="padding-bottom: 656px;"><div role="presentation" style="position: relative; outline: none;"><div class="CodeMirror-measure"><pre class="CodeMirror-line-like"><span>xxxxxxxxxx</span></pre></div><div class="CodeMirror-measure"></div><div class="CodeMirror-other-cursors"></div><div style="position: relative; z-index: 1;"><div class="CodeMirror-selected" style="position: absolute; left: 0px; top: 110px; width: 0px; height: 0px;"></div></div><div class="CodeMirror-cursors" style="visibility: hidden;"><div class="CodeMirror-cursor" style="left: 0px; top: 110px; height: 0px;">&nbsp;</div></div><div class="cursor-menu"><ul class="dropdown-menu CodeMirror-other-cursor" style="left: 0px; position: absolute; z-index: 100; top: 132px; display: none; bottom: auto;" data-line="10" data-ch="0" data-offset-left="0" data-offset-top="22"><li class="textcomplete-item active" data-index="0"><a>![image alt][reference]</a></li><li class="textcomplete-item" data-index="1"><a>![image alt](https:// "title")</a></li><li class="textcomplete-item" data-index="2"><a>![image alt](https:// "title" =WidthxHeight)</a></li></ul></div><div class="CodeMirror-code" role="presentation" style=""><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">1</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div><div class="CodeMirror-gutter-elt" style="left: 44px; width: 13px;"><div class="CodeMirror-foldgutter-open CodeMirror-guttermarker-subtle"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-header cm-header-1"># </span><span class="cm-m-markdown cm-strong cm-header cm-header-1">**💡Lab: Excessive trust in client-side controls**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">2</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-hr">---</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">3</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div><div class="CodeMirror-gutter-elt" style="left: 44px; width: 13px;"><div class="CodeMirror-foldgutter-open CodeMirror-guttermarker-subtle"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-header cm-header-3">### </span><span class="cm-m-markdown cm-strong cm-header cm-header-3">**Mô tả**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">4</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bài lab này có một </span><span class="cm-m-markdown cm-strong">**lỗ hổng logic**</span><span class="cm-m-markdown"> do </span><span class="cm-m-markdown cm-strong">**giá trị của sản phẩm**</span><span class="cm-m-markdown"> được kiểm soát và xác thực </span><span class="cm-m-markdown cm-strong">**trên phía client**</span><span class="cm-m-markdown"> thay vì phía server. Điều này cho phép kẻ tấn công thay đổi giá trị của sản phẩm khi gửi yêu cầu mua hàng đến server, dẫn đến việc </span><span class="cm-m-markdown cm-strong">**mua hàng với giá </span><span class="cm-m-markdown cm-formatting cm-formatting-math cm-strong cm-math">$</span><span class="cm-m-markdown cm-strong cm-math">0**.</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">5</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">6</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div><div class="CodeMirror-gutter-elt" style="left: 44px; width: 13px;"><div class="CodeMirror-foldgutter-open CodeMirror-guttermarker-subtle"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-math cm-header cm-header-3">### **Mục tiêu**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">7</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-math">Mục tiêu của bài lab này là khai thác **lỗ hổng logic** do sự tin tưởng quá mức vào kiểm soát phía client để lấy được hàng hóa với giá </span><span class="cm-m-markdown cm-formatting cm-formatting-math cm-math">$</span><span class="cm-m-markdown">0. </span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">8</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">9</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-hr">---</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">10</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Đăng nhập với wiener/peter</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">11</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker cm-overlay cm-matchhighlight">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link cm-overlay cm-matchhighlight">[image]</span><span class="cm-m-markdown cm-string cm-url cm-overlay cm-matchhighlight">(https://hackmd.io/_uploads/Hy78oI99C.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">12</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-tag cm-bracket">&lt;</span><span class="cm-m-xml cm-tag">br</span><span class="cm-m-xml cm-tag cm-bracket">&gt;</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">13</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Test thử chức năng thêm vào giỏ hàng</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">14</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/BkQii859R.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">15</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">16</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bắt request gửi sang Repeater để phân tích</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">17</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">18</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Sửa giá về 0, 1 respone 302 được trả về nhưng trong giỏ hàng vẫn trống -&gt; khả năng không nhận giá 0</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">19</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/r12L2L9qC.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">20</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">21</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Sửa thành giá tiền âm cũng không được</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">22</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/Sy2tnI95C.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">23</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">24</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Chỉ chấp nhận giá tiền &gt;0, sửa giá thành 1 thì được</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">25</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/SkxA2Ic5A.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">26</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">27</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bây giờ giá đã nhỏ hơn số dư, có thể mua hàng</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">28</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">29</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">30</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Nhấn </span><span class="cm-m-markdown cm-strong">**Place Order**</span><span class="cm-m-markdown"> đơn hàng được đặt thành công, Bài lab được </span><span class="cm-m-markdown cm-strong cm-em">***hoàn thành***</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">31</div><div class="CodeMirror-gutter-elt" style="left: 36px; width: 8px;"><div style="height: 100%;" class="authorship-gutter authorship-gutter-c1130d" title="" data-original-title="Cường17"></div></div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/H1IPTUqqC.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -57px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">32</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div></div></div></div></div></div><div style="position: absolute; height: 50px; width: 1px; border-bottom: 0px solid transparent; top: 1479px;"></div><div class="CodeMirror-gutters" style="left: 0px; height: 1529px;"><div class="CodeMirror-gutter CodeMirror-linenumbers" style="width: 36px;"></div><div class="CodeMirror-gutter authorship-gutters"></div><div class="CodeMirror-gutter CodeMirror-foldgutter"></div></div></div></div><div class="container-thin template-menu font-system-code text-text-subtle" style="display: none;">
  <div class="flex flex-col gap-6 p-4">
    <div class="github-signin-sync" style="display: none">
      <p class="menu-tip" data-i18n="github.sync.empty-note.sign-in-tip" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
        Sign in to import from GitHub:
      </p>
      <button class="neo-btn menu-item ui-signin" data-toggle="modal" data-target=".signin-modal">
        <span data-i18n="github.sync.empty-note.sign-in" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
          Sign in to HackMD
        </span>
      </button>
    </div>
    <div class="github-sync flex flex-col gap-2" style="display: none">
      <span class="menu-tip" data-i18n="github.sync.empty-note.sync-tip" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
        Link to GitHub:
      </span>
      <span class="flex flex-row flex-wrap gap-2">
        <button class="neo-btn menu-item ui-github-pull">
          <i class="ph ph-arrow-down text-[20px] leading-[20px]"></i>
          <span data-i18n="github.sync.pull-github" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
            Pull from GitHub
          </span>
        </button>
        <button class="neo-btn menu-item ui-github-push">
          <i class="ph ph-arrow-up text-[20px] leading-[20px]"></i>
          <span data-i18n="github.sync.push-github" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
            Push to GitHub
          </span>
        </button>
      </span>
    </div>
    <div class="-mb-2 flex flex-col gap-2">
      <span class="menu-tip" data-i18n="template.menu-tip" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">
        Or start with a template:
      </span>
      <span class="inline text-[0px]">
        <span class="ui-template-menu-list inline"></span>
        <button class="neo-btn menu-item more-template ui-more-template mr-2 mb-2" tabindex="-1" data-toggle="modal" data-target="#templateModal">
          <span data-i18n="template.more-templates" data-i18n-options="{&quot;provider&quot;:&quot;GitHub&quot;}">More templates</span>
          <i class="ph ph-caret-right text-[20px] leading-[20px]"></i>
        </button>
      </span>
    </div>
  </div>
</div><div class="
    hmd-flex hmd-justify-between status-bar
    border-0 border-t-1 border-solid border-border-default
    font-system font-medium text-text-subtle bg-background-subtler text-xs leading-xs
">
    <div class="hmd-flex status-info hmd-flex-one">
        <div class="hmd-ph-1">
            <div class="status-cursor">
              <span class="status-line-column">Line 11, Columns 1</span>
              <span class="status-selection"> — Selected 50 columns</span>
            </div>
            <div class="status-file text-text-subtler"> — 32 Lines</div>
        </div>
        <div class="status-nyancat">
            <div class="bg"></div>
            <div class="nyancat"></div>
        </div>
    </div>
    <div class="status-indicators">
        <div class="status-length px-2" data-toggle="popover" data-original-title="" title="You could write up to 100000 characters in this note." style="color: currentcolor;">Length 1245</div>
        <div class="status-preferences dropup toggle-dropdown pull-right inline-flex justify-center items-center px-1.5">
            <a id="preferencesLabel" class="ui-preferences-label text-uppercase text-normal leading-[14px] h-3.5 inline-block" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false" title="Click to change preferences" data-i18n="[title]editor.status-bar.preferences.title">
                <i class="ph ph-wrench"></i>
            </a>
            <ul class="dropdown-menu" aria-labelledby="preferencesLabel">
                <li class="ui-preferences-override-browser-keymap"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.allow-override-browser-keymap">Allow override browser keymap</span></label></a></li>
                <li class="ui-preferences-show-editor-toolbar"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.show-editor-toolbar">Show editor toolbar</span></label></a></li>
                <li class="ui-preferences-enable-shortcut-keys-for-table"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-shortcut-keys-for-table">Enable shortcut keys for table</span></label></a></li>
                <li class="ui-preferences-enable-word-wrap"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-word-wrap">Enable word wrap</span></label></a></li>
                <li class="ui-preferences-enable-smart-paste"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-smart-paste">Enable smart paste</span></label></a></li>
                <li class="ui-preferences-enable-relative-linenumber"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-relative-line-number">Enable relative line number</span></label></a></li>
                <li class="ui-preferences-enable-continue-list-2"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-continue-list">Auto increase list number</span></label></a></li>
                <li class="ui-preferences-enable-indent-guide"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-indent-guide">Enable indent guide</span></label></a></li>
                <li class="ui-preferences-enable-activate-power-mode"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.activate-power-mode">Activate power mode</span></label></a></li>
                <li class="ui-preferences-enable-nyanbar"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-nyanbar">What does the red panda say?</span></label></a></li>
                <li class="ui-preferences-enable-connection-debugger" style="display: none;"><a><label><input type="checkbox"><span data-i18n="editor.status-bar.preferences.enable-connection-debugger">Enable connection debugger</span></label></a></li>
            </ul>
        </div>
        <div class="status-keymap dropup pull-right px-2">
            <a id="keymapLabel" class="ui-keymap-label text-uppercase" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false" title="Click to change keymap" data-i18n="[title]editor.status-bar.keymap.title">sublime</a>
            <ul class="dropdown-menu" aria-labelledby="keymapLabel">
                <li class="ui-keymap-sublime"><a>Sublime</a></li>
                <li class="ui-keymap-emacs"><a>Emacs</a></li>
                <li class="ui-keymap-vim"><a>Vim</a></li>
            </ul>
        </div>
        <div class="status-breaks px-2" style="">
            <a class="ui-breaks-toggle" data-i18n="editor.status-bar.status-breaks">Breaks</a>
        </div>
        <div class="status-indent px-2">
            <div class="indent-type" title="Click to switch indentation type" data-i18n="[title]editor.status-bar.status-indent.indent-type;editor.status-bar.space">Spaces:</div>
            <div class="indent-width-label" title="Click to change indentation size" data-i18n="[title]editor.status-bar.status-indent.indent-width-label">4</div>
            <input class="hidden indent-width-input" type="number" min="1" max="10" maxlength="2" size="2">
        </div>
        <div class="status-theme dropup inline-flex justify-center items-center px-1.5">
            <a id="themeLabel" class="ui-theme-label text-uppercase text-normal leading-[14px] h-3.5 inline-block" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false" title="Select theme" data-i18n="[title]editor.status-bar.select-theme">
                <i class="ph ph-paint-brush"></i>
            </a>
            <ul class="dropdown-menu" aria-labelledby="themeLabel" style="overflow: auto; max-height: 618.8px;">
            <li value="default"><a>Light</a></li><li value="one-dark"><a>One Dark</a></li><li value="neo-light"><a>Neo Light</a></li><li value="neo-dark" class="active"><a>Neo Dark (Default)</a></li><li value="monokai"><a>Monokai</a></li><li value="solarized dark"><a>Solarized Dark</a></li><li value="solarized light"><a>Solarized Light</a></li><li value="dracula"><a>Dracula</a></li><li value="material"><a>Material</a></li><li value="nord"><a>Nord</a></li><li value="panda-syntax"><a>Panda</a></li><li value="ayu-dark"><a>Ayu Dark</a></li><li value="ayu-mirage"><a>Ayu Mirage</a></li><li value="tomorrow-night-bright"><a>Tomorror Night Bright</a></li><li value="tomorrow-night-eighties"><a>Tomorror Night Eighties</a></li><li value="ctp-latte"><a>Catppuccin Latte</a></li><li value="ctp-frappe"><a>Catppuccin Frappé</a></li><li value="ctp-macchiato"><a>Catppuccin Macchiato</a></li><li value="ctp-mocha"><a>Catppuccin Mocha</a></li></ul>
        </div>
        <div class="status-spellcheck inline-flex justify-center items-center px-1.5">
            <a class="ui-spellcheck-toggle text-normal leading-[14px] h-3.5 inline-block" title="Toggle spellcheck" data-i18n="[title]editor.status-bar.status-spellcheck"><i class="ph ph-check"></i></a>
        </div>
        <div class="status-linter inline-flex justify-center items-center px-1.5">
            <a class="ui-linter-toggle text-normal leading-[14px] h-3.5 inline-block" title="Toggle linter" data-i18n="[title]editor.status-bar.status-linter"><i class="ph ph-lightbulb"></i></a>
        </div>
    </div>
</div></div>
        <div id="ui-vertical-tools" class="shrink-0 px-1.5 py-2.5 h-full border-0 border-l-1 border-solid border-border-default bg-background-subtler hidden-xs" style="display: none;"><div class="flex h-full w-6 flex-col text-icon-subtle"><button class="p-0 m-0 bg-transparent border-none text-5 leading-[20px] flex h-6 w-6 items-center justify-center rounded hocus:bg-element-bg-hover hocus:text-icon-emphasize" data-toggle="tooltip" data-placement="left" data-offset="0,5" data-original-title="Suggest edit"><i class="ph ph-pencil-simple-line"></i></button></div></div>
        <div id="ui-edit-mode-portal" class="z-[1050] hidden-xs portal-enabled" style="display: none;"><div class="ui-comment-panel-root flex flex-row-reverse fixed select-text overflow-y-auto overflow-x-hidden transition-all duration-200 top-[50px] h-[calc(100dvh-50px)] max-h-[calc(100dvh-50px)] react-resizable" style="width: 348px;"><div class="flex h-full min-w-0 flex-grow flex-col overflow-auto bg-background-sunken"><div class="ui-comment-panel-navbar sticky top-0 z-10 box-border flex flex-col text-4 leading-[16px] border-0 border-b-1 border-solid border-b-border-default border-t-1 border-t-border-default"><div class="flex flex-row items-center justify-between gap-1 bg-background-subtler py-1 pl-2 pr-4"><button class="p-0 m-0 bg-transparent border-none w-[155px] min-w-0 rounded px-3 py-2.5 text-normal leading-normal text-text-default hocus:bg-element-bg-hover hocus:text-text-emphasize" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-14" data-state="closed"><span class="flex flex-row items-center gap-1.5"><span class="flex min-w-0 flex-grow flex-row items-center gap-1.5"><i class="ph ph-chat-circle-dots text-lg leading-sm"></i><span class="min-w-0 flex-grow overflow-hidden overflow-ellipsis whitespace-nowrap text-left">Comments</span></span><i class="ph text-lg leading-sm ph-caret-down"></i></span></button><span class="flex flex-shrink-0 flex-row items-center gap-1.5 text-text-default"><button class="m-0 bg-transparent ui-comment-feedback p-1.5 text-sm leading-sm text-text-default rounded border border-solid border-border-default hocus:bg-element-bg-hover hocus:text-text-emphasize" data-tally-open="wo95EN" data-tally-emoji-text="👋" data-tally-emoji-animation="wave">Feedback</button><button class="rounded px-2.5 py-2 text-normal font-normal leading-normal bg-transparent text-text-default border-none focus:border focus:border-solid hocus:bg-element-bg-hover focus:border-element-border-hover hocus:text-text-emphasize focus:shadow-[0_0_0_2px_#77777733] disabled:bg-element-bg-disabled disabled:border-element-border-disabled disabled:text-element-text-disabled disabled:hocus:bg-element-bg-disabled disabled:hocus:border-element-border-disabled disabled:hocus:text-element-text-disabled disabled:border disabled:border-solid disabled:hocus:border disabled:hocus:border-solid hidden" data-toggle="tooltip" data-original-title="Pin right panel"><i class="ph ph-push-pin" aria-hidden="true"></i></button><button class="m-0 bg-transparent border-none inline-flex cursor-pointer items-center justify-center p-1.5 text-[16px] leading-sm"><i class="ph ph-x" aria-hidden="true"></i></button></span></div></div><div class="mt-20 flex flex-col items-center gap-5 px-[58.5px] text-center"><span class="px-[30px] py-3"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/new-comment-placeholder-dark.svg"></span><span class="flex flex-col items-center gap-3"><span class="text-normal font-semibold leading-normal text-text-default">There is no comment</span><span class="text-sm leading-sm text-text-subtle">Select some text and then click Comment, or simply add a comment to this page from below to start a discussion.</span></span></div><div class="flex flex-col gap-2.5 p-2.5"></div><div class="flex-grow"></div><div class="ui-anchorless-comment-input-container sticky bottom-0 w-full border-0 border-solid bg-background-subtler rounded-t-md border-t-1 border-border-default p-4"><div class="flex w-full flex-col gap-2"><div class="ui-comment-input-container relative"><textarea class="invisible absolute w-full resize-none border border-solid p-3 text-normal leading-normal" rows="1" readonly=""></textarea><textarea class="!placeholder:text-text-subtler p-3 text-normal leading-normal text-text-default w-full resize-none rounded-[3px] border border-solid border-border-default bg-background-subtler focus-within:border-border-subtle focus-within:bg-background-default focus:outline-none hocus:border-border-subtle" placeholder="Add a comment...." rows="1" maxlength="1000"></textarea><div class="text-complete-container fixed [&amp;&gt;.dropdown-menu]:!absolute" style="top: 0px;"></div></div><div class="flex-row justify-end gap-1.5 hidden"><button class="rounded py-2 text-normal font-normal leading-normal flex bg-transparent text-text-default border border-solid border-border-default hocus:bg-element-bg-hover hocus:border-element-border-hover hocus:text-text-emphasize focus:shadow-[0_0_0_2px_#77777733] disabled:bg-element-bg-disabled disabled:border-element-border-disabled disabled:text-element-text-disabled disabled:hocus:bg-element-bg-disabled disabled:hocus:border-element-border-disabled disabled:hocus:text-element-text-disabled disabled:border disabled:border-solid disabled:hocus:border disabled:hocus:border-solid px-3.5">Discard</button><button class="rounded text-normal font-normal leading-normal flex bg-background-primary-default text-white border-none hover:bg-background-primary-hover focus:bg-background-primary-focus focus:shadow-[0_0_0_2px_#453AFF33] disabled:bg-background-primary-disabled disabled:opacity-[0.65] px-[15px] py-[9px]" disabled="">Send</button></div></div></div></div><span class="ui-right-panel-resize-handle relative cursor-ew-resize select-none pl-[5px] border-0 border-r-2 border-l-1 border-solid border-r-border-default border-l-transparent hocus:border-r-[3px] hocus:border-l-0 hocus:border-r-border-subtler"></span></div></div>
    <div class="ui-resizable-handle ui-resizable-e" style="z-index: 90; display: none;"><button class="btn btn-lg btn-default ui-sync-toggle" title="Toggle sync scrolling" data-i18n="[title]editor.toggle-sync-scrolling" style="display: none;"><i class="ph ph-link-simple"></i></button></div></div>
    <div class="relative h-full ui-view-area" style="">
        <div class="ui-infobar container-fluid unselectable hidden-print comment-enabled" style="visibility: visible;">
            <small class="pull-left hmd-mt-1/2">
                <span class="ui-owner hmd-dn" style="display: none;">
                     <a class="ui-user-icon small user-card-popover" target="_blank" style="background-image:url(https://avatars.githubusercontent.com/u/72690085?s=96)" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A" data-toggle="popover" data-original-title="" title=""></a>
                    &nbsp;<span class="text-uppercase">owned this note</span>
                </span>

                <span class="ui-owner-team hmd-dn" style="display: none;">
                     <a class="ui-user-icon small" target="_blank"></a>
                    &nbsp;<span class="text-uppercase">owned this note</span>
                </span>

                <span class="ui-lastchangeuser hmd-dn" style="display: inline;">
                     <a class="ui-user-icon small user-card-popover" target="_blank" style="background-image:url(https://avatars.githubusercontent.com/u/72690085?s=96)" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A" data-toggle="popover" data-original-title="" title=""></a>
                    <span class="text-uppercase ui-status-lastchange" title="T4, 14 Th08 2024 23:39">changed 6 phút trước</span>
                </span>

                <span class="ui-no-lastchangeuser hmd-dn" style="display: none;">
                     <i class="ph ph-clock w-4.5 inline-flex justify-center" style="width: 18px;"></i>
                    <span class="text-uppercase ui-status-lastchange" title="T4, 14 Th08 2024 23:39">changed 6 phút trước</span>
                </span>

                <span class="ui-more-info" data-toggle="popover" style="" data-original-title="" title="">
                     <i class="ph-fill ph-info text-text-subtler text-[13px] leading-[13px] p-[1.5px]" aria-hidden="true"></i>

                    <div class="more-info-raw hmd-dn">
                        <span class="ui-published-note note-status-row hmd-dn items-center gap-1.5 text-text-subtle [&amp;_a]:text-text-subtle [&amp;_a]:hocus:text-text-subtle" style="display: none;">
                            <i class="ph-fill ph-globe-hemisphere-west text-[20px] leading-lg" aria-hidden="true"></i>
                            <span>Published</span>
                        </span>

                        <span class="ui-connectedGithub note-status-row text-text-subtle [&amp;_a]:text-text-subtle [&amp;_a]:hocus:text-text-subtle leading-lg hmd-db">
                            <span class="flex flex-row gap-1.5">
                                <i class="text-[20px] leading-lg w-5 text-center fa fa-github"></i>
                                <span>Linked with GitHub</span>
                            </span>
                            <span class="flex flex-row gap-1.5">
                                <span class="w-5"></span>
                                <a class="file-path" target="_blank" href="https://github.com/QuocCuong17/SafeGate_2024_Write_Up/blob/main/PortSwigger/Business%20logic%20vulnerabilities/Lab%20#1:%20Excessive%20trust%20in%20client-side%20controls.md">QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md</a>
                            </span>
                        </span>
                    </div>
                </span>
            </small>

            <span class="pull-right flex gap-0.5">
                
                    <span class="community-button ui-like" data-toggle="tooltip" data-placement="bottom" title="" data-original-title="Like">
                        <i class="ph ph-heart"></i>
                        <span class="count" style="display: none;"></span>
                    </span>
                    <span class="community-button ui-bookmark" data-toggle="tooltip" data-placement="bottom" title="" data-original-title="Bookmark">
                        <i class="ph ph-bookmark-simple"></i>
                    </span>
                
                <span class="ui-view-theme-select-root"><button class="rounded px-2.5 py-2 text-normal font-normal leading-normal flex bg-transparent text-text-default border-none focus:border focus:border-solid hocus:bg-element-bg-hover focus:border-element-border-hover hocus:text-text-emphasize focus:shadow-[0_0_0_2px_#77777733] disabled:bg-element-bg-disabled disabled:border-element-border-disabled disabled:text-element-text-disabled disabled:hocus:bg-element-bg-disabled disabled:hocus:border-element-border-disabled disabled:hocus:text-element-text-disabled disabled:border disabled:border-solid disabled:hocus:border disabled:hocus:border-solid community-button ui-view-theme gap-0.5 focus:p-[9px]" data-toggle="tooltip" data-placement="bottom" data-original-title="Select theme to preview" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-13" data-state="closed"><i class="ph ph-paint-brush"></i></button></span>
                
                <span class="ui-notification dropdown pull-right is-watch" style="">
                    <span id="notificationLabel" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                        <div data-no-email="" class="ui-notification-status community-button" title="" data-toggle="tooltip" data-placement="bottom" data-original-title="Subscribe">
                            <i class="ph-fill ph-bell"></i>
                            <span class="text hidden-xs">
                                Subscribed
                                <i class="ph ph-caret-down"></i>
                                <i class="ph ph-caret-up"></i>
                            </span>
                        </div>
                    </span>
                    <ul class="dropdown-menu" aria-labelledby="notificationLabel">
                        <li class="ui-notification-watch notification-menu-item is-checked">
                            <i class="ph ph-check"></i>
                            <i class="ph-fill ph-bell"></i>
                            <div class="info">
                                <div class="title">
                                    Any changes
                                </div>
                                <div class="description">
                                    Be notified of any changes
                                </div>
                            </div>
                        </li>
                        <li class="ui-notification-mention notification-menu-item">
                            <i class="ph ph-check"></i>
                            <i class="ph ph-at"></i>
                            <div class="info">
                                <div class="title">
                                    Mention me
                                </div>
                                <div class="description">
                                    Be notified of mention me
                                </div>
                            </div>
                        </li>
                        <li class="divider"></li>
                        <!--
                            <li class="ui-notification-list notification-menu-item"><span><a href="#"><i class="fa fa-list-ul fa-fw"></i>My subscribed list</a></span></li>
                        -->
                        <li class="ui-notification-unsubscribe notification-menu-item">
                            <i class="ph ph-bell-slash"></i>
                            <div class="info">
                                <div class="title">
                                    Unsubscribe
                                </div>
                            </div>
                        </li>
                    </ul>
                    <span class="ui-notification-subscribe community-button">
                        <i class="ph ph-bell"></i>
                        <span class="text hidden-xs">Subscribe</span>
                    </span>
                </span>
                
                
                    <div class="visible-xs" style="margin-top: 10px;"></div>
                
            </span>
            <div class="ui-comment-app" id="hackmd-app" style="right: -64px; width: 64px;">
                <div id="comment-app"><div class="open-comments open-comments-panel fixed z-[1049] !w-16"><div><button class="m-0 ui-open-comments flex gap-1 items-center p-2.5 h-[38px] text-normal leading-normal text-text-default bg-background-default rounded border border-solid border-border-default hover:bg-element-bg-hover hover:text-text-emphasize"><i class="ph ph-chat-circle-dots text-5 leading-sm" aria-hidden="true"></i><span class="text">0</span></button></div></div><div class="comments-scroller"><div class="comments-containers"></div></div></div>
            </div><div id="hmd-submenu-portal"></div>
        </div>

        <div class="ui-comment-app" style="right: -64px; width: 64px;"><div id="comments-panel-portal" style="display: none" theme="dark"><div class="ui-comment-panel-root flex flex-row-reverse fixed select-text overflow-y-auto overflow-x-hidden transition-all duration-200 top-[50px] h-[calc(100dvh-50px)] max-h-[calc(100dvh-50px)] react-resizable" style="width: 348px;"><div class="flex h-full min-w-0 flex-grow flex-col overflow-auto bg-background-sunken"><div class="ui-comment-panel-navbar sticky top-0 z-10 box-border flex flex-col text-4 leading-[16px] border-0 border-b-1 border-solid border-b-border-default border-t-1 border-t-border-default"><div class="flex flex-row items-center justify-between gap-1 bg-background-subtler py-1 pl-2 pr-4"><button class="p-0 m-0 bg-transparent border-none w-[155px] min-w-0 rounded px-3 py-2.5 text-normal leading-normal text-text-default hocus:bg-element-bg-hover hocus:text-text-emphasize" type="button" aria-haspopup="dialog" aria-expanded="false" aria-controls="radix-15" data-state="closed"><span class="flex flex-row items-center gap-1.5"><span class="flex min-w-0 flex-grow flex-row items-center gap-1.5"><i class="ph ph-chat-circle-dots text-lg leading-sm"></i><span class="min-w-0 flex-grow overflow-hidden overflow-ellipsis whitespace-nowrap text-left">Comments</span></span><i class="ph text-lg leading-sm ph-caret-down"></i></span></button><span class="flex flex-shrink-0 flex-row items-center gap-1.5 text-text-default"><button class="m-0 bg-transparent ui-comment-feedback p-1.5 text-sm leading-sm text-text-default rounded border border-solid border-border-default hocus:bg-element-bg-hover hocus:text-text-emphasize" data-tally-open="wo95EN" data-tally-emoji-text="👋" data-tally-emoji-animation="wave">Feedback</button><button class="rounded px-2.5 py-2 text-normal font-normal leading-normal flex bg-transparent text-text-default border-none focus:border focus:border-solid hocus:bg-element-bg-hover focus:border-element-border-hover hocus:text-text-emphasize focus:shadow-[0_0_0_2px_#77777733] disabled:bg-element-bg-disabled disabled:border-element-border-disabled disabled:text-element-text-disabled disabled:hocus:bg-element-bg-disabled disabled:hocus:border-element-border-disabled disabled:hocus:text-element-text-disabled disabled:border disabled:border-solid disabled:hocus:border disabled:hocus:border-solid" data-toggle="tooltip" data-original-title="Pin right panel"><i class="ph ph-push-pin" aria-hidden="true"></i></button><button class="m-0 bg-transparent border-none inline-flex cursor-pointer items-center justify-center p-1.5 text-[16px] leading-sm"><i class="ph ph-x" aria-hidden="true"></i></button></span></div></div><div class="mt-20 flex flex-col items-center gap-5 px-[58.5px] text-center"><span class="px-[30px] py-3"><img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/new-comment-placeholder-dark.svg"></span><span class="flex flex-col items-center gap-3"><span class="text-normal font-semibold leading-normal text-text-default">There is no comment</span><span class="text-sm leading-sm text-text-subtle">Select some text and then click Comment, or simply add a comment to this page from below to start a discussion.</span></span></div><div class="flex flex-col gap-2.5 p-2.5"></div><div class="flex-grow"></div><div class="ui-anchorless-comment-input-container sticky bottom-0 w-full border-0 border-solid bg-background-subtler rounded-t-md border-t-1 border-border-default p-4"><div class="flex w-full flex-col gap-2"><div class="ui-comment-input-container relative"><textarea class="invisible absolute w-full resize-none border border-solid p-3 text-normal leading-normal" rows="1" readonly=""></textarea><textarea class="!placeholder:text-text-subtler p-3 text-normal leading-normal text-text-default w-full resize-none rounded-[3px] border border-solid border-border-default bg-background-subtler focus-within:border-border-subtle focus-within:bg-background-default focus:outline-none hocus:border-border-subtle" placeholder="Add a comment...." rows="1" maxlength="1000"></textarea><div class="text-complete-container fixed [&amp;&gt;.dropdown-menu]:!absolute" style="top: 0px;"></div></div><div class="flex-row justify-end gap-1.5 hidden"><button class="rounded py-2 text-normal font-normal leading-normal flex bg-transparent text-text-default border border-solid border-border-default hocus:bg-element-bg-hover hocus:border-element-border-hover hocus:text-text-emphasize focus:shadow-[0_0_0_2px_#77777733] disabled:bg-element-bg-disabled disabled:border-element-border-disabled disabled:text-element-text-disabled disabled:hocus:bg-element-bg-disabled disabled:hocus:border-element-border-disabled disabled:hocus:text-element-text-disabled disabled:border disabled:border-solid disabled:hocus:border disabled:hocus:border-solid px-3.5">Discard</button><button class="rounded text-normal font-normal leading-normal flex bg-background-primary-default text-white border-none hover:bg-background-primary-hover focus:bg-background-primary-focus focus:shadow-[0_0_0_2px_#453AFF33] disabled:bg-background-primary-disabled disabled:opacity-[0.65] px-[15px] py-[9px]" disabled="">Send</button></div></div></div></div><span class="ui-right-panel-resize-handle relative cursor-ew-resize select-none pl-[5px] border-0 border-r-2 border-l-1 border-solid border-r-border-default border-l-transparent hocus:border-r-[3px] hocus:border-l-0 hocus:border-r-border-subtler"></span></div></div></div>

        <div id="doc" class="markdown-body container-fluid comment-enabled" data-hard-breaks="false"><h1 class="part" data-startline="1" data-endline="1" id="💡Lab-Excessive-trust-in-client-side-controls" data-id="💡Lab-Excessive-trust-in-client-side-controls"><a class="anchor hidden-xs" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#%F0%9F%92%A1Lab-Excessive-trust-in-client-side-controls" title="💡Lab-Excessive-trust-in-client-side-controls" smoothhashscroll=""><span class="octicon octicon-link ph ph-link-simple-horizontal"></span></a><strong data-position="2" data-size="0"><span data-position="4" data-size="46">💡Lab: Excessive trust in client-side controls</span></strong></h1><hr class=""><h3 class="part" data-startline="3" data-endline="3" id="Mô-tả" data-id="Mô-tả"><a class="anchor hidden-xs" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%C3%B4-t%E1%BA%A3" title="Mô-tả" smoothhashscroll=""><span class="octicon octicon-link ph ph-link-simple-horizontal"></span></a><strong data-position="61" data-size="0"><span data-position="63" data-size="5">Mô tả</span></strong></h3><p class="part" data-startline="4" data-endline="4" data-position="71" data-size="0"><span data-position="71" data-size="19">Bài lab này có một </span><strong data-position="90" data-size="0"><span data-position="92" data-size="13">lỗ hổng logic</span></strong><span data-position="107" data-size="4"> do </span><strong data-position="111" data-size="0"><span data-position="113" data-size="20">giá trị của sản phẩm</span></strong><span data-position="135" data-size="28"> được kiểm soát và xác thực </span><strong data-position="163" data-size="0"><span data-position="165" data-size="16">trên phía client</span></strong><span data-position="183" data-size="132"> thay vì phía server. Điều này cho phép kẻ tấn công thay đổi giá trị của sản phẩm khi gửi yêu cầu mua hàng đến server, dẫn đến việc </span><strong data-position="315" data-size="0"><span data-position="317" data-size="19">mua hàng với giá $0</span></strong><span data-position="338" data-size="1">.</span></p><h3 class="part" data-startline="6" data-endline="6" id="Mục-tiêu" data-id="Mục-tiêu"><a class="anchor hidden-xs" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%E1%BB%A5c-ti%C3%AAu" title="Mục-tiêu" smoothhashscroll=""><span class="octicon octicon-link ph ph-link-simple-horizontal"></span></a><strong data-position="345" data-size="0"><span data-position="347" data-size="8">Mục tiêu</span></strong></h3><p class="part" data-startline="7" data-endline="7" data-position="358" data-size="0"><span data-position="358" data-size="38">Mục tiêu của bài lab này là khai thác </span><strong data-position="396" data-size="0"><span data-position="398" data-size="13">lỗ hổng logic</span></strong><span data-position="413" data-size="83"> do sự tin tưởng quá mức vào kiểm soát phía client để lấy được hàng hóa với giá $0.</span></p><hr class=""><p class="part" data-startline="10" data-endline="14" data-position="503" data-size="0"><span data-position="503" data-size="26">Đăng nhập với wiener/peter</span>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/Hy78oI99C.png" alt="image" class="offline-handled error-handled" data-position="530" data-size="50" loading="lazy">
<br>
<span data-position="586" data-size="36">Test thử chức năng thêm vào giỏ hàng</span>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/BkQii859R.png" alt="image" class="offline-handled error-handled" data-position="623" data-size="50" loading="lazy"></p><p class="part" data-startline="16" data-endline="16" data-position="675" data-size="0"><span data-position="675" data-size="42">Bắt request gửi sang Repeater để phân tích</span></p><p class="part in-view" data-startline="18" data-endline="19" data-position="719" data-size="0"><span data-position="719" data-size="99">Sửa giá về 0, 1 respone 302 được trả về nhưng trong giỏ hàng vẫn trống -&gt; khả năng không nhận giá 0</span>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/r12L2L9qC.png" alt="image" class="offline-handled error-handled" data-position="819" data-size="50" loading="lazy"></p><p class="part in-view" data-startline="21" data-endline="22" data-position="871" data-size="0"><span data-position="871" data-size="37">Sửa thành giá tiền âm cũng không được</span>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/Sy2tnI95C.png" alt="image" class="offline-handled error-handled" data-position="909" data-size="50" loading="lazy"></p><p class="part in-view" data-startline="24" data-endline="25" data-position="961" data-size="0"><span data-position="961" data-size="51">Chỉ chấp nhận giá tiền &gt;0, sửa giá thành 1 thì được</span>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/SkxA2Ic5A.png" alt="image" class="offline-handled error-handled" data-position="1013" data-size="50" loading="lazy"></p><p class="part in-view" data-startline="27" data-endline="27" data-position="1065" data-size="0"><span data-position="1065" data-size="45">Bây giờ giá đã nhỏ hơn số dư, có thể mua hàng</span></p><p class="part in-view" data-startline="30" data-endline="31" data-position="1113" data-size="0"><span data-position="1113" data-size="5">Nhấn </span><strong data-position="1118" data-size="0"><span data-position="1120" data-size="11">Place Order</span></strong><span data-position="1133" data-size="44"> đơn hàng được đặt thành công, Bài lab được </span><em data-position="1177" data-size="0"><strong data-position="1177" data-size="0"><span data-position="1180" data-size="10">hoàn thành</span></strong></em>
<img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/H1IPTUqqC.png" alt="image" class="offline-handled error-handled" data-position="1194" data-size="50" loading="lazy"></p></div>

        <section class="absolute top-0 bottom-0 left-0 right-0 z-50 overflow-hidden slide-preview-container" style="display: none;">
            <link rel="stylesheet" href="./Lab #1_ Excessive trust in client-side controls - HackMD_files/defaultTheme.css" id="theme">
            <div class="h-full reveal">
                <div class="slides" style="display: none;"></div>
            </div>
        </section>

        <div class="ui-toc dropup unselectable hidden-print scrollspy-body scrollspy-view" style="left: 326.05px; display: none;">
            <div class="pull-left dropdown">
                <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                    <i class="fa fa-bars"></i>
                </a>
                <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel"><div class="toc"><ul class="nav">
<li class="active"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#%F0%9F%92%A1Lab-Excessive-trust-in-client-side-controls" title="💡Lab: Excessive trust in client-side controls" smoothhashscroll="">💡Lab: Excessive trust in client-side controls</a><ul class="nav">
<li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%C3%B4-t%E1%BA%A3" title="Mô tả" smoothhashscroll="">Mô tả</a></li>
<li class="active"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%E1%BB%A5c-ti%C3%AAu" title="Mục tiêu" smoothhashscroll="">Mục tiêu</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Expand all</a><a class="back-to-top" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Back to top</a><a class="go-to-bottom" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Go to bottom</a></div></ul>
            </div>
        </div>
        <div class="toc-placeholder hidden"></div>
        <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print scrollspy-body affix" data-spy="affix" style="top: 106.8px; max-width: min(364px, 15vw); right: 1112px;"><div class="toc"><ul class="nav">
<li class="active"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#%F0%9F%92%A1Lab-Excessive-trust-in-client-side-controls" title="💡Lab: Excessive trust in client-side controls" smoothhashscroll="">💡Lab: Excessive trust in client-side controls</a><ul class="nav">
<li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%C3%B4-t%E1%BA%A3" title="Mô tả" smoothhashscroll="">Mô tả</a></li>
<li class="active"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#M%E1%BB%A5c-ti%C3%AAu" title="Mục tiêu" smoothhashscroll="">Mục tiêu</a></li>
</ul>
</li>
</ul>
</div><div class="toc-menu"><a class="expand-toggle" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Expand all</a><a class="back-to-top" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Back to top</a><a class="go-to-bottom" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Go to bottom</a></div></div>
    </div>
</div>
<!-- clipboard modal -->
<div class="modal fade" id="clipboardModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from clipboard</h4>
            </div>
            <div class="modal-body">
                <div contenteditable="" data-ph="Paste your markdown or webpage here..." id="clipboardModalContent" style="overflow:auto;max-height:50vh"></div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="clipboardModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="clipboardModalConfirm">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- basic use modal -->
<div class="modal fade basic-use-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> Advanced permission required</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Your current role can only read. Ask the system administrator to acquire write and comment permission.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-primary ui-request-permission">Request permission</button>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
            </div>
        </div>
    </div>
</div>
<!-- team locked modal -->
<div class="modal fade team-locked-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> This team is disabled</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, this team is disabled. You can't edit this note.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- locked modal -->
<div class="modal fade locked-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> This note is locked</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, only owner can edit this note.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- limit modal -->
<div class="modal fade limit-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-exclamation-triangle"></i> Reach the limit</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, you've reached the max length this note can be.</h5>
                <strong>Please reduce the content or divide it to more notes, thank you!</strong>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-warning" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- gist import modal -->
<div class="modal fade" id="gistImportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from Gist</h4>
            </div>
            <div class="modal-body">
                <input type="url" class="form-control" placeholder="Paste your gist url here... (like: https://gist.github.com/username/gistid)" id="gistImportModalContent">
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="gistImportModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="gistImportModalConfirm">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- snippet import modal -->
<div class="modal fade" id="snippetImportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from Snippet</h4>
            </div>
            <div class="modal-body">
                <input type="hidden" id="snippetImportModalAccessToken">
                <input type="hidden" id="snippetImportModalBaseURL">
                <div class="ui-field-contain" style="display:table;margin-bottom:10px;width:100%;">
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Project:</label>
                        <select class="form-control" id="snippetImportModalProjects" style="display:table-cell;" disabled="disabled">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Projects</option>
                        </select>
                    </div>
                    <div style="display:table-row;">
                        <label style="display:table-cell;">Snippet:</label>
                        <select class="form-control" id="snippetImportModalSnippets" style="display:table-cell;" disabled="disabled">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Snippets</option>
                        </select>
                    </div>
                </div>
                <p class="snippet-import-or">or</p>
                <input type="url" class="form-control" placeholder="/projects/:id/snippets/:snippet_id" id="snippetImportModalContent" disabled="disabled">
            </div>
            <div class="modal-footer">
                <span id="snippetImportModalLoading"><i class="fa fa-refresh fa-spin fa-fw"></i></span>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="snippetImportModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="snippetImportModalConfirm" disabled="disabled">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- snippet export modal -->
<div class="modal fade" id="snippetExportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Export to Snippet</h4>
            </div>
            <div class="modal-body">
                <input type="hidden" id="snippetExportModalAccessToken">
                <input type="hidden" id="snippetExportModalBaseURL">
                <div class="ui-field-contain" style="display:table;margin-bottom:10px;width:100%;">
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Title:</label>
                        <input class="form-control" placeholder="new snippet" type="text" id="snippetExportModalTitle">
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">File Name:</label>
                        <input class="form-control" placeholder="new_snippet.md" type="text" id="snippetExportModalFileName">
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Project:</label>
                        <select class="form-control" id="snippetExportModalProjects" style="display:table-cell;">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Projects</option>
                        </select>
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Visibility:</label>
                        <select class="form-control" id="snippetExportModalVisibility" style="display:table-cell;">
                            <option value="" selected="selected" disabled="disabled">Select Visibility Level</option>
                            <option value="0">Private</option>
                            <option value="10">Internal</option>
                        </select>
                    </div>
                </div>
            </div>
            <div class="modal-footer">
                <span id="snippetExportModalLoading"><i class="fa fa-refresh fa-spin fa-fw"></i></span>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-primary" id="snippetExportModalConfirm">Export</button>
            </div>
        </div>
    </div>
</div>
<!-- delete modal -->
<div class="modal fade delete-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Are you sure?</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5 class="ui-delete-modal-msg">Do you really want to delete this note?</h5>
                <strong class="ui-delete-modal-item">All users will lost their connection.</strong>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger ui-delete-modal-confirm">Yes, do it!</button>
            </div>
        </div>
    </div>
</div>

<!-- template notes modal -->
<div class="modal fade template-modal" id="templateModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1000px;">
        <div class="modal-content template-content">
            <div class="modal-header">
                <button type="button" class="close ui-template-cancel visible-xs hidden-xs" style="margin-top: 2px !important; font-size: 15px !important; display: none;"><span aria-hidden="true">Cancel</span></button>
                <button type="button" class="close ui-template-close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span></button>
                <h4 class="modal-title ui-template-title" id="mySmallModalLabel"><i class="fa fa-file-image-o"></i> <span>Create a note from template</span></h4>
                <h4 class="modal-title visible-xs hidden-xs ui-template-title-xs"><i class="fa fa-file-image-o"></i> <span>Create a note from template</span></h4>
            </div>
            <div class="modal-body" style="padding: 0px; overflow-x: hidden;">
                <div class="row">
                    <div class="col-sm-8 template-preview-container hidden-xs">
                        <div>
                            <div class="ui-template-spinner unselectable hidden-print"><div class="spinner" role="progressbar" style="position: absolute; width: 0px; z-index: 2000000000; left: 50%; top: 50%;"><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-0-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(0deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-1-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(32deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-2-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(65deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-3-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(98deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-4-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(130deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-5-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(163deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-6-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(196deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-7-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(229deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-8-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(261deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-9-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(294deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-10-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(327deg) translate(30px, 0px); border-radius: 0px;"></div></div></div></div>
                            <iframe class="template-viewer" style="width: 100%; height: 100%; border: none;" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/saved_resource.html"></iframe>
                            <div class="template-empty ui-template-viewer-empty" style="display: none; margin: 0px;">
                                <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/not-available.svg">
                                <div>
                                    <div>Oops...</div>
                                    <div>This template has been removed or transferred.</div>
                                </div>
                            </div>
                        </div>
                        <button type="button" class="visible-xs btn btn-primary ui-use-template-btn-mobile">Use this template</button>
                    </div>
                    <div class="col-sm-4 template-list-container">
                        <div class="ui-templates-container">
                            <div class="border-0 border-b border-gray-200 border-solid template-button-container hmd-pa-2">
                                
                                    <button type="button" class="w-full btn btn-default ui-create-template-btn">
                                        <span style="margin-right: -20px;">
                                            Create new template
                                        </span>
                                        <i class="fa fa-plus fa-fw" style="float: right; margin-top: 3px;"></i>
                                    </button>
                                

                                <p style="margin-top: 15px; display: none;" class="template-quota-alert">
                                    <span class="template-quota-description" style="color: #777777;"></span>
                                    <br>
                                    <a target="_blank" href="https://hackmd.io/?nav=billing" class="template-quota-upgrade-now">
                                        Upgrade
                                        <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                                    </a>
                                </p>
                            </div>

                            <div class="dropdown ui-template-list-filter" style="margin: 20px;">
                                <a class="ui-template-list-filter-label" id="template-list-filter" data-filter-type="all" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><span>All</span><i class="fa fa-angle-down" aria-hidden="true" style="margin-left: 10px;"></i></a>
                                <ul class="dropdown-menu" role="menu" aria-labelledby="template-list-filter" style="right: 0px; left: auto;">
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-all" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">All</a></li>
                                    
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-default" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Default</a></li>
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-personal" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Personal</a></li>
                                    
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-team" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Team</a></li>
                                    
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-shared" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">Shared with me</a></li>
                                    
                                </ul>
                            </div>
                            <div class="template-empty ui-template-list-empty">
                                <i class="fa fa-file-image-o" aria-hidden="true"></i>
                                <div>No template.</div>
                            </div>
                            <div class="list-group ui-template-list" style="flex:1;">
                            </div>
                            <button type="button" class="btn btn-primary ui-use-template-btn hidden-xs">Use this template</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- create template modal -->
<div class="modal fade create-template-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 860px;">
        <form>
            <div class="modal-content template-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 2px; height: 17px;"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span>
                    </button>
                    <h4 class="modal-title" id="myModalLabel">Create a template</h4>
                </div>

                <div class="modal-body hmd-text-center" style="color:black; padding: 20px; padding-bottom: 10px; text-align: left;">
                    <div class="mb-5 template-quota-excceed-block">
                        <span class="template-quota-description" style="color: #777777;"></span>
                        <br>
                        <a target="_blank" href="https://hackmd.io/?nav=billing" class="template-quota-upgrade-now">
                            Upgrade
                            <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                        </a>
                    </div>


                    <div class="grid items-center grid-cols-12 form-group mb-7">
                        <label class="col-span-4 font-normal text-black-brand" for="templateName">Template name</label>

                        <input type="text" id="templateName" class="col-span-8 form-control" placeholder="Template name" aria-label="TemplateName" aria-describedby="template-name" maxlength="250" required="">
                    </div>

                    <div class="grid items-start grid-cols-12 form-group creation-method-option">
                        <label class="col-span-4 font-normal text-black-brand" for="templateName">Save as option</label>

                        <div class="col-span-8">
                            <label class="w-full font-normal ui-save-template-directly" for="save-template-directly">
                                <input type="radio" name="save-template" value="save-directly" checked="" id="save-template-directly">
                                <span class="ml-2">Save this note as a template</span>
                            </label>

                            <label class="w-full font-normal ui-save-template-as-another-template" for="save-template-as-another-template">
                                <input type="radio" name="save-template" value="save-as-another-template" id="save-template-as-another-template">
                                <span class="ml-2">Save to another note as a template</span>
                            </label>
                        </div>
                    </div>

                </div>

                <div class="modal-footer" style="border: none; padding: 20px;">
                    <button type="button" class="btn btn-default" data-dismiss="modal" style="flex:1;">Cancel</button>
                    <button type="submit" class="btn btn-primary ui-create-template-modal-confirm" style="flex:1;">Save</button>
                </div>
            </div>
        </form>
    </div>
</div>

<!-- delete template modal -->
<div class="modal fade delete-template-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content template-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 2px; height: 17px;"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Delete template</h4>
            </div>
            <div class="modal-body hmd-text-center" style="color:black; padding: 14.5px 15px; padding-bottom: 0px; text-align: left;">
                <p class="ui-delete-modal-msg" style="font-size: 15px;">Do you really want to delete this template?</p>
                <div class="form-check" style="display: flex;">
                    <input type="checkbox" class="form-check-input ui-delete-note-check" style="margin-top: 7px;" id="deleteNoteCheck">
                    <label class="form-check-label" style="margin-top: 3px; margin-left: 5px; font-weight: 400;" for="deleteNoteCheck">
                        Keep the content
                        <div style="font-size: 13px; margin-top: 5px; color: #818181; line-height: 18px;">Turn this template into a regular note and keep its content, versions, and comments.</div>
                    </label>
                </div>
            </div>
            <div class="modal-footer" style="border: none; padding: 20px 15px; display: flex;">
                <button type="button" class="btn btn-default" data-dismiss="modal" style="flex:1;">Cancel</button>
                <button type="button" class="btn btn-danger ui-delete-template-modal-confirm" style="flex:1;">Delete</button>
            </div>
        </div>
    </div>
</div>

<!-- refresh modal -->
<div class="modal fade" id="refreshModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">This page need refresh</h4>
            </div>
            <div class="modal-body">
                <div class="incompatible-version">
                    <h5>You have an incompatible client version.</h5>
                    <strong>Refresh to update.</strong>
                </div>
                <div class="new-version" style="display:none;">
                    <h5>New version available!</h5>
                    <a href="https://hackmd.io/s/release-notes" target="_blank">See releases notes here</a>
                    <br>
                    <strong>Refresh to enjoy new features.</strong>
                </div>
                <div class="user-state-changed" style="display:none;">
                    <h5>Your user state has changed.</h5>
                    <strong>Refresh to load new user state.</strong>
                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-primary" id="refreshModalRefresh">Refresh</button>
            </div>
        </div>
    </div>
</div>

<!-- signin modal -->

<div class="modal fade signin-modal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog">
        <div class="modal-content">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 10px; right: 20px; position: absolute;"><span aria-hidden="true">×</span></button>
            






    









<h3>Sign in</h3>

<form data-toggle="validator" role="form" class="form-horizontal" method="post" enctype="application/x-www-form-urlencoded" id="signin-form" novalidate="true">
    <div class="hmd-dn"><input type="hidden" name="_csrf" value="rzEb1HnF-b552DtX3-Jzr4IDXG48oPEqychI"></div>
    <div class="hmd-dn"><input type="hidden" name="create_team" value="false"></div>
    <div class="hmd-dn"><input type="hidden" name="create_paid_team" value="false"></div>
    
    <div class="form-group  ">
        <label for="email" class="control-label">Email</label>
        <label for="inputEmail" class="control-label pull-right errors">
            
        </label>
        <span class="help-block control-label with-errors pull-right" style="display: inline;"></span>
        <div class="input-block">
            
                <input type="email" class="form-control" name="email" placeholder="Your email" required="" autocomplete="email">
            
            <span class="error-sign"></span>
        </div>
    </div>
    <div class="form-group ">
        <label for="password" class="control-label">Password</label>
        <label for="inputPassword" class="control-label pull-right errors">
            
        </label>
        <span class="help-block control-label with-errors pull-right" style="display: inline;"></span>
        <div class="input-block">
            <input type="password" class="form-control" name="password" placeholder="Your password" required="" autocomplete="current-password" maxlength="128">
            <span class="error-sign"></span>
            
                <span class="control-label pull-right" style="font-size: 13px; margin-top: 5px;"><a href="https://hackmd.io/settings/forgotPassword" style="text-decoration: underline;">Forgot password</a></span>
            
        </div>
    </div>

    <div style="text-align: center; padding-top: 15px; margin-bottom: 0px;">
        <div hidden="" id="hmd-captcha" data-provider="" data-captcha-data="" class="flex justify-center"></div>

        
            <input type="submit" class="btn btn-success btn-large disabled" formaction="https://hackmd.io/login" value="Sign in">
        

        
    </div>
</form>














    
        <p class="separator">or</p>
    

    
        <p>By clicking below, you agree to our <a href="https://hackmd.io/s/terms" target="_blank">terms of service</a>.</p>
    

    












<script id="gsi-client" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/client" async="" defer="" nonce=""></script>
<script nonce="">
    function handleCredentialResponse(response) {
        const form = document.getElementById('sign-in-with-google-form')
        form.children.credential.value = response.credential
        form.children.method.value = location.href.toLowerCase() === 'https://hackmd.io/settings#general' ? 'merge' : 'login'
        form.submit()
    }
    var GSI_READY = new Promise(function (resolve) {
        function initialize () {
            google.accounts.id.initialize({
                client_id: '911617723593-drikdibvvn63slfd6kbqigo8ql1no55s.apps.googleusercontent.com',
                callback: handleCredentialResponse
            })
            const loginPath = 'https://hackmd.io/login'
            const joinPath = 'https://hackmd.io/join'
            const renderButton = function () {
                google.accounts.id.renderButton(
                    document.getElementById('sign-in-with-google-button'),
                    { type: 'standard', width: 250 }
                )
            }
            if (location.href.toLowerCase() === loginPath || location.href.toLowerCase() === joinPath) {
                renderButton()
            } else {
                $('.signin-modal').one('shown.bs.modal', function () {
                    renderButton()
                })
            }
            resolve()
        }

        window.addEventListener('load', function () { initialize() })
    })
</script>
<form class="hidden" id="sign-in-with-google-form" action="https://hackmd.io/auth/google" method="post">
    <input type="hidden" name="credential">
    <input type="hidden" name="method">
</form>


<div class="social-buttons-container">
    
    <div id="sign-in-with-google-button"></div>
    
    
    <a href="https://hackmd.io/auth/facebook" class="btn btn-lg btn-block btn-social btn-facebook">
        <i class="fa fa-facebook"></i> Sign in via Facebook
    </a>
    
    
    <a href="https://hackmd.io/auth/twitter" class="btn btn-lg btn-block btn-social btn-twitter">
        <i class="fa fa-twitter"></i> Sign in via Twitter
    </a>
    
    
    <a href="https://hackmd.io/auth/github" class="btn btn-lg btn-block btn-social btn-github">
        <i class="fa fa-github"></i> Sign in via GitHub
    </a>
    
    
    <a href="https://hackmd.io/auth/dropbox" class="btn btn-lg btn-block btn-social btn-dropbox">
        <i class="fa fa-dropbox"></i> Sign in via Dropbox
    </a>
    
    
    
      <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="bg-white btn btn-block btn-social btn-web3 bg-gray-800 hocus:bg-[#2b2b2b] text-white hocus:text-white">
          <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/wallet.svg" style="max-height: 20px; margin-top: 8px; margin-left: 6px; border: none;">
          <span class="sign-in-wallet-text">
              Sign in with Wallet
          </span>

          <div class="inline-flex items-center justify-between w-full hidden web3-wallet-info">
              <span>
                   Wallet
                   (
                    <span class="web3-wallet-address"></span>
                   )
              </span>

              <i class="fa fa-arrow-right" aria-hidden="true"></i>
          </div>
      </a>

      <small class="web3-wallet-info hidden text-left hocus:text-white underline hocus:underline block pt-2 ui-disconnect-connected-wallets text-gray-600 cursor-pointer">
          Connect another wallet
      </small>
    
</div>




    <div>
        <p>New to HackMD? <a href="https://hackmd.io/join" class="plausible-event-name=LoginModalSignUp">Sign up</a></p>
    </div>




        </div>
    </div>
</div>

<!-- help modal -->
<div class="modal fade help-modal" id="help-modal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header text-text-default">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel"><i class="fa fa-question"></i> Help</h4>
            </div>
            <div class="modal-body">
                <div class="row">
                    <div class="col-lg-3">
                        <div class="dropdown" style="margin-bottom: 30px;">
                            <button id="helpLangDropdown" type="button" class="btn btn-default modal-lang-btn" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Switch language
                                <span class="caret"></span>
                            </button>
                            <ul class="dropdown-menu" id="modal-lang-menu" aria-labelledby="helpLangDropdown">
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="en">
                                    <i class="fa fa-check"></i> English
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="zh">
                                    <i class="fa fa-check"></i> 中文
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="fr">
                                    <i class="fa fa-check"></i> Français
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="de">
                                    <i class="fa fa-check"></i> Deutsch
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="ja">
                                    <i class="fa fa-check"></i> 日本語
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="es">
                                    <i class="fa fa-check"></i> Español
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="ca">
                                    <i class="fa fa-check"></i> Català
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="el">
                                    <i class="fa fa-check"></i> Ελληνικά
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="pt">
                                    <i class="fa fa-check"></i> Português
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="it">
                                    <i class="fa fa-check"></i> italiano
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="tr">
                                    <i class="fa fa-check"></i> Türkçe
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="ru">
                                    <i class="fa fa-check"></i> Русский
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="nl">
                                    <i class="fa fa-check"></i> Nederlands
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="hr">
                                    <i class="fa fa-check"></i> hrvatski jezik
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="pl">
                                    <i class="fa fa-check"></i> język polski
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="uk">
                                    <i class="fa fa-check"></i> Українська
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="hi">
                                    <i class="fa fa-check"></i> हिन्दी
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="sv">
                                    <i class="fa fa-check"></i> svenska
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="eo">
                                    <i class="fa fa-check"></i> Esperanto
                                </a></li>
                                <li><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="modal-lang-menu-item" data-lang="da">
                                    <i class="fa fa-check"></i> dansk
                                </a></li>
                            </ul>
                        </div>
                        <div class="modal-side-menu-block">
                            <h4>Documents</h4>
                            <p>
                                <a href="https://hackmd.io/c/tutorials" title="Tutorials" target="_blank">Tutorials <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-book" title="Book Mode Tutorial" target="_blank">Book Mode Tutorial <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-slide-deck" title="Slide Mode Tutorial" target="_blank">Slide Example <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/yaml-metadata" title="YAML Metadata" target="_blank">YAML Metadata <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>

                        
                        <div class="modal-side-menu-block">
                            <h4>Contacts</h4>
                            <p>
                                <a href="https://facebook.com/hackmdio" target="_blank">Facebook <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://twitter.com/hackmdio" target="_blank">Twitter <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://discord.gg/yDw3AJbmwx" target="_blank">Discord <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                                <p>
                                    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" data-toggle="modal" data-target=".feedback-modal">Feedback <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                                </p>
                            
                            <p>
                                <span>Send us email</span>
                                <br>
                                <span class="view-email-address"></span>
                            </p>
                        </div>
                        

                        <div class="modal-side-menu-block">
                            <h4>Resources</h4>
                            <p>
                                <a href="https://hackmd.io/s/release-notes" title="Tutorials" target="_blank">Releases <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                            <p>
                                <a href="https://hackmd.io/pricing" title="YAML Metadata" target="_blank">Pricing <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                            <p>
                                <a href="https://blog.hackmd.io/" title="Blog" target="_blank">Blog <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>

                        <div class="modal-side-menu-block">
                            <h4>Policy</h4>
                            <p>
                                <a href="https://hackmd.io/s/terms" title="Tutorials" target="_blank">Terms <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/s/privacy" title="YAML Metadata" target="_blank">Privacy <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>
                    </div>
                    <div class="col-lg-9">
                        <div class="modal-vertical-divider"></div>
                        <div class="tabs">
                            <h4 class="tab-item active" data-tabidx="1">Cheatsheet</h4>
                            <!-- <h4 class="tab-item" data-tabidx="2">FAQ</h4> -->
                            <div class="tab-slider-rail">
                                <div class="tab-slider"></div>
                            </div>
                        </div>
                        <table class="table table-condensed table-cheatsheet">
                            <thead class="markdown-example-table-head">
                                <tr>
                                    <th>Syntax</th>
                                    <th>Example</th>
                                    <th class="hidden-xs">Reference</th>
                                </tr>
                            </thead>
                            <tbody class="markdown-body markdown-example-table-body" style="font-family: inherit; font-size: 14px; padding: 0; max-width: inherit;">
                                <tr>
                                    <td class="example-syntax"># Header</td>
                                    <td class="example-present">Header</td>
                                    <td rowspan="14" class="show-on-zh hidden-xs" style="display: none;"><a href="https://hackmd.io/c/tutorials-tw/%2Fs%2Fbasic-markdown-formatting-tw">基本排版</a></td>
                                    <td class="show-on-not-zh hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">- Unordered List</td>
                                    <td class="example-present"><ul style="margin: 0;"><li>Unordered List</li></ul></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">1. Ordered List</td>
                                    <td class="example-present"><ol style="margin: 0;"><li>Ordered List</li></ol></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">- [ ] Todo List</td>
                                    <td class="example-present"><ul style="margin: 0;"><li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""><label></label>Todo List</li></ul></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">&gt; Blockquote</td>
                                    <td class="example-present"><blockquote style="margin: 0;"> Blockquote</blockquote></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">**Bold font**</td>
                                    <td class="example-present"><strong>Bold font</strong></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">*Italics font*</td>
                                    <td class="example-present"><i>Italics font</i></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">~~Strikethrough~~</td>
                                    <td class="example-present"><s>Strikethrough</s></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">19^th^</td>
                                    <td class="example-present">19<sup>th</sup></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">H~2~O</td>
                                    <td class="example-present">H<sub>2</sub>O</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">++Inserted text++</td>
                                    <td class="example-present"><ins>Inserted text</ins></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">==Marked text==</td>
                                    <td class="example-present"><mark>Marked text</mark></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">[link text](https:// "title")</td>
                                    <td class="example-present"><a>Link</a></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">![image alt](https:// "title")</td>
                                    <td class="example-present">Image</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">`Code`</td>
                                    <td class="example-present"><code>Code</code></td>
                                    <td rowspan="2" class="show-on-zh hidden-xs" style="display: none;"><a href="https://hackmd.io/c/tutorials-tw/%2Fs%2Fhow-to-use-code-blocks-tw">在筆記中貼入程式碼</a></td>
                                    <td class="show-on-not-zh hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">```javascript<br>var i = 0;<br>```</td>
                                    <td class="example-present"><pre style="border:none !important; margin: 0;"><code class="javascript hljs"><div class="wrapper"><div class="gutter linenumber"><span data-linenumber="1"></span></div><div class="code"><span class="hljs-keyword">var</span> i = <span class="hljs-number">0</span>;</div></div></code></pre></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">:smile:</td>
                                    <td class="example-present"><img align="absmiddle" alt=":smile:" class="emoji" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/smile.png" title=":smile:"></td>
                                    <td class="hidden-xs"><a href="https://github.com/ikatyang/emoji-cheat-sheet">Emoji list</a></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">{%youtube youtube_id %}</td>
                                    <td class="example-present">Externals</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">$L^aT_eX$</td>
                                    <td class="example-present">L<sup>a</sup>T<sub>e</sub>X</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">:::info<br>This is a alert area.<br>:::</td>
                                    <td class="example-present"><div class="alert alert-info" style="margin: 0;"><p>This is a alert area.</p></div></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- revision modal -->
<div class="modal fade" id="namedRevisionModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1200px; height: calc(100vh - 100px);">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <button type="button" class="close back" aria-label="Back"><span aria-hidden="true"><i class="fa fa-arrow-left" aria-hidden="true"></i></span>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel"><i class="fa fa-history"></i> Versions and GitHub Sync</h4>
            </div>
            <div class="container-fluid modal-body hmd-pa-0 github-sync-enabled" style="max-height: calc(100vh - 100px); height: calc(100vh - 100px); overflow: hidden;">
                
                <div class="hidden-xs ui-github-sync" style="height: 51px; border-bottom: solid 1px #e7e7e7;">
                    <div style="display: none;" class="signin-to-connect">
                        Sign in to link this note to GitHub
                        <button class="btn btn-success" style="margin-left: 30px" data-toggle="modal" data-target=".signin-modal">Sign in to HackMD</button>
                        <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank" style="margin-left: 30px;"><span>Learn more</span><i class="fa fa-angle-right fa-fw"></i></a>
                    </div>
                    <div style="display: none;" class="no-connect-github">
                        This note is not linked with GitHub
                        <button class="btn btn-primary btn-outline ui-github-pull" style="margin-left: 30px">Pull from GitHub</button>
                        <button class="btn btn-primary btn-outline ui-github-push" style="margin-left: 10px">Push to GitHub</button>
                        <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank" style="margin-left: 30px;"><span>Learn more</span><i class="fa fa-angle-right fa-fw"></i></a>
                    </div>
                    <div style="" class="github-status">
                        <i class="fa fa-github"></i>&nbsp;<div class="github-path-container"><a target="_blank" class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="30px,5" data-container=".github-status" data-original-title="This note is linked with QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md" href="https://github.com/QuocCuong17/SafeGate_2024_Write_Up/blob/main/PortSwigger/Business%20logic%20vulnerabilities/Lab%20#1:%20Excessive%20trust%20in%20client-side%20controls.md">QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md</a></div>

                        <a class="ui-github-badge github-control site-ui-font" style="margin-left: 30px;" data-toggle="popover" data-original-title="" title="">
                            <i class="fa fa-link fa-18"></i>
                            Add badge
                        </a>
                        <a class="ui-github-pull github-control" style="margin-left: 30px;">
                            <i class="fa fa-arrow-down fa-18"></i>
                            Pull
                        </a>
                        <a class="ui-github-push github-control" style="margin-left: 30px;">
                            <i class="fa fa-arrow-up fa-18"></i>
                            Push
                        </a>
                        <a class="ui-show-github-synced-settings-modal github-control" style="margin-left: 30px;">
                            <i class="fa fa-cog fa-18"></i>
                            GitHub Link Settings
                        </a>
                    </div>
                </div>
                
                <div class="col-xs-12 col-sm-4 hmd-pl-0 hmd-pr-0 sidebar revision-list-container">
                    <div class="list-group ui-named-revision-list mb-0 has-named-revision"><div class="revision-card current active" data-revision-time="current">
      <div class="hmd-flex revision-card-heading">
        
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex items-center text-inherit hocus:text-inherit hocus:no-underline current-anchor">
            Current note content
          </a>
        </div>
      </div>

      <div class="child-revision-list"></div>
    </div><div href="#" class="revision-card" data-revision-time="1723653654275">
      <div class="hmd-flex revision-card-heading">
      
          <div class="ui-revision-list-toggle">
            <i class="fa fa-caret-right" aria-hidden="true"></i>
          </div>
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex flex-col items-start text-inherit hocus:text-inherit hocus:no-underline named-anchor">
            <span title="Untitled-1">
              Untitled-1
            </span>
            <small>T4, 14 Th08 2024 23:40</small>
          </a>
        <div><ul class="m-0 flex flex-col overflow-hidden p-0 max-h-[160px]"><li class="list-none"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="flex items-center px-2 py-[6px] text-inherit hocus:text-inherit hocus:no-underline"><span class="mx-[6px] inline-block h-2 w-2 shrink-0 rounded-full" style="background-color: rgb(193, 19, 13);"></span><div class="relative rounded-full" style="background-image: url(&quot;https://avatars.githubusercontent.com/u/72690085?s=96&quot;); background-size: cover; width: 20px; height: 20px; min-width: 20px; min-height: 20px;"></div><span class="ml-[6px] shrink overflow-hidden text-ellipsis font-normal">Cường17</span></a></li></ul></div></div>
      </div>

      <div class="child-revision-list"><div class="revision-item" data-revision-time="1723653070211">
    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex items-center h-[28px] mb-[2px] text-inherit w-full hocus:text-inherit hocus:no-underline">
      T4, 14 Th08 2024 23:31
    </a><div><ul class="m-0 flex flex-col overflow-hidden p-0 max-h-[160px]"><li class="list-none"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="flex items-center px-2 py-[6px] text-inherit hocus:text-inherit hocus:no-underline"><span class="mx-[6px] inline-block h-2 w-2 shrink-0 rounded-full" style="background-color: rgb(193, 19, 13);"></span><div class="relative rounded-full" style="background-image: url(&quot;https://avatars.githubusercontent.com/u/72690085?s=96&quot;); background-size: cover; width: 20px; height: 20px; min-width: 20px; min-height: 20px;"></div><span class="ml-[6px] shrink overflow-hidden text-ellipsis font-normal">Cường17</span></a></li></ul></div></div><div class="revision-item" data-revision-time="1723651863153">
    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex items-center h-[28px] mb-[2px] text-inherit w-full hocus:text-inherit hocus:no-underline">
      T4, 14 Th08 2024 23:11
    </a><div><ul class="m-0 flex flex-col overflow-hidden p-0 max-h-[160px]"><li class="list-none"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="flex items-center px-2 py-[6px] text-inherit hocus:text-inherit hocus:no-underline"><span class="mx-[6px] inline-block h-2 w-2 shrink-0 rounded-full" style="background-color: rgb(193, 19, 13);"></span><div class="relative rounded-full" style="background-image: url(&quot;https://avatars.githubusercontent.com/u/72690085?s=96&quot;); background-size: cover; width: 20px; height: 20px; min-width: 20px; min-height: 20px;"></div><span class="ml-[6px] shrink overflow-hidden text-ellipsis font-normal">Cường17</span></a></li></ul></div></div><div class="revision-item" data-revision-time="1723651271771">
    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex items-center h-[28px] mb-[2px] text-inherit w-full hocus:text-inherit hocus:no-underline">
      T4, 14 Th08 2024 23:01
    </a><div><ul class="m-0 flex flex-col overflow-hidden p-0 max-h-[160px]"><li class="list-none"><a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="flex items-center px-2 py-[6px] text-inherit hocus:text-inherit hocus:no-underline"><span class="mx-[6px] inline-block h-2 w-2 shrink-0 rounded-full" style="background-color: rgb(193, 19, 13);"></span><div class="relative rounded-full" style="background-image: url(&quot;https://avatars.githubusercontent.com/u/72690085?s=96&quot;); background-size: cover; width: 20px; height: 20px; min-width: 20px; min-height: 20px;"></div><span class="ml-[6px] shrink overflow-hidden text-ellipsis font-normal">Cường17</span></a></li></ul></div></div></div>
    </div><div href="#" class="revision-card" data-revision-time="1723644479634">
      <div class="hmd-flex revision-card-heading">
      
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="inline-flex flex-col items-start text-inherit hocus:text-inherit hocus:no-underline named-anchor">
            <span title="last changed at Aug 14, 2024 10:30 PM, pushed by Cường17">
              last changed at Aug 14, 2024 10:30 PM, pushed by Cường17
            </span>
            <small>T4, 14 Th08 2024 21:07</small>
          </a>
        <div><ul class="m-0 flex flex-col overflow-hidden p-0 max-h-[160px]"></ul></div></div>
      </div>

      <div class="child-revision-list"></div>
    </div></div>
                    <div class="list-group ui-upgrade-tips" style="display: none;">
                        <div class="upgrade-tips"></div>
                        <a class="ui-upgrade-button" target="_blank" href="https://hackmd.io/?nav=billing">Upgrade now<i class="fa fa-angle-right" style="margin-left: 5px"></i></a>
                    </div>
                    <div class="list-group ui-version-preview-list" style="display: none;"></div>
                </div>
                <div id="revision-editor-container" class="col-xs-12 col-sm-8 hmd-pl-0 hmd-pr-0 hmd-flex hmd-flex-column">
                    <div id="revisionSummary" style="" class="hmd-flex">
                        <h4 style="margin-right: 5px;">
                            <i class="fa fa-history"></i>
                        </h4>

                        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
                            <h4 class="summary-title">Current note content</h4>
                            <p class="summary-author-info hmd-flex hmd-flex-wrap-xs" style="display: none;">
                                <span class="summary-timestamp" style="margin-right: 15px;"></span>
                                <span>Version named by &nbsp;</span>
                                <span class="summary-authorship">
                                    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#"></a> &nbsp;
                                </span>
                                <span></span>
                            </p>
                            <div class="hmd-flex hmd-items-end hmd-justify-between">
                                <p class="summary-description" style="margin-bottom: 22px; display: none;"></p>
                                <div class="summary-collapse-toggle" style="display: none;">
                                    <span class="expand">
                                        More
                                        <i class="fa fa-angle-down" aria-hidden="true"></i>
                                    </span>
                                    <span class="collapse">
                                        Less
                                        <i class="fa fa-angle-up" aria-hidden="true"></i>
                                    </span>
                                </div>
                            </div>
                        </div>

                        <div class="dropdown-container hmd-dni-xs" id="revisionSummaryDropdown" style="display: none;">
                            <ul class="dropdown-menu" role="menu" aria-labelledby="menu">
                                <li role="presentation">
                                    <a role="menuitem" class="ui-rename-revision" id="rename-named-revision-button" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#">
                                        <i class="fa fa-pencil fa-fw"></i> Edit
                                    </a>
                                </li>

                                <li role="presentation">
                                    <a role="menuitem" class="ui-delete-revision" tabindex="-1" href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" id="remove-named-revision-button">
                                    <i class="fa fa-trash fa-fw"></i> Delete</a>
                                </li>
                            </ul>
                            <a class="ui-revision-action-menu" data-toggle="dropdown" style="color: #777;" aria-expanded="false"><i class="fa fa-ellipsis-h fa-fw" style="vertical-align: middle; width:100%;"></i>
                            </a>
                        </div>

                        <div class="create-revision-button-container hmd-flex hmd-items-center hmd-dni-xs">
                            <i class="fa fa-question-circle fa-fw tooltip-align-left" style="color: #CDCDCD; margin-right: 10px;" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="Save current content into a named version."></i>
                            <button class="btn btn-outline btn-primary ui-create-revision-button disabled" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="Note content is identical to the latest version.">Save as version</button>
                        </div>
                    </div>

                    <form data-toggle="validator" id="namedRevisionForm" style="display: none;" class="hmd-flex hmd-flex-column hmd-dni-xs" role="form" novalidate="true">
                        <h4 style="display: none;" class="revision-timestamp">
                            <i style="margin-right: 1px;" class="fa fa-history"></i>
                            <span></span>
                        </h4>
                        <div class="hmd-flex" style="margin-top: 10px;">
                            <div class="hmd-flex hmd-flex-column hmd-flex-auto">
                                <div class="hmd-flex hmd-items-center form-group">
                                    <label class="control-label" for="name">
                                        Name
                                    </label>
                                    <input class="form-control" name="name" type="text" placeholder="Please name the version" required="" maxlength="80">
                                </div>

                                <div class="hmd-flex hmd-items-start form-group">
                                    <label class="control-label" for="description">
                                        Description
                                    </label>
                                    <textarea rows="3" class="form-control" name="description" placeholder="Please describe the version (optional)" maxlength="500" style="max-height: 74px; resize: none;"></textarea>
                                    <div class="help-block with-errors"></div>
                                </div>
                            </div>
                            <div class="hmd-flex hmd-items-end form-group" style="margin-left: 40px;">
                                <strong class="ui-state-message" style="position: absolute; top: 20px; color:green; padding-right: 15px;">
                                    Note content is identical to the latest version.
                                </strong>
                                <button type="button" id="cancel-named-revision-button" class="btn btn-default" style="margin-right: 10px;">Cancel</button>
                                <button type="submit" id="submit-named-revision-button" class="btn btn-primary disabled" disabled="disabled">
                                    Name this version
                                </button>
                            </div>
                        </div>
                    </form>

                    <div style="height: calc(100vh - 140px); overflow: hidden;">
                        <textarea id="namedrevisionViewer" style="display:none;"></textarea><div class="CodeMirror cm-s-default CodeMirror-wrap CodeMirror-overlayscroll" translate="no"><div style="overflow: hidden; position: relative; width: 3px; height: 0px; top: 8px; left: 41px;"><textarea autocorrect="off" autocapitalize="off" spellcheck="false" style="position: absolute; bottom: -1em; padding: 0px; width: 1000px; height: 1em; min-height: 1em; outline: none;" readonly="" tabindex="0"></textarea></div><div class="CodeMirror-overlayscroll-horizontal" cm-not-content="true" style="display: none;"><div></div></div><div class="CodeMirror-overlayscroll-vertical" cm-not-content="true" style="display: block; bottom: 0px;"><div style="height: 233.992px; top: 0px;"></div></div><div class="CodeMirror-scrollbar-filler" cm-not-content="true"></div><div class="CodeMirror-gutter-filler" cm-not-content="true"></div><div class="CodeMirror-scroll" tabindex="-1" style="height: 482px;"><div class="CodeMirror-sizer" style="margin-left: 37px; margin-bottom: 0px; border-right-width: 50px; min-height: 914px; padding-right: 10px; padding-bottom: 0px;"><div style="position: relative; top: 0px;"><div class="CodeMirror-lines" role="presentation"><div role="presentation" style="position: relative; outline: none;"><div class="CodeMirror-measure"><pre class="CodeMirror-line-like"><span>xxxxxxxxxx</span></pre><div class="CodeMirror-linenumber CodeMirror-gutter-elt"><div>1</div></div><div class="CodeMirror-linenumber CodeMirror-gutter-elt"><div>32</div></div></div><div class="CodeMirror-measure"></div><div class="CodeMirror-other-cursors"></div><div style="position: relative; z-index: 1;"></div><div class="CodeMirror-cursors"><div class="CodeMirror-cursor" style="left: 4px; top: 0px; height: 24px;">&nbsp;</div></div><div class="CodeMirror-code" role="presentation" style=""><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">1</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-header cm-header-1"># </span><span class="cm-m-markdown cm-strong cm-header cm-header-1">**💡Lab: Excessive trust in client-side controls**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">2</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-hr">---</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">3</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-header cm-header-3">### </span><span class="cm-m-markdown cm-strong cm-header cm-header-3">**Mô tả**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">4</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bài lab này có một </span><span class="cm-m-markdown cm-strong">**lỗ hổng logic**</span><span class="cm-m-markdown"> do </span><span class="cm-m-markdown cm-strong">**giá trị của sản phẩm**</span><span class="cm-m-markdown"> được kiểm soát và xác thực </span><span class="cm-m-markdown cm-strong">**trên phía client**</span><span class="cm-m-markdown"> thay vì phía server. Điều này cho phép kẻ tấn công thay đổi giá trị của sản phẩm khi gửi yêu cầu mua hàng đến server, dẫn đến việc </span><span class="cm-m-markdown cm-strong">**mua hàng với giá </span><span class="cm-m-markdown cm-formatting cm-formatting-math cm-strong cm-math">$</span><span class="cm-m-markdown cm-strong cm-math">0**.</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">5</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">6</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-math cm-header cm-header-3">### **Mục tiêu**</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">7</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-math">Mục tiêu của bài lab này là khai thác **lỗ hổng logic** do sự tin tưởng quá mức vào kiểm soát phía client để lấy được hàng hóa với giá </span><span class="cm-m-markdown cm-formatting cm-formatting-math cm-math">$</span><span class="cm-m-markdown">0. </span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">8</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">9</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-hr">---</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">10</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Đăng nhập với wiener/peter</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">11</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/Hy78oI99C.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">12</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-tag cm-bracket">&lt;</span><span class="cm-m-xml cm-tag">br</span><span class="cm-m-xml cm-tag cm-bracket">&gt;</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">13</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Test thử chức năng thêm vào giỏ hàng</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">14</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/BkQii859R.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">15</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">16</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bắt request gửi sang Repeater để phân tích</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">17</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">18</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Sửa giá về 0, 1 respone 302 được trả về nhưng trong giỏ hàng vẫn trống -&gt; khả năng không nhận giá 0</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">19</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/r12L2L9qC.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">20</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">21</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Sửa thành giá tiền âm cũng không được</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">22</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/Sy2tnI95C.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">23</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">24</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Chỉ chấp nhận giá tiền &gt;0, sửa giá thành 1 thì được</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">25</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/SkxA2Ic5A.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">26</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">27</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Bây giờ giá đã nhỏ hơn số dư, có thể mua hàng</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">28</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">29</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">30</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown">Nhấn </span><span class="cm-m-markdown cm-strong">**Place Order**</span><span class="cm-m-markdown"> đơn hàng được đặt thành công, Bài lab được </span><span class="cm-m-markdown cm-strong cm-em">***hoàn thành***</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">31</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span class="cm-m-markdown cm-image cm-image-marker">!</span><span class="cm-m-markdown cm-image cm-image-alt-text cm-link">[image]</span><span class="cm-m-markdown cm-string cm-url">(https://hackmd.io/_uploads/H1IPTUqqC.png)</span></span></pre></div><div style="position: relative;"><div class="CodeMirror-gutter-wrapper" aria-hidden="true" style="left: -37px;"><div class="CodeMirror-linenumber CodeMirror-gutter-elt" style="left: 0px; width: 28px;">32</div></div><pre class=" CodeMirror-line " role="presentation"><span role="presentation" style="padding-right: 0.1px;"><span cm-text="">​</span></span></pre></div></div></div></div></div></div><div style="position: absolute; height: 50px; width: 1px; border-bottom: 0px solid transparent; top: 914px;"></div><div class="CodeMirror-gutters" style="height: 964px; left: 0px;"><div class="CodeMirror-gutter CodeMirror-linenumbers" style="width: 36px;"></div></div></div><div style="position: absolute; right: 0px; top: 0px; z-index: 7; pointer-events: none;"></div><div style="position: absolute; right: 0px; top: 0px; z-index: 7; pointer-events: none;"></div></div>
                    </div>

                    <div class="hmd-flex hmd-justify-between hmd-items-center hmd-dni-xs" id="revision-operation-panel">
                        <!-- #region Compare revision dropdown menu -->
                        <div class="diff-revision-menu hmd-flex hmd-items-center">
                            <span>
                                <input type="checkbox" name="compareWithLastVersion" checked="">
                            </span>
                            <span>
                                Compare with
                            </span>
                            <div class="btn-group dropup" id="diff-revision-dropdown-menu">
                                <button class="btn btn-default dropdown-toggle ui-diff-revision-menu hmd-flex hmd-items-center hmd-justify-between" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                                    <span>Previous version</span>
                                    <i class="fa fa-angle-down fa-12" aria-hidden="true" style="margin-left: 5px;"></i>
                                </button>
                                <ul class="dropdown-menu pull-left" aria-labelledby="diff-revision-dropdown-menu">
                                    <div class="dropdown-section">
                                        <div class="section-header">
                                            Choose a version
                                        </div>

                                        <div class="section-filter">
                                            <span>
                                                <input id="showOnlyNamedRevision" type="checkbox" name="showOnlyNamedRevision">
                                                <label for="showOnlyNamedRevision">
                                                    Only named versions
                                                </label>
                                            </span>
                                        </div>
                                    </div>
                                    <div class="revision-list-container d-flex hmd-justify-center">
                                        <div class="revision-list-inner"><div href="#" class="revision-card  " data-revision-time="current" disabled="">
      <div class="hmd-flex revision-card-heading">
        
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          Current note content
        </div>
      </div>

      <div class="child-revision-list"></div>
    </div><div href="#" class="revision-card  active" data-revision-time="1723653654275">
      <div class="hmd-flex revision-card-heading">
      
          <div class="ui-revision-list-toggle">
            <i class="fa fa-caret-right" aria-hidden="true"></i>
          </div>
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          <span title="Untitled-1 (Previous version)">Untitled-1 (Previous version)</span>
          <small>T4, 14 Th08 2024 23:40</small>
        </div>
      </div>

      <div class="child-revision-list"><div href="#" class="revision-item " data-revision-time="1723653070211" title="T4, 14 Th08 2024 23:31">
      T4, 14 Th08 2024 23:31
    </div><div href="#" class="revision-item " data-revision-time="1723651863153" title="T4, 14 Th08 2024 23:11">
      T4, 14 Th08 2024 23:11
    </div><div href="#" class="revision-item " data-revision-time="1723651271771" title="T4, 14 Th08 2024 23:01">
      T4, 14 Th08 2024 23:01
    </div></div>
    </div><div href="#" class="revision-card  " data-revision-time="1723644479634">
      <div class="hmd-flex revision-card-heading">
      
        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
          <span title="last changed at Aug 14, 2024 10:30 PM, pushed by Cường17">last changed at Aug 14, 2024 10:30 PM, pushed by Cường17</span>
          <small>T4, 14 Th08 2024 21:07</small>
        </div>
      </div>

      <div class="child-revision-list"></div>
    </div></div>
                                        <div class="empty-revision-list" style="display: none;">
                                            <div class="search-icon">
                                                <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/empty-search-result.svg" alt="No search result">
                                            </div>
                                            Version not found
                                        </div>
                                    </div>
                                </ul>
                            </div>
                            <span>
                                
                            </span>
                        </div>
                        <!-- #endregion -->

                        <div>
                            <button type="button" class="btn btn-danger btn-outline ui-revisionModalRevert" style="margin-right: 10px; display: none;">Revert</button>
                            <button type="button" class="btn btn-primary btn-outline ui-revisionModalDownload">Download</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- message modal -->
<div class="modal fade message-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
  <div class="modal-dialog modal-sm">
      <div class="modal-content">
          <div class="modal-header">
              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
              </button>
              <h4 class="modal-title" id="myModalLabel"></h4>
          </div>
          <div class="modal-body" style="color:black;">
              <img>
              <h5 style="font-weight: 600; font-size: 18px;"></h5>
              <p></p>
              <a target="_blank" style="word-break: break-all;" rel="noopener"></a>
          </div>
          <div class="modal-footer">
              <button type="button" class="btn btn-default" data-dismiss="modal">OK</button>
          </div>
      </div>
  </div>
</div>

<!-- feedback modal -->
<div class="modal fade feedback-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
  <div class="modal-dialog modal-lg" role="document">
    <div class="modal-content">
      <div class="modal-header" style="padding: 8px 15px; font-weight: 700">
        <button type="button" class="close" aria-label="Close" style="font-size: 26px; margin-top: -1px;" data-dismiss="modal">
          <span aria-hidden="true">×</span>
        </button>
        <h4 class="modal-title">Feedback</h4>
      </div>
      <div class="modal-body" style="text-align: left;">
        <div class="alert alert-danger" style="display: none;">
          <i class="fa fa-exclamation-triangle" aria-hidden="true" style="margin-right: 5px"></i>
          Submission failed, please try again
        </div>
        <h3 style="margin-top:5px">Thanks for your support.</h3>
        <p>On a scale of 0-10, how likely is it that you would recommend HackMD to your friends, family or business associates?</p>
        <div class="rating-group" style="margin-top: 15px; margin-bottom: 30px;"><button type="button" class="btn" data-value="0">0</button><button type="button" class="btn" data-value="1">1</button><button type="button" class="btn" data-value="2">2</button><button type="button" class="btn" data-value="3">3</button><button type="button" class="btn" data-value="4">4</button><button type="button" class="btn" data-value="5">5</button><button type="button" class="btn" data-value="6">6</button><button type="button" class="btn" data-value="7">7</button><button type="button" class="btn" data-value="8">8</button><button type="button" class="btn" data-value="9">9</button><button type="button" class="btn" data-value="10">10</button></div>
        <p style="font-size:16px">Please give us some advice and help us improve HackMD.</p>
        <form role="form" data-toggle="validator" novalidate="true">
          <div class="form-group" style="margin-bottom: 10px;">
            <textarea name="feedback" class="form-control" placeholder="Enter your feedback" rows="3" style="resize: none;" required=""></textarea>
          </div>
          <div class="checkbox" style="font-size:16px">
            <label>
              <input name="engage" type="checkbox" checked="">
              I’m willing to participate in user experience research or beta testing so HackMD could build things I want.
            </label>
          </div>
          <div class="form-group hmd-flex hmd-items-center" style="font-size: 16px; padding-left: 20px;">
            <label style="font-weight: normal;">My Email:</label>
            &nbsp;
            <div class="hmd-flex-auto hmd-pr-0">
              <input type="email" name="email" class="form-control col-sm-9" aria-describedby="helpId" placeholder="Email address" required="">
            </div>
          </div>
          <div class="modal-footer" style="padding: 15px 0; border: none;">
            <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
            <button type="submit" class="btn btn-primary ui-feedback-submit disabled">Submit</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>

<!-- feedback success modal -->
<div class="modal fade feedback-success-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
  <div class="modal-dialog modal-sm" role="document">
    <div class="modal-content">
      <div class="modal-body" style="padding: 50px 20px; text-align: center;">
        <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/feedback.svg" width="85" height="95">
        <h4>Thanks for your feedback</h4>
      </div>
    </div>
  </div>
</div>

<!-- action modal -->
<div class="modal fade action-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"></h4>
            </div>
            <div class="modal-body" style="color:black;">
                <p></p>
            </div>
            <div class="hmd-flex modal-footer">
                <button type="button" class="btn btn-default cancel hmd-flex-one" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-primary yes hmd-flex-one" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>

<!-- action modal -->
<div class="modal fade remove-revision-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Remove version name</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Do you want to remove this version name and description?</h5>
            </div>
            <div class="hmd-flex modal-footer">
                <button type="button" class="btn btn-default hmd-flex-one" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger hmd-flex-one" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>

<!-- transfer modal -->
<div class="modal fade transfer-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Transfer ownership</h4>
            </div>
            <div class="modal-body" style="color:black; overflow: inherit; padding-bottom: 0;">
                Transfer to

                <div class="form-group" style="margin-bottom: 0;">
                    <div class="radio">
                        <label>
                            <input type="radio" name="transfer-type" value="team" required="" checked="checked">
                            <span>
                                Transfer to team you've joined
                            </span>
                        </label>
                    </div>

                    <div class="dropdown btn-group ui-transfer-modal-team-dropdown" style="width: 100%; margin-bottom: 10px;">
                        <button class="btn btn-default hmd-text-left dropdown-toggle" type="button" style="width: 100%; height: 40px;" id="dropdownMenuTransferToTeam" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                            <span class="ui-transfer-modal-team-label" style="line-height: 18px;">
                                No teams available
                            </span>

                            <span class="caret" style="position: absolute; top: 17px; right: 10px;"></span>
                        </button>

                        <ul class="dropdown-menu" aria-labelledby="dropdownMenuTransferToTeam" style="width: 100%;"></ul>
                    </div>
                    <div class="public-team-notice" style="font-size: 12px; color: #C9302C; display: none;">
                        Warning: <span class="team-name"></span> is a <b>public team</b>. If you transfer note to this team, <b>everyone on the web can find and read this note.</b>
                    </div>

                    <div class="radio transfer-team-radio">
                        <label>
                            <input type="radio" name="transfer-type" value="member" required="">
                            <span>
                                Transfer to current team member
                            </span>
                        </label>
                    </div>

                    <div class="dropdown btn-group ui-transfer-modal-team-member-dropdown" style="width: 100%; margin-bottom: 10px;">
                        <button class="btn btn-default hmd-text-left dropdown-toggle" type="button" style="width: 100%; height: 40px;" id="dropdownMenuTransferToTeamMember" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                            <span class="ui-transfer-modal-team-member-label" style="line-height: 18px;">
                                No team members available
                            </span>

                            <span class="caret" style="position: absolute; top: 17px; right: 10px;"></span>
                        </button>

                        <ul class="dropdown-menu" aria-labelledby="dropdownMenuTransferToTeamMember" style="width: 100%;"></ul>
                    </div>
                </div>

                <div class="error text-danger" style="display: none; margin-top: 10px; color: red;"></div>
            </div>

            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">
                    Cancel
                </button>

                <button type="button" class="btn btn-danger ui-transfer-modal-confirm" disabled="">
                    Transfer
                </button>
            </div>
        </div>
    </div>
</div>


<!-- github signin modal -->
<div class="modal fade github-signin-modal hmd-text-left" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Link with GitHub</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">Please authorize HackMD on GitHub</h4>
                <p style="margin-bottom: 15px;">
                    
                        Please sign in to GitHub and install the HackMD app on your GitHub repo.
                    
                    <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank">Learn more</a>
                </p>


                
                    <a href="https://github.com/login/oauth/authorize?client_id=Iv1.dce7f04830297ce5&amp;redirect_uri=https%3A%2F%2Fhackmd.io%2Fapi%2Fgithub%2Fsync%2Fcallback" data-href="https://github.com/apps/hackmd-hub/installations/new" type="button" class="btn btn-primary ui-github-signin-button" style="margin-bottom: 30px"><i class="fa fa-github fa-fw"></i>&nbsp;Sign in to GitHub</a>
                

                
                    <p><small style="color: #888888">HackMD links with GitHub through a GitHub App. You can choose which repo to install our App.</small></p>
                
            </div>
        </div>
    </div>
</div>

<!-- github sync modal -->
<div class="modal fade github-sync-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>

                <h4 class="modal-title" id="myModalLabel">
                    <span class="ui-push-title" style="display: none;">Push the note to GitHub</span>
                    <span class="ui-push-only-title">Push to GitHub</span>
                    <span class="ui-pull-title" style="display: none;">Pull a file from GitHub</span>
                </h4>
            </div>
            <div class="modal-body">
                <div class="alert alert-danger" style="display: none;">
                    <i class="fa fa-times ui-close-alert" aria-hidden="true" style="float: right;"></i>
                    <span class="ui-github-sync-alert-msg"></span>
                    &nbsp;
                    
                        <a href="https://github.com/login/oauth/authorize?client_id=Iv1.dce7f04830297ce5&amp;redirect_uri=https%3A%2F%2Fhackmd.io%2Fapi%2Fgithub%2Fsync%2Fcallback" target="_blank" class="ui-github-sync-authorize-again" style="display: none;">Authorize again</a>
                    
                </div>

                <div class="github-path-container hmd-flex hmd-items-center form-group">
                    <i class="fa fa-github"></i>&nbsp;
                    <span class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="This note is linked with QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md">QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md</span>
                </div>

                <div class="choose-repo-file-section">
                    <h4 class="github-section-title">Choose which file to push to</h4>
                    <div style="display: flex; margin-bottom: 0px; align-items: center;">
                        <div style="flex: 1">Select repo
                            
                                <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="Select from repos that had HackMD’s GitHub App installed"></i>
                            
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-repos" placeholder="Select a repo" tabindex="-1" class="selectized" disabled="" style="display: none;"><option value="" selected="selected"></option></select><div class="selectize-control single plugin-restore_on_focus plugin-preserve_on_blur"><div class="selectize-input items not-full disabled locked"><input type="select-one" autocomplete="off" tabindex="-1" id="github-repos-selectized" placeholder="Select a repo" style="width: 95.8px;" disabled=""></div><div class="selectize-dropdown single plugin-restore_on_focus plugin-preserve_on_blur" style="display: none;"><div class="selectize-dropdown-content"></div></div></div>
                        </div>
                    </div>

                    <div style="margin: 5px 0px 30px 0px; text-align: right;">
                        <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#" class="ui-refresh-github-sync-repos" style="margin-right: 10px;">Refresh<i class="fa fa-rotate-left fa-12" style="margin-left: 3px;"></i></a>
                        
                            <a href="https://github.com/apps/hackmd-hub/installations/new" target="_blank">Authorize more repos<i class="fa fa-angle-right fa-12" style="margin-left: 3px;"></i></a>
                        
                    </div>

                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select branch
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="You can select the target branch every time you push or pull"></i>
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-branches" tabindex="-1" class="selectized" disabled="" style="display: none;"><option value="" selected="selected"></option></select><div class="selectize-control single plugin-restore_on_focus plugin-preserve_on_blur"><div class="selectize-input items not-full disabled locked"><input type="select-one" autocomplete="off" tabindex="-1" id="github-branches-selectized" disabled="" style="width: 4px;"></div><div class="selectize-dropdown single plugin-restore_on_focus plugin-preserve_on_blur" style="display: none;"><div class="selectize-dropdown-content"></div></div></div>
                        </div>
                    </div>

                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select file</div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-files" tabindex="-1" class="selectized" disabled="" style="display: none;"><option value="" selected="selected"></option></select><div class="selectize-control single plugin-restore_on_focus plugin-preserve_on_blur"><div class="selectize-input items not-full disabled locked"><input type="select-one" autocomplete="off" tabindex="-1" id="github-files-selectized" disabled="" style="width: 4px;"></div><div class="selectize-dropdown single plugin-restore_on_focus plugin-preserve_on_blur" style="display: none;"><div class="selectize-dropdown-content"></div></div></div>
                        </div>
                    </div>
                </div>

                <div class="choose-branch-section">
                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select branch
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="You can select the target branch every time you push or pull"></i>
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-push-branches" placeholder="Select or create a branch" tabindex="-1" class="selectized" style="display: none;"><option value="main" selected="selected">main</option></select><div class="selectize-control single plugin-restore_on_focus plugin-preserve_on_blur"><div class="selectize-input items has-options full has-items"><div class="item" data-value="main">main</div><input type="select-one" autocomplete="off" tabindex="0" id="github-push-branches-selectized" style="width: 4px; opacity: 0; position: absolute; left: -10000px;"></div><div class="selectize-dropdown single plugin-restore_on_focus plugin-preserve_on_blur" style="display: none; width: 578.925px; top: 34.9875px; left: 0px; visibility: visible;"><div class="selectize-dropdown-content"><div style="padding: 5px 10px" data-selectable="" data-value="Web-Exploitation" class="">Web-Exploitation</div><div style="padding: 5px 10px" data-selectable="" data-value="main" class="selected">main</div><div style="padding: 5px 10px" data-selectable="" data-value="patch-1" class="">patch-1</div></div></div></div>
                        </div>
                    </div>
                </div>

                <div class="relative flex flex-col ui-push-mode" style="">
                    <div class="flex">
                        <div style="flex: 1;" class="pt-2.5">Choose version(s) to push
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="HackMD will concatenate the version name and description as its commit message"></i>
                        </div>
                        <div style="flex: 2 1 0%; max-width: calc(66.6667%); margin-bottom: 35px;" id="version-select-tabs">
                            <ul class="nav nav-tabs" role="tablist" style="margin-bottom: 20px;">
                                <li role="presentation" class="ui-create-new-version">
                                    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#create-new-version" aria-controls="create-new-version" role="tab" data-toggle="tab" style="height: 100%;" aria-expanded="false">
                                        <i class="fa fa-check visibility-on-active" aria-hidden="true" style="margin-right:  3px;"></i>Save a new version and push</a>
                                </li>
                                <li role="presentation" class="ui-select-from-existing-version active">
                                    <a href="https://hackmd.io/BsSOoqD5SSOWgG8aI_06Dg?view#select-from-existing-version" aria-controls="select-from-existing-version" role="tab" data-toggle="tab" style="height: 100%;" aria-expanded="true">
                                        <i class="fa fa-check visibility-on-active" aria-hidden="true" style="margin-right:  3px;"></i>Choose from existing versions</a>
                                </li>
                            </ul>
                            <!-- Tab panes -->
                            <div class="tab-content">
                                <div role="tabpanel" class="tab-pane" id="create-new-version">
                                    <form role="form" class="form create-version-form">
    <div class="form-group">
        <div class="ui-revision-timestamp">
            <i class="fa fa-clock-o fa-fw"></i>
            <span></span>
        </div>
    </div>

    <div class="form-group">
        <label for="">Name</label>
        <input type="text" class="form-control" maxlength="80">
    </div>

    <div class="form-group">
        <label for="">Description</label>
        <textarea class="form-control" style="width: 100%; height: 76px; resize: vertical;" placeholder="Please describe the version (optional)" maxlength="500"></textarea>
    </div>

    <input type="text" required="" name="canPushHiddenField" class="hidden">

    <div class="github-sync-button-container">
        <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
        <button type="submit" class="btn btn-primary ui-github-sync-button">Push</button>
    </div>
</form>

                                </div>

                                <div role="tabpanel" class="tab-pane active" id="select-from-existing-version">
                                    <div class="version-list hmd-flex hmd-flex-column"><label><input type="checkbox" value="ef1d47c0-e4a8-455f-b084-5f48d4ed270a" checked=""><span>Untitled-1</span></label><label><input type="checkbox" value="debda94a-ea90-474d-97d7-50f1ae6480a3"><span>last changed at Aug 14, 2024 10:30 PM, pushed by Cường17</span></label></div>

                                    <div class="github-sync-button-container">
                                        <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
                                        <button type="button" class="btn btn-primary ui-github-sync-button">Push</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="flex flex-row mb-[30px]">
                        <span class="flex-1">
                            Include title and tags
                        </span>
                        <span class="flex-[2] w-[66.7%] max-w-[66.7%]">
                            <input type="checkbox" class="ui-gh-push-include-meta">
                        </span>
                    </div>

                    <div class="flex items-start mb-11 github-available-quota-section" style="display: none;">
                        <div style="flex: 1">
                            Available push count
                        </div>

                        <div style="flex: 2; word-break: break-all">
                            <div class="ui-github-synced-push-count mb-2.5">18</div>
                            <div class="text-gray-600" style="font-size: 12px;">
                                <span class="github-synced-push-info">Counting from now to 2024/09/01. Please upgrade to Prime Plan for unlimited pushing.</span>
                                <br>
                                <a target="_blank" href="https://hackmd.io/?nav=billing" class="github-push-quota-upgrade-now">
                                    Upgrade
                                    <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="ui-pull-mode" style="text-align: right; display: none;">
                    <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
                    <button type="button" class="btn btn-primary ui-github-sync-button">Push</button>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- github sync pull modal -->
<div class="modal fade" id="githubSyncPullModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1200px; height: calc(100vh - 100px);">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                
                <h4 class="modal-title" id="mySmallModalLabel">Pull from GitHub</h4>
            </div>
            <div class="container-fluid modal-body hmd-pa-0 hmd-flex hmd-flex-column" style="max-height: calc(100vh - 100px); height: calc(100vh - 100px); overflow: hidden;">
                <div class="github-sync-pull-error hmd-flex hmd-flex-column hmd-items-center hmd-justify-center" style="display: none;">
                    <h3></h3>
                </div>

                <div class="github-path-container hmd-flex hmd-items-center">
                    <i class="fa fa-github"></i>&nbsp;
                    <span class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="This note is linked with QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md">QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md</span>
                </div>

                <div class="github-pull-form">
                    <form class="form" id="github-sync-pull-form">
                        <div class="form-group hmd-flex hmd-justify-between hmd-items-center">
                            <label class="hmd-flex-shrink-0 hmd-mr-1">Pull from branch</label>

                            <select id="github-pull-branches" placeholder="Select a branch"></select>

                            <div class="pull-actions hmd-flex-shrink-0 hmd-ml-1">
                                <button type="button" data-dismiss="modal" class="btn btn-default" style="margin-right: 10px;">Cancel</button>

                                <button type="submit" class="btn btn-primary">
                                    Apply all changes
                                </button>
                            </div>
                        </div>

                        <div class="pull-view-indicator hmd-flex">
                            <div class="hmd-flex-one github">
                                <small>File from GitHub</small>
                            </div>
                            <div class="hmd-flex-one source">
                                <small>File from HackMD</small>
                            </div>
                        </div>
                    </form>

                </div>
                <div class="pull-editor-container hmd-flex hmd-flex-column">
                    <div id="github-sync-pull-editor" class="hmd-flex-one"></div>
                    <div class="ui-spinner unselectable hidden-print" style="display: none;"><div class="spinner" role="progressbar" style="position: absolute; width: 0px; z-index: 2000000000; left: 50%; top: 50%;"><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-0-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(0deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-1-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(32deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-2-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(65deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-3-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(98deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-4-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(130deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-5-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(163deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-6-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(196deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-7-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(229deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-8-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(261deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-9-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(294deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-10-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(327deg) translate(30px, 0px); border-radius: 0px;"></div></div></div></div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- github synced settings modal -->
<div class="modal fade github-synced-settings-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">GitHub Link Settings</h4>
            </div>

            <div class="modal-body" style="color:black;">
                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">File linked</h4>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">Linked by</div>
                    <div style="flex: 2; text-overflow: ellipsis; overflow: hidden; white-space: nowrap;" class="ui-github-synced-user">
                        <a target="_blank" class="ui-github-synced-user-photo user-card-popover" data-toggle="popover" data-original-title="" title="" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A"><img class="ui-avatar" width="30" height="30" style="border-radius: 100%; margin-right: 10px;" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/72690085"></a>
                        <a target="_blank" class="ui-github-synced-user-name user-card-popover" data-toggle="popover" data-original-title="" title="" href="https://hackmd.io/@67p6tOfWT7-iuRH5Yhbw_A">Cường17</a>
                    </div>
                </div>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">File path</div>
                    <div style="flex: 2; word-break: break-all" class="ui-github-synced-filepath">QuocCuong17/SafeGate_2024_Write_Up/PortSwigger/Business logic vulnerabilities/Lab #1: Excessive trust in client-side controls.md</div>
                </div>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">Last synced branch
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="You can select the target branch every time you push or pull"></i>
                    </div>
                    <div style="flex: 2; word-break: break-all" class="ui-github-synced-recent-branch">main</div>
                </div>

                <div class="flex mb-7.5 items-start github-available-quota-section" style="display: none;">
                    <div style="flex: 1">
                        Available push count
                    </div>

                    <div style="flex: 2; word-break: break-all">
                        <div class="ui-github-synced-push-count mb-2.5"></div>
                        <div class="text-gray-600" style="font-size: 12px;">
                            <span class="github-synced-push-info"></span>
                            <br>
                            <a target="_blank" href="https://hackmd.io/?nav=billing" class="github-setting-quota-upgrade-now">
                                Upgrade
                                <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                            </a>
                        </div>
                    </div>
                </div>


                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">Danger Zone</h4>

                <div style="display: flex; margin-bottom: 5px;">
                    <div style="flex: 1; margin-top: 7px;">Unlink</div>
                    <div style="flex: 2">
                        <button type="button" class="btn btn-danger btn-outline ui-github-cancel-sync-button" data-mapping-id="74775780-0ca6-4d8e-a4bd-5e750bb79f44">Unlink</button>
                        <div style="margin-top: 15px; font-size: 12px; color: #888;">You will no longer receive notification when GitHub file changes after unlink.</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- loading modal -->
<div class="modal fade loading-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" data-backdrop="static" data-keyboard="false" theme="light">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-body">
                <div>
                    <div class="ui-loading" style="height: 139px; width: 139px; position: relative; margin: 0 auto; top: 10px;"><div class="spinner" role="progressbar" style="position: absolute; width: 0px; z-index: 2000000000; left: 50%; top: 50%;"><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-0-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(0deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-1-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(32deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-2-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(65deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-3-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(98deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-4-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(130deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-5-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(163deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-6-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(196deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-7-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(229deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-8-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(261deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-9-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(294deg) translate(30px, 0px); border-radius: 0px;"></div></div><div style="position: absolute; top: -1px; transform: translate3d(0px, 0px, 0px); opacity: 0.25; animation: 0.909091s linear 0s infinite normal none running opacity-60-25-10-11;"><div style="position: absolute; width: 22px; height: 2px; background: rgb(0, 0, 0); box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px; transform-origin: left center; transform: rotate(327deg) translate(30px, 0px); border-radius: 0px;"></div></div></div></div>
                    <p class="ui-loading-msg" style="text-align: center; margin-bottom: 35px; position: relative; top: 15px;">Syncing</p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- push failed modal -->
<div class="modal fade push-failed-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
  <div class="modal-dialog modal-lg" style="max-width: 400px; margin: auto;">
      <div class="modal-content">
          <div class="modal-header">
              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span>
              </button>
              <h4 class="modal-title" id="myModalLabel">Push failed</h4>
          </div>
          <div class="modal-body" style="text-align: center;">
              <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/push-xx.svg" width="85px" height="96px" style="margin-top: 5px;">
              <div style="font-size: 16px; text-align: left; margin-top: 20px; word-break: break-all;"></div>
          </div>
          <div class="modal-footer" style="border: none; padding-top: 5px;">
              <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
              <button type="button" class="btn btn-primary" data-dismiss="modal">Try again</button>
          </div>
      </div>
  </div>
</div>
<!-- push success modal -->
<div class="modal fade push-success-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" theme="light">
  <div class="modal-dialog modal-lg" style="max-width: 400px; margin: auto;">
      <div class="modal-content">
          <div class="modal-body" style="text-align: center; margin: 35px 0px;">
                <img src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/push-done.svg" width="85px" height="94.7px">
                <div style="font-size: 18px; margin-top: 20px;">
                    Push successfully
                </div>
          </div>
      </div>
  </div>
</div>

<div class="publish-limiter"></div>

    
    
    <script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/js(1)"></script><script type="text/javascript" id="" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/script.manual.js.tải xuống"></script>
<script type="text/javascript" id="" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/tracks.js.tải xuống"></script>

    <script nonce="">
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        let userid = (document.cookie.match('(^|; )userid=([^;]*)')||0)[2];
        gtag('config', 'G-NGVZMM6DR6', {'user_id': userid});
        
    </script>



<script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/bundle.min.js.tải xuống" crossorigin="anonymous"></script>
<script nonce="">Sentry.init({ dsn: 'https://73410f1915d84abc8b2dd1f1aabd1c82@sentry.hackmd.dev/4', environment: 'production', integrations: function (intrus) { return intrus.filter(function (itr) { return itr.name !== 'TryCatch' }) } });</script>



<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-KLW9Z3"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->


<script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/i18n.js.tải xuống"></script>
 <script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/font-vendor.eaa8dd82d4e056021b8c.js.tải xuống" defer="defer"></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/common-vendor.04da453a2a68f624f4d4.js.tải xuống" defer="defer"></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/index-vendor.af42add7524f615aae97.js.tải xuống" defer="defer"></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/index-common.dd9bdfdbe765ef0f9064.js.tải xuống" defer="defer"></script><script src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/index.eecbe172434cf261b3aa.js.tải xuống" defer="defer"></script>






<span style="position: absolute; top: -99999px; left: -99999px; width: auto; padding: 0px; white-space: pre; letter-spacing: 0.35px; font-size: 14px; font-family: Inter, system-ui, sans-serif; font-weight: 400; text-transform: none;">Select or create a branch</span><script type="text/javascript" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/dropins.js.tải xuống" id="dropboxjs" data-app-key="rdoizrlnkuha23r" async="" defer=""></script><script type="text/javascript" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/api.js.tải xuống" async="" defer="" gapi_processed="true"></script><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><span></span><div class="ReactModalPortal"></div><div id="toasts-container" class="toasts-container"><div><div class="pointer-events-auto ml-auto mr-auto flex w-fit flex-col justify-end"></div></div><div><div class="pointer-events-auto ml-auto mr-auto flex w-fit flex-col justify-end"></div></div><div><div class="pointer-events-auto ml-auto mr-auto flex w-fit flex-col justify-end"></div></div></div><div class="ReactModalPortal"></div><script type="text/javascript" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/client" async="" defer=""></script><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><iframe id="apiproxy9efdd7155c53700b876ad8b40d20abd6e7c2dcb50.1497556029" name="apiproxy9efdd7155c53700b876ad8b40d20abd6e7c2dcb50.1497556029" src="./Lab #1_ Excessive trust in client-side controls - HackMD_files/proxy.html" tabindex="-1" aria-hidden="true" style="width: 1px; height: 1px; position: absolute; top: -100px; display: none;"></iframe><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div><div class="ReactModalPortal"></div></body><div></div><div><div></div></div><div style="position: absolute; top: 0px; z-index: 2147483647; display: block !important; overflow: unset;"><template shadowrootmode="open"><style>@import "chrome-extension://jdfkmiabjpfjacifcmihfdjhpnjpiick/css/content-script.css";
</style><div class="body"><div class="turn-lights-overlay"></div><toasts id="toasts-container"></toasts></div></template></div></html>
