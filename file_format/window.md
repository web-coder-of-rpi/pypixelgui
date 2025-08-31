# Windows
The root of an application, is, obviously, the window. 
```xml
<window>
    <properties>
        <!-- properties here -->
    </property>
    <content>
        <!-- content of window here -->
    </content>
</window>
```
The window format consists of 7 properties:
1. <code>windowTitle</code>: This is the title of the window when activated.
```xml
<property name="windowTitle">
    <value content="My Window">
</property>
```
2. <code>width</code>: The width of the window.
```xml
<property name="width">
    <value content="300">
</property>
```
3. <code>height</code>: The height of the window.
```xml
<property name="height">
    <value content="400">
</property>
```
4. <code>defaultWindow</code>: If this is the default window and it starts up when you run the app.
```xml
<property name="defaultWindow">
    <value content="True">
</property>
```
5. <code>parentWindow</code>: That if the window is deleted, all the other child windows of the application do to. ***<h4><i>Note: If defaultWindow is True, then this has to be true.</i></h4>***
```xml
<property name="parentWindow">
    <value content="True">
</property>
```
6. <code>icon</code>: The icon of the window.
```xml
<property name="icon">
    <value content="icons/main_window_icon.svg">
</property>
```
7. <code>name</code>: The ID of the window.
```xml
<property name="name">
    <value content="mywindow">
</property>
```
