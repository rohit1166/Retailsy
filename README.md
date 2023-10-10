<!DOCTYPE html>
<html lang="en-GB" style="overflow-y: auto;">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="profile" href="https://gmpg.org/xfn/11">

    <title>Retailsy</title>
    <meta name="robots" content="max-image-preview:large">
    <link rel="alternate" href="https://preview.sellerthemes.com/pro/retailsy/" hreflang="en">
    <link rel="alternate" href="https://preview.sellerthemes.com/pro/retailsy/es/home-espanol/" hreflang="es">
    <link rel="alternate" href="https://preview.sellerthemes.com/pro/retailsy/ro/home-romana/" hreflang="ro">
    <link rel="dns-prefetch" href="//fonts.googleapis.com">
    <link rel="alternate" type="application/rss+xml" title="Retailsy » Feed" href="https://preview.sellerthemes.com/pro/retailsy/feed/">
    <link rel="alternate" type="application/rss+xml" title="Retailsy » Comments Feed" href="https://preview.sellerthemes.com/pro/retailsy/comments/feed/">
    <script type="text/javascript">
        window._wpemojiSettings = {
            "baseUrl": "https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/72x72\/",
            "ext": ".png",
            "svgUrl": "https:\/\/s.w.org\/images\/core\/emoji\/14.0.0\/svg\/",
            "svgExt": ".svg",
            "source": {
                "concatemoji": "https:\/\/preview.sellerthemes.com\/pro\/retailsy\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.3.1"
            }
        };


        ! function(i, n) {
            var o, s, e;

            function c(e) {
                try {
                    var t = {
                        supportTests: e,
                        timestamp: (new Date).
                        valueOf()
                    };
                    sessionStorage.setItem(o, JSON.stringify(t))
                } catch (e) {}
            }

            function p(e, t, n) {
                e.clearRect(0, 0, e.canvas.width, e.canvas.height), e.fillText(t, 0, 0);
                var t = new Uint32Array(e.getImageData(0, 0, e.canvas.width, e.canvas.height).data),
                    r = (e.clearRect(0, 0, e.canvas.width, e.canvas.height), e.fillText(n, 0, 0), new Uint32Array(e.getImageData(0, 0, e.canvas.width, e.canvas.height).data));
                return t.every(function(e, t) {
                    return e === r[t]
                })
            }

            function u(e, t, n) {
                switch (t) {
                    case "flag":
                        return n(e, "\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f", "\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f") ? !1 : !n(e, "\ud83c\uddfa\ud83c\uddf3", "\ud83c\uddfa\u200b\ud83c\uddf3") && !n(e, "\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f", "\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");
                    case "emoji":
                        return !n(e, "\ud83e\udef1\ud83c\udffb\u200d\ud83e\udef2\ud83c\udfff", "\ud83e\udef1\ud83c\udffb\u200b\ud83e\udef2\ud83c\udfff")
                }
                return !1
            }

            function f(e, t, n) {
                var r = "undefined" != typeof WorkerGlobalScope && self instanceof WorkerGlobalScope ? new OffscreenCanvas(300, 150) : i.createElement("canvas"),
                    a = r.getContext("2d", {
                        willReadFrequently: !0
                    }),
                    o = (a.textBaseline = "top", a.font = "600 32px Arial", {});
                return e.forEach(function(e) {
                    o[e] = t(a, e, n)
                }), o
            }

            function t(e) {
                var t = i.createElement("script");
                t.src = e, t.defer = !0, i.head.appendChild(t)
            }
            "undefined" != typeof Promise && (o = "wpEmojiSettingsSupports", s = ["flag", "emoji"], n.supports = {
                everything: !0,
                everythingExceptFlag: !0
            }, e = new Promise(function(e) {
                i.addEventListener("DOMContentLoaded", e, {
                    once: !0
                })
            }), new Promise(function(t) {
                var n = function() {
                    try {
                        var e = JSON.parse(sessionStorage.getItem(o));
                        if ("object" == typeof e && "number" == typeof e.timestamp && (new Date).valueOf() < e.timestamp + 604800 && "object" == typeof e.supportTests) return e.supportTests
                    } catch (e) {}
                    return null
                }();
                if (!n) {
                    if ("undefined" != typeof Worker && "undefined" != typeof OffscreenCanvas && "undefined" != typeof URL && URL.createObjectURL && "undefined" != typeof Blob) try {
                        var e = "postMessage(" + f.toString() + "(" + [JSON.stringify(s), u.toString(), p.toString()].join(",") + "));",
                            r = new Blob([e], {
                                type: "text/javascript"
                            }),
                            a = new Worker(URL.createObjectURL(r), {
                                name: "wpTestEmojiSupports"
                            });
                        return void(a.onmessage = function(e) {
                            c(n = e.data), a.terminate(), t(n)
                        })
                    } catch (e) {}
                    c(n = f(s, u, p))
                }
                t(n)
            }).then(function(e) {
                for (var t in e) n.supports[t] = e[t], n.supports.everything = n.supports.everything && n.supports[t], "flag" !== t && (n.supports.everythingExceptFlag = n.supports.everythingExceptFlag && n.supports[t]);
                n.supports.everythingExceptFlag = n.supports.everythingExceptFlag && !n.supports.flag, n.DOMReady = !1, n.readyCallback = function() {
                    n.DOMReady = !0
                }
            }).then(function() {
                return e
            }).then(function() {
                var e;
                n.supports.everything || (n.readyCallback(), (e = n.source || {}).concatemoji ? t(e.concatemoji) : e.wpemoji && e.twemoji && (t(e.twemoji), t(e.wpemoji)))
            }))
        }((window, document), window._wpemojiSettings);
    </script>
    <style type="text/css">
        img.wp-smiley,
        img.emoji {
            display: inline !important;
            border: none !important;
            box-shadow: none !important;
            height: 1em !important;
            width: 1em !important;
            margin: 0 0.07em !important;
            vertical-align: -0.1em !important;
            background: none !important;
            padding: 0 !important;
        }
    </style>
    <link rel="stylesheet" id="wp-block-library-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-includes/css/dist/block-library/style.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="wc-blocks-vendors-style-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woocommerce/packages/woocommerce-blocks/build/wc-blocks-vendors-style.css?ver=9.8.4" type="text/css" media="all">
    <link rel="stylesheet" id="wc-blocks-style-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woocommerce/packages/woocommerce-blocks/build/wc-blocks-style.css?ver=9.8.4" type="text/css" media="all">
    <style id="classic-theme-styles-inline-css" type="text/css">
        .wp-block-button__link {
            color: #fff;
            background-color: #32373c;
            border-radius: 9999px;
            box-shadow: none;
            text-decoration: none;
            padding: calc(.667em + 2px) calc(1.333em + 2px);
            font-size: 1.125em
        }
        
        .wp-block-file__button {
            background: #32373c;
            color: #fff;
            text-decoration: none
        }
    </style>
    <style id="global-styles-inline-css" type="text/css">
        body {
            --wp--preset--color--black: #000000;
            --wp--preset--color--cyan-bluish-gray: #abb8c3;
            --wp--preset--color--white: #ffffff;
            --wp--preset--color--pale-pink: #f78da7;
            --wp--preset--color--vivid-red: #cf2e2e;
            --wp--preset--color--luminous-vivid-orange: #ff6900;
            --wp--preset--color--luminous-vivid-amber: #fcb900;
            --wp--preset--color--light-green-cyan: #7bdcb5;
            --wp--preset--color--vivid-green-cyan: #00d084;
            --wp--preset--color--pale-cyan-blue: #8ed1fc;
            --wp--preset--color--vivid-cyan-blue: #0693e3;
            --wp--preset--color--vivid-purple: #9b51e0;
            --wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg, rgba(6, 147, 227, 1) 0%, rgb(155, 81, 224) 100%);
            --wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg, rgb(122, 220, 180) 0%, rgb(0, 208, 130) 100%);
            --wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg, rgba(252, 185, 0, 1) 0%, rgba(255, 105, 0, 1) 100%);
            --wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg, rgba(255, 105, 0, 1) 0%, rgb(207, 46, 46) 100%);
            --wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg, rgb(238, 238, 238) 0%, rgb(169, 184, 195) 100%);
            --wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg, rgb(74, 234, 220) 0%, rgb(151, 120, 209) 20%, rgb(207, 42, 186) 40%, rgb(238, 44, 130) 60%, rgb(251, 105, 98) 80%, rgb(254, 248, 76) 100%);
            --wp--preset--gradient--blush-light-purple: linear-gradient(135deg, rgb(255, 206, 236) 0%, rgb(152, 150, 240) 100%);
            --wp--preset--gradient--blush-bordeaux: linear-gradient(135deg, rgb(254, 205, 165) 0%, rgb(254, 45, 45) 50%, rgb(107, 0, 62) 100%);
            --wp--preset--gradient--luminous-dusk: linear-gradient(135deg, rgb(255, 203, 112) 0%, rgb(199, 81, 192) 50%, rgb(65, 88, 208) 100%);
            --wp--preset--gradient--pale-ocean: linear-gradient(135deg, rgb(255, 245, 203) 0%, rgb(182, 227, 212) 50%, rgb(51, 167, 181) 100%);
            --wp--preset--gradient--electric-grass: linear-gradient(135deg, rgb(202, 248, 128) 0%, rgb(113, 206, 126) 100%);
            --wp--preset--gradient--midnight: linear-gradient(135deg, rgb(2, 3, 129) 0%, rgb(40, 116, 252) 100%);
            --wp--preset--font-size--small: 13px;
            --wp--preset--font-size--medium: 20px;
            --wp--preset--font-size--large: 36px;
            --wp--preset--font-size--x-large: 42px;
            --wp--preset--spacing--20: 0.44rem;
            --wp--preset--spacing--30: 0.67rem;
            --wp--preset--spacing--40: 1rem;
            --wp--preset--spacing--50: 1.5rem;
            --wp--preset--spacing--60: 2.25rem;
            --wp--preset--spacing--70: 3.38rem;
            --wp--preset--spacing--80: 5.06rem;
            --wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);
            --wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);
            --wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);
            --wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);
            --wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);
        }
        
         :where(.is-layout-flex) {
            gap: 0.5em;
        }
        
         :where(.is-layout-grid) {
            gap: 0.5em;
        }
        
        body .is-layout-flow>.alignleft {
            float: left;
            margin-inline-start: 0;
            margin-inline-end: 2em;
        }
        
        body .is-layout-flow>.alignright {
            float: right;
            margin-inline-start: 2em;
            margin-inline-end: 0;
        }
        
        body .is-layout-flow>.aligncenter {
            margin-left: auto !important;
            margin-right: auto !important;
        }
        
        body .is-layout-constrained>.alignleft {
            float: left;
            margin-inline-start: 0;
            margin-inline-end: 2em;
        }
        
        body .is-layout-constrained>.alignright {
            float: right;
            margin-inline-start: 2em;
            margin-inline-end: 0;
        }
        
        body .is-layout-constrained>.aligncenter {
            margin-left: auto !important;
            margin-right: auto !important;
        }
        
        body .is-layout-constrained> :where(:not(.alignleft):not(.alignright):not(.alignfull)) {
            max-width: var(--wp--style--global--content-size);
            margin-left: auto !important;
            margin-right: auto !important;
        }
        
        body .is-layout-constrained>.alignwide {
            max-width: var(--wp--style--global--wide-size);
        }
        
        body .is-layout-flex {
            display: flex;
        }
        
        body .is-layout-flex {
            flex-wrap: wrap;
            align-items: center;
        }
        
        body .is-layout-flex>* {
            margin: 0;
        }
        
        body .is-layout-grid {
            display: grid;
        }
        
        body .is-layout-grid>* {
            margin: 0;
        }
        
         :where(.wp-block-columns.is-layout-flex) {
            gap: 2em;
        }
        
         :where(.wp-block-columns.is-layout-grid) {
            gap: 2em;
        }
        
         :where(.wp-block-post-template.is-layout-flex) {
            gap: 1.25em;
        }
        
         :where(.wp-block-post-template.is-layout-grid) {
            gap: 1.25em;
        }
        
        .has-black-color {
            color: var(--wp--preset--color--black) !important;
        }
        
        .has-cyan-bluish-gray-color {
            color: var(--wp--preset--color--cyan-bluish-gray) !important;
        }
        
        .has-white-color {
            color: var(--wp--preset--color--white) !important;
        }
        
        .has-pale-pink-color {
            color: var(--wp--preset--color--pale-pink) !important;
        }
        
        .has-vivid-red-color {
            color: var(--wp--preset--color--vivid-red) !important;
        }
        
        .has-luminous-vivid-orange-color {
            color: var(--wp--preset--color--luminous-vivid-orange) !important;
        }
        
        .has-luminous-vivid-amber-color {
            color: var(--wp--preset--color--luminous-vivid-amber) !important;
        }
        
        .has-light-green-cyan-color {
            color: var(--wp--preset--color--light-green-cyan) !important;
        }
        
        .has-vivid-green-cyan-color {
            color: var(--wp--preset--color--vivid-green-cyan) !important;
        }
        
        .has-pale-cyan-blue-color {
            color: var(--wp--preset--color--pale-cyan-blue) !important;
        }
        
        .has-vivid-cyan-blue-color {
            color: var(--wp--preset--color--vivid-cyan-blue) !important;
        }
        
        .has-vivid-purple-color {
            color: var(--wp--preset--color--vivid-purple) !important;
        }
        
        .has-black-background-color {
            background-color: var(--wp--preset--color--black) !important;
        }
        
        .has-cyan-bluish-gray-background-color {
            background-color: var(--wp--preset--color--cyan-bluish-gray) !important;
        }
        
        .has-white-background-color {
            background-color: var(--wp--preset--color--white) !important;
        }
        
        .has-pale-pink-background-color {
            background-color: var(--wp--preset--color--pale-pink) !important;
        }
        
        .has-vivid-red-background-color {
            background-color: var(--wp--preset--color--vivid-red) !important;
        }
        
        .has-luminous-vivid-orange-background-color {
            background-color: var(--wp--preset--color--luminous-vivid-orange) !important;
        }
        
        .has-luminous-vivid-amber-background-color {
            background-color: var(--wp--preset--color--luminous-vivid-amber) !important;
        }
        
        .has-light-green-cyan-background-color {
            background-color: var(--wp--preset--color--light-green-cyan) !important;
        }
        
        .has-vivid-green-cyan-background-color {
            background-color: var(--wp--preset--color--vivid-green-cyan) !important;
        }
        
        .has-pale-cyan-blue-background-color {
            background-color: var(--wp--preset--color--pale-cyan-blue) !important;
        }
        
        .has-vivid-cyan-blue-background-color {
            background-color: var(--wp--preset--color--vivid-cyan-blue) !important;
        }
        
        .has-vivid-purple-background-color {
            background-color: var(--wp--preset--color--vivid-purple) !important;
        }
        
        .has-black-border-color {
            border-color: var(--wp--preset--color--black) !important;
        }
        
        .has-cyan-bluish-gray-border-color {
            border-color: var(--wp--preset--color--cyan-bluish-gray) !important;
        }
        
        .has-white-border-color {
            border-color: var(--wp--preset--color--white) !important;
        }
        
        .has-pale-pink-border-color {
            border-color: var(--wp--preset--color--pale-pink) !important;
        }
        
        .has-vivid-red-border-color {
            border-color: var(--wp--preset--color--vivid-red) !important;
        }
        
        .has-luminous-vivid-orange-border-color {
            border-color: var(--wp--preset--color--luminous-vivid-orange) !important;
        }
        
        .has-luminous-vivid-amber-border-color {
            border-color: var(--wp--preset--color--luminous-vivid-amber) !important;
        }
        
        .has-light-green-cyan-border-color {
            border-color: var(--wp--preset--color--light-green-cyan) !important;
        }
        
        .has-vivid-green-cyan-border-color {
            border-color: var(--wp--preset--color--vivid-green-cyan) !important;
        }
        
        .has-pale-cyan-blue-border-color {
            border-color: var(--wp--preset--color--pale-cyan-blue) !important;
        }
        
        .has-vivid-cyan-blue-border-color {
            border-color: var(--wp--preset--color--vivid-cyan-blue) !important;
        }
        
        .has-vivid-purple-border-color {
            border-color: var(--wp--preset--color--vivid-purple) !important;
        }
        
        .has-vivid-cyan-blue-to-vivid-purple-gradient-background {
            background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;
        }
        
        .has-light-green-cyan-to-vivid-green-cyan-gradient-background {
            background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;
        }
        
        .has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background {
            background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;
        }
        
        .has-luminous-vivid-orange-to-vivid-red-gradient-background {
            background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;
        }
        
        .has-very-light-gray-to-cyan-bluish-gray-gradient-background {
            background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;
        }
        
        .has-cool-to-warm-spectrum-gradient-background {
            background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;
        }
        
        .has-blush-light-purple-gradient-background {
            background: var(--wp--preset--gradient--blush-light-purple) !important;
        }
        
        .has-blush-bordeaux-gradient-background {
            background: var(--wp--preset--gradient--blush-bordeaux) !important;
        }
        
        .has-luminous-dusk-gradient-background {
            background: var(--wp--preset--gradient--luminous-dusk) !important;
        }
        
        .has-pale-ocean-gradient-background {
            background: var(--wp--preset--gradient--pale-ocean) !important;
        }
        
        .has-electric-grass-gradient-background {
            background: var(--wp--preset--gradient--electric-grass) !important;
        }
        
        .has-midnight-gradient-background {
            background: var(--wp--preset--gradient--midnight) !important;
        }
        
        .has-small-font-size {
            font-size: var(--wp--preset--font-size--small) !important;
        }
        
        .has-medium-font-size {
            font-size: var(--wp--preset--font-size--medium) !important;
        }
        
        .has-large-font-size {
            font-size: var(--wp--preset--font-size--large) !important;
        }
        
        .has-x-large-font-size {
            font-size: var(--wp--preset--font-size--x-large) !important;
        }
        
        .wp-block-navigation a:where(:not(.wp-element-button)) {
            color: inherit;
        }
        
         :where(.wp-block-post-template.is-layout-flex) {
            gap: 1.25em;
        }
        
         :where(.wp-block-post-template.is-layout-grid) {
            gap: 1.25em;
        }
        
         :where(.wp-block-columns.is-layout-flex) {
            gap: 2em;
        }
        
         :where(.wp-block-columns.is-layout-grid) {
            gap: 2em;
        }
        
        .wp-block-pullquote {
            font-size: 1.5em;
            line-height: 1.6;
        }
    </style>
    <link rel="stylesheet" id="contact-form-7-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/contact-form-7/includes/css/styles.css?ver=5.7.5.1" type="text/css" media="all">
    <link rel="stylesheet" id="woo-multi-currency-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woo-multi-currency/css/woo-multi-currency.min.css?ver=2.1.29" type="text/css" media="all">
    <style id="woo-multi-currency-inline-css" type="text/css">
        .woo-multi-currency .wmc-list-currencies .wmc-currency.wmc-active,
        .woo-multi-currency .wmc-list-currencies .wmc-currency:hover {
            background: #f78080 !important;
        }
        
        .woo-multi-currency .wmc-list-currencies .wmc-currency,
        .woo-multi-currency .wmc-title,
        .woo-multi-currency.wmc-price-switcher a {
            background: #212121 !important;
        }
        
        .woo-multi-currency .wmc-title,
        .woo-multi-currency .wmc-list-currencies .wmc-currency span,
        .woo-multi-currency .wmc-list-currencies .wmc-currency a,
        .woo-multi-currency.wmc-price-switcher a {
            color: #ffffff !important;
        }
        
        .woo-multi-currency.wmc-shortcode .wmc-currency {
            background-color: #ffffff;
            color: #212121
        }
        
        .woo-multi-currency.wmc-shortcode .wmc-currency.wmc-active,
        .woo-multi-currency.wmc-shortcode .wmc-current-currency {
            background-color: #ffffff;
            color: #212121
        }
        
        .woo-multi-currency.wmc-shortcode.vertical-currency-symbols-circle:not(.wmc-currency-trigger-click) .wmc-currency-wrapper:hover .wmc-sub-currency,
        .woo-multi-currency.wmc-shortcode.vertical-currency-symbols-circle.wmc-currency-trigger-click .wmc-sub-currency {
            animation: height_slide 100ms;
        }
        
        @keyframes height_slide {
            0% {
                height: 0;
            }
            100% {
                height: 20 %;
            }
        }
    </style>
    <link rel="stylesheet" id="wmc-flags-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woo-multi-currency/css/flags-64.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="woocommerce-layout-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woocommerce/assets/css/woocommerce-layout.css?ver=7.6.0" type="text/css" media="all">
    <link rel="stylesheet" id="woocommerce-smallscreen-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woocommerce/assets/css/woocommerce-smallscreen.css?ver=7.6.0" type="text/css" media="only screen and (max-width: 768px)">
    <link rel="stylesheet" id="woocommerce-general-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woocommerce/assets/css/woocommerce.css?ver=7.6.0" type="text/css" media="all">
    <style id="woocommerce-inline-inline-css" type="text/css">
        .woocommerce form .form-row .required {
            visibility: visible;
        }
    </style>
    <link rel="stylesheet" id="tiny-slider-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/tiny-slider.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="owl-carousel-min-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/owl.carousel.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="owl-theme-default-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/owl.theme.default.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="font-awesome-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/fonts/font-awesome/css/font-awesome.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="icofont-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/icofont/icofont.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="bootstrap-icons-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/bootstrap1.5/bootstrap-icons.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-animations-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/animations.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-editor-style-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/editor-style.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-menu-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/menu.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-widgets-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/widget.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-main-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/main.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-theme-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/theme.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-default-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/default.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-media-query-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/css/responsive.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-style-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/style.css?ver=6.3.1" type="text/css" media="all">
    <style id="retailsy-style-inline-css" type="text/css">
        .bread-title {
            background: url(https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/breadcrumb.jpg) no-repeat center;
        }
        
        .bread-title::before {
            background: rgba(24, 24, 24, 1);
        }
        
        @media (min-width: 992px) {
            #st-primary-content {
                max-width: 72%;
                flex-basis: 72%;
            }
            #st-secondary-content {
                max-width: 28%;
                flex-basis: 28%;
            }
        }
        
        .jcs-container {
            max-width: 1170px;
        }
        
        .py-default {
            padding: 70px 0;
        }
        
        body {
            font-weight: inherit;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: none;
        }
        
        h1 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
        h2 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
        h3 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
        h4 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
        h5 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
        h6 {
            font-family: ;
            font-weight: 700;
            text-transform: inherit;
            font-style: inherit;
            text-decoration: inherit;
        }
        
         :root {
            --color-hover: 247, 124, 41;
        }
        
        .footer-section {
            background-color: #f7f7f7;
        }
    </style>
    <link rel="stylesheet" id="retailsy-fonts-css" href="//fonts.googleapis.com/css?family=Poppins%3Aital%2Cwght%400%2C100%3B0%2C200%3B0%2C300%3B0%2C400%3B0%2C500%3B0%2C600%3B0%2C700%3B0%2C800%3B0%2C900%3B1%2C100%3B1%2C200%3B1%2C300%3B1%2C400%3B1%2C500%3B1%2C600%3B1%2C700%3B1%2C800%3B1%2C900&amp;subset=latin%2Clatin-ext"
        type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-product-search-style-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-product-search.css?ver=1.0.0" type="text/css" media="all">
    <link rel="stylesheet" id="dashicons-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-includes/css/dashicons.min.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-woocompare-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-woocompare.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-woowishlist-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-woowishlist.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="bootstrap-grid-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/grid.css?ver=6.3.1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-product-video-css-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-product-video.css?ver=1" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy_product_size_chart-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/sizechart_frontend.css?ver=1.0" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy-woosl-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-wcsl.css?ver=1.0" type="text/css" media="all">
    <link rel="stylesheet" id="flipper-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/libs/flipper/style.css?ver=1.0" type="text/css" media="all">
    <link rel="stylesheet" id="retailsy_ct-frontend-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/retailsy-countdown-frontend.css?ver=1.0" type="text/css" media="all">
    <link rel="stylesheet" id="stwsb-frontend-css" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/inc/retailsy-woocommerce/assets/css/bundle-frontend.css?ver=1.0" type="text/css" media="all">
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-includes/js/jquery/jquery.min.js?ver=3.7.0" id="jquery-core-js"></script>
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js"></script>
    <script type="text/javascript" id="woo-multi-currency-js-extra">
        var wooMultiCurrencyParams = {
            "enableCacheCompatible": "0",
            "ajaxUrl": "https:\/\/preview.sellerthemes.com\/pro\/retailsy\/wp-admin\/admin-ajax.php",
            "extra_params": [],
            "current_currency": "USD"
        };
        /* ]]> */
    </script>
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/plugins/woo-multi-currency/js/woo-multi-currency.min.js?ver=2.1.29" id="woo-multi-currency-js"></script>
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/js/tiny-slider.js?ver=1" id="tiny-slider-js"></script>
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/js/owl.carousel.min.js?ver=1" id="owl-carousel-js"></script>
    <script type="text/javascript" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/js/owlcarousel2-filter.min.js?ver=1" id="owlcarousel2-filter-js"></script>
    <link rel="https://api.w.org/" href="https://preview.sellerthemes.com/pro/retailsy/wp-json/">
    <link rel="alternate" type="application/json" href="https://preview.sellerthemes.com/pro/retailsy/wp-json/wp/v2/pages/1229">
    <link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://preview.sellerthemes.com/pro/retailsy/xmlrpc.php?rsd">
    <meta name="generator" content="WordPress 6.3.1">
    <meta name="generator" content="WooCommerce 7.6.0">
    <link rel="canonical" href="https://preview.sellerthemes.com/pro/retailsy/">
    <link rel="shortlink" href="https://preview.sellerthemes.com/pro/retailsy/">
    <link rel="alternate" type="application/json+oembed" href="https://preview.sellerthemes.com/pro/retailsy/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fpreview.sellerthemes.com%2Fpro%2Fretailsy%2F">
    <link rel="alternate" type="text/xml+oembed" href="https://preview.sellerthemes.com/pro/retailsy/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fpreview.sellerthemes.com%2Fpro%2Fretailsy%2F&amp;format=xml">
    <style>
        body.boxed {
            background: url("https://preview.sellerthemes.com/pro/retailsy/wp-content/themes/retailsy-pro/assets/images/bg-pattern/bg-img1.png");
        }
    </style> <noscript><style>.woocommerce-product-gallery{ opacity: 1 !important; }</style></noscript>
    <style type="text/css">
        .recentcomments a {
            display: inline !important;
            padding: 0 !important;
            margin: 0 !important;
        }
    </style>
    <style type="text/css">
        body .header h4.site-title,
        body .header p.site-description {
            color: #fff;
        }
    </style>
    <link rel="icon" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/cropped-Light-32x32.png" sizes="32x32">
    <link rel="icon" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/cropped-Light-192x192.png" sizes="192x192">
    <link rel="apple-touch-icon" href="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/cropped-Light-180x180.png">
    <meta name="msapplication-TileImage" content="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/cropped-Light-270x270.png">
    <script src="https://preview.sellerthemes.com/pro/retailsy/wp-includes/js/wp-emoji-release.min.js?ver=6.3.1" defer=""></script>
    <style></style>
    <style></style>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@300&amp;display=swap">
    <link href="chrome-extension://iibninhmiggehlcdolcilmhacighjamp/shared-ui-components/fonts.css" rel="stylesheet">
