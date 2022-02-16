# Cuppa Elements

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/cuppajs-elements)

Standard web components based on lit-html and free of dependencies.

# Documentation

Doc [http://cuppajs.cloudbit.co/](https://cuppajs.cloudbit.co/) <br />
Git [https://github.com/cloudbit-interactive/cuppajs](https://github.com/cloudbit-interactive/cuppajs) <br />
Npm [https://www.npmjs.com/package/cuppajs](https://www.npmjs.com/package/cuppajs) <br />
WebComponents [https://www.webcomponents.org/element/cuppajs-elements](https://www.webcomponents.org/element/cuppajs-elements)

# cuppa-alert (~9kB)
<!--
```
<custom-element-demo height="300">
  <template>
    <style> body, html{ font-family:arial; } </style>
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

# cuppa-switch (~6.3kB)
<!--
```
<custom-element-demo>
  <template>
    <script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.switch.min.js" type="module"></script>
    <cuppa-switch name="switch" onchange="console.log(this.checked, this.name)"></cuppa-switch>
  </template>
</custom-element-demo>
```
-->

# cuppa-tabs (~6.3kB)
<!--
```
<custom-element-demo>
  <template>
    <style> body, html{ font-family:arial; } </style>
    <script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.tabs.min.js" type="module"></script>
    <cuppa-tabs selected="microsoft" onchange="console.log(this.selected)" >
      <cuppa-tab value="apple" >Apple</cuppa-tab>
      <cuppa-tab value="microsoft" >Microsoft</cuppa-tab>
      <cuppa-tab value="google" >Google</cuppa-tab>
    </cuppa-tabs>
  </template>
</custom-element-demo>
```
-->
# cuppa.collapsible (~40kB)
<!--
```
<custom-element-demo>
  <template>
    <style> body, html{ font-family:arial; } </style>
    <script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.collapsible.min.js" type="module"></script>
    
    <cuppa-collapsible 
      header="Collapsible Title 1"
      content="Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum."
      group="collapsible-group-1"
      name="collapsible-1"
    ></cuppa-collapsible>
    <cuppa-collapsible 
      group="collapsible-group-1"
      name="collapsible-2"
    >
      <cuppa-collapsible-header>Collapsible Title 2</cuppa-collapsible-header>
      <cuppa-collapsible-content>
        <h3 class="title-3">My Title Content</h3>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      </cuppa-collapsible-content>
    </cuppa-collapsible>
    <cuppa-collapsible
      group="collapsible-group-1"
      name="collapsible-3"
    >
      <cuppa-collapsible-header>Collapsible Title 3</cuppa-collapsible-header>
      <cuppa-collapsible-content>
        <img width="100%" height="auto" src="https://cdn.pixabay.com/photo/2016/12/13/05/15/puppy-1903313__340.jpg" />
      </cuppa-collapsible-content>
    </cuppa-collapsible>
  </template>
</custom-element-demo>
```
-->
# cuppa.drawer (~42kB)
<!--
```
<custom-element-demo height="300">
  <template>
    <style> body, html{ font-family:arial; } </style>
    <script src="https://cdn.jsdelivr.net/npm/cuppajs/libs/components/cuppa.drawer.min.js" type="module"></script>
    <cuppa-drawer id="drawer" position="right">
      <cuppa-drawer-content style="display:flex; height: 100%; flex-direction: column; padding:10px;">
        <h1 style="margin:0">Menu</h1>
        <ul>
          <li>Item 1</li>
          <li>Item 2</li>
        </ul>
      </cuppa-drawer-content>
    </cuppa-drawer>

    <button id="btnOpen">Open Drawer</button>
    <script>
    	let drawer = document.getElementById("drawer");
    	document.getElementById("btnOpen").onclick = ()=>drawer.open();
    </script>
  </template>
</custom-element-demo>
```
-->
