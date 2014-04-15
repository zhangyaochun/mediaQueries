mediaQueries
============

this is a mixin for sass Mobile use media query

```shell
iPad media query

min-device-width: 768px
max-device-width: 1024px

1. iPad1-iPad2
2. iPad3-iPad4 has Retina
```


```shell
iPhone media query

1. iPhone2G-4S

min-device-width: 320px
max-device-width: 480px

Not: iPhone4 and 4S has Retina

2. iPhone5

min-device-width: 320px
max-device-width: 568px

```


```shell
screen

1. {param} $resMin for min-width 
2. {param} $resMax for max-width

@media screen and (min-width: $resMin) and (max-width: $resMax) {
    @content;
}
```


```shell
max-screen

1.{param} $res for max-width 

@media screen and (max-width: $res) {
    @content;
}
```


```shell
min-screen

1.{param} $res for min-width 

@media screen and (min-width: $res) {
    @content;
}
```


```shell
orientation

1.{param} $orientation for orientation

@media screen and (orientation: $orientation) {
    @content;
}
```