</head>

<body class="home page-template page-template-templates page-template-template-homepage page-template-templatestemplate-homepage-php page page-id-1229 wp-custom-logo wide theme-retailsy-pro woocommerce-multi-currency-USD woocommerce-js header1 home1"
    style="overflow-y: auto;">

    <div id="page" class="site">
        <a class="skip-link screen-reader-text" href="#content">Skip to content</a>

        <header id="header-section" class="header header-one">



            <div id="above-header" class="header-above-info d-block d-none">
                <div class="header-widget header-dark">
                    <div class="jcs-container">
                        <div class="jcs-row align-items-start">

                            <div class="col-6">
                                <div class="widget-left text-lg-left text-center">
                                    <aside id="info_widget-2" class="widget retailsy_info_widget">
                                        <h5 class="widget-title">Info Icon<span></span></h5>
                                        <ul>
                                            <li><a class="infoicon-fa-lock tool-bounce tool-bottom-left" href="#" aria-label="fa-lock" target="_blank" style="font-size:14px;"><i class="fa fa-lock" style="color:#f77c29; background-color:Icon BG; border-radius: 0px;"></i><span class="info_description_name"> 100% Secure Delivery</span></a></li>
                                            <li><a class="infoicon-fa-gift tool-bounce tool-bottom-left" href="#" aria-label="fa-gift" target="_blank" style="font-size:14px;"><i class="fa fa-gift" style="color:#f77c29; background-color:Icon BG; border-radius: 0px;"></i><span class="info_description_name"> Gift Vouchers</span></a></li>
                                            <li><a class="infoicon-fa-question-circle tool-bounce tool-bottom-left" href="#" aria-label="fa-question-circle" target="_blank" style="font-size:14px;"><i class="fa fa-question-circle" style="color:#f77c29; background-color:Icon BG; border-radius: 0px;"></i><span class="info_description_name"> FAQ</span></a></li>
                                        </ul>

                                    </aside>
                                </div>
                            </div>
                            <div class="col-6">
                                <div class="widget-right justify-content-lg-end text-right text-center">
                                    <aside id="nav_menu-2" class="widget widget_nav_menu">
                                        <div class="menu-language-container">
                                            <ul id="menu-language" class="menu">
                                                <li id="menu-item-1224" class="pll-parent-menu-item menu-item menu-item-type-custom menu-item-object-custom current-menu-parent menu-item-has-children menu-item-1224">
                                                    <a href="#pll_switcher"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAALCAMAAABBPP0LAAAAt1BMVEWSmb66z+18msdig8La3u+tYX9IaLc7W7BagbmcUW+kqMr/q6n+//+hsNv/lIr/jIGMnNLJyOP9/fyQttT/wb3/////aWn+YWF5kNT0oqz0i4ueqtIZNJjhvt/8gn//WVr/6+rN1+o9RKZwgcMPJpX/VFT9UEn+RUX8Ozv2Ly+FGzdYZrfU1e/8LS/lQkG/mbVUX60AE231hHtcdMb0mp3qYFTFwNu3w9prcqSURGNDaaIUMX5FNW5wYt7AAAAAjklEQVR4AR3HNUJEMQCGwf+L8RR36ajR+1+CEuvRdd8kK9MNAiRQNgJmVDAt1yM6kSzYVJUsPNssAk5N7ZFKjVNFAY4co6TAOI+kyQm+LFUEBEKKzuWUNB7rSH/rSnvOulOGk+QlXTBqMIrfYX4tSe2nP3iRa/KNK7uTmWJ5a9+erZ3d+18od4ytiZdvZyuKWy8o3UpTVAAAAABJRU5ErkJggg=="
                                                            alt="English" width="16" height="11" style="width: 16px; height: 11px;"><span style="margin-left:0.3em;">English</span></a>
                                                    <ul class="sub-menu">
                                                        <li id="menu-item-1224-en" class="lang-item lang-item-105 lang-item-en current-lang lang-item-first menu-item menu-item-type-custom menu-item-object-custom current_page_item menu-item-home menu-item-1224-en">
                                                            <a href="https://preview.sellerthemes.com/pro/retailsy/" hreflang="en-GB" lang="en-GB"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAALCAMAAABBPP0LAAAAt1BMVEWSmb66z+18msdig8La3u+tYX9IaLc7W7BagbmcUW+kqMr/q6n+//+hsNv/lIr/jIGMnNLJyOP9/fyQttT/wb3/////aWn+YWF5kNT0oqz0i4ueqtIZNJjhvt/8gn//WVr/6+rN1+o9RKZwgcMPJpX/VFT9UEn+RUX8Ozv2Ly+FGzdYZrfU1e/8LS/lQkG/mbVUX60AE231hHtcdMb0mp3qYFTFwNu3w9prcqSURGNDaaIUMX5FNW5wYt7AAAAAjklEQVR4AR3HNUJEMQCGwf+L8RR36ajR+1+CEuvRdd8kK9MNAiRQNgJmVDAt1yM6kSzYVJUsPNssAk5N7ZFKjVNFAY4co6TAOI+kyQm+LFUEBEKKzuWUNB7rSH/rSnvOulOGk+QlXTBqMIrfYX4tSe2nP3iRa/KNK7uTmWJ5a9+erZ3d+18od4ytiZdvZyuKWy8o3UpTVAAAAABJRU5ErkJggg=="
                                                                    alt="English" width="16" height="11" style="width: 16px; height: 11px;"><span style="margin-left:0.3em;">English</span></a>
                                                        </li>
                                                        <li id="menu-item-1224-es" class="lang-item lang-item-108 lang-item-es menu-item menu-item-type-custom menu-item-object-custom menu-item-1224-es">
                                                            <a href="https://preview.sellerthemes.com/pro/retailsy/es/home-espanol/" hreflang="es-CR" lang="es-CR"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAALCAMAAABBPP0LAAAAe1BMVEUACYYAAHoAAGwAAFmUqdWMo9GCm815kshxjMT7/v75+vr19/fi5eX5oqL81dX6ycj2v7/0t7bgaGbgAADxcnPtUFDqRkboPj7mNzflLy/kJibiGxu6AADfEhLdDw/xh4Xwrq3tpKTUPjzy8/Nohb5dfLgAACEAAEgAADT3QOSVAAAATklEQVR4AQXBMQ4BABAAwdnLkRCJVqH0/3/p9AQzgRAhi4jk3QmIoN2CEL/ZY5FK+RwGUimTRalkyl5ehSthpvMvxA08myW5E2riQfjCH0mcB8B5WEZHAAAAAElFTkSuQmCC"
                                                                    alt="Español" width="16" height="11" style="width: 16px; height: 11px;"><span style="margin-left:0.3em;">Español</span></a>
                                                        </li>
                                                        <li id="menu-item-1224-ro" class="lang-item lang-item-112 lang-item-ro menu-item menu-item-type-custom menu-item-object-custom menu-item-1224-ro">
                                                            <a href="https://preview.sellerthemes.com/pro/retailsy/ro/home-romana/" hreflang="ro-RO" lang="ro-RO"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAALCAMAAABBPP0LAAAAbFBMVEUAJsgAFMT13wDyAgLqAAB4muX8/G3581z5Vlb3RkZagt78/Ef5+T/08Tn1NTX1KSlQe9709Ez5+TX36S71GxvkAABHdNv4+CvzDw8AA7lqjuFBcNn29h/05Rg6adnfAAAAAK3nvQDrwgDkqgALguDCAAAAX0lEQVR4ARXHtWEDQBAEwNmn4BMz9V+eIzsTS8c7EWqR2mQgkJDTYHIZ5cRRg7XJWjG9tLIypqmVV7k0aN8f1vTw3OXaNft5mwyyG7NTxi/5+WPFSdYpPA+fSG60/4074PMLPA8bHzoAAAAASUVORK5CYII="
                                                                    alt="Română" width="16" height="11" style="width: 16px; height: 11px;"><span style="margin-left:0.3em;">Română</span></a>
                                                        </li>
                                                    </ul>
                                                </li>
                                            </ul>
                                        </div>
                                    </aside>
                                    <aside id="wmc_widget-1" class="widget widget_wmc_widget">
                                        <h5 class="widget-title">Currency</h5>
                                        <div class="woo-multi-currency wmc-shortcode">
                                            <div class="wmc-currency">
                                                <select class="wmc-nav" onchange="this.options[this.selectedIndex].value &amp;&amp; (window.location = this.options[this.selectedIndex].value);" fdprocessedid="xd0lvy">
                        <option selected="selected" value="/pro/retailsy/?wmc-currency=USD" data-currency="USD">
                United States (US) dollar                </option>
                        <option value="/pro/retailsy/?wmc-currency=EUR" data-currency="EUR">
                Euro                </option>
        
    </select>
                                            </div>
                                        </div>
                                    </aside>
                                    <aside id="social_widget-7" class="widget retailsy_social_icon_widget">
                                        <h5 class="widget-title">Social Icon</h5>
                                        <ul>
                                            <li><a class="socicon-fa-facebook tool-bounce tool-bottom-left" href="#" aria-label="fa-facebook" target="_blank" style=" font-size: 14px;"><i class="fa fa-facebook" style="color:#ffffff; background-color: #f77c29; border-radius: 1000px;"></i></a></li>
                                            <li><a class="socicon-fa-twitter tool-bounce tool-bottom-left" href="#" aria-label="fa-twitter" target="_blank" style=" font-size: 14px;"><i class="fa fa-twitter" style="color:#ffffff; background-color: #f77c29; border-radius: 1000px;"></i></a></li>
                                            <li><a class="socicon-fa-instagram tool-bounce tool-bottom-left" href="#" aria-label="fa-instagram" target="_blank" style=" font-size: 14px;"><i class="fa fa-instagram" style="color:#ffffff; background-color: #f77c29; border-radius: 1000px;"></i></a></li>
                                            <li><a class="socicon-fa-linkedin tool-bounce tool-bottom-left" href="#" aria-label="fa-linkedin" target="_blank" style=" font-size: 14px;"><i class="fa fa-linkedin" style="color:#ffffff; background-color: #f77c29; border-radius: 1000px;"></i></a></li>
                                            <li><a class="socicon-fa-vimeo tool-bounce tool-bottom-left" href="#" aria-label="fa-vimeo" target="_blank" style=" font-size: 14px;"><i class="fa fa-vimeo" style="color:#ffffff; background-color: #f77c29; border-radius: 1000px;"></i></a></li>
                                        </ul>

                                    </aside>
                                </div>
                            </div>

                        </div>
                    </div>
                </div>
            </div>


            <div class="navigation-middle d-block">
                <div class="jcs-container">
                    <div class="jcs-row navigation-middle-row">
                        <div class="col-lg-3 col-12 d-none d-block text-lg-left text-center my-auto mb-lg-auto mb-2">
                            <div class="logo">
                                <a href="https://preview.sellerthemes.com/pro/retailsy/" class="custom-logo-link" rel="home" aria-current="page"><img width="220" height="60" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/Light.png" class="custom-logo" alt="Retailsy" decoding="async"></a>
                            </div>
                        </div>
                        <div class="col-lg-6 col-12 text-center my-auto mb-lg-auto mb-2 d-block">
                            <div class="footer-search-overlay">
                                <button type="button" class="header-close-menu close-style"></button>
                                <div class="header-search-form product-search">
                                    <form name="product-search" method="get" action="https://preview.sellerthemes.com/pro/retailsy/">
                                        <div class="custom-search-select search-wrapper">
                                            <select name="category" class="category header-search-select" fdprocessedid="xv8sfw">
                            <option class="default" value="">Select Category</option>
                        
                                                            <option class="default" value="all">All</option>
                                                                <option class="default" value="best-seller">Best Seller</option>
                                                                <option class="default" value="deal-of-day">Deal of day</option>
                                                                <option class="default" value="electronics">Electronics</option>
                                                                <option class="default" value="featured">Featured</option>
                                                                <option class="default" value="furniture">Furniture</option>
                                                                <option class="default" value="latest">Latest</option>
                                                                <option class="default" value="offers">Offers</option>
                                                                <option class="default" value="product">Product</option>
                                                    </select>
                                        </div>
                                        <input type="hidden" name="post_type" value="product">
                                        <input type="search" name="s" class="search header-search-input search-field" placeholder="Search Products Here" value="">
                                        <svg class="search-svg" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 471.701 471.701">
                        <path d="M409.6,0c-9.426,0-17.067,7.641-17.067,17.067v62.344C304.667-5.656,164.478-3.386,79.411,84.479
                            c-40.09,41.409-62.455,96.818-62.344,154.454c0,9.426,7.641,17.067,17.067,17.067S51.2,248.359,51.2,238.933
                            c0.021-103.682,84.088-187.717,187.771-187.696c52.657,0.01,102.888,22.135,138.442,60.976l-75.605,25.207
                            c-8.954,2.979-13.799,12.652-10.82,21.606s12.652,13.799,21.606,10.82l102.4-34.133c6.99-2.328,11.697-8.88,11.674-16.247v-102.4
                            C426.667,7.641,419.026,0,409.6,0z"></path>
                        <path d="M443.733,221.867c-9.426,0-17.067,7.641-17.067,17.067c-0.021,103.682-84.088,187.717-187.771,187.696
                            c-52.657-0.01-102.888-22.135-138.442-60.976l75.605-25.207c8.954-2.979,13.799-12.652,10.82-21.606
                            c-2.979-8.954-12.652-13.799-21.606-10.82l-102.4,34.133c-6.99,2.328-11.697,8.88-11.674,16.247v102.4
                            c0,9.426,7.641,17.067,17.067,17.067s17.067-7.641,17.067-17.067v-62.345c87.866,85.067,228.056,82.798,313.122-5.068
                            c40.09-41.409,62.455-96.818,62.344-154.454C460.8,229.508,453.159,221.867,443.733,221.867z"></path>
                    </svg>
                                        <button class="header-search-button search-submit" type="submit" fdprocessedid="2h1jd"><i class="fa fa-search" aria-hidden="true"></i></button>
                                    </form>
                                    <div class="search-results woocommerce"></div>
                                </div>
                            </div>
                        </div>
                        <div class="col-lg-3 col-12 text-lg-right d-none d-block text-center my-auto mb-lg-auto mb-2">
                            <div class="main-menu-right">
                                <ul class="menu-right-list">
                                    <li class="favourite">
                                        <div class="favourite-btn">
                                            <a href="https://preview.sellerthemes.com/pro/retailsy/wishlist/" class="e-commerce-corn">
                                                <i class="fa fa-heart-o"></i>
                                                <i class="fa fa-heart-o"></i>
                                            </a>

                                            <span class="yith-wcwl-items-count">0</span>
                                            <p>Wishlist</p>
                                        </div>
                                    </li>

                                    <li class="arrow">
                                        <div class="arrow-btn">
                                            <a href="https://preview.sellerthemes.com/pro/retailsy/compare/" class="e-commerce-corn">
                                                <i class="fa fa-refresh"></i>
                                                <i class="fa fa-refresh"></i>
                                            </a>
                                            <span class="yith-wcwl-items-count">0</span>
                                            <p>Compare</p>
                                        </div>
                                    </li>
                                    <li class="cart-wrapper">
                                        <div class="cart-main">
                                            <button type="button" class="cart-icon-wrap header-cart cart-trigger" fdprocessedid="1ut4el">
                    <a href="javascript:void(0)" class="e-commerce-corn" id="cart-bag">
                     <i class="fa fa-cart-plus"></i><i class="fa fa-cart-plus"></i>
                    </a> 
                                                             
        <span class="cart-counts">0</span>
    
                                                    </button>
                                            <p>Cart</p>

                                            <span class="cart-label">
    <span><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>0.00</span>
                                            </span>
                                            </span>

                                        </div>
                                        <div class="cart-modal cart-modal-1">
                                            <div class="cart-container">
                                                <div class="cart-header">
                                                    <div class="cart-top">
                                                        <span class="cart-text">Cart</span>
                                                        <a href="javascript:void(0);" class="cart-close"><i class="fa fa-times"></i></a>
                                                    </div>
                                                </div>
                                                <div class="cart-data">

                                                    <p class="woocommerce-mini-cart__empty-message">No products in the cart.</p>


                                                </div>

                                            </div>
                                            <div class="cart-overlay"></div>
                                        </div>
                                    </li>
                                    <li class="user">
                                        <div class="user-btn">
                                            <a href="https://preview.sellerthemes.com/pro/retailsy/my-account/" class="e-commerce-corn">
                                                <i class="fa fa-sign-in"></i>
                                                <i class="fa fa-sign-in"></i>
                                            </a>
                                            <p>Login</p>

                                        </div>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>



            <div class="navigator-wrapper">
                <!--===// Start: Mobile Toggle
