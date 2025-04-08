# Managing Mail Template Layouts in Joomla 5

Joomla 5 allows you to customize the layout and content of system-generated emails using the Mail Templates feature. This helps align automated communications with your site's branding and tone.

## Accessing Mail Templates

1. Log in to your Joomla Administrator panel.
2. Go to **System** > **Mail Templates** under the **Templates** section.

## Customizing a Template

1. Choose the template you wish to modify (e.g., "User - Registration Email").
2. Click on it to open the editor.
3. Modify the **Subject** and **Body** fields as required.
   - Use available placeholders like `{name}`, `{sitename}`, `{link}`, etc.
4. Use the editor toolbar to style text, insert links, or use code view.

## Template Layout Options

Joomla supports multiple layouts for email templates:
- **HTML Layout:** Rich formatting using HTML and inline styles.
- **Plain Text Layout:** A simpler version for plain email clients.

You can toggle between them using the **Tabs** at the top of the editor.

## Adding New Layouts

You can override existing templates via your template's `/html/layouts/com_mailto` folder if you require advanced customization.

## Tips

✅ Always test email formatting before going live  
✅ Keep language neutral and professional  
✅ Maintain responsive layout for mobile-friendly emails

## Benefits

- Consistent communication style  
- Better branding across automated messages  
- Improved user experience

---

By managing your mail templates, you ensure all site-generated emails align with your Joomla 5 site's design and communication standards.
