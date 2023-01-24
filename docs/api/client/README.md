
## Client

#### Setup 
```html
<script src="https://unpkg.com/htmx.org@1.8.5/dist/htmx.min.js"></script>
```

#### Get DatabaseName
```html
<!-- have a button POST a click via AJAX -->
<div hx-get="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

#### Get ProviderServiceName
```html
<!-- have a button GET a click via AJAX -->
<div hx-get="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

#### Get StorageBrowser
```html
<!-- have a button GET a click via AJAX -->
<div hx-get="https://tiddlywiki-store.netlify.app/api/{StorageBrowser}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

#### POST DatabaseName
```html
<!-- have a button POST a click via AJAX -->
<div hx-post="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

#### POST ProviderServiceName
```html
<!-- have a button GET a click via AJAX -->
<div hx-post="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

#### POST StorageBrowser
```html
<!-- have a button GET a click via AJAX -->
<div hx-post="https://tiddlywiki-store.netlify.app/api/{StorageBrowser}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```
