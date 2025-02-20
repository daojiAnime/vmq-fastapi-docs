---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "VMQ Fastapi"
  text: "vmq-fastapi 文档"
  tagline: 一个基于 Fastapi 的支付系统
  image:
    src: /logo.png
    alt: VitePress
  actions:
    - theme: brand
      text: 示例
      link: /markdown-examples
    - theme: alt
      text: 项目源码
      link: https://github.com/daojiAnime/vmq-fastapi

features:
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2zm1.41 16.09V20h-2.67v-1.93c-1.71-.36-3.16-1.46-3.27-3.4h1.96c.1 1.05.82 1.87 2.65 1.87c1.96 0 2.4-.98 2.4-1.59c0-.83-.44-1.61-2.67-2.14c-2.48-.6-4.18-1.62-4.18-3.67c0-1.72 1.39-2.84 3.11-3.21V4h2.67v1.95c1.86.45 2.79 1.86 2.85 3.39H14.3c-.05-1.11-.64-1.87-2.22-1.87c-1.5 0-2.4.68-2.4 1.64c0 .84.65 1.39 2.67 1.91s4.18 1.39 4.18 3.91c-.01 1.83-1.38 2.83-3.12 3.16z"/></svg>
    title: 多渠道
    details: 能根据渠道来获取不同的支付消息，如微信、支付宝
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M12 2C6.486 2 2 6.486 2 12c0 5.515 4.486 10 10 10s10-4.485 10-10c0-5.514-4.486-10-10-10zm0 18c-4.411 0-8-3.589-8-8s3.589-8 8-8s8 3.589 8 8s-3.589 8-8 8zm.5-13H11v6l5.25 3.15l.75-1.23l-4.5-2.67z"/></svg>
    title: 异步回调
    details: 生成订单后无需等待，可在异步回调中处理订单
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M3 13h1v7c0 1.103.897 2 2 2h12c1.103 0 2-.897 2-2v-7h1a1 1 0 0 0 .707-1.707l-9-9a.999.999 0 0 0-1.414 0l-9 9A1 1 0 0 0 3 13zm9-8.586l6 6V15l.001 5H6v-9.586l6-6z"/></svg>
    title: 订单管理
    details: 后台可查看订单信息，并进行管理
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M12 2C9.243 2 7 4.243 7 7v3H6c-1.103 0-2 .897-2 2v8c0 1.103.897 2 2 2h12c1.103 0 2-.897 2-2v-8c0-1.103-.897-2-2-2h-1V7c0-2.757-2.243-5-5-5zm6 10l.002 8H6v-8h12zm-9-2V7c0-1.654 1.346-3 3-3s3 1.346 3 3v3H9z"/></svg>
    title: 超时异步锁
    details: 通过异步锁确保订单和付款信息一致性，在单支付渠道下增加并发量。
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M3 5v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2zm12 14H9v-2h6v2zm-6-4v-2h6v2h-6zm-2 4H5v-2h2v2zm0-4H5v-2h2v2zm10 4h-2v-2h2v2zm0-4h-2v-2h2v2zm0-4H5V7h12v4z"/></svg>
    title: 多租户支持
    details: 支持多租户，每个租户可以有独立的支付渠道和支付信息
  - icon: <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><path fill="currentColor" d="M12 4a4 4 0 0 1 4 4a4 4 0 0 1-4 4a4 4 0 0 1-4-4a4 4 0 0 1 4-4m0 10c4.42 0 8 1.79 8 4v2H4v-2c0-2.21 3.58-4 8-4Z"/><path fill="currentColor" d="M12 4a4 4 0 0 0-4 4a4 4 0 0 0 4 4a4 4 0 0 0 4-4a4 4 0 0 0-4-4m0 2a2 2 0 0 1 2 2a2 2 0 0 1-2 2a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 10c-4.42 0-8 1.79-8 4v2h16v-2c0-2.21-3.58-4-8-4m0 2c3.17 0 5.85 1.08 6.7 2H5.3c.85-.92 3.53-2 6.7-2Z"/></svg>
    title: 单渠道多账号(TODO)
    details: 单个支付渠道可以支持多个账号，如微信可以支持多个收款账号
---

