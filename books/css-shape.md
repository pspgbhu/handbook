# CSS Shape

- 一个叉叉，带圆形底色

```css
.icon-close {
  position: absolute;
  right: 48px;
  top: 30px;
  display: inline-block;
  transform: rotate(45deg);
  color: #fff;
  border-radius: 50%;
  width: 32px;
  height: 32px;
  vertical-align: middle;
  background: #999;
}
.icon-close::before, .icon-close::after {
  content: '';
  display: block;
  position: absolute;
  left: 16px;
  top: 16px;
  transform: translate(-50%, -50%);
  box-shadow: inset 0 0 0 32px;
}
.icon-close::before {
  display: block;
  width: 20px;
  height: 1px;
}
.icon-close::after {
  display: block;
  width: 1px;
  height: 20px;
}
```
