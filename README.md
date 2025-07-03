# Animation Estate

A stunning real estate landing page featuring interactive SVG animations and smooth scroll effects. Experience the future of property showcasing with immersive animations that bring buildings to life.


## 🏢 Features

- **Interactive Building Animations**: Dynamic city skyline that deconstructs as you scroll
- **Smooth Scroll Effects**: Powered by GSAP ScrollTrigger for cinematic transitions
- **Real Estate Focus**: Designed specifically for property and real estate showcasing
- **Responsive Design**: Optimized for all devices and screen sizes
- **Modern UI**: Clean, professional design with dark theme
- **Performance Optimized**: Lightweight and fast-loading animations

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Animation**: GSAP (GreenSock Animation Platform) with ScrollTrigger
- **Graphics**: Custom SVG illustrations and animations
- **Fonts**: Google Fonts (Poppins), CDN Fonts (Allenia)

## 📁 Project Structure

```
animation-estate/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with responsive design
├── app.js              # Animation logic and scroll triggers
├── city.svg            # Custom SVG city/building illustration
└── img/                # Image assets
    ├── 1.png - 10.png  # Real estate related images
```

## 🎨 Key Animation Features

### Building Deconstruction Animation
- **Stage 1**: City skyline scales up while overall opacity fades
- **Stage 2**: Building components (top, walls) move and fade in different directions
- **Stage 3**: Interior elements disappear to reveal the final scene

### Scroll-Triggered Interactions
- Smooth pinning effect during animation sequence
- Coordinated element movements with precise timing
- Seamless transitions between animation states

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/dev0jha/Animation_Estate.git
   cd Animation_Estate
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your preferred browser
   # Or use a local server for development
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Customize for your real estate needs**
   - Replace `city.svg` with your property illustrations
   - Update content in `index.html` with your property details
   - Modify colors and branding in `style.css`
   - Adjust animation timings in `app.js`

## 🏠 Real Estate Integration

Perfect for:
- **Property Developers**: Showcase new developments with interactive animations
- **Real Estate Agencies**: Create engaging property presentations
- **Architects**: Display building designs with animated reveals
- **Property Marketing**: Capture attention with immersive experiences

## 🎯 Animation Breakdown

The building deconstruction animation follows a carefully choreographed sequence:

1. **Initial State**: Full city view with all elements visible
2. **Scale & Fade**: City scales up (1.5x) while full city opacity reduces to 0
3. **Deconstruction**: Building components move in coordinated directions:
   - Top elements move up and fade out
   - Side walls move left and fade out
   - Front walls move right/down and fade out
4. **Interior Reveal**: Interior walls fade out to complete the sequence

## 📱 Browser Support

- Chrome (recommended for best performance)
- Firefox
- Safari
- Edge

## ⚡ Performance Notes

- Optimized for 60fps animations
- Hardware acceleration enabled for smooth transitions
- Efficient SVG rendering with `preserveAspectRatio` optimization
- Minimal DOM manipulation for better performance

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/NewAnimation`)
3. Commit your changes (`git commit -m 'Add new building animation'`)
4. Push to the branch (`git push origin feature/NewAnimation`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Dev** - [@dev0jha](https://github.com/dev0jha)

Project Link: [https://github.com/dev0jha/Animation_Estate](https://github.com/dev0jha/Animation_Estate)

---

⭐ If you found this project helpful for your real estate projects, please give it a star!

## 🔧 Development Notes

- The animation requires `city.svg` to be properly structured with the following IDs:
  - `#full_city` - Complete city view
  - `#building_top` - Building top section
  - `#wall_side`, `#wall_front` - Exterior walls
  - `#interior_wall_*` - Interior wall elements
- GSAP libraries are loaded via CDN for optimal performance
- All animations use `scrub: true` for smooth scroll synchronization
- Responsive breakpoints at 1023px and 767px

## 🎭 Demo

Check out the live demo: [Animation Estate](https://dev0jha.github.io/Animation_Estate)

*Built with ❤️ for the real estate industry by Dev*
