# Aerapay Corporate Form

The Aerapay Corporate Form is a snippet which can be implemented on any corporate website to let customers of this corporate directly register.

## Documentation

### init(options)

Initializes the corporate form.

__Options__

* `corporate` - Mandatory. Defines the name of the corporate, which the customers are registered to (has to be the corporate name of the Aerapay Account)
* `element` - Optional. Defines the selector the form would be added to (Default: '#customer-form-container')
* `styles` - Optional. Custom styles for the form can be added here

__Example__

```html
<div id="customer-form-container"></div>

<script src="https://app.aerapay.com/widgets/customer-form.js" charset="utf-8"></script>
<script type='text/javascript'>
    Aerapay.CustomerForm.init({
        corporate: 'Example Company'
    });
</script>
```
