
The Flutter Mall case demo supports Android, iOS and Web (the web version code is in the web branch, you can use your mobile phone to visit http://success-together/Flutter-shopping-app to experience): the main functions include
- Multi-floor display on the homepage, floor entry viewport animation,
- Search Prompt list, search result list.
- Elastic sliding of category pages
- discover large list,
- ScopeModel state management cart,
- Internationalization support, screen adaptation, etc.



Due to screenshot recording, the actual running effect should be smoother, and there is no obvious difference between the experience of animation, sliding, routing transition and other effects compared with native. **The simulation data used in the project is only for technical research**

After packaging, the android APK size is 6M, and the package size for ios is 12M

Android apk can be scanned and downloaded (please compile the iOS version by yourself)

![](/screenshot/qrcode.png)

- 1. Home page + search Judging that the component appears on the screen, adding animation, sliding the home page with multiple tabs to load the image list, and the search function, the height of the built-in bottombar is not appropriate, customize the BottomBar


![](/screenshot/1.gif)


Hero and PageView implement picture preview

![](/screenshot/5.gif)


- 2. Product category page, elastic sliding pagination


![](/screenshot/2.gif)


- 3. Discover a large list of pictures and texts


![](/screenshot/3.gif)


- 4. Shopping cart scopeModal realizes state management


![](/screenshot/4.gif)