---
layout: post
title:  Fortigate Authentication
date: 2017-08-20 21:20:10
categories: 安全产品
tags: Fortigate Authentication
excerpt: Fortigate的用户管理认证特性。
---

# 认证的方法
1. 本地密码认证
2. 服务器密码认证
```
   FortiAuthenticator服务器
   Radius服务器
   LDAP服务器
   TACACS+服务器
   POP3服务器
   SSO服务器--FSSO
   RSA ACE (SecurID)服务器
```
3. 证书认证
4. 双因子认证

# 认证的类型
## 安全策略的认证
1. FSO
2. NTLM
3. 证书
4. Radius SSO
5. FortiGuard Web Filter override authentication

## VPN客户端的认证
1. IPSec对端认证
2. IPSec用户认证
3. SSLVPN用户认证
4. PPTP&L2TP用户认证

## 单点登陆认证

# 用户视角的认证
1. 基于web的认证
2. 基于VPN客户端的认证

#用户和用户组
## 用户类型
1. 本地用户
2. authentication server上的远程用户
3. FSSO用户
4. PKI用户
5. IM用户
6. 访客

# SSO
1. AD SSO
```
   查询windows server上的登陆事件，解析workstaion的名字和ip，查询域控服务器上的该用户所属的用户组。
```
2. 基于代理的SSO
```
   Domain Controller (DC) agent
   eDirectory agent
   Citrix/Terminal Server (TS) agent
   Collector (CA) agent
```
3. NTLM
4. Radius SSO


