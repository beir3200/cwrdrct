[![bower version](https://img.shields.io/bower/v/k-redirect.svg)](https://libraries.io/bower/k-redirect) 
[![open issues](https://img.shields.io/github/issues/k4ng%2Fk-redirect.svg)](https://github.com/k4ng/k-redirect/issues) 
[![npm](https://img.shields.io/npm/v/k-redirect.svg)](https://www.npmjs.com/package/k-redirect) 
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://github.com/k4ng/k-redirect) 


# \<k-redirect\>

a simple component for redirect page.


<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="k-redirect.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<k-redirect mode="off" to="https://github.com/k4ng/k-redirect"></k-redirect>
<p>
    Remove property <code>mode="off"</code> or change value property from OFF to ON. 
    Result, the component will automatically redirect the page to 
    <code>https://github.com/k4ng/k-redirect</code> in 10 milliseconds (0.01 sec)
</p>
```


## How to install

### bower

```markdown
bower install --save k-redirect
```

### npm

```markdown
npm install k-redirect
```


## Properties

Data Attribute | Description | Default Value
-------------- | ----------- | -------------
to | to set the destination URL | http://www.kang-cahya.com 
time | to set speed redirect. Unit within a millisecond. Tips:: 1000 milliseconds = 1 second | 10 milliseconds
mode | to set redirect mode "ON" or "OFF" | ON


## Contributing

1. Fork it!
1. Create your feature branch: git checkout -b my-new-feature
1. Commit your changes: git commit -m 'Add some feature'
1. Push to the branch: git push origin my-new-feature
1. Submit a pull request :D


## License

[MIT License](https://github.com/dyazincahya/k-redirect/blob/master/LICENSE) 
