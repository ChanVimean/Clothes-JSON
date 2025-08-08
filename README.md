# 🛍️ Clothing & Accessories Dataset

A **sample JSON dataset** containing clothing, footwear, and accessories information for demo, testing, or prototype e-commerce applications.  
All products include an `image` field already filled with sample image URLs sourced from Google for demonstration purposes.

---

## 📂 Dataset Structure

Each product in the dataset includes:

| Field      | Type    | Description                                                   |
| ---------- | ------- | ------------------------------------------------------------- |
| `id`       | Integer | Unique product identifier                                     |
| `name`     | String  | Name of the product                                           |
| `category` | String  | Product category (e.g., Tops, Bottoms, Footwear, Accessories) |
| `size`     | Array   | Available sizes                                               |
| `color`    | String  | Main color of the product                                     |
| `price`    | Float   | Price in USD                                                  |
| `image`    | String  | Image URL (left empty for you to fill)                        |

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
