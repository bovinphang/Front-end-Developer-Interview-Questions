# hello-world
first project test



<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <!-- Angular Material style sheet -->
    <link rel="stylesheet" href="../../components/common/css/angular-material.css">
</head>
<body ng-app="MyApp" ng-cloak>
<!--
  Your HTML content here
-->
<div ng-controller="DemoCtrl as ctrl">
    <ul>
        <li>
            <span>Nexus S</span>
            <p>
                Fast just got faster with Nexus S.
            </p>
        </li>
        <li>
            <span>Motorola XOOM™ with Wi-Fi</span>
            <p>
                The Next, Next Generation tablet.
            </p>
        </li>
    </ul>
    <p>Total number of phones: 2</p>
</div>
<!-- Angular Material requires Angular.js Libraries -->
<script src="../../components/common/js/lib/angular.min.js"></script>
<script src="../../components/common/js/lib/angular-animate.min.js"></script>
<!-- 动画模块 -->
<script src="../../components/common/js/lib/angular-aria.min.js"></script>
<!-- 富互联网应用模块 -->
<script src="../../components/common/js/lib/angular-messages.min.js"></script>
<!-- 表单验证模块 -->

<!-- Angular Material Library -->
<script src="../../components/common/js/lib/angular-material.js"></script>

<!-- Your application bootstrap  -->
<script src="./TestController.js" type="text/javascript"></script>

</body>
</html>

