#Compass-Flex

A Compass module to provide the "new" CSS3 Flexbox because Compass use the "old" one

Mixins writes the 2009, 2011 and 2012 (final) syntaxes


## Getting Started

### Install

Download `lib/_flex.scss`

### Install with bower

```
bower install https://github.com/Freddy03h/compass-flex.git --save
```
(Note: Use the github repo link because it not officially registred has a bower component)


## How to use

Don't forget to import the file

### display: flex

```
@include display-flex;
```

### flex-direction
```
@include flex-direction(row);
```
```
@include flex-direction(column);
```

### flex-wrap
```
@include flex-wrap(nowrap);
```
```
@include flex-wrap(wrap);
```

### justify-content
```
@include justify-content(flex-end);
```
```
@include justify-content(center);
```

### align-items
```
@include align-items(flex-end);
```
```
@include align-items(center);
```

### flex
```
@include flex(1);
```
```
@include flex(3);
```
```
@include flex(2 150px);
```