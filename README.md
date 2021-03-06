
<h1 class="hide">React Native 實戰演練：<br />使用 JavaScript 開發 iOS App</h1>

> 學習 Objective-C、Apple Swift 與 Android SDK（Java）的話，就是三套觀念與技術；學習 React Native 的話就是一套觀念與技術

React Native 是開發手機應用程式 (App) 的新選擇。使用 React Native 與 JavaScript 程式語言，同時開發 iOS 與 Android 應用程式，是今年相當受歡迎的技術。

## PhoneGap vs React Native

React Native 與 PhoenGap 都是行動應用程式（App）的開發框架，也都是以 JavaScript 打造 App 的軟體框架。如果我想進入 App 開發領域，要學習哪一個框架，以及二個框架有什麼差異？

* **PhoneGap** 是「使用 JavaScript 開發 App」的始祖，它的技術原理是將 *WebView* 封裝成手機應用。*WebView* 是手機瀏覽器的元件，這意謂開發者可以使用 JavaScript/CSS3/HTML5 來製作 Web UI，並透過 *WebView* 元件在手機上運行。PhoneGap 就是利用這樣的原理所打造的框架。PhoneGap 所提供的 JavaScript API 都要透過 *WebView* 元件執行，*WebView* 再實作一個稱為 *JavaScript-Java Bindings* 的介面，呼叫 Native APIs。

* **React Native** 與 PhoneGap 最大的差異，在於 React Native 直接使用手機原生（Native）的 JavaScript 元件，這表示使用 React Native 打造的 App，與直接使用原生 SDK 製作的 App 沒有倆樣。

## 為什麼選擇 React Native ?

我現在知道 React Native 與 PhoneGap 的差別了，如果我想學習 iOS App 開發，為什麼要選擇 React Native 框架，會建議學習 Objective-C 或是 Apple Swift 嗎？