=================================-->
                <div class="theme-mobile-nav sticky-nav">
                    <div class="jcs-container">
                        <div class="jcs-row">
                            <div class="col-12">
                                <div class="theme-mobile-menu">
                                    <div class="menu-toggle-wrap">
                                        <div class="hamburger hamburger-menu">
                                            <button type="button" class="toggle-lines menu-toggle" id="mob-toggle-lines" fdprocessedid="b90pik">
                                    <div class="top-bun"></div>
                                    <div class="meat"></div>
                                    <div class="bottom-bun"></div>
                                </button>
                                        </div>

                                    </div>
                                    <div class="mobile-logo">
                                        <div class="logo">
                                            <a href="https://preview.sellerthemes.com/pro/retailsy/" class="custom-logo-link" rel="home" aria-current="page"><img width="220" height="60" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/Light.png" class="custom-logo" alt="Retailsy" decoding="async"></a>
                                        </div>
                                    </div>
                                    <div id="mobile-m" class="mobile-menu">
                                        <button type="button" class="header-close-menu close-style"></button>
                                        <div class="switcher-tab">
                                            <button class="active-bg">Menu</button>
                                            <button class="cat-menu-bt"><i class="fa fa-list-ul"></i> Browse Categories</button>
                                        </div>
                                        <ul id="menu-primary-menu" class="main-menu menu-wrap">
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1249" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-1229 current_page_item active menu-item-1249 nav-item"><a title="Home" href="https://preview.sellerthemes.com/pro/retailsy/" class="nav-link hover-color" aria-current="page" style="font-weight: 800;"><span class="nav-link-text" data-splitting="">Home</span></a></li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-220" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-220 nav-item"><a title="Pages" href="#" class="nav-link"><span class="nav-link-text" data-splitting="">Pages</span></a>
                                                <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                <ul class="dropdown-menu" role="menu">
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1596" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1596 nav-item"><a title="About Us" href="https://preview.sellerthemes.com/pro/retailsy/about-us/" class="dropdown-item"><span class="nav-link-text" data-splitting="">About Us</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1597" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1597 nav-item"><a title="Team" href="https://preview.sellerthemes.com/pro/retailsy/team/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Team</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-210" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-210 nav-item"><a title="Term &amp; Condition" href="https://preview.sellerthemes.com/pro/retailsy/term-condition/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Term &amp; Condition</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1347" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1347 nav-item"><a title="Refund  Policy" href="https://preview.sellerthemes.com/pro/retailsy/refund_returns-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Refund  Policy</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-212" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-212 nav-item"><a title="Privacy Policy" href="https://preview.sellerthemes.com/pro/retailsy/privacy-policy-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Privacy Policy</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-269" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-269 nav-item"><a title="404 Page" href="https://preview.sellerthemes.com/pro/retailsy/404" class="dropdown-item"><span class="nav-link-text" data-splitting="">404 Page</span></a></li>
                                                </ul>
                                            </li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1330" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children dropdown menu-item-1330 nav-item"><a title="Shop" href="https://preview.sellerthemes.com/pro/retailsy/shop/" class="nav-link"><span class="nav-link-text" data-splitting="">Shop</span></a>
                                                <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1331" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1331 nav-item"><a title="Cart" href="https://preview.sellerthemes.com/pro/retailsy/cart/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Cart</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1332" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1332 nav-item"><a title="Checkout" href="https://preview.sellerthemes.com/pro/retailsy/checkout/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Checkout</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1333" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1333 nav-item"><a title="My account" href="https://preview.sellerthemes.com/pro/retailsy/my-account/" class="dropdown-item"><span class="nav-link-text" data-splitting="">My account</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1267" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1267 nav-item"><a title="Compare" href="https://preview.sellerthemes.com/pro/retailsy/compare-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Compare</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1261" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1261 nav-item"><a title="Wishlist" href="https://preview.sellerthemes.com/pro/retailsy/wishlist-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Wishlist</span></a></li>
                                                </ul>
                                            </li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1316" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-1316 nav-item"><a title="Features" href="#" class="nav-link"><span class="nav-link-text" data-splitting="">Features</span></a>
                                                <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1317" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-1317 nav-item"><a title="More Features" href="#" class="dropdown-item"><span class="nav-link-text" data-splitting="">More Features</span></a>
                                                        <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                        <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1119" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1119 nav-item"><a title="Save Later" href="https://preview.sellerthemes.com/pro/retailsy/cart/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Save Later</span></a></li>
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1120" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1120 nav-item"><a title="Quantity Left" href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Quantity Left</span></a></li>
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1121" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1121 nav-item"><a title="Product Bundle" href="https://preview.sellerthemes.com/pro/retailsy/product/t-shirt/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Bundle</span></a></li>
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1122" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1122 nav-item"><a title="Size Chart" href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Size Chart</span></a></li>
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1124" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1124 nav-item"><a title="Color Swatches" href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Color Swatches</span></a></li>
                                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1351" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1351 nav-item"><a title="Need Help" href="https://preview.sellerthemes.com/pro/retailsy/need-help/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Need Help</span></a></li>
                                                        </ul>
                                                    </li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-906" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-906 nav-item"><a title="Product 360 View" href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product 360 View</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1123" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1123 nav-item"><a title="Related Products" href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Related Products</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1113" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1113 nav-item"><a title="Image Magnifier" href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Image Magnifier</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1114" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1114 nav-item"><a title="Sale Timer" href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Sale Timer</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1115" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1115 nav-item"><a title="Product FAQ" href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product FAQ</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1116" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1116 nav-item"><a title="Product Share" href="https://preview.sellerthemes.com/pro/retailsy/product/hat/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Share</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1117" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1117 nav-item"><a title="Product Video" href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Video</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1118" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1118 nav-item"><a title="EMI Module" href="https://preview.sellerthemes.com/pro/retailsy/product/shoes/" class="dropdown-item"><span class="nav-link-text" data-splitting="">EMI Module</span></a></li>
                                                </ul>
                                            </li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-1036" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children dropdown menu-item-1036 nav-item"><a title="Blog" href="https://preview.sellerthemes.com/pro/retailsy/blog/" class="nav-link"><span class="nav-link-text" data-splitting="">Blog</span></a>
                                                <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-67" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-67 nav-item"><a title="Blog Left Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-left-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Left Sidebar</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-215" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-215 nav-item"><a title="Blog Right Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-right-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Right Sidebar</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-213" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-213 nav-item"><a title="Blog No Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-no-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog No Sidebar</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-214" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-214 nav-item"><a title="Blog Masonry" href="https://preview.sellerthemes.com/pro/retailsy/blog-masonry/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Masonry</span></a></li>
                                                    <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-268" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-268 nav-item"><a title="Blog Single" href="https://preview.sellerthemes.com/pro/retailsy/blog/2022/02/17/the-holiday-hosting-hack-i-live-by/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Single</span></a></li>
                                                </ul>
                                            </li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-216" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-216 nav-item"><a title="FAQ Page" href="https://preview.sellerthemes.com/pro/retailsy/faq-page/" class="nav-link"><span class="nav-link-text" data-splitting="">FAQ Page</span></a></li>
                                            <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" id="menu-item-224" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-224 nav-item"><a title="Contact" href="https://preview.sellerthemes.com/pro/retailsy/contact/" class="nav-link"><span class="nav-link-text" data-splitting="">Contact</span></a></li>
                                        </ul>
                                        <div class="product-categories d-none">
                                            <div class="product-categories-list">
                                                <ul class="main-menu">
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/all/"><i class="fa fa-globe"></i>All</a></li>
                                                    <li class="menu-item main-top-menu menu-item-has-children"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/"><i class="fa fa-certificate  "></i>Best Seller</a><span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                        <ul class="dropdown-menu 2-main-top-menu">
                                                            <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/smarttv/"><i class="fa fa-television"></i>Smart TV</a></li>
                                                            <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/smartwatch/"><i class="fa fa-clock-o"></i>SmartWatch</a></li>
                                                        </ul>
                                                    </li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/deal-of-day/"><i class="fa fa-briefcase "></i>Deal of day</a></li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/featured/"><i class="fa fa-newspaper-o "></i>Featured</a></li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/furniture/"><i class="fa fa-bed"></i>Furniture</a></li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/latest/"><i class="fa fa-bolt"></i>Latest</a></li>
                                                    <li class="menu-item main-top-menu menu-item-has-children"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/"><i class="fa fa-diamond"></i>Offers</a><span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                        <ul class="dropdown-menu 2-main-top-menu">
                                                            <li class="menu-item menu-item-has-children"><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/"><i class="fa fa-sun-o"></i>Electronics</a><span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                                <ul class="dropdown-menu 3-main-top-menu">
                                                                    <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/laptop/"><i class="fa fa-laptop"></i>Laptop</a></li>
                                                                    <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/mac/"><i class="fa fa-tablet"></i>MAC</a></li>
                                                                    <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/pc/"><i class="fa fa-desktop"></i>Pc</a></li>
                                                                    <li class="menu-item "><a class="dropdown-item" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/smartphone/"><i class="fa fa-mobile"></i>SmartPhone</a></li>
                                                                </ul>
                                                            </li>
                                                        </ul>
                                                    </li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/product/"><i class="fa fa-product-hunt"></i>Product</a></li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/uncategorized/"><i class="fa fa-code-fork"></i>Uncategorized</a></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="mobile-menu-right">
                                        <ul class="header-wrap-right">
                                            <li class="cart-wrapper">
                                                <div class="cart-main">
                                                    <button type="button" class="cart-icon-wrap header-cart cart-trigger" fdprocessedid="ty7uhq">
                    <a href="javascript:void(0)" class="e-commerce-corn" id="cart-bag">
                     <i class="fa fa-cart-plus"></i><i class="fa fa-cart-plus"></i>
                    </a> 
                                                             
        <span class="cart-counts">0</span>
    
                                                    </button>
                                                    <p>Cart</p>

                                                    <span class="cart-label">
    <span><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>0.00</span>
                                                    </span>
                                                    </span>

                                                </div>
                                                <div class="cart-modal cart-modal-1">
                                                    <div class="cart-container">
                                                        <div class="cart-header">
                                                            <div class="cart-top">
                                                                <span class="cart-text">Cart</span>
                                                                <a href="javascript:void(0);" class="cart-close"><i class="fa fa-times"></i></a>
                                                            </div>
                                                        </div>
                                                        <div class="cart-data">

                                                            <p class="woocommerce-mini-cart__empty-message">No products in the cart.</p>


                                                        </div>

                                                    </div>
                                                    <div class="cart-overlay"></div>
                                                </div>
                                            </li>
                                        </ul>
                                    </div>
                                    <div class="header-above-wrapper">
                                        <div class="header-above-index">
                                            <div class="header-above-btn">
                                                <button type="button" class="header-above-collapse" aria-label="Header Above Collapse" fdprocessedid="q7qebi"><span></span></button>
                                            </div>
                                            <div id="header-above-bar" class="header-above-bar">
                                                <div class="header-widget d-flex align-items-center">
                                                    <div class="container">
                                                        <div class="row">
                                                            <div class="col-lg-6 col-12 mb-lg-0 ">
                                                                <div class="widget-left text-lg-left text-center">
                                                                    <aside id="wmc_widget-1" class="widget widget_wmc_widget">
                                                                        <h5 class="widget-title">Currency</h5>
                                                                        <div class="woo-multi-currency shortcode">
                                                                            <div class="wmc-currency">
                                                                                <select class="wmc-nav" onchange="this.options[this.selectedIndex].value &amp;&amp; (window.location = this.options[this.selectedIndex].value);">
                        <option selected="selected" value="/pro/storely/?wmc-currency=USD" data-currency="USD">
                United States (US) dollar                </option>
                        <option value="/pro/storely/?wmc-currency=EUR" data-currency="EUR">
                Euro                </option>
        
    </select>
                                                                            </div>
                                                                        </div>
                                                                    </aside>
                                                                    <aside id="polylang-2" class="widget widget_polylang">
                                                                        <h5 class="widget-title">Language</h5><label class="screen-reader-text" for="lang_choice_polylang-2">Language</label><select name="lang_choice_polylang-2" id="lang_choice_polylang-2" class="pll-switcher-select">
