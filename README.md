# Product Card Component

A responsive, display-only React component for showcasing products with image, name, price, rating, description, and optional badges.

## Features

- ✅ Static component with JSX structure
- ✅ Props for name, price, image, rating, and description
- ✅ Display-only without state management
- ✅ Badge support for "on sale" or "new arrival"
- ✅ Responsive layout with Tailwind CSS
- ✅ Star rating visualization

## Props

| Prop          | Type           | Default                  | Description                        |
| ------------- | -------------- | ------------------------ | ---------------------------------- |
| `name`        | string         | "Product Name"           | Product name                       |
| `price`       | number         | 99.99                    | Product price                      |
| `image`       | string         | placeholder image        | Product image URL                  |
| `rating`      | number         | 4.5                      | Rating from 0-5                    |
| `description` | string         | "A wonderful product..." | Product description                |
| `badge`       | string         | new                      | Badge type: "sale", "new"          |
| `ratingCount` | number         | 0 | Product rating count  |

## Usage

```jsx
<ProductCard
  name="Wireless Headphones"
  price={1259}
  image="https://example.com/headphones.jpg"
  rating={4.5}
  description="Premium sound quality with active noise cancellation"
  badge="sale"
  ratingCount={110}
/>
```
