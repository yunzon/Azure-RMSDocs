---
title: class mip::AuthDelegate::OAuth2Token 
description: Documents the mip::authdelegate class of the Microsoft Information Protection (MIP) SDK.
author: msmbaldwin
ms.service: information-protection
ms.topic: reference
ms.author: mbaldwin
ms.date: 10/29/2019
---

# class mip::AuthDelegate::OAuth2Token 
A class defining how the MIP SDK expects the oauth2 token to be passed back into the SDK.
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public OAuth2Token()  |  Construct a new OAuth2Token object.
public OAuth2Token(const std::string& accessToken)  |  Construct a new OAuth2Token object from an accessToken.
public const std::string& GetAccessToken() const  |  Get the Access token string.
public void SetAccessToken(const std::string& accessToken)  |  Set the Access Token string.
  
## Members
  
### OAuth2Token function
Construct a new OAuth2Token object.
  
### OAuth2Token function
Construct a new OAuth2Token object from an accessToken.

Parameters:  
* **accessToken**: The actual access token passed into the SDK.


  
### GetAccessToken function
Get the Access token string.

  
**Returns**: The access token string.
  
### SetAccessToken function
Set the Access Token string.

Parameters:  
* **accessToken**: the access token string.

