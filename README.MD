# 🎬 Video Editor - VEED.io Clone  

A simple, browser-based **video/photo editor** inspired by **VEED.io**. This editor allows users to upload media, resize, reposition, and control visibility over a timeline.  

## 🚀 Live Demo  
🔗 [Video Editor](https://video-editor-alpha-one.vercel.app/)  

## 📸 Features  

✅ **Upload Videos & Images** – Add media to the canvas using the "Upload" button.  
✅ **Drag & Resize** – Move and scale media elements freely on the canvas.  
✅ **Adjust Dimensions** – Modify width & height via input fields in the **Elements Panel** (Right Side).  
✅ **Timeline Visibility** – Control start & end time of media appearance. Media will only be visible between these times when the play button is pressed.  

## 🎨 User Interface  

The layout includes:  
- **Left Sidebar**: Upload panel with **Videos, Audio, Image, Text, Animation, Effects, Fill, and Export** options.  
- **Center Canvas**: Displays the added video/photo with controls for resizing and dragging.  
- **Right Sidebar**: **Elements Panel** containing input fields for media adjustments.  
- **Bottom Timeline**: Displays a **play button** and time marker, allowing users to control media visibility over time.  

## 🛠️ Tech Stack  

- **Frontend:** Next.js, Tailwind CSS, Mantine UI, Vanilla CSS  
- **State Management:** Local state for handling media properties  
- **Interactions:** Custom drag-and-resize implementation  

## 📌 Installation  

```bash
# Clone the repository
git clone https://github.com/your-username/video-editor-clone.git
cd video-editor-clone

# Install dependencies
npm install

# Start the development server
npm run dev
