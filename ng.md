# 在angularjs中插入不安全的外部代码
```
<script src="http://cdn.bootcss.com/angular.js/1.5.0/angular-sanitize.min.js"></script>
```

```
angular.module('app',["ngSanitize"]);
```


```

ng-bind-html="d.body"
```

