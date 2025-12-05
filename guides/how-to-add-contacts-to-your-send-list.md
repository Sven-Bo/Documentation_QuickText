---
description: >-
  Quickly import contacts from your Contact Manager into the Send List for bulk
  messaging.
---

# How to add contacts to your send list

### Overview

This feature lets you:

* Select one or more contact lists to import
* Optionally set a message template for all imported contacts
* Use placeholders like `{{first_name}}` for personalization
* Handle duplicates automatically

<div align="left"><figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure></div>

***

### How It Works

1. **Select Contact Lists** Check the lists you want to import. Each list shows the number of contacts it contains. Use "Select All" or "Deselect All" for quick selection.\
   ![](<../.gitbook/assets/image (1).png>)
2. **Add a Message (Optional)** Type a message template that will be applied to all imported contacts. Leave empty to import phone numbers only.\
   ![](<../.gitbook/assets/image (2).png>)
3. **Set Options**
   * **Remove duplicates** – If a contact appears in multiple selected lists, it will only be imported once
   * **Clear existing entries** – Removes all current entries from the Send List before importing\
     ![](<../.gitbook/assets/image (4).png>)
4. **Click "Add to Send List"** Your contacts are imported and ready to send.

***

### Using Placeholders

You can personalize your message using placeholders based on your Contacts table columns:

```
Hi {{first_name}}!Special offer for {{company}} customers.
```

Available placeholders are shown below the message box. Hover over the label to see all available placeholders if you have many columns.\
![](<../.gitbook/assets/image (5).png>)

***

### Things to Know

**No Lists?** If no lists appear, make sure your contacts in the Contact Manager have values in the "Lists" column.

**Contacts Without a List** Contacts that have no list assigned will appear under "(No List)" and can still be imported.

**Live Preview** The status at the bottom shows how many contacts will be imported. If "Remove duplicates" is checked, it also shows the unique count.

**Appending vs. Replacing**

* With "Clear existing entries" checked: Your Send List is cleared first, then contacts are imported
* With it unchecked: Contacts are added below your existing entries

***

### Tips

* Organize your contacts into lists (e.g., "VIP", "Newsletter", "Customers") for easy bulk selection
* A contact can belong to multiple lists (comma-separated in the Lists column)
* Use the message template to save time when sending the same message to many contacts
