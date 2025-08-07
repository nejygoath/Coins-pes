<!DOCTYPE html>
<html>
<head>

  <style>
        .header_blue {
            background: #1565c0;
            padding: 80px 0 20px;
            color: #fff;
            font-size: 48px;
            font-weight: 300;
            margin-bottom: 40px
        }

        .header_text {
            margin-left: auto;
            margin-right: auto;
            width: 80%
        }

        body {
            margin: 0;
            font-family: Roboto, sans-serif;
            color: #444
        }

        .unlockBtn:hover {
            box-shadow: 0 3px 6px rgba(0, 0, 0, .16), 0 3px 6px rgba(0, 0, 0, .23)
        }

        .unlockBtn {
            background: #2196f3;
            border: none;
            border-radius: 2px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, .12), 0 1px 2px rgba(0, 0, 0, .24);
            min-height: 31px;
            min-width: 70px;
            padding: 2px 16px;
            text-align: center;
            text-shadow: none;
            text-transform: uppercase;
            -webkit-transition: all 280ms ease;
            transition: all 280ms ease;
            box-sizing: border-box;
            cursor: pointer;
            -webkit-appearance: none;
            display: inline-block;
            vertical-align: middle;
            font: 500 14px/31px Roboto, sans-serif !important;
            outline: 0 !important;
            color: #fff
        }

        .content-container {
            width: 80%;
            margin: 0 auto
        }

        @font-face {
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            src: local('Roboto Light'), local(Roboto-Light), url(//fonts.gstatic.com/s/roboto/v15/Pru33qjShpZSmG3z6VYwnRJtnKITppOI_IvcXXDNrsc.woff2) format("woff2");
            unicode-range: U+0100-024F, U+1E00-1EFF, U+20A0-20AB, U+20AD-20CF, U+2C60-2C7F, U+A720-A7FF
        }

        @font-face {
            font-family: Roboto;
            font-style: normal;
            font-weight: 300;
            src: local('Roboto Light'), local(Roboto-Light), url(//fonts.gstatic.com/s/roboto/v15/Hgo13k-tfSpn0qi1SFdUfVtXRa8TVwTICgirnJhmVJw.woff2) format("woff2");
            unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2212, U+2215, U+E0FF, U+EFFD, U+F000
        }

        @font-face {
            font-family: Roboto;
            font-style: normal;
            font-weight: 500;
            src: local('Roboto Medium'), local(Roboto-Medium), url(//fonts.gstatic.com/s/roboto/v15/oOeFwZNlrTefzLYmlVV1UBJtnKITppOI_IvcXXDNrsc.woff2) format("woff2");
            unicode-range: U+0100-024F, U+1E00-1EFF, U+20A0-20AB, U+20AD-20CF, U+2C60-2C7F, U+A720-A7FF
        }

        @font-face {
            font-family: Roboto;
            font-style: normal;
            font-weight: 500;
            src: local('Roboto Medium'), local(Roboto-Medium), url(//fonts.gstatic.com/s/roboto/v15/RxZJdnzeo3R5zSexge8UUVtXRa8TVwTICgirnJhmVJw.woff2) format("woff2");
            unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2212, U+2215, U+E0FF, U+EFFD, U+F000
        }

        body {
            font-family: 'Alegreya Sans', sans-serif;
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center center;
            min-height: 100vh;
            background-attachment: fixed;
            background-image: url(https://i.postimg.cc/XJz9vr8q/IMG-20250418-211840.jpg);
            animation: myAnim 15s ease-in-out 0s normal forwards
        }

        @keyframes myAnim {
            0% {
                background-position: 0 50%
            }

            50% {
                background-position: 100% 50%
            }

            100% {
                background-position: 50% 0
            }
        }

        .lastStep-text {
            color: #fff;
            font-size: 26px;
            margin-top: 10px;
            text-shadow: 5px;
            font-weight: 900;
            letter-spacing: 4px;
            animation: bounceIn .5s ease-in;
            font-family: 'Alegreya Sans', sans-serif;
            text-shadow: #000 0 0 3px, #000 0 0 3px, #fff 0 0 3px, #000 0 0 3px, #000 0 0 3px, #fff 0 0 3px
        }

        .ads {
            position: absolute;
            width: 100%;
            background-color: red;
            top: 770px;
            left: 0
        }

        .bgani {
            position: absolute;
            animation: bgani1 2s ease-in infinite
        }

        @keyframes bgani1 {
            0% {
                left: 1px;
                transform: scale(.5);
                opacity: .1
            }

            25% {
                opacity: .1;
                transform: rotate(10deg)
            }

            50% {
                opacity: .1;
                transform: rotate(50deg)
            }

            75% {
                opacity: .1;
                transform: rotate(200deg)
            }

            100% {
                left: 100%;
                transform: scale(10);
                opacity: .1
            }
        }

        .bgani2 {
            position: absolute;
            animation: bgani2 2s ease-in infinite
        }

        @keyframes bgani2 {
            0% {
                top: 100px;
                left: 1px;
                transform: scale(1.5);
                opacity: .1
            }

            25% {
                opacity: .01;
                transform: rotate(10deg)
            }

            50% {
                opacity: .01;
                transform: rotate(50deg)
            }

            75% {
                opacity: .01;
                transform: rotate(200deg)
            }

            100% {
                top: -20px;
                left: 50%;
                transform: scale(10);
                opacity: .1
            }
        }

        .bgani3 {
            position: absolute;
            animation: bgani3 2s ease-in infinite
        }

        @keyframes bgani3 {
            0% {
                top: -20px;
                left: 70%;
                transform: scale(.5);
                opacity: .1
            }

            25% {
                opacity: .1;
                transform: rotate(10deg)
            }

            50% {
                opacity: .1;
                transform: rotate(50deg)
            }

            75% {
                opacity: .1;
                transform: rotate(200deg)
            }

            100% {
                top: 100px;
                left: 1%;
                transform: scale(5);
                opacity: .1
            }
        }

        .logo {
            position: relative;
            margin-top: 200px;
            width: 300px;
            margin-bottom: 35px;
            z-index: 2;
            animation: myAnim1 2s ease-in-out 0s infinite normal forwards
        }

        @keyframes myAnim1 {
            0% {
                transform: translate(0)
            }

            20% {
                transform: translate(2px, -2px)
            }

            40% {
                transform: translate(2px, 2px)
            }

            60% {
                transform: translate(-2px, 2px)
            }

            80% {
                transform: translate(-2px, -2px)
            }

            100% {
                transform: translate(0)
            }
        }

        @keyframes pulse2 {
            0% {
                transform: scale(1)
            }

            25% {
                transform: scale(1)
            }

            75% {
                transform: scale(.9)
            }
        }

        @keyframes bounceIn {
            0% {
                opacity: 0;
                transform: scale(.3) translate3d(0, 0, 0)
            }

            50% {
                opacity: .9;
                transform: scale(1.1)
            }

            80% {
                opacity: 1;
                transform: scale(.89)
            }

            100% {
                opacity: 1;
                transform: scale(1) translate3d(0, 0, 0)
            }
        }

        .text-lastStep {
            max-width: 500px;
            color: #fff;
            font-family: 'Alegreya Sans', sans-serif;
            font-weight: 600;
            text-shadow: 2px 2px rgba(0, 0, 0, .45)
        }

        :root {
            --background: radial-gradient(#222222, #222222);
            --backgroundUsername: linear-gradient(to left top, #111111, #111111);
            --platform: linear-gradient(to left top, #111111, #111111);
            --SelectedPlatform: linear-gradient(to left top, #08a1fe, #1a69b6);
            --waitingtext: white;
            --UserFoundText: white;
            --LogoFound: rgba(255, 255, 255, 0.1);
            --borderbuttons: rgba(255, 255, 255, 0.1);
            --selectedborderbuttons: white;
            --gemsbuttons1: linear-gradient(to left top, #111111, #111111);
            --buttons: linear-gradient(to left top, #08a1fe, #1a69b6);
            --buttonsHover: linear-gradient(to left top, #20a8fa, #1e75c9);
            --boxshadow1: rgba(255, 255, 255, 0.1);
            --boxshadow2: rgba(255, 255, 255, 0.1);
            --boxshadow3: rgba(255, 255, 255, 0.1);
            --boxshadow4: rgba(255, 255, 255, 0.1);
            --boxshadow5: rgba(255, 255, 255, 0.1)
        }

        .main {
            background: var(--background);
            width: 650px;
            height: 450px;
            position: relative;
            margin-top: -25px;
            padding: 10px;
            -webkit-background-clip: padding-box;
            background-clip: padding-box;
            z-index: 1;
            border: rgba(0, 0, 0, .75) solid 1px;
            border-radius: 20px;
            box-shadow: 15px 15px 45px 5px rgba(0, 0, 0, .75);
            background: #154351
        }

        .step {
            width: 60px;
            height: 60px;
            background-color: transparent;
            border-radius: 50%;
            margin-top: -40px
        }

        .step1 {
            width: 450px;
            height: 450px
        }

        .step1-text {
            color: #f5f5f5;
            margin-top: 10px;
            text-shadow: 2px 2px rgba(0, 0, 0, .75);
            font-family: 'Alegreya Sans', sans-serif;
            font-size: 20px;
            font-weight: 900;
            animation: bounceIn .5s ease-in
        }

        .u-i {
            position: absolute;
            left: 50%;
            margin-left: -230px;
            outline: 0;
            -moz-appearance: none;
            -webkit-appearance: none;
            background: rgba(0, 0, 0, .75);
            border: none;
            width: 355x;
            height: 90px;
            padding: 0 15px 0 70px;
            color: #fff;
            font-size: 28px;
            border-radius: 10px;
            font-weight: 700;
            animation: bounceIn .5s ease-in;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
        }

        .username-icon {
            left: 10px;
            top: 25px;
            position: absolute;
            width: 35px;
            z-index: 2;
            animation: bounceIn .5s ease-in;
            filter: invert(60%)
        }

        .inputbox {
            position: relative;
            width: 450px;
            height: 100px
        }

        .selectedPlatform {
            width: 100px;
            height: 60px;
            background: var(--SelectedPlatform);
            display: inline-table;
            margin-top: 15px;
            border-radius: 10px;
            padding-top: 25px;
            border-style: solid;
            border-width: 1px;
            border-color: rgba(255, 255, 255, .1);
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45);
            animation: myAnim2 .7s ease-in-out 0s 1 normal forwards
        }

        @keyframes myAnim2 {
            0% {
                transform: scale3d(1, 1, 1)
            }

            30% {
                transform: scale3d(.75, 1.25, 1)
            }

            40% {
                transform: scale3d(1.25, .75, 1)
            }

            50% {
                transform: scale3d(.85, 1.15, 1)
            }

            65% {
                transform: scale3d(1.05, .95, 1)
            }

            75% {
                transform: scale3d(.95, 1.05, 1)
            }

            100% {
                transform: scale3d(1, 1, 1)
            }
        }

        .platform {
            width: 100px;
            height: 60px;
            background: rgba(0, 0, 0, .75);
            display: inline-table;
            margin-top: 20px;
            border-radius: 10px;
            padding-top: 25px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
        }

        .platform:hover {
            cursor: pointer;
            background-color: rgba(0, 0, 0, .4);
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .4);
            border-radius: 10px
        }

        @keyframes pulse {
            25% {
                transform: scale(.9)
            }

            75% {
                transform: scale(1)
            }
        }

        .grid-container {
            margin-left: 15px;
            display: grid;
            grid-template-columns: auto auto auto auto
        }

        .bnt {
            width: 300px;
            height: 50px;
            background: var(--buttons);
            font-family: Arial, sans-serif;
            font-size: 35px;
            font-weight: 900;
            color: #171717;
            padding: 5px;
            margin-top: 50px;
            border-radius: 10px;
            border-color: var(--borderbuttons);
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
        }

        .bnt:hover {
            cursor: pointer;
            background: var(--buttonsHover);
            animation: myAnim3 1.5s ease-in-out 0s infinite normal forwards;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .25)
        }

        @keyframes myAnim3 {

            0%,
            100% {
                transform: rotate(0);
                transform-origin: 50% 100%
            }

            10% {
                transform: rotate(2deg)
            }

            20%,
            40%,
            60% {
                transform: rotate(-4deg)
            }

            30%,
            50%,
            70% {
                transform: rotate(4deg)
            }

            80% {
                transform: rotate(-2deg)
            }

            90% {
                transform: rotate(2deg)
            }
        }

        @keyframes pulse {
            25% {
                transform: scale(.9)
            }

            75% {
                transform: scale(1)
            }
        }

        .step2 {
            margin-top: 50px;
            width: 300px;
            height: 200px;
            animation: pulse .5s ease-in infinite
        }

        @keyframes step2animation1 {
            25% {
                transform: rotate(-2deg)
            }

            75% {
                transform: rotate(2deg)
            }
        }

        .seaching-text {
            font-size: 26px;
            animation: pulse1 1s ease-in infinite;
            color: #fff
        }

        .userfound-text {
            font-size: 26px;
            color: #fff;
            font-weight: 700;
            text-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75);
            animation: pulse2 1s ease-in infinite
        }

        .searching-box {
            width: 280px;
            border-style: solid;
            border-width: 1px;
            border-radius: 10px;
            border-color: rgba(255, 255, 255, .1);
            color: #fff;
            font-size: 32px;
            padding: 10px;
            padding-top: 10px;
            padding-bottom: 10px;
            animation: pulse1 .5s ease-in infinite;
            animation: blinker .7s linear infinite
        }

        @keyframes blinker {
            50% {
                opacity: 0
            }
        }

        .searching-platform {
            width: 60px;
            height: 60px;
            background-color: var(--LogoFound);
            border-style: solid;
            border-width: 4px;
            border-radius: 10px;
            border-color: rgba(255, 255, 255, .1);
            margin-top: 30px;
            animation: pulse1 .5s ease-in infinite;
            animation: blinker .7s linear infinite
        }

        @keyframes pulse1 {
            25% {
                transform: scale(.98)
            }

            75% {
                transform: scale(1)
            }
        }

        .step3 {
            margin-top: 50px;
            width: 300px;
            height: 200px
        }

        .imgcheckok {
            width: 160px;
            animation: slit-in-diagonal-1 .45s ease-out both;
            filter: invert(20%)
        }

        @keyframes slit-in-diagonal-1 {
            0% {
                transform: translateZ(-800px) rotate3d(1, 1, 0, 90deg);
                animation-timing-function: ease-in;
                opacity: 0
            }

            54% {
                transform: translateZ(-160px) rotate3d(1, 1, 0, 87deg);
                animation-timing-function: ease-in-out;
                opacity: 1
            }

            100% {
                transform: translateZ(0) rotate3d(1, 1, 0, 0);
                animation-timing-function: ease-out
            }
        }

        .slide-in-blurred-bottom {
            animation: slide-in-blurred-bottom .6s cubic-bezier(.23, 1, .32, 1) both
        }

        @keyframes slide-in-blurred-bottom {
            0% {
                transform: translateY(1000px) scaleY(2.5) scaleX(.2);
                transform-origin: 50% 100%;
                filter: blur(40px);
                opacity: 0
            }

            100% {
                transform: translateY(0) scaleY(1) scaleX(1);
                transform-origin: 50% 50%;
                filter: blur(0);
                opacity: 1
            }
        }

        .gems-Amount {
            position: relative;
            width: 300px;
            height: 35px;
            padding: 5px;
            background: rgba(0, 0, 0, .75);
            border-radius: 10px;
            margin-top: 10px;
            border-color: var(--borderbuttons);
            color: #fff;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
        }

        .gems-Amount:hover {
            cursor: pointer;
            background: rgba(0, 0, 0, .4);
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .25)
        }

        .gems-Amount-Selected {
            position: relative;
            width: 300px;
            height: 35px;
            padding: 5px;
            background: var(--SelectedPlatform);
            border-radius: 10px;
            margin-top: 10px;
            border-width: 2px;
            border-style: solid;
            border-color: var(--selectedborderbuttons);
            animation: searchAnimation .5s linear;
            box-shadow: 0 0 5px var(--boxshadow1), 0 0 6px var(--boxshadow2), 0 0 7px var(--boxshadow3), 0 0 8px var(--boxshadow4), 0 0 9px var(--boxshadow5);
            color: #fff
        }

        .gemstext {
            font-size: 27px;
            font-weight: 900;
            position: relative;
            animation: flip-in-hor-top .5s ease-in;
            color: #fff
        }

        .gemstext1 {
            font-size: 24px;
            font-weight: 900
        }

        @keyframes flip-in-hor-top {
            0% {
                transform: rotateX(-80deg);
                opacity: 0
            }

            100% {
                transform: rotateX(0);
                opacity: 1
            }
        }

        @keyframes searchAnimation {
            0% {
                left: 0
            }

            25% {
                left: 5px
            }

            50% {
                left: -5px
            }

            75% {
                left: 5px
            }

            100% {
                left: 0
            }
        }

        .sake {
            position: relative
        }

        .bnt2 {
            width: 300px;
            height: 50px;
            background: var(--buttons);
            font-size: 35px;
            font-weight: 900;
            font-family: Arial, sans-serif;
            color: #171717;
            padding: 5px;
            margin-top: -110px;
            border-radius: 10px;
            border-color: var(--borderbuttons);
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
        }

        .bnt2:hover {
            cursor: pointer;
            animation: myAnim3 1.5s ease-in-out 0s infinite normal forwards;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .25);
            background: var(--buttonsHover)
        }

        .bnt3 {
            width: 300px;
            height: 50px;
            background: var(--buttons);
            font-family: Arial, sans-serif;
            font-size: 35px;
            font-weight: 900;
            color: #171717;
            padding: 5px;
            margin-top: 8px;
            border-radius: 10px;
            animation: pulsel 2s ease-in infinite;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
        }

        .bnt3:hover {
            cursor: pointer;
            animation: myAnim3 1.5s ease-in-out 0s infinite normal forwards;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .25);
            background: var(--buttonsHover)
        }

        .main3 {
            background: var(--background);
            width: 400px;
            height: 300px;
            position: relative;
            border-radius: 10px;
            margin-top: -25px;
            -webkit-background-clip: padding-box;
            background-clip: padding-box;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 15px 15px 45px 5px rgba(0, 0, 0, .75);
            background: #154351
        }

        .main5 {
            background: var(--background);
            width: 600px;
            height: 470px;
            position: relative;
            border-radius: 10px;
            border-style: solid;
            -webkit-background-clip: padding-box;
            background-clip: padding-box;
            margin-top: -25px;
            color: #fff;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 15px 15px 45px 5px rgba(0, 0, 0, .75);
            background: #154351
        }

        .lastStep-card {
            margin-top: 20px;
            width: 180px;
            height: 155px;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 25px 0 rgba(0, 0, 0, .75);
            background: #154351;
            border-radius: 10px;
            animation: pulsel 2s ease-in infinite;
            color: #fff
        }

        @keyframes pulsel {
            0% {
                transform: scale(1)
            }

            25% {
                transform: scale(.95)
            }

            50% {
                transform: scale(1)
            }

            75% {
                transform: scale(.95)
            }

            100% {
                transform: scale(1)
            }
        }

        .setting-icon {
            margin-top: 20px;
            animation: step2animation 3s linear infinite
        }

        @keyframes step2animation {
            0% {
                transform: rotate(0)
            }

            100% {
                transform: rotate(360deg)
            }
        }

        .sloading {
            animation: Asloading 2s linear infinite
        }

        @keyframes Asloading {
            0% {
                transform: rotate(0)
            }

            100% {
                transform: rotate(360deg)
            }
        }

        .pro-bg {
            margin-top: 10px;
            width: 250px;
            height: 15px;
            background-color: #ccc;
            border-radius: 5px;
            text-align: left;
            box-shadow: 5px 5px 25px 0 rgba(0, 0, 0, .75)
        }

        .pro-bar {
            margin-top: 10px;
            width: 0;
            height: 15px;
            background-color: rgba(0, 0, 0, .75);
            border-radius: 5px;
            box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
        }

        .probar40 {
            animation: prostep 1s linear;
            animation-fill-mode: forwards
        }

        @keyframes prostep {
            0% {
                width: 0
            }

            100% {
                width: 25%
            }
        }

        .probar60 {
            animation: prostep2 1s linear;
            animation-fill-mode: forwards
        }

        @keyframes prostep2 {
            0% {
                width: 25%
            }

            100% {
                width: 40%
            }
        }

        .probar40-75 {
            animation: prostep40-75 1s linear;
            animation-fill-mode: forwards
        }

        @keyframes prostep40-75 {
            0% {
                width: 40%
            }

            100% {
                width: 75%
            }
        }

        .probar75-90 {
            animation: prostep75-90 1s linear;
            animation-fill-mode: forwards
        }

        @keyframes prostep75-90 {
            0% {
                width: 75%
            }

            100% {
                width: 98%
            }
        }

        .main4 {
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            width: 200px;
            height: 150px;
            margin-top: -285px;
            position: relative;
            border-radius: 10px;
            border-style: solid;
            -webkit-background-clip: padding-box;
            background-clip: padding-box;
            border: rgba(0, 0, 0, .75) solid 1px;
            box-shadow: 5px 5px 25px 0 rgba(0, 0, 0, .75);
            background: #154351;
            animation: pulse 1s ease-in-out infinite
        }

        .gemsgen {
            width: 100px;
            background: linear-gradient(to left top, #08a1fe, #1a69b6);
            border-radius: 10px;
            padding-top: 2px;
            padding-bottom: 2px;
            font-size: 22px;
            font-weight: 900;
            color: #f5f5f5;
            margin-bottom: 5px;
            box-shadow: 3px 3px 15px 0 rgba(0, 0, 0, .75)
        }

        .gemsgenname {
            font-size: 22px;
            font-weight: 900;
            color: #f5f5f5;
            text-shadow: 2px 2px rgba(0, 0, 0, .75)
        }

        @media only screen and (max-width:680px) {
            .grid-container {
                display: grid;
                grid-template-columns: auto auto;
                margin-left: 35px
            }

            .platform:hover {
                border-radius: 10px
            }

            body {
                background-color: transparent;
                font-family: 'Alegreya Sans', sans-serif;
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center center;
                background-attachment: fixed
            }

            .main {
                background: var(--background);
                width: 350px;
                height: 480px;
                position: relative;
                margin-top: -25px;
                border-radius: 10px;
                -webkit-background-clip: padding-box;
                background-clip: padding-box;
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 15px 15px 45px 5px rgba(0, 0, 0, .75);
                background: #154351
            }

            .step1 {
                width: 300px;
                height: 350px
            }

            .step1-text {
                color: #f5f5f5;
                margin-top: 10px;
                text-shadow: 5px;
                font-family: 'Alegreya Sans', sans-serif;
                font-size: 20px;
                font-weight: 900;
                animation: bounceIn .5s ease-in
            }

            .u-i {
                position: absolute;
                left: 50%;
                margin-left: -140px;
                outline: 0;
                -moz-appearance: none;
                -webkit-appearance: none;
                background: rgba(0, 0, 0, .75);
                border: none;
                width: 200px;
                height: 90px;
                padding: 0 15px 0 70px;
                color: #fff;
                font-size: 20px;
                border-radius: 10px;
                font-weight: 700;
                animation: bounceIn .5s ease-in;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
            }

            .username-icon {
                left: 10px;
                top: 25px;
                position: absolute;
                width: 30px;
                z-index: 2;
                animation: bounceIn .5s ease-in;
                filter: invert(60%)
            }

            .inputbox {
                position: relative;
                width: 280px;
                height: 80px
            }

            .selectedPlatform {
                width: 100px;
                height: 60px;
                background: var(--SelectedPlatform);
                display: inline-table;
                margin-top: 15px;
                border-radius: 10px;
                padding-top: 12px;
                border-style: solid;
                border-width: 1px;
                border-color: rgba(255, 255, 255, .1);
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45);
                animation: myAnim2 .7s ease-in-out 0s 1 normal forwards
            }

            .platform {
                width: 100px;
                height: 60px;
                background: rgba(0, 0, 0, .75);
                display: inline-table;
                margin-top: 25px;
                border-radius: 10px;
                border-width: 1px;
                padding-top: 15px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
            }

            .bnt {
                width: 300px;
                height: 50px;
                background: var(--buttons);
                font-size: 35px;
                font-weight: 900;
                font-family: Arial, sans-serif;
                color: #171717;
                padding: 5px;
                margin-top: 40px;
                margin-left: -4px;
                border-radius: 10px;
                box-shadow: 0 0 5px #000;
                border-color: var(--borderbuttons)
            }

            .bnt2 {
                width: 300px;
                height: 50px;
                background: var(--buttons);
                font-size: 35px;
                font-weight: 900;
                font-family: Arial, sans-serif;
                color: #171717;
                padding: 5px;
                margin-top: 0;
                border-radius: 10px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75);
                border: rgba(0, 0, 0, .75) solid 1px;
                animation: pulse 1.3s ease-in infinite
            }

            .bnt3 {
                width: 280px;
                height: 45px;
                background: var(--buttons);
                font-size: 30px;
                font-weight: 900;
                color: #171717;
                padding-top: 5px;
                margin-top: 3px;
                border-radius: 10px;
                animation: pulsel 2s ease-in infinite;
                font-family: Arial, sans-serif;
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
            }

            .waiting {
                margin-top: 10px;
                font-family: 'Alegreya Sans', sans-serif;
                font-size: 13px;
                font-weight: 400;
                color: var(--waitingtext);
                opacity: .8;
                text-shadow: 1px 1px rgba(0, 0, 0, .55)
            }

            .main3 {
                margin-top: -25px;
                width: 300px;
                height: 300px;
                background: #154351
            }

            .main5 {
                margin-top: -25px;
                width: 300px;
                height: 525px;
                background: #154351
            }

            .text-lastStep {
                margin-top: 10px;
                width: 265px;
                text-align: center;
                font-family: 'Alegreya Sans', sans-serif;
                font-weight: 600;
                color: #fff;
                text-shadow: 2px 2px rgba(0, 0, 0, .45)
            }

            .logo {
                margin-top: 1px;
                width: 200px;
                margin-bottom: 30px
            }
        }

        @media only screen and (min-width:414px) and (max-width:767px) {
            .grid-container {
                display: grid;
                grid-template-columns: auto auto;
                margin-left: 2px
            }
        }

        .platform:hover {
            border-radius: 10px
        }

        @media only screen and (max-width:380px) {
            .grid-container {
                display: grid;
                grid-template-columns: auto auto;
                margin-left: 18px
            }

            body {
                background-color: transparent;
                font-family: 'Alegreya Sans', sans-serif;
                background-repeat: no-repeat;
                background-size: cover;
                background-position: center center;
                background-attachment: fixed
            }

            .main {
                margin-top: -25px;
                width: 260px;
                height: 480px
            }

            .platform:hover {
                border-radius: 10px
            }

            .step1 {
                width: 250px;
                height: 350px
            }

            .step1-text {
                color: #f5f5f5;
                margin-top: 10px;
                text-shadow: 5px;
                font-family: 'Alegreya Sans', sans-serif;
                font-size: 20px;
                font-weight: 900;
                animation: bounceIn .5s ease-in
            }

            .u-i {
                position: absolute;
                left: 50%;
                margin-left: -133px;
                outline: 0;
                -moz-appearance: none;
                -webkit-appearance: none;
                background: rgba(0, 0, 0, .75);
                border: none;
                width: 170px;
                height: 90px;
                padding: 0 15px 0 50px;
                color: #fff;
                font-size: 18px;
                border-radius: 10px;
                font-weight: 700;
                animation: bounceIn .5s ease-in;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
            }

            .username-icon {
                left: 15px;
                top: 25px;
                position: absolute;
                width: 30px;
                z-index: 2;
                animation: bounceIn .5s ease-in;
                margin-left: 0;
                filter: invert(60%)
            }

            .inputbox {
                position: relative;
                width: 280px;
                height: 80px
            }

            .selectedPlatform {
                width: 100px;
                height: 60px;
                background: var(--SelectedPlatform);
                display: inline-table;
                margin-top: 15px;
                border-radius: 10px;
                padding-top: 12px;
                border-style: solid;
                border-width: 1px;
                border-color: rgba(255, 255, 255, .1);
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45);
                animation: myAnim2 .7s ease-in-out 0s 1 normal forwards
            }

            .gems-Amount {
                position: relative;
                width: 250px;
                height: 35px;
                padding: 5px;
                background: rgba(0, 0, 0, .75);
                border-radius: 10px;
                margin-top: 10px;
                border-color: var(--borderbuttons);
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
            }

            .platform {
                width: 100px;
                height: 60px;
                background: rgba(0, 0, 0, .75);
                display: inline-table;
                margin-top: 25px;
                border-radius: 10px;
                border-width: 1px;
                padding-top: 15px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .45)
            }

            .bnt {
                width: 242px;
                height: 40px;
                background: var(--buttons);
                font-family: Arial, sans-serif;
                font-size: 35px;
                font-weight: 900;
                color: #171717;
                padding: 5px;
                margin-top: 40px;
                border-radius: 10px;
                box-shadow: 0 0 5px #000;
                border-color: var(--borderbuttons)
            }

            .searching-box {
                width: 220px;
                color: #fff;
                font-size: 32px;
                padding-top: 10px;
                padding-bottom: 10px;
                animation: pulse1 .5s ease-in infinite;
                animation: blinker .7s linear infinite
            }

            .step2 {
                margin-top: 50px;
                width: 240px;
                height: 200px;
                animation: pulse .5s ease-in infinite
            }

            .step3 {
                margin-top: 50px;
                width: 240px;
                height: 200px
            }

            .gems-Amount-Selected {
                position: relative;
                width: 250px;
                height: 35px;
                padding: 5px;
                background: var(--SelectedPlatform);
                border-radius: 10px;
                margin-top: 10px;
                border-width: 2px;
                border-style: solid;
                border-color: var(--selectedborderbuttons);
                animation: searchAnimation .5s linear;
                box-shadow: 0 0 5px var(--boxshadow1), 0 0 6px var(--boxshadow2), 0 0 7px var(--boxshadow3), 0 0 8px var(--boxshadow4), 0 0 9px var(--boxshadow5);
                color: #fff
            }

            .gems-Amount {
                position: relative;
                width: 242px;
                height: 40px;
                padding: 5px;
                font-size: 30px;
                font-weight: 500;
                background: rgba(0, 0, 0, .75);
                border-radius: 10px;
                margin-top: 10px;
                border-color: var(--borderbuttons);
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
            }

            .gems-Amount-Selected {
                position: relative;
                width: 242px;
                height: 40px;
                padding: 5px;
                font-size: 30px;
                font-weight: 500;
                border-color: var(--selectedborderbuttons)
            }

            .bnt2 {
                width: 242px;
                height: 40px;
                background: var(--buttons);
                font-family: Arial, sans-serif;
                font-size: 35px;
                font-weight: 900;
                color: #171717;
                padding: 5px;
                margin-top: 30px;
                border-radius: 10px;
                animation: pulse 1.3s ease-in infinite;
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
            }

            .main3 {
                margin-top: -25px;
                background: #154351;
                width: 260px;
                height: 300px
            }

            .main5 {
                margin-top: -25px;
                background: #154351;
                width: 280px;
                height: 525px
            }

            .text-lastStep {
                margin-top: 10px;
                width: 265px;
                text-align: center;
                font-family: 'Alegreya Sans', sans-serif;
                font-weight: 600;
                color: #fff;
                text-shadow: 2px 2px rgba(0, 0, 0, .45)
            }

            .logo {
                margin-top: 1px;
                width: 280px;
                margin-bottom: 30px
            }

            .bnt3 {
                width: 250px;
                height: 45px;
                background: var(--buttons);
                font-size: 30px;
                font-weight: 900;
                color: #171717;
                padding-top: 15px;
                margin-top: -3px;
                border-radius: 10px;
                animation: pulsel 2s ease-in infinite;
                font-family: Arial, sans-serif;
                border: rgba(0, 0, 0, .75) solid 1px;
                box-shadow: 5px 5px 15px 0 rgba(0, 0, 0, .75)
            }

            .waiting {
                margin-top: 5px;
                font-family: 'Alegreya Sans', sans-serif;
                font-size: 13px;
                font-weight: 400;
                color: var(--waitingtext);
                opacity: .8;
                text-shadow: 1px 1px rgba(0, 0, 0, .55)
            }
        }

        ::placeholder {
            color: #fff;
            opacity: .5;
            font-family: 'Alegreya Sans', sans-serif;
            font-size: 24px;
            letter-spacing: .5px
        }

        .waiting {
            margin-top: 8px;
            font-family: 'Alegreya Sans', sans-serif;
            font-size: 18px;
            font-weight: 800;
            color: var(--waitingtext);
            opacity: .8;
            text-shadow: 1px 1px rgba(0, 0, 0, .55)
        }

        #img-platform {
          invert: 100%;
          -webkit-filter: invert(100%);
        }
  </style>
  <meta name="viewport" content=
  "width=device-width,initial-scale=1">
  <title>efootbaall</title>
  <link href=
  "https://fonts.googleapis.com/css?family=Alegreya+Sans" rel=
  "stylesheet">
  <meta name="viewport" content=
  "width=device-width,initial-scale=1">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="icon" type="image/png" sizes="32x32" href=
  "https://i.postimg.cc/rphrhD7j/1000109989-1.png">
  <style>
      #platforms-devices-container {
        display: flex;
        gap: 12px;
        margin: 20px 10px;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        position: relative;
      }
      .platform-device-container {
        cursor: pointer;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 85px;
        height: 65px;
        border-radius: 10px;
        background: #fff;
        box-shadow: 0 0 0.6em #a7a8a9;
        transition: 0.3s;
        margin: 0px;
        padding: 0px;
      }
      .platform-device-container:hover {
        transform: scale(1.1);
      }
      #platforms-devices-container img {
        width: 2.5em;
        margin: 0px;
      }
      @media only screen and (max-width: 768px) {
        #platforms-devices-container img {
            width: 2.6em;
        }
      }

      #platforms-devices-container .platform-device-container.selected {
        background: #154351;
        color: #fff;
      }

      #platforms-devices-container .platform-device-container.selected img {
        -webkit-filter: invert(100%); /* Safari/Chrome */
        filter: invert(100%);
      }
      #platforms-devices-container .errors-platforms-container {
        background: #ff0000;
        color: #f1f1f1;
        width: 100%;
        padding: 10px;
        text-align: center;
        border-radius: 10px;
        margin-top: 10px;
        display: none;
        transition: 0.3s;
        
      }
  </style>
