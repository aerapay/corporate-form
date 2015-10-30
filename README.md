# Aerapay Corporate Form

The Aerapay Corporate Registration Form is a snippet which can be implemented on a corporate website to permit consumer registration for Aerapay Corporate accounts.

## Documentation

### init(options)

Initializes the corporate form.

__Options__

* `accessToken` - Required. Aerapay API access token.
* `element` - Optional. Defines the selector the form would be added to (Default: '#customer-form-container')
* `styles` - Optional. Custom styles for the form can be added here

__Example__

```html
<div id="customer-form-container"></div>

<script src="https://app.aerapay.com/widgets/customer-form.js" charset="utf-8"></script>
<script type='text/javascript'>
    Aerapay.CustomerForm.init({
        accessToken: 'TOKEN'
    });
</script>
```
