
## Client

#### Setup 
```html
<script src="https://unpkg.com/htmx.org@1.8.5/dist/htmx.min.js"></script>
```

#### Get DatabaseName
```html
<!-- have a button POST a click via AJAX -->
<button hx-get="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```

#### Get ProviderServiceName
```html
<!-- have a button GET a click via AJAX -->
<button hx-get="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```

#### Get StorageBrowser
```html
<!-- have a button GET a click via AJAX -->
<button hx-get="https://tiddlywiki-store.netlify.app/api/{StorageBrowser}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```

#### POST DatabaseName
```html
<!-- have a button POST a click via AJAX -->
<button hx-post="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```

#### POST ProviderServiceName
```html
<!-- have a button GET a click via AJAX -->
<button hx-post="https://tiddlywiki-store.netlify.app/api/{DatabaseName}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```

#### POST StorageBrowser
```html
<!-- have a button GET a click via AJAX -->
<button hx-post="https://tiddlywiki-store.netlify.app/api/{StorageBrowser}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML"></button>
```
