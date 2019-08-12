# email-html

Base de template pour email HTML


## Image

```html
<!--Image-->
<img src="img/image.jpg" width="536" height="100" alt="" style="display: block;" />
```

## Lien

```html
<!--Lien-->
<a href="#" style="color: #ff0000;"><span style="color: #ff0000;">Texte du lien</span></a>
```

> La couleur doit être indiquée une 2ème fois dans un span supplémentaire.

## Texte

```html
<!--Style de texte-->
<p style="font-family: Arial, Helvetica, sans-serif; font-size: 12px; line-height: 18px; font-weight: normal; color: #ff0000; text-align: left; margin: 0;"></p>
```

## Tableau

```html
<table bgcolor="#ffffff" border="0" cellpadding="0" cellspacing="0" width="100%" role="presentation">
  <tr>
    <td align="left" valign="top">

    </td>
  </tr>
</table>
```


## Liste

```css
<!--[if gte mso 9]>
<style>
li {
  text-indent: -1em; /* Normalise space between bullets and text */
}
</style>
<![endif]-->
```

```html
<!--Liste-->
<ul style="padding: 0; Margin: 0 0 0 40px;">
    <li style="Margin: 0 0 10px 0">Will look the same</li>
    <li style="Margin: 0 0 10px 0">Across all mail clients</li>
</ul>
```



