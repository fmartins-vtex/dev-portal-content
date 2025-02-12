---
title: "Catalog API - Seller Portal - Overview"
slug: "catalog-api-seller-portal-overview"
hidden: false
createdAt: "2021-07-05T14:12:39.168Z"
updatedAt: "2022-11-10T17:09:42.326Z"
---

With the Catalog API for Seller Portal, you will be able to create, edit and consult products and their variations, brands, and categories.

> This API is part of the [Seller Portal Catalog](https://help.vtex.com/en/tutorial/how-the-seller-portal-catalog-works--7pMB6YOt6YQDQQbzFB4Pxp). This functionality is in the Beta stage and can be discontinued at any moment at VTEX's discretion. VTEX will not be responsible for any instabilities caused by its use or discontinuity. If you have any questions, please contact [our Support Center](https://help.vtex.com/support).

## Index

### Product

`GET` [Get Product by ID](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/products/-productId-)
`PUT` [Update Product](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#put-/api/catalog-seller-portal/products/-productId-)
`GET` [Get Product Description by Product ID](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/products/-productId-/description)
`PUT` [Update Product Description by Product ID](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#put-/api/catalog-seller-portal/products/-productId-/description)
`GET` [Get Product by external ID, SKU ID, SKU external ID or slug](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/products/-param-)
`POST` [Create Product](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#post-/api/catalog-seller-portal/products)

### SKU

`GET` [Search for SKU](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/skus/_search)
`GET` [Get List of SKUs](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/skus/ids)

### Brand

`GET` [Get List of Brands](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/brands)
`POST` [Create a Brand](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#post-/api/catalog-seller-portal/brands)
`GET` [Get Brand by ID](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/brands/-brandId-)
`PUT` [Update Brand](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#put-/api/catalog-seller-portal/brands/-brandId-)

### Category

`GET` [Get Category Tree](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/category-tree)
`PUT` [Update Category Tree](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#put-/api/catalog-seller-portal/category-tree)
`GET` [Get Category by ID](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#get-/api/catalog-seller-portal/category-tree/categories/-categoryId-)
`POST` [Create a Category](https://developers.vtex.com/docs/api-reference/catalog-api-seller-portal#post-/api/catalog-seller-portal/category-tree/categories)
