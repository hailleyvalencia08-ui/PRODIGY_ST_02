# Task‑02 Report: Compatibility Testing for Demo E‑Commerce Website

## 🔍 Objective
To evaluate the demo e‑commerce website across multiple browsers (Chrome, Firefox, Safari, Edge) and devices (desktop, tablet, mobile) for layout consistency, broken links, and functionality discrepancies.

---

## 🖥️ Test Environment
- **Browsers Tested:** Chrome v124, Firefox v126, Safari v17, Edge v124
- **Devices Tested:** Windows 10 Desktop, iPad Tablet, Android Mobile, iPhone Mobile
- **Network:** Stable Wi‑Fi connection

---

## 🧪 Findings

### 1. Layout Issues
- **Mobile (Safari/iPhone):** Product grid overlaps when screen width < 375px.  
- **Tablet (Firefox/iPad):** Navigation bar misaligned; “Cart” button shifts below menu.  
- **Desktop (Edge):** Footer text appears stretched on 4K resolution.

### 2. Broken Links
- **Contact Us page:** Link in footer redirects to a 404 error.  
- **Social Media icons:** Instagram icon does not open any page.

### 3. Functionality Discrepancies
- **Search Bar (Firefox):** Enter key does not trigger search; only clicking the button works.  
- **Add to Cart (Safari Mobile):** Item added but cart count does not update until page refresh.  
- **Checkout Form (Chrome Desktop):** “State” dropdown does not load options consistently.

---

## 📸 Evidence
Screenshots of layout overlaps, broken links, and cart issues are stored in the `/screenshots` folder.

---

## ✅ Recommendations
1. **Responsive Design Fixes:**  
   - Use CSS media queries for small screen widths (<375px).  
   - Adjust flexbox/grid layout for tablet navigation bar.  

2. **Broken Link Resolution:**  
   - Update footer “Contact Us” link to correct URL.  
   - Ensure all social media icons are mapped to valid pages.  

3. **Functionality Improvements:**  
   - Debug search bar input handling in Firefox.  
   - Fix cart count update with AJAX refresh for Safari.  
   - Validate dropdown population logic in checkout form.

---

## 📌 Conclusion
The demo e‑commerce website works well on most platforms but requires fixes for mobile responsiveness, broken links, and minor functionality discrepancies. Addressing these issues will improve user experience and ensure cross‑browser compatibility.
