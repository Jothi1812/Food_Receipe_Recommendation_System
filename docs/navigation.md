# 🧭 **Navigation Flow for Food Recipe Recommendation System**

This document describes the detailed navigation flow between various pages in the Food Recipe Recommendation System.

---

## 1️⃣ **Homepage (Welcome Page)**
- **Objective:** Allow users to input available ingredients and receive recipe suggestions.
- **Navigation Options:**  
  - 🔍 **Search Bar:** Enter ingredients → Redirect to **Recipe Suggestions Page** with matching recipes.
  - 🔑 **Login/Sign Up:** Redirect to **Login/Sign-Up Page**.
  - ⭐ **My Favorites:** (Visible only if logged in) Redirect to **Favorites Page**.
  - 📜 **Navigation Bar Links:** Home, Profile, Favorites, Logout (if logged in).
  
---

## 2️⃣ **Login/Sign-Up Page**
- **Objective:** Enable user authentication and account creation.
- **Navigation Options:**  
  - 🏠 **Back to Homepage:** Click the logo or navigation link to return to **Homepage**.
  - 🔓 **Login Button:** Successful login → Redirect to **Recipe Suggestions Page**.
  - 📝 **Sign-Up Button:** Successful sign-up → Redirect to **Profile Page** for user setup.

---

## 3️⃣ **Recipe Suggestions Page**
- **Objective:** Display recipe recommendations based on user-input ingredients.
- **Navigation Options:**  
  - 🖼️ **Recipe Cards:** Click on any recipe → Redirect to **Recipe Details Page**.
  - 🔧 **Filter & Sorting Options:** Update the displayed recipe list dynamically.
  - ⭐ **Save to Favorites:** Save recipe → Redirect or update **Favorites Page**.
  - 🔙 **Back to Homepage:** Navigation link returns user to **Homepage**.

---

## 4️⃣ **Recipe Details Page**
- **Objective:** Display detailed information about a selected recipe.
- **Navigation Options:**  
  - ⭐ **Save to Favorites:** Save the recipe to the **Favorites Page**.
  - 💬 **Comment/Rate Section:** Submit feedback, which dynamically updates the page.
  - 🔙 **Back to Recipe Suggestions:** Redirect back to **Recipe Suggestions Page**.

---

## 5️⃣ **Favorites Page**
- **Objective:** Allow logged-in users to view and manage their saved recipes.
- **Navigation Options:**  
  - 🖼️ **Recipe Cards:** Click on any saved recipe → Redirect to **Recipe Details Page**.
  - ❌ **Remove from Favorites:** Update the favorites list dynamically.
  - 🔙 **Back to Recipe Suggestions:** Return to **Recipe Suggestions Page**.

---

## 6️⃣ **Profile Page**
- **Objective:** Display user information and allow account updates.
- **Navigation Options:**  
  - 🔄 **Edit Profile:** Update user information and refresh the page.
  - 📜 **View Recipe History:** Click on a rated recipe → Redirect to **Recipe Details Page**.
  - 🔙 **Back to Homepage:** Navigation link returns user to **Homepage**.
  - 🔓 **Logout:** Redirect to **Homepage**, clearing user session.

---

## 7️⃣ **Advanced Search & Filter Page**
- **Objective:** Provide advanced search and filter functionality.
- **Navigation Options:**  
  - 🔍 **Search Bar:** Input query → Display filtered recipe results on the same page.
  - 🔧 **Filter Options:** Apply filters (cuisine, difficulty, dietary preferences) → Update recipe list.
  - 🖼️ **Recipe Cards:** Click on a filtered recipe → Redirect to **Recipe Details Page**.
  - 🔙 **Back to Recipe Suggestions:** Return to **Recipe Suggestions Page**.

---

## 📚 **Navigation Bar (Global)**
The navigation bar is available across all pages, providing quick access to essential sections:
- 🏠 **Home:** Redirect to Homepage.
- ⭐ **Favorites:** Redirect to **Favorites Page** (if logged in).
- 📜 **Profile:** Redirect to **Profile Page** (if logged in).
- 🔍 **Search:** Accessible search bar for quick recipe queries.
- 🔓 **Logout:** Log out and return to the **Homepage**.

---

## 📋 **Navigation Summary Table**

| Page               | From                     | To                            | Action/Trigger                  |
|--------------------|--------------------------|------------------------------|----------------------------------|
| Homepage           | Any                      | Recipe Suggestions           | Enter ingredients               |
| Homepage           | Any                      | Login/Sign-Up                | Click Login/Sign-Up             |
| Login Page         | Homepage                 | Recipe Suggestions           | Successful login                |
| Recipe Suggestions | Homepage/Login           | Recipe Details               | Click on a recipe               |
| Recipe Details     | Recipe Suggestions       | Favorites                    | Save to favorites               |
| Favorites          | Any                      | Recipe Details               | Click on saved recipe           |
| Profile            | Login/Favorites/Homepage | Recipe History/Recipe Details| Click on history/rated recipe   |
| Search Page        | Any                      | Recipe Suggestions           | Apply search/filter             |
| Global Nav Bar     | All Pages                | Homepage/Profile/Favorites   | Click navigation links          |

```