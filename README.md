# Quote.Web

A modern, dark, minimal website for daily inspiration. Browse random quotes with a premium UI, learn more about the project, and find contact links.

## Features

- **Immersive Reader** - Distraction-free interface with expressive typography
- **Command Palette (`Ctrl+K`)** - Instant search across the entire quote library
- **Deep Void Theme** - A premium dark aesthetic with paralax starfield background
- **Contextual Drawers** - Clean "About" and "Contact" sections that slide in
- **Mobile Optimized** - Adaptive layout with native safe-area support for all devices
- **Performance First** - Intelligent resource scaling for 60fps animations on mobile
- **One-Click Actions** - Copy, Share, and Fetch new quotes instantly

## Sections

### Home

Your daily quote generator with powerful search capabilities. View random inspirational quotes, search by keyword, filter by author, or browse through matching results.

### About

Learn about Quote.Web, our mission, features, and the technologies we use.

### Contact

Connect with us through email or GitHub links.

## Getting Started

### Online

Visit the live website at: [Quote.Web](https://chronos778.github.io/quote.web)

### Local Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/Chronos778/quote.web.git
   cd quote.web
   ```

2. Open `index.html` in your web browser

3. Start exploring quotes!

## How It Works

Quote.Web fetches quotes from the [Quotes API](https://quotes-api-ruddy.vercel.app) using a CORS proxy:

- **Random quotes** are fetched from `/quotes/random` endpoint
- **Search & filter** queries the full `/quotes` endpoint and filters client-side
- Results display instantly with smooth animations and a beautiful minimal interface

## Technologies

- **HTML5** - Semantic structure
- **CSS3** - Responsive, dark-theme design with smooth animations and tilt
- **Vanilla JavaScript** - Pure JavaScript, no frameworks
- **Quotes API** - 10,000+ curated quotes

## Project Structure

```text
quote.web/
├── index.html       # Main website with all sections
├── README.md        # Project documentation
├── LICENSE          # MIT License
└── .gitignore       # Git ignore file
```

## Features in Detail

### Quote Display

- Automatic quote loading on page visit
- Smooth fade-in animations
- Clean typography and spacing

### Search & Filter

- Search quotes by keyword (searches quote text)
- Filter quotes by author name
- Real-time filtering across entire database
- Result counter showing number of matches
- Press Enter to search quickly
- Clear button to reset filters

### Navigation

- Sticky navigation bar
- Easy section switching
- Active state indicators
- Mobile-friendly menu

### Contact Information

- Contact section with email and GitHub links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Future Enhancements

- Quote filtering by category/tags
- User favorites/bookmarks
- Share to social media
- Dark mode theme
- Quote of the day email subscription
- Advanced search with multiple filters

## Contributing

Contributions are welcome! Feel free to:

- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## License

MIT License - See LICENSE file for details

## Author

Created by [Chronos778](https://github.com/Chronos778)

---

### Built with ❤️ for daily inspiration
