# Text
About every application uses non-interactive text boxes.
```xml
<textbox>
    <properties>
        <!-- Properties here -->
    </properties>
    <!-- No content tag -->
</textbox>
The textbox has 3 properties:
1. <code>name</code>: The ID of the textbox; so it can be accessed in code.
```xml
<property name="name">
    <value content="mytextbox">
</property>
2. <code>renderType</code>: The language format to render.
```xml
<property name="renderType">
    <value content="html">
</property>
3. <code>content</code>: The content to be displayed in the value of renderType.
```xml
<property name="content">
    <value content="<p style='color: red;'>Hello!!!</p>">
</property>