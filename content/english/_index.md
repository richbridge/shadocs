---
weight: 0
title: "Shadocs 主题文档"
description: "Shadocs 主题首页"
categories: ["主题"]
---

{{< intro
  introtitle="主题入门引导"
  id="introHome"
>}}
{
  "onexit": "manageDefaultCollapsibleSidebar();toggleExtendMenu(false);",
  "oncomplete": "window.location.href = './theme';",
  "steps": [
    {
      "title": "Shadocs 主题",
      "intro": "欢迎来到 Shadocs 主题文档网站。<br>通过这个分步入门指南，您将了解网站的多种功能，进而熟悉该主题的各项特性。",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "Logo 标志",
      "intro": "网站 Logo 可让您返回首页。",
      "element": "#globalLogo",
      "position": "right",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "导航栏",
      "intro": "位于屏幕顶部的水平条，也称为导航栏，包含多个功能以方便网站导航和提升用户体验。根据窗口宽度，会出现一个扩展菜单，用于显示隐藏的导航栏按钮。",
      "element": "#navbar",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "搜索",
      "intro": "搜索功能允许在整个网站中搜索内容。<br><i>注意：不支持使用正则表达式的高级搜索。</i>",
      "element": "#search",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "亮色/暗色模式",
      "intro": "亮色/暗色模式允许在亮色和暗色显示模式之间切换。</i>",
      "element": "#colorModeToggle",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "打印",
      "intro": "打印功能允许打印当前页面的内容。",
      "element": "getFirstVisibleElement('#printButton, #printButtonExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "二维码",
      "intro": "二维码功能用于显示与当前页面 URL 关联的二维码。",
      "element": "getFirstVisibleElement('#qrCodeButton, #qrCodeButtonExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "快捷键",
      "intro": "快捷键按钮提供网站上可用快捷键的列表。",
      "element": "getFirstVisibleElement('#shortcutsInfo, #shortcutsInfoExtend');",
      "position": "left",
      "triggerexcept": ["nohover"],
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "分类",
      "intro": "分类按钮提供网站的各种分类入口。<br><i>注意：仅当至少存在一个分类时，此按钮才可见。</i>",
      "element": "getFirstVisibleElement('#taxonomiesSelector, #taxonomiesSelectorExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "多语言",
      "intro": "多语言按钮提供当前页面的多个翻译版本。<br><i>注意：仅当当前页面存在翻译时，此按钮才可见。</i>",
      "element": "getFirstVisibleElement('#langsSelector, #langsSelectorExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "版本管理",
      "intro": "版本管理按钮提供网站的其他可用版本。",
      "element": "getFirstVisibleElement('#versionsSelector, #versionsSelectorExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "关于网站",
      "intro": "信息按钮提供关于网站的常规信息。",
      "element": "getFirstVisibleElement('#siteInfo, #siteInfoExtend');",
      "position": "left",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(true);"
    },{
      "title": "侧边栏",
      "intro": "屏幕左侧的侧边栏允许浏览网站的所有页面。",
      "element": "#sidebar",
      "onbeforechange": "toggleSidebar(true,true);toggleExtendMenu(false);"
    },{
      "title": "侧边栏",
      "intro": "可以折叠侧边栏，仅显示主要部分的图标。",
      "element": "#sidebarCollapse",
      "onbeforechange": "toggleSidebar(true,true);toggleExtendMenu(false);"
    },{
      "title": "侧边栏",
      "intro": "当侧边栏折叠时，将鼠标悬停在一个区域上可显示关联的子菜单（在触摸设备上点击即可）。<br><i>注意：当窗口宽度小于 1024 像素时，侧边栏默认折叠。</i>",
      "element": "#sidebarUncollapse",
      "onbeforechange": "toggleSidebar(false,true);toggleExtendMenu(false);"
    },{
      "title": "Shadocs 主题",
      "intro": "恭喜！！<br>您现在可以浏览网站以了解更多关于该主题的信息。<br><i>点击“完成”继续引导流程。</i>",
      "onbeforechange": "manageDefaultCollapsibleSidebar();toggleExtendMenu(false);"
    }
  ]
}
{{< /intro >}}