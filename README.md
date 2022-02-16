# Cuppa Elements

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/cuppajs-elements)

Standard web components based on lit-html and free of dependencies.

# Documentation
[Online: http://cuppajs.cloudbit.co/](https://cuppajs.cloudbit.co/)

<!--
```
<custom-element-demo>
  <template>
    <style>
      body, html{ font-family:arial; }
    </style>
    <script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.alert.min.js" type="module"></script>
    <cuppa-alert 
        title="Message" 
        message="What is your name?" 
        input-text="" 
        cancel-text="Cancel" 
        onclose="console.log(this.value, this.inputText)" >
    </cuppa-alert>
  </template>
</custom-element-demo>
```
-->
```html
<script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.alert.min.js" type="module"></script>
<cuppa-alert 
    title="Message" 
    message="What is your name?" 
    input-text="" 
    cancel-text="Cancel" 
    onclose="console.log(this.value, this.inputText)" >
</cuppa-alert>
```