* **JavaScript** 是 React Native 的編程語言，對於有 JavaScript 程式設計經驗的前端工程師、UI 設計師或產品經驗來說，React Native 的學習門檻低，入門速度快。
* [**Learn Once, Write Anywhere**](https://facebook.github.io/react/blog/2015/03/26/introducing-react-native.html) 是 React Native 的精神。Facebook 開發團隊認為，不同的行動平台有不同的風格與外觀，因此不引用 <del>write once, run anywhere</del> 的理念（這是 PhoneGap 的訴求），而是分別為 iOS 與 Android 製作應用程式。但是 React Native 能提供「一致的觀念」與「相同的技術」，讓你不需要「學習 iOS 與 Android 二個平台的觀念與技術」，也能「開發 iOS 與 Android 的應用程式」。所以，如果學習 Objective-C、Apple Swift 與 Android SDK（Java）的話，就會是三套觀念與技術；但是，如果學習 React Native 的話，就只有一套觀念與技術。

## 先備知識

以下是參加本課程，必須具備的條件：

* 具備 React 基礎知識：曾撰寫過 JSX 語法或是撰寫過 React Component
* 需有基本的 JavaScript 寫作能力
* 使用過 Node.js 開發環境：曾使用 npm 安裝過 Node.js 模組

這個課程是全程上機實作，對於完全沒有 React 開發經驗的朋友，可能會有學習成效的問題。建議課前自學 React 基本知識，以下是幾個建議：

1. 可閱讀 React 官方文件：[Getting Started](https://facebook.github.io/react/docs/getting-started.html)、[Tutorial](https://facebook.github.io/react/docs/tutorial.html) 與 [Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html) 文件，並練習撰寫簡單的 React Component。
2. 如果想節省入門時間，可參加 [React 101 實戰教學：開始用 React 打造 Web Frontend](https://www.mokoversity.com/training/React-101) 課程
3. 如果想在家自學，可購買 [React 101 線上課程：開始用 React 打造 Web Frontend](https://www.mokoversity.com/course/React/React-101-Online)，這份線上課程為全中文規劃與製作，相信可以讓學習時間更有效率

> 具備基本的 React 基礎知識，參加本課程，就可以在 7 個小時的時間裡，有條理地獨立完成一個 iOS App 專題

## 上課環境

* 請自備 Macbook，作業系統版本為 OS X 10.9 以上
* 請安裝 Xcode，版本 7.0 以上
* 請安裝 Node.js，版本 v4.3 以上

## 課程大綱

* 第 1 課：建立第一個 React Native 專案（iOS App）
* 第 2 課：React Native UI 基本結構（iOS App）
 * Welcome Page 製作
 * View 與 Image 元件的使用
 * 圖檔製作原則
 * Props 觀念加強
* 第 3 課：React Native 地圖元件實作（iOS App）
 * 美食地圖 Page 製作（MapView）
 * 如何使用樣式（Styles）
* 第 4 課：Navigation Bar 與 React Router（iOS App）
 * 選單 (Menu) 製作
 * 分頁切換
* 第 5 課：ListView 與 ScrollView（iOS App）
* 第 6 課：Persist Data 與 REST API (Web Service 整合)
* 第 7 課：Styles in JavaScript 與 Reusable Styles
* 第 8 課：美食推薦 iOS App 專題
 
<div class="row">
  <div class="col-md-4 col-xs-6 col-lg-4 col-xs-4">
    <img class="img-responsive" src="https://cloud.githubusercontent.com/assets/1126021/14764948/1e67a4e0-09fe-11e6-887d-e6c226a222f2.png" />
    <p>圖 1：Welcome Page 製作</p>
  </div>
</div>


## 課程專題

課程內容分為 3 大主軸：

* 學習使用 React Native 的觀念與 iOS App UI 製作
* 學習使用 React Native 開發基本 iOS UI 元件：ListView、WebView、Button 等
* 學習 REST API 並製作美食推薦 iOS App

> 製作專題的過程中，也會給予學員 Thinking in React 與 Thinking in Architecture 的訓練...

## 課程目標

React Native 實戰演練課程，採取工作坊的形式，搭配一個美食推薦 iOS App 專題。本課程適合：

* iOS App 初學者
* 想開始接觸使用 JavaScript 開發 iOS app 的設計師
* 想認識最新 iOS app 技術的產品經理

## 課程講師

<section style="background: #fff;">
  <div style="padding-bottom: 0px; padding-bottom: 0px;" class="container">
    <div class="row">
      <div class="col-md-2 text-left"><img src="https://avatars1.githubusercontent.com/u/1126021?v=3&s=400" width="128" height="128" class="img-circle img-responsive"></div>
      <div class="col-md-10">
        <h3 style="font-weight: 400; font-size: 1.6em; ">Jollen Chen</h3>
        <p style="font-weight: 300; color: #222; margin-top: -12px;">Jollen 是 Node.js 的全端開發者，正大量使用 Backbone 與 React 開發 IoT 相關的 web frontend 與 single-page application。Jollen 是 Moko365 的技術總監暨講師，也是 WoT.City 物聯網軟體公司的開發者。</p>
      </div>
    </div>
     <div class="row" style="margin-top: 65px;">
      <div class="col-md-2"><img src="https://avatars0.githubusercontent.com/u/2017447?v=3&amp;s=460" width="128" height="128" class="img-circle img-responsive"></div>
      <div class="col-md-10 text-left">
        <h3 style="font-weight: 400; font-size: 1.6em; ">Casear Chu</h3>
        <p style="font-weight: 300; color: #222; margin-top: -12px;">Casear 對於各種前後端技術皆有興趣，曾於 Microsoft 與 Trend Micro 任職，2012 獲得 Node.js Knockout 台灣區第一名，於 JSDC 2014、2015 擔任講師，曾致力於建立 slidenow（線上 Markdown 編輯 slide），目前興趣轉向 IoT，於 2015 年建立 KitchBot，轉至於廚具的系統分享與建立，並獲得聯發科穿戴式比賽亞軍。</p>
      </div>
    </div>
  </div>
</section>

## 開課時間

* 時間：平日下午班（共 2 天、總計 7 小時）
 * Day 1－2016 年 未定（四）14:00-17:30
 * Day 2－2016 年 未定（四）14:00-17:30
* 地點：台北市博愛路 25 號 3F
