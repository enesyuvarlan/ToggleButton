# ToggleButton
### Preview

![ToggleButton](https://github.com/nsyvrln/ToggleButton/assets/32177958/2609220f-2ecd-49f8-a066-57a12b38c323)

### How To Use
```html
<label>
        <input type="checkbox" />
        <div class="checkbox">
            <span class="check-btn"></span>
        </div>
    </label>
```
```css
label input {
    position: absolute;
    height: 50px;
    width:  50px;
    display: none;
}

.checkbox{
    display: inline-block;
    position: relative;
    height: 118px;
    width: 228px;
    background-color: #DDDDDD;
    border-radius: 60px;
    cursor: pointer;
}

input:checked + .checkbox {
    background-color: #1c89f4;
    transition: 400ms background-color;
}

.checkbox .check-btn {
    position: absolute;
    height: 97px;
    width: 97px;
    top: 9px;
    bottom: 9px;
    left: 9px;
    border-radius: 50%;
    background-color: #F5F5F5;
    box-shadow: inset 0 0 0 5px #fdfdfc, 0 0 9px rgba(0, 0, 0, 0.3);
    transition: 350ms left;
}

label input:checked + .checkbox .check-btn {
    left: 122px;
}
```
