# NGX Focus Point

Websites don't have a single layout any more. The space you have for an image may be portrait on a laptop, landscape on a tablet, and square on a mobile - particularly if you're using a full-screen image.

If you have to use the same image file in all these contexts, you might not be happy with the results you get when you 'fill' the allocated space with your image. Your subject might be clipped or completely missing, or just really awkward looking.

[Demo and Focus Tool](https:believablecreations.com/ngx-focus-point?src=https://66.media.tumblr.com/8fd2436a90888b09af3c1eeefe8ef250/tumblr_p6ud1vgk6g1qjac96o1_1280.jpg).

This component does not rely on jQuery.

Import Module.
```
import {NgxFocusPointModule} from './ngx-focus-point/ngx-focus-point.module';
```

Use 'ngx-focus-point' component.
```
<ngx-focus-point [focusX]="0.0" [focusY]="0.0">
  <img
    src="your-image.jpg"
  />
</ngx-focus-point>
```

Use 'ngx-focus-point-select' component.

```
<ngx-focus-point-select (change)="updateFocus($event)" src="your-image.jpg"></ngx-focus-point-select>
```
 Output() change :{
  x: number;
  y: number;
  h: number;
}
##Believable Creations 
Submit a pull request [Help](https://github.com/LeoCreer/NGX-Focus-Point).


