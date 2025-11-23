
> **Note:** `173573538039` is the original theme.  
> Make sure to **create a Git branch first**, then connect that theme on Shopify.  
> Do all development on the **staging theme**, not the live one.

---

# ✨ Front-end Preview

https://cuff-collection-test.myshopify.com/products/cuff-ring

---

# ✨ Files

### **sections/**
- `hero-product.liquid`  
- `customize-section.liquid` — (Customise section)  
- `timeless-elegance.liquid` — (Timeless Elegance)

### **snippets/**
- `product-hero.liquid`  
- `product-info-variants.liquid`

### **Product Template**
- `templates/product.cuff-new-tp.json`

---

# ✨ Developer’s POV

## ✨ Design Decisions
- **90% pixel-perfect implementation**  

---

# ✨ Challenges Faced — Blockages

### **Product Featured section**  
The design was **not followed exactly** because it does not look good on desktop when implemented literally.

Bad result when following the exact design:  
https://www.awesomescreenshot.com/image/57564352?key=a3683ae9e1b3bbb78de2c988574992b5

Improved and polished version (with correct padding rules):  
https://www.awesomescreenshot.com/image/57564357?key=e50b09c25a58f1379cf5dd43f7a21c60

This follows proper CSS spacing because the two variants are different.

---

### **Reasons for the Decision**

To simplify development and avoid maintaining two separate codebases for desktop and mobile:

- A modified version of the layout was created instead of strictly following the Figma design.  
- This keeps the structure cleaner and reduces repetitive markup.  
- It makes styling easier to manage.  
- Ensures responsiveness across all devices.  
- Avoids overly long or duplicated code.

---

# 👤 Author
Maricon Espinosa

**Maricon Espinosa**
