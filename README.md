# **websitebd**

A lightweight configuration and asset repository used for managing domain rules, extension permissions, default images, and search configurations for browser extensions or related web tools.

## **📁 Project Structure**

### **1. `domains.json`**

Contains the list of domains used by the extension or service.

* Add new domains here.
* Remove domains that should no longer be supported.
* The extension uses this file to clear or filter data when a matching domain is detected.

### **2. `extidallow.json`**

This file stores extension IDs that are allowed during installation.

* When the extension installs, it fetches this file.
* If the extension ID is listed, it is allowed to operate.

### **3. `search.json`**

Configuration file for search-based ads.

* Used by the extension for showing ads during Google search.
* Contains search keywords, ad mappings, or related metadata.

### **4. `offer-360x180.png`**

A default offer/alarm image.

* Used as a fallback image (`alarm default image`).
* Typically displayed in notifications, offers, or promotional UI modules.

---


## **🔧 Recent Update**

**Commit:** `ca35a67`
**Author:** @theprashant29
**Message:** *Update domains.json with new entries and removals*
**Date:** 2 days ago

---

## **🚀 Usage**

1. Update `domains.json` whenever new domains must be monitored or filtered.
2. Add or remove extension IDs in `extidallow.json` to manage access control.
3. Modify `search.json` for search-based ads configuration.
4. Replace `offer-360x180.png` if you want a new default alarm/offer image.

---

## **📄 License**

