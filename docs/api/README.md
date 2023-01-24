# API & Settings

## Client
```html
<script src="https://unpkg.com/htmx.org@1.8.5/dist/htmx.min.js"></script>
<!-- have a button POST a click via AJAX -->
<div hx-{get|post}="https://tiddlywiki-store.netlify.app/api/{send|get}/{databaseName|serviceDatabase|}/{first|latest|all|list|view}" hx-value={obj|json|xml|html|txt} hx-swap="outerHTML">
</div>
```

## Server
### Get all database-type 
GET: `api/database-type/` or `https://tiddlywiki-store.netlify.app/api/database-type/`

### Get a specific database-type  
GET: `api/database-type/id` or `https://tiddlywiki-store.netlify.app/api/database-type/`

### Create a new database-type 
POST: `api/database-type` or `https://tiddlywiki-store.netlify.app/api/database-type/`

### Update an existing database-type
PUT: `api/database-type/id` or `https://tiddlywiki-store.netlify.app/api/database-type/`

###  Delete an existing database-type
DELETE: `api/database-type/id` or `https://tiddlywiki-store.netlify.app/api/database-type/`

### Get all protocol-networking 
GET: `api/protocol-networking-type/` or `https://tiddlywiki-store.netlify.app/api/protocol-networking-type/`

### Get a specific protocol-networking  
GET: `api/protocol-networking-type/id` or `https://tiddlywiki-store.netlify.app/api/protocol-networking-type/`

### Create a new protocol-networking 
POST: `api/protocol-networking-type` or `https://tiddlywiki-store.netlify.app/api/protocol-networking-type/`

### Update an existing protocol-networking
PUT: `api/protocol-networking-type/id` or `https://tiddlywiki-store.netlify.app/api/protocol-networking-type/`

###  Delete an existing protocol-networking
DELETE: `api/protocol-networking-type/id` or `https://tiddlywiki-store.netlify.app/api/protocol-networking-type/`

### Get all service-provider-type 
GET: `api/service-provider-type/` or `https://tiddlywiki-store.netlify.app/api/service-provider-type/`

### Get a specific service-provider-type  
GET: `api/service-provider-type/id` or `https://tiddlywiki-store.netlify.app/api/service-provider-type/`

### Create a new service-provider-type 
POST: `api/service-provider-type` or `https://tiddlywiki-store.netlify.app/api/service-provider-type/`

### Update an existing service-provider-type
PUT: `api/service-provider-type/id` or `https://tiddlywiki-store.netlify.app/api/service-provider-type/`

###  Delete an existing service-provider-type
DELETE: `api/service-provider-type/id` or `https://tiddlywiki-store.netlify.app/api/service-provider-type/`
