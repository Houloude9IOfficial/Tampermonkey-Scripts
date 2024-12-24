// ==UserScript==
// @name         Remove Ads
// @namespace    http://tampermonkey.net/
// @version      2024-12-24
// @description  Remove ads (Adblock installation recommended)
// @author       HTDevs
// @match        https://control.bot-hosting.net/*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=bot-hosting.net
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    window.addEventListener('load', function() {
        const panelAnchor = document.getElementById('panel-anchor');
        if (panelAnchor) {
            panelAnchor.remove();
        }
    });
})();
