# Useful extensions for BulmaCSS

Especially for Rails, I've found that these, the bulma-rails and font-awesome-rails are the most bulletproof way to set this up and not have boring lookalike Rails/Bootstrap apps.

Note that for the Rails flash messages to be dismissable just tag them with this JavaScript:

```javascript
onClick="document.getElementById('notificationMessage').classList.remove('is-active')">
```

That just strips the 'is-active' tag from the modal and hides it.

See the giantravens/rails5template for an example of it all working together.
