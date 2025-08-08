# 🛍️ Clothing & Accessories Dataset

A **sample JSON dataset** containing clothing, footwear, and accessories information for demo, testing, or prototype e-commerce applications.  
All products include an `image` field already filled with sample image URLs sourced from Google for demonstration purposes.

---

## 📂 Dataset Structure

Each product in the dataset includes:

## 📂 Dataset Structure

Each product in the dataset includes:

| Field       | Type   | TypeScript | Description                                                                                     |
|-------------|--------|------------|-------------------------------------------------------------------------------------------------|
| `id`        | Int | number     | Unique product identifier (integer)                                                            |
| `name`      | String | string     | Name of the product                                                                             |
| `category`  | String | string     | Product category (e.g., Tops, Bottoms, Footwear, Accessories)                                   |
| `size`      | Array  | string[]   | Available sizes                                                                                 |
| `color`     | String | string     | Main color of the product                                                                       |
| `price`     | Float | number     | Price in USD (float for cents)                                                                  |
| `image`     | String | string     | Image URL for product display (already filled with sample URLs)                                 |     |

---

## 📊 Example Entry

```json
{
  "id": 1,
  "name": "Classic White T-Shirt",
  "category": "Tops",
  "size": ["S", "M", "L", "XL"],
  "color": "White",
  "price": 15.99,
  "image": "https://nobero.com/cdn/shop/products white_c26fa070-f26d-4a2f-ba1e-66d2b17a2508.jpg?v=1711979035"
}
```
