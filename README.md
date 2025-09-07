🍹 Mojito – Cocktails Website

A modern and interactive cocktails website built using React, GSAP animations, and smooth scrolling with @studio-freight/react-lenis.
Explore a wide range of refreshing cocktails with smooth animations and a sleek, elegant design.

🚀 Live Demo

🔗 View Live

✨ Features

🍸 Dynamic Cocktail Showcase – Browse through premium cocktails.

🎥 Background Video Support – Engaging animated background hero section.

🎨 Smooth Animations – GSAP powered animations for a seamless experience.

🖱️ Smooth Scrolling – Powered by React Lenis.

📱 Fully Responsive – Works perfectly on mobile, tablet, and desktop.

⚡ Optimized Performance – Lightweight and fast loading.

🛠️ Tech Stack

Frontend: React, JSX, Tailwind CSS

Animations: GSAP, SplitText, ScrollTrigger

Smooth Scrolling: @studio-freight/react-lenis

Deployment: Vercel / Netlify

📂 Project Structure
mojito/
│
├── public/            # Static files (images, videos, icons)
│   ├── images/
│   └── videos/
│
├── src/
│   ├── components/    # Navbar, Hero, etc.
│   ├── sections/      # Structured sections like About, Services
│   ├── App.jsx        # Main App file
│   └── index.js       # Entry point
│
└── package.json

⚙️ Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/mojito.git


Navigate to the project folder:

cd mojito


Install dependencies:

npm install


Run the development server:

npm run dev


Build for production:

npm run build

🎥 FFmpeg Video Optimization (Optional)

To optimize your video for the background hero section:

ffmpeg -i input.mp4 -vf scale=960:-1 -movflags faststart -c:v libx264 -crf 20 -g 1 -pix_fmt yuv420p output.mp4

📧 Contact

For any inquiries or suggestions:
Your Name – krishnasharmau4@gmail.com

GitHub: github.com/fearDluffy
