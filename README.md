# polymer-sw4p-header
A Polymer Web Component written for [sw4pspace.com](https://sw4psapce.com) to create menu and nav bars

## Example
```html
<sw4p-header>
    <a slot="title" href="https://sw4pspace.com">Sw4pSpace</a>
    <div slot="menu">
        <button style="height: 64px; margin: 0;">Home</button>
        <button style="height: 64px; margin: 0;">Team</button>
    </div>
</sw4p-header>
```

## Demo
Run `polymer serve` from root directory.  
Open http://127.0.0.1:8001/components/sw4p-header/demo/ in your browser.