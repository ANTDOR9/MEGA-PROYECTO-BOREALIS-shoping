 ```
/tienda-web
├── /frontend
│   ├── /public
│   ├── /src
│   │   ├── /components
│   │   │   ├── /ui           # Botones, inputs, modals (reusables)
│   │   │   ├── /layout       # Header, Footer, Sidebar
│   │   │   ├── /products     # ProductCard, ProductGrid, Filters
│   │   │   ├── /cart         # CartItem, CartSummary
│   │   │   ├── /checkout     # Steps, PaymentForm, AddressForm
│   │   │   ├── /user         # ProfileCard, OrderHistory
│   │   │   └── /admin        # AdminPanel, StatsCard
│   │   ├── /pages
│   │   │   ├── /public       # Home, Catalog, Product, Cart
│   │   │   ├── /auth         # Login, Register, ForgotPassword
│   │   │   ├── /user         # Profile, Orders, Wishlist
│   │   │   └── /admin        # Dashboard, Products, Orders, Users
│   │   ├── /hooks            # Custom React hooks
│   │   ├── /utils            # Helpers, formatters, validators
│   │   ├── /services         # API calls, axios config
│   │   ├── /store            # Zustand/Redux (global state)
│   │   ├── /types            # TypeScript interfaces
│   │   └── /assets
│   │       ├── /fonts
│   │       ├── /icons
│   │       └── /styles       # Global, variables, mixins
│   └── theme.json
│
├── /backend
│   ├── /src
│   │   ├── /controllers
│   │   │   ├── auth.controller.js
│   │   │   ├── product.controller.js
│   │   │   ├── cart.controller.js
│   │   │   ├── order.controller.js
│   │   │   ├── user.controller.js
│   │   │   ├── admin.controller.js
│   │   │   └── upload.controller.js
│   │   ├── /models
│   │   │   ├── User.model.js
│   │   │   ├── Product.model.js
│   │   │   ├── Category.model.js
│   │   │   ├── Order.model.js
│   │   │   ├── Cart.model.js
│   │   │   └── Review.model.js
│   │   ├── /routes
│   │   │   ├── /api
│   │   │   │   ├── index.js
│   │   │   │   ├── auth.routes.js
│   │   │   │   ├── products.routes.js
│   │   │   │   └── ...
│   │   │   └── /admin        # Rutas protegidas admin
│   │   ├── /middlewares
│   │   │   ├── auth.middleware.js
│   │   │   ├── admin.middleware.js
│   │   │   ├── validation.middleware.js
│   │   │   ├── error.middleware.js
│   │   │   └── upload.middleware.js
│   │   ├── /services
│   │   │   ├── email.service.js
│   │   │   ├── payment.service.js
│   │   │   ├── storage.service.js
│   │   │   └── analytics.service.js
│   │   ├── /utils
│   │   │   ├── validators.js
│   │   │   ├── generators.js   # IDs, códigos
│   │   │   └── formatters.js
│   │   └── /config           # Database, auth, server config
│   ├── /tests
│   │   ├── unit
│   │   └── integration
│   └── package.json
│
├── /database
│   ├── /migrations
│   ├── /seeds
│   └── /scripts             # Backup, restore scripts
│
├── /storage
│   ├── /uploads
│   │   ├── /products
│   │   │   ├── /{id}
│   │   │   │   ├── main.jpg
│   │   │   │   ├── gallery-1.jpg
│   │   │   │   └── thumbnails/
│   │   │   └── /temp        # Uploads temporales
│   │   ├── /banners
│   │   ├── /logos
│   │   └── /avatars
│   └── /exports             # CSV, reportes
│
├── /config
│   ├── store.json
│   ├── permissions.json
│   ├── layout.json
│   ├── shipping.json        # Zonas, precios, proveedores
│   ├── payment.json         # Métodos config
│   └── email-templates.json
│
├── /docs
│   ├── API.md
│   ├── SETUP.md
│   └── DEPLOYMENT.md
│
├── /scripts
│   ├── deploy.sh
│   ├── backup.sh
│   └── seed-data.sh
│
├── docker-compose.yml
├── README.md
└── .env.example
 ```
