# Cuppa Elements

Standard web components implementation based on lit-html and observables and free of dependencies.

<!--
```
<custom-element-demo>
  <template>
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
