# FoodTuck 🍔  
A dynamic Q-Commerce website designed for delivering freshly prepared meals efficiently, built with **Next.js**, **Tailwind CSS**, and **Sanity.io**.

## 📝 **Project Overview**
FoodTuck provides a seamless experience for users to explore and purchase food items online. The system is powered by an efficient backend using **Sanity.io** for content management and a modern, responsive frontend. 

### **Key Features**
1. **Shop Page Navigation:**  
   - Users can click on the "Shop" link from the navbar to view all available products.
2. **Product Detail View:**  
   - Clicking on a product or the "Add to Cart" icon redirects to the dynamic **Product Detail Page**, displaying product details and similar product suggestions.
3. **Add to Cart:**  
   - Users can add products to the cart directly from the detail page.
4. **Cart Page:**  
   - View, increase, or decrease product quantities in the **Cart Page**.
5. **Checkout Process:**  
   - Upon clicking the "Proceed to Checkout" button, users are directed to the **Checkout Form**, which must be filled completely before submission.
6. **Dynamic Routing:**  
   - Detail pages use dynamic routes based on the product ID.
  
## 🔗 **How It Works**
1. **Backend (Sanity.io)**:
   - Products and their details are managed in Sanity.
   - Data is fetched dynamically using Sanity's APIs.

2. **Frontend (Next.js + Tailwind CSS)**:
   - The Shop page dynamically renders all available products.
   - Product Detail pages fetch product-specific details based on the product ID.
   - Related products are displayed using a filter query.

3. **Cart and Checkout**:
   - Products added to the cart are managed in the state.
   - Quantity adjustments and total price updates are reflected in real-time.
   - Checkout requires form validation before submission.
