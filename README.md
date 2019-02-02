# Gunbbang Pocket

Gunbbang Pocket is a chrome extension for intranet environment. It aims at clipping all important page information and display them into one page.

## 📜Background

---

In ROKAF intranet environment, it is very hard to keep everything on track, due to the fact that **it lacks proper tools** and **no one actually tries to contribute to convenience** of soldiers on intranet. 

To my knowledge, the only few things on intranet with which you can manage what you keep on track of what event is going to be held or what you should keep on watching is taking notes on your own memo or sticky notes. 

To streamline and game up the experience of both office working soldiers and officers, Gunbbang Pocket provides **web clipping, tagging, remainder, and displaying the data** into one page like Evernote, Notion, and many other apps out there. 

## How?

---
Chrome extension APIs

- [storage.sync](https://developer.chrome.com/extensions/storage)
  - send current tab's metadata (i.e., URL, tags, date, and so on) to synchronized storage, and pull those from it to list them

- [Cross Origin XMLHttpRequest](https://developer.chrome.com/extensions/xhr)
  - Pull clipped page's data from storage

- [Active Tabs](https://developer.chrome.com/extensions/activeTab)
  - Enables extension to access to the data of active tab

- [chrome.sessions](https://developer.chrome.com/extensions/sessions)
  - If needed, some intranet sites needs session cookies, so it might be needed.

## Requirements

---

- [ ]  Save current tab to localstorage when users click the icon
- [ ]  Tag the saved page with user input
- [ ]  Turn on remainder/notification for users
- [ ]  List all clipped tabs/pages into one page

## 💯Tests

---

- [ ]  Is it showing necessary data to users?
- [ ]  Can users manipulate their own data as they wish?
- [ ]  Extendible to other projects and etc.

## Measuring Success

---

1. User base (>100)
2. Contributors & Maintainers (>3)
3. Able to see people actually using it in daliy basis