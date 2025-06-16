# Parralex-design
A Parallax design for shaping my skills and also some parts which have professional looks. I think It was an amazing practice set?
# 👋 Welcome to Parralex Design

> Made with ❤️ by [Abbasi Codes Hub](https://github.com/Abbasi-codes-hub)

---

## 🔥 Live Typing Effect Preview (HTML + CSS)

```html
<h1 class="typing">Welcome to Parralex World</h1>

<style>
.typing {
  width: 22ch;
  animation: typing 3s steps(22), blink .5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid orange;
  font-family: monospace;
  font-size: 1.5rem;
  color: #fca311;
}

@keyframes typing {
  from { width: 0 }
  to { width: 22ch }
}

@keyframes blink {
  50% { border-color: transparent }
}
</style>