<option value="https://preview.sellerthemes.com/pro/storely/af/home-2/">Afrikaans</option>
<option value="https://preview.sellerthemes.com/pro/storely/" selected="selected">English</option>
<option value="https://preview.sellerthemes.com/pro/storely/es/home-3/">Español</option>

</select></aside>
                                                                </div>
                                                            </div>
                                                            <div class="col-lg-6 col-12 mb-lg-0 ">
                                                                <div class="widget-right justify-content-lg-end justify-content-center text-lg-right text-center">
                                                                    <aside class="widget widget_social_widget">
                                                                        <ul>
                                                                            <li><a href="#"><i class="fa fa-facebook"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-twitter"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-behance"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-pinterest-p"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-whatsapp"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-instagram"></i></a></li>
                                                                            <li><a href="#"><i class="fa fa-youtube-play"></i></a></li>
                                                                        </ul>
                                                                    </aside>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--===// End: Mobile Toggle
=================================-->

                <!--===// Start: Navigation
=================================-->
                <div class="nav-area d-none d-block">
                    <div class="navbar-area sticky-nav">
                        <div class="jcs-container">
                            <div class="jcs-row">
                                <div class="col-3 my-auto">
                                    <div class="product-category-browse active">
                                        <button type="button" class="product-category-btn" fdprocessedid="w54bk5">
        <span class="cat-left">
            <i class="fa fa-list-ul"></i> Browse Categories			</span>
        <i class="fa fa-spinner"></i>
    </button>
                                        <div class="product-category-menus">
                                            <div class="product-category-menus-list active">
                                                <ul class="main-menu" style="display: ">
                                                    <li class="menu-item main-top-menu " style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/all/"><i class="fa fa-globe"></i>All</a></li>
                                                    <li class="menu-item main-top-menu menu-item-has-children" style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/"><i class="fa fa-certificate  "></i>Best Seller</a>
                                                        <ul class="dropdown-menu 2-main-top-menu">
                                                            <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/smarttv/"><i class="fa fa-television"></i>Smart TV</a></li>
                                                            <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/best-seller/smartwatch/"><i class="fa fa-clock-o"></i>SmartWatch</a></li>
                                                        </ul>
                                                    </li>
                                                    <li class="menu-item main-top-menu " style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/deal-of-day/"><i class="fa fa-briefcase "></i>Deal of day</a></li>
                                                    <li class="menu-item main-top-menu " style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/featured/"><i class="fa fa-newspaper-o "></i>Featured</a></li>
                                                    <li class="menu-item main-top-menu " style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/furniture/"><i class="fa fa-bed"></i>Furniture</a></li>
                                                    <li class="menu-item main-top-menu " style="display: list-item;"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/latest/"><i class="fa fa-bolt"></i>Latest</a></li>
                                                    <li class="menu-item main-top-menu menu-item-has-children"><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/"><i class="fa fa-diamond"></i>Offers</a>
                                                        <ul class="dropdown-menu 2-main-top-menu">
                                                            <li class="menu-item menu-item-has-children"><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/"><i class="fa fa-sun-o"></i>Electronics</a>
                                                                <ul class="dropdown-menu 3-main-top-menu">
                                                                    <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/laptop/"><i class="fa fa-laptop"></i>Laptop</a></li>
                                                                    <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/mac/"><i class="fa fa-tablet"></i>MAC</a></li>
                                                                    <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/pc/"><i class="fa fa-desktop"></i>Pc</a></li>
                                                                    <li class="menu-item "><a class="nav-link" href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/electronics/smartphone/"><i class="fa fa-mobile"></i>SmartPhone</a></li>
                                                                </ul>
                                                            </li>
                                                        </ul>
                                                    </li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/product/"><i class="fa fa-product-hunt"></i>Product</a></li>
                                                    <li class="menu-item main-top-menu "><a href="https://preview.sellerthemes.com/pro/retailsy/product-category/uncategorized/"><i class="fa fa-code-fork"></i>Uncategorized</a></li>
                                                    <li class="menu-item more-item"><button type="button" class="browse-more" fdprocessedid="36yphi"><i class="fa fa-plus"></i> <span>More Category</span></button></li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-9 my-auto">
                                    <div class="theme-menu">
                                        <nav class="menubar">
                                            <ul id="menu-primary-menu-1" class="main-menu menu-wrap">
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-home current-menu-item page_item page-item-1229 current_page_item active menu-item-1249 nav-item"><a title="Home" href="https://preview.sellerthemes.com/pro/retailsy/" class="nav-link hover-color" aria-current="page" style="font-weight: 800;"><span class="nav-link-text" data-splitting="">Home</span></a></li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-220 nav-item"><a title="Pages" href="#" class="nav-link"><span class="nav-link-text" data-splitting="">Pages</span></a>
                                                    <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                    <ul class="dropdown-menu" role="menu">
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1596 nav-item"><a title="About Us" href="https://preview.sellerthemes.com/pro/retailsy/about-us/" class="dropdown-item"><span class="nav-link-text" data-splitting="">About Us</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1597 nav-item"><a title="Team" href="https://preview.sellerthemes.com/pro/retailsy/team/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Team</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-210 nav-item"><a title="Term &amp; Condition" href="https://preview.sellerthemes.com/pro/retailsy/term-condition/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Term &amp; Condition</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1347 nav-item"><a title="Refund  Policy" href="https://preview.sellerthemes.com/pro/retailsy/refund_returns-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Refund  Policy</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-212 nav-item"><a title="Privacy Policy" href="https://preview.sellerthemes.com/pro/retailsy/privacy-policy-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Privacy Policy</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-269 nav-item"><a title="404 Page" href="https://preview.sellerthemes.com/pro/retailsy/404" class="dropdown-item"><span class="nav-link-text" data-splitting="">404 Page</span></a></li>
                                                    </ul>
                                                </li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children dropdown menu-item-1330 nav-item"><a title="Shop" href="https://preview.sellerthemes.com/pro/retailsy/shop/" class="nav-link"><span class="nav-link-text" data-splitting="">Shop</span></a>
                                                    <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                    <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1331 nav-item"><a title="Cart" href="https://preview.sellerthemes.com/pro/retailsy/cart/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Cart</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1332 nav-item"><a title="Checkout" href="https://preview.sellerthemes.com/pro/retailsy/checkout/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Checkout</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1333 nav-item"><a title="My account" href="https://preview.sellerthemes.com/pro/retailsy/my-account/" class="dropdown-item"><span class="nav-link-text" data-splitting="">My account</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1267 nav-item"><a title="Compare" href="https://preview.sellerthemes.com/pro/retailsy/compare-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Compare</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1261 nav-item"><a title="Wishlist" href="https://preview.sellerthemes.com/pro/retailsy/wishlist-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Wishlist</span></a></li>
                                                    </ul>
                                                </li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-1316 nav-item"><a title="Features" href="#" class="nav-link"><span class="nav-link-text" data-splitting="">Features</span></a>
                                                    <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                    <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children dropdown menu-item-1317 nav-item"><a title="More Features" href="#" class="dropdown-item"><span class="nav-link-text" data-splitting="">More Features</span></a>
                                                            <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                            <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1119 nav-item"><a title="Save Later" href="https://preview.sellerthemes.com/pro/retailsy/cart/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Save Later</span></a></li>
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1120 nav-item"><a title="Quantity Left" href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Quantity Left</span></a></li>
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1121 nav-item"><a title="Product Bundle" href="https://preview.sellerthemes.com/pro/retailsy/product/t-shirt/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Bundle</span></a></li>
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1122 nav-item"><a title="Size Chart" href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Size Chart</span></a></li>
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1124 nav-item"><a title="Color Swatches" href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Color Swatches</span></a></li>
                                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1351 nav-item"><a title="Need Help" href="https://preview.sellerthemes.com/pro/retailsy/need-help/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Need Help</span></a></li>
                                                            </ul>
                                                        </li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-906 nav-item"><a title="Product 360 View" href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product 360 View</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1123 nav-item"><a title="Related Products" href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Related Products</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1113 nav-item"><a title="Image Magnifier" href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Image Magnifier</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1114 nav-item"><a title="Sale Timer" href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Sale Timer</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1115 nav-item"><a title="Product FAQ" href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product FAQ</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1116 nav-item"><a title="Product Share" href="https://preview.sellerthemes.com/pro/retailsy/product/hat/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Share</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1117 nav-item"><a title="Product Video" href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Product Video</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1118 nav-item"><a title="EMI Module" href="https://preview.sellerthemes.com/pro/retailsy/product/shoes/" class="dropdown-item"><span class="nav-link-text" data-splitting="">EMI Module</span></a></li>
                                                    </ul>
                                                </li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children dropdown menu-item-1036 nav-item"><a title="Blog" href="https://preview.sellerthemes.com/pro/retailsy/blog/" class="nav-link"><span class="nav-link-text" data-splitting="">Blog</span></a>
                                                    <span class="mobile-collapsed d-lg-none"><span class="mobile-toggler"><button type="button" class="fa fa-chevron-right" aria-label="Mobile Toggler" aria-hidden="true"></button></span></span>
                                                    <ul class="dropdown-menu" aria-labelledby="true'></button></span></span><ul class=" role="menu">
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-67 nav-item"><a title="Blog Left Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-left-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Left Sidebar</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-215 nav-item"><a title="Blog Right Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-right-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Right Sidebar</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-213 nav-item"><a title="Blog No Sidebar" href="https://preview.sellerthemes.com/pro/retailsy/blog-no-sidebar/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog No Sidebar</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-214 nav-item"><a title="Blog Masonry" href="https://preview.sellerthemes.com/pro/retailsy/blog-masonry/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Masonry</span></a></li>
                                                        <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-268 nav-item"><a title="Blog Single" href="https://preview.sellerthemes.com/pro/retailsy/blog/2022/02/17/the-holiday-hosting-hack-i-live-by/" class="dropdown-item"><span class="nav-link-text" data-splitting="">Blog Single</span></a></li>
                                                    </ul>
                                                </li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-216 nav-item"><a title="FAQ Page" href="https://preview.sellerthemes.com/pro/retailsy/faq-page/" class="nav-link"><span class="nav-link-text" data-splitting="">FAQ Page</span></a></li>
                                                <li itemscope="itemscope" itemtype="https://www.schema.org/SiteNavigationElement" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-224 nav-item"><a title="Contact" href="https://preview.sellerthemes.com/pro/retailsy/contact/" class="nav-link"><span class="nav-link-text" data-splitting="">Contact</span></a></li>
                                            </ul>
                                        </nav>
                                        <div class="menu-right">
                                            <ul class="header-wrap-right">
                                                <li class="contact-wrapper">
                                                    <a href="#" class="headphone-icon-wrap" id="headphone" title="Contact Us">
                                                        <i class="fa fa-headphones" aria-hidden="true"></i>
                                                        <span class="contact-number">+51 234 567 89</span>
                                                    </a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--===// End:  Navigation
