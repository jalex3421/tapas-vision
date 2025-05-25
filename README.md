# tapas-vision

This app uses **Firebase AI Studio** and computer vision to recognize real-world objects from images and turn them into **authentic Spanish cuisine recipes**.

It’s a creative prototype that merges image recognition with generative AI to provide cultural value through culinary suggestions — built in just one day!

---

## 🚀 Features

- 🖼️ **Object Recognition**  
  Upload or capture an image — the app identifies ingredients using a vision model.

- 🧠 **AI-Powered Recipe Generation**  
  Detected objects are passed to Firebase AI Studio to generate traditional Spanish recipes using those ingredients.

- 🇪🇸 **Cultural Focus**  
  The recipes reflect the richness of **Spanish gastronomy**, tailored to the detected ingredients.

- ☁️ **Firebase Integration**  
  Leveraged Firebase for inference, logic, and (optionally) deployment.

---

## 🧪 Example Workflow

1. 📷 User uploads a picture (e.g., tomato, garlic, bread).
2. 🧠 Vision model detects: `["tomato", "garlic", "bread"]`.
3. 📝 Prompt sent to Firebase AI Studio -> user obtain a list of potential recipes

4. LINK: https://studio--tapas-vision.us-central1.hosted.app/
