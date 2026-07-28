---
title: "Shop"
permalink: /shop/
classes: wide
---

Welcome to my shop! Every item is 3D printed to order in Delaware. Ships via USPS Ground Advantage.

<div class="shop-grid">
{% for product in site.products %}
  <a class="shop-card" href="{{ product.url | relative_url }}">
    {% if product.thumbnail %}
      <img src="{{ product.thumbnail | relative_url }}" alt="{{ product.title }}">
    {% endif %}
    <div class="shop-card-body">
      <h3 class="shop-card-title">{{ product.title }}</h3>
      <p class="shop-card-price">${{ product.price }}</p>
    </div>
  </a>
{% endfor %}
</div>

<style>
.shop-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  gap: 1.5em;
  margin-top: 2em;
}
.shop-card {
  display: block;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  text-decoration: none !important;
  color: inherit !important;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
  background: #fff;
}
.shop-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.08);
}
.shop-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
}
.shop-card-body {
  padding: 1em;
}
.shop-card-title {
  margin: 0 0 0.4em 0;
  font-size: 1.1em;
  line-height: 1.3;
}
.shop-card-price {
  margin: 0;
  font-weight: 600;
  color: #444;
}
</style>