=================================-->
            </div>
        </header>
        <div class="d-none" style="height: 240px;"></div>



        <div id="content" class="retailsy-content">


            <section class="banner">
                <div class="tns-outer" id="tns1-ow">
                    <div class="tns-nav" aria-label="Carousel Pagination"><button data-nav="0" aria-controls="tns1" style="background-color: rgba(var(--color-icon),1);" aria-label="Carousel Page 1" class="" fdprocessedid="w6sm7c" tabindex="-1"></button><button data-nav="1" aria-controls="tns1" style="background-color: rgba(var(--color-icon),1);"
                            aria-label="Carousel Page 2" class="" fdprocessedid="9smuys" tabindex="-1"></button><button data-nav="2" aria-controls="tns1" style="background-color: rgba(var(--color-icon),1);" aria-label="Carousel Page 3" class="" fdprocessedid="4ufmon"
                            tabindex="-1"></button><button data-nav="3" aria-controls="tns1" style="background-color: rgba(var(--color-icon),1);" aria-label="Carousel Page 4" class="" fdprocessedid="o6uj8j" tabindex="-1"></button><button data-nav="4" aria-controls="tns1"
                            style="background-color: rgba(var(--color-icon),1);" aria-label="Carousel Page 5" class="" fdprocessedid="y0aqvc" tabindex="-1"></button><button data-nav="5" aria-controls="tns1" style="background-color: rgba(var(--color-hover),1);"
                            aria-label="Carousel Page 6 (Current Slide)" class="tns-nav-active" fdprocessedid="35ddii"></button></div>
                    <div class="tns-liveregion tns-visually-hidden" aria-live="polite" aria-atomic="true">slide <span class="current">6</span> of 6</div>
                    <div id="tns1-mw" class="tns-ovh">
                        <div class="tns-inner" id="tns1-iw">
                            <div class="page2-slider  tns-slider tns-carousel tns-subpixel tns-calc tns-horizontal" id="tns1" style="transform: translate3d(-83.3333%, 0px, 0px);">
                                <div class="page2-slider-wrapper tns-item" id="tns1-item0" aria-hidden="true" tabindex="-1">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/slider1-1.png" alt="Deal of the Day">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #f77c29">Deal of the Day</div>

                                                <div class="banner-main-content down animate seven" style="color: #ffffff">Save upto $200 First Order</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/Mobile.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="page2-slider-wrapper tns-item" id="tns1-item1" aria-hidden="true" tabindex="-1">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/4.jpg" alt="Exclusive offers 30% Off">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #f77c29">Exclusive offers 30% Off</div>

                                                <div class="banner-main-content down animate seven" style="color: #2b4279">Hot Trending Collection 2021</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/03/slider-speaker.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="page2-slider-wrapper tns-item" id="tns1-item2" aria-hidden="true" tabindex="-1">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/slider3.png" alt="Treading  Promotion ">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #F77C29">Treading Promotion </div>

                                                <div class="banner-main-content down animate seven" style="color: #ffffff">Flat 10% OFF Electronic items</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/Chair.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="page2-slider-wrapper tns-item" id="tns1-item3" aria-hidden="true" tabindex="-1">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/retailsysliderBackground-2.jpg" alt="Deals That Never Miss">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #f77c29">Deals That Never Miss</div>

                                                <div class="banner-main-content down animate seven" style="color: #2b4279">Upto 50% Off On First Purchase</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/retaisysliderwatch-2.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="page2-slider-wrapper tns-item" id="tns1-item4" aria-hidden="true" tabindex="-1">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/Background.jpg" alt="New Deals Arrived">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #f77c29">New Deals Arrived</div>

                                                <div class="banner-main-content down animate seven" style="color: #ffffff">Offer That You Can't Beat</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/product2.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="page2-slider-wrapper tns-item tns-slide-active" id="tns1-item5">
                                    <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/retailsysliderBackground-1.jpg" alt="Offers That Surprise You">

                                    <div class="jcs-container">
                                        <div class="jcs-row">
                                            <div class="banner-text-section">
                                                <div class="offer down animate seven" style="color: #f77c29">Offers That Surprise You</div>

                                                <div class="banner-main-content down animate seven" style="color: #2b4279">Grab Offer That May Comeback</div>

                                                <div class="bubble-flex item-wrapper gap10">
                                                    <a href="#" class="cbb blue">Shop Now <i class="fa fa-chevron-right"></i></a>

                                                    <a href="#" class="cbb orange">Add To Cart<i class="fa fa-chevron-right"></i></a>
                                                </div>
                                            </div>

                                            <div class="page2-image-slider"><img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/Headphone.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--<div class="jcs-container">
    <div class="outer-bullet-wrapper in2">
        <div id="bullet-wrapper">
            <div class="bullets"> </div>
            <div class="bullets"> </div>
            <div class="bullets"> </div>
        </div>
    </div>
