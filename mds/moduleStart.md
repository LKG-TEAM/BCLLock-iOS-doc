## 只要在application:didFinishLaunchingWithOptions:中</br>[EGRouterManager startAppWithModuleRouter:EGModuleRouter(BCLLockModule)];</br>一行代码调用即可

```objective-c
- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions
{
    [EGRouterManager startAppWithModuleRouter:EGModuleRouter(BCLLockModule)];
    
    return YES;
}
```

