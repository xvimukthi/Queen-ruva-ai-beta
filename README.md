<p align="center">
  <img src="https://files.catbox.moe/hj0hur.webp" width="450px">
</p>

<h1 align="center">
  <a href="#">
    <span id="typewriter"></span>
  </a>
</h1>

## 👤 <span id="blinking-owner">Owner: Iconic Tech</span>

---

## 🔥 **Queen Ruva Beta Tip**  
🚀 **Upload the file and deploy where you want.**  
❓ **If you don't know how, follow us and watch the videos below!**  

---

## 📥 **Download the Bot**  

[![⬇️ Download File](https://img.shields.io/badge/⬇️%20Download%20File-green?style=for-the-badge)](YOUR_DIRECT_DOWNLOAD_LINK_HERE)  

---

## 🎖 **Special Thanks**  
🔥 **Agung** – API and hosting support  
👑 **Iconic Tech** – Developer & Maintainer of Queen Ruva AI Beta  

---

## 📞 **Connect & Follow Us**  

🔹 **Telegram:** [![Telegram](https://img.shields.io/badge/Telegram-Join%20Now-blue?style=for-the-badge)](https://t.me/kinetech06)  

🔹 **WhatsApp Group:**  
<a href="https://chat.whatsapp.com/LyFPHDvc5vMCglUFjv7Rlp">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="18px">
</a>  

🔹 **WhatsApp Channel:**  
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp%20Channel-Join%20Now-green?style=for-the-badge)](https://whatsapp.com/channel/0029ValX2Js9RZAVtDgMYj0r)  

---

## 🚀 **Developed by ICONICS-TECH**  

---

### **JavaScript for Typewriter & Blinking Effect** (For Web Pages)
GitHub README **doesn't support JavaScript**, but if you use it on a webpage, add this script:

```html
<script>
  const text = "Queen Ruva AI Beta development by ICONICS-TECH";
  let i = 0;
  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeWriter, 150);
    }
  }
  window.onload = typeWriter;

  function blink() {
    let element = document.getElementById("blinking-owner");
    element.style.opacity = (element.style.opacity == 0 ? 1 : 0);
  }
  setInterval(blink, 500);
</script>
