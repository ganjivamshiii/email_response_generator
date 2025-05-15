Great! Here's a professional and clear **README.md template** tailored to your **Chrome Extension + Java Gemini API email generator project**:

---

````markdown
# 📧 AI Email Writer Assistant

A Chrome Extension that helps you generate professional email replies using the Gemini Open API. Built with a Java Spring Boot backend and integrated seamlessly with Gmail.

---

## 🚀 Features

- ✨ "AI Reply" button added directly to Gmail's compose toolbar.
- 🧠 Uses Gemini API to generate smart, professional responses.
- 🔄 Observes Gmail UI changes and injects the button dynamically.
- ⚙️ Lightweight, fast, and easy to set up locally.

---

## 🧰 Tech Stack

- **Frontend**: JavaScript (Chrome Extension)
- **Backend**: Java (Spring Boot)
- **AI API**: Google Gemini (via API Key)

---

## 📂 Project Structure

```plaintext
├── backend/
│   ├── EmailRequest.java
│   ├── EmailGenerateService.java
│   └── Emailgeneratorcontroller.java
├── extension/
│   ├── content.js
│   ├── manifest.json
│   └── icons/ (optional icons)
````

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/email-writer-assistant.git
cd email-writer-assistant
```

### 2. Backend Setup (Spring Boot)

* Open the project in your IDE (IntelliJ, Eclipse, etc.)
* Add your **Gemini API key** in the service class (`EmailGenerateService.java`)
* Run the Spring Boot application (typically on `http://localhost:8080`)

### 3. Chrome Extension Setup

1. Open **Google Chrome**.
2. Go to `chrome://extensions/`
3. Enable **Developer Mode** (top right).
4. Click **"Load unpacked"**.
5. Select the `extension/` folder.
6. Open **Gmail**, click **Compose**, and see the **"AI Reply"** button!

---

## 🔐 Environment Variables (if needed)

If using an `.env` or `application.properties`, you may define:

```properties
gemini.api.key=YOUR_API_KEY
```

---

## 📸 Screenshots

>![alt text](<Screenshot 2025-05-15 125031.png>)
>![alt text](image.png)
---

## 🧪 Test the API Manually (Optional)

You can use Postman or curl:

```bash
curl -X POST http://localhost:8080/api/email/generate \
-H "Content-Type: application/json" \
-d '{"emailContent":"Hi, can we reschedule our meeting?", "tone":"professional"}'
```

---

## 🙋‍♂️ Author

* Name: G.vamshi
* GitHub: [@ganjivamshiii](https://github.com/ganjivamshiii)

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).

---

## 💡 Future Improvements

* Add UI customization for tone (friendly, formal, etc.)
* Support multiple email platforms
* Deploy backend using Render/Railway for public access

```

