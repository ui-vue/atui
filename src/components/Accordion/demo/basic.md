---
order: 0
title:
  zh-CN: 基本
  en-US: Type
---

## zh-CN




## en-US




````jsx
<accordion open-one>
  <panel open>
    <div slot="panel-header" class="custom-class">Panel #1</div>
    内容一
  </panel>
  <panel>
    <div slot="panel-header" class="custom-class">Panel #2</div>
    内容二
  </panel>
  <panel>
    <div slot="panel-header" class="custom-class">Panel #3</div>
    内容三
  </panel>
  <panel>
    <div slot="panel-header" class="custom-class">Panel #4</div>
    内容四
  </panel>
</accordion>
````

````vue-script
new Vue({
  el: 'body',
  components: {
    accordion: atui.Accordion,
    panel: atui.Accordion.Panel
  }
})
````
