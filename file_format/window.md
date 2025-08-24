# Windows
The root of an application, is, obviously, the window. 
```xml
<window>
    <properties>
        <!-- properties here -->
    </property>
    <content>
        <!-- content of window here -->
</window>
```
The window format consists of 5 properties:
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
<property name="icon">
    <value content="icons/homeWindow.svg">
</property>
```
4. <code>defaultWindow</code>: If this is the default window and it starts up when you run the app.
```xml
<property name="defaultWindow">
    <value content="True">
</property>
```
5. <code>parentWindow</code>: That if the window is deleted, all the other child windows of the application do to. ***<i>Note: If defaultWindow is True, then this has to be true.</i>***
```xml
<property name="parentWindow">
    <value content="True">
</property>
```a