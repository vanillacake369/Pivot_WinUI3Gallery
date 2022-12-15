
<p align="center">
<img src="https://user-images.githubusercontent.com/75259783/207767271-4e8a6034-88d3-48dc-b41a-b54f72d4be0f.gif">
</p>

```xaml
<Pivot .../>
-or-
<Pivot ...>
  oneOrMorePivotItems
</Pivot>
```
위와 같은 코드 형식을 통해 아래와 같이 코딩해줍니다.
**MainWindow.xaml**
```xaml

<StackPanel>
        <Pivot Title="EMAIL" MinHeight="400">
            <PivotItem Header="All">
                <TextBlock Text="all emails go here." />
            </PivotItem>
            <PivotItem Header="Unread">
                <TextBlock Text="unread emails go here." />
            </PivotItem>
            <PivotItem Header="Flagged">
                <TextBlock Text="flagged emails go here." />
            </PivotItem>
            <PivotItem Header="Urgent">
                <TextBlock Text="urgent emails go here." />
            </PivotItem>
        </Pivot>
    </StackPanel>

```

이후 MainWindow.xaml.cpp와 MainWindow.xaml.h에서 Init에 관한 코드를 작성해줍니다.


---
참고자료
Learn more about Windows App SDK here:
https://docs.microsoft.com/windows/apps/windows-app-sdk/
Pivot 참고코드
https://github.com/microsoft/WinUI-Gallery/blob/main/WinUIGallery/ControlPages/ProgressRingPage.xaml.cs
https://github.com/microsoft/WinUI-Gallery/blob/main/WinUIGallery/ControlPages/ProgressRingPage.xaml
Learn more about WinUI3 here:
https://docs.microsoft.com/windows/apps/winui/winui3/
Learn more about C++/WinRT here:
http://aka.ms/cppwinrt/
---