</div> -->
                <div class="slider-arrows">
                    <div class="jcs-container">
                        <div class="outer-nav-wrapper in2 active">
                            <div id="nav-wrapper">
                                <a href="javascript:void(0)" class="prev1 prev navigator"><i class="fa fa-chevron-left"></i>
                </a>
                                <a href="javascript:void(0)" class="next1 next navigator"><i class="fa fa-chevron-right"></i>
                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="jcs-section-1 py-default info-home">
                <div class="jcs-container">
                    <div class="jcs-row info-service-flex">
                        <div class="col-12 col-sm-6 col-lg-3 info-service">
                            <div class="item-wrapper section-1-type">
                                <div class="">
                                    <div class="section-1-icon">
                                        <i class="fa fa-truck"></i>
                                    </div>
                                </div>
                                <div class="">
                                    <div class="service-1-action">
                                        <a href="#" class="service-1-title">Free Delivery $100</a>


                                        <div class="reverse-support">For All Orders $100</div>

                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-sm-6 col-lg-3 info-service">
                            <div class="item-wrapper section-1-type">
                                <div class="">
                                    <div class="section-1-icon">
                                        <i class="fa fa-money"></i>
                                    </div>
                                </div>
                                <div class="">
                                    <div class="service-1-action">
                                        <a href="#" class="service-1-title">Money Back Guarantee</a>


                                        <div class="reverse-support">Money Back</div>

                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-sm-6 col-lg-3 info-service">
                            <div class="item-wrapper section-1-type">
                                <div class="">
                                    <div class="section-1-icon">
                                        <i class="fa fa-link"></i>
                                    </div>
                                </div>
                                <div class="">
                                    <div class="service-1-action">
                                        <a href="#" class="service-1-title">Return 15 Days</a>


                                        <div class="reverse-support">For Free Return</div>

                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-sm-6 col-lg-3 info-service">
                            <div class="item-wrapper section-1-type">
                                <div class="">
                                    <div class="section-1-icon">
                                        <i class="fa fa-users"></i>
                                    </div>
                                </div>
                                <div class="">
                                    <div class="service-1-action">
                                        <a href="#" class="service-1-title">24/7 Support</a>


                                        <div class="reverse-support">Online Support</div>

                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="jcs-section-2 pb-default banner-home">
                <div class="jcs-container">
                    <div class="jcs-row banner-cards">
                        <div class="col-12 col-md-6 col-lg-4 product-banner-card">
                            <div class="card-display">
                                <div class="item-wrapper card-overlay">
                                    <div class="image-shine">
                                        <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/card1.png">

                                        <div class="section-2-left">

                                            <div class="section-2-name">Mobile &amp; Tab</div>

                                            <div class="section-2-discount">25% Discount</div>

                                            <div class="card-button-bubble-container">
                                                <a href="#" class="cbb smoke">Shop Now<i class="fa fa-chevron-right"></i>
                                        </a>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 col-lg-4 product-banner-card">
                            <div class="card-display">
                                <div class="item-wrapper card-overlay">
                                    <div class="image-shine">
                                        <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/card2.png">

                                        <div class="section-2-left">

                                            <div class="section-2-name">Digital Speaker</div>

                                            <div class="section-2-discount">45% Discount</div>

                                            <div class="card-button-bubble-container">
                                                <a href="#" class="cbb smoke">Shop Now<i class="fa fa-chevron-right"></i>
                                        </a>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-12 col-md-6 col-lg-4 product-banner-card">
                            <div class="card-display">
                                <div class="item-wrapper card-overlay">
                                    <div class="image-shine">
                                        <img src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2023/05/card3.png">

                                        <div class="section-2-left">

                                            <div class="section-2-name">Digital Camera</div>

                                            <div class="section-2-discount">35% Discount</div>

                                            <div class="card-button-bubble-container">
                                                <a href="#" class="cbb smoke">Shop Now<i class="fa fa-chevron-right"></i>
                                        </a>
                                            </div>

                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <section class="jcs-section-3 pb-default feature-products-home">
                <div class="jcs-container">


                    <div class="section-3-up filter-container">
                        <div id="feature-p-grid" class="jcs-row">
                            <div class="section-title-name col-md-4 col-lg-3">Feature Product</div>
                            <div class="jcs-row sec3feature col-md-8 col-lg-9 justify-content-between w-100">

                                <div class="">
                                    <div class="section-categories">
                                        <div class="item-wrapper">
                                            <nav class="owl-filter-bar">
                                                <a href="javascript:void(0)" class="item orange-text" data-owl-filter=".product_cat-all">All</a>


                                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-best-seller">Best Seller</a>

                                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-deal-of-day">Deal of day</a>

                                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-electronics">Electronics</a>

                                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-featured">Featured</a>

                                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-furniture">Furniture</a>

                                            </nav>
                                        </div>
                                    </div>
                                </div>
                                <div class="">
                                    <a href="#" class="cbb blue">View All <i class="fa fa-chevron-right"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="">
                        <ul class="products columns-4 owl-carousel owl-theme owl-loaded owl-drag">

                            <div class="owl-stage-outer">
                                <div class="owl-stage" style="transform: translate3d(-7420px, 0px, 0px); transition: all 0.25s ease 0s; width: 11307px;">
                                    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                                        <li class="product type-product post-89 status-publish last instock product_cat-all product_cat-furniture has-post-thumbnail sale shipping-taxable product-type-grouped retailsy_ct-ended">
                                            <div class="product">
                                                <div class="product-single">
                                                    <div class="product-img">
                                                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1.jpg 800w"
                                                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="89" data-nonce="dbead313f2"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="89" data-nonce="5274067ba5"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                                        </div>
                                                        </span>
                                                        </span>
                                                    </div> <a href="#" class="button quickview-trigger" data-product_id="89"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                                    <div class="product-action">
                                                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/" data-quantity="1" class="button wp-element-button product_type_grouped" data-product_id="89" data-product_sku="" aria-label="View products in the “Office Chair” group" rel="nofollow">View products</a>                                                        </div>
                                                </div>
                                                <div class="product-content-outer">
                                                    <div class="product-content">
                                                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/">Office Chair</a></h3>
                                                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                                                        <!--div class="price"-->


                                                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>210.00</span>
                                                        </span>
                                                        <!--/div-->

                                                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                                                    </div>
                                                </div>
                                            </div>
                                    </div>
                                    </li>
                                </div>
                                <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                                    <li class="product type-product post-43 status-publish first instock product_cat-all has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
                                        <div class="product">
                                            <div class="product-single">
                                                <div class="product-img">
                                                    <a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                                        <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                                        <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1.jpg 800w"
                                                            sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="43" data-nonce="7a8cbe0189"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                                    <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="43" data-nonce="a42f8fa9a3"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                                    </div>
                                                    </span>
                                                    </span>
                                                </div> <a href="#" class="button quickview-trigger" data-product_id="43"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                                <div class="product-action">
                                                    <a href="?add-to-cart=43" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="43" data-product_sku="STO123RELY" aria-label="Add “Mobile Phone” to your basket" rel="nofollow">Add to basket</a>                                                    </div>
                                            </div>
                                            <div class="product-content-outer">
                                                <div class="product-content">
                                                    <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/">Mobile Phone</a></h3>
                                                    <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                                                    <!--div class="price"-->


                                                    <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span>
                                                    </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>285.00</span></ins></span>
                                                    <div class="retailsy-stocks">
                                                        <div class="remaining-stock"> <span class="stock-count">34</span> left in stock </div>
                                                        <div class="barline">
                                                            <div class="stock-countbar" data-percentnumber="34" style="width: 34%;"></div>
                                                        </div>
                                                    </div>
                                                    <!--/div-->

                                                    <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                                                </div>
                                            </div>
                                        </div>
                                </div>
                                </li>
                            </div>
                            <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                                <li class="product type-product post-39 status-publish instock product_cat-best-seller product_cat-featured product_cat-latest product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
                                    <div class="product">
                                        <div class="product-single">
                                            <div class="product-img">
                                                <a href="https://preview.sellerthemes.com/pro/retailsy/product/hat/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                                    <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                                    <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1.jpg 800w"
                                                        sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="39" data-nonce="1569520402"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                                <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="39" data-nonce="7e3037ac28"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                                </div>
                                                </span>
                                                </span>
                                            </div> <a href="#" class="button quickview-trigger" data-product_id="39"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                            <div class="product-action">
                                                <a href="?add-to-cart=39" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="39" data-product_sku="" aria-label="Add “Hat” to your basket" rel="nofollow">Add to basket</a>                                                </div>
                                        </div>
                                        <div class="product-content-outer">
                                            <div class="product-content">
                                                <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/hat/">Hat</a></h3>
                                                <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                                                <!--div class="price"-->


                                                <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>39.00</span>
                                                </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>30.00</span></ins></span>
                                                <div class="retailsy-stocks">
                                                    <div class="remaining-stock"> <span class="stock-count">6</span> left in stock </div>
                                                    <div class="barline">
                                                        <div class="stock-countbar" data-percentnumber="6" style="width: 6%;"></div>
                                                    </div>
                                                </div>
                                                <!--/div-->

                                                <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                                            </div>
                                        </div>
                                    </div>
                            </div>
                            </li>
                    </div>
                    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                        <li class="product type-product post-36 status-publish last outofstock product_cat-best-seller product_cat-featured product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-variable has-default-attributes retailsy_ct-ended">
                            <div class="product">
                                <div class="product-single">
                                    <div class="product-img">
                                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1.jpg 800w"
                                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="36" data-nonce="c0f5ff0c24"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="36" data-nonce="53f1fbd80f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                        </div>
                                        </span>
                                        </span>
                                    </div> <a href="#" class="button quickview-trigger" data-product_id="36"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                    <div class="product-action">
                                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" data-quantity="1" class="button wp-element-button product_type_variable" data-product_id="36" data-product_sku="" aria-label="Select options for “Western Wear”" rel="nofollow">Select options</a>                                        </div>
                                </div>
                                <div class="product-content-outer">
                                    <div class="product-content">
                                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/">Western Wear</a></h3>
                                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                                        <!--div class="price"-->

                                        <div class="star-rating" role="img" aria-label="Rated 5.00 out of 5"><span style="width:100%">Rated <strong class="rating">5.00</strong> out of 5</span></div>
                                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span>
                                        </span>
                                        <!--/div-->

                                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                                    </div>
                                </div>
                            </div>
                    </div>
                    </li>
                </div>
                <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                    <li class="product type-product post-34 status-publish first instock product_cat-all product_cat-featured product_cat-latest product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
                        <div class="product">
                            <div class="product-single">
                                <div class="product-img">
                                    <a href="https://preview.sellerthemes.com/pro/retailsy/product/house-security/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                        <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                        <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1.jpg 800w"
                                            sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="34" data-nonce="c2e1fd12db"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                    <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="34" data-nonce="f7c011024b"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                    </div>
                                    </span>
                                    </span>
                                </div> <a href="#" class="button quickview-trigger" data-product_id="34"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                <div class="product-action">
                                    <a href="?add-to-cart=34" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="34" data-product_sku="" aria-label="Add “House Security” to your basket" rel="nofollow">Add to basket</a>                                    </div>
                            </div>
                            <div class="product-content-outer">
                                <div class="product-content">
                                    <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/house-security/">House Security</a></h3>
                                    <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                                    <!--div class="price"-->


                                    <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>390.00</span>
                                    </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span></ins></span>
                                    <!--/div-->

                                    <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                                </div>
                            </div>
                        </div>
                </div>
                </li>
        </div>
        <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
            <li class="product type-product post-32 status-publish instock product_cat-deal-of-day has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
                <div class="product">
                    <div class="product-single">
                        <div class="product-img">
                            <a href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1.jpg 800w"
                                    sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="32" data-nonce="88e82bb3a8"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                            <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="32" data-nonce="cc234ab446"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                            </div>
                            </span>
                            </span>
                        </div> <a href="#" class="button quickview-trigger" data-product_id="32"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                        <div class="product-action">
                            <a href="?add-to-cart=32" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="32" data-product_sku="" aria-label="Add “Airpods pro” to your basket" rel="nofollow">Add to basket</a>                            </div>
                    </div>
                    <div class="product-content-outer">
                        <div class="product-content">
                            <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/">Airpods pro</a></h3>
                            <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                            <!--div class="price"-->


                            <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>249.00</span>
                            </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                            <!--/div-->

                            <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                        </div>
                    </div>
                </div>
        </div>
        </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-28 status-publish last instock product_cat-deal-of-day product_tag-rockwell has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="28" data-nonce="d94c4a1b09"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="28" data-nonce="8eba777c4a"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="28"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=28" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="28" data-product_sku="" aria-label="Add “Wireless Speaker” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/">Wireless Speaker</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>124.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>100.00</span></ins></span>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-22 status-publish first instock product_cat-all product_cat-best-seller product_cat-featured product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="22" data-nonce="65a4754616"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="22" data-nonce="bf421ba0d5"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="22"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=22" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="22" data-product_sku="STD1001" aria-label="Add “Shirt” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/">Shirt</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">15</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="15" style="width: 15%;"></div>
                            </div>
                        </div>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-762 status-publish first instock product_cat-electronics product_cat-smartphone has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-300x300.png" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" fetchpriority="high" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-300x300.png 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-100x100.png 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-150x150.png 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75.png 367w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="762" data-nonce="4280db5efb"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="762" data-nonce="e81081c4fb"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="762"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=762" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="762" data-product_sku="" aria-label="Add “360 Degree View” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/">360 Degree View</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-690 status-publish instock product_cat-featured product_tag-lifestyle has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/analog-watch/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="690" data-nonce="ce13c56b28"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="690" data-nonce="8f90309a57"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="690"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=690" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="690" data-product_sku="STD1002" aria-label="Add “Analog Watch” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/analog-watch/">Analog Watch</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">5</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="5" style="width: 5%;"></div>
                            </div>
                        </div>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-122 status-publish last instock product_cat-featured product_tag-communication has-post-thumbnail sale shipping-taxable purchasable product-type-variable retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="122" data-nonce="4427458ad9"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="122" data-nonce="6b85efebcf"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="122"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" data-quantity="1" class="button wp-element-button product_type_variable add_to_cart_button" data-product_id="122" data-product_sku="" aria-label="Select options for “i Phone”" rel="nofollow">Select options</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/">i Phone</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>210.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>230.00</span>
                        </span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock bpss-remaining"> <span class="stock-count">12</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="12" style="width: 12%;"></div>
                            </div>
                        </div>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-118 status-publish first outofstock product_cat-featured product_tag-shooting has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="118" data-nonce="22ef2fb76b"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="118" data-nonce="c52854da81"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="118"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="118" data-product_sku="" aria-label="Read more about “Camera”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/">Camera</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>190.00</span></ins></span>
                        <div class="remaining-out-stock"> Out of stock</div>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-113 status-publish instock product_cat-featured product_tag-sound has-post-thumbnail shipping-taxable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link"><img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="113" data-nonce="6d9f63c057"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="113" data-nonce="4415d1429f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="113"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="113" data-product_sku="" aria-label="Read more about “Headphone”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/">Headphone</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">13</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="13" style="width: 13%;"></div>
                            </div>
                        </div>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-97 status-publish last outofstock product_cat-deal-of-day product_tag-communication product_tag-mobile has-post-thumbnail sale sold-individually shipping-taxable purchasable product-type-variable retailsy_ct-active retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="97" data-nonce="41e94f8a1d"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="97" data-nonce="c2cc49395f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="97"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" data-quantity="1" class="button wp-element-button product_type_variable" data-product_id="97" data-product_sku="" aria-label="Select options for “i Phone”" rel="nofollow">Select options</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/">i Phone</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>380.00</span>
                        </span>
                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-95 status-publish first instock product_cat-deal-of-day product_tag-home has-post-thumbnail shipping-taxable product-type-simple retailsy_ct-active retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link"><img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="95" data-nonce="af1acaa470"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="95" data-nonce="797fc02891"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="95"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="95" data-product_sku="Hot" aria-label="Read more about “Macbook Pro”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/">Macbook Pro</a></h3>
                        <!--div class="easy-stocks">
                        <div class="remaining-stock"> <span class="stock-count">600</span> left
                            in
                            stock
                        </div>
                        <div class="barline">
                            <div class="stock-countbar" data-percentnumber="60"
                                style="width: 60%;"></div>
                        </div>
                    </div-->

                        <!--div class="price"-->


                        <!--/div-->

                        <!--div class="pro-rating">
                        <i class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i><i class="fa fa-star"></i><i
                            class="fa fa-star"></i>
                    </div-->
                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-93 status-publish instock product_cat-deal-of-day product_tag-decoration product_tag-light has-post-thumbnail sale shipping-taxable product-type-grouped retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="93" data-nonce="63a61c173a"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="93" data-nonce="b09d50e512"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="93"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/" data-quantity="1" class="button wp-element-button product_type_grouped" data-product_id="93" data-product_sku="" aria-label="View products in the “Smart Watch” group" rel="nofollow">View products</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/">Smart Watch</a></h3>


                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>100.00</span>
                        </span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-89 status-publish last instock product_cat-all product_cat-furniture has-post-thumbnail sale shipping-taxable product-type-grouped retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="89" data-nonce="dbead313f2"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="89" data-nonce="5274067ba5"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="89"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/" data-quantity="1" class="button wp-element-button product_type_grouped" data-product_id="89" data-product_sku="" aria-label="View products in the “Office Chair” group" rel="nofollow">View products</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/office-chair/">Office Chair</a></h3>



                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>210.00</span>
                        </span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-43 status-publish first instock product_cat-all has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="43" data-nonce="7a8cbe0189"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="43" data-nonce="a42f8fa9a3"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="43"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=43" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="43" data-product_sku="STO123RELY" aria-label="Add “Mobile Phone” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/">Mobile Phone</a></h3>




                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>285.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">34</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="34" style="width: 34%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-39 status-publish instock product_cat-best-seller product_cat-featured product_cat-latest product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/hat/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="39" data-nonce="1569520402"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="39" data-nonce="7e3037ac28"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="39"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=39" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="39" data-product_sku="" aria-label="Add “Hat” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/hat/">Hat</a></h3>


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>39.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>30.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">6</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="6" style="width: 6%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-36 status-publish last outofstock product_cat-best-seller product_cat-featured product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-variable has-default-attributes retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-2-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="36" data-nonce="c0f5ff0c24"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="36" data-nonce="53f1fbd80f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="36"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/" data-quantity="1" class="button wp-element-button product_type_variable" data-product_id="36" data-product_sku="" aria-label="Select options for “Western Wear”" rel="nofollow">Select options</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/western-wear/">Western Wear</a></h3>


                        <div class="star-rating" role="img" aria-label="Rated 5.00 out of 5"><span style="width:100%">Rated <strong class="rating">5.00</strong> out of 5</span></div>
                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span>
                        </span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-34 status-publish first instock product_cat-all product_cat-featured product_cat-latest product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/house-security/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/10-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="34" data-nonce="c2e1fd12db"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="34" data-nonce="f7c011024b"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="34"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=34" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="34" data-product_sku="" aria-label="Add “House Security” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/house-security/">House Security</a></h3>


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>390.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span></ins></span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item active" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-32 status-publish instock product_cat-deal-of-day has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-2-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="32" data-nonce="88e82bb3a8"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="32" data-nonce="cc234ab446"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="32"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=32" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="32" data-product_sku="" aria-label="Add “Airpods pro” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/airpods-pro/">Airpods pro</a></h3>



                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>249.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item active" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-28 status-publish last instock product_cat-deal-of-day product_tag-rockwell has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/5-1-1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="28" data-nonce="d94c4a1b09"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="28" data-nonce="8eba777c4a"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="28"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=28" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="28" data-product_sku="" aria-label="Add “Wireless Speaker” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/wireless-speaker/">Wireless Speaker</a></h3>



                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>124.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>100.00</span></ins></span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-22 status-publish first instock product_cat-all product_cat-best-seller product_cat-featured product_cat-offers has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-2.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="22" data-nonce="65a4754616"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="22" data-nonce="bf421ba0d5"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="22"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=22" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="22" data-product_sku="STD1001" aria-label="Add “Shirt” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/shirt/">Shirt</a></h3>


                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">15</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="15" style="width: 15%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-762 status-publish first instock product_cat-electronics product_cat-smartphone has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-300x300.png" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" fetchpriority="high" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-300x300.png 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-100x100.png 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75-150x150.png 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/03/75.png 367w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="762" data-nonce="4280db5efb"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="762" data-nonce="e81081c4fb"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="762"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=762" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="762" data-product_sku="" aria-label="Add “360 Degree View” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/360-degree-view/">360 Degree View</a></h3>



                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-690 status-publish instock product_cat-featured product_tag-lifestyle has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/analog-watch/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/02/watch1.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="690" data-nonce="ce13c56b28"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="690" data-nonce="8f90309a57"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="690"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="?add-to-cart=690" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="690" data-product_sku="STD1002" aria-label="Add “Analog Watch” to your basket" rel="nofollow">Add to basket</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/analog-watch/">Analog Watch</a></h3>



                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>200.00</span></ins></span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">5</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="5" style="width: 5%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-122 status-publish last instock product_cat-featured product_tag-communication has-post-thumbnail sale shipping-taxable purchasable product-type-variable retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/9.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="122" data-nonce="4427458ad9"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="122" data-nonce="6b85efebcf"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="122"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/" data-quantity="1" class="button wp-element-button product_type_variable add_to_cart_button" data-product_id="122" data-product_sku="" aria-label="Select options for “i Phone”" rel="nofollow">Select options</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone/">i Phone</a></h3>



                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>210.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>230.00</span>
                        </span>
                        <div class="retailsy-stocks">
                            <div class="remaining-stock bpss-remaining"> <span class="stock-count">12</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="12" style="width: 12%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-118 status-publish first outofstock product_cat-featured product_tag-shooting has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/12.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="118" data-nonce="22ef2fb76b"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="118" data-nonce="c52854da81"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="118"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="118" data-product_sku="" aria-label="Read more about “Camera”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/camera/">Camera</a></h3>



                        <span class="price"><del aria-hidden="true"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>250.00</span>
                        </del> <ins><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>190.00</span></ins></span>
                        <div class="remaining-out-stock"> Out of stock</div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-113 status-publish instock product_cat-featured product_tag-sound has-post-thumbnail shipping-taxable product-type-simple retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link"><img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/16.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="113" data-nonce="6d9f63c057"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="113" data-nonce="4415d1429f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="113"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="113" data-product_sku="" aria-label="Read more about “Headphone”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/headphone/">Headphone</a></h3>



                        <div class="retailsy-stocks">
                            <div class="remaining-stock"> <span class="stock-count">13</span> left in stock </div>
                            <div class="barline">
                                <div class="stock-countbar" data-percentnumber="13" style="width: 13%;"></div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-97 status-publish last outofstock product_cat-deal-of-day product_tag-communication product_tag-mobile has-post-thumbnail sale sold-individually shipping-taxable purchasable product-type-variable retailsy_ct-active retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon"><span class="tag-line">Out of Stock</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/3-5.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="97" data-nonce="41e94f8a1d"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="97" data-nonce="c2cc49395f"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="97"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/" data-quantity="1" class="button wp-element-button product_type_variable" data-product_id="97" data-product_sku="" aria-label="Select options for “i Phone”" rel="nofollow">Select options</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/i-phone-2/">i Phone</a></h3>



                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>300.00</span> – <span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>380.00</span>
                        </span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-95 status-publish first instock product_cat-deal-of-day product_tag-home has-post-thumbnail shipping-taxable product-type-simple retailsy_ct-active retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link"><img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/2-2.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="95" data-nonce="af1acaa470"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="95" data-nonce="797fc02891"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="95"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/" data-quantity="1" class="button wp-element-button product_type_simple" data-product_id="95" data-product_sku="Hot" aria-label="Read more about “Macbook Pro”" rel="nofollow">Read more</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/macbook-pro/">Macbook Pro</a></h3>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
        <li class="product type-product post-93 status-publish instock product_cat-deal-of-day product_tag-decoration product_tag-light has-post-thumbnail sale shipping-taxable product-type-grouped retailsy_ct-ended">
            <div class="product">
                <div class="product-single">
                    <div class="product-img">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/20.jpg 800w"
                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="93" data-nonce="63a61c173a"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="93" data-nonce="b09d50e512"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                        </div>
                        </span>
                        </span>
                    </div> <a href="#" class="button quickview-trigger" data-product_id="93"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                    <div class="product-action">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/" data-quantity="1" class="button wp-element-button product_type_grouped" data-product_id="93" data-product_sku="" aria-label="View products in the “Smart Watch” group" rel="nofollow">View products</a>                        </div>
                </div>
                <div class="product-content-outer">
                    <div class="product-content">
                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/smart-watch/">Smart Watch</a></h3>



                        <span class="price"><span class="woocommerce-Price-amount amount"><span class="woocommerce-Price-currencySymbol">$</span>100.00</span>
                        </span>

                    </div>
                </div>
            </div>
    </div>
    </li>
    </div>
    </div>
    </div>
    <div class="owl-nav"><button type="button" role="presentation" class="owl-prev"><span aria-label="Previous">‹</span></button><button type="button" role="presentation" class="owl-next"><span aria-label="Next">›</span></button></div>
    <div class="owl-dots disabled"></div>
    </ul>
    </div>

    </div>
    </section>

    <section class="jcs-section-4 pb-default electric-products-home">
        <div class="jcs-container">
            <div class="section-grid-home">
                <div class="section-left-home section-left">
                    <div class="section-title-name title title-4">
                        Electric Product </div>
                    <div class="items-names owl-filter-bar-4">
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product-category/all/" class="item">All</a>
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product-category/furniture/" class="item">Furniture</a>
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product-category/latest/" class="item">Latest</a>
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product-category/offers/" class="item">Offers</a>
                        <a href="https://preview.sellerthemes.com/pro/retailsy/product-category/product/" class="item">Product</a>

                    </div>
                </div>
                <div class="section-right-home section-right">
                    <div class="jcs-row">
                        <div class="section-categories">
                            <nav class="owl-filter-bar-4">
                                <a href="javascript:void(0)" class="item orange-text" data-owl-filter=".product_cat-all">All</a>


                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-furniture">Furniture</a>

                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-latest">Latest</a>

                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-offers">Offers</a>

                                <a href="javascript:void(0)" class="item" data-owl-filter=".product_cat-product">Product</a>

                            </nav>
                        </div>
                        <div class="easy_ct-countdown easy_ct-style-02  easy_ct-running" data-style="02" data-timer="2023-12-29 12:14:00" data-ended="">
                            <div class="easy_ct-timer">
                                <span><span id="days1">80</span><span>D</span></span>
                                <span><span id="hours1">20</span><span>H</span></span>
                                <span><span id="minutes1">44</span><span>M</span></span>
                                <span><span id="seconds1">47</span><span>S</span></span>
                            </div>
                        </div>
                        <a href="#" class="cbb blue">View All <i class="fa fa-chevron-right"></i></a>
                    </div>


                    <div class="">
                        <ul class="products columns-4 owl-carousel owl-theme owl-loaded owl-drag">
                            <div class="owl-stage-outer">
                                <div class="owl-stage" style="transform: translate3d(-3533px, 0px, 0px); transition: all 0.25s ease 0s; width: 7067px;">
                                    <div class="owl-item cloned" style="width: 323.334px; margin-right: 30px;">
                                        <li class="product type-product post-43 status-publish first instock product_cat-all has-post-thumbnail sale shipping-taxable purchasable product-type-simple retailsy_ct-ended">
                                            <div class="product">
                                                <div class="product-single">
                                                    <div class="product-img">
                                                        <a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/" class="woocommerce-LoopProduct-link woocommerce-loop-product__link">
                                                            <div class="sale-ribbon ttt"><span class="tag-line">Sale</span></div>
                                                            <img width="300" height="300" src="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg" class="attachment-woocommerce_thumbnail size-woocommerce_thumbnail" alt="" decoding="async" srcset="https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-300x300.jpg 300w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-100x100.jpg 100w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-600x600.jpg 600w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-150x150.jpg 150w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1-768x768.jpg 768w, https://preview.sellerthemes.com/pro/retailsy/wp-content/uploads/2022/01/1-1-1.jpg 800w"
                                                                sizes="(max-width: 300px) 100vw, 300px"> </a><a class="button compare-btn compare" data-id="43" data-nonce="7a8cbe0189"><span class="retailsy_woocompare_product_actions_tip"><span class="text"></span></span></a>
                                                        <div class="yith-wcwl-add-to-wishlist retailsy-woowishlist-button" data-id="43" data-nonce="a42f8fa9a3"><span class="retailsy_woowishlist_product_actions_tip"><span class="text"><div class="yith-wcwl-add-button"><a href="#" class="add_to_wishlist single_add_to_wishlist" data-product-type="simple" data-title="Add to wishlist" rel="nofollow">                                                    <i class="yith-wcwl-icon fa fa-heart"></i><i class="yith-wcwl-icon fa fa-heart"></i><span>Add to wishlist</span></a>
                                                        </div>
                                                        </span>
                                                        </span>
                                                    </div> <a href="#" class="button quickview-trigger" data-product_id="43"><i class="fa fa-eye"></i><i class="fa fa-eye"></i></a>
                                                    <div class="product-action">
                                                        <a href="?add-to-cart=43" data-quantity="1" class="button wp-element-button product_type_simple add_to_cart_button ajax_add_to_cart" data-product_id="43" data-product_sku="STO123RELY" aria-label="Add “Mobile Phone” to your basket" rel="nofollow">Add to basket</a>                                                        </div>
                                                </div>
                                                <div class="product-content-outer">
                                                    <div class="product-content">
                                                        <h3><a href="https://preview.sellerthemes.com/pro/retailsy/product/mobile-phone/">Mobile Phone</a></h3>20

