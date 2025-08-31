# Buttons
Buttons are one of the most common elements in an application.
```xml
<button>
    <properties>
        <!-- Properties -->
    </properties>
    <!-- No content -->
</button>
```
The button has 8 properties:
1. <code>name</code>: The ID of the button; so it can be accessed in code.
```xml
<property name="name">
    <value content="mybutton">
</property>
```
2. <code>action</code>: The action to perform when the button is clicked.
```xml
<property name="action">
    <value content="submitForm">
</property>
```
3. <code>label</code>: The text displayed on the button.
```xml
<property name="label">
    <value content="Submit">
</property>
```
4. <code>x</code>: The x position of the button.
```xml
<property name="x">
    <value content="15">
</property>
```
5. <code>y</code>: The y position of the button.
```xml
<property name="y">
    <value content="25">
</property>
```
6. <code>width</code>: The width of the button.
```xml
<property name="width">
    <value content="100">
</property>
```
7. <code>height</code>: The height of the button.
```xml
<property name="height">
    <value content="30">
</property>
```
8. <code>style</code>: The style of the button (optional).
```xml
<property name="style">
    <value content="primary">
</property>
```