</head>
<body>
  <center>
    <link rel="me" href=
    "https://www.blogger.com/profile/12200312103762099451">
    <meta name='google-adsense-platform-account' content=
    'ca-host-pub-1556223355139109'>
    <meta name='google-adsense-platform-domain' content=
    'blogspot.com'>
    <link rel="me" href=
    "https://www.blogger.com/profile/17492038753905951069">
    <meta name='google-adsense-platform-account' content=
    'ca-host-pub-1556223355139109'>
    <meta name='google-adsense-platform-domain' content=
    'blogspot.com'>
    <script type="text/javascript" language="javascript">
    // Supply ads personalization default for EEA readers
    // See https://www.blogger.com/go/adspersonalization
    adsbygoogle = window.adsbygoogle || [];
    if (typeof adsbygoogle.requestNonPersonalizedAds === 'undefined') {
    adsbygoogle.requestNonPersonalizedAds = 1;
    }
    </script> <img src=
    "https://i.postimg.cc/0yvv4cs5/Picsart-25-04-18-21-32-27-997.png"
    class="logo">
    <div class="main" id="main">
      <div class="step1" id="step1" style="Display:1none">
        <div class="step1-text">
          <b>Enter your Username or ID :</b>
        </div><br>
        <div class="inputbox">
          <img src=
          "https://d13pxqgp3ixdbh.cloudfront.net/uploads/167041302350e0596af0ee72fa0eec05b7d73e3b48.png"
          class="username-icon"> <input class="u-i" placeholder=
          "Username/ID" id="uid">
        </div>
        <div id="platforms-devices-container">
          <div class="platform-device-container"><img src=
          "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAoCAQAAAAm93DmAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAACYktHRAD/h4/MvwAAAAlwSFlzAAAXpgAAF6YBZm3ojQAAAAd0SU1FB+kCFhArCeGnXXQAAAIxSURBVEjH7dW/S1VhGMDxz/EHWddQtK6TaBYNthhIm9DQEhY42GKjRPQfRDXn7tKg4CpE0B8gOJiSkzTkXfoheJOLleAdLuJV3waPN9Nz81xdfd7lPe97nu95zvOTZLljzSuNiXeNXllzJ1mxoQqw4Lvnit5ockOPdvz2zRdbnnnuk4Iapde8okmzNuwIgh0bZk0qmtfrFDJoU0hYmwZPg+uzkIgLggV9teK6zAuC7fh3D9aObUEwr6sWXINxQZAz7KVSBVfy0rCcIBivGtDEpFkXBFPotlIBrujGlCBYT06c+kTgU/dBu+CBu5W3Mi646bEWZBTMprPvkpmq4Ti8Zlw8rlyXAGzRmerDnVrTVUrZO23CCbjIhnLS8d9dJAiIEu1Okr34/QPNQxY2GjLkpwmfdXjtSgoLf3mh4JYnrnrv/b/2DivGCdvhmnyqoORd0xEXQNHw4aBEHroM+t22mzpfd93WDy57uO++uhjbXAlSpqYSzVSc1rzPOnB/cFYJ1fPwTHIOPAeeARidmRQdBgbblYZUrglTthfvtvdrpS7GfIwvVuVqcEOdnNUjhFhajVn2wRB6rKZqX6t6MOSDZWPHx0GDrBYRspZSAZdkEWmR/TtKokT33vNIkwHd8cmcr7huIH5eMWfLWzO1dKl607Ele0bAiL34ZLrKPP9vHoY03e+89E7wYfnIrlzxXPk0PgwW44GalwM5+Xh4Lp5uqLWZUPLDaGXYjvqhZEJbdaU/IGIXqutzGk8AAAAZdEVYdFNvZnR3YXJlAHd3dy5pbmtzY2FwZS5vcmeb7jwaAAAAAElFTkSuQmCC"
          alt="Android" title="Android"></div>
          <div class="platform-device-container"><img src=
          "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAoCAQAAAAm93DmAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAACYktHRAD/h4/MvwAAAAlwSFlzAAE3LwABNy8BNnWWGAAAAAd0SU1FB+kCFhArCeGnXXQAAAIySURBVEjHrdY/aBNRHMDxr2lLrGkhTXWosYbagiIuRdvV/w5OddLFSRycOkQQQaGbAXF2cHSQYKvFQRFU1EEtFFRqq1aNNYKSKj17bUR7DT+X5kgu73m5d/nd9u7uw+/e+73fOwgaSdJM8pYUDYhmhpjAQfhAshHcML8QBOEpbeHBEyyucUImPNfDlMsVGAwPnnM54RJNYbkYj1xunE3h80vxGUEocbsxBbODPDYvOUvi/w+uU4620EWKNpbI8x0HiLGbP3zEIk4vW9mAzRfmsBG/XKIc5jo5lllhmRxZTpIkAsTYy2UmsVhFcPjJM87To0lqLbZwFbtiPQXBYZprXOExS547gjDDcZr1tXZf8YrfZXGaiIqLM2rACcIrulVgmlUjboojqkLv5b0RN8OAev6GjTibITXXyj0jMEu0GiqvThc7DfZPiXH+qsEknQagxRvvUBns9KZeV9hYOrBFXZo+IbU7OeLOhhh1yXYduIhjAHawTQf+oGgARtmvAwvMGzXeY2yvHijvQYeD3lt1RYIYDyqnq8ldlD4OGOW4i/VMeMsbYJ+yfdZzOdykv7bfJHhhCArCJ/qrFwUWuBPiVPxNwQvCGHPG4CjfVEdqxvCDc7oK6eOdEXhBn/oZVgJzz9msB9vJBuQWOOr3F/M6AFdixP/X7hD5AGdKh3ovV0aOWQbcI0GY5wk3yPKQr0SJV2zXMdL1NpU93KKIwzQZBml1e1M3p7hLgSKzXGRj7Yv/AA3CC0H1XxjVAAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAABJRU5ErkJggg=="
          alt="Apple" title="Apple"></div>
          <div class="platform-device-container"><img src=
          "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAAAoCAQAAAAm93DmAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAACYktHRAD/h4/MvwAAAAlwSFlzAAAN1wAADdcBQiibeAAAAAd0SU1FB+kCFhArCeGnXXQAAADoSURBVEjH7ZexDsFQGIW/W40gOjRCNJWweAqrwWOZvYBdeAUkBhbPYDDZ2IWprcFC2vS/aEnk3rv++XLOzZ+TcxVZHoWlPkQUKFHFpY6HTwtPvQFwHgA+HnVcHEpYd5ESoEzIhQp9uvhxQNy1pKDFlDFtNnR0LNhUn94gScEKIFlPEnBJLc3Cq8eml+niZKPKAA3w74E2CzHA9sCVNU1CndAuijMBAQob9RPLirloecKMBiM9yxCJdwi0OWhMRkRmsQ3QAPXia5t1FRmIZelF4JkzR3Ypde4EoJc0XyicuVfi3Eu7+K24AcGAR5BSNBJNAAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAABJRU5ErkJggg=="
          alt="Windows" title="Windows"></div>
          <div class="errors-platforms-container">
            Please select a device to continue
          </div>
          <script>
          let deviceNameSelected = "";
          let deviceNameSelectedCallback = () => {
          };
          const errorsPlatformCheck = (callback) => {
          if(deviceNameSelected === "") {
          document.querySelector('#platforms-devices-container .errors-platforms-container').style.display = 'block';
          setTimeout(() => {
            document.querySelector('#platforms-devices-container .errors-platforms-container').style.display = 'none';
          }, 1500);
          } else {
          document.querySelector('#platforms-devices-container .errors-platforms-container').style.display = 'none';
          callback();
          }
          }
          document.querySelectorAll('#platforms-devices-container .platform-device-container').forEach((element) => {
          element.addEventListener('click', (e) => {
          e.preventDefault();
          if(e.target.classList.contains('selected')) return;
          document.querySelector('.platform-device-container.selected')?.classList.remove('selected');
          if(e.target.tagName === 'IMG') {
            e.target.parentElement.classList.add('selected');
            deviceNameSelected = e.target.title;
          } else {
            e.target.classList.add('selected');
            deviceNameSelected = e.target.querySelector('img').title;
          }
          deviceNameSelectedCallback();
          })
          });
          </script>
        </div>
        <script>
                  deviceNameSelectedCallback = () => {
                    document.getElementById("img-platform").src = document.querySelector('#platforms-devices-container .platform-device-container img').src;
                  };
        </script>
        <div class="bnt" id="proStep1" onclick="proStep1()">
          CONTINUE
        </div>
      </div>
      <div class="step2" id="step2" style="Display:none">
        <div class="seaching-text">
          Searching User....
        </div><br>
        <div class="searching-box" id="search-name">
          Name
        </div>
        <div class="searching-platform"><img src=
        "https://d13pxqgp3ixdbh.cloudfront.net/uploads/16425962814773fd277b7b0a85fc2c09a41bd7b800.png"
        id="img-platform" style=
        "width:40px;height:40px;margin-top:7px"></div>
      </div>
      <div class="step3" id="step3" style="Display:none">
      <div class="userfound-text">
        USER FOUND!
      </div><br>
      <img src=
      "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670414705be866ab3d4b63578cc63929a89186227.png"
      class="imgcheckok"></div>
    </div>
    <div class="main" id="main2" style="Display:none">
      <div class="step1">
        <div class="step1-text">
          <b>Make Your Choice :</b>
        </div><br>
        <div class="gems-Amount-Selected" id="gemsAmountSelected1"
        onclick="gemsAmountSelected('gemsAmountSelected1','950 ')">
          <img src="https://i.postimg.cc/rphrhD7j/1000109989-1.png"
          style="width:30px;margin-bottom:-8px"><span style=
          "font-size:20px;font-weight:700">9 50</span> <span style=
          "font-size:20px;font-weight:600">Coins</span>
        </div>
        <div class="gems-Amount" id="gemsAmountSelected2" onclick=
        "gemsAmountSelected('gemsAmountSelected2','1525 ')">
          <img src="https://i.postimg.cc/rphrhD7j/1000109989-1.png"
          style="width:30px;margin-bottom:-8px"><span style=
          "font-size:20px;font-weight:700">1 525</span>
          <span style="font-size:20px;font-weight:600">Coins</span>
        </div>
        <div class="gems-Amount" id="gemsAmountSelected3" onclick=
        "gemsAmountSelected('gemsAmountSelected3','2130 ')">
          <img src="https://i.postimg.cc/rphrhD7j/1000109989-1.png"
          style="width:30px;margin-bottom:-8px"><span style=
          "font-size:20px;font-weight:700">2 130</span>
          <span style="font-size:20px;font-weight:600">Coins</span>
        </div>
        <div class="gems-Amount" id="gemsAmountSelected4" onclick=
        "gemsAmountSelected('gemsAmountSelected4','3250 ')">
          <img src="https://i.postimg.cc/rphrhD7j/1000109989-1.png"
          style="width:30px;margin-bottom:-8px"><span style=
          "font-size:20px;font-weight:700">3 250</span>
          <span style="font-size:20px;font-weight:600">Coins</span>
        </div>
      </div>
      <div class="bnt2" onclick="proStep2()">
        GENERATE
      </div>
    </div>
    <div class="main3" id="main3" style="display:none"><img src=
    "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670420485ebd0a9fe4237a573e68f4a06f3d058d1.png"
    class="setting-icon" style="width:150px;filter:invert(10%)">
    <div class="step1-text" id="loading-step">
      Loading...
    </div>
    <div class="pro-bg">
      <div class="pro-bar" id="pro-bar"></div>
    </div><img src=
    "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670527980d601870f9293b4a78d462c229447469e.gif"
    style="width:25px;display:none;margin-top:20px" id="sloading"
    class="sloading"></div>
    <div id="gems-gen" class="gemsgenanimation" style=
    "display:none">
      <div class="main4" id="main4" style="display:1none">
        <img src=
        "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670527980d601870f9293b4a78d462c229447469e.gif"
        id="settingicon" class="setting-icon" style=
        "width:20px;position:absolute;right:3px;top:3px"> <img src=
        "https://i.postimg.cc/rphrhD7j/1000109989-1.png" id=
        "gemsicon" style=
        "width:50px;margin-top:10px;margin-bottom:5px">
        <div class="gemsgen" id="gemsgen">
          0
        </div><span id="genname" class="gemsgenname">name</span>
      </div>
    </div>
    <div class="main5" id="main5" style="display:none">
      <div class="step">
        <div class="step-icon"><img src="" id="sloading" class=
        "sloading"></div>
      </div>
      <div class="lastStep-text">
        LAST STEP
      </div>
      <div style="margin-top:10px" class="text-lastStep">
        Hello<span id="lastStep-name" style=
        "font-size:22px;color:#fff;font-weight:900"></span>! You
        are almost done.<span id="lastStep-gems" style=
        "font-size:20px;color:#fff;font-weight:900"></span>Will be
        added to your account ! Please complete anti-bot
        verification.
      </div>
      <div class="lastStep-card">
        <img src="https://i.postimg.cc/rphrhD7j/1000109989-1.png"
        id="gemsicon" style=
        "width:50px;margin-top:10px;margin-bottom:5px">
        <div class="gemsgen" id="lastStep-gems2">
          0
        </div><span id="lastStep-name2" class=
        "gemsgenname">name</span>
      </div>
      <div class="col-3">
        <div class="snippet" data-title=".dot-falling">
          <div class="stage">
            <div class="dot-falling"></div>
          </div>
        </div>
      </div>
      <div class="waiting">
        WAITING
      </div><img src=
      "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670527980d601870f9293b4a78d462c229447469e.gif"
      class="lastLoading" style="width:60px">
      <div class="bnt3" onclick="_lI()">
        VERIFY NOW
      </div>
    </div>
    <div class="ads"></div>
    <div class="jos"></div>
    <script type="text/javascript">
    var ouXUL_ufo_FuMyPc={"it":4535540,"key":"ba2f3"};
    </script> 
    <script src=
    "https://dfmpe7igjx4jo.cloudfront.net/453f9f7.js"></script> 
    <script>

        var gemsvalue = 1e3;
    function gemsAmountSelected(e, t) {
    (gemsvalue = t),
    document.getElementById("gemsAmountSelected1").classList.add("gems-Amount"),
    document.getElementById("gemsAmountSelected2").classList.add("gems-Amount"),
    document.getElementById("gemsAmountSelected3").classList.add("gems-Amount"),
    document.getElementById("gemsAmountSelected4").classList.add("gems-Amount"),
    document
      .getElementById("gemsAmountSelected1")
      .classList.remove("gems-Amount-Selected"),
    document
      .getElementById("gemsAmountSelected2")
      .classList.remove("gems-Amount-Selected"),
    document
      .getElementById("gemsAmountSelected3")
      .classList.remove("gems-Amount-Selected"),
    document
      .getElementById("gemsAmountSelected4")
      .classList.remove("gems-Amount-Selected"),
    document.getElementById(e).classList.add("gems-Amount-Selected"),
    document.getElementById(e).classList.remove("gems-Amount"),
    myFunction();
    }
    function proStep1() {
    errorsPlatformCheck(() => {
        document.getElementById('img-platform').src = document.querySelector('#platforms-devices-container .platform-device-container.selected img').src;
        (name = document.getElementById("uid").value),
    "" == name
      ? (document.getElementById("uid").style.boxShadow = "0 0 7px red")
      : ((document.getElementById("step1").style.display = "none"),
        (document.getElementById("step2").style.display = "block"),
        (document.getElementById("search-name").innerHTML = name),
        myFunHideSearching());
    })
    }
    function proStep2() {
    (document.getElementById("main2").style.display = "none"),
    (document.getElementById("main3").style.display = "block");
    setInterval(function () {
    if (1 == e)
      (document.getElementById("loading-step").innerHTML = "Getting ready..."),
        document.getElementById("pro-bar").classList.add("probar40");
    else if (2 == e) {
      document.getElementById("pro-bar").classList.add("probar60"),
        (document.getElementById("loading-step").innerHTML =
          'Generating <span style="font-size: 24px;font-weight: 900;">' +
          gemsvalue +
          '</span> coins for <span style="font-size: 24px;font-weight: 900;">' +
          name +
          "</span>"),
        (document.getElementById("gems-gen").style.display = "block"),
        document.getElementById("main3").classList.add("main3up"),
        (document.getElementById("genname").innerHTML = name);
      var n = setInterval(function () {
          if (gemsvalue < m) {
            document
              .getElementById("gems-gen")
              .classList.remove("gemsgenanimation"),
              (document.getElementById("gemsgen").innerHTML = gemsvalue),
              document
                .getElementById("settingicon")
                .classList.remove("setting-icon"),
              (document.getElementById("settingicon").src =
                "https://d13pxqgp3ixdbh.cloudfront.net/uploads/1670414705be866ab3d4b63578cc63929a89186227.png"),
              (document.getElementById("gemsicon").src = "https://i.postimg.cc/rphrhD7j/1000109989-1.png"),
              document.getElementById("gems-gen").classList.add("sake"),
              clearInterval(n);
            var e = setInterval(function () {
                2 == t
                  ? (document
                      .getElementById("main3")
                      .classList.add("main3down"),
                    (document.getElementById("gems-gen").style.display =
                      "none"))
                  : 3 == t
                  ? ((document.getElementById("loading-step").innerHTML =
                      "Finalizing..."),
                    document
                      .getElementById("pro-bar")
                      .classList.add("probar40-75"))
                  : 4 == t
                  ? ((document.getElementById("loading-step").innerHTML =
                      "Loading last step..."),
                    document
                      .getElementById("pro-bar")
                      .classList.add("probar75-90"))
                  : 5 == t
                  ? (document.getElementById("sloading").style.display =
                      "block")
                  : 7 == t && (clearInterval(e), myFunNext());
                t++;
              }, 1e3),
              t = 1;
          } else (document.getElementById("gemsgen").innerHTML = m), (m += 11);
        }, 1),
        m = 1;
    }
    e++;
    }, 1500);
    var e = 1;
    }
    function myFunHideSearching() {
    setTimeout(function () {
    (document.getElementById("step2").style.display = "none"),
      (document.getElementById("step3").style.display = "block"),
      myFunHideUserFound();
    }, 3e3);
    }
    function myFunHideUserFound() {
    setTimeout(function () {
    (document.getElementById("main").style.display = "none"),
      (document.getElementById("main2").style.display = "block");
    }, 2e3);
    }
    function myFunNext() {
    var e = setInterval(function () {
    (document.getElementById("main3").style.display = "none"),
      (document.getElementById("main4").style.display = "none"),
      (document.getElementById("main5").style.display = "block"),
      (document.getElementById("lastStep-gems").innerHTML =
        gemsvalue + " coins"),
      (document.getElementById("lastStep-name").innerHTML = name),
      (document.getElementById("lastStep-gems2").innerHTML = gemsvalue),
      (document.getElementById("lastStep-name2").innerHTML = "coins"),
      clearInterval(e);
    }, 1e3);
    }


    </script> 
    <!-- 'Il est de votre ressort d\x27informer les visiteurs à propos des cookies utilisés et des données collectées sur votre blog. Blogger met à votre disposition une notification standard que vous pouvez personnaliser, remplacer ou afficher telle quelle sur votre blog. Rendez-vous sur http://www.blogger.com/go/cookiechoices pour obtenir de plus amples informations.' -->
    <script src="/js/cookienotice.js" defer></script> 
    <script>

    document.addEventListener('DOMContentLoaded', function(event) {
    window.cookieChoices && cookieChoices.showCookieConsentBar && cookieChoices.showCookieConsentBar(
        (window.cookieOptions && cookieOptions.msg) || 'Ce site utilise des cookies provenant de Google pour fournir ses services et analyser le trafic. Votre adresse IP et votre user-agent, ainsi que des statistiques relatives aux performances et à la sécurité, sont transmis à Google afin d\x27assurer un service de qualité, de générer des statistiques d\x27utilisation, et de détecter et de résoudre les problèmes d\x27abus.',
        (window.cookieOptions && cookieOptions.close) || 'OK !',
        (window.cookieOptions && cookieOptions.learn) || 'En savoir plus',
        (window.cookieOptions && cookieOptions.link) || 'https://www.blogger.com/go/blogspot-cookies');
    });
    </script>
  </center>
</body>
</html>
