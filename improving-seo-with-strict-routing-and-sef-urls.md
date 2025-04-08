# Improving SEO with Strict Routing and SEF URLs

Search Engine Optimization (SEO) plays a key role in increasing the visibility of your Joomla site. Joomla 5 introduces enhanced support for Strict Routing and Search Engine Friendly (SEF) URLs that help improve how search engines interpret your site's structure.

## What are SEF URLs?

SEF URLs (Search Engine Friendly URLs) make Joomla site links more readable and meaningful to both users and search engines.

### Example:

- **Without SEF:**  
  `index.php?option=com_content&view=article&id=42`  
- **With SEF:**  
  `/my-article-title`

These cleaner URLs are easier to read, remember, and get ranked better by search engines.

## Enabling SEF URLs and Strict Routing in Joomla 5

1. Log in to your Joomla Administrator panel.
2. Navigate to **System > Global Configuration**.
3. Under the **Site** tab, set **Search Engine Friendly URLs** to **Yes**.
4. Also enable **Use URL Rewriting** (requires `.htaccess` or `web.config` file to be renamed/enabled).
5. Switch to the **Joomla SEF Settings** tab.
6. Set **Strict Routing** to **Yes**.
7. Save the configuration.

## Why Use SEF and Strict Routing?

- ✅ Cleaner, user-friendly URLs  
- ✅ Better SEO performance  
- ✅ Improved click-through rates from search engines  
- ✅ Helps search engines understand site structure more clearly

## Final Tips

- Ensure your web server supports URL rewriting (Apache, Nginx, etc.).
- Rename your `.htaccess.txt` file to `.htaccess` if using Apache.
- After enabling, check a few pages to ensure there are no 404 errors.

---

By enabling SEF URLs and Strict Routing, you're optimizing your Joomla 5 site for better visibility and user experience.
