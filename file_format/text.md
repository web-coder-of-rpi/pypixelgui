# Text
About every application uses non-interactive text boxes.
```xml
<textbox>
    <properties>
        <!-- Properties here -->
    </properties>
    <!-- No content tag -->
</textbox>
The textbox has 7 properties:
1. <code>name</code>: The ID of the textbox; so it can be accessed in code.
```xml
<property name="name">
    <value content="mytextbox">
</property>
```
2. <code>renderType</code>: The language format to render.
```xml
<property name="renderType">
    <value content="html">
</property>
```
3. <code>content</code>: The content to be displayed in the value of renderType.
```xml
<property name="content">
    <value content="<p style='color: red;'>Hello!!!</p>">
</property>
```
4. <code>x</code>: The x position of the textbox.
```xml
<property name="x">
    <value content="10">
</property>
```
5. <code>y</code>: The y position of the textbox.
```xml
<property name="y">
    <value content="20">
</property>
```
6. <code>width</code>: The width of the textbox.
```xml
<property name="width">
    <value content="200">
</property>
```
7. <code>height</code>: The height of the textbox.
```xml
<property name="height">
    <value content="40">
</property>
```