# 🕸️ How Websites Work & Web Technologies - TryHackMe Notes

**Path:** Pre-Security  
**Status:** Completed  

---

## Rooms Covered
* How Websites Work
* DNS in Detail
* HTTP in Detail

---

##  Key Technical Concepts

### 1. DNS (Domain Name System)
DNS acts as the phonebook of the internet, converting human-readable domain names (e.g., `google.com`) into computer-readable IP addresses.

**The DNS Resolution Process:**
1. **DNS Request:** User requests a website.
2. **Recursive DNS Server:** Looks for the IP address in its cache.
3. **Root Name Server:** Directs the query to the correct TLD server.
4. **TLD (Top-Level Domain) Server:** (e.g., `.com`, `.org`) directs to the Authoritative server.
5. **Authoritative Name Server:** Provides the exact IP address.

### 2. HTTP (HyperText Transfer Protocol)
HTTP is the protocol used to transfer data web pages over the internet.

* **Key HTTP Methods:**
  * `GET`: Requests data from a server.
  * `POST`: Sends data to a server (e.g., login forms).
  * `PUT`: Updates existing data.
  * `DELETE`: Removes data.

* **Important Status Codes:**
  * `200 OK`: Request succeeded.
  * `301 Moved Permanently`: URL redirection.
  * `404 Not Found`: Server cannot find the requested page.
  * `500 Internal Server Error`: Generic server-side error.

### 3. Web Components
* **HTML:** The structural backbone of a webpage.
* **CSS:** Controls the styling and visual appearance.
* **JavaScript:** Adds interactivity and dynamic features to the site.

---

## 🛠️ Key Takeaway for Cybersecurity
Web penetration testing relies heavily on understanding HTTP requests and responses to detect vulnerabilities like Cross-Site Scripting (XSS) or SQL Injection.
