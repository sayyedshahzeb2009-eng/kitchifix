# KitchiFix Product Management

KitchiFix is designed so the store owner manages products in Shopify Admin; the theme automatically renders the product data.

## Product workflow

1. Shopify Admin → Products → Add product.
2. Add product title, description, price, compare-at price, images and variants.
3. Set product status to Active.
4. Add the optional custom metafields below.
5. Assign the product to collections such as Best Sellers or New Arrivals.
6. The theme automatically displays the product in collection and featured-product sections.

## Recommended metafields

Create these in Shopify Admin → Settings → Custom data → Products.

| Namespace/key | Type | Purpose |
|---|---|---|
| `custom.badge` | Single line text | Main badge such as BEST SELLER, NEW or LIMITED |
| `custom.badge_2` | Single line text | Optional second badge |
| `custom.short_description` | Multi-line text | One-line benefit shown on cards/product pages |
| `custom.rating` | Single line text | Display rating, e.g. 4.9 ★★★★★ |
| `custom.review_count` | Integer | Review count |
| `custom.features` | List of single-line text | Product benefits/features |
| `custom.shipping_note` | Single line text | Product-specific shipping message |
| `custom.model_3d_url` | URL | Public `.glb` or `.gltf` model URL |

## Example

Title: 5-in-1 Kitchen Organizer

Price: ₹799

Compare-at price: ₹1,499

Badge: BEST SELLER

Short description: Organize five everyday kitchen tools in one compact system.

Rating: 4.9 ★★★★★

Review count: 128

Features:
- Space-saving design
- Easy to clean
- Durable everyday material

Shipping note: Free shipping over ₹999

3D model URL: your public GLB/GLTF URL

## Importing products

For dropshipping, import products through your chosen Shopify-compatible supplier/app or Shopify's product CSV importer. The theme does not store supplier credentials or product data in GitHub. Once products exist in Shopify, KitchiFix reads the standard Shopify product fields and optional metafields above.

## Important

Never put supplier API keys, Shopify Admin API tokens, payment credentials or private customer data into this GitHub repository. Those belong in the relevant Shopify/app secret-management system.
