---
seoDescription: Use Hot Reload to speed up your mobile app development by instantly updating your UI without rebuilding the entire app.
type: rule
archivedreason:
title: Debugging - Do you use Hot Reload?
guid: e8523286-b3e3-49a1-8a9c-c01b43bc7390
uri: use-hot-reload
created: 2020-10-07T23:15:56.0000000Z
authors:
  - title: Adam Cogan
    url: https://ssw.com.au/people/adam-cogan
  - title: Matt Goldman
    url: https://ssw.com.au/people/matt-goldman
related: []
redirects:
  - do-you-use-hot-reload
---

Developing mobile apps presents unique challenges compared to web or desktop development. One of the problems is that when using MVVM or using dynamic data on a page, you need to run your app to populate the data and see what your UI will actually look like.

<!--endintro-->

::: bad  
![Figure: Bad example - Rebuilding your app every time to see small UI changes](hot-reload-bad.png)  
:::

To get around this problem use Hot Reload. This lets you make changes to your XAML while debugging your app - as soon as you save your UI will update, without having to stop and rebuild your app.

::: good  
![Figure: Good example - Hot reload enable screenshot Windows](hot-reload-good.png)  
:::

**Tip:** This works on the iOS simulator, the Android emulator, and physical iOS and Android devices.
